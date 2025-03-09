# Function: <code>linear_range_get_selector_high</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int linear_range_get_selector_high(const struct linear_range * r, unsigned int val, unsigned int * selector, bool * found)
```

```json
{
  "name": "linear_range_get_selector_high",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584719040,
      "name": "linear_range_get_selector_high",
      "external": true,
      "loc": "lib/linear_ranges.c:219",
      "file": "lib/linear_ranges.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584719040,
      "name": "linear_range_get_selector_high",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int linear_range_get_selector_high(const struct linear_range * r, unsigned int val, unsigned int * selector, bool * found)
```

```json
{
  "name": "linear_range_get_selector_high",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584832208,
      "name": "linear_range_get_selector_high",
      "external": true,
      "loc": "lib/linear_ranges.c:219",
      "file": "lib/linear_ranges.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584832208,
      "name": "linear_range_get_selector_high",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int linear_range_get_selector_high(const struct linear_range * r, unsigned int val, unsigned int * selector, bool * found)
```

```json
{
  "name": "linear_range_get_selector_high",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584876720,
      "name": "linear_range_get_selector_high",
      "external": true,
      "loc": "lib/linear_ranges.c:219",
      "file": "lib/linear_ranges.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584876720,
      "name": "linear_range_get_selector_high",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int linear_range_get_selector_high(const struct linear_range * r, unsigned int val, unsigned int * selector, bool * found)
```

```json
{
  "name": "linear_range_get_selector_high",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585301984,
      "name": "linear_range_get_selector_high",
      "external": true,
      "loc": "lib/linear_ranges.c:219",
      "file": "lib/linear_ranges.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585301984,
      "name": "linear_range_get_selector_high",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
int linear_range_get_selector_high(const struct linear_range * r, unsigned int val, unsigned int * selector, bool * found)
```

```json
{
  "name": "linear_range_get_selector_high",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586157232,
      "name": "linear_range_get_selector_high",
      "external": true,
      "loc": "lib/linear_ranges.c:219",
      "file": "lib/linear_ranges.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/helpers.c:regulator_map_voltage_linear_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586157232,
      "name": "linear_range_get_selector_high",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
int linear_range_get_selector_high(const struct linear_range * r, unsigned int val, unsigned int * selector, bool * found)
```

```json
{
  "name": "linear_range_get_selector_high",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587150784,
      "name": "linear_range_get_selector_high",
      "external": true,
      "loc": "lib/linear_ranges.c:219",
      "file": "lib/linear_ranges.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/helpers.c:regulator_map_voltage_linear_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587150784,
      "name": "linear_range_get_selector_high",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
int linear_range_get_selector_high(const struct linear_range * r, unsigned int val, unsigned int * selector, bool * found)
```

```json
{
  "name": "linear_range_get_selector_high",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587413312,
      "name": "linear_range_get_selector_high",
      "external": true,
      "loc": "lib/linear_ranges.c:219",
      "file": "lib/linear_ranges.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/helpers.c:regulator_map_voltage_linear_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587413312,
      "name": "linear_range_get_selector_high",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
int linear_range_get_selector_high(const struct linear_range * r, unsigned int val, unsigned int * selector, bool * found)
```

```json
{
  "name": "linear_range_get_selector_high",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587748128,
      "name": "linear_range_get_selector_high",
      "external": true,
      "loc": "lib/linear_ranges.c:219",
      "file": "lib/linear_ranges.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/helpers.c:regulator_map_voltage_linear_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587748128,
      "name": "linear_range_get_selector_high",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int linear_range_get_selector_high(const struct linear_range * r, unsigned int val, unsigned int * selector, bool * found)
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
