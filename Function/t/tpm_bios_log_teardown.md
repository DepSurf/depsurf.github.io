# Function: <code>tpm_bios_log_teardown</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void tpm_bios_log_teardown(struct dentry * * lst)
```

```json
{
  "name": "tpm_bios_log_teardown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584252224,
      "name": "tpm_bios_log_teardown",
      "external": true,
      "loc": "drivers/char/tpm/tpm_eventlog.c:448",
      "file": "drivers/char/tpm/tpm_eventlog.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584252224,
      "name": "tpm_bios_log_teardown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void tpm_bios_log_teardown(struct dentry * * lst)
```

```json
{
  "name": "tpm_bios_log_teardown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584592272,
      "name": "tpm_bios_log_teardown",
      "external": true,
      "loc": "drivers/char/tpm/tpm_eventlog.c:448",
      "file": "drivers/char/tpm/tpm_eventlog.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584592272,
      "name": "tpm_bios_log_teardown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void tpm_bios_log_teardown(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_bios_log_teardown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584771264,
      "name": "tpm_bios_log_teardown",
      "external": true,
      "loc": "drivers/char/tpm/tpm_eventlog.c:442",
      "file": "drivers/char/tpm/tpm_eventlog.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/char/tpm/tpm_eventlog.c:tpm_bios_log_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584771264,
      "name": "tpm_bios_log_teardown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
void tpm_bios_log_teardown(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_bios_log_teardown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584856704,
      "name": "tpm_bios_log_teardown",
      "external": true,
      "loc": "drivers/char/tpm/tpm1_eventlog.c:449",
      "file": "drivers/char/tpm/tpm1_eventlog.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/char/tpm/tpm1_eventlog.c:tpm_bios_log_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584856704,
      "name": "tpm_bios_log_teardown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
void tpm_bios_log_teardown(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_bios_log_teardown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585275856,
      "name": "tpm_bios_log_teardown",
      "external": true,
      "loc": "drivers/char/tpm/tpm1_eventlog.c:449",
      "file": "drivers/char/tpm/tpm1_eventlog.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/char/tpm/tpm1_eventlog.c:tpm_bios_log_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585275856,
      "name": "tpm_bios_log_teardown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
void tpm_bios_log_teardown(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_bios_log_teardown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585511840,
      "name": "tpm_bios_log_teardown",
      "external": true,
      "loc": "drivers/char/tpm/eventlog/common.c:175",
      "file": "drivers/char/tpm/eventlog/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585511840,
      "name": "tpm_bios_log_teardown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
void tpm_bios_log_teardown(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_bios_log_teardown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585638896,
      "name": "tpm_bios_log_teardown",
      "external": true,
      "loc": "drivers/char/tpm/eventlog/common.c:175",
      "file": "drivers/char/tpm/eventlog/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585638896,
      "name": "tpm_bios_log_teardown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
void tpm_bios_log_teardown(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_bios_log_teardown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585862592,
      "name": "tpm_bios_log_teardown",
      "external": true,
      "loc": "drivers/char/tpm/eventlog/common.c:170",
      "file": "drivers/char/tpm/eventlog/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585862592,
      "name": "tpm_bios_log_teardown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
void tpm_bios_log_teardown(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_bios_log_teardown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586005152,
      "name": "tpm_bios_log_teardown",
      "external": true,
      "loc": "drivers/char/tpm/eventlog/common.c:170",
      "file": "drivers/char/tpm/eventlog/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586005152,
      "name": "tpm_bios_log_teardown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
void tpm_bios_log_teardown(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_bios_log_teardown",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586743356,
      "name": "tpm_bios_log_teardown",
      "external": true,
      "loc": "drivers/char/tpm/eventlog/common.c:166",
      "file": "drivers/char/tpm/eventlog/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup"
      ],
      "caller_func": [
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586743504,
      "name": "tpm_bios_log_teardown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
void tpm_bios_log_teardown(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_bios_log_teardown",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586837340,
      "name": "tpm_bios_log_teardown",
      "external": true,
      "loc": "drivers/char/tpm/eventlog/common.c:166",
      "file": "drivers/char/tpm/eventlog/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup"
      ],
      "caller_func": [
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586837488,
      "name": "tpm_bios_log_teardown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
void tpm_bios_log_teardown(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_bios_log_teardown",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586717690,
      "name": "tpm_bios_log_teardown",
      "external": true,
      "loc": "drivers/char/tpm/eventlog/common.c:169",
      "file": "drivers/char/tpm/eventlog/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup"
      ],
      "caller_func": [
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586717856,
      "name": "tpm_bios_log_teardown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
void tpm_bios_log_teardown(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_bios_log_teardown",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587268744,
      "name": "tpm_bios_log_teardown",
      "external": true,
      "loc": "drivers/char/tpm/eventlog/common.c:169",
      "file": "drivers/char/tpm/eventlog/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup"
      ],
      "caller_func": [
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587269024,
      "name": "tpm_bios_log_teardown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 179
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
void tpm_bios_log_teardown(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_bios_log_teardown",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588579294,
      "name": "tpm_bios_log_teardown",
      "external": true,
      "loc": "drivers/char/tpm/eventlog/common.c:169",
      "file": "drivers/char/tpm/eventlog/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup"
      ],
      "caller_func": [
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588579568,
      "name": "tpm_bios_log_teardown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
void tpm_bios_log_teardown(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_bios_log_teardown",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590034542,
      "name": "tpm_bios_log_teardown",
      "external": true,
      "loc": "drivers/char/tpm/eventlog/common.c:169",
      "file": "drivers/char/tpm/eventlog/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup"
      ],
      "caller_func": [
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590034832,
      "name": "tpm_bios_log_teardown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
void tpm_bios_log_teardown(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_bios_log_teardown",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590343886,
      "name": "tpm_bios_log_teardown",
      "external": true,
      "loc": "drivers/char/tpm/eventlog/common.c:169",
      "file": "drivers/char/tpm/eventlog/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup"
      ],
      "caller_func": [
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590344176,
      "name": "tpm_bios_log_teardown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
void tpm_bios_log_teardown(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_bios_log_teardown",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590685374,
      "name": "tpm_bios_log_teardown",
      "external": true,
      "loc": "drivers/char/tpm/eventlog/common.c:169",
      "file": "drivers/char/tpm/eventlog/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup"
      ],
      "caller_func": [
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590685664,
      "name": "tpm_bios_log_teardown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
void tpm_bios_log_teardown(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_bios_log_teardown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498801824,
      "name": "tpm_bios_log_teardown",
      "external": true,
      "loc": "drivers/char/tpm/eventlog/common.c:170",
      "file": "drivers/char/tpm/eventlog/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498801824,
      "name": "tpm_bios_log_teardown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void tpm_bios_log_teardown(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_bios_log_teardown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231416464,
      "name": "tpm_bios_log_teardown",
      "external": true,
      "loc": "drivers/char/tpm/eventlog/common.c:170",
      "file": "drivers/char/tpm/eventlog/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231416464,
      "name": "tpm_bios_log_teardown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void tpm_bios_log_teardown(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_bios_log_teardown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291998832,
      "name": "tpm_bios_log_teardown",
      "external": true,
      "loc": "drivers/char/tpm/eventlog/common.c:170",
      "file": "drivers/char/tpm/eventlog/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291998832,
      "name": "tpm_bios_log_teardown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
void tpm_bios_log_teardown(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_bios_log_teardown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276304616,
      "name": "tpm_bios_log_teardown",
      "external": true,
      "loc": "drivers/char/tpm/eventlog/common.c:170",
      "file": "drivers/char/tpm/eventlog/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276304616,
      "name": "tpm_bios_log_teardown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void tpm_bios_log_teardown(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_bios_log_teardown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585766128,
      "name": "tpm_bios_log_teardown",
      "external": true,
      "loc": "drivers/char/tpm/eventlog/common.c:170",
      "file": "drivers/char/tpm/eventlog/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585766128,
      "name": "tpm_bios_log_teardown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
void tpm_bios_log_teardown(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_bios_log_teardown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585625312,
      "name": "tpm_bios_log_teardown",
      "external": true,
      "loc": "drivers/char/tpm/eventlog/common.c:170",
      "file": "drivers/char/tpm/eventlog/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585625312,
      "name": "tpm_bios_log_teardown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
void tpm_bios_log_teardown(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_bios_log_teardown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585955168,
      "name": "tpm_bios_log_teardown",
      "external": true,
      "loc": "drivers/char/tpm/eventlog/common.c:170",
      "file": "drivers/char/tpm/eventlog/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585955168,
      "name": "tpm_bios_log_teardown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
void tpm_bios_log_teardown(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_bios_log_teardown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586062912,
      "name": "tpm_bios_log_teardown",
      "external": true,
      "loc": "drivers/char/tpm/eventlog/common.c:170",
      "file": "drivers/char/tpm/eventlog/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586062912,
      "name": "tpm_bios_log_teardown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct tpm_chip * chip</code>
</li>
<li>
<b>Param removed. </b>
<code>struct dentry * * lst</code>
</li>
</ul>
</details>
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
