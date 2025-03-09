# Function: <code>sunxi_usb_clk_setup</code>

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
void sunxi_usb_clk_setup(struct device_node * node, const struct usb_clk_data * data, spinlock_t * lock)
```

```json
{
  "name": "sunxi_usb_clk_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336511184968,
      "name": "sunxi_usb_clk_setup",
      "external": false,
      "loc": "drivers/clk/sunxi/clk-usb.c:88",
      "file": "drivers/clk/sunxi/clk-usb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/sunxi/clk-usb.c:sun9i_a80_usb_phy_setup",
        "drivers/clk/sunxi/clk-usb.c:sun9i_a80_usb_mod_setup",
        "drivers/clk/sunxi/clk-usb.c:sun8i_h3_usb_setup",
        "drivers/clk/sunxi/clk-usb.c:sun8i_a23_usb_setup",
        "drivers/clk/sunxi/clk-usb.c:sun6i_a31_usb_setup",
        "drivers/clk/sunxi/clk-usb.c:sun5i_a13_usb_setup",
        "drivers/clk/sunxi/clk-usb.c:sun4i_a10_usb_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336511184968,
      "name": "sunxi_usb_clk_setup",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 628
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
void sunxi_usb_clk_setup(struct device_node * node, const struct usb_clk_data * data, spinlock_t * lock)
```
</details>
</li>
</ul>
