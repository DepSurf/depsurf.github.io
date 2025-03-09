# Function: <code>genpd_add_subdomain</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "genpd_add_subdomain",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585002235,
      "name": "genpd_add_subdomain",
      "external": false,
      "loc": "drivers/base/power/domain.c:1286",
      "file": "drivers/base/power/domain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:pm_genpd_add_subdomain"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "genpd_add_subdomain",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585087547,
      "name": "genpd_add_subdomain",
      "external": false,
      "loc": "drivers/base/power/domain.c:1369",
      "file": "drivers/base/power/domain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:pm_genpd_add_subdomain"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "genpd_add_subdomain",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585513099,
      "name": "genpd_add_subdomain",
      "external": false,
      "loc": "drivers/base/power/domain.c:1492",
      "file": "drivers/base/power/domain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:pm_genpd_add_subdomain"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "genpd_add_subdomain",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585758198,
      "name": "genpd_add_subdomain",
      "external": false,
      "loc": "drivers/base/power/domain.c:1490",
      "file": "drivers/base/power/domain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:pm_genpd_add_subdomain"
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
  "name": "genpd_add_subdomain",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585884342,
      "name": "genpd_add_subdomain",
      "external": false,
      "loc": "drivers/base/power/domain.c:1569",
      "file": "drivers/base/power/domain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:pm_genpd_add_subdomain"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "genpd_add_subdomain",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586121473,
      "name": "genpd_add_subdomain",
      "external": false,
      "loc": "drivers/base/power/domain.c:1622",
      "file": "drivers/base/power/domain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:pm_genpd_add_subdomain"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "genpd_add_subdomain",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586270113,
      "name": "genpd_add_subdomain",
      "external": false,
      "loc": "drivers/base/power/domain.c:1617",
      "file": "drivers/base/power/domain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:pm_genpd_add_subdomain"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int genpd_add_subdomain(struct generic_pm_domain * genpd, struct generic_pm_domain * subdomain)
