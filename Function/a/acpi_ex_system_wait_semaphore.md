# Function: <code>acpi_ex_system_wait_semaphore</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
acpi_status acpi_ex_system_wait_semaphore(void * semaphore, u16 timeout)
```

```json
{
  "name": "acpi_ex_system_wait_semaphore",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583669515,
      "name": "acpi_ex_system_wait_semaphore",
      "external": true,
      "loc": "drivers/acpi/acpica/exsystem.c:65",
      "file": "drivers/acpi/acpica/exsystem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583669515,
      "name": "acpi_ex_system_wait_semaphore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
acpi_status acpi_ex_system_wait_semaphore(void * semaphore, u16 timeout)
```

```json
{
  "name": "acpi_ex_system_wait_semaphore",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583992410,
      "name": "acpi_ex_system_wait_semaphore",
      "external": true,
      "loc": "drivers/acpi/acpica/exsystem.c:65",
      "file": "drivers/acpi/acpica/exsystem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583992410,
      "name": "acpi_ex_system_wait_semaphore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
acpi_status acpi_ex_system_wait_semaphore(void * semaphore, u16 timeout)
```

```json
{
  "name": "acpi_ex_system_wait_semaphore",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584133806,
      "name": "acpi_ex_system_wait_semaphore",
      "external": true,
      "loc": "drivers/acpi/acpica/exsystem.c:65",
      "file": "drivers/acpi/acpica/exsystem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584133806,
      "name": "acpi_ex_system_wait_semaphore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
acpi_status acpi_ex_system_wait_semaphore(void * semaphore, u16 timeout)
```

```json
{
  "name": "acpi_ex_system_wait_semaphore",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584200926,
      "name": "acpi_ex_system_wait_semaphore",
      "external": true,
      "loc": "drivers/acpi/acpica/exsystem.c:65",
      "file": "drivers/acpi/acpica/exsystem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584200926,
      "name": "acpi_ex_system_wait_semaphore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
acpi_status acpi_ex_system_wait_semaphore(void * semaphore, u16 timeout)
```

```json
{
  "name": "acpi_ex_system_wait_semaphore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584527240,
      "name": "acpi_ex_system_wait_semaphore",
      "external": true,
      "loc": "drivers/acpi/acpica/exsystem.c:65",
      "file": "drivers/acpi/acpica/exsystem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584527240,
      "name": "acpi_ex_system_wait_semaphore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
acpi_status acpi_ex_system_wait_semaphore(void * semaphore, u16 timeout)
```

```json
{
  "name": "acpi_ex_system_wait_semaphore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584751584,
      "name": "acpi_ex_system_wait_semaphore",
      "external": true,
      "loc": "drivers/acpi/acpica/exsystem.c:31",
      "file": "drivers/acpi/acpica/exsystem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584751584,
      "name": "acpi_ex_system_wait_semaphore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
acpi_status acpi_ex_system_wait_semaphore(void * semaphore, u16 timeout)
```

```json
{
  "name": "acpi_ex_system_wait_semaphore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584853152,
      "name": "acpi_ex_system_wait_semaphore",
      "external": true,
      "loc": "drivers/acpi/acpica/exsystem.c:31",
      "file": "drivers/acpi/acpica/exsystem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584853152,
      "name": "acpi_ex_system_wait_semaphore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
acpi_status acpi_ex_system_wait_semaphore(void * semaphore, u16 timeout)
```

```json
{
  "name": "acpi_ex_system_wait_semaphore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585056882,
      "name": "acpi_ex_system_wait_semaphore",
      "external": true,
      "loc": "drivers/acpi/acpica/exsystem.c:31",
      "file": "drivers/acpi/acpica/exsystem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585056882,
      "name": "acpi_ex_system_wait_semaphore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 251
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
acpi_status acpi_ex_system_wait_semaphore(void * semaphore, u16 timeout)
```

```json
{
  "name": "acpi_ex_system_wait_semaphore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585192967,
      "name": "acpi_ex_system_wait_semaphore",
      "external": true,
      "loc": "drivers/acpi/acpica/exsystem.c:31",
      "file": "drivers/acpi/acpica/exsystem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585192967,
      "name": "acpi_ex_system_wait_semaphore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 251
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
acpi_status acpi_ex_system_wait_semaphore(void * semaphore, u16 timeout)
```

```json
{
  "name": "acpi_ex_system_wait_semaphore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585898341,
      "name": "acpi_ex_system_wait_semaphore",
      "external": true,
      "loc": "drivers/acpi/acpica/exsystem.c:31",
      "file": "drivers/acpi/acpica/exsystem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585898341,
      "name": "acpi_ex_system_wait_semaphore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 251
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
acpi_status acpi_ex_system_wait_semaphore(void * semaphore, u16 timeout)
```

```json
{
  "name": "acpi_ex_system_wait_semaphore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586019677,
      "name": "acpi_ex_system_wait_semaphore",
      "external": true,
      "loc": "drivers/acpi/acpica/exsystem.c:31",
      "file": "drivers/acpi/acpica/exsystem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586019677,
      "name": "acpi_ex_system_wait_semaphore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 251
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
acpi_status acpi_ex_system_wait_semaphore(void * semaphore, u16 timeout)
```

```json
{
  "name": "acpi_ex_system_wait_semaphore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585896690,
      "name": "acpi_ex_system_wait_semaphore",
      "external": true,
      "loc": "drivers/acpi/acpica/exsystem.c:31",
      "file": "drivers/acpi/acpica/exsystem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585896690,
      "name": "acpi_ex_system_wait_semaphore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 251
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
acpi_status acpi_ex_system_wait_semaphore(void * semaphore, u16 timeout)
```

```json
{
  "name": "acpi_ex_system_wait_semaphore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586384194,
      "name": "acpi_ex_system_wait_semaphore",
      "external": true,
      "loc": "drivers/acpi/acpica/exsystem.c:31",
      "file": "drivers/acpi/acpica/exsystem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586384194,
      "name": "acpi_ex_system_wait_semaphore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 251
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
acpi_status acpi_ex_system_wait_semaphore(void * semaphore, u16 timeout)
```

```json
{
  "name": "acpi_ex_system_wait_semaphore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587632260,
      "name": "acpi_ex_system_wait_semaphore",
      "external": true,
      "loc": "drivers/acpi/acpica/exsystem.c:31",
      "file": "drivers/acpi/acpica/exsystem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587632260,
      "name": "acpi_ex_system_wait_semaphore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
acpi_status acpi_ex_system_wait_semaphore(void * semaphore, u16 timeout)
```

```json
{
  "name": "acpi_ex_system_wait_semaphore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588930992,
      "name": "acpi_ex_system_wait_semaphore",
      "external": true,
      "loc": "drivers/acpi/acpica/exsystem.c:31",
      "file": "drivers/acpi/acpica/exsystem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588930992,
      "name": "acpi_ex_system_wait_semaphore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 306
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
acpi_status acpi_ex_system_wait_semaphore(void * semaphore, u16 timeout)
```

```json
{
  "name": "acpi_ex_system_wait_semaphore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589220992,
      "name": "acpi_ex_system_wait_semaphore",
      "external": true,
      "loc": "drivers/acpi/acpica/exsystem.c:31",
      "file": "drivers/acpi/acpica/exsystem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589220992,
      "name": "acpi_ex_system_wait_semaphore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 306
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
acpi_status acpi_ex_system_wait_semaphore(void * semaphore, u16 timeout)
```

```json
{
  "name": "acpi_ex_system_wait_semaphore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589527504,
      "name": "acpi_ex_system_wait_semaphore",
      "external": true,
      "loc": "drivers/acpi/acpica/exsystem.c:31",
      "file": "drivers/acpi/acpica/exsystem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589527504,
      "name": "acpi_ex_system_wait_semaphore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 306
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
acpi_status acpi_ex_system_wait_semaphore(void * semaphore, u16 timeout)
```

```json
{
  "name": "acpi_ex_system_wait_semaphore",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497537452,
      "name": "acpi_ex_system_wait_semaphore",
      "external": true,
      "loc": "drivers/acpi/acpica/exsystem.c:31",
      "file": "drivers/acpi/acpica/exsystem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497537452,
      "name": "acpi_ex_system_wait_semaphore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
    }
  ]
}
```
</details>
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
acpi_status acpi_ex_system_wait_semaphore(void * semaphore, u16 timeout)
```

```json
{
  "name": "acpi_ex_system_wait_semaphore",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585070140,
      "name": "acpi_ex_system_wait_semaphore",
      "external": true,
      "loc": "drivers/acpi/acpica/exsystem.c:31",
      "file": "drivers/acpi/acpica/exsystem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585070140,
      "name": "acpi_ex_system_wait_semaphore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
acpi_status acpi_ex_system_wait_semaphore(void * semaphore, u16 timeout)
```

```json
{
  "name": "acpi_ex_system_wait_semaphore",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584985619,
      "name": "acpi_ex_system_wait_semaphore",
      "external": true,
      "loc": "drivers/acpi/acpica/exsystem.c:31",
      "file": "drivers/acpi/acpica/exsystem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584985619,
      "name": "acpi_ex_system_wait_semaphore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
acpi_status acpi_ex_system_wait_semaphore(void * semaphore, u16 timeout)
```

```json
{
  "name": "acpi_ex_system_wait_semaphore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585144551,
      "name": "acpi_ex_system_wait_semaphore",
      "external": true,
      "loc": "drivers/acpi/acpica/exsystem.c:31",
      "file": "drivers/acpi/acpica/exsystem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585144551,
      "name": "acpi_ex_system_wait_semaphore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 251
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
acpi_status acpi_ex_system_wait_semaphore(void * semaphore, u16 timeout)
```

```json
{
  "name": "acpi_ex_system_wait_semaphore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585250711,
      "name": "acpi_ex_system_wait_semaphore",
      "external": true,
      "loc": "drivers/acpi/acpica/exsystem.c:31",
      "file": "drivers/acpi/acpica/exsystem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585250711,
      "name": "acpi_ex_system_wait_semaphore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 251
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
acpi_status acpi_ex_system_wait_semaphore(void * semaphore, u16 timeout)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
acpi_status acpi_ex_system_wait_semaphore(void * semaphore, u16 timeout)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
acpi_status acpi_ex_system_wait_semaphore(void * semaphore, u16 timeout)
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
