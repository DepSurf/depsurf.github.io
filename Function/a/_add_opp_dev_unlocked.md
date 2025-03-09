# Function: <code>_add_opp_dev_unlocked</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "_add_opp_dev_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587535506,
      "name": "_add_opp_dev_unlocked",
      "external": false,
      "loc": "drivers/opp/core.c:792",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:_add_opp_dev"
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
  "name": "_add_opp_dev_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587809378,
      "name": "_add_opp_dev_unlocked",
      "external": false,
      "loc": "drivers/opp/core.c:870",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:_add_opp_dev"
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
  "name": "_add_opp_dev_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588014546,
      "name": "_add_opp_dev_unlocked",
      "external": false,
      "loc": "drivers/opp/core.c:918",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:_add_opp_dev"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "_add_opp_dev_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588871714,
      "name": "_add_opp_dev_unlocked",
      "external": false,
      "loc": "drivers/opp/core.c:996",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:_add_opp_dev"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct opp_device * _add_opp_dev_unlocked(const struct device * dev, struct opp_table * opp_table)
```

```json
{
  "name": "_add_opp_dev_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501264520,
      "name": "_add_opp_dev_unlocked",
      "external": false,
      "loc": "drivers/opp/core.c:918",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_opp_get_opp_table",
        "drivers/opp/core.c:_add_opp_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501264520,
      "name": "_add_opp_dev_unlocked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
struct opp_device * _add_opp_dev_unlocked(const struct device * dev, struct opp_table * opp_table)
```

```json
{
  "name": "_add_opp_dev_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233755328,
      "name": "_add_opp_dev_unlocked",
      "external": false,
      "loc": "drivers/opp/core.c:918",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_opp_get_opp_table",
        "drivers/opp/core.c:_add_opp_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233755328,
      "name": "_add_opp_dev_unlocked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
struct opp_device * _add_opp_dev_unlocked(const struct device * dev, struct opp_table * opp_table)
```

```json
{
  "name": "_add_opp_dev_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294787728,
      "name": "_add_opp_dev_unlocked",
      "external": false,
      "loc": "drivers/opp/core.c:918",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_opp_get_opp_table",
        "drivers/opp/core.c:_add_opp_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294787728,
      "name": "_add_opp_dev_unlocked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
struct opp_device * _add_opp_dev_unlocked(const struct device * dev, struct opp_table * opp_table)
```

```json
{
  "name": "_add_opp_dev_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277941886,
      "name": "_add_opp_dev_unlocked",
      "external": false,
      "loc": "drivers/opp/core.c:918",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_opp_get_opp_table",
        "drivers/opp/core.c:_add_opp_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277941886,
      "name": "_add_opp_dev_unlocked",
      "section": ".text",
      "bind": "STB_LOCAL",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "_add_opp_dev_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587639538,
      "name": "_add_opp_dev_unlocked",
      "external": false,
      "loc": "drivers/opp/core.c:918",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:_add_opp_dev"
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
  "name": "_add_opp_dev_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587413410,
      "name": "_add_opp_dev_unlocked",
      "external": false,
      "loc": "drivers/opp/core.c:918",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:_add_opp_dev"
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
  "name": "_add_opp_dev_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587970690,
      "name": "_add_opp_dev_unlocked",
      "external": false,
      "loc": "drivers/opp/core.c:918",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:_add_opp_dev"
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
  "name": "_add_opp_dev_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588086066,
      "name": "_add_opp_dev_unlocked",
      "external": false,
      "loc": "drivers/opp/core.c:918",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:_add_opp_dev"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
struct opp_device * _add_opp_dev_unlocked(const struct device * dev, struct opp_table * opp_table)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
struct opp_device * _add_opp_dev_unlocked(const struct device * dev, struct opp_table * opp_table)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
struct opp_device * _add_opp_dev_unlocked(const struct device * dev, struct opp_table * opp_table)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
struct opp_device * _add_opp_dev_unlocked(const struct device * dev, struct opp_table * opp_table)
```
</details>
</li>
</ul>
