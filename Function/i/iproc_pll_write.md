# Function: <code>iproc_pll_write</code>

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
void iproc_pll_write(const struct iproc_pll * pll, void * base, const u32 offset, u32 val)
```

```json
{
  "name": "iproc_pll_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497805624,
      "name": "iproc_pll_write",
      "external": false,
      "loc": "drivers/clk/bcm/clk-iproc-pll.c:173",
      "file": "drivers/clk/bcm/clk-iproc-pll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/bcm/clk-iproc-pll.c:iproc_pll_clk_setup",
        "drivers/clk/bcm/clk-iproc-pll.c:iproc_clk_set_rate",
        "drivers/clk/bcm/clk-iproc-pll.c:iproc_clk_disable",
        "drivers/clk/bcm/clk-iproc-pll.c:iproc_clk_enable",
        "drivers/clk/bcm/clk-iproc-pll.c:iproc_clk_enable",
        "drivers/clk/bcm/clk-iproc-pll.c:iproc_pll_disable",
        "drivers/clk/bcm/clk-iproc-pll.c:iproc_pll_disable",
        "drivers/clk/bcm/clk-iproc-pll.c:iproc_pll_disable",
        "drivers/clk/bcm/clk-iproc-pll.c:iproc_pll_disable",
        "drivers/clk/bcm/clk-iproc-pll.c:pll_set_rate",
        "drivers/clk/bcm/clk-iproc-pll.c:pll_set_rate",
        "drivers/clk/bcm/clk-iproc-pll.c:pll_set_rate",
        "drivers/clk/bcm/clk-iproc-pll.c:pll_set_rate",
        "drivers/clk/bcm/clk-iproc-pll.c:pll_set_rate",
        "drivers/clk/bcm/clk-iproc-pll.c:pll_set_rate",
        "drivers/clk/bcm/clk-iproc-pll.c:pll_set_rate",
        "drivers/clk/bcm/clk-iproc-pll.c:pll_set_rate",
        "drivers/clk/bcm/clk-iproc-pll.c:pll_set_rate",
        "drivers/clk/bcm/clk-iproc-pll.c:pll_set_rate",
        "drivers/clk/bcm/clk-iproc-pll.c:pll_set_rate",
        "drivers/clk/bcm/clk-iproc-pll.c:__pll_enable",
        "drivers/clk/bcm/clk-iproc-pll.c:__pll_enable",
        "drivers/clk/bcm/clk-iproc-pll.c:__pll_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497805624,
      "name": "iproc_pll_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
void iproc_pll_write(const struct iproc_pll * pll, void * base, const u32 offset, u32 val)
```
</details>
</li>
</ul>
