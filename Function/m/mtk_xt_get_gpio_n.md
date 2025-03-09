# Function: <code>mtk_xt_get_gpio_n</code>

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
int mtk_xt_get_gpio_n(void * data, long unsigned int eint_n, unsigned int * gpio_n, struct gpio_chip * * gpio_chip)
```

```json
{
  "name": "mtk_xt_get_gpio_n",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496676752,
      "name": "mtk_xt_get_gpio_n",
      "external": false,
      "loc": "drivers/pinctrl/mediatek/pinctrl-mtk-common.c:927",
      "file": "drivers/pinctrl/mediatek/pinctrl-mtk-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336496687752,
      "name": "mtk_xt_get_gpio_n",
      "external": false,
      "loc": "drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:229",
      "file": "drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_xt_set_gpio_as_eint",
        "drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_xt_get_gpio_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496676752,
      "name": "mtk_xt_get_gpio_n",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    },
    {
      "addr": 18446603336496687752,
      "name": "mtk_xt_get_gpio_n",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
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
int mtk_xt_get_gpio_n(void * data, long unsigned int eint_n, unsigned int * gpio_n, struct gpio_chip * * gpio_chip)
```

```json
{
  "name": "mtk_xt_get_gpio_n",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229978468,
      "name": "mtk_xt_get_gpio_n",
      "external": false,
      "loc": "drivers/pinctrl/mediatek/pinctrl-mtk-common.c:927",
      "file": "drivers/pinctrl/mediatek/pinctrl-mtk-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3229988688,
      "name": "mtk_xt_get_gpio_n",
      "external": false,
      "loc": "drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:229",
      "file": "drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_xt_set_gpio_as_eint",
        "drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_xt_get_gpio_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229978468,
      "name": "mtk_xt_get_gpio_n",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    },
    {
      "addr": 3229988688,
      "name": "mtk_xt_get_gpio_n",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
int mtk_xt_get_gpio_n(void * data, long unsigned int eint_n, unsigned int * gpio_n, struct gpio_chip * * gpio_chip)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int mtk_xt_get_gpio_n(void * data, long unsigned int eint_n, unsigned int * gpio_n, struct gpio_chip * * gpio_chip)
```
</details>
</li>
</ul>
