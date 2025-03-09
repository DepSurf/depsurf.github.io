# Function: <code>mtk_pmx_set_mode</code>

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
int mtk_pmx_set_mode(struct pinctrl_dev * pctldev, long unsigned int pin, long unsigned int mode)
```

```json
{
  "name": "mtk_pmx_set_mode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496679400,
      "name": "mtk_pmx_set_mode",
      "external": false,
      "loc": "drivers/pinctrl/mediatek/pinctrl-mtk-common.c:673",
      "file": "drivers/pinctrl/mediatek/pinctrl-mtk-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_xt_set_gpio_as_eint",
        "drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pmx_gpio_request_enable",
        "drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pmx_set_mux"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496679400,
      "name": "mtk_pmx_set_mode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
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
int mtk_pmx_set_mode(struct pinctrl_dev * pctldev, long unsigned int pin, long unsigned int mode)
```

```json
{
  "name": "mtk_pmx_set_mode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229980636,
      "name": "mtk_pmx_set_mode",
      "external": false,
      "loc": "drivers/pinctrl/mediatek/pinctrl-mtk-common.c:673",
      "file": "drivers/pinctrl/mediatek/pinctrl-mtk-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_xt_set_gpio_as_eint",
        "drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pmx_gpio_request_enable",
        "drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pmx_set_mux"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229980636,
      "name": "mtk_pmx_set_mode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
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
int mtk_pmx_set_mode(struct pinctrl_dev * pctldev, long unsigned int pin, long unsigned int mode)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int mtk_pmx_set_mode(struct pinctrl_dev * pctldev, long unsigned int pin, long unsigned int mode)
```
</details>
</li>
</ul>
