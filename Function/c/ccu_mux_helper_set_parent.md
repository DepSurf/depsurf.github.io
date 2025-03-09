# Function: <code>ccu_mux_helper_set_parent</code>

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
int ccu_mux_helper_set_parent(struct ccu_common * common, struct ccu_mux_internal * cm, u8 index)
```

```json
{
  "name": "ccu_mux_helper_set_parent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497980440,
      "name": "ccu_mux_helper_set_parent",
      "external": true,
      "loc": "drivers/clk/sunxi-ng/ccu_mux.c:178",
      "file": "drivers/clk/sunxi-ng/ccu_mux.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/sunxi-ng/ccu_div.c:ccu_div_set_parent",
        "drivers/clk/sunxi-ng/ccu_mux.c:ccu_mux_notifier_cb",
        "drivers/clk/sunxi-ng/ccu_mux.c:ccu_mux_notifier_cb",
        "drivers/clk/sunxi-ng/ccu_mux.c:ccu_mux_set_parent",
        "drivers/clk/sunxi-ng/ccu_mult.c:ccu_mult_set_parent",
        "drivers/clk/sunxi-ng/ccu_nkm.c:ccu_nkm_set_parent",
        "drivers/clk/sunxi-ng/ccu_mp.c:ccu_mp_set_parent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497980440,
      "name": "ccu_mux_helper_set_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
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
int ccu_mux_helper_set_parent(struct ccu_common * common, struct ccu_mux_internal * cm, u8 index)
```
</details>
</li>
</ul>
