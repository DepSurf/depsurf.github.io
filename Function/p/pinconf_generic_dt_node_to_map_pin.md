# Function: <code>pinconf_generic_dt_node_to_map_pin</code>

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
int pinconf_generic_dt_node_to_map_pin(struct pinctrl_dev * pctldev, struct device_node * np_config, struct pinctrl_map * * map, unsigned int * num_maps)
```

```json
{
  "name": "pinconf_generic_dt_node_to_map_pin",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496522744,
      "name": "pinconf_generic_dt_node_to_map_pin",
      "external": false,
      "loc": "include/linux/pinctrl/pinconf-generic.h:202",
      "file": "drivers/pinctrl/pinctrl-as3722.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336496541832,
      "name": "pinconf_generic_dt_node_to_map_pin",
      "external": false,
      "loc": "include/linux/pinctrl/pinconf-generic.h:202",
      "file": "drivers/pinctrl/pinctrl-palmas.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336496571704,
      "name": "pinconf_generic_dt_node_to_map_pin",
      "external": false,
      "loc": "include/linux/pinctrl/pinconf-generic.h:202",
      "file": "drivers/pinctrl/pinctrl-sx150x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336496576664,
      "name": "pinconf_generic_dt_node_to_map_pin",
      "external": false,
      "loc": "include/linux/pinctrl/pinconf-generic.h:202",
      "file": "drivers/pinctrl/pinctrl-ocelot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336496597336,
      "name": "pinconf_generic_dt_node_to_map_pin",
      "external": false,
      "loc": "include/linux/pinctrl/pinconf-generic.h:202",
      "file": "drivers/pinctrl/bcm/pinctrl-iproc-gpio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336496604448,
      "name": "pinconf_generic_dt_node_to_map_pin",
      "external": false,
      "loc": "include/linux/pinctrl/pinconf-generic.h:202",
      "file": "drivers/pinctrl/bcm/pinctrl-ns2-mux.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496522744,
      "name": "pinconf_generic_dt_node_to_map_pin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446603336496541832,
      "name": "pinconf_generic_dt_node_to_map_pin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446603336496571704,
      "name": "pinconf_generic_dt_node_to_map_pin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446603336496576664,
      "name": "pinconf_generic_dt_node_to_map_pin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446603336496597336,
      "name": "pinconf_generic_dt_node_to_map_pin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446603336496604448,
      "name": "pinconf_generic_dt_node_to_map_pin",
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
int pinconf_generic_dt_node_to_map_pin(struct pinctrl_dev * pctldev, struct device_node * np_config, struct pinctrl_map * * map, unsigned int * num_maps)
```

```json
{
  "name": "pinconf_generic_dt_node_to_map_pin",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229827100,
      "name": "pinconf_generic_dt_node_to_map_pin",
      "external": false,
      "loc": "include/linux/pinctrl/pinconf-generic.h:202",
      "file": "drivers/pinctrl/pinctrl-as3722.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3229840212,
      "name": "pinconf_generic_dt_node_to_map_pin",
      "external": false,
      "loc": "include/linux/pinctrl/pinconf-generic.h:202",
      "file": "drivers/pinctrl/pinctrl-palmas.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3229882288,
      "name": "pinconf_generic_dt_node_to_map_pin",
      "external": false,
      "loc": "include/linux/pinctrl/pinconf-generic.h:202",
      "file": "drivers/pinctrl/pinctrl-sx150x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3229893832,
      "name": "pinconf_generic_dt_node_to_map_pin",
      "external": false,
      "loc": "include/linux/pinctrl/pinconf-generic.h:202",
      "file": "drivers/pinctrl/pinctrl-ocelot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3230905272,
      "name": "pinconf_generic_dt_node_to_map_pin",
      "external": false,
      "loc": "include/linux/pinctrl/pinconf-generic.h:202",
      "file": "drivers/soc/tegra/pmc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3233334784,
      "name": "pinconf_generic_dt_node_to_map_pin",
      "external": false,
      "loc": "include/linux/pinctrl/pinconf-generic.h:202",
      "file": "drivers/rtc/rtc-omap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3229827100,
      "name": "pinconf_generic_dt_node_to_map_pin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 3229840212,
      "name": "pinconf_generic_dt_node_to_map_pin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 3229882288,
      "name": "pinconf_generic_dt_node_to_map_pin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 3229893832,
      "name": "pinconf_generic_dt_node_to_map_pin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 3230905272,
      "name": "pinconf_generic_dt_node_to_map_pin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 3233334784,
      "name": "pinconf_generic_dt_node_to_map_pin",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Duplicate ❓</summary>

```c
int pinconf_generic_dt_node_to_map_pin(struct pinctrl_dev * pctldev, struct device_node * np_config, struct pinctrl_map * * map, unsigned int * num_maps)
```

```json
{
  "name": "pinconf_generic_dt_node_to_map_pin",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290744000,
      "name": "pinconf_generic_dt_node_to_map_pin",
      "external": false,
      "loc": "include/linux/pinctrl/pinconf-generic.h:202",
      "file": "drivers/pinctrl/pinctrl-as3722.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055290757648,
      "name": "pinconf_generic_dt_node_to_map_pin",
      "external": false,
      "loc": "include/linux/pinctrl/pinconf-generic.h:202",
      "file": "drivers/pinctrl/pinctrl-palmas.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055290777968,
      "name": "pinconf_generic_dt_node_to_map_pin",
      "external": false,
      "loc": "include/linux/pinctrl/pinconf-generic.h:202",
      "file": "drivers/pinctrl/pinctrl-sx150x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055290781568,
      "name": "pinconf_generic_dt_node_to_map_pin",
      "external": false,
      "loc": "include/linux/pinctrl/pinconf-generic.h:202",
      "file": "drivers/pinctrl/pinctrl-ocelot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290744000,
      "name": "pinconf_generic_dt_node_to_map_pin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 13835058055290757648,
      "name": "pinconf_generic_dt_node_to_map_pin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 13835058055290777968,
      "name": "pinconf_generic_dt_node_to_map_pin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 13835058055290781568,
      "name": "pinconf_generic_dt_node_to_map_pin",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Duplicate ❓</summary>

```c
int pinconf_generic_dt_node_to_map_pin(struct pinctrl_dev * pctldev, struct device_node * np_config, struct pinctrl_map * * map, unsigned int * num_maps)
```

```json
{
  "name": "pinconf_generic_dt_node_to_map_pin",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275438358,
      "name": "pinconf_generic_dt_node_to_map_pin",
      "external": false,
      "loc": "include/linux/pinctrl/pinconf-generic.h:202",
      "file": "drivers/pinctrl/pinctrl-as3722.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936275446324,
      "name": "pinconf_generic_dt_node_to_map_pin",
      "external": false,
      "loc": "include/linux/pinctrl/pinconf-generic.h:202",
      "file": "drivers/pinctrl/pinctrl-palmas.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936275459058,
      "name": "pinconf_generic_dt_node_to_map_pin",
      "external": false,
      "loc": "include/linux/pinctrl/pinconf-generic.h:202",
      "file": "drivers/pinctrl/pinctrl-sx150x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936275461470,
      "name": "pinconf_generic_dt_node_to_map_pin",
      "external": false,
      "loc": "include/linux/pinctrl/pinconf-generic.h:202",
      "file": "drivers/pinctrl/pinctrl-ocelot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275438358,
      "name": "pinconf_generic_dt_node_to_map_pin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446743936275446324,
      "name": "pinconf_generic_dt_node_to_map_pin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446743936275459058,
      "name": "pinconf_generic_dt_node_to_map_pin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446743936275461470,
      "name": "pinconf_generic_dt_node_to_map_pin",
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
int pinconf_generic_dt_node_to_map_pin(struct pinctrl_dev * pctldev, struct device_node * np_config, struct pinctrl_map * * map, unsigned int * num_maps)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int pinconf_generic_dt_node_to_map_pin(struct pinctrl_dev * pctldev, struct device_node * np_config, struct pinctrl_map * * map, unsigned int * num_maps)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
int pinconf_generic_dt_node_to_map_pin(struct pinctrl_dev * pctldev, struct device_node * np_config, struct pinctrl_map * * map, unsigned int * num_maps)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
int pinconf_generic_dt_node_to_map_pin(struct pinctrl_dev * pctldev, struct device_node * np_config, struct pinctrl_map * * map, unsigned int * num_maps)
```
</details>
</li>
</ul>
