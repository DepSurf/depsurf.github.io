# Function: <code>crb_map_io</code>

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
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "crb_map_io",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585530118,
      "name": "crb_map_io",
      "external": false,
      "loc": "drivers/char/tpm/tpm_crb.c:484",
      "file": "drivers/char/tpm/tpm_crb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_crb.c:crb_acpi_add"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "crb_map_io",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585654617,
      "name": "crb_map_io",
      "external": false,
      "loc": "drivers/char/tpm/tpm_crb.c:494",
      "file": "drivers/char/tpm/tpm_crb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_crb.c:crb_acpi_add"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int crb_map_io(struct acpi_device * device, struct crb_priv * priv, struct acpi_table_tpm2 * buf)
```

```json
{
  "name": "crb_map_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "crb_map_io",
      "external": false,
      "loc": "drivers/char/tpm/tpm_crb.c:490",
      "file": "drivers/char/tpm/tpm_crb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_crb.c:crb_acpi_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585878768,
      "name": "crb_map_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 825
    },
    {
      "addr": 18446744071585880097,
      "name": "crb_map_io.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
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
int crb_map_io(struct acpi_device * device, struct crb_priv * priv, struct acpi_table_tpm2 * buf)
```

```json
{
  "name": "crb_map_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "crb_map_io",
      "external": false,
      "loc": "drivers/char/tpm/tpm_crb.c:490",
      "file": "drivers/char/tpm/tpm_crb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_crb.c:crb_acpi_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586021328,
      "name": "crb_map_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 825
    },
    {
      "addr": 18446744071586022657,
      "name": "crb_map_io.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
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
int crb_map_io(struct acpi_device * device, struct crb_priv * priv, struct acpi_table_tpm2 * buf)
```

```json
{
  "name": "crb_map_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "crb_map_io",
      "external": false,
      "loc": "drivers/char/tpm/tpm_crb.c:502",
      "file": "drivers/char/tpm/tpm_crb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_crb.c:crb_acpi_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586759936,
      "name": "crb_map_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1266
    },
    {
      "addr": 18446744071586761720,
      "name": "crb_map_io.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 390
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
int crb_map_io(struct acpi_device * device, struct crb_priv * priv, struct acpi_table_tpm2 * buf)
```

```json
{
  "name": "crb_map_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "crb_map_io",
      "external": false,
      "loc": "drivers/char/tpm/tpm_crb.c:502",
      "file": "drivers/char/tpm/tpm_crb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_crb.c:crb_acpi_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586851472,
      "name": "crb_map_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1296
    },
    {
      "addr": 18446744071591473596,
      "name": "crb_map_io.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
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
int crb_map_io(struct acpi_device * device, struct crb_priv * priv, struct acpi_table_tpm2 * buf)
```

```json
{
  "name": "crb_map_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "crb_map_io",
      "external": false,
      "loc": "drivers/char/tpm/tpm_crb.c:502",
      "file": "drivers/char/tpm/tpm_crb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_crb.c:crb_acpi_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586731920,
      "name": "crb_map_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1303
    },
    {
      "addr": 18446744071591414843,
      "name": "crb_map_io.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 376
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
int crb_map_io(struct acpi_device * device, struct crb_priv * priv, struct acpi_table_tpm2 * buf)
```

```json
{
  "name": "crb_map_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "crb_map_io",
      "external": false,
      "loc": "drivers/char/tpm/tpm_crb.c:502",
      "file": "drivers/char/tpm/tpm_crb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_crb.c:crb_acpi_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587283664,
      "name": "crb_map_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2150
    },
    {
      "addr": 18446744071592466929,
      "name": "crb_map_io.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 384
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
int crb_map_io(struct acpi_device * device, struct crb_priv * priv, struct acpi_table_tpm2 * buf)
```

```json
{
  "name": "crb_map_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "crb_map_io",
      "external": false,
      "loc": "drivers/char/tpm/tpm_crb.c:502",
      "file": "drivers/char/tpm/tpm_crb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_crb.c:crb_acpi_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588596096,
      "name": "crb_map_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2072
    },
    {
      "addr": 18446744071594337038,
      "name": "crb_map_io.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 369
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
int crb_map_io(struct acpi_device * device, struct crb_priv * priv, struct acpi_table_tpm2 * buf)
```

```json
{
  "name": "crb_map_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590054576,
      "name": "crb_map_io",
      "external": false,
      "loc": "drivers/char/tpm/tpm_crb.c:502",
      "file": "drivers/char/tpm/tpm_crb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_crb.c:crb_acpi_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590054576,
      "name": "crb_map_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2425
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
int crb_map_io(struct acpi_device * device, struct crb_priv * priv, struct acpi_table_tpm2 * buf)
```

```json
{
  "name": "crb_map_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590365616,
      "name": "crb_map_io",
      "external": false,
      "loc": "drivers/char/tpm/tpm_crb.c:548",
      "file": "drivers/char/tpm/tpm_crb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_crb.c:crb_acpi_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590365616,
      "name": "crb_map_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2454
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
int crb_map_io(struct acpi_device * device, struct crb_priv * priv, struct acpi_table_tpm2 * buf)
```

```json
{
  "name": "crb_map_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590707136,
      "name": "crb_map_io",
      "external": false,
      "loc": "drivers/char/tpm/tpm_crb.c:548",
      "file": "drivers/char/tpm/tpm_crb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_crb.c:crb_acpi_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590707136,
      "name": "crb_map_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2454
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
int crb_map_io(struct acpi_device * device, struct crb_priv * priv, struct acpi_table_tpm2 * buf)
```

```json
{
  "name": "crb_map_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498820560,
      "name": "crb_map_io",
      "external": false,
      "loc": "drivers/char/tpm/tpm_crb.c:490",
      "file": "drivers/char/tpm/tpm_crb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_crb.c:crb_acpi_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498820560,
      "name": "crb_map_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1008
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
int crb_map_io(struct acpi_device * device, struct crb_priv * priv, struct acpi_table_tpm2 * buf)
```

```json
{
  "name": "crb_map_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "crb_map_io",
      "external": false,
      "loc": "drivers/char/tpm/tpm_crb.c:490",
      "file": "drivers/char/tpm/tpm_crb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_crb.c:crb_acpi_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585782304,
      "name": "crb_map_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 825
    },
    {
      "addr": 18446744071585783633,
      "name": "crb_map_io.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
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
int crb_map_io(struct acpi_device * device, struct crb_priv * priv, struct acpi_table_tpm2 * buf)
```

```json
{
  "name": "crb_map_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "crb_map_io",
      "external": false,
      "loc": "drivers/char/tpm/tpm_crb.c:490",
      "file": "drivers/char/tpm/tpm_crb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_crb.c:crb_acpi_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585641488,
      "name": "crb_map_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 825
    },
    {
      "addr": 18446744071585642817,
      "name": "crb_map_io.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
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
int crb_map_io(struct acpi_device * device, struct crb_priv * priv, struct acpi_table_tpm2 * buf)
```

```json
{
  "name": "crb_map_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "crb_map_io",
      "external": false,
      "loc": "drivers/char/tpm/tpm_crb.c:490",
      "file": "drivers/char/tpm/tpm_crb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_crb.c:crb_acpi_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585971344,
      "name": "crb_map_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 825
    },
    {
      "addr": 18446744071585972673,
      "name": "crb_map_io.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
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
int crb_map_io(struct acpi_device * device, struct crb_priv * priv, struct acpi_table_tpm2 * buf)
```

```json
{
  "name": "crb_map_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "crb_map_io",
      "external": false,
      "loc": "drivers/char/tpm/tpm_crb.c:490",
      "file": "drivers/char/tpm/tpm_crb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_crb.c:crb_acpi_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586079072,
      "name": "crb_map_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 825
    },
    {
      "addr": 18446744071586080401,
      "name": "crb_map_io.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int crb_map_io(struct acpi_device * device, struct crb_priv * priv, struct acpi_table_tpm2 * buf)
```
</details>
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
int crb_map_io(struct acpi_device * device, struct crb_priv * priv, struct acpi_table_tpm2 * buf)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int crb_map_io(struct acpi_device * device, struct crb_priv * priv, struct acpi_table_tpm2 * buf)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int crb_map_io(struct acpi_device * device, struct crb_priv * priv, struct acpi_table_tpm2 * buf)
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
