# Function: <code>ioapic_write_entry</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void ioapic_write_entry(int apic, int pin, struct IO_APIC_route_entry e)
```

```json
{
  "name": "ioapic_write_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579196816,
      "name": "ioapic_write_entry",
      "external": false,
      "loc": "arch/x86/kernel/apic/io_apic.c:342",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:mask_ioapic_entries",
        "arch/x86/kernel/apic/io_apic.c:restore_ioapic_entries",
        "arch/x86/kernel/apic/io_apic.c:native_disable_io_apic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579196816,
      "name": "ioapic_write_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
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
void ioapic_write_entry(int apic, int pin, struct IO_APIC_route_entry e)
```

```json
{
  "name": "ioapic_write_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579197408,
      "name": "ioapic_write_entry",
      "external": false,
      "loc": "arch/x86/kernel/apic/io_apic.c:342",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:native_disable_io_apic",
        "arch/x86/kernel/apic/io_apic.c:restore_ioapic_entries",
        "arch/x86/kernel/apic/io_apic.c:mask_ioapic_entries",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579197408,
      "name": "ioapic_write_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
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
void ioapic_write_entry(int apic, int pin, struct IO_APIC_route_entry e)
```

```json
{
  "name": "ioapic_write_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579209104,
      "name": "ioapic_write_entry",
      "external": false,
      "loc": "arch/x86/kernel/apic/io_apic.c:341",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:native_disable_io_apic",
        "arch/x86/kernel/apic/io_apic.c:restore_ioapic_entries",
        "arch/x86/kernel/apic/io_apic.c:mask_ioapic_entries",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579209104,
      "name": "ioapic_write_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
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
void ioapic_write_entry(int apic, int pin, struct IO_APIC_route_entry e)
```

```json
{
  "name": "ioapic_write_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579206624,
      "name": "ioapic_write_entry",
      "external": false,
      "loc": "arch/x86/kernel/apic/io_apic.c:341",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:native_disable_io_apic",
        "arch/x86/kernel/apic/io_apic.c:restore_ioapic_entries",
        "arch/x86/kernel/apic/io_apic.c:mask_ioapic_entries",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579206624,
      "name": "ioapic_write_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
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
void ioapic_write_entry(int apic, int pin, struct IO_APIC_route_entry e)
```

```json
{
  "name": "ioapic_write_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579224304,
      "name": "ioapic_write_entry",
      "external": false,
      "loc": "arch/x86/kernel/apic/io_apic.c:342",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:native_disable_io_apic",
        "arch/x86/kernel/apic/io_apic.c:restore_ioapic_entries",
        "arch/x86/kernel/apic/io_apic.c:mask_ioapic_entries",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579224304,
      "name": "ioapic_write_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
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
void ioapic_write_entry(int apic, int pin, struct IO_APIC_route_entry e)
```

```json
{
  "name": "ioapic_write_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579236704,
      "name": "ioapic_write_entry",
      "external": false,
      "loc": "arch/x86/kernel/apic/io_apic.c:343",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:native_restore_boot_irq_mode",
        "arch/x86/kernel/apic/io_apic.c:mask_ioapic_entries",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579236704,
      "name": "ioapic_write_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
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
void ioapic_write_entry(int apic, int pin, struct IO_APIC_route_entry e)
```

```json
{
  "name": "ioapic_write_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579260368,
      "name": "ioapic_write_entry",
      "external": false,
      "loc": "arch/x86/kernel/apic/io_apic.c:343",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:native_restore_boot_irq_mode",
        "arch/x86/kernel/apic/io_apic.c:mask_ioapic_entries",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579260368,
      "name": "ioapic_write_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
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
void ioapic_write_entry(int apic, int pin, struct IO_APIC_route_entry e)
```

```json
{
  "name": "ioapic_write_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579274480,
      "name": "ioapic_write_entry",
      "external": false,
      "loc": "arch/x86/kernel/apic/io_apic.c:344",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:native_restore_boot_irq_mode",
        "arch/x86/kernel/apic/io_apic.c:restore_ioapic_entries",
        "arch/x86/kernel/apic/io_apic.c:mask_ioapic_entries",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579274480,
      "name": "ioapic_write_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
void ioapic_write_entry(int apic, int pin, struct IO_APIC_route_entry e)
```

```json
{
  "name": "ioapic_write_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579276912,
      "name": "ioapic_write_entry",
      "external": false,
      "loc": "arch/x86/kernel/apic/io_apic.c:344",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:native_restore_boot_irq_mode",
        "arch/x86/kernel/apic/io_apic.c:restore_ioapic_entries",
        "arch/x86/kernel/apic/io_apic.c:mask_ioapic_entries",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579276912,
      "name": "ioapic_write_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
void ioapic_write_entry(int apic, int pin, struct IO_APIC_route_entry e)
```

```json
{
  "name": "ioapic_write_entry",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579312111,
      "name": "ioapic_write_entry",
      "external": false,
      "loc": "arch/x86/kernel/apic/io_apic.c:331",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:native_restore_boot_irq_mode",
        "arch/x86/kernel/apic/io_apic.c:restore_ioapic_entries",
        "arch/x86/kernel/apic/io_apic.c:mask_ioapic_entries",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic",
        "arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579305696,
      "name": "ioapic_write_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
void ioapic_write_entry(int apic, int pin, struct IO_APIC_route_entry e)
```

```json
{
  "name": "ioapic_write_entry",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579317424,
      "name": "ioapic_write_entry",
      "external": false,
      "loc": "arch/x86/kernel/apic/io_apic.c:323",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:native_restore_boot_irq_mode",
        "arch/x86/kernel/apic/io_apic.c:restore_ioapic_entries",
        "arch/x86/kernel/apic/io_apic.c:mask_ioapic_entries",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic",
        "arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579310976,
      "name": "ioapic_write_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
void ioapic_write_entry(int apic, int pin, struct IO_APIC_route_entry e)
```

```json
{
  "name": "ioapic_write_entry",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579320192,
      "name": "ioapic_write_entry",
      "external": false,
      "loc": "arch/x86/kernel/apic/io_apic.c:323",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:native_restore_boot_irq_mode",
        "arch/x86/kernel/apic/io_apic.c:restore_ioapic_entries",
        "arch/x86/kernel/apic/io_apic.c:mask_ioapic_entries",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic",
        "arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579313808,
      "name": "ioapic_write_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
void ioapic_write_entry(int apic, int pin, struct IO_APIC_route_entry e)
```

```json
{
  "name": "ioapic_write_entry",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579375520,
      "name": "ioapic_write_entry",
      "external": false,
      "loc": "arch/x86/kernel/apic/io_apic.c:323",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:native_restore_boot_irq_mode",
        "arch/x86/kernel/apic/io_apic.c:restore_ioapic_entries",
        "arch/x86/kernel/apic/io_apic.c:mask_ioapic_entries",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic",
        "arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579362768,
      "name": "ioapic_write_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
void ioapic_write_entry(int apic, int pin, struct IO_APIC_route_entry e)
```

```json
{
  "name": "ioapic_write_entry",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579439768,
      "name": "ioapic_write_entry",
      "external": false,
      "loc": "arch/x86/kernel/apic/io_apic.c:324",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:native_restore_boot_irq_mode",
        "arch/x86/kernel/apic/io_apic.c:restore_ioapic_entries",
        "arch/x86/kernel/apic/io_apic.c:mask_ioapic_entries",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic",
        "arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579425952,
      "name": "ioapic_write_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
  "name": "ioapic_write_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627665653,
      "name": "ioapic_write_entry",
      "external": false,
      "loc": "arch/x86/kernel/apic/io_apic.c:324",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic",
        "arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic",
        "arch/x86/kernel/apic/io_apic.c:native_restore_boot_irq_mode",
        "arch/x86/kernel/apic/io_apic.c:restore_ioapic_entries",
        "arch/x86/kernel/apic/io_apic.c:mask_ioapic_entries",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin"
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
  "name": "ioapic_write_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619422613,
      "name": "ioapic_write_entry",
      "external": false,
      "loc": "arch/x86/kernel/apic/io_apic.c:325",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic",
        "arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic",
        "arch/x86/kernel/apic/io_apic.c:native_restore_boot_irq_mode",
        "arch/x86/kernel/apic/io_apic.c:restore_ioapic_entries",
        "arch/x86/kernel/apic/io_apic.c:mask_ioapic_entries",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin"
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
  "name": "ioapic_write_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071621718668,
      "name": "ioapic_write_entry",
      "external": false,
      "loc": "arch/x86/kernel/apic/io_apic.c:325",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic",
        "arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic",
        "arch/x86/kernel/apic/io_apic.c:native_restore_boot_irq_mode",
        "arch/x86/kernel/apic/io_apic.c:restore_ioapic_entries",
        "arch/x86/kernel/apic/io_apic.c:mask_ioapic_entries",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin"
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
void ioapic_write_entry(int apic, int pin, struct IO_APIC_route_entry e)
```

```json
{
  "name": "ioapic_write_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579275616,
      "name": "ioapic_write_entry",
      "external": false,
      "loc": "arch/x86/kernel/apic/io_apic.c:344",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:native_restore_boot_irq_mode",
        "arch/x86/kernel/apic/io_apic.c:restore_ioapic_entries",
        "arch/x86/kernel/apic/io_apic.c:mask_ioapic_entries",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579275616,
      "name": "ioapic_write_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
void ioapic_write_entry(int apic, int pin, struct IO_APIC_route_entry e)
```

```json
{
  "name": "ioapic_write_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579210944,
      "name": "ioapic_write_entry",
      "external": false,
      "loc": "arch/x86/kernel/apic/io_apic.c:344",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:native_restore_boot_irq_mode",
        "arch/x86/kernel/apic/io_apic.c:restore_ioapic_entries",
        "arch/x86/kernel/apic/io_apic.c:mask_ioapic_entries",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579210944,
      "name": "ioapic_write_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
void ioapic_write_entry(int apic, int pin, struct IO_APIC_route_entry e)
```

```json
{
  "name": "ioapic_write_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579276816,
      "name": "ioapic_write_entry",
      "external": false,
      "loc": "arch/x86/kernel/apic/io_apic.c:344",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:native_restore_boot_irq_mode",
        "arch/x86/kernel/apic/io_apic.c:restore_ioapic_entries",
        "arch/x86/kernel/apic/io_apic.c:mask_ioapic_entries",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579276816,
      "name": "ioapic_write_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
void ioapic_write_entry(int apic, int pin, struct IO_APIC_route_entry e)
```

```json
{
  "name": "ioapic_write_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579282704,
      "name": "ioapic_write_entry",
      "external": false,
      "loc": "arch/x86/kernel/apic/io_apic.c:344",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:native_restore_boot_irq_mode",
        "arch/x86/kernel/apic/io_apic.c:restore_ioapic_entries",
        "arch/x86/kernel/apic/io_apic.c:mask_ioapic_entries",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579282704,
      "name": "ioapic_write_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void ioapic_write_entry(int apic, int pin, struct IO_APIC_route_entry e)
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
void ioapic_write_entry(int apic, int pin, struct IO_APIC_route_entry e)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void ioapic_write_entry(int apic, int pin, struct IO_APIC_route_entry e)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void ioapic_write_entry(int apic, int pin, struct IO_APIC_route_entry e)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void ioapic_write_entry(int apic, int pin, struct IO_APIC_route_entry e)
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
