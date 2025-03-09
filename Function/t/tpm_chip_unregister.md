# Function: <code>tpm_chip_unregister</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void tpm_chip_unregister(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_chip_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584241712,
      "name": "tpm_chip_unregister",
      "external": true,
      "loc": "drivers/char/tpm/tpm-chip.c:270",
      "file": "drivers/char/tpm/tpm-chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_remove",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_acpi_remove",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584241712,
      "name": "tpm_chip_unregister.part.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
    },
    {
      "addr": 18446744071584241888,
      "name": "tpm_chip_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void tpm_chip_unregister(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_chip_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584581936,
      "name": "tpm_chip_unregister",
      "external": true,
      "loc": "drivers/char/tpm/tpm-chip.c:403",
      "file": "drivers/char/tpm/tpm-chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_remove",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_acpi_remove",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584581936,
      "name": "tpm_chip_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 213
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
void tpm_chip_unregister(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_chip_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584762864,
      "name": "tpm_chip_unregister",
      "external": true,
      "loc": "drivers/char/tpm/tpm-chip.c:383",
      "file": "drivers/char/tpm/tpm-chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_remove",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_acpi_remove",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584762864,
      "name": "tpm_chip_unregister",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void tpm_chip_unregister(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_chip_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584844640,
      "name": "tpm_chip_unregister",
      "external": true,
      "loc": "drivers/char/tpm/tpm-chip.c:458",
      "file": "drivers/char/tpm/tpm-chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_remove",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584844640,
      "name": "tpm_chip_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
void tpm_chip_unregister(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_chip_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585265280,
      "name": "tpm_chip_unregister",
      "external": true,
      "loc": "drivers/char/tpm/tpm-chip.c:451",
      "file": "drivers/char/tpm/tpm-chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_remove",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585265280,
      "name": "tpm_chip_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
void tpm_chip_unregister(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_chip_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585502256,
      "name": "tpm_chip_unregister",
      "external": true,
      "loc": "drivers/char/tpm/tpm-chip.c:486",
      "file": "drivers/char/tpm/tpm-chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_remove",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_remove",
        "drivers/char/tpm/tpm_crb.c:crb_acpi_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585502256,
      "name": "tpm_chip_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
void tpm_chip_unregister(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_chip_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585616896,
      "name": "tpm_chip_unregister",
      "external": true,
      "loc": "drivers/char/tpm/tpm-chip.c:505",
      "file": "drivers/char/tpm/tpm-chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_remove",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_remove",
        "drivers/char/tpm/tpm_crb.c:crb_acpi_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585616896,
      "name": "tpm_chip_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
void tpm_chip_unregister(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_chip_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585837216,
      "name": "tpm_chip_unregister",
      "external": true,
      "loc": "drivers/char/tpm/tpm-chip.c:647",
      "file": "drivers/char/tpm/tpm-chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_remove",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_remove",
        "drivers/char/tpm/tpm_crb.c:crb_acpi_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585837216,
      "name": "tpm_chip_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
void tpm_chip_unregister(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_chip_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585979872,
      "name": "tpm_chip_unregister",
      "external": true,
      "loc": "drivers/char/tpm/tpm-chip.c:644",
      "file": "drivers/char/tpm/tpm-chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_remove",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_remove",
        "drivers/char/tpm/tpm_crb.c:crb_acpi_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585979872,
      "name": "tpm_chip_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
void tpm_chip_unregister(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_chip_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586721760,
      "name": "tpm_chip_unregister",
      "external": true,
      "loc": "drivers/char/tpm/tpm-chip.c:637",
      "file": "drivers/char/tpm/tpm-chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_remove",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_remove",
        "drivers/char/tpm/tpm_crb.c:crb_acpi_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586721760,
      "name": "tpm_chip_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 295
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
void tpm_chip_unregister(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_chip_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586817584,
      "name": "tpm_chip_unregister",
      "external": true,
      "loc": "drivers/char/tpm/tpm-chip.c:637",
      "file": "drivers/char/tpm/tpm-chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_remove",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_remove",
        "drivers/char/tpm/tpm_crb.c:crb_acpi_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586817584,
      "name": "tpm_chip_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 295
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
void tpm_chip_unregister(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_chip_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586697488,
      "name": "tpm_chip_unregister",
      "external": true,
      "loc": "drivers/char/tpm/tpm-chip.c:637",
      "file": "drivers/char/tpm/tpm-chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_remove",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_remove",
        "drivers/char/tpm/tpm_crb.c:crb_acpi_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586697488,
      "name": "tpm_chip_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 295
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
void tpm_chip_unregister(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_chip_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587246816,
      "name": "tpm_chip_unregister",
      "external": true,
      "loc": "drivers/char/tpm/tpm-chip.c:645",
      "file": "drivers/char/tpm/tpm-chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_remove",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_remove",
        "drivers/char/tpm/tpm_crb.c:crb_acpi_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587246816,
      "name": "tpm_chip_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 305
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
void tpm_chip_unregister(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_chip_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588555600,
      "name": "tpm_chip_unregister",
      "external": true,
      "loc": "drivers/char/tpm/tpm-chip.c:620",
      "file": "drivers/char/tpm/tpm-chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_remove",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_remove",
        "drivers/char/tpm/tpm_crb.c:crb_acpi_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588555600,
      "name": "tpm_chip_unregister",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void tpm_chip_unregister(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_chip_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590007648,
      "name": "tpm_chip_unregister",
      "external": true,
      "loc": "drivers/char/tpm/tpm-chip.c:683",
      "file": "drivers/char/tpm/tpm-chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_remove",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_remove",
        "drivers/char/tpm/tpm_crb.c:crb_acpi_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590007648,
      "name": "tpm_chip_unregister",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void tpm_chip_unregister(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_chip_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590317232,
      "name": "tpm_chip_unregister",
      "external": true,
      "loc": "drivers/char/tpm/tpm-chip.c:664",
      "file": "drivers/char/tpm/tpm-chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_remove",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_remove",
        "drivers/char/tpm/tpm_crb.c:crb_acpi_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590317232,
      "name": "tpm_chip_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 245
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
void tpm_chip_unregister(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_chip_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590658704,
      "name": "tpm_chip_unregister",
      "external": true,
      "loc": "drivers/char/tpm/tpm-chip.c:669",
      "file": "drivers/char/tpm/tpm-chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_remove",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_remove",
        "drivers/char/tpm/tpm_crb.c:crb_acpi_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590658704,
      "name": "tpm_chip_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 245
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
void tpm_chip_unregister(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_chip_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498774712,
      "name": "tpm_chip_unregister",
      "external": true,
      "loc": "drivers/char/tpm/tpm-chip.c:644",
      "file": "drivers/char/tpm/tpm-chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_remove",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_remove",
        "drivers/char/tpm/tpm_crb.c:crb_acpi_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498774712,
      "name": "tpm_chip_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
void tpm_chip_unregister(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_chip_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231390464,
      "name": "tpm_chip_unregister",
      "external": true,
      "loc": "drivers/char/tpm/tpm-chip.c:644",
      "file": "drivers/char/tpm/tpm-chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231390464,
      "name": "tpm_chip_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
void tpm_chip_unregister(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_chip_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291963888,
      "name": "tpm_chip_unregister",
      "external": true,
      "loc": "drivers/char/tpm/tpm-chip.c:644",
      "file": "drivers/char/tpm/tpm-chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_remove",
        "drivers/char/tpm/tpm_i2c_atmel.c:i2c_atmel_remove",
        "drivers/char/tpm/tpm_i2c_infineon.c:tpm_tis_i2c_remove",
        "drivers/char/tpm/tpm_i2c_nuvoton.c:i2c_nuvoton_remove",
        "drivers/char/tpm/tpm_ibmvtpm.c:tpm_ibmvtpm_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291963888,
      "name": "tpm_chip_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
void tpm_chip_unregister(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_chip_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276269194,
      "name": "tpm_chip_unregister",
      "external": true,
      "loc": "drivers/char/tpm/tpm-chip.c:644",
      "file": "drivers/char/tpm/tpm-chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276269194,
      "name": "tpm_chip_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 242
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
void tpm_chip_unregister(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_chip_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585740848,
      "name": "tpm_chip_unregister",
      "external": true,
      "loc": "drivers/char/tpm/tpm-chip.c:644",
      "file": "drivers/char/tpm/tpm-chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_remove",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_remove",
        "drivers/char/tpm/tpm_crb.c:crb_acpi_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585740848,
      "name": "tpm_chip_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
void tpm_chip_unregister(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_chip_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585600032,
      "name": "tpm_chip_unregister",
      "external": true,
      "loc": "drivers/char/tpm/tpm-chip.c:644",
      "file": "drivers/char/tpm/tpm-chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_remove",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_remove",
        "drivers/char/tpm/tpm_crb.c:crb_acpi_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585600032,
      "name": "tpm_chip_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
void tpm_chip_unregister(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_chip_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585929888,
      "name": "tpm_chip_unregister",
      "external": true,
      "loc": "drivers/char/tpm/tpm-chip.c:644",
      "file": "drivers/char/tpm/tpm-chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_remove",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_remove",
        "drivers/char/tpm/tpm_crb.c:crb_acpi_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585929888,
      "name": "tpm_chip_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
void tpm_chip_unregister(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_chip_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586037872,
      "name": "tpm_chip_unregister",
      "external": true,
      "loc": "drivers/char/tpm/tpm-chip.c:644",
      "file": "drivers/char/tpm/tpm-chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_remove",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_remove",
        "drivers/char/tpm/tpm_crb.c:crb_acpi_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586037872,
      "name": "tpm_chip_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
