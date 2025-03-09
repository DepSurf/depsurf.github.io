# Function: <code>mtk_clk_register_gates</code>

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
int mtk_clk_register_gates(struct device_node * node, const struct mtk_gate * clks, int num, struct clk_onecell_data * clk_data)
```

```json
{
  "name": "mtk_clk_register_gates",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497896000,
      "name": "mtk_clk_register_gates",
      "external": true,
      "loc": "drivers/clk/mediatek/clk-mtk.c:141",
      "file": "drivers/clk/mediatek/clk-mtk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/mediatek/clk-mt6779.c:clk_mt6779_infra_probe",
        "drivers/clk/mediatek/clk-mt6779.c:clk_mt6779_apmixed_probe",
        "drivers/clk/mediatek/clk-mt6779-mm.c:clk_mt6779_mm_probe",
        "drivers/clk/mediatek/clk-mt6779-img.c:clk_mt6779_img_probe",
        "drivers/clk/mediatek/clk-mt6779-ipe.c:clk_mt6779_ipe_probe",
        "drivers/clk/mediatek/clk-mt6779-cam.c:clk_mt6779_cam_probe",
        "drivers/clk/mediatek/clk-mt6779-vdec.c:clk_mt6779_vdec_probe",
        "drivers/clk/mediatek/clk-mt6779-venc.c:clk_mt6779_venc_probe",
        "drivers/clk/mediatek/clk-mt6779-mfg.c:clk_mt6779_mfg_probe",
        "drivers/clk/mediatek/clk-mt6779-aud.c:clk_mt6779_aud_probe",
        "drivers/clk/mediatek/clk-mt6797.c:mtk_infrasys_init",
        "drivers/clk/mediatek/clk-mt6797-img.c:clk_mt6797_img_probe",
        "drivers/clk/mediatek/clk-mt6797-mm.c:clk_mt6797_mm_probe",
        "drivers/clk/mediatek/clk-mt6797-vdec.c:clk_mt6797_vdec_probe",
        "drivers/clk/mediatek/clk-mt6797-venc.c:clk_mt6797_venc_probe",
        "drivers/clk/mediatek/clk-mt2712.c:clk_mt2712_peri_probe",
        "drivers/clk/mediatek/clk-mt2712.c:clk_mt2712_infra_probe",
        "drivers/clk/mediatek/clk-mt2712.c:clk_mt2712_top_probe",
        "drivers/clk/mediatek/clk-mt2712-bdp.c:clk_mt2712_bdp_probe",
        "drivers/clk/mediatek/clk-mt2712-img.c:clk_mt2712_img_probe",
        "drivers/clk/mediatek/clk-mt2712-jpgdec.c:clk_mt2712_jpgdec_probe",
        "drivers/clk/mediatek/clk-mt2712-mfg.c:clk_mt2712_mfg_probe",
        "drivers/clk/mediatek/clk-mt2712-mm.c:clk_mt2712_mm_probe",
        "drivers/clk/mediatek/clk-mt2712-vdec.c:clk_mt2712_vdec_probe",
        "drivers/clk/mediatek/clk-mt2712-venc.c:clk_mt2712_venc_probe",
        "drivers/clk/mediatek/clk-mt7622.c:mtk_pericfg_init",
        "drivers/clk/mediatek/clk-mt7622.c:mtk_apmixedsys_init",
        "drivers/clk/mediatek/clk-mt7622.c:mtk_infrasys_init",
        "drivers/clk/mediatek/clk-mt7622.c:mtk_topckgen_init",
        "drivers/clk/mediatek/clk-mt7622-eth.c:clk_mt7622_sgmiisys_init",
        "drivers/clk/mediatek/clk-mt7622-eth.c:clk_mt7622_ethsys_init",
        "drivers/clk/mediatek/clk-mt7622-hif.c:clk_mt7622_pciesys_init",
        "drivers/clk/mediatek/clk-mt7622-hif.c:clk_mt7622_ssusbsys_init",
        "drivers/clk/mediatek/clk-mt7622-aud.c:clk_mt7622_audiosys_init",
        "drivers/clk/mediatek/clk-mt8173.c:mtk_vencltsys_init",
        "drivers/clk/mediatek/clk-mt8173.c:mtk_vencsys_init",
        "drivers/clk/mediatek/clk-mt8173.c:mtk_vdecsys_init",
        "drivers/clk/mediatek/clk-mt8173.c:mtk_mmsys_init",
        "drivers/clk/mediatek/clk-mt8173.c:mtk_imgsys_init",
        "drivers/clk/mediatek/clk-mt8173.c:mtk_pericfg_init",
        "drivers/clk/mediatek/clk-mt8173.c:mtk_infrasys_init",
        "drivers/clk/mediatek/clk-mt8183.c:clk_mt8183_peri_probe",
        "drivers/clk/mediatek/clk-mt8183.c:clk_mt8183_infra_probe",
        "drivers/clk/mediatek/clk-mt8183.c:clk_mt8183_top_probe",
        "drivers/clk/mediatek/clk-mt8183.c:clk_mt8183_apmixed_probe",
        "drivers/clk/mediatek/clk-mt8183-audio.c:clk_mt8183_audio_probe",
        "drivers/clk/mediatek/clk-mt8183-cam.c:clk_mt8183_cam_probe",
        "drivers/clk/mediatek/clk-mt8183-img.c:clk_mt8183_img_probe",
        "drivers/clk/mediatek/clk-mt8183-ipu0.c:clk_mt8183_ipu_core0_probe",
        "drivers/clk/mediatek/clk-mt8183-ipu1.c:clk_mt8183_ipu_core1_probe",
        "drivers/clk/mediatek/clk-mt8183-ipu_adl.c:clk_mt8183_ipu_adl_probe",
        "drivers/clk/mediatek/clk-mt8183-ipu_conn.c:clk_mt8183_ipu_conn_probe",
        "drivers/clk/mediatek/clk-mt8183-mm.c:clk_mt8183_mm_probe",
        "drivers/clk/mediatek/clk-mt8183-vdec.c:clk_mt8183_vdec_probe",
        "drivers/clk/mediatek/clk-mt8183-venc.c:clk_mt8183_venc_probe",
        "drivers/clk/mediatek/clk-mt8516.c:mtk_topckgen_init",
        "drivers/clk/mediatek/clk-mt8516-aud.c:mtk_audsys_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497896000,
      "name": "mtk_clk_register_gates",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
int mtk_clk_register_gates(struct device_node * node, const struct mtk_gate * clks, int num, struct clk_onecell_data * clk_data)
```

```json
{
  "name": "mtk_clk_register_gates",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230657792,
      "name": "mtk_clk_register_gates",
      "external": true,
      "loc": "drivers/clk/mediatek/clk-mtk.c:141",
      "file": "drivers/clk/mediatek/clk-mtk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/mediatek/clk-mt7622.c:mtk_pericfg_init",
        "drivers/clk/mediatek/clk-mt7622.c:mtk_apmixedsys_init",
        "drivers/clk/mediatek/clk-mt7622.c:mtk_infrasys_init",
        "drivers/clk/mediatek/clk-mt7622.c:mtk_topckgen_init",
        "drivers/clk/mediatek/clk-mt7622-eth.c:clk_mt7622_sgmiisys_init",
        "drivers/clk/mediatek/clk-mt7622-eth.c:clk_mt7622_ethsys_init",
        "drivers/clk/mediatek/clk-mt7622-hif.c:clk_mt7622_pciesys_init",
        "drivers/clk/mediatek/clk-mt7622-hif.c:clk_mt7622_ssusbsys_init",
        "drivers/clk/mediatek/clk-mt7622-aud.c:clk_mt7622_audiosys_init",
        "drivers/clk/mediatek/clk-mt7629.c:mtk_apmixedsys_init",
        "drivers/clk/mediatek/clk-mt7629.c:mtk_pericfg_init",
        "drivers/clk/mediatek/clk-mt7629.c:mtk_infrasys_init",
        "drivers/clk/mediatek/clk-mt7629-eth.c:clk_mt7629_sgmiisys_init",
        "drivers/clk/mediatek/clk-mt7629-eth.c:clk_mt7629_ethsys_init",
        "drivers/clk/mediatek/clk-mt7629-hif.c:clk_mt7629_pciesys_init",
        "drivers/clk/mediatek/clk-mt7629-hif.c:clk_mt7629_ssusbsys_init",
        "drivers/clk/mediatek/clk-mt8135.c:mtk_pericfg_init",
        "drivers/clk/mediatek/clk-mt8135.c:mtk_infrasys_init",
        "drivers/clk/mediatek/clk-mt8173.c:mtk_vencltsys_init",
        "drivers/clk/mediatek/clk-mt8173.c:mtk_vencsys_init",
        "drivers/clk/mediatek/clk-mt8173.c:mtk_vdecsys_init",
        "drivers/clk/mediatek/clk-mt8173.c:mtk_mmsys_init",
        "drivers/clk/mediatek/clk-mt8173.c:mtk_imgsys_init",
        "drivers/clk/mediatek/clk-mt8173.c:mtk_pericfg_init",
        "drivers/clk/mediatek/clk-mt8173.c:mtk_infrasys_init",
        "drivers/clk/mediatek/clk-mt8516.c:mtk_topckgen_init",
        "drivers/clk/mediatek/clk-mt8516-aud.c:mtk_audsys_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230657792,
      "name": "mtk_clk_register_gates",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
int mtk_clk_register_gates(struct device_node * node, const struct mtk_gate * clks, int num, struct clk_onecell_data * clk_data)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int mtk_clk_register_gates(struct device_node * node, const struct mtk_gate * clks, int num, struct clk_onecell_data * clk_data)
```
</details>
</li>
</ul>
