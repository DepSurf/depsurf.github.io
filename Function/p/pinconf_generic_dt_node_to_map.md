# Function: <code>pinconf_generic_dt_node_to_map</code>

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
int pinconf_generic_dt_node_to_map(struct pinctrl_dev * pctldev, struct device_node * np_config, struct pinctrl_map * * map, unsigned int * num_maps, enum pinctrl_map_type type)
```

```json
{
  "name": "pinconf_generic_dt_node_to_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496520008,
      "name": "pinconf_generic_dt_node_to_map",
      "external": true,
      "loc": "drivers/pinctrl/pinconf-generic.c:374",
      "file": "drivers/pinctrl/pinconf-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-as3722.c:pinconf_generic_dt_node_to_map_pin",
        "drivers/pinctrl/pinctrl-amd.c:pinconf_generic_dt_node_to_map_group",
        "drivers/pinctrl/pinctrl-bm1880.c:pinconf_generic_dt_node_to_map_all",
        "drivers/pinctrl/meson/pinctrl-meson.c:pinconf_generic_dt_node_to_map_all",
        "drivers/pinctrl/pinctrl-palmas.c:pinconf_generic_dt_node_to_map_pin",
        "drivers/pinctrl/pinctrl-sx150x.c:pinconf_generic_dt_node_to_map_pin",
        "drivers/pinctrl/pinctrl-ocelot.c:pinconf_generic_dt_node_to_map_pin",
        "drivers/pinctrl/actions/pinctrl-owl.c:pinconf_generic_dt_node_to_map_all",
        "drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_pctl_dt_node_to_map",
        "drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:pinconf_generic_dt_node_to_map_pin",
        "drivers/pinctrl/bcm/pinctrl-ns2-mux.c:pinconf_generic_dt_node_to_map_pin",
        "drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:pinconf_generic_dt_node_to_map_group",
        "drivers/pinctrl/qcom/pinctrl-msm.c:pinconf_generic_dt_node_to_map_group",
        "drivers/pinctrl/mediatek/pinctrl-moore.c:pinconf_generic_dt_node_to_map_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496520008,
      "name": "pinconf_generic_dt_node_to_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
int pinconf_generic_dt_node_to_map(struct pinctrl_dev * pctldev, struct device_node * np_config, struct pinctrl_map * * map, unsigned int * num_maps, enum pinctrl_map_type type)
```

```json
{
  "name": "pinconf_generic_dt_node_to_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229824708,
      "name": "pinconf_generic_dt_node_to_map",
      "external": true,
      "loc": "drivers/pinctrl/pinconf-generic.c:374",
      "file": "drivers/pinctrl/pinconf-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-as3722.c:pinconf_generic_dt_node_to_map_pin",
        "drivers/pinctrl/pinctrl-amd.c:pinconf_generic_dt_node_to_map_group",
        "drivers/pinctrl/meson/pinctrl-meson.c:pinconf_generic_dt_node_to_map_all",
        "drivers/pinctrl/pinctrl-palmas.c:pinconf_generic_dt_node_to_map_pin",
        "drivers/pinctrl/pinctrl-sx150x.c:pinconf_generic_dt_node_to_map_pin",
        "drivers/pinctrl/pinctrl-ocelot.c:pinconf_generic_dt_node_to_map_pin",
        "drivers/pinctrl/actions/pinctrl-owl.c:pinconf_generic_dt_node_to_map_all",
        "drivers/pinctrl/aspeed/pinctrl-aspeed-g6.c:pinconf_generic_dt_node_to_map_all",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm7xx_dt_node_to_map",
        "drivers/pinctrl/qcom/pinctrl-msm.c:pinconf_generic_dt_node_to_map_group",
        "drivers/pinctrl/uniphier/pinctrl-uniphier-core.c:pinconf_generic_dt_node_to_map_all",
        "drivers/pinctrl/mediatek/pinctrl-moore.c:pinconf_generic_dt_node_to_map_all",
        "drivers/soc/tegra/pmc.c:pinconf_generic_dt_node_to_map_pin",
        "drivers/rtc/rtc-omap.c:pinconf_generic_dt_node_to_map_pin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229824708,
      "name": "pinconf_generic_dt_node_to_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int pinconf_generic_dt_node_to_map(struct pinctrl_dev * pctldev, struct device_node * np_config, struct pinctrl_map * * map, unsigned int * num_maps, enum pinctrl_map_type type)
```

```json
{
  "name": "pinconf_generic_dt_node_to_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290740304,
      "name": "pinconf_generic_dt_node_to_map",
      "external": true,
      "loc": "drivers/pinctrl/pinconf-generic.c:374",
      "file": "drivers/pinctrl/pinconf-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-as3722.c:pinconf_generic_dt_node_to_map_pin",
        "drivers/pinctrl/pinctrl-amd.c:pinconf_generic_dt_node_to_map_group",
        "drivers/pinctrl/pinctrl-palmas.c:pinconf_generic_dt_node_to_map_pin",
        "drivers/pinctrl/pinctrl-sx150x.c:pinconf_generic_dt_node_to_map_pin",
        "drivers/pinctrl/pinctrl-ocelot.c:pinconf_generic_dt_node_to_map_pin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290740304,
      "name": "pinconf_generic_dt_node_to_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int pinconf_generic_dt_node_to_map(struct pinctrl_dev * pctldev, struct device_node * np_config, struct pinctrl_map * * map, unsigned int * num_maps, enum pinctrl_map_type type)
```

```json
{
  "name": "pinconf_generic_dt_node_to_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275436044,
      "name": "pinconf_generic_dt_node_to_map",
      "external": true,
      "loc": "drivers/pinctrl/pinconf-generic.c:374",
      "file": "drivers/pinctrl/pinconf-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-as3722.c:pinconf_generic_dt_node_to_map_pin",
        "drivers/pinctrl/pinctrl-amd.c:pinconf_generic_dt_node_to_map_group",
        "drivers/pinctrl/pinctrl-palmas.c:pinconf_generic_dt_node_to_map_pin",
        "drivers/pinctrl/pinctrl-sx150x.c:pinconf_generic_dt_node_to_map_pin",
        "drivers/pinctrl/pinctrl-ocelot.c:pinconf_generic_dt_node_to_map_pin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275436044,
      "name": "pinconf_generic_dt_node_to_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
    }
  ]
}
```
</details>
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
int pinconf_generic_dt_node_to_map(struct pinctrl_dev * pctldev, struct device_node * np_config, struct pinctrl_map * * map, unsigned int * num_maps, enum pinctrl_map_type type)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int pinconf_generic_dt_node_to_map(struct pinctrl_dev * pctldev, struct device_node * np_config, struct pinctrl_map * * map, unsigned int * num_maps, enum pinctrl_map_type type)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
int pinconf_generic_dt_node_to_map(struct pinctrl_dev * pctldev, struct device_node * np_config, struct pinctrl_map * * map, unsigned int * num_maps, enum pinctrl_map_type type)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
int pinconf_generic_dt_node_to_map(struct pinctrl_dev * pctldev, struct device_node * np_config, struct pinctrl_map * * map, unsigned int * num_maps, enum pinctrl_map_type type)
```
</details>
</li>
</ul>
