# Function: <code>genpd_add_device</code>

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
  "name": "genpd_add_device",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585005239,
      "name": "genpd_add_device",
      "external": false,
      "loc": "drivers/base/power/domain.c:1169",
      "file": "drivers/base/power/domain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:__pm_genpd_add_device"
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
  "name": "genpd_add_device",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585090919,
      "name": "genpd_add_device",
      "external": false,
      "loc": "drivers/base/power/domain.c:1248",
      "file": "drivers/base/power/domain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:__pm_genpd_add_device"
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
  "name": "genpd_add_device",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585516647,
      "name": "genpd_add_device",
      "external": false,
      "loc": "drivers/base/power/domain.c:1371",
      "file": "drivers/base/power/domain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:__pm_genpd_add_device"
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
  "name": "genpd_add_device",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585761698,
      "name": "genpd_add_device",
      "external": false,
      "loc": "drivers/base/power/domain.c:1376",
      "file": "drivers/base/power/domain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:pm_genpd_add_device"
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
  "name": "genpd_add_device",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585894898,
      "name": "genpd_add_device",
      "external": false,
      "loc": "drivers/base/power/domain.c:1455",
      "file": "drivers/base/power/domain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:pm_genpd_add_device"
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
  "name": "genpd_add_device",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586132547,
      "name": "genpd_add_device",
      "external": false,
      "loc": "drivers/base/power/domain.c:1503",
      "file": "drivers/base/power/domain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:pm_genpd_add_device"
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
  "name": "genpd_add_device",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586281123,
      "name": "genpd_add_device",
      "external": false,
      "loc": "drivers/base/power/domain.c:1498",
      "file": "drivers/base/power/domain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:pm_genpd_add_device"
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
int genpd_add_device(struct generic_pm_domain * genpd, struct device * dev, struct device * base_dev)
```

```json
{
  "name": "genpd_add_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587047680,
      "name": "genpd_add_device",
      "external": false,
      "loc": "drivers/base/power/domain.c:1487",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:pm_genpd_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587047680,
      "name": "genpd_add_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 519
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
int genpd_add_device(struct generic_pm_domain * genpd, struct device * dev, struct device * base_dev)
```

```json
{
  "name": "genpd_add_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587131456,
      "name": "genpd_add_device",
      "external": false,
      "loc": "drivers/base/power/domain.c:1552",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:pm_genpd_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587131456,
      "name": "genpd_add_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 519
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
int genpd_add_device(struct generic_pm_domain * genpd, struct device * dev, struct device * base_dev)
```

```json
{
  "name": "genpd_add_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587021056,
      "name": "genpd_add_device",
      "external": false,
      "loc": "drivers/base/power/domain.c:1548",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:pm_genpd_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587021056,
      "name": "genpd_add_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 706
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
int genpd_add_device(struct generic_pm_domain * genpd, struct device * dev, struct device * base_dev)
```

```json
{
  "name": "genpd_add_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587588048,
      "name": "genpd_add_device",
      "external": false,
      "loc": "drivers/base/power/domain.c:1588",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:pm_genpd_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587588048,
      "name": "genpd_add_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 706
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
int genpd_add_device(struct generic_pm_domain * genpd, struct device * dev, struct device * base_dev)
```

```json
{
  "name": "genpd_add_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588918384,
      "name": "genpd_add_device",
      "external": false,
      "loc": "drivers/base/power/domain.c:1621",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:pm_genpd_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588918384,
      "name": "genpd_add_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 842
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
int genpd_add_device(struct generic_pm_domain * genpd, struct device * dev, struct device * base_dev)
```

```json
{
  "name": "genpd_add_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590430256,
      "name": "genpd_add_device",
      "external": false,
      "loc": "drivers/base/power/domain.c:1600",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:pm_genpd_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590430256,
      "name": "genpd_add_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 846
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
int genpd_add_device(struct generic_pm_domain * genpd, struct device * dev, struct device * base_dev)
```

```json
{
  "name": "genpd_add_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590749808,
      "name": "genpd_add_device",
      "external": false,
      "loc": "drivers/base/power/domain.c:1626",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:pm_genpd_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590749808,
      "name": "genpd_add_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 758
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
int genpd_add_device(struct generic_pm_domain * genpd, struct device * dev, struct device * base_dev)
```

```json
{
  "name": "genpd_add_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589994704,
      "name": "genpd_add_device",
      "external": false,
      "loc": "drivers/pmdomain/core.c:1633",
      "file": "drivers/pmdomain/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pmdomain/core.c:pm_genpd_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589994704,
      "name": "genpd_add_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 852
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
int genpd_add_device(struct generic_pm_domain * genpd, struct device * dev, struct device * base_dev)
```

```json
{
  "name": "genpd_add_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499109744,
      "name": "genpd_add_device",
      "external": false,
      "loc": "drivers/base/power/domain.c:1498",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:__genpd_dev_pm_attach",
        "drivers/base/power/domain.c:__genpd_dev_pm_attach",
        "drivers/base/power/domain.c:of_genpd_add_device",
        "drivers/base/power/domain.c:pm_genpd_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499109744,
      "name": "genpd_add_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 764
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
int genpd_add_device(struct generic_pm_domain * genpd, struct device * dev, struct device * base_dev)
```

```json
{
  "name": "genpd_add_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231650912,
      "name": "genpd_add_device",
      "external": false,
      "loc": "drivers/base/power/domain.c:1498",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:__genpd_dev_pm_attach",
        "drivers/base/power/domain.c:of_genpd_add_device",
        "drivers/base/power/domain.c:pm_genpd_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231650912,
      "name": "genpd_add_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 652
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
int genpd_add_device(struct generic_pm_domain * genpd, struct device * dev, struct device * base_dev)
```

```json
{
  "name": "genpd_add_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292297648,
      "name": "genpd_add_device",
      "external": false,
      "loc": "drivers/base/power/domain.c:1498",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:__genpd_dev_pm_attach",
        "drivers/base/power/domain.c:__genpd_dev_pm_attach",
        "drivers/base/power/domain.c:of_genpd_add_device",
        "drivers/base/power/domain.c:pm_genpd_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292297648,
      "name": "genpd_add_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1032
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
int genpd_add_device(struct generic_pm_domain * genpd, struct device * dev, struct device * base_dev)
```

```json
{
  "name": "genpd_add_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276430608,
      "name": "genpd_add_device",
      "external": false,
      "loc": "drivers/base/power/domain.c:1498",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:__genpd_dev_pm_attach",
        "drivers/base/power/domain.c:of_genpd_add_device",
        "drivers/base/power/domain.c:pm_genpd_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276430608,
      "name": "genpd_add_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 646
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
  "name": "genpd_add_device",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586044371,
      "name": "genpd_add_device",
      "external": false,
      "loc": "drivers/base/power/domain.c:1498",
      "file": "drivers/base/power/domain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:pm_genpd_add_device"
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
  "name": "genpd_add_device",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585890371,
      "name": "genpd_add_device",
      "external": false,
      "loc": "drivers/base/power/domain.c:1498",
      "file": "drivers/base/power/domain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:pm_genpd_add_device"
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
  "name": "genpd_add_device",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586231139,
      "name": "genpd_add_device",
      "external": false,
      "loc": "drivers/base/power/domain.c:1498",
      "file": "drivers/base/power/domain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:pm_genpd_add_device"
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
  "name": "genpd_add_device",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586338035,
      "name": "genpd_add_device",
      "external": false,
      "loc": "drivers/base/power/domain.c:1498",
      "file": "drivers/base/power/domain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:pm_genpd_add_device"
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
int genpd_add_device(struct generic_pm_domain * genpd, struct device * dev, struct device * base_dev)
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
int genpd_add_device(struct generic_pm_domain * genpd, struct device * dev, struct device * base_dev)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int genpd_add_device(struct generic_pm_domain * genpd, struct device * dev, struct device * base_dev)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
int genpd_add_device(struct generic_pm_domain * genpd, struct device * dev, struct device * base_dev)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
int genpd_add_device(struct generic_pm_domain * genpd, struct device * dev, struct device * base_dev)
```
</details>
</li>
</ul>
