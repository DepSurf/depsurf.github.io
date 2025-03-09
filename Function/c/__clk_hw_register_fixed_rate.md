# Function: <code>__clk_hw_register_fixed_rate</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct clk_hw * __clk_hw_register_fixed_rate(struct device * dev, struct device_node * np, const char * name, const char * parent_name, const struct clk_hw * parent_hw, const struct clk_parent_data * parent_data, long unsigned int flags, long unsigned int fixed_rate, long unsigned int fixed_accuracy, long unsigned int clk_fixed_flags)
```

```json
{
  "name": "__clk_hw_register_fixed_rate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586200320,
      "name": "__clk_hw_register_fixed_rate",
      "external": true,
      "loc": "drivers/clk/clk-fixed-rate.c:52",
      "file": "drivers/clk/clk-fixed-rate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-fixed-rate.c:clk_register_fixed_rate",
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents",
        "drivers/clk/x86/clk-st.c:st_clk_probe",
        "drivers/clk/x86/clk-st.c:st_clk_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586200320,
      "name": "__clk_hw_register_fixed_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
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
struct clk_hw * __clk_hw_register_fixed_rate(struct device * dev, struct device_node * np, const char * name, const char * parent_name, const struct clk_hw * parent_hw, const struct clk_parent_data * parent_data, long unsigned int flags, long unsigned int fixed_rate, long unsigned int fixed_accuracy, long unsigned int clk_fixed_flags)
```

```json
{
  "name": "__clk_hw_register_fixed_rate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586319696,
      "name": "__clk_hw_register_fixed_rate",
      "external": true,
      "loc": "drivers/clk/clk-fixed-rate.c:52",
      "file": "drivers/clk/clk-fixed-rate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-fixed-rate.c:clk_register_fixed_rate",
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents",
        "drivers/clk/x86/clk-fch.c:fch_clk_probe",
        "drivers/clk/x86/clk-fch.c:fch_clk_probe",
        "drivers/clk/x86/clk-fch.c:fch_clk_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586319696,
      "name": "__clk_hw_register_fixed_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
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
struct clk_hw * __clk_hw_register_fixed_rate(struct device * dev, struct device_node * np, const char * name, const char * parent_name, const struct clk_hw * parent_hw, const struct clk_parent_data * parent_data, long unsigned int flags, long unsigned int fixed_rate, long unsigned int fixed_accuracy, long unsigned int clk_fixed_flags)
```

```json
{
  "name": "__clk_hw_register_fixed_rate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586193568,
      "name": "__clk_hw_register_fixed_rate",
      "external": true,
      "loc": "drivers/clk/clk-fixed-rate.c:52",
      "file": "drivers/clk/clk-fixed-rate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-fixed-rate.c:clk_register_fixed_rate",
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents",
        "drivers/clk/x86/clk-fch.c:fch_clk_probe",
        "drivers/clk/x86/clk-fch.c:fch_clk_probe",
        "drivers/clk/x86/clk-fch.c:fch_clk_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586193568,
      "name": "__clk_hw_register_fixed_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 333
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
struct clk_hw * __clk_hw_register_fixed_rate(struct device * dev, struct device_node * np, const char * name, const char * parent_name, const struct clk_hw * parent_hw, const struct clk_parent_data * parent_data, long unsigned int flags, long unsigned int fixed_rate, long unsigned int fixed_accuracy, long unsigned int clk_fixed_flags)
```

```json
{
  "name": "__clk_hw_register_fixed_rate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586696240,
      "name": "__clk_hw_register_fixed_rate",
      "external": true,
      "loc": "drivers/clk/clk-fixed-rate.c:52",
      "file": "drivers/clk/clk-fixed-rate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-fixed-rate.c:clk_register_fixed_rate",
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents",
        "drivers/clk/x86/clk-fch.c:fch_clk_probe",
        "drivers/clk/x86/clk-fch.c:fch_clk_probe",
        "drivers/clk/x86/clk-fch.c:fch_clk_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586696240,
      "name": "__clk_hw_register_fixed_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 333
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
struct clk_hw * __clk_hw_register_fixed_rate(struct device * dev, struct device_node * np, const char * name, const char * parent_name, const struct clk_hw * parent_hw, const struct clk_parent_data * parent_data, long unsigned int flags, long unsigned int fixed_rate, long unsigned int fixed_accuracy, long unsigned int clk_fixed_flags)
```

```json
{
  "name": "__clk_hw_register_fixed_rate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587968640,
      "name": "__clk_hw_register_fixed_rate",
      "external": true,
      "loc": "drivers/clk/clk-fixed-rate.c:52",
      "file": "drivers/clk/clk-fixed-rate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-fixed-rate.c:clk_register_fixed_rate",
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents",
        "drivers/clk/x86/clk-fch.c:fch_clk_probe",
        "drivers/clk/x86/clk-fch.c:fch_clk_probe",
        "drivers/clk/x86/clk-fch.c:fch_clk_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587968640,
      "name": "__clk_hw_register_fixed_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 342
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
struct clk_hw * __clk_hw_register_fixed_rate(struct device * dev, struct device_node * np, const char * name, const char * parent_name, const struct clk_hw * parent_hw, const struct clk_parent_data * parent_data, long unsigned int flags, long unsigned int fixed_rate, long unsigned int fixed_accuracy, long unsigned int clk_fixed_flags, bool devm)
```

```json
{
  "name": "__clk_hw_register_fixed_rate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589331008,
      "name": "__clk_hw_register_fixed_rate",
      "external": true,
      "loc": "drivers/clk/clk-fixed-rate.c:64",
      "file": "drivers/clk/clk-fixed-rate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-fixed-rate.c:clk_register_fixed_rate",
        "drivers/clk/x86/clk-fch.c:fch_clk_probe",
        "drivers/clk/x86/clk-fch.c:fch_clk_probe",
        "drivers/clk/x86/clk-fch.c:fch_clk_probe",
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589331008,
      "name": "__clk_hw_register_fixed_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 455
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
struct clk_hw * __clk_hw_register_fixed_rate(struct device * dev, struct device_node * np, const char * name, const char * parent_name, const struct clk_hw * parent_hw, const struct clk_parent_data * parent_data, long unsigned int flags, long unsigned int fixed_rate, long unsigned int fixed_accuracy, long unsigned int clk_fixed_flags, bool devm)
```

```json
{
  "name": "__clk_hw_register_fixed_rate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589629200,
      "name": "__clk_hw_register_fixed_rate",
      "external": true,
      "loc": "drivers/clk/clk-fixed-rate.c:64",
      "file": "drivers/clk/clk-fixed-rate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-fixed-rate.c:clk_register_fixed_rate",
        "drivers/clk/x86/clk-fch.c:fch_clk_probe",
        "drivers/clk/x86/clk-fch.c:fch_clk_probe",
        "drivers/clk/x86/clk-fch.c:fch_clk_probe",
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589629200,
      "name": "__clk_hw_register_fixed_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 455
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
struct clk_hw * __clk_hw_register_fixed_rate(struct device * dev, struct device_node * np, const char * name, const char * parent_name, const struct clk_hw * parent_hw, const struct clk_parent_data * parent_data, long unsigned int flags, long unsigned int fixed_rate, long unsigned int fixed_accuracy, long unsigned int clk_fixed_flags, bool devm)
```

```json
{
  "name": "__clk_hw_register_fixed_rate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589939152,
      "name": "__clk_hw_register_fixed_rate",
      "external": true,
      "loc": "drivers/clk/clk-fixed-rate.c:64",
      "file": "drivers/clk/clk-fixed-rate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-fixed-rate.c:clk_register_fixed_rate",
        "drivers/clk/x86/clk-fch.c:fch_clk_probe",
        "drivers/clk/x86/clk-fch.c:fch_clk_probe",
        "drivers/clk/x86/clk-fch.c:fch_clk_probe",
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589939152,
      "name": "__clk_hw_register_fixed_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 506
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
struct clk_hw * __clk_hw_register_fixed_rate(struct device * dev, struct device_node * np, const char * name, const char * parent_name, const struct clk_hw * parent_hw, const struct clk_parent_data * parent_data, long unsigned int flags, long unsigned int fixed_rate, long unsigned int fixed_accuracy, long unsigned int clk_fixed_flags)
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool devm</code>
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
