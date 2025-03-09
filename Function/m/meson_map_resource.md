# Function: <code>meson_map_resource</code>

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
  "name": "meson_map_resource",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496537016,
      "name": "meson_map_resource",
      "external": false,
      "loc": "drivers/pinctrl/meson/pinctrl-meson.c:620",
      "file": "drivers/pinctrl/meson/pinctrl-meson.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/meson/pinctrl-meson.c:meson_pinctrl_probe",
        "drivers/pinctrl/meson/pinctrl-meson.c:meson_pinctrl_probe",
        "drivers/pinctrl/meson/pinctrl-meson.c:meson_pinctrl_probe",
        "drivers/pinctrl/meson/pinctrl-meson.c:meson_pinctrl_probe",
        "drivers/pinctrl/meson/pinctrl-meson.c:meson_pinctrl_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496537016,
      "name": "meson_map_resource.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
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
struct regmap * meson_map_resource(struct meson_pinctrl * pc, struct device_node * node, char * name)
```

```json
{
  "name": "meson_map_resource",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229834664,
      "name": "meson_map_resource",
      "external": false,
      "loc": "drivers/pinctrl/meson/pinctrl-meson.c:620",
      "file": "drivers/pinctrl/meson/pinctrl-meson.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/meson/pinctrl-meson.c:meson_pinctrl_probe",
        "drivers/pinctrl/meson/pinctrl-meson.c:meson_pinctrl_probe",
        "drivers/pinctrl/meson/pinctrl-meson.c:meson_pinctrl_probe",
        "drivers/pinctrl/meson/pinctrl-meson.c:meson_pinctrl_probe",
        "drivers/pinctrl/meson/pinctrl-meson.c:meson_pinctrl_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229834664,
      "name": "meson_map_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
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
struct regmap * meson_map_resource(struct meson_pinctrl * pc, struct device_node * node, char * name)
```
</details>
</li>
</ul>
