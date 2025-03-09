# Function: <code>mtk_gpio_set</code>

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
<summary>In <code>5.4.0-26-generic-arm64</code>: Collision ❓</summary>

```c
void mtk_gpio_set(struct gpio_chip * chip, unsigned int offset, int value)
```

```json
{
  "name": "mtk_gpio_set",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496677704,
      "name": "mtk_gpio_set",
      "external": false,
      "loc": "drivers/pinctrl/mediatek/pinctrl-mtk-common.c:92",
      "file": "drivers/pinctrl/mediatek/pinctrl-mtk-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_gpio_direction_output",
        "drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pconf_group_set"
      ]
    },
    {
      "addr": 18446603336496686072,
      "name": "mtk_gpio_set",
      "external": false,
      "loc": "drivers/pinctrl/mediatek/pinctrl-moore.c:446",
      "file": "drivers/pinctrl/mediatek/pinctrl-moore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_gpio_direction_output"
      ]
    },
    {
      "addr": 18446603336496694672,
      "name": "mtk_gpio_set",
      "external": false,
      "loc": "drivers/pinctrl/mediatek/pinctrl-paris.c:720",
      "file": "drivers/pinctrl/mediatek/pinctrl-paris.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/mediatek/pinctrl-paris.c:mtk_gpio_direction_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496677704,
      "name": "mtk_gpio_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    },
    {
      "addr": 18446603336496686072,
      "name": "mtk_gpio_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    },
    {
      "addr": 18446603336496694672,
      "name": "mtk_gpio_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Collision ❓</summary>

```c
void mtk_gpio_set(struct gpio_chip * chip, unsigned int offset, int value)
```

```json
{
  "name": "mtk_gpio_set",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229979280,
      "name": "mtk_gpio_set",
      "external": false,
      "loc": "drivers/pinctrl/mediatek/pinctrl-mtk-common.c:92",
      "file": "drivers/pinctrl/mediatek/pinctrl-mtk-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_gpio_direction_output",
        "drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pconf_group_set"
      ]
    },
    {
      "addr": 3229987088,
      "name": "mtk_gpio_set",
      "external": false,
      "loc": "drivers/pinctrl/mediatek/pinctrl-moore.c:446",
      "file": "drivers/pinctrl/mediatek/pinctrl-moore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_gpio_direction_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229979280,
      "name": "mtk_gpio_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    },
    {
      "addr": 3229987088,
      "name": "mtk_gpio_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
void mtk_gpio_set(struct gpio_chip * chip, unsigned int offset, int value)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void mtk_gpio_set(struct gpio_chip * chip, unsigned int offset, int value)
```
</details>
</li>
</ul>
