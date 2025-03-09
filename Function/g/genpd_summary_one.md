# Function: <code>genpd_summary_one</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "genpd_summary_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585510339,
      "name": "genpd_summary_one",
      "external": false,
      "loc": "drivers/base/power/domain.c:2397",
      "file": "drivers/base/power/domain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:genpd_summary_show"
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
  "name": "genpd_summary_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585755267,
      "name": "genpd_summary_one",
      "external": false,
      "loc": "drivers/base/power/domain.c:2581",
      "file": "drivers/base/power/domain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:genpd_summary_show"
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
  "name": "genpd_summary_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585888787,
      "name": "genpd_summary_one",
      "external": false,
      "loc": "drivers/base/power/domain.c:2695",
      "file": "drivers/base/power/domain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:summary_show"
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
  "name": "genpd_summary_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586125427,
      "name": "genpd_summary_one",
      "external": false,
      "loc": "drivers/base/power/domain.c:2768",
      "file": "drivers/base/power/domain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:summary_show"
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
  "name": "genpd_summary_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586274755,
      "name": "genpd_summary_one",
      "external": false,
      "loc": "drivers/base/power/domain.c:2763",
      "file": "drivers/base/power/domain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:summary_show"
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
int genpd_summary_one(struct seq_file * s, struct generic_pm_domain * genpd)
```

```json
{
  "name": "genpd_summary_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587041168,
      "name": "genpd_summary_one",
      "external": false,
      "loc": "drivers/base/power/domain.c:2801",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:summary_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587041168,
      "name": "genpd_summary_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 538
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
int genpd_summary_one(struct seq_file * s, struct generic_pm_domain * genpd)
```

```json
{
  "name": "genpd_summary_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587124384,
      "name": "genpd_summary_one",
      "external": false,
      "loc": "drivers/base/power/domain.c:2958",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:summary_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587124384,
      "name": "genpd_summary_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 538
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
int genpd_summary_one(struct seq_file * s, struct generic_pm_domain * genpd)
```

```json
{
  "name": "genpd_summary_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587011472,
      "name": "genpd_summary_one",
      "external": false,
      "loc": "drivers/base/power/domain.c:2964",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:summary_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587011472,
      "name": "genpd_summary_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 624
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
int genpd_summary_one(struct seq_file * s, struct generic_pm_domain * genpd)
```

```json
{
  "name": "genpd_summary_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587578032,
      "name": "genpd_summary_one",
      "external": false,
      "loc": "drivers/base/power/domain.c:3026",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:summary_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587578032,
      "name": "genpd_summary_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 660
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
int genpd_summary_one(struct seq_file * s, struct generic_pm_domain * genpd)
```

```json
{
  "name": "genpd_summary_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588914784,
      "name": "genpd_summary_one",
      "external": false,
      "loc": "drivers/base/power/domain.c:3091",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:summary_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588914784,
      "name": "genpd_summary_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 703
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
int genpd_summary_one(struct seq_file * s, struct generic_pm_domain * genpd)
```

```json
{
  "name": "genpd_summary_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590426912,
      "name": "genpd_summary_one",
      "external": false,
      "loc": "drivers/base/power/domain.c:3084",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:summary_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590426912,
      "name": "genpd_summary_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 703
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
int genpd_summary_one(struct seq_file * s, struct generic_pm_domain * genpd)
```

```json
{
  "name": "genpd_summary_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590746464,
      "name": "genpd_summary_one",
      "external": false,
      "loc": "drivers/base/power/domain.c:3113",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:summary_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590746464,
      "name": "genpd_summary_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 703
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
int genpd_summary_one(struct seq_file * s, struct generic_pm_domain * genpd)
```

```json
{
  "name": "genpd_summary_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589991200,
      "name": "genpd_summary_one",
      "external": false,
      "loc": "drivers/pmdomain/core.c:3089",
      "file": "drivers/pmdomain/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pmdomain/core.c:summary_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589991200,
      "name": "genpd_summary_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 703
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
  "name": "genpd_summary_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336499097400,
      "name": "genpd_summary_one",
      "external": false,
      "loc": "drivers/base/power/domain.c:2763",
      "file": "drivers/base/power/domain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:summary_show"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "genpd_summary_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3231648852,
      "name": "genpd_summary_one",
      "external": false,
      "loc": "drivers/base/power/domain.c:2763",
      "file": "drivers/base/power/domain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:summary_show"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "genpd_summary_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055292282112,
      "name": "genpd_summary_one",
      "external": false,
      "loc": "drivers/base/power/domain.c:2763",
      "file": "drivers/base/power/domain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:summary_show"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "genpd_summary_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936276423996,
      "name": "genpd_summary_one",
      "external": false,
      "loc": "drivers/base/power/domain.c:2763",
      "file": "drivers/base/power/domain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:summary_show"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "genpd_summary_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586038003,
      "name": "genpd_summary_one",
      "external": false,
      "loc": "drivers/base/power/domain.c:2763",
      "file": "drivers/base/power/domain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:summary_show"
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
  "name": "genpd_summary_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585884019,
      "name": "genpd_summary_one",
      "external": false,
      "loc": "drivers/base/power/domain.c:2763",
      "file": "drivers/base/power/domain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:summary_show"
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
  "name": "genpd_summary_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586224771,
      "name": "genpd_summary_one",
      "external": false,
      "loc": "drivers/base/power/domain.c:2763",
      "file": "drivers/base/power/domain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:summary_show"
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
  "name": "genpd_summary_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586334195,
      "name": "genpd_summary_one",
      "external": false,
      "loc": "drivers/base/power/domain.c:2763",
      "file": "drivers/base/power/domain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:summary_show"
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
int genpd_summary_one(struct seq_file * s, struct generic_pm_domain * genpd)
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
