# Function: <code>acpi_ds_push_walk_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void acpi_ds_push_walk_state(struct acpi_walk_state * walk_state, struct acpi_thread_state * thread)
```

```json
{
  "name": "acpi_ds_push_walk_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583628078,
      "name": "acpi_ds_push_walk_state",
      "external": true,
      "loc": "drivers/acpi/acpica/dswstate.c:475",
      "file": "drivers/acpi/acpica/dswstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state"
      ],
      "caller_func": [
        "drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583628078,
      "name": "acpi_ds_push_walk_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void acpi_ds_push_walk_state(struct acpi_walk_state * walk_state, struct acpi_thread_state * thread)
```

```json
{
  "name": "acpi_ds_push_walk_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583951345,
      "name": "acpi_ds_push_walk_state",
      "external": true,
      "loc": "drivers/acpi/acpica/dswstate.c:475",
      "file": "drivers/acpi/acpica/dswstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state"
      ],
      "caller_func": [
        "drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583951154,
      "name": "acpi_ds_push_walk_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void acpi_ds_push_walk_state(struct acpi_walk_state * walk_state, struct acpi_thread_state * thread)
```

```json
{
  "name": "acpi_ds_push_walk_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584092857,
      "name": "acpi_ds_push_walk_state",
      "external": true,
      "loc": "drivers/acpi/acpica/dswstate.c:475",
      "file": "drivers/acpi/acpica/dswstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state"
      ],
      "caller_func": [
        "drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584092666,
      "name": "acpi_ds_push_walk_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void acpi_ds_push_walk_state(struct acpi_walk_state * walk_state, struct acpi_thread_state * thread)
```

```json
{
  "name": "acpi_ds_push_walk_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584159636,
      "name": "acpi_ds_push_walk_state",
      "external": true,
      "loc": "drivers/acpi/acpica/dswstate.c:475",
      "file": "drivers/acpi/acpica/dswstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state"
      ],
      "caller_func": [
        "drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584159445,
      "name": "acpi_ds_push_walk_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void acpi_ds_push_walk_state(struct acpi_walk_state * walk_state, struct acpi_thread_state * thread)
```

```json
{
  "name": "acpi_ds_push_walk_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584452522,
      "name": "acpi_ds_push_walk_state",
      "external": true,
      "loc": "drivers/acpi/acpica/dswstate.c:475",
      "file": "drivers/acpi/acpica/dswstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state",
        "drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584452522,
      "name": "acpi_ds_push_walk_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void acpi_ds_push_walk_state(struct acpi_walk_state * walk_state, struct acpi_thread_state * thread)
```

```json
{
  "name": "acpi_ds_push_walk_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584676549,
      "name": "acpi_ds_push_walk_state",
      "external": true,
      "loc": "drivers/acpi/acpica/dswstate.c:441",
      "file": "drivers/acpi/acpica/dswstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state",
        "drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584676549,
      "name": "acpi_ds_push_walk_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void acpi_ds_push_walk_state(struct acpi_walk_state * walk_state, struct acpi_thread_state * thread)
```

```json
{
  "name": "acpi_ds_push_walk_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584776522,
      "name": "acpi_ds_push_walk_state",
      "external": true,
      "loc": "drivers/acpi/acpica/dswstate.c:441",
      "file": "drivers/acpi/acpica/dswstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state",
        "drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584776522,
      "name": "acpi_ds_push_walk_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void acpi_ds_push_walk_state(struct acpi_walk_state * walk_state, struct acpi_thread_state * thread)
```

```json
{
  "name": "acpi_ds_push_walk_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584979114,
      "name": "acpi_ds_push_walk_state",
      "external": true,
      "loc": "drivers/acpi/acpica/dswstate.c:441",
      "file": "drivers/acpi/acpica/dswstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state",
        "drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584979114,
      "name": "acpi_ds_push_walk_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void acpi_ds_push_walk_state(struct acpi_walk_state * walk_state, struct acpi_thread_state * thread)
```

```json
{
  "name": "acpi_ds_push_walk_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585114978,
      "name": "acpi_ds_push_walk_state",
      "external": true,
      "loc": "drivers/acpi/acpica/dswstate.c:441",
      "file": "drivers/acpi/acpica/dswstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state",
        "drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585114978,
      "name": "acpi_ds_push_walk_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void acpi_ds_push_walk_state(struct acpi_walk_state * walk_state, struct acpi_thread_state * thread)
```

```json
{
  "name": "acpi_ds_push_walk_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585819780,
      "name": "acpi_ds_push_walk_state",
      "external": true,
      "loc": "drivers/acpi/acpica/dswstate.c:441",
      "file": "drivers/acpi/acpica/dswstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state",
        "drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585819780,
      "name": "acpi_ds_push_walk_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void acpi_ds_push_walk_state(struct acpi_walk_state * walk_state, struct acpi_thread_state * thread)
```

```json
{
  "name": "acpi_ds_push_walk_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585940602,
      "name": "acpi_ds_push_walk_state",
      "external": true,
      "loc": "drivers/acpi/acpica/dswstate.c:441",
      "file": "drivers/acpi/acpica/dswstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state",
        "drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585940602,
      "name": "acpi_ds_push_walk_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void acpi_ds_push_walk_state(struct acpi_walk_state * walk_state, struct acpi_thread_state * thread)
```

```json
{
  "name": "acpi_ds_push_walk_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585817869,
      "name": "acpi_ds_push_walk_state",
      "external": true,
      "loc": "drivers/acpi/acpica/dswstate.c:441",
      "file": "drivers/acpi/acpica/dswstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state",
        "drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585817869,
      "name": "acpi_ds_push_walk_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void acpi_ds_push_walk_state(struct acpi_walk_state * walk_state, struct acpi_thread_state * thread)
```

```json
{
  "name": "acpi_ds_push_walk_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586304000,
      "name": "acpi_ds_push_walk_state",
      "external": true,
      "loc": "drivers/acpi/acpica/dswstate.c:441",
      "file": "drivers/acpi/acpica/dswstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state",
        "drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586304000,
      "name": "acpi_ds_push_walk_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void acpi_ds_push_walk_state(struct acpi_walk_state * walk_state, struct acpi_thread_state * thread)
```

```json
{
  "name": "acpi_ds_push_walk_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587549165,
      "name": "acpi_ds_push_walk_state",
      "external": true,
      "loc": "drivers/acpi/acpica/dswstate.c:441",
      "file": "drivers/acpi/acpica/dswstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state",
        "drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587549165,
      "name": "acpi_ds_push_walk_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void acpi_ds_push_walk_state(struct acpi_walk_state * walk_state, struct acpi_thread_state * thread)
```

```json
{
  "name": "acpi_ds_push_walk_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588831524,
      "name": "acpi_ds_push_walk_state",
      "external": true,
      "loc": "drivers/acpi/acpica/dswstate.c:441",
      "file": "drivers/acpi/acpica/dswstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state"
      ],
      "caller_func": [
        "drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588831088,
      "name": "acpi_ds_push_walk_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void acpi_ds_push_walk_state(struct acpi_walk_state * walk_state, struct acpi_thread_state * thread)
```

```json
{
  "name": "acpi_ds_push_walk_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589120852,
      "name": "acpi_ds_push_walk_state",
      "external": true,
      "loc": "drivers/acpi/acpica/dswstate.c:441",
      "file": "drivers/acpi/acpica/dswstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state"
      ],
      "caller_func": [
        "drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589120416,
      "name": "acpi_ds_push_walk_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void acpi_ds_push_walk_state(struct acpi_walk_state * walk_state, struct acpi_thread_state * thread)
```

```json
{
  "name": "acpi_ds_push_walk_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589426683,
      "name": "acpi_ds_push_walk_state",
      "external": true,
      "loc": "drivers/acpi/acpica/dswstate.c:441",
      "file": "drivers/acpi/acpica/dswstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state"
      ],
      "caller_func": [
        "drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589426288,
      "name": "acpi_ds_push_walk_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void acpi_ds_push_walk_state(struct acpi_walk_state * walk_state, struct acpi_thread_state * thread)
```

```json
{
  "name": "acpi_ds_push_walk_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497502820,
      "name": "acpi_ds_push_walk_state",
      "external": true,
      "loc": "drivers/acpi/acpica/dswstate.c:441",
      "file": "drivers/acpi/acpica/dswstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state"
      ],
      "caller_func": [
        "drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497502584,
      "name": "acpi_ds_push_walk_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void acpi_ds_push_walk_state(struct acpi_walk_state * walk_state, struct acpi_thread_state * thread)
```

```json
{
  "name": "acpi_ds_push_walk_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585026768,
      "name": "acpi_ds_push_walk_state",
      "external": true,
      "loc": "drivers/acpi/acpica/dswstate.c:441",
      "file": "drivers/acpi/acpica/dswstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state"
      ],
      "caller_func": [
        "drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585026576,
      "name": "acpi_ds_push_walk_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void acpi_ds_push_walk_state(struct acpi_walk_state * walk_state, struct acpi_thread_state * thread)
```

```json
{
  "name": "acpi_ds_push_walk_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584942391,
      "name": "acpi_ds_push_walk_state",
      "external": true,
      "loc": "drivers/acpi/acpica/dswstate.c:441",
      "file": "drivers/acpi/acpica/dswstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state"
      ],
      "caller_func": [
        "drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584942204,
      "name": "acpi_ds_push_walk_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void acpi_ds_push_walk_state(struct acpi_walk_state * walk_state, struct acpi_thread_state * thread)
```

```json
{
  "name": "acpi_ds_push_walk_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585066562,
      "name": "acpi_ds_push_walk_state",
      "external": true,
      "loc": "drivers/acpi/acpica/dswstate.c:441",
      "file": "drivers/acpi/acpica/dswstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state",
        "drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585066562,
      "name": "acpi_ds_push_walk_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void acpi_ds_push_walk_state(struct acpi_walk_state * walk_state, struct acpi_thread_state * thread)
```

```json
{
  "name": "acpi_ds_push_walk_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585172722,
      "name": "acpi_ds_push_walk_state",
      "external": true,
      "loc": "drivers/acpi/acpica/dswstate.c:441",
      "file": "drivers/acpi/acpica/dswstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state",
        "drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585172722,
      "name": "acpi_ds_push_walk_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void acpi_ds_push_walk_state(struct acpi_walk_state * walk_state, struct acpi_thread_state * thread)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void acpi_ds_push_walk_state(struct acpi_walk_state * walk_state, struct acpi_thread_state * thread)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void acpi_ds_push_walk_state(struct acpi_walk_state * walk_state, struct acpi_thread_state * thread)
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
