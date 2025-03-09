# Function: <code>sun6i_rtc_clk_init</code>

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
void sun6i_rtc_clk_init(struct device_node * node, const struct sun6i_rtc_clk_data * data)
```

```json
{
  "name": "sun6i_rtc_clk_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336511250600,
      "name": "sun6i_rtc_clk_init",
      "external": false,
      "loc": "drivers/rtc/rtc-sun6i.c:214",
      "file": "drivers/rtc/rtc-sun6i.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/rtc-sun6i.c:sun8i_v3_rtc_clk_of_clk_init_driver",
        "drivers/rtc/rtc-sun6i.c:sun8i_r40_rtc_clk_of_clk_init_driver",
        "drivers/rtc/rtc-sun6i.c:sun50i_h6_rtc_clk_of_clk_init_driver",
        "drivers/rtc/rtc-sun6i.c:sun8i_h3_rtc_clk_of_clk_init_driver",
        "drivers/rtc/rtc-sun6i.c:sun8i_a23_rtc_clk_of_clk_init_driver",
        "drivers/rtc/rtc-sun6i.c:sun6i_a31_rtc_clk_of_clk_init_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336511250600,
      "name": "sun6i_rtc_clk_init",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 816
    }
  ]
}
```
</details>
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
void sun6i_rtc_clk_init(struct device_node * node, const struct sun6i_rtc_clk_data * data)
```
</details>
</li>
</ul>
