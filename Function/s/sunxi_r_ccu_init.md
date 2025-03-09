# Function: <code>sunxi_r_ccu_init</code>

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
<summary>In <code>5.4.0-26-generic-arm64</code>: Collision, Selective Inline ❓</summary>

```c
void sunxi_r_ccu_init(struct device_node * node, const struct sunxi_ccu_desc * desc)
```

```json
{
  "name": "sunxi_r_ccu_init",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336511186592,
      "name": "sunxi_r_ccu_init",
      "external": false,
      "loc": "drivers/clk/sunxi-ng/ccu-sun50i-h6-r.c:188",
      "file": "drivers/clk/sunxi-ng/ccu-sun50i-h6-r.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/sunxi-ng/ccu-sun50i-h6-r.c:sun50i_h6_r_ccu_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336511187052,
      "name": "sunxi_r_ccu_init",
      "external": false,
      "loc": "drivers/clk/sunxi-ng/ccu-sun8i-r.c:257",
      "file": "drivers/clk/sunxi-ng/ccu-sun8i-r.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/sunxi-ng/ccu-sun8i-r.c:sun50i_a64_r_ccu_setup",
        "drivers/clk/sunxi-ng/ccu-sun8i-r.c:sun8i_h3_r_ccu_setup",
        "drivers/clk/sunxi-ng/ccu-sun8i-r.c:sun8i_a83t_r_ccu_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336511187052,
      "name": "sunxi_r_ccu_init",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 116
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
void sunxi_r_ccu_init(struct device_node * node, const struct sunxi_ccu_desc * desc)
```
</details>
</li>
</ul>
