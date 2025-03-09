# Function: <code>tpm_read_log_acpi</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int tpm_read_log_acpi(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_read_log_acpi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584773664,
      "name": "tpm_read_log_acpi",
      "external": true,
      "loc": "drivers/char/tpm/tpm_acpi.c:49",
      "file": "drivers/char/tpm/tpm_acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_eventlog.c:tpm_bios_log_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584773664,
      "name": "tpm_read_log_acpi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
int tpm_read_log_acpi(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_read_log_acpi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584862880,
      "name": "tpm_read_log_acpi",
      "external": true,
      "loc": "drivers/char/tpm/tpm_acpi.c:49",
      "file": "drivers/char/tpm/tpm_acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm1_eventlog.c:tpm_bios_log_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584862880,
      "name": "tpm_read_log_acpi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 322
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
int tpm_read_log_acpi(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_read_log_acpi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585281840,
      "name": "tpm_read_log_acpi",
      "external": true,
      "loc": "drivers/char/tpm/tpm_acpi.c:49",
      "file": "drivers/char/tpm/tpm_acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm1_eventlog.c:tpm_bios_log_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585281840,
      "name": "tpm_read_log_acpi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 322
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
int tpm_read_log_acpi(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_read_log_acpi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585518848,
      "name": "tpm_read_log_acpi",
      "external": true,
      "loc": "drivers/char/tpm/eventlog/acpi.c:50",
      "file": "drivers/char/tpm/eventlog/acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585518848,
      "name": "tpm_read_log_acpi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 325
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
int tpm_read_log_acpi(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_read_log_acpi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585642944,
      "name": "tpm_read_log_acpi",
      "external": true,
      "loc": "drivers/char/tpm/eventlog/acpi.c:50",
      "file": "drivers/char/tpm/eventlog/acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585642944,
      "name": "tpm_read_log_acpi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 325
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
int tpm_read_log_acpi(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_read_log_acpi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm_read_log_acpi",
      "external": true,
      "loc": "drivers/char/tpm/eventlog/acpi.c:45",
      "file": "drivers/char/tpm/eventlog/acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585867551,
      "name": "tpm_read_log_acpi.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071585867248,
      "name": "tpm_read_log_acpi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 303
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int tpm_read_log_acpi(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_read_log_acpi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm_read_log_acpi",
      "external": true,
      "loc": "drivers/char/tpm/eventlog/acpi.c:45",
      "file": "drivers/char/tpm/eventlog/acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586010111,
      "name": "tpm_read_log_acpi.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071586009808,
      "name": "tpm_read_log_acpi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 303
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int tpm_read_log_acpi(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_read_log_acpi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm_read_log_acpi",
      "external": true,
      "loc": "drivers/char/tpm/eventlog/acpi.c:45",
      "file": "drivers/char/tpm/eventlog/acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586748148,
      "name": "tpm_read_log_acpi.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071586747840,
      "name": "tpm_read_log_acpi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int tpm_read_log_acpi(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_read_log_acpi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm_read_log_acpi",
      "external": true,
      "loc": "drivers/char/tpm/eventlog/acpi.c:45",
      "file": "drivers/char/tpm/eventlog/acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591471270,
      "name": "tpm_read_log_acpi.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071586841824,
      "name": "tpm_read_log_acpi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 392
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int tpm_read_log_acpi(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_read_log_acpi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm_read_log_acpi",
      "external": true,
      "loc": "drivers/char/tpm/eventlog/acpi.c:66",
      "file": "drivers/char/tpm/eventlog/acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591412601,
      "name": "tpm_read_log_acpi.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071586722240,
      "name": "tpm_read_log_acpi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 462
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int tpm_read_log_acpi(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_read_log_acpi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm_read_log_acpi",
      "external": true,
      "loc": "drivers/char/tpm/eventlog/acpi.c:66",
      "file": "drivers/char/tpm/eventlog/acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592464553,
      "name": "tpm_read_log_acpi.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071587273696,
      "name": "tpm_read_log_acpi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 462
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int tpm_read_log_acpi(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_read_log_acpi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm_read_log_acpi",
      "external": true,
      "loc": "drivers/char/tpm/eventlog/acpi.c:66",
      "file": "drivers/char/tpm/eventlog/acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594334568,
      "name": "tpm_read_log_acpi.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071588584288,
      "name": "tpm_read_log_acpi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 490
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
int tpm_read_log_acpi(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_read_log_acpi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590039952,
      "name": "tpm_read_log_acpi",
      "external": true,
      "loc": "drivers/char/tpm/eventlog/acpi.c:66",
      "file": "drivers/char/tpm/eventlog/acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590039952,
      "name": "tpm_read_log_acpi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 565
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
int tpm_read_log_acpi(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_read_log_acpi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590349312,
      "name": "tpm_read_log_acpi",
      "external": true,
      "loc": "drivers/char/tpm/eventlog/acpi.c:67",
      "file": "drivers/char/tpm/eventlog/acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590349312,
      "name": "tpm_read_log_acpi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 575
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
int tpm_read_log_acpi(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_read_log_acpi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590690848,
      "name": "tpm_read_log_acpi",
      "external": true,
      "loc": "drivers/char/tpm/eventlog/acpi.c:67",
      "file": "drivers/char/tpm/eventlog/acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590690848,
      "name": "tpm_read_log_acpi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 575
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
int tpm_read_log_acpi(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_read_log_acpi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498807240,
      "name": "tpm_read_log_acpi",
      "external": true,
      "loc": "drivers/char/tpm/eventlog/acpi.c:45",
      "file": "drivers/char/tpm/eventlog/acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498807240,
      "name": "tpm_read_log_acpi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "tpm_read_log_acpi",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm_read_log_acpi",
      "external": false,
      "loc": "drivers/char/tpm/eventlog/common.h:13",
      "file": "drivers/char/tpm/eventlog/common.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "tpm_read_log_acpi",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm_read_log_acpi",
      "external": false,
      "loc": "drivers/char/tpm/eventlog/common.h:13",
      "file": "drivers/char/tpm/eventlog/common.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "tpm_read_log_acpi",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm_read_log_acpi",
      "external": false,
      "loc": "drivers/char/tpm/eventlog/common.h:13",
      "file": "drivers/char/tpm/eventlog/common.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int tpm_read_log_acpi(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_read_log_acpi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm_read_log_acpi",
      "external": true,
      "loc": "drivers/char/tpm/eventlog/acpi.c:45",
      "file": "drivers/char/tpm/eventlog/acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585771087,
      "name": "tpm_read_log_acpi.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071585770784,
      "name": "tpm_read_log_acpi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 303
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int tpm_read_log_acpi(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_read_log_acpi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm_read_log_acpi",
      "external": true,
      "loc": "drivers/char/tpm/eventlog/acpi.c:45",
      "file": "drivers/char/tpm/eventlog/acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585630271,
      "name": "tpm_read_log_acpi.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071585629968,
      "name": "tpm_read_log_acpi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 303
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int tpm_read_log_acpi(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_read_log_acpi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm_read_log_acpi",
      "external": true,
      "loc": "drivers/char/tpm/eventlog/acpi.c:45",
      "file": "drivers/char/tpm/eventlog/acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585960127,
      "name": "tpm_read_log_acpi.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071585959824,
      "name": "tpm_read_log_acpi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 303
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int tpm_read_log_acpi(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_read_log_acpi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm_read_log_acpi",
      "external": true,
      "loc": "drivers/char/tpm/eventlog/acpi.c:45",
      "file": "drivers/char/tpm/eventlog/acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586067871,
      "name": "tpm_read_log_acpi.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071586067568,
      "name": "tpm_read_log_acpi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 303
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
int tpm_read_log_acpi(struct tpm_chip * chip)
```
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int tpm_read_log_acpi(struct tpm_chip * chip)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int tpm_read_log_acpi(struct tpm_chip * chip)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int tpm_read_log_acpi(struct tpm_chip * chip)
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
