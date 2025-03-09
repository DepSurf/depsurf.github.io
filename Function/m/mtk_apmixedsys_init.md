# Function: <code>mtk_apmixedsys_init</code>

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
int mtk_apmixedsys_init(struct platform_device * pdev)
```

```json
{
  "name": "mtk_apmixedsys_init",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497905624,
      "name": "mtk_apmixedsys_init",
      "external": false,
      "loc": "drivers/clk/mediatek/clk-mt6797.c:664",
      "file": "drivers/clk/mediatek/clk-mt6797.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336497909624,
      "name": "mtk_apmixedsys_init",
      "external": false,
      "loc": "drivers/clk/mediatek/clk-mt7622.c:671",
      "file": "drivers/clk/mediatek/clk-mt7622.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336511154016,
      "name": "mtk_apmixedsys_init",
      "external": false,
      "loc": "drivers/clk/mediatek/clk-mt8173.c:1078",
      "file": "drivers/clk/mediatek/clk-mt8173.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336511155500,
      "name": "mtk_apmixedsys_init",
      "external": false,
      "loc": "drivers/clk/mediatek/clk-mt8516.c:787",
      "file": "drivers/clk/mediatek/clk-mt8516.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497905624,
      "name": "mtk_apmixedsys_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    },
    {
      "addr": 18446603336497909624,
      "name": "mtk_apmixedsys_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
    },
    {
      "addr": 18446603336511154016,
      "name": "mtk_apmixedsys_init",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 348
    },
    {
      "addr": 18446603336511155500,
      "name": "mtk_apmixedsys_init",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 164
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
int mtk_apmixedsys_init(struct platform_device * pdev)
```

```json
{
  "name": "mtk_apmixedsys_init",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230665808,
      "name": "mtk_apmixedsys_init",
      "external": false,
      "loc": "drivers/clk/mediatek/clk-mt7622.c:671",
      "file": "drivers/clk/mediatek/clk-mt7622.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3230667940,
      "name": "mtk_apmixedsys_init",
      "external": false,
      "loc": "drivers/clk/mediatek/clk-mt7629.c:652",
      "file": "drivers/clk/mediatek/clk-mt7629.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3243753120,
      "name": "mtk_apmixedsys_init",
      "external": false,
      "loc": "drivers/clk/mediatek/clk-mt8135.c:626",
      "file": "drivers/clk/mediatek/clk-mt8135.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3243754844,
      "name": "mtk_apmixedsys_init",
      "external": false,
      "loc": "drivers/clk/mediatek/clk-mt8173.c:1078",
      "file": "drivers/clk/mediatek/clk-mt8173.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3243755604,
      "name": "mtk_apmixedsys_init",
      "external": false,
      "loc": "drivers/clk/mediatek/clk-mt8516.c:787",
      "file": "drivers/clk/mediatek/clk-mt8516.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3230665808,
      "name": "mtk_apmixedsys_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
    },
    {
      "addr": 3230667940,
      "name": "mtk_apmixedsys_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
    },
    {
      "addr": 3243753120,
      "name": "mtk_apmixedsys_init",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 3243754844,
      "name": "mtk_apmixedsys_init",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 332
    },
    {
      "addr": 3243755604,
      "name": "mtk_apmixedsys_init",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 148
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
int mtk_apmixedsys_init(struct platform_device * pdev)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int mtk_apmixedsys_init(struct platform_device * pdev)
```
</details>
</li>
</ul>
