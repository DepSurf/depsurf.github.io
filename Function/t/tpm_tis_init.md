# Function: <code>tpm_tis_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int tpm_tis_init(struct device * dev, struct tpm_info * tpm_info, acpi_handle acpi_dev_handle)
```

```json
{
  "name": "tpm_tis_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584256224,
      "name": "tpm_tis_init",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis.c:665",
      "file": "drivers/char/tpm/tpm_tis.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_acpi_init",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584256224,
      "name": "tpm_tis_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1844
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
int tpm_tis_init(struct device * dev, struct tpm_info * tpm_info, acpi_handle acpi_dev_handle)
```

```json
{
  "name": "tpm_tis_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584599088,
      "name": "tpm_tis_init",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis.c:142",
      "file": "drivers/char/tpm/tpm_tis.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_acpi_init",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584599088,
      "name": "tpm_tis_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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
int tpm_tis_init(struct device * dev, struct tpm_info * tpm_info, acpi_handle acpi_dev_handle)
```

```json
{
  "name": "tpm_tis_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584780528,
      "name": "tpm_tis_init",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis.c:144",
      "file": "drivers/char/tpm/tpm_tis.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_acpi_init",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584780528,
      "name": "tpm_tis_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tpm_tis_init",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584870785,
      "name": "tpm_tis_init",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis.c:287",
      "file": "drivers/char/tpm/tpm_tis.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init"
      ],
      "caller_func": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584870080,
      "name": "tpm_tis_init.part.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tpm_tis_init",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585290113,
      "name": "tpm_tis_init",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis.c:193",
      "file": "drivers/char/tpm/tpm_tis.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init"
      ],
      "caller_func": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585289376,
      "name": "tpm_tis_init.part.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 297
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tpm_tis_init",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585528465,
      "name": "tpm_tis_init",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis.c:193",
      "file": "drivers/char/tpm/tpm_tis.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init"
      ],
      "caller_func": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585527744,
      "name": "tpm_tis_init.part.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tpm_tis_init",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585652577,
      "name": "tpm_tis_init",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis.c:193",
      "file": "drivers/char/tpm/tpm_tis.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init"
      ],
      "caller_func": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585651840,
      "name": "tpm_tis_init.part.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 289
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tpm_tis_init",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585877169,
      "name": "tpm_tis_init",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis.c:189",
      "file": "drivers/char/tpm/tpm_tis.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init"
      ],
      "caller_func": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585876416,
      "name": "tpm_tis_init.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tpm_tis_init",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586019729,
      "name": "tpm_tis_init",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis.c:189",
      "file": "drivers/char/tpm/tpm_tis.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init"
      ],
      "caller_func": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586018976,
      "name": "tpm_tis_init.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tpm_tis_init",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586758241,
      "name": "tpm_tis_init",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis.c:189",
      "file": "drivers/char/tpm/tpm_tis.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init"
      ],
      "caller_func": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586757488,
      "name": "tpm_tis_init.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 311
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tpm_tis_init",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586849809,
      "name": "tpm_tis_init",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis.c:212",
      "file": "drivers/char/tpm/tpm_tis.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init"
      ],
      "caller_func": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586849040,
      "name": "tpm_tis_init.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 283
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tpm_tis_init",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586730257,
      "name": "tpm_tis_init",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis.c:212",
      "file": "drivers/char/tpm/tpm_tis.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init"
      ],
      "caller_func": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586729472,
      "name": "tpm_tis_init.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tpm_tis_init",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587281985,
      "name": "tpm_tis_init",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis.c:212",
      "file": "drivers/char/tpm/tpm_tis.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init"
      ],
      "caller_func": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587281200,
      "name": "tpm_tis_init.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
    },
    {
      "addr": 18446744071592466648,
      "name": "tpm_tis_init.part.0.cold",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tpm_tis_init",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588594113,
      "name": "tpm_tis_init",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis.c:205",
      "file": "drivers/char/tpm/tpm_tis.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init"
      ],
      "caller_func": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588593296,
      "name": "tpm_tis_init.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 311
    },
    {
      "addr": 18446744071594336726,
      "name": "tpm_tis_init.part.0.cold",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tpm_tis_init",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590052577,
      "name": "tpm_tis_init",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis.c:206",
      "file": "drivers/char/tpm/tpm_tis.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init"
      ],
      "caller_func": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590051664,
      "name": "tpm_tis_init.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 311
    },
    {
      "addr": 18446744071596239907,
      "name": "tpm_tis_init.part.0.cold",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tpm_tis_init",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590363439,
      "name": "tpm_tis_init",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis.c:309",
      "file": "drivers/char/tpm/tpm_tis.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init"
      ],
      "caller_func": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590362528,
      "name": "tpm_tis_init.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 306
    },
    {
      "addr": 18446744071596767989,
      "name": "tpm_tis_init.part.0.cold",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tpm_tis_init",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590704975,
      "name": "tpm_tis_init",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis.c:221",
      "file": "drivers/char/tpm/tpm_tis.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init"
      ],
      "caller_func": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590704176,
      "name": "tpm_tis_init.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 320
    },
    {
      "addr": 18446744071597676650,
      "name": "tpm_tis_init.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "tpm_tis_init",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498818196,
      "name": "tpm_tis_init",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis.c:189",
      "file": "drivers/char/tpm/tpm_tis.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init"
      ],
      "caller_func": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498817424,
      "name": "tpm_tis_init.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 356
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
  "name": "tpm_tis_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3231428764,
      "name": "tpm_tis_init",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis.c:189",
      "file": "drivers/char/tpm/tpm_tis.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe"
      ],
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
  "name": "tpm_tis_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055292015108,
      "name": "tpm_tis_init",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis.c:189",
      "file": "drivers/char/tpm/tpm_tis.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe"
      ],
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
  "name": "tpm_tis_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936276314868,
      "name": "tpm_tis_init",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis.c:189",
      "file": "drivers/char/tpm/tpm_tis.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe"
      ],
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tpm_tis_init",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585780705,
      "name": "tpm_tis_init",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis.c:189",
      "file": "drivers/char/tpm/tpm_tis.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init"
      ],
      "caller_func": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585779952,
      "name": "tpm_tis_init.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tpm_tis_init",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585639889,
      "name": "tpm_tis_init",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis.c:189",
      "file": "drivers/char/tpm/tpm_tis.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init"
      ],
      "caller_func": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585639136,
      "name": "tpm_tis_init.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tpm_tis_init",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585969745,
      "name": "tpm_tis_init",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis.c:189",
      "file": "drivers/char/tpm/tpm_tis.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init"
      ],
      "caller_func": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585968992,
      "name": "tpm_tis_init.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tpm_tis_init",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586077473,
      "name": "tpm_tis_init",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis.c:189",
      "file": "drivers/char/tpm/tpm_tis.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init"
      ],
      "caller_func": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586076720,
      "name": "tpm_tis_init.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
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
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
int tpm_tis_init(struct device * dev, struct tpm_info * tpm_info, acpi_handle acpi_dev_handle)
```
</details>
</li>
</ul>
