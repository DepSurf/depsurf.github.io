# Function: <code>check_acpi_tpm2</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int check_acpi_tpm2(struct device * dev)
```

```json
{
  "name": "check_acpi_tpm2",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584869184,
      "name": "check_acpi_tpm2",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis.c:103",
      "file": "drivers/char/tpm/tpm_tis.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584869184,
      "name": "check_acpi_tpm2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
int check_acpi_tpm2(struct device * dev)
```

```json
{
  "name": "check_acpi_tpm2",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585289216,
      "name": "check_acpi_tpm2",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis.c:104",
      "file": "drivers/char/tpm/tpm_tis.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585289216,
      "name": "check_acpi_tpm2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
int check_acpi_tpm2(struct device * dev)
```

```json
{
  "name": "check_acpi_tpm2",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585527584,
      "name": "check_acpi_tpm2",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis.c:104",
      "file": "drivers/char/tpm/tpm_tis.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585527584,
      "name": "check_acpi_tpm2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
int check_acpi_tpm2(struct device * dev)
```

```json
{
  "name": "check_acpi_tpm2",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585651680,
      "name": "check_acpi_tpm2",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis.c:104",
      "file": "drivers/char/tpm/tpm_tis.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585651680,
      "name": "check_acpi_tpm2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
int check_acpi_tpm2(struct device * dev)
```

```json
{
  "name": "check_acpi_tpm2",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_acpi_tpm2",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis.c:100",
      "file": "drivers/char/tpm/tpm_tis.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585876256,
      "name": "check_acpi_tpm2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
    },
    {
      "addr": 18446744071585877223,
      "name": "check_acpi_tpm2.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
int check_acpi_tpm2(struct device * dev)
```

```json
{
  "name": "check_acpi_tpm2",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_acpi_tpm2",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis.c:100",
      "file": "drivers/char/tpm/tpm_tis.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586018816,
      "name": "check_acpi_tpm2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
    },
    {
      "addr": 18446744071586019783,
      "name": "check_acpi_tpm2.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
int check_acpi_tpm2(struct device * dev)
```

```json
{
  "name": "check_acpi_tpm2",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_acpi_tpm2",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis.c:100",
      "file": "drivers/char/tpm/tpm_tis.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586757344,
      "name": "check_acpi_tpm2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    },
    {
      "addr": 18446744071586758295,
      "name": "check_acpi_tpm2.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
int check_acpi_tpm2(struct device * dev)
```

```json
{
  "name": "check_acpi_tpm2",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_acpi_tpm2",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis.c:123",
      "file": "drivers/char/tpm/tpm_tis.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586848896,
      "name": "check_acpi_tpm2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    },
    {
      "addr": 18446744071591473314,
      "name": "check_acpi_tpm2.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
int check_acpi_tpm2(struct device * dev)
```

```json
{
  "name": "check_acpi_tpm2",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_acpi_tpm2",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis.c:123",
      "file": "drivers/char/tpm/tpm_tis.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586729328,
      "name": "check_acpi_tpm2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    },
    {
      "addr": 18446744071591414558,
      "name": "check_acpi_tpm2.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
int check_acpi_tpm2(struct device * dev)
```

```json
{
  "name": "check_acpi_tpm2",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_acpi_tpm2",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis.c:123",
      "file": "drivers/char/tpm/tpm_tis.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587281056,
      "name": "check_acpi_tpm2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    },
    {
      "addr": 18446744071592466623,
      "name": "check_acpi_tpm2.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
int check_acpi_tpm2(struct device * dev)
```

```json
{
  "name": "check_acpi_tpm2",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_acpi_tpm2",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis.c:123",
      "file": "drivers/char/tpm/tpm_tis.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588593120,
      "name": "check_acpi_tpm2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
    },
    {
      "addr": 18446744071594336701,
      "name": "check_acpi_tpm2.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
int check_acpi_tpm2(struct device * dev)
```

```json
{
  "name": "check_acpi_tpm2",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590051216,
      "name": "check_acpi_tpm2",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis.c:123",
      "file": "drivers/char/tpm/tpm_tis.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590051216,
      "name": "check_acpi_tpm2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
int check_acpi_tpm2(struct device * dev)
```

```json
{
  "name": "check_acpi_tpm2",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590362096,
      "name": "check_acpi_tpm2",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis.c:226",
      "file": "drivers/char/tpm/tpm_tis.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590362096,
      "name": "check_acpi_tpm2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
int check_acpi_tpm2(struct device * dev)
```

```json
{
  "name": "check_acpi_tpm2",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590703744,
      "name": "check_acpi_tpm2",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis.c:138",
      "file": "drivers/char/tpm/tpm_tis.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590703744,
      "name": "check_acpi_tpm2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
int check_acpi_tpm2(struct device * dev)
```

```json
{
  "name": "check_acpi_tpm2",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498817232,
      "name": "check_acpi_tpm2",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis.c:100",
      "file": "drivers/char/tpm/tpm_tis.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498817232,
      "name": "check_acpi_tpm2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
  "name": "check_acpi_tpm2",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "check_acpi_tpm2",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis.c:126",
      "file": "drivers/char/tpm/tpm_tis.c",
      "inline": "not declared, inlined",
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
  "name": "check_acpi_tpm2",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "check_acpi_tpm2",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis.c:126",
      "file": "drivers/char/tpm/tpm_tis.c",
      "inline": "not declared, inlined",
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
  "name": "check_acpi_tpm2",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "check_acpi_tpm2",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis.c:126",
      "file": "drivers/char/tpm/tpm_tis.c",
      "inline": "not declared, inlined",
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
int check_acpi_tpm2(struct device * dev)
```

```json
{
  "name": "check_acpi_tpm2",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_acpi_tpm2",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis.c:100",
      "file": "drivers/char/tpm/tpm_tis.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585779792,
      "name": "check_acpi_tpm2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
    },
    {
      "addr": 18446744071585780759,
      "name": "check_acpi_tpm2.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
int check_acpi_tpm2(struct device * dev)
```

```json
{
  "name": "check_acpi_tpm2",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_acpi_tpm2",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis.c:100",
      "file": "drivers/char/tpm/tpm_tis.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585638976,
      "name": "check_acpi_tpm2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
    },
    {
      "addr": 18446744071585639943,
      "name": "check_acpi_tpm2.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
int check_acpi_tpm2(struct device * dev)
```

```json
{
  "name": "check_acpi_tpm2",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_acpi_tpm2",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis.c:100",
      "file": "drivers/char/tpm/tpm_tis.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585968832,
      "name": "check_acpi_tpm2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
    },
    {
      "addr": 18446744071585969799,
      "name": "check_acpi_tpm2.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
int check_acpi_tpm2(struct device * dev)
```

```json
{
  "name": "check_acpi_tpm2",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_acpi_tpm2",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis.c:100",
      "file": "drivers/char/tpm/tpm_tis.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586076560,
      "name": "check_acpi_tpm2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
    },
    {
      "addr": 18446744071586077527,
      "name": "check_acpi_tpm2.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int check_acpi_tpm2(struct device * dev)
```
</details>
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
int check_acpi_tpm2(struct device * dev)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int check_acpi_tpm2(struct device * dev)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int check_acpi_tpm2(struct device * dev)
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
