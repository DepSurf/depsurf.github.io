# Function: <code>ata_msleep</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void ata_msleep(struct ata_port * ap, unsigned int msecs)
```

```json
{
  "name": "ata_msleep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584908896,
      "name": "ata_msleep",
      "external": true,
      "loc": "drivers/ata/libata-core.c:6693",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:sata_link_debounce",
        "drivers/ata/libata-core.c:ata_wait_register",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:ata_wait_ready",
        "drivers/ata/libata-core.c:ata_wait_after_reset",
        "drivers/ata/libata-core.c:sata_link_hardreset",
        "drivers/ata/libata-eh.c:ata_port_wait_eh",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_sff_busy_sleep",
        "drivers/ata/libata-sff.c:ata_sff_busy_sleep",
        "drivers/ata/libata-sff.c:ata_sff_pio_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584908896,
      "name": "ata_msleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void ata_msleep(struct ata_port * ap, unsigned int msecs)
```

```json
{
  "name": "ata_msleep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585273840,
      "name": "ata_msleep",
      "external": true,
      "loc": "drivers/ata/libata-core.c:6892",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_wait_register",
        "drivers/ata/libata-core.c:sata_link_hardreset",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:sata_link_debounce",
        "drivers/ata/libata-core.c:ata_wait_after_reset",
        "drivers/ata/libata-core.c:ata_wait_ready",
        "drivers/ata/libata-eh.c:ata_port_wait_eh",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_sff_pio_task",
        "drivers/ata/libata-sff.c:ata_sff_busy_sleep",
        "drivers/ata/libata-sff.c:ata_sff_busy_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585273840,
      "name": "ata_msleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
void ata_msleep(struct ata_port * ap, unsigned int msecs)
```

```json
{
  "name": "ata_msleep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585473392,
      "name": "ata_msleep",
      "external": true,
      "loc": "drivers/ata/libata-core.c:6934",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_wait_register",
        "drivers/ata/libata-core.c:sata_link_hardreset",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:sata_link_debounce",
        "drivers/ata/libata-core.c:ata_wait_after_reset",
        "drivers/ata/libata-core.c:ata_wait_ready",
        "drivers/ata/libata-eh.c:ata_port_wait_eh",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_sff_pio_task",
        "drivers/ata/libata-sff.c:ata_sff_busy_sleep",
        "drivers/ata/libata-sff.c:ata_sff_busy_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585473392,
      "name": "ata_msleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
void ata_msleep(struct ata_port * ap, unsigned int msecs)
```

```json
{
  "name": "ata_msleep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585556880,
      "name": "ata_msleep",
      "external": true,
      "loc": "drivers/ata/libata-core.c:7020",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_wait_register",
        "drivers/ata/libata-core.c:sata_link_hardreset",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:sata_link_debounce",
        "drivers/ata/libata-core.c:ata_wait_after_reset",
        "drivers/ata/libata-core.c:ata_wait_ready",
        "drivers/ata/libata-eh.c:ata_port_wait_eh",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_sff_pio_task",
        "drivers/ata/libata-sff.c:ata_sff_busy_sleep",
        "drivers/ata/libata-sff.c:ata_sff_busy_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585556880,
      "name": "ata_msleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
void ata_msleep(struct ata_port * ap, unsigned int msecs)
```

```json
{
  "name": "ata_msleep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585988592,
      "name": "ata_msleep",
      "external": true,
      "loc": "drivers/ata/libata-core.c:7050",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_wait_register",
        "drivers/ata/libata-core.c:sata_link_hardreset",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:sata_link_debounce",
        "drivers/ata/libata-core.c:ata_wait_after_reset",
        "drivers/ata/libata-core.c:ata_wait_ready",
        "drivers/ata/libata-eh.c:ata_port_wait_eh",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_sff_pio_task",
        "drivers/ata/libata-sff.c:ata_sff_busy_sleep",
        "drivers/ata/libata-sff.c:ata_sff_busy_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585988592,
      "name": "ata_msleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
void ata_msleep(struct ata_port * ap, unsigned int msecs)
```

```json
{
  "name": "ata_msleep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586236960,
      "name": "ata_msleep",
      "external": true,
      "loc": "drivers/ata/libata-core.c:7097",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_wait_register",
        "drivers/ata/libata-core.c:sata_link_hardreset",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:sata_link_debounce",
        "drivers/ata/libata-core.c:ata_wait_after_reset",
        "drivers/ata/libata-core.c:ata_wait_ready",
        "drivers/ata/libata-eh.c:ata_port_wait_eh",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_sff_pio_task",
        "drivers/ata/libata-sff.c:ata_sff_busy_sleep",
        "drivers/ata/libata-sff.c:ata_sff_busy_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586236960,
      "name": "ata_msleep",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void ata_msleep(struct ata_port * ap, unsigned int msecs)
```

```json
{
  "name": "ata_msleep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586377376,
      "name": "ata_msleep",
      "external": true,
      "loc": "drivers/ata/libata-core.c:7101",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_wait_register",
        "drivers/ata/libata-core.c:sata_link_hardreset",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:sata_link_debounce",
        "drivers/ata/libata-core.c:ata_wait_after_reset",
        "drivers/ata/libata-core.c:ata_wait_ready",
        "drivers/ata/libata-eh.c:ata_port_wait_eh",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_sff_pio_task",
        "drivers/ata/libata-sff.c:ata_sff_busy_sleep",
        "drivers/ata/libata-sff.c:ata_sff_busy_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586377376,
      "name": "ata_msleep",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void ata_msleep(struct ata_port * ap, unsigned int msecs)
```

```json
{
  "name": "ata_msleep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586621056,
      "name": "ata_msleep",
      "external": true,
      "loc": "drivers/ata/libata-core.c:7086",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_wait_register",
        "drivers/ata/libata-core.c:sata_link_hardreset",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:sata_link_debounce",
        "drivers/ata/libata-core.c:ata_wait_after_reset",
        "drivers/ata/libata-core.c:ata_wait_ready",
        "drivers/ata/libata-eh.c:ata_port_wait_eh",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_sff_pio_task",
        "drivers/ata/libata-sff.c:ata_sff_busy_sleep",
        "drivers/ata/libata-sff.c:ata_sff_busy_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586621056,
      "name": "ata_msleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void ata_msleep(struct ata_port * ap, unsigned int msecs)
```

```json
{
  "name": "ata_msleep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586768624,
      "name": "ata_msleep",
      "external": true,
      "loc": "drivers/ata/libata-core.c:7133",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_wait_register",
        "drivers/ata/libata-core.c:sata_link_hardreset",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:sata_link_debounce",
        "drivers/ata/libata-core.c:ata_wait_after_reset",
        "drivers/ata/libata-core.c:ata_wait_ready",
        "drivers/ata/libata-eh.c:ata_port_wait_eh",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_sff_pio_task",
        "drivers/ata/libata-sff.c:ata_sff_busy_sleep",
        "drivers/ata/libata-sff.c:ata_sff_busy_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586768624,
      "name": "ata_msleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void ata_msleep(struct ata_port * ap, unsigned int msecs)
```

```json
{
  "name": "ata_msleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587580986,
      "name": "ata_msleep",
      "external": true,
      "loc": "drivers/ata/libata-core.c:6338",
      "file": "drivers/ata/libata-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_wait_after_reset",
        "drivers/ata/libata-core.c:ata_wait_ready"
      ],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_wait_register",
        "drivers/ata/libata-eh.c:ata_port_wait_eh",
        "drivers/ata/libata-sata.c:sata_link_hardreset",
        "drivers/ata/libata-sata.c:sata_link_resume",
        "drivers/ata/libata-sata.c:sata_link_debounce",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_sff_pio_task",
        "drivers/ata/libata-sff.c:ata_sff_busy_sleep",
        "drivers/ata/libata-sff.c:ata_sff_busy_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587571360,
      "name": "ata_msleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void ata_msleep(struct ata_port * ap, unsigned int msecs)
```

```json
{
  "name": "ata_msleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587647242,
      "name": "ata_msleep",
      "external": true,
      "loc": "drivers/ata/libata-core.c:6338",
      "file": "drivers/ata/libata-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_wait_after_reset",
        "drivers/ata/libata-core.c:ata_wait_ready"
      ],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_wait_register",
        "drivers/ata/libata-eh.c:ata_port_wait_eh",
        "drivers/ata/libata-sata.c:sata_link_hardreset",
        "drivers/ata/libata-sata.c:sata_link_resume",
        "drivers/ata/libata-sata.c:sata_link_debounce",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_sff_pio_task",
        "drivers/ata/libata-sff.c:ata_sff_busy_sleep",
        "drivers/ata/libata-sff.c:ata_sff_busy_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587637760,
      "name": "ata_msleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void ata_msleep(struct ata_port * ap, unsigned int msecs)
```

```json
{
  "name": "ata_msleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587527082,
      "name": "ata_msleep",
      "external": true,
      "loc": "drivers/ata/libata-core.c:6338",
      "file": "drivers/ata/libata-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_wait_after_reset",
        "drivers/ata/libata-core.c:ata_wait_ready"
      ],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_wait_register",
        "drivers/ata/libata-eh.c:ata_port_wait_eh",
        "drivers/ata/libata-sata.c:sata_link_hardreset",
        "drivers/ata/libata-sata.c:sata_link_resume",
        "drivers/ata/libata-sata.c:sata_link_debounce",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_sff_pio_task",
        "drivers/ata/libata-sff.c:ata_sff_busy_sleep",
        "drivers/ata/libata-sff.c:ata_sff_busy_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587518464,
      "name": "ata_msleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void ata_msleep(struct ata_port * ap, unsigned int msecs)
```

```json
{
  "name": "ata_msleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588104538,
      "name": "ata_msleep",
      "external": true,
      "loc": "drivers/ata/libata-core.c:6400",
      "file": "drivers/ata/libata-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_wait_after_reset",
        "drivers/ata/libata-core.c:ata_wait_ready"
      ],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_wait_register",
        "drivers/ata/libata-eh.c:ata_port_wait_eh",
        "drivers/ata/libata-sata.c:sata_link_hardreset",
        "drivers/ata/libata-sata.c:sata_link_resume",
        "drivers/ata/libata-sata.c:sata_link_debounce",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_sff_pio_task",
        "drivers/ata/libata-sff.c:ata_sff_busy_sleep",
        "drivers/ata/libata-sff.c:ata_sff_busy_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588094608,
      "name": "ata_msleep",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ata_msleep(struct ata_port * ap, unsigned int msecs)
```

```json
{
  "name": "ata_msleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589482873,
      "name": "ata_msleep",
      "external": true,
      "loc": "drivers/ata/libata-core.c:6411",
      "file": "drivers/ata/libata-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_wait_after_reset",
        "drivers/ata/libata-core.c:ata_wait_ready"
      ],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_wait_register",
        "drivers/ata/libata-eh.c:ata_port_wait_eh",
        "drivers/ata/libata-sata.c:sata_link_hardreset",
        "drivers/ata/libata-sata.c:sata_link_resume",
        "drivers/ata/libata-sata.c:sata_link_debounce",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_sff_pio_task",
        "drivers/ata/libata-sff.c:ata_sff_busy_sleep",
        "drivers/ata/libata-sff.c:ata_sff_busy_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589472592,
      "name": "ata_msleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
void ata_msleep(struct ata_port * ap, unsigned int msecs)
```

```json
{
  "name": "ata_msleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591064281,
      "name": "ata_msleep",
      "external": true,
      "loc": "drivers/ata/libata-core.c:6417",
      "file": "drivers/ata/libata-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_wait_after_reset",
        "drivers/ata/libata-core.c:ata_wait_ready"
      ],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_wait_register",
        "drivers/ata/libata-eh.c:ata_port_wait_eh",
        "drivers/ata/libata-sata.c:sata_link_hardreset",
        "drivers/ata/libata-sata.c:sata_link_resume",
        "drivers/ata/libata-sata.c:sata_link_debounce",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_sff_pio_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591051552,
      "name": "ata_msleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
void ata_msleep(struct ata_port * ap, unsigned int msecs)
```

```json
{
  "name": "ata_msleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591419561,
      "name": "ata_msleep",
      "external": true,
      "loc": "drivers/ata/libata-core.c:6643",
      "file": "drivers/ata/libata-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_wait_after_reset",
        "drivers/ata/libata-core.c:ata_wait_ready"
      ],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_wait_register",
        "drivers/ata/libata-eh.c:ata_port_wait_eh",
        "drivers/ata/libata-sata.c:sata_link_hardreset",
        "drivers/ata/libata-sata.c:sata_link_resume",
        "drivers/ata/libata-sata.c:sata_link_debounce",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_sff_pio_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591405600,
      "name": "ata_msleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
void ata_msleep(struct ata_port * ap, unsigned int msecs)
```

```json
{
  "name": "ata_msleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591771225,
      "name": "ata_msleep",
      "external": true,
      "loc": "drivers/ata/libata-core.c:6614",
      "file": "drivers/ata/libata-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_wait_after_reset",
        "drivers/ata/libata-core.c:ata_wait_ready"
      ],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_wait_register",
        "drivers/ata/libata-eh.c:ata_port_wait_eh",
        "drivers/ata/libata-sata.c:sata_link_hardreset",
        "drivers/ata/libata-sata.c:sata_link_resume",
        "drivers/ata/libata-sata.c:sata_link_debounce",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_sff_pio_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591756480,
      "name": "ata_msleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
void ata_msleep(struct ata_port * ap, unsigned int msecs)
```

```json
{
  "name": "ata_msleep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499688392,
      "name": "ata_msleep",
      "external": true,
      "loc": "drivers/ata/libata-core.c:7133",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_wait_register",
        "drivers/ata/libata-core.c:sata_link_hardreset",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:sata_link_debounce",
        "drivers/ata/libata-core.c:ata_wait_after_reset",
        "drivers/ata/libata-core.c:ata_wait_ready",
        "drivers/ata/libata-eh.c:ata_port_wait_eh",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_sff_pio_task",
        "drivers/ata/libata-sff.c:ata_sff_busy_sleep",
        "drivers/ata/libata-sff.c:ata_sff_busy_sleep",
        "drivers/ata/libahci.c:ahci_do_softreset",
        "drivers/ata/libahci.c:ahci_set_lpm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499688392,
      "name": "ata_msleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
void ata_msleep(struct ata_port * ap, unsigned int msecs)
```

```json
{
  "name": "ata_msleep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232136848,
      "name": "ata_msleep",
      "external": true,
      "loc": "drivers/ata/libata-core.c:7133",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_wait_register",
        "drivers/ata/libata-core.c:sata_link_hardreset",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:sata_link_debounce",
        "drivers/ata/libata-core.c:ata_wait_after_reset",
        "drivers/ata/libata-core.c:ata_wait_ready",
        "drivers/ata/libata-eh.c:ata_port_wait_eh",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_sff_pio_task",
        "drivers/ata/libata-sff.c:ata_sff_busy_sleep",
        "drivers/ata/libata-sff.c:ata_sff_busy_sleep",
        "drivers/ata/libahci.c:ahci_do_softreset",
        "drivers/ata/libahci.c:ahci_set_lpm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232136848,
      "name": "ata_msleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
void ata_msleep(struct ata_port * ap, unsigned int msecs)
```

```json
{
  "name": "ata_msleep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293020624,
      "name": "ata_msleep",
      "external": true,
      "loc": "drivers/ata/libata-core.c:7133",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_wait_register",
        "drivers/ata/libata-core.c:sata_link_hardreset",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:sata_link_debounce",
        "drivers/ata/libata-core.c:sata_link_debounce",
        "drivers/ata/libata-core.c:ata_wait_after_reset",
        "drivers/ata/libata-core.c:ata_wait_ready",
        "drivers/ata/libata-eh.c:ata_port_wait_eh",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_sff_pio_task",
        "drivers/ata/libata-sff.c:ata_sff_busy_sleep",
        "drivers/ata/libata-sff.c:ata_sff_busy_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293020624,
      "name": "ata_msleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
void ata_msleep(struct ata_port * ap, unsigned int msecs)
```

```json
{
  "name": "ata_msleep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276860012,
      "name": "ata_msleep",
      "external": true,
      "loc": "drivers/ata/libata-core.c:7133",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_wait_register",
        "drivers/ata/libata-core.c:sata_link_hardreset",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:sata_link_debounce",
        "drivers/ata/libata-core.c:ata_wait_after_reset",
        "drivers/ata/libata-core.c:ata_wait_ready",
        "drivers/ata/libata-eh.c:ata_port_wait_eh",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_sff_pio_task",
        "drivers/ata/libata-sff.c:ata_sff_busy_sleep",
        "drivers/ata/libata-sff.c:ata_sff_busy_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276860012,
      "name": "ata_msleep",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void ata_msleep(struct ata_port * ap, unsigned int msecs)
```

```json
{
  "name": "ata_msleep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586527328,
      "name": "ata_msleep",
      "external": true,
      "loc": "drivers/ata/libata-core.c:7133",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_wait_register",
        "drivers/ata/libata-core.c:sata_link_hardreset",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:sata_link_debounce",
        "drivers/ata/libata-core.c:ata_wait_after_reset",
        "drivers/ata/libata-core.c:ata_wait_ready",
        "drivers/ata/libata-eh.c:ata_port_wait_eh",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_sff_pio_task",
        "drivers/ata/libata-sff.c:ata_sff_busy_sleep",
        "drivers/ata/libata-sff.c:ata_sff_busy_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586527328,
      "name": "ata_msleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void ata_msleep(struct ata_port * ap, unsigned int msecs)
```

```json
{
  "name": "ata_msleep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586395904,
      "name": "ata_msleep",
      "external": true,
      "loc": "drivers/ata/libata-core.c:7133",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_wait_register",
        "drivers/ata/libata-core.c:sata_link_hardreset",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:sata_link_debounce",
        "drivers/ata/libata-core.c:ata_wait_after_reset",
        "drivers/ata/libata-core.c:ata_wait_ready",
        "drivers/ata/libata-eh.c:ata_port_wait_eh",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_sff_pio_task",
        "drivers/ata/libata-sff.c:ata_sff_busy_sleep",
        "drivers/ata/libata-sff.c:ata_sff_busy_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586395904,
      "name": "ata_msleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void ata_msleep(struct ata_port * ap, unsigned int msecs)
```

```json
{
  "name": "ata_msleep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586723184,
      "name": "ata_msleep",
      "external": true,
      "loc": "drivers/ata/libata-core.c:7133",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_wait_register",
        "drivers/ata/libata-core.c:sata_link_hardreset",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:sata_link_debounce",
        "drivers/ata/libata-core.c:ata_wait_after_reset",
        "drivers/ata/libata-core.c:ata_wait_ready",
        "drivers/ata/libata-eh.c:ata_port_wait_eh",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_sff_pio_task",
        "drivers/ata/libata-sff.c:ata_sff_busy_sleep",
        "drivers/ata/libata-sff.c:ata_sff_busy_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586723184,
      "name": "ata_msleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void ata_msleep(struct ata_port * ap, unsigned int msecs)
```

```json
{
  "name": "ata_msleep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586829360,
      "name": "ata_msleep",
      "external": true,
      "loc": "drivers/ata/libata-core.c:7133",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_wait_register",
        "drivers/ata/libata-core.c:sata_link_hardreset",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:sata_link_debounce",
        "drivers/ata/libata-core.c:ata_wait_after_reset",
        "drivers/ata/libata-core.c:ata_wait_ready",
        "drivers/ata/libata-eh.c:ata_port_wait_eh",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_sff_pio_task",
        "drivers/ata/libata-sff.c:ata_sff_busy_sleep",
        "drivers/ata/libata-sff.c:ata_sff_busy_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586829360,
      "name": "ata_msleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
