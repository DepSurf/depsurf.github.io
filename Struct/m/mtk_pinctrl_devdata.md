# Struct: <code>mtk_pinctrl_devdata</code>

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
struct mtk_pinctrl_devdata {
    const struct mtk_desc_pin * pins;
    unsigned int npins;
    const struct mtk_drv_group_desc * grp_desc;
    unsigned int n_grp_cls;
    const struct mtk_pin_drv_grp * pin_drv_grp;
    unsigned int n_pin_drv_grps;
    int (*)(struct regmap *, unsigned int, unsigned char, bool, unsigned int) spec_pull_set;
    int (*)(struct regmap *, unsigned int, unsigned char, int, enum pin_config_param) spec_ies_smt_set;
    void (*)(struct regmap *, unsigned int, unsigned int) spec_pinmux_set;
    void (*)(unsigned int *, unsigned int) spec_dir_set;
    unsigned int dir_offset;
    unsigned int ies_offset;
    unsigned int smt_offset;
    unsigned int pullen_offset;
    unsigned int pullsel_offset;
    unsigned int drv_offset;
    unsigned int dout_offset;
    unsigned int din_offset;
    unsigned int pinmux_offset;
    short unsigned int type1_start;
    short unsigned int type1_end;
    unsigned char port_shf;
    unsigned char port_mask;
    unsigned char port_align;
    struct mtk_eint_hw eint_hw;
    struct mtk_eint_regs * eint_regs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct mtk_pinctrl_devdata {
    const struct mtk_desc_pin * pins;
    unsigned int npins;
    const struct mtk_drv_group_desc * grp_desc;
    unsigned int n_grp_cls;
    const struct mtk_pin_drv_grp * pin_drv_grp;
    unsigned int n_pin_drv_grps;
    int (*)(struct regmap *, unsigned int, unsigned char, bool, unsigned int) spec_pull_set;
    int (*)(struct regmap *, unsigned int, unsigned char, int, enum pin_config_param) spec_ies_smt_set;
    void (*)(struct regmap *, unsigned int, unsigned int) spec_pinmux_set;
    void (*)(unsigned int *, unsigned int) spec_dir_set;
    unsigned int dir_offset;
    unsigned int ies_offset;
    unsigned int smt_offset;
    unsigned int pullen_offset;
    unsigned int pullsel_offset;
    unsigned int drv_offset;
    unsigned int dout_offset;
    unsigned int din_offset;
    unsigned int pinmux_offset;
    short unsigned int type1_start;
    short unsigned int type1_end;
    unsigned char port_shf;
    unsigned char port_mask;
    unsigned char port_align;
    struct mtk_eint_hw eint_hw;
    struct mtk_eint_regs * eint_regs;
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
struct mtk_pinctrl_devdata {
    const struct mtk_desc_pin * pins;
    unsigned int npins;
    const struct mtk_drv_group_desc * grp_desc;
    unsigned int n_grp_cls;
    const struct mtk_pin_drv_grp * pin_drv_grp;
    unsigned int n_pin_drv_grps;
    int (*)(struct regmap *, unsigned int, unsigned char, bool, unsigned int) spec_pull_set;
    int (*)(struct regmap *, unsigned int, unsigned char, int, enum pin_config_param) spec_ies_smt_set;
    void (*)(struct regmap *, unsigned int, unsigned int) spec_pinmux_set;
    void (*)(unsigned int *, unsigned int) spec_dir_set;
    unsigned int dir_offset;
    unsigned int ies_offset;
    unsigned int smt_offset;
    unsigned int pullen_offset;
    unsigned int pullsel_offset;
    unsigned int drv_offset;
    unsigned int dout_offset;
    unsigned int din_offset;
    unsigned int pinmux_offset;
    short unsigned int type1_start;
    short unsigned int type1_end;
    unsigned char port_shf;
    unsigned char port_mask;
    unsigned char port_align;
    struct mtk_eint_hw eint_hw;
    struct mtk_eint_regs * eint_regs;
}
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
struct mtk_pinctrl_devdata {
    const struct mtk_desc_pin * pins;
    unsigned int npins;
    const struct mtk_drv_group_desc * grp_desc;
    unsigned int n_grp_cls;
    const struct mtk_pin_drv_grp * pin_drv_grp;
    unsigned int n_pin_drv_grps;
    int (*)(struct regmap *, unsigned int, unsigned char, bool, unsigned int) spec_pull_set;
    int (*)(struct regmap *, unsigned int, unsigned char, int, enum pin_config_param) spec_ies_smt_set;
    void (*)(struct regmap *, unsigned int, unsigned int) spec_pinmux_set;
    void (*)(unsigned int *, unsigned int) spec_dir_set;
    unsigned int dir_offset;
    unsigned int ies_offset;
    unsigned int smt_offset;
    unsigned int pullen_offset;
    unsigned int pullsel_offset;
    unsigned int drv_offset;
    unsigned int dout_offset;
    unsigned int din_offset;
    unsigned int pinmux_offset;
    short unsigned int type1_start;
    short unsigned int type1_end;
    unsigned char port_shf;
    unsigned char port_mask;
    unsigned char port_align;
    struct mtk_eint_hw eint_hw;
    struct mtk_eint_regs * eint_regs;
}
```
</details>
</li>
</ul>
