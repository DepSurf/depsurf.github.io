# Function: <code>omap_i2c_reset</code>

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
  "name": "omap_i2c_reset",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336500888780,
      "name": "omap_i2c_reset",
      "external": false,
      "loc": "drivers/i2c/busses/i2c-omap.c:309",
      "file": "drivers/i2c/busses/i2c-omap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_msg",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_msg"
      ],
      "caller_func": [
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_msg",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500884664,
      "name": "omap_i2c_reset.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
int omap_i2c_reset(struct omap_hwmod * oh)
```

```json
{
  "name": "omap_i2c_reset",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224594656,
      "name": "omap_i2c_reset",
      "external": true,
      "loc": "arch/arm/mach-omap2/i2c.c:36",
      "file": "arch/arm/mach-omap2/i2c.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3233405684,
      "name": "omap_i2c_reset",
      "external": false,
      "loc": "drivers/i2c/busses/i2c-omap.c:309",
      "file": "drivers/i2c/busses/i2c-omap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_msg",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_msg"
      ],
      "caller_func": [
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_msg",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233402964,
      "name": "omap_i2c_reset.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
    },
    {
      "addr": 3224594656,
      "name": "omap_i2c_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int omap_i2c_reset(struct omap_hwmod * oh)
```
</details>
</li>
</ul>
