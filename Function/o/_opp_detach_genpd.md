# Function: <code>_opp_detach_genpd</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "_opp_detach_genpd",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587805504,
      "name": "_opp_detach_genpd",
      "external": false,
      "loc": "drivers/opp/core.c:1754",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_detach_genpd",
        "drivers/opp/core.c:dev_pm_opp_attach_genpd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587805504,
      "name": "_opp_detach_genpd.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
  "name": "_opp_detach_genpd",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588010528,
      "name": "_opp_detach_genpd",
      "external": false,
      "loc": "drivers/opp/core.c:1803",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_detach_genpd",
        "drivers/opp/core.c:dev_pm_opp_attach_genpd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588010528,
      "name": "_opp_detach_genpd.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
void _opp_detach_genpd(struct opp_table * opp_table)
```

```json
{
  "name": "_opp_detach_genpd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588863344,
      "name": "_opp_detach_genpd",
      "external": false,
      "loc": "drivers/opp/core.c:1917",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_detach_genpd",
        "drivers/opp/core.c:dev_pm_opp_attach_genpd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588863344,
      "name": "_opp_detach_genpd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
  "name": "_opp_detach_genpd",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588879795,
      "name": "_opp_detach_genpd",
      "external": false,
      "loc": "drivers/opp/core.c:2014",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:dev_pm_opp_detach_genpd",
        "drivers/opp/core.c:dev_pm_opp_attach_genpd"
      ],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_detach_genpd",
        "drivers/opp/core.c:dev_pm_opp_attach_genpd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588878640,
      "name": "_opp_detach_genpd.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
  "name": "_opp_detach_genpd",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588777137,
      "name": "_opp_detach_genpd",
      "external": false,
      "loc": "drivers/opp/core.c:2299",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:devm_pm_opp_attach_genpd",
        "drivers/opp/core.c:dev_pm_opp_attach_genpd"
      ],
      "caller_func": [
        "drivers/opp/core.c:devm_pm_opp_attach_genpd",
        "drivers/opp/core.c:dev_pm_opp_attach_genpd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588765504,
      "name": "_opp_detach_genpd.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
  "name": "_opp_detach_genpd",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589469233,
      "name": "_opp_detach_genpd",
      "external": false,
      "loc": "drivers/opp/core.c:2309",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:devm_pm_opp_attach_genpd",
        "drivers/opp/core.c:dev_pm_opp_attach_genpd"
      ],
      "caller_func": [
        "drivers/opp/core.c:devm_pm_opp_attach_genpd",
        "drivers/opp/core.c:dev_pm_opp_attach_genpd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589457040,
      "name": "_opp_detach_genpd.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
  "name": "_opp_detach_genpd",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590947954,
      "name": "_opp_detach_genpd",
      "external": false,
      "loc": "drivers/opp/core.c:2449",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:devm_pm_opp_attach_genpd",
        "drivers/opp/core.c:dev_pm_opp_attach_genpd"
      ],
      "caller_func": [
        "drivers/opp/core.c:devm_pm_opp_attach_genpd",
        "drivers/opp/core.c:dev_pm_opp_attach_genpd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590933936,
      "name": "_opp_detach_genpd.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
  "name": "_opp_detach_genpd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592638664,
      "name": "_opp_detach_genpd",
      "external": false,
      "loc": "drivers/opp/core.c:2403",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:_opp_clear_config"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "_opp_detach_genpd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593069160,
      "name": "_opp_detach_genpd",
      "external": false,
      "loc": "drivers/opp/core.c:2411",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:_opp_clear_config"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "_opp_detach_genpd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593831561,
      "name": "_opp_detach_genpd",
      "external": false,
      "loc": "drivers/opp/core.c:2363",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:dev_pm_opp_set_config",
        "drivers/opp/core.c:_opp_clear_config"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "_opp_detach_genpd",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501266504,
      "name": "_opp_detach_genpd",
      "external": false,
      "loc": "drivers/opp/core.c:1803",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_detach_genpd",
        "drivers/opp/core.c:dev_pm_opp_attach_genpd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501266504,
      "name": "_opp_detach_genpd.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
void _opp_detach_genpd(struct opp_table * opp_table)
```

```json
{
  "name": "_opp_detach_genpd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233756736,
      "name": "_opp_detach_genpd",
      "external": false,
      "loc": "drivers/opp/core.c:1803",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_detach_genpd",
        "drivers/opp/core.c:dev_pm_opp_attach_genpd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233756736,
      "name": "_opp_detach_genpd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
void _opp_detach_genpd(struct opp_table * opp_table)
```

```json
{
  "name": "_opp_detach_genpd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294786992,
      "name": "_opp_detach_genpd",
      "external": false,
      "loc": "drivers/opp/core.c:1803",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_detach_genpd",
        "drivers/opp/core.c:dev_pm_opp_attach_genpd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294786992,
      "name": "_opp_detach_genpd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
void _opp_detach_genpd(struct opp_table * opp_table)
```

```json
{
  "name": "_opp_detach_genpd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277942898,
      "name": "_opp_detach_genpd",
      "external": false,
      "loc": "drivers/opp/core.c:1803",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_detach_genpd",
        "drivers/opp/core.c:dev_pm_opp_attach_genpd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277942898,
      "name": "_opp_detach_genpd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "_opp_detach_genpd",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587635520,
      "name": "_opp_detach_genpd",
      "external": false,
      "loc": "drivers/opp/core.c:1803",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_detach_genpd",
        "drivers/opp/core.c:dev_pm_opp_attach_genpd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587635520,
      "name": "_opp_detach_genpd.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
  "name": "_opp_detach_genpd",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587409392,
      "name": "_opp_detach_genpd",
      "external": false,
      "loc": "drivers/opp/core.c:1803",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_detach_genpd",
        "drivers/opp/core.c:dev_pm_opp_attach_genpd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587409392,
      "name": "_opp_detach_genpd.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
  "name": "_opp_detach_genpd",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587966672,
      "name": "_opp_detach_genpd",
      "external": false,
      "loc": "drivers/opp/core.c:1803",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_detach_genpd",
        "drivers/opp/core.c:dev_pm_opp_attach_genpd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587966672,
      "name": "_opp_detach_genpd.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
  "name": "_opp_detach_genpd",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588082048,
      "name": "_opp_detach_genpd",
      "external": false,
      "loc": "drivers/opp/core.c:1803",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_detach_genpd",
        "drivers/opp/core.c:dev_pm_opp_attach_genpd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588082048,
      "name": "_opp_detach_genpd.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
void _opp_detach_genpd(struct opp_table * opp_table)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
void _opp_detach_genpd(struct opp_table * opp_table)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void _opp_detach_genpd(struct opp_table * opp_table)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
void _opp_detach_genpd(struct opp_table * opp_table)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
void _opp_detach_genpd(struct opp_table * opp_table)
```
</details>
</li>
</ul>
