# Function: <code>pinconf_generic_dt_node_to_map_group</code>

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
<summary>In <code>5.4.0-26-generic-arm64</code>: Duplicate ❓</summary>

```c
int pinconf_generic_dt_node_to_map_group(struct pinctrl_dev * pctldev, struct device_node * np_config, struct pinctrl_map * * map, unsigned int * num_maps)
```

```json
{
  "name": "pinconf_generic_dt_node_to_map_group",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496523920,
      "name": "pinconf_generic_dt_node_to_map_group",
      "external": false,
      "loc": "include/linux/pinctrl/pinconf-generic.h:194",
      "file": "drivers/pinctrl/pinctrl-amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336496627096,
      "name": "pinconf_generic_dt_node_to_map_group",
      "external": false,
      "loc": "include/linux/pinctrl/pinconf-generic.h:194",
      "file": "drivers/pinctrl/mvebu/pinctrl-armada-37xx.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336496631536,
      "name": "pinconf_generic_dt_node_to_map_group",
      "external": false,
      "loc": "include/linux/pinctrl/pinconf-generic.h:194",
      "file": "drivers/pinctrl/qcom/pinctrl-msm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496523920,
      "name": "pinconf_generic_dt_node_to_map_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446603336496627096,
      "name": "pinconf_generic_dt_node_to_map_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446603336496631536,
      "name": "pinconf_generic_dt_node_to_map_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Duplicate ❓</summary>

```c
int pinconf_generic_dt_node_to_map_group(struct pinctrl_dev * pctldev, struct device_node * np_config, struct pinctrl_map * * map, unsigned int * num_maps)
```

```json
{
  "name": "pinconf_generic_dt_node_to_map_group",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229832168,
      "name": "pinconf_generic_dt_node_to_map_group",
      "external": false,
      "loc": "include/linux/pinctrl/pinconf-generic.h:194",
      "file": "drivers/pinctrl/pinctrl-amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3229936208,
      "name": "pinconf_generic_dt_node_to_map_group",
      "external": false,
      "loc": "include/linux/pinctrl/pinconf-generic.h:194",
      "file": "drivers/pinctrl/qcom/pinctrl-msm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3229832168,
      "name": "pinconf_generic_dt_node_to_map_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 3229936208,
      "name": "pinconf_generic_dt_node_to_map_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
int pinconf_generic_dt_node_to_map_group(struct pinctrl_dev * pctldev, struct device_node * np_config, struct pinctrl_map * * map, unsigned int * num_maps)
```

```json
{
  "name": "pinconf_generic_dt_node_to_map_group",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290745520,
      "name": "pinconf_generic_dt_node_to_map_group",
      "external": false,
      "loc": "include/linux/pinctrl/pinconf-generic.h:194",
      "file": "drivers/pinctrl/pinctrl-amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290745520,
      "name": "pinconf_generic_dt_node_to_map_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
int pinconf_generic_dt_node_to_map_group(struct pinctrl_dev * pctldev, struct device_node * np_config, struct pinctrl_map * * map, unsigned int * num_maps)
```

```json
{
  "name": "pinconf_generic_dt_node_to_map_group",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275442870,
      "name": "pinconf_generic_dt_node_to_map_group",
      "external": false,
      "loc": "include/linux/pinctrl/pinconf-generic.h:194",
      "file": "drivers/pinctrl/pinctrl-amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275442870,
      "name": "pinconf_generic_dt_node_to_map_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
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
int pinconf_generic_dt_node_to_map_group(struct pinctrl_dev * pctldev, struct device_node * np_config, struct pinctrl_map * * map, unsigned int * num_maps)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int pinconf_generic_dt_node_to_map_group(struct pinctrl_dev * pctldev, struct device_node * np_config, struct pinctrl_map * * map, unsigned int * num_maps)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
int pinconf_generic_dt_node_to_map_group(struct pinctrl_dev * pctldev, struct device_node * np_config, struct pinctrl_map * * map, unsigned int * num_maps)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
int pinconf_generic_dt_node_to_map_group(struct pinctrl_dev * pctldev, struct device_node * np_config, struct pinctrl_map * * map, unsigned int * num_maps)
```
</details>
</li>
</ul>
