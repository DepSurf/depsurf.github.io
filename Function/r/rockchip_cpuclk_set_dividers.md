# Function: <code>rockchip_cpuclk_set_dividers</code>

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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "rockchip_cpuclk_set_dividers",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497947976,
      "name": "rockchip_cpuclk_set_dividers",
      "external": false,
      "loc": "drivers/clk/rockchip/clk-cpu.c:102",
      "file": "drivers/clk/rockchip/clk-cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/rockchip/clk-cpu.c:rockchip_cpuclk_notifier_cb",
        "drivers/clk/rockchip/clk-cpu.c:rockchip_cpuclk_notifier_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497947976,
      "name": "rockchip_cpuclk_set_dividers.isra.0",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void rockchip_cpuclk_set_dividers(struct rockchip_cpuclk * cpuclk, const struct rockchip_cpuclk_rate_table * rate)
```

```json
{
  "name": "rockchip_cpuclk_set_dividers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230694900,
      "name": "rockchip_cpuclk_set_dividers",
      "external": false,
      "loc": "drivers/clk/rockchip/clk-cpu.c:102",
      "file": "drivers/clk/rockchip/clk-cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/rockchip/clk-cpu.c:rockchip_cpuclk_notifier_cb",
        "drivers/clk/rockchip/clk-cpu.c:rockchip_cpuclk_notifier_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230694900,
      "name": "rockchip_cpuclk_set_dividers",
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void rockchip_cpuclk_set_dividers(struct rockchip_cpuclk * cpuclk, const struct rockchip_cpuclk_rate_table * rate)
```
</details>
</li>
</ul>
