# Function: <code>irq_activate_and_startup</code>

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
int irq_activate_and_startup(struct irq_desc * desc, bool resend)
```

```json
{
  "name": "irq_activate_and_startup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579836432,
      "name": "irq_activate_and_startup",
      "external": true,
      "loc": "kernel/irq/chip.c:297",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/chip.c:__irq_do_set_handler",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579836432,
      "name": "irq_activate_and_startup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
int irq_activate_and_startup(struct irq_desc * desc, bool resend)
```

```json
{
  "name": "irq_activate_and_startup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579870304,
      "name": "irq_activate_and_startup",
      "external": true,
      "loc": "kernel/irq/chip.c:295",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/chip.c:__irq_do_set_handler",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579870304,
      "name": "irq_activate_and_startup",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
int irq_activate_and_startup(struct irq_desc * desc, bool resend)
```

```json
{
  "name": "irq_activate_and_startup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579917344,
      "name": "irq_activate_and_startup",
      "external": true,
      "loc": "kernel/irq/chip.c:295",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/chip.c:__irq_do_set_handler",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579917344,
      "name": "irq_activate_and_startup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int irq_activate_and_startup(struct irq_desc * desc, bool resend)
```

```json
{
  "name": "irq_activate_and_startup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "irq_activate_and_startup",
      "external": true,
      "loc": "kernel/irq/chip.c:295",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/chip.c:__irq_do_set_handler",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579957956,
      "name": "irq_activate_and_startup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071579955424,
      "name": "irq_activate_and_startup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
int irq_activate_and_startup(struct irq_desc * desc, bool resend)
```

```json
{
  "name": "irq_activate_and_startup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580005280,
      "name": "irq_activate_and_startup",
      "external": true,
      "loc": "kernel/irq/chip.c:295",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/chip.c:__irq_do_set_handler",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580005280,
      "name": "irq_activate_and_startup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
int irq_activate_and_startup(struct irq_desc * desc, bool resend)
```

```json
{
  "name": "irq_activate_and_startup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580054848,
      "name": "irq_activate_and_startup",
      "external": true,
      "loc": "kernel/irq/chip.c:295",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/chip.c:__irq_do_set_handler",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580054848,
      "name": "irq_activate_and_startup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
int irq_activate_and_startup(struct irq_desc * desc, bool resend)
```

```json
{
  "name": "irq_activate_and_startup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580037440,
      "name": "irq_activate_and_startup",
      "external": true,
      "loc": "kernel/irq/chip.c:295",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/chip.c:__irq_do_set_handler",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580037440,
      "name": "irq_activate_and_startup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
int irq_activate_and_startup(struct irq_desc * desc, bool resend)
```

```json
{
  "name": "irq_activate_and_startup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580038304,
      "name": "irq_activate_and_startup",
      "external": true,
      "loc": "kernel/irq/chip.c:298",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/chip.c:__irq_do_set_handler",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580038304,
      "name": "irq_activate_and_startup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
int irq_activate_and_startup(struct irq_desc * desc, bool resend)
```

```json
{
  "name": "irq_activate_and_startup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580170864,
      "name": "irq_activate_and_startup",
      "external": true,
      "loc": "kernel/irq/chip.c:298",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/chip.c:__irq_do_set_handler",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580170864,
      "name": "irq_activate_and_startup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
int irq_activate_and_startup(struct irq_desc * desc, bool resend)
```

```json
{
  "name": "irq_activate_and_startup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580317792,
      "name": "irq_activate_and_startup",
      "external": true,
      "loc": "kernel/irq/chip.c:295",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/chip.c:__irq_do_set_handler",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580317792,
      "name": "irq_activate_and_startup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
int irq_activate_and_startup(struct irq_desc * desc, bool resend)
```

```json
{
  "name": "irq_activate_and_startup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580531776,
      "name": "irq_activate_and_startup",
      "external": true,
      "loc": "kernel/irq/chip.c:297",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/chip.c:__irq_do_set_handler",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580531776,
      "name": "irq_activate_and_startup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
int irq_activate_and_startup(struct irq_desc * desc, bool resend)
```

```json
{
  "name": "irq_activate_and_startup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580607246,
      "name": "irq_activate_and_startup",
      "external": true,
      "loc": "kernel/irq/chip.c:297",
      "file": "kernel/irq/chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:__irq_do_set_handler"
      ],
      "caller_func": [
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580605088,
      "name": "irq_activate_and_startup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
int irq_activate_and_startup(struct irq_desc * desc, bool resend)
```

```json
{
  "name": "irq_activate_and_startup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580671758,
      "name": "irq_activate_and_startup",
      "external": true,
      "loc": "kernel/irq/chip.c:297",
      "file": "kernel/irq/chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:__irq_do_set_handler"
      ],
      "caller_func": [
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580669600,
      "name": "irq_activate_and_startup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
int irq_activate_and_startup(struct irq_desc * desc, bool resend)
```

```json
{
  "name": "irq_activate_and_startup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491201400,
      "name": "irq_activate_and_startup",
      "external": true,
      "loc": "kernel/irq/chip.c:295",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/chip.c:__irq_do_set_handler",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491201400,
      "name": "irq_activate_and_startup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int irq_activate_and_startup(struct irq_desc * desc, bool resend)
```

```json
{
  "name": "irq_activate_and_startup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225220508,
      "name": "irq_activate_and_startup",
      "external": true,
      "loc": "kernel/irq/chip.c:295",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/chip.c:__irq_do_set_handler",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225220508,
      "name": "irq_activate_and_startup",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int irq_activate_and_startup(struct irq_desc * desc, bool resend)
```

```json
{
  "name": "irq_activate_and_startup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284104512,
      "name": "irq_activate_and_startup",
      "external": true,
      "loc": "kernel/irq/chip.c:295",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/chip.c:__irq_do_set_handler",
        "kernel/irq/chip.c:__irq_do_set_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284104512,
      "name": "irq_activate_and_startup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
int irq_activate_and_startup(struct irq_desc * desc, bool resend)
```

```json
{
  "name": "irq_activate_and_startup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271743182,
      "name": "irq_activate_and_startup",
      "external": true,
      "loc": "kernel/irq/chip.c:295",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/chip.c:__irq_do_set_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271743182,
      "name": "irq_activate_and_startup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
int irq_activate_and_startup(struct irq_desc * desc, bool resend)
```

```json
{
  "name": "irq_activate_and_startup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579974016,
      "name": "irq_activate_and_startup",
      "external": true,
      "loc": "kernel/irq/chip.c:295",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/chip.c:__irq_do_set_handler",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579974016,
      "name": "irq_activate_and_startup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
int irq_activate_and_startup(struct irq_desc * desc, bool resend)
```

```json
{
  "name": "irq_activate_and_startup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579911824,
      "name": "irq_activate_and_startup",
      "external": true,
      "loc": "kernel/irq/chip.c:295",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/chip.c:__irq_do_set_handler",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579911824,
      "name": "irq_activate_and_startup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
int irq_activate_and_startup(struct irq_desc * desc, bool resend)
```

```json
{
  "name": "irq_activate_and_startup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579965552,
      "name": "irq_activate_and_startup",
      "external": true,
      "loc": "kernel/irq/chip.c:295",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/chip.c:__irq_do_set_handler",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579965552,
      "name": "irq_activate_and_startup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
int irq_activate_and_startup(struct irq_desc * desc, bool resend)
```

```json
{
  "name": "irq_activate_and_startup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580012080,
      "name": "irq_activate_and_startup",
      "external": true,
      "loc": "kernel/irq/chip.c:295",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/chip.c:__irq_do_set_handler",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580012080,
      "name": "irq_activate_and_startup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
int irq_activate_and_startup(struct irq_desc * desc, bool resend)
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
