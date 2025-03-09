# Function: <code>pinconf_generic_dt_node_to_map_all</code>

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
<summary>In <code>5.4.0-26-generic-arm64</code>: Duplicate, Selective Inline ❓</summary>

```c
int pinconf_generic_dt_node_to_map_all(struct pinctrl_dev * pctldev, struct device_node * np_config, struct pinctrl_map * * map, unsigned int * num_maps)
```

```json
{
  "name": "pinconf_generic_dt_node_to_map_all",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496532904,
      "name": "pinconf_generic_dt_node_to_map_all",
      "external": false,
      "loc": "include/linux/pinctrl/pinconf-generic.h:210",
      "file": "drivers/pinctrl/pinctrl-bm1880.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336496535424,
      "name": "pinconf_generic_dt_node_to_map_all",
      "external": false,
      "loc": "include/linux/pinctrl/pinconf-generic.h:210",
      "file": "drivers/pinctrl/meson/pinctrl-meson.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336496579792,
      "name": "pinconf_generic_dt_node_to_map_all",
      "external": false,
      "loc": "include/linux/pinctrl/pinconf-generic.h:210",
      "file": "drivers/pinctrl/actions/pinctrl-owl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336496590320,
      "name": "pinconf_generic_dt_node_to_map_all",
      "external": false,
      "loc": "include/linux/pinctrl/pinconf-generic.h:210",
      "file": "drivers/pinctrl/bcm/pinctrl-bcm2835.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_pctl_dt_node_to_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496686048,
      "name": "pinconf_generic_dt_node_to_map_all",
      "external": false,
      "loc": "include/linux/pinctrl/pinconf-generic.h:210",
      "file": "drivers/pinctrl/mediatek/pinctrl-moore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496532904,
      "name": "pinconf_generic_dt_node_to_map_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446603336496535424,
      "name": "pinconf_generic_dt_node_to_map_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446603336496579792,
      "name": "pinconf_generic_dt_node_to_map_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446603336496686048,
      "name": "pinconf_generic_dt_node_to_map_all",
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
int pinconf_generic_dt_node_to_map_all(struct pinctrl_dev * pctldev, struct device_node * np_config, struct pinctrl_map * * map, unsigned int * num_maps)
```

```json
{
  "name": "pinconf_generic_dt_node_to_map_all",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229834572,
      "name": "pinconf_generic_dt_node_to_map_all",
      "external": false,
      "loc": "include/linux/pinctrl/pinconf-generic.h:210",
      "file": "drivers/pinctrl/meson/pinctrl-meson.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3229899512,
      "name": "pinconf_generic_dt_node_to_map_all",
      "external": false,
      "loc": "include/linux/pinctrl/pinconf-generic.h:210",
      "file": "drivers/pinctrl/actions/pinctrl-owl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3229907176,
      "name": "pinconf_generic_dt_node_to_map_all",
      "external": false,
      "loc": "include/linux/pinctrl/pinconf-generic.h:210",
      "file": "drivers/pinctrl/aspeed/pinctrl-aspeed-g6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3229973012,
      "name": "pinconf_generic_dt_node_to_map_all",
      "external": false,
      "loc": "include/linux/pinctrl/pinconf-generic.h:210",
      "file": "drivers/pinctrl/uniphier/pinctrl-uniphier-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3229987052,
      "name": "pinconf_generic_dt_node_to_map_all",
      "external": false,
      "loc": "include/linux/pinctrl/pinconf-generic.h:210",
      "file": "drivers/pinctrl/mediatek/pinctrl-moore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3229834572,
      "name": "pinconf_generic_dt_node_to_map_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 3229899512,
      "name": "pinconf_generic_dt_node_to_map_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 3229907176,
      "name": "pinconf_generic_dt_node_to_map_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 3229973012,
      "name": "pinconf_generic_dt_node_to_map_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 3229987052,
      "name": "pinconf_generic_dt_node_to_map_all",
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
int pinconf_generic_dt_node_to_map_all(struct pinctrl_dev * pctldev, struct device_node * np_config, struct pinctrl_map * * map, unsigned int * num_maps)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int pinconf_generic_dt_node_to_map_all(struct pinctrl_dev * pctldev, struct device_node * np_config, struct pinctrl_map * * map, unsigned int * num_maps)
```
</details>
</li>
</ul>
