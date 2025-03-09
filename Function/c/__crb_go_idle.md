# Function: <code>__crb_go_idle</code>

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
  "name": "__crb_go_idle",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585530692,
      "name": "__crb_go_idle",
      "external": false,
      "loc": "drivers/char/tpm/tpm_crb.c:150",
      "file": "drivers/char/tpm/tpm_crb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_crb.c:crb_acpi_add",
        "drivers/char/tpm/tpm_crb.c:crb_go_idle"
      ],
      "caller_func": [
        "drivers/char/tpm/tpm_crb.c:crb_acpi_add",
        "drivers/char/tpm/tpm_crb.c:crb_go_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585529392,
      "name": "__crb_go_idle.isra.9.part.10",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
  "name": "__crb_go_idle",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585655222,
      "name": "__crb_go_idle",
      "external": false,
      "loc": "drivers/char/tpm/tpm_crb.c:150",
      "file": "drivers/char/tpm/tpm_crb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_crb.c:crb_acpi_add",
        "drivers/char/tpm/tpm_crb.c:crb_go_idle"
      ],
      "caller_func": [
        "drivers/char/tpm/tpm_crb.c:crb_acpi_add",
        "drivers/char/tpm/tpm_crb.c:crb_go_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585653888,
      "name": "__crb_go_idle.isra.9.part.10",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
  "name": "__crb_go_idle",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585879399,
      "name": "__crb_go_idle",
      "external": false,
      "loc": "drivers/char/tpm/tpm_crb.c:146",
      "file": "drivers/char/tpm/tpm_crb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_go_idle"
      ],
      "caller_func": [
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_go_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585878320,
      "name": "__crb_go_idle.isra.0.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    },
    {
      "addr": 18446744071585879997,
      "name": "__crb_go_idle.isra.0.part.0.cold",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__crb_go_idle",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586021959,
      "name": "__crb_go_idle",
      "external": false,
      "loc": "drivers/char/tpm/tpm_crb.c:146",
      "file": "drivers/char/tpm/tpm_crb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_go_idle"
      ],
      "caller_func": [
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_go_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586020880,
      "name": "__crb_go_idle.isra.0.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    },
    {
      "addr": 18446744071586022557,
      "name": "__crb_go_idle.isra.0.part.0.cold",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __crb_go_idle(struct device * dev, struct crb_priv * priv)
```

```json
{
  "name": "__crb_go_idle",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586759555,
      "name": "__crb_go_idle",
      "external": false,
      "loc": "drivers/char/tpm/tpm_crb.c:146",
      "file": "drivers/char/tpm/tpm_crb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_crb.c:crb_go_idle",
        "drivers/char/tpm/tpm_crb.c:crb_go_idle"
      ],
      "caller_func": [
        "drivers/char/tpm/tpm_crb.c:crb_map_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586759088,
      "name": "__crb_go_idle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071586761519,
      "name": "__crb_go_idle.cold",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __crb_go_idle(struct device * dev, struct crb_priv * priv)
```

```json
{
  "name": "__crb_go_idle",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586851091,
      "name": "__crb_go_idle",
      "external": false,
      "loc": "drivers/char/tpm/tpm_crb.c:146",
      "file": "drivers/char/tpm/tpm_crb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_crb.c:crb_go_idle",
        "drivers/char/tpm/tpm_crb.c:crb_go_idle"
      ],
      "caller_func": [
        "drivers/char/tpm/tpm_crb.c:crb_map_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586850624,
      "name": "__crb_go_idle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071591473395,
      "name": "__crb_go_idle.cold",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __crb_go_idle(struct device * dev, struct crb_priv * priv)
```

```json
{
  "name": "__crb_go_idle",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586731539,
      "name": "__crb_go_idle",
      "external": false,
      "loc": "drivers/char/tpm/tpm_crb.c:146",
      "file": "drivers/char/tpm/tpm_crb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_crb.c:crb_go_idle",
        "drivers/char/tpm/tpm_crb.c:crb_go_idle"
      ],
      "caller_func": [
        "drivers/char/tpm/tpm_crb.c:crb_map_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586731072,
      "name": "__crb_go_idle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
    },
    {
      "addr": 18446744071591414642,
      "name": "__crb_go_idle.cold",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __crb_go_idle(struct device * dev, struct crb_priv * priv)
```

```json
{
  "name": "__crb_go_idle",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587283283,
      "name": "__crb_go_idle",
      "external": false,
      "loc": "drivers/char/tpm/tpm_crb.c:146",
      "file": "drivers/char/tpm/tpm_crb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_crb.c:crb_go_idle",
        "drivers/char/tpm/tpm_crb.c:crb_go_idle"
      ],
      "caller_func": [
        "drivers/char/tpm/tpm_crb.c:crb_map_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587282816,
      "name": "__crb_go_idle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
    },
    {
      "addr": 18446744071592466728,
      "name": "__crb_go_idle.cold",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __crb_go_idle(struct device * dev, struct crb_priv * priv)
```

```json
{
  "name": "__crb_go_idle",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588596000,
      "name": "__crb_go_idle",
      "external": false,
      "loc": "drivers/char/tpm/tpm_crb.c:146",
      "file": "drivers/char/tpm/tpm_crb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_crb.c:crb_go_idle"
      ],
      "caller_func": [
        "drivers/char/tpm/tpm_crb.c:crb_map_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588595040,
      "name": "__crb_go_idle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
    },
    {
      "addr": 18446744071594336812,
      "name": "__crb_go_idle.cold",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __crb_go_idle(struct device * dev, struct crb_priv * priv)
```

```json
{
  "name": "__crb_go_idle",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590057824,
      "name": "__crb_go_idle",
      "external": false,
      "loc": "drivers/char/tpm/tpm_crb.c:146",
      "file": "drivers/char/tpm/tpm_crb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_crb.c:crb_go_idle"
      ],
      "caller_func": [
        "drivers/char/tpm/tpm_crb.c:crb_map_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590053664,
      "name": "__crb_go_idle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
int __crb_go_idle(struct device * dev, struct crb_priv * priv)
```

```json
{
  "name": "__crb_go_idle",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590368320,
      "name": "__crb_go_idle",
      "external": false,
      "loc": "drivers/char/tpm/tpm_crb.c:172",
      "file": "drivers/char/tpm/tpm_crb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_crb.c:crb_go_idle"
      ],
      "caller_func": [
        "drivers/char/tpm/tpm_crb.c:crb_map_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590364816,
      "name": "__crb_go_idle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
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
int __crb_go_idle(struct device * dev, struct crb_priv * priv)
```

```json
{
  "name": "__crb_go_idle",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590709840,
      "name": "__crb_go_idle",
      "external": false,
      "loc": "drivers/char/tpm/tpm_crb.c:172",
      "file": "drivers/char/tpm/tpm_crb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_crb.c:crb_go_idle"
      ],
      "caller_func": [
        "drivers/char/tpm/tpm_crb.c:crb_map_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590706336,
      "name": "__crb_go_idle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
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
  "name": "__crb_go_idle",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498821172,
      "name": "__crb_go_idle",
      "external": false,
      "loc": "drivers/char/tpm/tpm_crb.c:146",
      "file": "drivers/char/tpm/tpm_crb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_go_idle"
      ],
      "caller_func": [
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_go_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498819672,
      "name": "__crb_go_idle.isra.0.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__crb_go_idle",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585782935,
      "name": "__crb_go_idle",
      "external": false,
      "loc": "drivers/char/tpm/tpm_crb.c:146",
      "file": "drivers/char/tpm/tpm_crb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_go_idle"
      ],
      "caller_func": [
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_go_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585781856,
      "name": "__crb_go_idle.isra.0.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    },
    {
      "addr": 18446744071585783533,
      "name": "__crb_go_idle.isra.0.part.0.cold",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__crb_go_idle",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585642119,
      "name": "__crb_go_idle",
      "external": false,
      "loc": "drivers/char/tpm/tpm_crb.c:146",
      "file": "drivers/char/tpm/tpm_crb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_go_idle"
      ],
      "caller_func": [
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_go_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585641040,
      "name": "__crb_go_idle.isra.0.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    },
    {
      "addr": 18446744071585642717,
      "name": "__crb_go_idle.isra.0.part.0.cold",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__crb_go_idle",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585971975,
      "name": "__crb_go_idle",
      "external": false,
      "loc": "drivers/char/tpm/tpm_crb.c:146",
      "file": "drivers/char/tpm/tpm_crb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_go_idle"
      ],
      "caller_func": [
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_go_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585970896,
      "name": "__crb_go_idle.isra.0.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    },
    {
      "addr": 18446744071585972573,
      "name": "__crb_go_idle.isra.0.part.0.cold",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__crb_go_idle",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586079703,
      "name": "__crb_go_idle",
      "external": false,
      "loc": "drivers/char/tpm/tpm_crb.c:146",
      "file": "drivers/char/tpm/tpm_crb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_go_idle"
      ],
      "caller_func": [
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_go_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586078624,
      "name": "__crb_go_idle.isra.0.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    },
    {
      "addr": 18446744071586080301,
      "name": "__crb_go_idle.isra.0.part.0.cold",
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int __crb_go_idle(struct device * dev, struct crb_priv * priv)
```
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
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
