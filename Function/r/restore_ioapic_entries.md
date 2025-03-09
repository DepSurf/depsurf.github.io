# Function: <code>restore_ioapic_entries</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int restore_ioapic_entries()
```

```json
{
  "name": "restore_ioapic_entries",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579201424,
      "name": "restore_ioapic_entries",
      "external": true,
      "loc": "arch/x86/kernel/apic/io_apic.c:684",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic",
        "arch/x86/kernel/apic/io_apic.c:ioapic_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579201424,
      "name": "restore_ioapic_entries",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
int restore_ioapic_entries()
```

```json
{
  "name": "restore_ioapic_entries",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579202048,
      "name": "restore_ioapic_entries",
      "external": true,
      "loc": "arch/x86/kernel/apic/io_apic.c:684",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic",
        "arch/x86/kernel/apic/io_apic.c:ioapic_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579202048,
      "name": "restore_ioapic_entries",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
int restore_ioapic_entries()
```

```json
{
  "name": "restore_ioapic_entries",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579213712,
      "name": "restore_ioapic_entries",
      "external": true,
      "loc": "arch/x86/kernel/apic/io_apic.c:683",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic",
        "arch/x86/kernel/apic/io_apic.c:ioapic_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579213712,
      "name": "restore_ioapic_entries",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
int restore_ioapic_entries()
```

```json
{
  "name": "restore_ioapic_entries",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579211232,
      "name": "restore_ioapic_entries",
      "external": true,
      "loc": "arch/x86/kernel/apic/io_apic.c:683",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic",
        "arch/x86/kernel/apic/io_apic.c:ioapic_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579211232,
      "name": "restore_ioapic_entries",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
int restore_ioapic_entries()
```

```json
{
  "name": "restore_ioapic_entries",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579228880,
      "name": "restore_ioapic_entries",
      "external": true,
      "loc": "arch/x86/kernel/apic/io_apic.c:684",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic",
        "arch/x86/kernel/apic/io_apic.c:ioapic_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579228880,
      "name": "restore_ioapic_entries",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int restore_ioapic_entries()
```

```json
{
  "name": "restore_ioapic_entries",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579240536,
      "name": "restore_ioapic_entries",
      "external": true,
      "loc": "arch/x86/kernel/apic/io_apic.c:685",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:ioapic_resume"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic",
        "arch/x86/kernel/apic/io_apic.c:ioapic_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579240240,
      "name": "restore_ioapic_entries.part.11",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    },
    {
      "addr": 18446744071579241552,
      "name": "restore_ioapic_entries",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int restore_ioapic_entries()
```

```json
{
  "name": "restore_ioapic_entries",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579264680,
      "name": "restore_ioapic_entries",
      "external": true,
      "loc": "arch/x86/kernel/apic/io_apic.c:685",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:ioapic_resume"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic",
        "arch/x86/kernel/apic/io_apic.c:ioapic_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579264384,
      "name": "restore_ioapic_entries.part.10",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    },
    {
      "addr": 18446744071579265328,
      "name": "restore_ioapic_entries",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int restore_ioapic_entries()
```

```json
{
  "name": "restore_ioapic_entries",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579279296,
      "name": "restore_ioapic_entries",
      "external": true,
      "loc": "arch/x86/kernel/apic/io_apic.c:686",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic",
        "arch/x86/kernel/apic/io_apic.c:ioapic_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579279296,
      "name": "restore_ioapic_entries",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
int restore_ioapic_entries()
```

```json
{
  "name": "restore_ioapic_entries",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579281760,
      "name": "restore_ioapic_entries",
      "external": true,
      "loc": "arch/x86/kernel/apic/io_apic.c:686",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic",
        "arch/x86/kernel/apic/io_apic.c:ioapic_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579281760,
      "name": "restore_ioapic_entries",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
int restore_ioapic_entries()
```

```json
{
  "name": "restore_ioapic_entries",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579311392,
      "name": "restore_ioapic_entries",
      "external": true,
      "loc": "arch/x86/kernel/apic/io_apic.c:673",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic",
        "arch/x86/kernel/apic/io_apic.c:ioapic_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579311392,
      "name": "restore_ioapic_entries",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
int restore_ioapic_entries()
```

```json
{
  "name": "restore_ioapic_entries",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579316688,
      "name": "restore_ioapic_entries",
      "external": true,
      "loc": "arch/x86/kernel/apic/io_apic.c:660",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic",
        "arch/x86/kernel/apic/io_apic.c:ioapic_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579316688,
      "name": "restore_ioapic_entries",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
int restore_ioapic_entries()
```

```json
{
  "name": "restore_ioapic_entries",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579319456,
      "name": "restore_ioapic_entries",
      "external": true,
      "loc": "arch/x86/kernel/apic/io_apic.c:660",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic",
        "arch/x86/kernel/apic/io_apic.c:ioapic_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579319456,
      "name": "restore_ioapic_entries",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
int restore_ioapic_entries()
```

```json
{
  "name": "restore_ioapic_entries",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579374192,
      "name": "restore_ioapic_entries",
      "external": true,
      "loc": "arch/x86/kernel/apic/io_apic.c:660",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic",
        "arch/x86/kernel/apic/io_apic.c:ioapic_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579374192,
      "name": "restore_ioapic_entries",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 294
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
int restore_ioapic_entries()
```

```json
{
  "name": "restore_ioapic_entries",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579438352,
      "name": "restore_ioapic_entries",
      "external": true,
      "loc": "arch/x86/kernel/apic/io_apic.c:661",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic",
        "arch/x86/kernel/apic/io_apic.c:ioapic_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579438352,
      "name": "restore_ioapic_entries",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 319
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
int restore_ioapic_entries()
```

```json
{
  "name": "restore_ioapic_entries",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579523232,
      "name": "restore_ioapic_entries",
      "external": true,
      "loc": "arch/x86/kernel/apic/io_apic.c:661",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic",
        "arch/x86/kernel/apic/io_apic.c:ioapic_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579523232,
      "name": "restore_ioapic_entries",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 319
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
int restore_ioapic_entries()
```

```json
{
  "name": "restore_ioapic_entries",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579535984,
      "name": "restore_ioapic_entries",
      "external": true,
      "loc": "arch/x86/kernel/apic/io_apic.c:662",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic",
        "arch/x86/kernel/apic/io_apic.c:ioapic_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579535984,
      "name": "restore_ioapic_entries",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 346
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
int restore_ioapic_entries()
```

```json
{
  "name": "restore_ioapic_entries",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579564800,
      "name": "restore_ioapic_entries",
      "external": true,
      "loc": "arch/x86/kernel/apic/io_apic.c:662",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic",
        "arch/x86/kernel/apic/io_apic.c:ioapic_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579564800,
      "name": "restore_ioapic_entries",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 346
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
int restore_ioapic_entries()
```

```json
{
  "name": "restore_ioapic_entries",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579280464,
      "name": "restore_ioapic_entries",
      "external": true,
      "loc": "arch/x86/kernel/apic/io_apic.c:686",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic",
        "arch/x86/kernel/apic/io_apic.c:ioapic_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579280464,
      "name": "restore_ioapic_entries",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
int restore_ioapic_entries()
```

```json
{
  "name": "restore_ioapic_entries",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579215792,
      "name": "restore_ioapic_entries",
      "external": true,
      "loc": "arch/x86/kernel/apic/io_apic.c:686",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic",
        "arch/x86/kernel/apic/io_apic.c:ioapic_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579215792,
      "name": "restore_ioapic_entries",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
int restore_ioapic_entries()
```

```json
{
  "name": "restore_ioapic_entries",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579281664,
      "name": "restore_ioapic_entries",
      "external": true,
      "loc": "arch/x86/kernel/apic/io_apic.c:686",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic",
        "arch/x86/kernel/apic/io_apic.c:ioapic_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579281664,
      "name": "restore_ioapic_entries",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
int restore_ioapic_entries()
```

```json
{
  "name": "restore_ioapic_entries",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579287552,
      "name": "restore_ioapic_entries",
      "external": true,
      "loc": "arch/x86/kernel/apic/io_apic.c:686",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic",
        "arch/x86/kernel/apic/io_apic.c:ioapic_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579287552,
      "name": "restore_ioapic_entries",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
int restore_ioapic_entries()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int restore_ioapic_entries()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int restore_ioapic_entries()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int restore_ioapic_entries()
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
