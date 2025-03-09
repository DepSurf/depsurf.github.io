# Function: <code>owl_factor_helper_round_rate</code>

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
long int owl_factor_helper_round_rate(struct owl_clk_common * common, const struct owl_factor_hw * factor_hw, long unsigned int rate, long unsigned int * parent_rate)
```

```json
{
  "name": "owl_factor_helper_round_rate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497799624,
      "name": "owl_factor_helper_round_rate",
      "external": true,
      "loc": "drivers/clk/actions/owl-factor.c:120",
      "file": "drivers/clk/actions/owl-factor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/actions/owl-factor.c:owl_factor_round_rate",
        "drivers/clk/actions/owl-composite.c:owl_comp_fact_round_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497799624,
      "name": "owl_factor_helper_round_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 548
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
long int owl_factor_helper_round_rate(struct owl_clk_common * common, const struct owl_factor_hw * factor_hw, long unsigned int rate, long unsigned int * parent_rate)
```

```json
{
  "name": "owl_factor_helper_round_rate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230621680,
      "name": "owl_factor_helper_round_rate",
      "external": true,
      "loc": "drivers/clk/actions/owl-factor.c:120",
      "file": "drivers/clk/actions/owl-factor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/actions/owl-factor.c:owl_factor_round_rate",
        "drivers/clk/actions/owl-composite.c:owl_comp_fact_round_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230621680,
      "name": "owl_factor_helper_round_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 500
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
long int owl_factor_helper_round_rate(struct owl_clk_common * common, const struct owl_factor_hw * factor_hw, long unsigned int rate, long unsigned int * parent_rate)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
long int owl_factor_helper_round_rate(struct owl_clk_common * common, const struct owl_factor_hw * factor_hw, long unsigned int rate, long unsigned int * parent_rate)
```
</details>
</li>
</ul>
