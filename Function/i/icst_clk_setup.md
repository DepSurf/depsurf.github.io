# Function: <code>icst_clk_setup</code>

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
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct clk * icst_clk_setup(struct device * dev, const struct clk_icst_desc * desc, const char * name, const char * parent_name, struct regmap * map, enum icst_control_type ctype)
```

```json
{
  "name": "icst_clk_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586706352,
      "name": "icst_clk_setup",
      "external": true,
      "loc": "drivers/clk/versatile/clk-icst.c:336",
      "file": "drivers/clk/versatile/clk-icst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/versatile/clk-icst.c:icst_clk_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586706352,
      "name": "icst_clk_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
    }
  ]
}
```
</details>
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct clk * icst_clk_setup(struct device * dev, const struct clk_icst_desc * desc, const char * name, const char * parent_name, struct regmap * map, enum icst_control_type ctype)
```

```json
{
  "name": "icst_clk_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230781048,
      "name": "icst_clk_setup",
      "external": false,
      "loc": "drivers/clk/versatile/clk-icst.c:347",
      "file": "drivers/clk/versatile/clk-icst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/versatile/clk-icst.c:of_syscon_icst_setup",
        "drivers/clk/versatile/clk-icst.c:icst_clk_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230781048,
      "name": "icst_clk_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 324
    }
  ]
}
```
</details>
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
struct clk * icst_clk_setup(struct device * dev, const struct clk_icst_desc * desc, const char * name, const char * parent_name, struct regmap * map, enum icst_control_type ctype)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
struct clk * icst_clk_setup(struct device * dev, const struct clk_icst_desc * desc, const char * name, const char * parent_name, struct regmap * map, enum icst_control_type ctype)
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
struct clk * icst_clk_setup(struct device * dev, const struct clk_icst_desc * desc, const char * name, const char * parent_name, struct regmap * map, enum icst_control_type ctype)
```
</details>
</li>
</ul>
