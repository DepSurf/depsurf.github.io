# Function: <code>mtk_pinctrl_init</code>

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
int mtk_pinctrl_init()
```

```json
{
  "name": "mtk_pinctrl_init",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336511094000,
      "name": "mtk_pinctrl_init",
      "external": false,
      "loc": "drivers/pinctrl/mediatek/pinctrl-mt2712.c:609",
      "file": "drivers/pinctrl/mediatek/pinctrl-mt2712.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336511094160,
      "name": "mtk_pinctrl_init",
      "external": false,
      "loc": "drivers/pinctrl/mediatek/pinctrl-mt8173.c:364",
      "file": "drivers/pinctrl/mediatek/pinctrl-mt8173.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336511094240,
      "name": "mtk_pinctrl_init",
      "external": false,
      "loc": "drivers/pinctrl/mediatek/pinctrl-mt8516.c:358",
      "file": "drivers/pinctrl/mediatek/pinctrl-mt8516.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336511094000,
      "name": "mtk_pinctrl_init",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446603336511094160,
      "name": "mtk_pinctrl_init",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446603336511094240,
      "name": "mtk_pinctrl_init",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 40
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
int mtk_pinctrl_init()
```

```json
{
  "name": "mtk_pinctrl_init",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3243573984,
      "name": "mtk_pinctrl_init",
      "external": false,
      "loc": "drivers/pinctrl/mediatek/pinctrl-mt2701.c:555",
      "file": "drivers/pinctrl/mediatek/pinctrl-mt2701.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3243574024,
      "name": "mtk_pinctrl_init",
      "external": false,
      "loc": "drivers/pinctrl/mediatek/pinctrl-mt8135.c:336",
      "file": "drivers/pinctrl/mediatek/pinctrl-mt8135.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3243574064,
      "name": "mtk_pinctrl_init",
      "external": false,
      "loc": "drivers/pinctrl/mediatek/pinctrl-mt8127.c:321",
      "file": "drivers/pinctrl/mediatek/pinctrl-mt8127.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3243574104,
      "name": "mtk_pinctrl_init",
      "external": false,
      "loc": "drivers/pinctrl/mediatek/pinctrl-mt7623.c:1437",
      "file": "drivers/pinctrl/mediatek/pinctrl-mt7623.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3243573984,
      "name": "mtk_pinctrl_init",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 3243574024,
      "name": "mtk_pinctrl_init",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 3243574064,
      "name": "mtk_pinctrl_init",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 3243574104,
      "name": "mtk_pinctrl_init",
      "section": ".init.text",
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
int mtk_pinctrl_init()
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int mtk_pinctrl_init()
```
</details>
</li>
</ul>
