# Function: <code>usb2_clock_sel_enable_extal_only</code>

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
void usb2_clock_sel_enable_extal_only(struct usb2_clock_sel_priv * priv)
```

```json
{
  "name": "usb2_clock_sel_enable_extal_only",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497935336,
      "name": "usb2_clock_sel_enable_extal_only",
      "external": false,
      "loc": "drivers/clk/renesas/rcar-usb2-clock-sel.c:37",
      "file": "drivers/clk/renesas/rcar-usb2-clock-sel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_resume",
        "drivers/clk/renesas/rcar-usb2-clock-sel.c:usb2_clock_sel_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497935336,
      "name": "usb2_clock_sel_enable_extal_only",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void usb2_clock_sel_enable_extal_only(struct usb2_clock_sel_priv * priv)
```

```json
{
  "name": "usb2_clock_sel_enable_extal_only",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3230681684,
      "name": "usb2_clock_sel_enable_extal_only",
      "external": false,
      "loc": "drivers/clk/renesas/rcar-usb2-clock-sel.c:37",
      "file": "drivers/clk/renesas/rcar-usb2-clock-sel.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_resume",
        "drivers/clk/renesas/rcar-usb2-clock-sel.c:usb2_clock_sel_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230681684,
      "name": "usb2_clock_sel_enable_extal_only",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
void usb2_clock_sel_enable_extal_only(struct usb2_clock_sel_priv * priv)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void usb2_clock_sel_enable_extal_only(struct usb2_clock_sel_priv * priv)
```
</details>
</li>
</ul>
