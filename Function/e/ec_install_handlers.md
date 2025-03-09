# Function: <code>ec_install_handlers</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ec_install_handlers(struct acpi_ec * ec)
```

```json
{
  "name": "ec_install_handlers",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586136168,
      "name": "ec_install_handlers",
      "external": false,
      "loc": "drivers/acpi/ec.c:1286",
      "file": "drivers/acpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_add",
        "drivers/acpi/ec.c:acpi_boot_ec_enable",
        "drivers/acpi/ec.c:acpi_ec_ecdt_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586136168,
      "name": "ec_install_handlers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
int ec_install_handlers(struct acpi_ec * ec)
```

```json
{
  "name": "ec_install_handlers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586549800,
      "name": "ec_install_handlers",
      "external": false,
      "loc": "drivers/acpi/ec.c:1293",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_ecdt_probe",
        "drivers/acpi/ec.c:acpi_ec_dsdt_probe",
        "drivers/acpi/ec.c:acpi_ec_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586549800,
      "name": "ec_install_handlers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
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
int ec_install_handlers(struct acpi_ec * ec, bool handle_events)
```

```json
{
  "name": "ec_install_handlers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584044915,
      "name": "ec_install_handlers",
      "external": false,
      "loc": "drivers/acpi/ec.c:1386",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584044915,
      "name": "ec_install_handlers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
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
int ec_install_handlers(struct acpi_ec * ec, bool handle_events)
```

```json
{
  "name": "ec_install_handlers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584102736,
      "name": "ec_install_handlers",
      "external": false,
      "loc": "drivers/acpi/ec.c:1409",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584102736,
      "name": "ec_install_handlers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 510
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
int ec_install_handlers(struct acpi_ec * ec, bool handle_events)
```

```json
{
  "name": "ec_install_handlers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584374192,
      "name": "ec_install_handlers",
      "external": false,
      "loc": "drivers/acpi/ec.c:1411",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584374192,
      "name": "ec_install_handlers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 516
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
int ec_install_handlers(struct acpi_ec * ec, bool handle_events)
```

```json
{
  "name": "ec_install_handlers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ec_install_handlers",
      "external": false,
      "loc": "drivers/acpi/ec.c:1417",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584592464,
      "name": "ec_install_handlers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 401
    },
    {
      "addr": 18446744071584597072,
      "name": "ec_install_handlers.cold.32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int ec_install_handlers(struct acpi_ec * ec, bool handle_events)
```

```json
{
  "name": "ec_install_handlers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ec_install_handlers",
      "external": false,
      "loc": "drivers/acpi/ec.c:1429",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584692800,
      "name": "ec_install_handlers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 401
    },
    {
      "addr": 18446744071584694576,
      "name": "ec_install_handlers.cold.31",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
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
int ec_install_handlers(struct acpi_ec * ec, bool handle_events)
```

```json
{
  "name": "ec_install_handlers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ec_install_handlers",
      "external": false,
      "loc": "drivers/acpi/ec.c:1443",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_ecdt_probe",
        "drivers/acpi/ec.c:acpi_ec_dsdt_probe",
        "drivers/acpi/ec.c:acpi_ec_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584893744,
      "name": "ec_install_handlers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 413
    },
    {
      "addr": 18446744071584895402,
      "name": "ec_install_handlers.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
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
int ec_install_handlers(struct acpi_ec * ec, bool handle_events)
```

```json
{
  "name": "ec_install_handlers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ec_install_handlers",
      "external": false,
      "loc": "drivers/acpi/ec.c:1417",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_ecdt_probe",
        "drivers/acpi/ec.c:acpi_ec_dsdt_probe",
        "drivers/acpi/ec.c:acpi_ec_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585029488,
      "name": "ec_install_handlers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 413
    },
    {
      "addr": 18446744071585031128,
      "name": "ec_install_handlers.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
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
int ec_install_handlers(struct acpi_ec * ec, struct acpi_device * device)
```

```json
{
  "name": "ec_install_handlers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585730448,
      "name": "ec_install_handlers",
      "external": false,
      "loc": "drivers/acpi/ec.c:1454",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585730448,
      "name": "ec_install_handlers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 654
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
int ec_install_handlers(struct acpi_ec * ec, struct acpi_device * device)
```

```json
{
  "name": "ec_install_handlers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585852608,
      "name": "ec_install_handlers",
      "external": false,
      "loc": "drivers/acpi/ec.c:1441",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585852608,
      "name": "ec_install_handlers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 658
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
int ec_install_handlers(struct acpi_ec * ec, struct acpi_device * device)
```

```json
{
  "name": "ec_install_handlers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585731280,
      "name": "ec_install_handlers",
      "external": false,
      "loc": "drivers/acpi/ec.c:1442",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585731280,
      "name": "ec_install_handlers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 658
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
int ec_install_handlers(struct acpi_ec * ec, struct acpi_device * device)
```

```json
{
  "name": "ec_install_handlers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ec_install_handlers",
      "external": false,
      "loc": "drivers/acpi/ec.c:1459",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586213248,
      "name": "ec_install_handlers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 621
    },
    {
      "addr": 18446744071592409744,
      "name": "ec_install_handlers.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
int ec_install_handlers(struct acpi_ec * ec, struct acpi_device * device)
```

```json
{
  "name": "ec_install_handlers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ec_install_handlers",
      "external": false,
      "loc": "drivers/acpi/ec.c:1465",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587450576,
      "name": "ec_install_handlers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 583
    },
    {
      "addr": 18446744071594276357,
      "name": "ec_install_handlers.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int ec_install_handlers(struct acpi_ec * ec, struct acpi_device * device, bool call_reg)
```

```json
{
  "name": "ec_install_handlers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ec_install_handlers",
      "external": false,
      "loc": "drivers/acpi/ec.c:1463",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_ecdt_probe",
        "drivers/acpi/ec.c:acpi_ec_dsdt_probe",
        "drivers/acpi/ec.c:acpi_ec_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588712416,
      "name": "ec_install_handlers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 701
    },
    {
      "addr": 18446744071596219145,
      "name": "ec_install_handlers.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int ec_install_handlers(struct acpi_ec * ec, struct acpi_device * device, bool call_reg)
```

```json
{
  "name": "ec_install_handlers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ec_install_handlers",
      "external": false,
      "loc": "drivers/acpi/ec.c:1482",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_ecdt_probe",
        "drivers/acpi/ec.c:acpi_ec_dsdt_probe",
        "drivers/acpi/ec.c:acpi_ec_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589000656,
      "name": "ec_install_handlers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 693
    },
    {
      "addr": 18446744071596745741,
      "name": "ec_install_handlers.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int ec_install_handlers(struct acpi_ec * ec, struct acpi_device * device, bool call_reg)
```

```json
{
  "name": "ec_install_handlers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ec_install_handlers",
      "external": false,
      "loc": "drivers/acpi/ec.c:1482",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_ecdt_probe",
        "drivers/acpi/ec.c:acpi_ec_dsdt_probe",
        "drivers/acpi/ec.c:acpi_ec_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589304960,
      "name": "ec_install_handlers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 693
    },
    {
      "addr": 18446744071597654389,
      "name": "ec_install_handlers.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int ec_install_handlers(struct acpi_ec * ec, bool handle_events)
```

```json
{
  "name": "ec_install_handlers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497441648,
      "name": "ec_install_handlers",
      "external": false,
      "loc": "drivers/acpi/ec.c:1417",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_ecdt_probe",
        "drivers/acpi/ec.c:acpi_ec_dsdt_probe",
        "drivers/acpi/ec.c:acpi_ec_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497441648,
      "name": "ec_install_handlers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int ec_install_handlers(struct acpi_ec * ec, bool handle_events)
```

```json
{
  "name": "ec_install_handlers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ec_install_handlers",
      "external": false,
      "loc": "drivers/acpi/ec.c:1417",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_ecdt_probe",
        "drivers/acpi/ec.c:acpi_ec_dsdt_probe",
        "drivers/acpi/ec.c:acpi_ec_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584971872,
      "name": "ec_install_handlers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 413
    },
    {
      "addr": 18446744071584973464,
      "name": "ec_install_handlers.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
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
int ec_install_handlers(struct acpi_ec * ec, bool handle_events)
```

```json
{
  "name": "ec_install_handlers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ec_install_handlers",
      "external": false,
      "loc": "drivers/acpi/ec.c:1417",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_ecdt_probe",
        "drivers/acpi/ec.c:acpi_ec_dsdt_probe",
        "drivers/acpi/ec.c:acpi_ec_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584880672,
      "name": "ec_install_handlers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 413
    },
    {
      "addr": 18446744071584882312,
      "name": "ec_install_handlers.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
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
int ec_install_handlers(struct acpi_ec * ec, bool handle_events)
```

```json
{
  "name": "ec_install_handlers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ec_install_handlers",
      "external": false,
      "loc": "drivers/acpi/ec.c:1417",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_ecdt_probe",
        "drivers/acpi/ec.c:acpi_ec_dsdt_probe",
        "drivers/acpi/ec.c:acpi_ec_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584981072,
      "name": "ec_install_handlers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 413
    },
    {
      "addr": 18446744071584982712,
      "name": "ec_install_handlers.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
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
int ec_install_handlers(struct acpi_ec * ec, bool handle_events)
```

```json
{
  "name": "ec_install_handlers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ec_install_handlers",
      "external": false,
      "loc": "drivers/acpi/ec.c:1417",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_ecdt_probe",
        "drivers/acpi/ec.c:acpi_ec_dsdt_probe",
        "drivers/acpi/ec.c:acpi_ec_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585087248,
      "name": "ec_install_handlers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 413
    },
    {
      "addr": 18446744071585088888,
      "name": "ec_install_handlers.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
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
<code>bool handle_events</code>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct acpi_device * device</code>
</li>
<li>
<b>Param removed. </b>
<code>bool handle_events</code>
</li>
</ul>
</details>
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
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool call_reg</code>
</li>
</ul>
</details>
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
int ec_install_handlers(struct acpi_ec * ec, bool handle_events)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int ec_install_handlers(struct acpi_ec * ec, bool handle_events)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int ec_install_handlers(struct acpi_ec * ec, bool handle_events)
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
