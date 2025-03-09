# Function: <code>mvebu_pinctrl_find_setting_by_name</code>

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
  "name": "mvebu_pinctrl_find_setting_by_name",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496620904,
      "name": "mvebu_pinctrl_find_setting_by_name",
      "external": false,
      "loc": "drivers/pinctrl/mvebu/pinctrl-mvebu.c:121",
      "file": "drivers/pinctrl/mvebu/pinctrl-mvebu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinctrl_dt_node_to_map",
        "drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinmux_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496620904,
      "name": "mvebu_pinctrl_find_setting_by_name.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
struct mvebu_mpp_ctrl_setting * mvebu_pinctrl_find_setting_by_name(struct mvebu_pinctrl * pctl, struct mvebu_pinctrl_group * grp, const char * name)
```

```json
{
  "name": "mvebu_pinctrl_find_setting_by_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229916284,
      "name": "mvebu_pinctrl_find_setting_by_name",
      "external": false,
      "loc": "drivers/pinctrl/mvebu/pinctrl-mvebu.c:121",
      "file": "drivers/pinctrl/mvebu/pinctrl-mvebu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinctrl_dt_node_to_map",
        "drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinmux_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229916284,
      "name": "mvebu_pinctrl_find_setting_by_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
struct mvebu_mpp_ctrl_setting * mvebu_pinctrl_find_setting_by_name(struct mvebu_pinctrl * pctl, struct mvebu_pinctrl_group * grp, const char * name)
```
</details>
</li>
</ul>
