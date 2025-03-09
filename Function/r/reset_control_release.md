# Function: <code>reset_control_release</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void reset_control_release(struct reset_control * rstc)
```

```json
{
  "name": "reset_control_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "reset_control_release",
      "external": true,
      "loc": "drivers/reset/core.c:527",
      "file": "drivers/reset/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/reset/core.c:reset_control_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585527708,
      "name": "reset_control_release.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071585524896,
      "name": "reset_control_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
void reset_control_release(struct reset_control * rstc)
```

```json
{
  "name": "reset_control_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585665936,
      "name": "reset_control_release",
      "external": true,
      "loc": "drivers/reset/core.c:526",
      "file": "drivers/reset/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/reset/core.c:reset_control_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585665936,
      "name": "reset_control_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
void reset_control_release(struct reset_control * rstc)
```

```json
{
  "name": "reset_control_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586391248,
      "name": "reset_control_release",
      "external": true,
      "loc": "drivers/reset/core.c:527",
      "file": "drivers/reset/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/reset/core.c:reset_control_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586391248,
      "name": "reset_control_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
void reset_control_release(struct reset_control * rstc)
```

```json
{
  "name": "reset_control_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586506272,
      "name": "reset_control_release",
      "external": true,
      "loc": "drivers/reset/core.c:601",
      "file": "drivers/reset/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/reset/core.c:reset_control_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586506272,
      "name": "reset_control_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
void reset_control_release(struct reset_control * rstc)
```

```json
{
  "name": "reset_control_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586390272,
      "name": "reset_control_release",
      "external": true,
      "loc": "drivers/reset/core.c:715",
      "file": "drivers/reset/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/reset/core.c:reset_control_bulk_release",
        "drivers/reset/core.c:reset_control_release",
        "drivers/reset/core.c:reset_control_bulk_acquire"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586390272,
      "name": "reset_control_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
void reset_control_release(struct reset_control * rstc)
```

```json
{
  "name": "reset_control_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "reset_control_release",
      "external": true,
      "loc": "drivers/reset/core.c:715",
      "file": "drivers/reset/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/reset/core.c:reset_control_bulk_release",
        "drivers/reset/core.c:reset_control_release",
        "drivers/reset/core.c:reset_control_bulk_acquire"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592445135,
      "name": "reset_control_release.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071586916800,
      "name": "reset_control_release",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void reset_control_release(struct reset_control * rstc)
```

```json
{
  "name": "reset_control_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "reset_control_release",
      "external": true,
      "loc": "drivers/reset/core.c:716",
      "file": "drivers/reset/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/reset/core.c:reset_control_bulk_release",
        "drivers/reset/core.c:reset_control_release",
        "drivers/reset/core.c:reset_control_bulk_acquire",
        "drivers/reset/core.c:reset_control_acquire"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594313164,
      "name": "reset_control_release.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071588209536,
      "name": "reset_control_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
void reset_control_release(struct reset_control * rstc)
```

```json
{
  "name": "reset_control_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "reset_control_release",
      "external": true,
      "loc": "drivers/reset/core.c:716",
      "file": "drivers/reset/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/reset/core.c:reset_control_bulk_release",
        "drivers/reset/core.c:reset_control_release",
        "drivers/reset/core.c:reset_control_bulk_acquire",
        "drivers/reset/core.c:reset_control_acquire"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596231986,
      "name": "reset_control_release.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071589617520,
      "name": "reset_control_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
void reset_control_release(struct reset_control * rstc)
```

```json
{
  "name": "reset_control_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "reset_control_release",
      "external": true,
      "loc": "drivers/reset/core.c:716",
      "file": "drivers/reset/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/reset/core.c:reset_control_bulk_release",
        "drivers/reset/core.c:reset_control_release",
        "drivers/reset/core.c:reset_control_bulk_acquire",
        "drivers/reset/core.c:reset_control_acquire"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596759895,
      "name": "reset_control_release.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071589921056,
      "name": "reset_control_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
void reset_control_release(struct reset_control * rstc)
```

```json
{
  "name": "reset_control_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "reset_control_release",
      "external": true,
      "loc": "drivers/reset/core.c:716",
      "file": "drivers/reset/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/reset/core.c:reset_control_bulk_release",
        "drivers/reset/core.c:reset_control_release",
        "drivers/reset/core.c:reset_control_bulk_acquire",
        "drivers/reset/core.c:reset_control_acquire"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597668445,
      "name": "reset_control_release.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071590259552,
      "name": "reset_control_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
void reset_control_release(struct reset_control * rstc)
```

```json
{
  "name": "reset_control_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498332328,
      "name": "reset_control_release",
      "external": true,
      "loc": "drivers/reset/core.c:526",
      "file": "drivers/reset/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/reset/core.c:reset_control_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498332328,
      "name": "reset_control_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void reset_control_release(struct reset_control * rstc)
```

```json
{
  "name": "reset_control_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231024624,
      "name": "reset_control_release",
      "external": true,
      "loc": "drivers/reset/core.c:526",
      "file": "drivers/reset/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/soc/tegra/pmc.c:tegra_powergate_init",
        "drivers/soc/tegra/pmc.c:tegra_powergate_init",
        "drivers/soc/tegra/pmc.c:tegra_genpd_power_off",
        "drivers/soc/tegra/pmc.c:tegra_genpd_power_on",
        "drivers/reset/core.c:reset_control_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231024624,
      "name": "reset_control_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
void reset_control_release(struct reset_control * rstc)
```

```json
{
  "name": "reset_control_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291513120,
      "name": "reset_control_release",
      "external": true,
      "loc": "drivers/reset/core.c:526",
      "file": "drivers/reset/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/reset/core.c:reset_control_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291513120,
      "name": "reset_control_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
void reset_control_release(struct reset_control * rstc)
```

```json
{
  "name": "reset_control_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276020024,
      "name": "reset_control_release",
      "external": true,
      "loc": "drivers/reset/core.c:526",
      "file": "drivers/reset/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/reset/core.c:reset_control_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276020024,
      "name": "reset_control_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void reset_control_release(struct reset_control * rstc)
```

```json
{
  "name": "reset_control_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585426960,
      "name": "reset_control_release",
      "external": true,
      "loc": "drivers/reset/core.c:526",
      "file": "drivers/reset/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/reset/core.c:reset_control_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585426960,
      "name": "reset_control_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
void reset_control_release(struct reset_control * rstc)
```

```json
{
  "name": "reset_control_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585297008,
      "name": "reset_control_release",
      "external": true,
      "loc": "drivers/reset/core.c:526",
      "file": "drivers/reset/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/reset/core.c:reset_control_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585297008,
      "name": "reset_control_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
void reset_control_release(struct reset_control * rstc)
```

```json
{
  "name": "reset_control_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585616336,
      "name": "reset_control_release",
      "external": true,
      "loc": "drivers/reset/core.c:526",
      "file": "drivers/reset/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/reset/core.c:reset_control_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585616336,
      "name": "reset_control_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
void reset_control_release(struct reset_control * rstc)
```

```json
{
  "name": "reset_control_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585724464,
      "name": "reset_control_release",
      "external": true,
      "loc": "drivers/reset/core.c:526",
      "file": "drivers/reset/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/reset/core.c:reset_control_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585724464,
      "name": "reset_control_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
void reset_control_release(struct reset_control * rstc)
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
