# Function: <code>_add_opp_table_indexed</code>

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
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct opp_table * _add_opp_table_indexed(struct device * dev, int index)
```

```json
{
  "name": "_add_opp_table_indexed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588888592,
      "name": "_add_opp_table_indexed",
      "external": true,
      "loc": "drivers/opp/core.c:1146",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_add",
        "drivers/opp/core.c:dev_pm_opp_attach_genpd",
        "drivers/opp/core.c:dev_pm_opp_set_clkname",
        "drivers/opp/core.c:dev_pm_opp_set_regulators",
        "drivers/opp/core.c:dev_pm_opp_set_prop_name",
        "drivers/opp/core.c:dev_pm_opp_set_supported_hw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588888592,
      "name": "_add_opp_table_indexed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
struct opp_table * _add_opp_table_indexed(struct device * dev, int index, bool getclk)
```

```json
{
  "name": "_add_opp_table_indexed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_add_opp_table_indexed",
      "external": true,
      "loc": "drivers/opp/core.c:1299",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_add",
        "drivers/opp/core.c:dev_pm_opp_attach_genpd",
        "drivers/opp/core.c:dev_pm_opp_set_clkname",
        "drivers/opp/core.c:dev_pm_opp_set_regulators",
        "drivers/opp/core.c:dev_pm_opp_set_prop_name",
        "drivers/opp/core.c:dev_pm_opp_set_supported_hw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591540069,
      "name": "_add_opp_table_indexed.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
    },
    {
      "addr": 18446744071588774288,
      "name": "_add_opp_table_indexed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 488
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
struct opp_table * _add_opp_table_indexed(struct device * dev, int index, bool getclk)
```

```json
{
  "name": "_add_opp_table_indexed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_add_opp_table_indexed",
      "external": true,
      "loc": "drivers/opp/core.c:1309",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_add",
        "drivers/opp/core.c:dev_pm_opp_attach_genpd",
        "drivers/opp/core.c:dev_pm_opp_set_clkname",
        "drivers/opp/core.c:dev_pm_opp_set_regulators",
        "drivers/opp/core.c:dev_pm_opp_set_prop_name",
        "drivers/opp/core.c:dev_pm_opp_set_supported_hw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592654646,
      "name": "_add_opp_table_indexed.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
    },
    {
      "addr": 18446744071589466368,
      "name": "_add_opp_table_indexed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 500
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
struct opp_table * _add_opp_table_indexed(struct device * dev, int index, bool getclk)
```

```json
{
  "name": "_add_opp_table_indexed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_add_opp_table_indexed",
      "external": true,
      "loc": "drivers/opp/core.c:1454",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_add",
        "drivers/opp/core.c:dev_pm_opp_attach_genpd",
        "drivers/opp/core.c:dev_pm_opp_set_clkname",
        "drivers/opp/core.c:dev_pm_opp_set_regulators",
        "drivers/opp/core.c:dev_pm_opp_set_prop_name",
        "drivers/opp/core.c:dev_pm_opp_set_supported_hw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594539348,
      "name": "_add_opp_table_indexed.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
    },
    {
      "addr": 18446744071590944880,
      "name": "_add_opp_table_indexed",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
struct opp_table * _add_opp_table_indexed(struct device * dev, int index, bool getclk)
```

```json
{
  "name": "_add_opp_table_indexed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_add_opp_table_indexed",
      "external": true,
      "loc": "drivers/opp/core.c:1426",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_add",
        "drivers/opp/core.c:dev_pm_opp_set_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596313441,
      "name": "_add_opp_table_indexed.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071592646416,
      "name": "_add_opp_table_indexed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 732
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
struct opp_table * _add_opp_table_indexed(struct device * dev, int index, bool getclk)
```

```json
{
  "name": "_add_opp_table_indexed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_add_opp_table_indexed",
      "external": true,
      "loc": "drivers/opp/core.c:1442",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_add",
        "drivers/opp/core.c:dev_pm_opp_set_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596842316,
      "name": "_add_opp_table_indexed.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071593077040,
      "name": "_add_opp_table_indexed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 733
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
struct opp_table * _add_opp_table_indexed(struct device * dev, int index, bool getclk)
```

```json
{
  "name": "_add_opp_table_indexed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_add_opp_table_indexed",
      "external": true,
      "loc": "drivers/opp/core.c:1553",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_add_dynamic",
        "drivers/opp/core.c:dev_pm_opp_set_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597767296,
      "name": "_add_opp_table_indexed.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071593828880,
      "name": "_add_opp_table_indexed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 754
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
struct opp_table * _add_opp_table_indexed(struct device * dev, int index)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool getclk</code>
</li>
</ul>
</details>
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
