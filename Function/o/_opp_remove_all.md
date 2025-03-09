# Function: <code>_opp_remove_all</code>

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
void _opp_remove_all(struct opp_table * opp_table, bool dynamic)
```

```json
{
  "name": "_opp_remove_all",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588880304,
      "name": "_opp_remove_all",
      "external": false,
      "loc": "drivers/opp/core.c:1357",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_remove_table",
        "drivers/opp/core.c:dev_pm_opp_remove_all_dynamic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588880304,
      "name": "_opp_remove_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 285
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
void _opp_remove_all(struct opp_table * opp_table, bool dynamic)
```

```json
{
  "name": "_opp_remove_all",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588767200,
      "name": "_opp_remove_all",
      "external": false,
      "loc": "drivers/opp/core.c:1514",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_remove_table",
        "drivers/opp/core.c:dev_pm_opp_remove_all_dynamic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588767200,
      "name": "_opp_remove_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 285
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
void _opp_remove_all(struct opp_table * opp_table, bool dynamic)
```

```json
{
  "name": "_opp_remove_all",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_opp_remove_all",
      "external": false,
      "loc": "drivers/opp/core.c:1524",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_remove_table",
        "drivers/opp/core.c:dev_pm_opp_remove_all_dynamic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589458816,
      "name": "_opp_remove_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
    },
    {
      "addr": 18446744071592653266,
      "name": "_opp_remove_all.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
void _opp_remove_all(struct opp_table * opp_table, bool dynamic)
```

```json
{
  "name": "_opp_remove_all",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_opp_remove_all",
      "external": false,
      "loc": "drivers/opp/core.c:1668",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_remove_table",
        "drivers/opp/core.c:dev_pm_opp_remove_all_dynamic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590936160,
      "name": "_opp_remove_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 316
    },
    {
      "addr": 18446744071594537915,
      "name": "_opp_remove_all.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
void _opp_remove_all(struct opp_table * opp_table, bool dynamic)
```

```json
{
  "name": "_opp_remove_all",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_opp_remove_all",
      "external": false,
      "loc": "drivers/opp/core.c:1644",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_remove_table",
        "drivers/opp/core.c:dev_pm_opp_remove_all_dynamic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592637760,
      "name": "_opp_remove_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 316
    },
    {
      "addr": 18446744071596313139,
      "name": "_opp_remove_all.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
void _opp_remove_all(struct opp_table * opp_table, bool dynamic)
```

```json
{
  "name": "_opp_remove_all",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_opp_remove_all",
      "external": false,
      "loc": "drivers/opp/core.c:1652",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_remove_table",
        "drivers/opp/core.c:dev_pm_opp_remove_all_dynamic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593068256,
      "name": "_opp_remove_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 316
    },
    {
      "addr": 18446744071596841993,
      "name": "_opp_remove_all.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
void _opp_remove_all(struct opp_table * opp_table, bool dynamic)
```

```json
{
  "name": "_opp_remove_all",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_opp_remove_all",
      "external": false,
      "loc": "drivers/opp/core.c:1762",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_remove_table",
        "drivers/opp/core.c:dev_pm_opp_remove_all_dynamic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593819456,
      "name": "_opp_remove_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 316
    },
    {
      "addr": 18446744071597766994,
      "name": "_opp_remove_all.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
void _opp_remove_all(struct opp_table * opp_table, bool dynamic)
```
</details>
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
