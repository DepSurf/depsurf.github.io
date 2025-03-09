# Function: <code>edac_mc_add_mc_with_groups</code>

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
int edac_mc_add_mc_with_groups(struct mem_ctl_info * mci, const struct attribute_group * * groups)
```

```json
{
  "name": "edac_mc_add_mc_with_groups",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586561360,
      "name": "edac_mc_add_mc_with_groups",
      "external": true,
      "loc": "drivers/edac/edac_mc.c:706",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586561360,
      "name": "edac_mc_add_mc_with_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 829
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
int edac_mc_add_mc_with_groups(struct mem_ctl_info * mci, const struct attribute_group * * groups)
```

```json
{
  "name": "edac_mc_add_mc_with_groups",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587028896,
      "name": "edac_mc_add_mc_with_groups",
      "external": true,
      "loc": "drivers/edac/edac_mc.c:711",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/ghes_edac.c:ghes_edac_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587028896,
      "name": "edac_mc_add_mc_with_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 814
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
int edac_mc_add_mc_with_groups(struct mem_ctl_info * mci, const struct attribute_group * * groups)
```

```json
{
  "name": "edac_mc_add_mc_with_groups",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "edac_mc_add_mc_with_groups",
      "external": true,
      "loc": "drivers/edac/edac_mc.c:713",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/ghes_edac.c:ghes_edac_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587333169,
      "name": "edac_mc_add_mc_with_groups.cold.13",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 229
    },
    {
      "addr": 18446744071587327376,
      "name": "edac_mc_add_mc_with_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 610
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
int edac_mc_add_mc_with_groups(struct mem_ctl_info * mci, const struct attribute_group * * groups)
```

```json
{
  "name": "edac_mc_add_mc_with_groups",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "edac_mc_add_mc_with_groups",
      "external": true,
      "loc": "drivers/edac/edac_mc.c:711",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/ghes_edac.c:ghes_edac_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587511521,
      "name": "edac_mc_add_mc_with_groups.cold.14",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 206
    },
    {
      "addr": 18446744071587505776,
      "name": "edac_mc_add_mc_with_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 553
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
int edac_mc_add_mc_with_groups(struct mem_ctl_info * mci, const struct attribute_group * * groups)
```

```json
{
  "name": "edac_mc_add_mc_with_groups",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "edac_mc_add_mc_with_groups",
      "external": true,
      "loc": "drivers/edac/edac_mc.c:707",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/ghes_edac.c:ghes_edac_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587785377,
      "name": "edac_mc_add_mc_with_groups.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
    },
    {
      "addr": 18446744071587779792,
      "name": "edac_mc_add_mc_with_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 476
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
int edac_mc_add_mc_with_groups(struct mem_ctl_info * mci, const struct attribute_group * * groups)
```

```json
{
  "name": "edac_mc_add_mc_with_groups",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "edac_mc_add_mc_with_groups",
      "external": true,
      "loc": "drivers/edac/edac_mc.c:700",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/ghes_edac.c:ghes_edac_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587990113,
      "name": "edac_mc_add_mc_with_groups.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
    },
    {
      "addr": 18446744071587984496,
      "name": "edac_mc_add_mc_with_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 476
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
int edac_mc_add_mc_with_groups(struct mem_ctl_info * mci, const struct attribute_group * * groups)
```

```json
{
  "name": "edac_mc_add_mc_with_groups",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "edac_mc_add_mc_with_groups",
      "external": true,
      "loc": "drivers/edac/edac_mc.c:669",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/ghes_edac.c:ghes_edac_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588844350,
      "name": "edac_mc_add_mc_with_groups.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071588839568,
      "name": "edac_mc_add_mc_with_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 398
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
int edac_mc_add_mc_with_groups(struct mem_ctl_info * mci, const struct attribute_group * * groups)
```

```json
{
  "name": "edac_mc_add_mc_with_groups",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "edac_mc_add_mc_with_groups",
      "external": true,
      "loc": "drivers/edac/edac_mc.c:673",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/ghes_edac.c:ghes_edac_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591593843,
      "name": "edac_mc_add_mc_with_groups.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071588855744,
      "name": "edac_mc_add_mc_with_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 398
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
int edac_mc_add_mc_with_groups(struct mem_ctl_info * mci, const struct attribute_group * * groups)
```

```json
{
  "name": "edac_mc_add_mc_with_groups",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "edac_mc_add_mc_with_groups",
      "external": true,
      "loc": "drivers/edac/edac_mc.c:673",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/ghes_edac.c:ghes_edac_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591536885,
      "name": "edac_mc_add_mc_with_groups.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
    },
    {
      "addr": 18446744071588742608,
      "name": "edac_mc_add_mc_with_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 503
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
int edac_mc_add_mc_with_groups(struct mem_ctl_info * mci, const struct attribute_group * * groups)
```

```json
{
  "name": "edac_mc_add_mc_with_groups",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "edac_mc_add_mc_with_groups",
      "external": true,
      "loc": "drivers/edac/edac_mc.c:676",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/ghes_edac.c:ghes_edac_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592650737,
      "name": "edac_mc_add_mc_with_groups.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
    },
    {
      "addr": 18446744071589433072,
      "name": "edac_mc_add_mc_with_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 503
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
int edac_mc_add_mc_with_groups(struct mem_ctl_info * mci, const struct attribute_group * * groups)
```

```json
{
  "name": "edac_mc_add_mc_with_groups",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "edac_mc_add_mc_with_groups",
      "external": true,
      "loc": "drivers/edac/edac_mc.c:601",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/ghes_edac.c:ghes_edac_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594535382,
      "name": "edac_mc_add_mc_with_groups.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
    },
    {
      "addr": 18446744071590911152,
      "name": "edac_mc_add_mc_with_groups",
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
int edac_mc_add_mc_with_groups(struct mem_ctl_info * mci, const struct attribute_group * * groups)
```

```json
{
  "name": "edac_mc_add_mc_with_groups",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592608768,
      "name": "edac_mc_add_mc_with_groups",
      "external": true,
      "loc": "drivers/edac/edac_mc.c:600",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592608768,
      "name": "edac_mc_add_mc_with_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 699
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
int edac_mc_add_mc_with_groups(struct mem_ctl_info * mci, const struct attribute_group * * groups)
```

```json
{
  "name": "edac_mc_add_mc_with_groups",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593039328,
      "name": "edac_mc_add_mc_with_groups",
      "external": true,
      "loc": "drivers/edac/edac_mc.c:600",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593039328,
      "name": "edac_mc_add_mc_with_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 699
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
int edac_mc_add_mc_with_groups(struct mem_ctl_info * mci, const struct attribute_group * * groups)
```

```json
{
  "name": "edac_mc_add_mc_with_groups",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593790752,
      "name": "edac_mc_add_mc_with_groups",
      "external": true,
      "loc": "drivers/edac/edac_mc.c:601",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593790752,
      "name": "edac_mc_add_mc_with_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 699
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
int edac_mc_add_mc_with_groups(struct mem_ctl_info * mci, const struct attribute_group * * groups)
```

```json
{
  "name": "edac_mc_add_mc_with_groups",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501228888,
      "name": "edac_mc_add_mc_with_groups",
      "external": true,
      "loc": "drivers/edac/edac_mc.c:700",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/ghes_edac.c:ghes_edac_register",
        "drivers/edac/altera_edac.c:altr_sdram_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501228888,
      "name": "edac_mc_add_mc_with_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 636
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
int edac_mc_add_mc_with_groups(struct mem_ctl_info * mci, const struct attribute_group * * groups)
```

```json
{
  "name": "edac_mc_add_mc_with_groups",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233732676,
      "name": "edac_mc_add_mc_with_groups",
      "external": true,
      "loc": "drivers/edac/edac_mc.c:700",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/armada_xp_edac.c:axp_mc_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233732676,
      "name": "edac_mc_add_mc_with_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 616
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
int edac_mc_add_mc_with_groups(struct mem_ctl_info * mci, const struct attribute_group * * groups)
```

```json
{
  "name": "edac_mc_add_mc_with_groups",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294757664,
      "name": "edac_mc_add_mc_with_groups",
      "external": true,
      "loc": "drivers/edac/edac_mc.c:700",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294757664,
      "name": "edac_mc_add_mc_with_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 796
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
int edac_mc_add_mc_with_groups(struct mem_ctl_info * mci, const struct attribute_group * * groups)
```

```json
{
  "name": "edac_mc_add_mc_with_groups",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277923478,
      "name": "edac_mc_add_mc_with_groups",
      "external": true,
      "loc": "drivers/edac/edac_mc.c:700",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277923478,
      "name": "edac_mc_add_mc_with_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 584
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int edac_mc_add_mc_with_groups(struct mem_ctl_info * mci, const struct attribute_group * * groups)
```

```json
{
  "name": "edac_mc_add_mc_with_groups",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "edac_mc_add_mc_with_groups",
      "external": true,
      "loc": "drivers/edac/edac_mc.c:700",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587621089,
      "name": "edac_mc_add_mc_with_groups.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
    },
    {
      "addr": 18446744071587615472,
      "name": "edac_mc_add_mc_with_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 476
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
int edac_mc_add_mc_with_groups(struct mem_ctl_info * mci, const struct attribute_group * * groups)
```

```json
{
  "name": "edac_mc_add_mc_with_groups",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "edac_mc_add_mc_with_groups",
      "external": true,
      "loc": "drivers/edac/edac_mc.c:700",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587389105,
      "name": "edac_mc_add_mc_with_groups.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
    },
    {
      "addr": 18446744071587383488,
      "name": "edac_mc_add_mc_with_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 476
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
int edac_mc_add_mc_with_groups(struct mem_ctl_info * mci, const struct attribute_group * * groups)
```

```json
{
  "name": "edac_mc_add_mc_with_groups",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "edac_mc_add_mc_with_groups",
      "external": true,
      "loc": "drivers/edac/edac_mc.c:700",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/ghes_edac.c:ghes_edac_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587946257,
      "name": "edac_mc_add_mc_with_groups.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
    },
    {
      "addr": 18446744071587940640,
      "name": "edac_mc_add_mc_with_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 476
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
int edac_mc_add_mc_with_groups(struct mem_ctl_info * mci, const struct attribute_group * * groups)
```

```json
{
  "name": "edac_mc_add_mc_with_groups",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "edac_mc_add_mc_with_groups",
      "external": true,
      "loc": "drivers/edac/edac_mc.c:700",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/ghes_edac.c:ghes_edac_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588061601,
      "name": "edac_mc_add_mc_with_groups.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
    },
    {
      "addr": 18446744071588055920,
      "name": "edac_mc_add_mc_with_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 476
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
int edac_mc_add_mc_with_groups(struct mem_ctl_info * mci, const struct attribute_group * * groups)
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
