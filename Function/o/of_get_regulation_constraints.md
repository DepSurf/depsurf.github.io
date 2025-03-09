# Function: <code>of_get_regulation_constraints</code>

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
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "of_get_regulation_constraints",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498327352,
      "name": "of_get_regulation_constraints",
      "external": false,
      "loc": "drivers/regulator/of_regulator.c:24",
      "file": "drivers/regulator/of_regulator.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/of_regulator.c:of_get_regulator_init_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498327352,
      "name": "of_get_regulation_constraints.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2188
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
int of_get_regulation_constraints(struct device * dev, struct device_node * np, struct regulator_init_data * * init_data, const struct regulator_desc * desc)
```

```json
{
  "name": "of_get_regulation_constraints",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231007856,
      "name": "of_get_regulation_constraints",
      "external": false,
      "loc": "drivers/regulator/of_regulator.c:24",
      "file": "drivers/regulator/of_regulator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/of_regulator.c:of_get_regulator_init_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231007856,
      "name": "of_get_regulation_constraints",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2312
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "of_get_regulation_constraints",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055291505344,
      "name": "of_get_regulation_constraints",
      "external": false,
      "loc": "drivers/regulator/of_regulator.c:24",
      "file": "drivers/regulator/of_regulator.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/of_regulator.c:of_get_regulator_init_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291505344,
      "name": "of_get_regulation_constraints.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2872
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "of_get_regulation_constraints",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276015800,
      "name": "of_get_regulation_constraints",
      "external": false,
      "loc": "drivers/regulator/of_regulator.c:24",
      "file": "drivers/regulator/of_regulator.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/of_regulator.c:of_get_regulator_init_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276015800,
      "name": "of_get_regulation_constraints.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1932
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int of_get_regulation_constraints(struct device * dev, struct device_node * np, struct regulator_init_data * * init_data, const struct regulator_desc * desc)
```
</details>
</li>
</ul>
