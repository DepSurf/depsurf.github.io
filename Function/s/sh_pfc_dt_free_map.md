# Function: <code>sh_pfc_dt_free_map</code>

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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
void sh_pfc_dt_free_map(struct pinctrl_dev * pctldev, struct pinctrl_map * map, unsigned int num_maps)
```

```json
{
  "name": "sh_pfc_dt_free_map",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496647008,
      "name": "sh_pfc_dt_free_map",
      "external": false,
      "loc": "drivers/pinctrl/sh-pfc/pinctrl.c:241",
      "file": "drivers/pinctrl/sh-pfc/pinctrl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_dt_node_to_map"
      ],
      "caller_func": [
        "drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_dt_node_to_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496645592,
      "name": "sh_pfc_dt_free_map.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 18446603336496645728,
      "name": "sh_pfc_dt_free_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
void sh_pfc_dt_free_map(struct pinctrl_dev * pctldev, struct pinctrl_map * map, unsigned int num_maps)
```

```json
{
  "name": "sh_pfc_dt_free_map",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229961608,
      "name": "sh_pfc_dt_free_map",
      "external": false,
      "loc": "drivers/pinctrl/sh-pfc/pinctrl.c:241",
      "file": "drivers/pinctrl/sh-pfc/pinctrl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_dt_node_to_map"
      ],
      "caller_func": [
        "drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_dt_node_to_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229960164,
      "name": "sh_pfc_dt_free_map.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    },
    {
      "addr": 3229960272,
      "name": "sh_pfc_dt_free_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
void sh_pfc_dt_free_map(struct pinctrl_dev * pctldev, struct pinctrl_map * map, unsigned int num_maps)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void sh_pfc_dt_free_map(struct pinctrl_dev * pctldev, struct pinctrl_map * map, unsigned int num_maps)
```
</details>
</li>
</ul>