```

```json
{
  "name": "genpd_add_subdomain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587043872,
      "name": "genpd_add_subdomain",
      "external": false,
      "loc": "drivers/base/power/domain.c:1606",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:pm_genpd_add_subdomain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587043872,
      "name": "genpd_add_subdomain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 513
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
int genpd_add_subdomain(struct generic_pm_domain * genpd, struct generic_pm_domain * subdomain)
```

```json
{
  "name": "genpd_add_subdomain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587128640,
      "name": "genpd_add_subdomain",
      "external": false,
      "loc": "drivers/base/power/domain.c:1766",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:pm_genpd_add_subdomain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587128640,
      "name": "genpd_add_subdomain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 513
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
int genpd_add_subdomain(struct generic_pm_domain * genpd, struct generic_pm_domain * subdomain)
```

```json
{
  "name": "genpd_add_subdomain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587014976,
      "name": "genpd_add_subdomain",
      "external": false,
      "loc": "drivers/base/power/domain.c:1762",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:pm_genpd_add_subdomain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587014976,
      "name": "genpd_add_subdomain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 513
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
int genpd_add_subdomain(struct generic_pm_domain * genpd, struct generic_pm_domain * subdomain)
```

```json
{
  "name": "genpd_add_subdomain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587580432,
      "name": "genpd_add_subdomain",
      "external": false,
      "loc": "drivers/base/power/domain.c:1802",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:pm_genpd_add_subdomain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587580432,
      "name": "genpd_add_subdomain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 513
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
int genpd_add_subdomain(struct generic_pm_domain * genpd, struct generic_pm_domain * subdomain)
```

```json
{
  "name": "genpd_add_subdomain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588917520,
      "name": "genpd_add_subdomain",
      "external": false,
      "loc": "drivers/base/power/domain.c:1838",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:pm_genpd_add_subdomain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588917520,
      "name": "genpd_add_subdomain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 535
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
int genpd_add_subdomain(struct generic_pm_domain * genpd, struct generic_pm_domain * subdomain)
```

```json
{
  "name": "genpd_add_subdomain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590429344,
      "name": "genpd_add_subdomain",
      "external": false,
      "loc": "drivers/base/power/domain.c:1817",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:pm_genpd_add_subdomain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590429344,
      "name": "genpd_add_subdomain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 535
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
int genpd_add_subdomain(struct generic_pm_domain * genpd, struct generic_pm_domain * subdomain)
```

```json
{
  "name": "genpd_add_subdomain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590748896,
      "name": "genpd_add_subdomain",
      "external": false,
      "loc": "drivers/base/power/domain.c:1843",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:pm_genpd_add_subdomain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590748896,
      "name": "genpd_add_subdomain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 535
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
int genpd_add_subdomain(struct generic_pm_domain * genpd, struct generic_pm_domain * subdomain)
```

```json
{
  "name": "genpd_add_subdomain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589993744,
      "name": "genpd_add_subdomain",
      "external": false,
      "loc": "drivers/pmdomain/core.c:1850",
      "file": "drivers/pmdomain/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pmdomain/core.c:pm_genpd_add_subdomain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589993744,
      "name": "genpd_add_subdomain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 584
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
int genpd_add_subdomain(struct generic_pm_domain * genpd, struct generic_pm_domain * subdomain)
```

```json
{
  "name": "genpd_add_subdomain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499103064,
      "name": "genpd_add_subdomain",
      "external": false,
      "loc": "drivers/base/power/domain.c:1617",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:of_genpd_add_subdomain",
        "drivers/base/power/domain.c:pm_genpd_add_subdomain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499103064,
      "name": "genpd_add_subdomain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 484
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
int genpd_add_subdomain(struct generic_pm_domain * genpd, struct generic_pm_domain * subdomain)
```

```json
{
  "name": "genpd_add_subdomain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231645312,
      "name": "genpd_add_subdomain",
      "external": false,
      "loc": "drivers/base/power/domain.c:1617",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:of_genpd_add_subdomain",
        "drivers/base/power/domain.c:pm_genpd_add_subdomain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231645312,
      "name": "genpd_add_subdomain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 536
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
int genpd_add_subdomain(struct generic_pm_domain * genpd, struct generic_pm_domain * subdomain)
```

```json
{
  "name": "genpd_add_subdomain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292296480,
      "name": "genpd_add_subdomain",
      "external": false,
      "loc": "drivers/base/power/domain.c:1617",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:of_genpd_add_subdomain",
        "drivers/base/power/domain.c:pm_genpd_add_subdomain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292296480,
      "name": "genpd_add_subdomain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 684
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
int genpd_add_subdomain(struct generic_pm_domain * genpd, struct generic_pm_domain * subdomain)
```

```json
{
  "name": "genpd_add_subdomain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276420350,
      "name": "genpd_add_subdomain",
      "external": false,
      "loc": "drivers/base/power/domain.c:1617",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:of_genpd_add_subdomain",
        "drivers/base/power/domain.c:pm_genpd_add_subdomain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276420350,
      "name": "genpd_add_subdomain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 366
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
  "name": "genpd_add_subdomain",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586033361,
      "name": "genpd_add_subdomain",
      "external": false,
      "loc": "drivers/base/power/domain.c:1617",
      "file": "drivers/base/power/domain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:pm_genpd_add_subdomain"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "genpd_add_subdomain",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585879377,
      "name": "genpd_add_subdomain",
      "external": false,
      "loc": "drivers/base/power/domain.c:1617",
      "file": "drivers/base/power/domain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:pm_genpd_add_subdomain"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "genpd_add_subdomain",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586220129,
      "name": "genpd_add_subdomain",
      "external": false,
      "loc": "drivers/base/power/domain.c:1617",
      "file": "drivers/base/power/domain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:pm_genpd_add_subdomain"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "genpd_add_subdomain",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586329553,
      "name": "genpd_add_subdomain",
      "external": false,
      "loc": "drivers/base/power/domain.c:1617",
      "file": "drivers/base/power/domain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:pm_genpd_add_subdomain"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int genpd_add_subdomain(struct generic_pm_domain * genpd, struct generic_pm_domain * subdomain)
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
int genpd_add_subdomain(struct generic_pm_domain * genpd, struct generic_pm_domain * subdomain)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int genpd_add_subdomain(struct generic_pm_domain * genpd, struct generic_pm_domain * subdomain)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
int genpd_add_subdomain(struct generic_pm_domain * genpd, struct generic_pm_domain * subdomain)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
int genpd_add_subdomain(struct generic_pm_domain * genpd, struct generic_pm_domain * subdomain)
```
</details>
</li>
</ul>
