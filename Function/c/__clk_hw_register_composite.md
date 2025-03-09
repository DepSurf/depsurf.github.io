# Function: <code>__clk_hw_register_composite</code>

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
struct clk_hw * __clk_hw_register_composite(struct device * dev, const char * name, const const char * * parent_names, const struct clk_parent_data * pdata, int num_parents, struct clk_hw * mux_hw, const struct clk_ops * mux_ops, struct clk_hw * rate_hw, const struct clk_ops * rate_ops, struct clk_hw * gate_hw, const struct clk_ops * gate_ops, long unsigned int flags)
```

```json
{
  "name": "__clk_hw_register_composite",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586205072,
      "name": "__clk_hw_register_composite",
      "external": false,
      "loc": "drivers/clk/clk-composite.c:202",
      "file": "drivers/clk/clk-composite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-composite.c:clk_register_composite_pdata",
        "drivers/clk/clk-composite.c:clk_register_composite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586205072,
      "name": "__clk_hw_register_composite",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 781
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
struct clk_hw * __clk_hw_register_composite(struct device * dev, const char * name, const const char * * parent_names, const struct clk_parent_data * pdata, int num_parents, struct clk_hw * mux_hw, const struct clk_ops * mux_ops, struct clk_hw * rate_hw, const struct clk_ops * rate_ops, struct clk_hw * gate_hw, const struct clk_ops * gate_ops, long unsigned int flags)
```

```json
{
  "name": "__clk_hw_register_composite",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586324432,
      "name": "__clk_hw_register_composite",
      "external": false,
      "loc": "drivers/clk/clk-composite.c:203",
      "file": "drivers/clk/clk-composite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-composite.c:devm_clk_hw_register_composite_pdata",
        "drivers/clk/clk-composite.c:clk_register_composite_pdata",
        "drivers/clk/clk-composite.c:clk_register_composite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586324432,
      "name": "__clk_hw_register_composite",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 781
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
struct clk_hw * __clk_hw_register_composite(struct device * dev, const char * name, const const char * * parent_names, const struct clk_parent_data * pdata, int num_parents, struct clk_hw * mux_hw, const struct clk_ops * mux_ops, struct clk_hw * rate_hw, const struct clk_ops * rate_ops, struct clk_hw * gate_hw, const struct clk_ops * gate_ops, long unsigned int flags)
```

```json
{
  "name": "__clk_hw_register_composite",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586198496,
      "name": "__clk_hw_register_composite",
      "external": false,
      "loc": "drivers/clk/clk-composite.c:203",
      "file": "drivers/clk/clk-composite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-composite.c:devm_clk_hw_register_composite_pdata",
        "drivers/clk/clk-composite.c:clk_register_composite_pdata",
        "drivers/clk/clk-composite.c:clk_register_composite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586198496,
      "name": "__clk_hw_register_composite",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 779
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
struct clk_hw * __clk_hw_register_composite(struct device * dev, const char * name, const const char * * parent_names, const struct clk_parent_data * pdata, int num_parents, struct clk_hw * mux_hw, const struct clk_ops * mux_ops, struct clk_hw * rate_hw, const struct clk_ops * rate_ops, struct clk_hw * gate_hw, const struct clk_ops * gate_ops, long unsigned int flags)
```

```json
{
  "name": "__clk_hw_register_composite",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586701536,
      "name": "__clk_hw_register_composite",
      "external": false,
      "loc": "drivers/clk/clk-composite.c:203",
      "file": "drivers/clk/clk-composite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-composite.c:devm_clk_hw_register_composite_pdata",
        "drivers/clk/clk-composite.c:clk_register_composite_pdata",
        "drivers/clk/clk-composite.c:clk_register_composite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586701536,
      "name": "__clk_hw_register_composite",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 779
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
struct clk_hw * __clk_hw_register_composite(struct device * dev, const char * name, const const char * * parent_names, const struct clk_parent_data * pdata, int num_parents, struct clk_hw * mux_hw, const struct clk_ops * mux_ops, struct clk_hw * rate_hw, const struct clk_ops * rate_ops, struct clk_hw * gate_hw, const struct clk_ops * gate_ops, long unsigned int flags)
```

```json
{
  "name": "__clk_hw_register_composite",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587973952,
      "name": "__clk_hw_register_composite",
      "external": false,
      "loc": "drivers/clk/clk-composite.c:232",
      "file": "drivers/clk/clk-composite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-composite.c:devm_clk_hw_register_composite_pdata",
        "drivers/clk/clk-composite.c:clk_register_composite_pdata",
        "drivers/clk/clk-composite.c:clk_register_composite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587973952,
      "name": "__clk_hw_register_composite",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 834
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
struct clk_hw * __clk_hw_register_composite(struct device * dev, const char * name, const const char * * parent_names, const struct clk_parent_data * pdata, int num_parents, struct clk_hw * mux_hw, const struct clk_ops * mux_ops, struct clk_hw * rate_hw, const struct clk_ops * rate_ops, struct clk_hw * gate_hw, const struct clk_ops * gate_ops, long unsigned int flags)
```

```json
{
  "name": "__clk_hw_register_composite",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589337072,
      "name": "__clk_hw_register_composite",
      "external": false,
      "loc": "drivers/clk/clk-composite.c:234",
      "file": "drivers/clk/clk-composite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-composite.c:devm_clk_hw_register_composite_pdata",
        "drivers/clk/clk-composite.c:clk_register_composite_pdata",
        "drivers/clk/clk-composite.c:clk_register_composite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589337072,
      "name": "__clk_hw_register_composite",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 834
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
struct clk_hw * __clk_hw_register_composite(struct device * dev, const char * name, const const char * * parent_names, const struct clk_parent_data * pdata, int num_parents, struct clk_hw * mux_hw, const struct clk_ops * mux_ops, struct clk_hw * rate_hw, const struct clk_ops * rate_ops, struct clk_hw * gate_hw, const struct clk_ops * gate_ops, long unsigned int flags)
```

```json
{
  "name": "__clk_hw_register_composite",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589635328,
      "name": "__clk_hw_register_composite",
      "external": false,
      "loc": "drivers/clk/clk-composite.c:237",
      "file": "drivers/clk/clk-composite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-composite.c:devm_clk_hw_register_composite_pdata",
        "drivers/clk/clk-composite.c:clk_register_composite_pdata",
        "drivers/clk/clk-composite.c:clk_register_composite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589635328,
      "name": "__clk_hw_register_composite",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 834
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
struct clk_hw * __clk_hw_register_composite(struct device * dev, const char * name, const const char * * parent_names, const struct clk_parent_data * pdata, int num_parents, struct clk_hw * mux_hw, const struct clk_ops * mux_ops, struct clk_hw * rate_hw, const struct clk_ops * rate_ops, struct clk_hw * gate_hw, const struct clk_ops * gate_ops, long unsigned int flags)
```

```json
{
  "name": "__clk_hw_register_composite",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589945424,
      "name": "__clk_hw_register_composite",
      "external": false,
      "loc": "drivers/clk/clk-composite.c:237",
      "file": "drivers/clk/clk-composite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-composite.c:devm_clk_hw_register_composite_pdata",
        "drivers/clk/clk-composite.c:clk_register_composite_pdata",
        "drivers/clk/clk-composite.c:clk_register_composite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589945424,
      "name": "__clk_hw_register_composite",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 881
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
struct clk_hw * __clk_hw_register_composite(struct device * dev, const char * name, const const char * * parent_names, const struct clk_parent_data * pdata, int num_parents, struct clk_hw * mux_hw, const struct clk_ops * mux_ops, struct clk_hw * rate_hw, const struct clk_ops * rate_ops, struct clk_hw * gate_hw, const struct clk_ops * gate_ops, long unsigned int flags)
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
