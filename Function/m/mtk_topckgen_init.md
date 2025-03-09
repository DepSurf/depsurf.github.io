# Function: <code>mtk_topckgen_init</code>

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
int mtk_topckgen_init(struct platform_device * pdev)
```

```json
{
  "name": "mtk_topckgen_init",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497905928,
      "name": "mtk_topckgen_init",
      "external": false,
      "loc": "drivers/clk/mediatek/clk-mt6797.c:383",
      "file": "drivers/clk/mediatek/clk-mt6797.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336497909872,
      "name": "mtk_topckgen_init",
      "external": false,
      "loc": "drivers/clk/mediatek/clk-mt7622.c:612",
      "file": "drivers/clk/mediatek/clk-mt7622.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336511153772,
      "name": "mtk_topckgen_init",
      "external": false,
      "loc": "drivers/clk/mediatek/clk-mt8173.c:924",
      "file": "drivers/clk/mediatek/clk-mt8173.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336511155028,
      "name": "mtk_topckgen_init",
      "external": false,
      "loc": "drivers/clk/mediatek/clk-mt8516.c:677",
      "file": "drivers/clk/mediatek/clk-mt8516.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497905928,
      "name": "mtk_topckgen_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
    },
    {
      "addr": 18446603336497909872,
      "name": "mtk_topckgen_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 432
    },
    {
      "addr": 18446603336511153772,
      "name": "mtk_topckgen_init",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 244
    },
    {
      "addr": 18446603336511155028,
      "name": "mtk_topckgen_init",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 280
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
int mtk_topckgen_init(struct platform_device * pdev)
```

```json
{
  "name": "mtk_topckgen_init",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230666036,
      "name": "mtk_topckgen_init",
      "external": false,
      "loc": "drivers/clk/mediatek/clk-mt7622.c:612",
      "file": "drivers/clk/mediatek/clk-mt7622.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3230668168,
      "name": "mtk_topckgen_init",
      "external": false,
      "loc": "drivers/clk/mediatek/clk-mt7629.c:572",
      "file": "drivers/clk/mediatek/clk-mt7629.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3243753184,
      "name": "mtk_topckgen_init",
      "external": false,
      "loc": "drivers/clk/mediatek/clk-mt8135.c:516",
      "file": "drivers/clk/mediatek/clk-mt8135.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3243754624,
      "name": "mtk_topckgen_init",
      "external": false,
      "loc": "drivers/clk/mediatek/clk-mt8173.c:924",
      "file": "drivers/clk/mediatek/clk-mt8173.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3243755176,
      "name": "mtk_topckgen_init",
      "external": false,
      "loc": "drivers/clk/mediatek/clk-mt8516.c:677",
      "file": "drivers/clk/mediatek/clk-mt8516.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3230666036,
      "name": "mtk_topckgen_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 392
    },
    {
      "addr": 3230668168,
      "name": "mtk_topckgen_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 336
    },
    {
      "addr": 3243753184,
      "name": "mtk_topckgen_init",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 216
    },
    {
      "addr": 3243754624,
      "name": "mtk_topckgen_init",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 220
    },
    {
      "addr": 3243755176,
      "name": "mtk_topckgen_init",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 264
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
int mtk_topckgen_init(struct platform_device * pdev)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int mtk_topckgen_init(struct platform_device * pdev)
```
</details>
</li>
</ul>
