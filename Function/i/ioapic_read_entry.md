# Function: <code>ioapic_read_entry</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct IO_APIC_route_entry ioapic_read_entry(int apic, int pin)
```

```json
{
  "name": "ioapic_read_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579196736,
      "name": "ioapic_read_entry",
      "external": false,
      "loc": "arch/x86/kernel/apic/io_apic.c:315",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:save_ioapic_entries",
        "arch/x86/kernel/apic/io_apic.c:io_apic_print_entries",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:enable_IO_APIC"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579196736,
      "name": "ioapic_read_entry",
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
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct IO_APIC_route_entry ioapic_read_entry(int apic, int pin)
```

```json
{
  "name": "ioapic_read_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579197328,
      "name": "ioapic_read_entry",
      "external": false,
      "loc": "arch/x86/kernel/apic/io_apic.c:315",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:enable_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:io_apic_print_entries",
        "arch/x86/kernel/apic/io_apic.c:save_ioapic_entries",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579197328,
      "name": "ioapic_read_entry",
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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct IO_APIC_route_entry ioapic_read_entry(int apic, int pin)
```

```json
{
  "name": "ioapic_read_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579209024,
      "name": "ioapic_read_entry",
      "external": false,
      "loc": "arch/x86/kernel/apic/io_apic.c:314",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:enable_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:io_apic_print_entries",
        "arch/x86/kernel/apic/io_apic.c:save_ioapic_entries",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579209024,
      "name": "ioapic_read_entry",
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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct IO_APIC_route_entry ioapic_read_entry(int apic, int pin)
```

```json
{
  "name": "ioapic_read_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579206544,
      "name": "ioapic_read_entry",
      "external": false,
      "loc": "arch/x86/kernel/apic/io_apic.c:314",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:enable_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:io_apic_print_entries",
        "arch/x86/kernel/apic/io_apic.c:save_ioapic_entries",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579206544,
      "name": "ioapic_read_entry",
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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct IO_APIC_route_entry ioapic_read_entry(int apic, int pin)
```

```json
{
  "name": "ioapic_read_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579224224,
      "name": "ioapic_read_entry",
      "external": false,
      "loc": "arch/x86/kernel/apic/io_apic.c:315",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:enable_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:io_apic_print_entries",
        "arch/x86/kernel/apic/io_apic.c:save_ioapic_entries",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579224224,
      "name": "ioapic_read_entry",
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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct IO_APIC_route_entry ioapic_read_entry(int apic, int pin)
```

```json
{
  "name": "ioapic_read_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579236624,
      "name": "ioapic_read_entry",
      "external": false,
      "loc": "arch/x86/kernel/apic/io_apic.c:316",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:enable_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:io_apic_print_entries",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579236624,
      "name": "ioapic_read_entry",
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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct IO_APIC_route_entry ioapic_read_entry(int apic, int pin)
```

```json
{
  "name": "ioapic_read_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579260288,
      "name": "ioapic_read_entry",
      "external": false,
      "loc": "arch/x86/kernel/apic/io_apic.c:316",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:enable_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:io_apic_print_entries",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579260288,
      "name": "ioapic_read_entry",
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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct IO_APIC_route_entry ioapic_read_entry(int apic, int pin)
```

```json
{
  "name": "ioapic_read_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579274400,
      "name": "ioapic_read_entry",
      "external": false,
      "loc": "arch/x86/kernel/apic/io_apic.c:317",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:enable_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:io_apic_print_entries",
        "arch/x86/kernel/apic/io_apic.c:save_ioapic_entries",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579274400,
      "name": "ioapic_read_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
struct IO_APIC_route_entry ioapic_read_entry(int apic, int pin)
```

```json
{
  "name": "ioapic_read_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579276832,
      "name": "ioapic_read_entry",
      "external": false,
      "loc": "arch/x86/kernel/apic/io_apic.c:317",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:enable_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:io_apic_print_entries",
        "arch/x86/kernel/apic/io_apic.c:save_ioapic_entries",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579276832,
      "name": "ioapic_read_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
struct IO_APIC_route_entry ioapic_read_entry(int apic, int pin)
```

```json
{
  "name": "ioapic_read_entry",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579308687,
      "name": "ioapic_read_entry",
      "external": false,
      "loc": "arch/x86/kernel/apic/io_apic.c:304",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:save_ioapic_entries",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic",
        "arch/x86/kernel/apic/io_apic.c:enable_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:io_apic_print_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579305504,
      "name": "ioapic_read_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
struct IO_APIC_route_entry ioapic_read_entry(int apic, int pin)
```

```json
{
  "name": "ioapic_read_entry",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579313823,
      "name": "ioapic_read_entry",
      "external": false,
      "loc": "arch/x86/kernel/apic/io_apic.c:299",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:save_ioapic_entries",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic",
        "arch/x86/kernel/apic/io_apic.c:enable_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:io_apic_print_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579310784,
      "name": "ioapic_read_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
struct IO_APIC_route_entry ioapic_read_entry(int apic, int pin)
```

```json
{
  "name": "ioapic_read_entry",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579316591,
      "name": "ioapic_read_entry",
      "external": false,
      "loc": "arch/x86/kernel/apic/io_apic.c:299",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:save_ioapic_entries",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic",
        "arch/x86/kernel/apic/io_apic.c:enable_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:io_apic_print_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579313616,
      "name": "ioapic_read_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
struct IO_APIC_route_entry ioapic_read_entry(int apic, int pin)
```

```json
{
  "name": "ioapic_read_entry",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579366593,
      "name": "ioapic_read_entry",
      "external": false,
      "loc": "arch/x86/kernel/apic/io_apic.c:299",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:save_ioapic_entries",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic",
        "arch/x86/kernel/apic/io_apic.c:enable_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:io_apic_print_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579362480,
      "name": "ioapic_read_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
struct IO_APIC_route_entry ioapic_read_entry(int apic, int pin)
```

```json
{
  "name": "ioapic_read_entry",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579430946,
      "name": "ioapic_read_entry",
      "external": false,
      "loc": "arch/x86/kernel/apic/io_apic.c:300",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:save_ioapic_entries",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic",
        "arch/x86/kernel/apic/io_apic.c:enable_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:io_apic_print_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579425648,
      "name": "ioapic_read_entry",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ioapic_read_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627665528,
      "name": "ioapic_read_entry",
      "external": false,
      "loc": "arch/x86/kernel/apic/io_apic.c:300",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic",
        "arch/x86/kernel/apic/io_apic.c:enable_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:io_apic_print_entries",
        "arch/x86/kernel/apic/io_apic.c:save_ioapic_entries",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin",
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
  "name": "ioapic_read_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619422488,
      "name": "ioapic_read_entry",
      "external": false,
      "loc": "arch/x86/kernel/apic/io_apic.c:301",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic",
        "arch/x86/kernel/apic/io_apic.c:enable_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:io_apic_print_entries",
        "arch/x86/kernel/apic/io_apic.c:save_ioapic_entries",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin",
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
  "name": "ioapic_read_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071621718520,
      "name": "ioapic_read_entry",
      "external": false,
      "loc": "arch/x86/kernel/apic/io_apic.c:301",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic",
        "arch/x86/kernel/apic/io_apic.c:enable_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:io_apic_print_entries",
        "arch/x86/kernel/apic/io_apic.c:save_ioapic_entries",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin",
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
struct IO_APIC_route_entry ioapic_read_entry(int apic, int pin)
```

```json
{
  "name": "ioapic_read_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579275536,
      "name": "ioapic_read_entry",
      "external": false,
      "loc": "arch/x86/kernel/apic/io_apic.c:317",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:enable_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:io_apic_print_entries",
        "arch/x86/kernel/apic/io_apic.c:save_ioapic_entries",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579275536,
      "name": "ioapic_read_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
struct IO_APIC_route_entry ioapic_read_entry(int apic, int pin)
```

```json
{
  "name": "ioapic_read_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579210864,
      "name": "ioapic_read_entry",
      "external": false,
      "loc": "arch/x86/kernel/apic/io_apic.c:317",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:enable_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:io_apic_print_entries",
        "arch/x86/kernel/apic/io_apic.c:save_ioapic_entries",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579210864,
      "name": "ioapic_read_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
struct IO_APIC_route_entry ioapic_read_entry(int apic, int pin)
```

```json
{
  "name": "ioapic_read_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579276736,
      "name": "ioapic_read_entry",
      "external": false,
      "loc": "arch/x86/kernel/apic/io_apic.c:317",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:enable_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:io_apic_print_entries",
        "arch/x86/kernel/apic/io_apic.c:save_ioapic_entries",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579276736,
      "name": "ioapic_read_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
struct IO_APIC_route_entry ioapic_read_entry(int apic, int pin)
```

```json
{
  "name": "ioapic_read_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579282624,
      "name": "ioapic_read_entry",
      "external": false,
      "loc": "arch/x86/kernel/apic/io_apic.c:317",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:enable_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:io_apic_print_entries",
        "arch/x86/kernel/apic/io_apic.c:save_ioapic_entries",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579282624,
      "name": "ioapic_read_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
struct IO_APIC_route_entry ioapic_read_entry(int apic, int pin)
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
struct IO_APIC_route_entry ioapic_read_entry(int apic, int pin)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct IO_APIC_route_entry ioapic_read_entry(int apic, int pin)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct IO_APIC_route_entry ioapic_read_entry(int apic, int pin)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct IO_APIC_route_entry ioapic_read_entry(int apic, int pin)
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
