# Function: <code>_set_opp</code>

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
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int _set_opp(struct device * dev, struct opp_table * opp_table, struct dev_pm_opp * opp, long unsigned int freq)
```

```json
{
  "name": "_set_opp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_set_opp",
      "external": false,
      "loc": "drivers/opp/core.c:985",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_set_opp",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588777616,
      "name": "_set_opp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1550
    },
    {
      "addr": 18446744071591540379,
      "name": "_set_opp.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 313
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
int _set_opp(struct device * dev, struct opp_table * opp_table, struct dev_pm_opp * opp, long unsigned int freq)
```

```json
{
  "name": "_set_opp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_set_opp",
      "external": false,
      "loc": "drivers/opp/core.c:995",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_set_opp",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589469712,
      "name": "_set_opp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1606
    },
    {
      "addr": 18446744071592654977,
      "name": "_set_opp.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 425
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
int _set_opp(struct device * dev, struct opp_table * opp_table, struct dev_pm_opp * opp, long unsigned int freq)
```

```json
{
  "name": "_set_opp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_set_opp",
      "external": false,
      "loc": "drivers/opp/core.c:1140",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_set_opp",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590948560,
      "name": "_set_opp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1552
    },
    {
      "addr": 18446744071594539623,
      "name": "_set_opp.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 477
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
int _set_opp(struct device * dev, struct opp_table * opp_table, struct dev_pm_opp * opp, void * clk_data, bool forced)
```

```json
{
  "name": "_set_opp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_set_opp",
      "external": false,
      "loc": "drivers/opp/core.c:1067",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_set_opp",
        "drivers/opp/core.c:dev_pm_opp_set_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592649952,
      "name": "_set_opp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1303
    },
    {
      "addr": 18446744071596313461,
      "name": "_set_opp.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
int _set_opp(struct device * dev, struct opp_table * opp_table, struct dev_pm_opp * opp, void * clk_data, bool forced)
```

```json
{
  "name": "_set_opp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_set_opp",
      "external": false,
      "loc": "drivers/opp/core.c:1080",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_set_opp",
        "drivers/opp/core.c:dev_pm_opp_set_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593080528,
      "name": "_set_opp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1445
    },
    {
      "addr": 18446744071596842336,
      "name": "_set_opp.cold",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int _set_opp(struct device * dev, struct opp_table * opp_table, struct dev_pm_opp * opp, void * clk_data, bool forced)
```

```json
{
  "name": "_set_opp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_set_opp",
      "external": false,
      "loc": "drivers/opp/core.c:1185",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_set_opp",
        "drivers/opp/core.c:dev_pm_opp_set_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593832736,
      "name": "_set_opp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1450
    },
    {
      "addr": 18446744071597767415,
      "name": "_set_opp.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
int _set_opp(struct device * dev, struct opp_table * opp_table, struct dev_pm_opp * opp, long unsigned int freq)
```
</details>
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
<code>void * clk_data</code>
</li>
<li>
<b>Param added. </b>
<code>bool forced</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int freq</code>
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
