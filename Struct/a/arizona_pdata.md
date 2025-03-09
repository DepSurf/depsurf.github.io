# Struct: <code>arizona_pdata</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct arizona_pdata {
    int reset;
    int ldoena;
    struct regulator_init_data * micvdd;
    struct regulator_init_data * ldo1;
    int clk32k_src;
    unsigned int irq_flags;
    int gpio_base;
    unsigned int[5] gpio_defaults;
    unsigned int[3] max_channels_clocked;
    bool jd_gpio5;
    bool jd_gpio5_nopull;
    bool jd_invert;
    bool hpdet_acc_id;
    bool hpdet_acc_id_line;
    int hpdet_id_gpio;
    unsigned int hpdet_channel;
    bool micd_software_compare;
    unsigned int micd_detect_debounce;
    int micd_pol_gpio;
    unsigned int micd_bias_start_time;
    unsigned int micd_rate;
    unsigned int micd_dbtime;
    unsigned int micd_timeout;
    bool micd_force_micbias;
    const struct arizona_micd_range * micd_ranges;
    int num_micd_ranges;
    struct arizona_micd_config * micd_configs;
    int num_micd_configs;
    int[4] dmic_ref;
    struct arizona_micbias[3] micbias;
    int[4] inmode;
    bool[6] out_mono;
    unsigned int[2] spk_mute;
    unsigned int[2] spk_fmt;
    unsigned int hap_act;
    int irq_gpio;
    unsigned int gpsw;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct arizona_pdata {
    int reset;
    int ldoena;
    struct regulator_init_data * micvdd;
    struct regulator_init_data * ldo1;
    int clk32k_src;
    unsigned int irq_flags;
    int gpio_base;
    unsigned int[5] gpio_defaults;
    unsigned int[3] max_channels_clocked;
    bool jd_gpio5;
    bool jd_gpio5_nopull;
    bool jd_invert;
    bool hpdet_acc_id;
    bool hpdet_acc_id_line;
    int hpdet_id_gpio;
    unsigned int hpdet_channel;
    bool micd_software_compare;
    unsigned int micd_detect_debounce;
    int micd_pol_gpio;
    unsigned int micd_bias_start_time;
    unsigned int micd_rate;
    unsigned int micd_dbtime;
    unsigned int micd_timeout;
    bool micd_force_micbias;
    const struct arizona_micd_range * micd_ranges;
    int num_micd_ranges;
    struct arizona_micd_config * micd_configs;
    int num_micd_configs;
    int[4] dmic_ref;
    struct arizona_micbias[3] micbias;
    int[4] inmode;
    int[6] out_mono;
    unsigned int[2] spk_mute;
    unsigned int[2] spk_fmt;
    unsigned int hap_act;
    int irq_gpio;
    unsigned int gpsw;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct arizona_pdata {
    int reset;
    int ldoena;
    struct regulator_init_data * micvdd;
    struct regulator_init_data * ldo1;
    int clk32k_src;
    unsigned int irq_flags;
    int gpio_base;
    unsigned int[5] gpio_defaults;
    unsigned int[3] max_channels_clocked;
    bool jd_gpio5;
    bool jd_gpio5_nopull;
    bool jd_invert;
    bool hpdet_acc_id;
    bool hpdet_acc_id_line;
    int hpdet_id_gpio;
    unsigned int hpdet_channel;
    bool micd_software_compare;
    unsigned int micd_detect_debounce;
    int micd_pol_gpio;
    unsigned int micd_bias_start_time;
    unsigned int micd_rate;
    unsigned int micd_dbtime;
    unsigned int micd_timeout;
    bool micd_force_micbias;
    const struct arizona_micd_range * micd_ranges;
    int num_micd_ranges;
    struct arizona_micd_config * micd_configs;
    int num_micd_configs;
    int[4] dmic_ref;
    struct arizona_micbias[3] micbias;
    int[4] inmode;
    int[6] out_mono;
    unsigned int[2] spk_mute;
    unsigned int[2] spk_fmt;
    unsigned int hap_act;
    int irq_gpio;
    unsigned int gpsw;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct arizona_pdata {
    int reset;
    struct arizona_micsupp_pdata micvdd;
    struct arizona_ldo1_pdata ldo1;
    int clk32k_src;
    unsigned int irq_flags;
    int gpio_base;
    unsigned int[5] gpio_defaults;
    unsigned int[3] max_channels_clocked;
    bool jd_gpio5;
    bool jd_gpio5_nopull;
    bool jd_invert;
    bool hpdet_acc_id;
    bool hpdet_acc_id_line;
    int hpdet_id_gpio;
    unsigned int hpdet_channel;
    bool micd_software_compare;
    unsigned int micd_detect_debounce;
    int micd_pol_gpio;
    unsigned int micd_bias_start_time;
    unsigned int micd_rate;
    unsigned int micd_dbtime;
    unsigned int micd_timeout;
    bool micd_force_micbias;
    const struct arizona_micd_range * micd_ranges;
    int num_micd_ranges;
    struct arizona_micd_config * micd_configs;
    int num_micd_configs;
    int[4] dmic_ref;
    struct arizona_micbias[3] micbias;
    int[4] inmode;
    int[6] out_mono;
    unsigned int[2] spk_mute;
    unsigned int[2] spk_fmt;
    unsigned int hap_act;
    int irq_gpio;
    unsigned int gpsw;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct arizona_pdata {
    int reset;
    struct arizona_micsupp_pdata micvdd;
    struct arizona_ldo1_pdata ldo1;
    int clk32k_src;
    unsigned int irq_flags;
    int gpio_base;
    unsigned int[5] gpio_defaults;
    unsigned int[3] max_channels_clocked;
    bool jd_gpio5;
    bool jd_gpio5_nopull;
    bool jd_invert;
    bool hpdet_acc_id;
    bool hpdet_acc_id_line;
    int hpdet_id_gpio;
    unsigned int hpdet_channel;
    bool micd_software_compare;
    unsigned int micd_detect_debounce;
    int micd_pol_gpio;
    unsigned int micd_bias_start_time;
    unsigned int micd_rate;
    unsigned int micd_dbtime;
    unsigned int micd_timeout;
    bool micd_force_micbias;
    const struct arizona_micd_range * micd_ranges;
    int num_micd_ranges;
    struct arizona_micd_config * micd_configs;
    int num_micd_configs;
    int[4] dmic_ref;
    struct arizona_micbias[3] micbias;
    int[4] inmode;
    int[6] out_mono;
    unsigned int[12] out_vol_limit;
    unsigned int[2] spk_mute;
    unsigned int[2] spk_fmt;
    unsigned int hap_act;
    int irq_gpio;
    unsigned int gpsw;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct arizona_pdata {
    struct gpio_desc * reset;
    struct arizona_micsupp_pdata micvdd;
    struct arizona_ldo1_pdata ldo1;
    int clk32k_src;
    unsigned int irq_flags;
    int gpio_base;
    unsigned int[5] gpio_defaults;
    unsigned int[3] max_channels_clocked;
    bool jd_gpio5;
    bool jd_gpio5_nopull;
    bool jd_invert;
    bool hpdet_acc_id;
    bool hpdet_acc_id_line;
    int hpdet_id_gpio;
    unsigned int hpdet_channel;
    bool micd_software_compare;
    unsigned int micd_detect_debounce;
    int micd_pol_gpio;
    unsigned int micd_bias_start_time;
    unsigned int micd_rate;
    unsigned int micd_dbtime;
    unsigned int micd_timeout;
    bool micd_force_micbias;
    const struct arizona_micd_range * micd_ranges;
    int num_micd_ranges;
    struct arizona_micd_config * micd_configs;
    int num_micd_configs;
    int[4] dmic_ref;
    struct arizona_micbias[3] micbias;
    int[4] inmode;
    int[6] out_mono;
    unsigned int[12] out_vol_limit;
    unsigned int[2] spk_mute;
    unsigned int[2] spk_fmt;
    unsigned int hap_act;
    int irq_gpio;
    unsigned int gpsw;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct arizona_pdata {
    struct gpio_desc * reset;
    struct arizona_micsupp_pdata micvdd;
    struct arizona_ldo1_pdata ldo1;
    int clk32k_src;
    unsigned int irq_flags;
    int gpio_base;
    unsigned int[5] gpio_defaults;
    unsigned int[3] max_channels_clocked;
    bool jd_gpio5;
    bool jd_gpio5_nopull;
    bool jd_invert;
    bool hpdet_acc_id;
    bool hpdet_acc_id_line;
    int hpdet_id_gpio;
    unsigned int hpdet_channel;
    bool micd_software_compare;
    unsigned int micd_detect_debounce;
    int micd_pol_gpio;
    unsigned int micd_bias_start_time;
    unsigned int micd_rate;
    unsigned int micd_dbtime;
    unsigned int micd_timeout;
    bool micd_force_micbias;
    const struct arizona_micd_range * micd_ranges;
    int num_micd_ranges;
    struct arizona_micd_config * micd_configs;
    int num_micd_configs;
    int[4] dmic_ref;
    struct arizona_micbias[3] micbias;
    int[4] inmode;
    int[6] out_mono;
    unsigned int[12] out_vol_limit;
    unsigned int[2] spk_mute;
    unsigned int[2] spk_fmt;
    unsigned int hap_act;
    int irq_gpio;
    unsigned int gpsw;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct arizona_pdata {
    struct gpio_desc * reset;
    struct arizona_micsupp_pdata micvdd;
    struct arizona_ldo1_pdata ldo1;
    int clk32k_src;
    unsigned int irq_flags;
    int gpio_base;
    unsigned int[5] gpio_defaults;
    unsigned int[3] max_channels_clocked;
    bool jd_gpio5;
    bool jd_gpio5_nopull;
    bool jd_invert;
    bool hpdet_acc_id;
    bool hpdet_acc_id_line;
    int hpdet_id_gpio;
    unsigned int hpdet_channel;
    bool micd_software_compare;
    unsigned int micd_detect_debounce;
    int micd_pol_gpio;
    unsigned int micd_bias_start_time;
    unsigned int micd_rate;
    unsigned int micd_dbtime;
    unsigned int micd_timeout;
    bool micd_force_micbias;
    const struct arizona_micd_range * micd_ranges;
    int num_micd_ranges;
    struct arizona_micd_config * micd_configs;
    int num_micd_configs;
    int[4] dmic_ref;
    struct arizona_micbias[3] micbias;
    int[4] inmode;
    int[6] out_mono;
    unsigned int[12] out_vol_limit;
    unsigned int[2] spk_mute;
    unsigned int[2] spk_fmt;
    unsigned int hap_act;
    int irq_gpio;
    unsigned int gpsw;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct arizona_pdata {
    struct gpio_desc * reset;
    struct arizona_micsupp_pdata micvdd;
    struct arizona_ldo1_pdata ldo1;
    int clk32k_src;
    unsigned int irq_flags;
    int gpio_base;
    unsigned int[5] gpio_defaults;
    unsigned int[3] max_channels_clocked;
    bool jd_gpio5;
    bool jd_gpio5_nopull;
    bool jd_invert;
    bool hpdet_acc_id;
    bool hpdet_acc_id_line;
    int hpdet_id_gpio;
    unsigned int hpdet_channel;
    bool micd_software_compare;
    unsigned int micd_detect_debounce;
    int micd_pol_gpio;
    unsigned int micd_bias_start_time;
    unsigned int micd_rate;
    unsigned int micd_dbtime;
    unsigned int micd_timeout;
    bool micd_force_micbias;
    const struct arizona_micd_range * micd_ranges;
    int num_micd_ranges;
    struct arizona_micd_config * micd_configs;
    int num_micd_configs;
    int[4] dmic_ref;
    struct arizona_micbias[3] micbias;
    int[4] inmode;
    int[6] out_mono;
    unsigned int[12] out_vol_limit;
    unsigned int[2] spk_mute;
    unsigned int[2] spk_fmt;
    unsigned int hap_act;
    int irq_gpio;
    unsigned int gpsw;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct arizona_pdata {
    struct gpio_desc * reset;
    struct arizona_micsupp_pdata micvdd;
    struct arizona_ldo1_pdata ldo1;
    int clk32k_src;
    unsigned int irq_flags;
    int gpio_base;
    unsigned int[5] gpio_defaults;
    unsigned int[3] max_channels_clocked;
    bool jd_gpio5;
    bool jd_gpio5_nopull;
    bool jd_invert;
    bool hpdet_acc_id;
    bool hpdet_acc_id_line;
    int hpdet_id_gpio;
    unsigned int hpdet_channel;
    bool micd_software_compare;
    unsigned int micd_detect_debounce;
    int micd_pol_gpio;
    unsigned int micd_bias_start_time;
    unsigned int micd_rate;
    unsigned int micd_dbtime;
    unsigned int micd_timeout;
    bool micd_force_micbias;
    const struct arizona_micd_range * micd_ranges;
    int num_micd_ranges;
    struct arizona_micd_config * micd_configs;
    int num_micd_configs;
    int[4] dmic_ref;
    struct arizona_micbias[3] micbias;
    int[4] inmode;
    int[6] out_mono;
    unsigned int[12] out_vol_limit;
    unsigned int[2] spk_mute;
    unsigned int[2] spk_fmt;
    unsigned int hap_act;
    int irq_gpio;
    unsigned int gpsw;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct arizona_pdata {
    struct gpio_desc * reset;
    struct arizona_micsupp_pdata micvdd;
    struct arizona_ldo1_pdata ldo1;
    int clk32k_src;
    unsigned int irq_flags;
    int gpio_base;
    unsigned int[5] gpio_defaults;
    unsigned int[3] max_channels_clocked;
    bool jd_gpio5;
    bool jd_gpio5_nopull;
    bool jd_invert;
    bool hpdet_acc_id;
    bool hpdet_acc_id_line;
    int hpdet_id_gpio;
    unsigned int hpdet_channel;
    bool micd_software_compare;
    unsigned int micd_detect_debounce;
    int micd_pol_gpio;
    unsigned int micd_bias_start_time;
    unsigned int micd_rate;
    unsigned int micd_dbtime;
    unsigned int micd_timeout;
    bool micd_force_micbias;
    const struct arizona_micd_range * micd_ranges;
    int num_micd_ranges;
    struct arizona_micd_config * micd_configs;
    int num_micd_configs;
    int[4] dmic_ref;
    struct arizona_micbias[3] micbias;
    int[4] inmode;
    int[6] out_mono;
    unsigned int[12] out_vol_limit;
    unsigned int[2] spk_mute;
    unsigned int[2] spk_fmt;
    unsigned int hap_act;
    int irq_gpio;
    unsigned int gpsw;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct arizona_pdata {
    struct gpio_desc * reset;
    struct arizona_micsupp_pdata micvdd;
    struct arizona_ldo1_pdata ldo1;
    int clk32k_src;
    unsigned int irq_flags;
    int gpio_base;
    unsigned int[5] gpio_defaults;
    unsigned int[3] max_channels_clocked;
    bool jd_gpio5;
    bool jd_gpio5_nopull;
    bool jd_invert;
    bool hpdet_acc_id;
    bool hpdet_acc_id_line;
    int hpdet_id_gpio;
    unsigned int hpdet_channel;
    bool micd_software_compare;
    unsigned int micd_detect_debounce;
    int micd_pol_gpio;
    unsigned int micd_bias_start_time;
    unsigned int micd_rate;
    unsigned int micd_dbtime;
    unsigned int micd_timeout;
    bool micd_force_micbias;
    const struct arizona_micd_range * micd_ranges;
    int num_micd_ranges;
    struct arizona_micd_config * micd_configs;
    int num_micd_configs;
    int[4] dmic_ref;
    struct arizona_micbias[3] micbias;
    int[4] inmode;
    int[6] out_mono;
    unsigned int[12] out_vol_limit;
    unsigned int[2] spk_mute;
    unsigned int[2] spk_fmt;
    unsigned int hap_act;
    int irq_gpio;
    unsigned int gpsw;
}
```
</details>
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
struct arizona_pdata {
    struct gpio_desc * reset;
    struct arizona_micsupp_pdata micvdd;
    struct arizona_ldo1_pdata ldo1;
    int clk32k_src;
    unsigned int irq_flags;
    int gpio_base;
    unsigned int[5] gpio_defaults;
    unsigned int[3] max_channels_clocked;
    bool jd_gpio5;
    bool jd_gpio5_nopull;
    bool jd_invert;
    bool hpdet_acc_id;
    bool hpdet_acc_id_line;
    int hpdet_id_gpio;
    unsigned int hpdet_channel;
    bool micd_software_compare;
    unsigned int micd_detect_debounce;
    int micd_pol_gpio;
    unsigned int micd_bias_start_time;
    unsigned int micd_rate;
    unsigned int micd_dbtime;
    unsigned int micd_timeout;
    bool micd_force_micbias;
    const struct arizona_micd_range * micd_ranges;
    int num_micd_ranges;
    struct arizona_micd_config * micd_configs;
    int num_micd_configs;
    int[4] dmic_ref;
    struct arizona_micbias[3] micbias;
    int[4] inmode;
    int[6] out_mono;
    unsigned int[12] out_vol_limit;
    unsigned int[2] spk_mute;
    unsigned int[2] spk_fmt;
    unsigned int hap_act;
    int irq_gpio;
    unsigned int gpsw;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct arizona_pdata {
    struct gpio_desc * reset;
    struct arizona_micsupp_pdata micvdd;
    struct arizona_ldo1_pdata ldo1;
    int clk32k_src;
    unsigned int irq_flags;
    int gpio_base;
    unsigned int[5] gpio_defaults;
    unsigned int[3] max_channels_clocked;
    bool jd_gpio5;
    bool jd_gpio5_nopull;
    bool jd_invert;
    bool hpdet_acc_id;
    bool hpdet_acc_id_line;
    int hpdet_id_gpio;
    unsigned int hpdet_channel;
    bool micd_software_compare;
    unsigned int micd_detect_debounce;
    int micd_pol_gpio;
    unsigned int micd_bias_start_time;
    unsigned int micd_rate;
    unsigned int micd_dbtime;
    unsigned int micd_timeout;
    bool micd_force_micbias;
    const struct arizona_micd_range * micd_ranges;
    int num_micd_ranges;
    struct arizona_micd_config * micd_configs;
    int num_micd_configs;
    int[4] dmic_ref;
    struct arizona_micbias[3] micbias;
    int[4] inmode;
    int[6] out_mono;
    unsigned int[12] out_vol_limit;
    unsigned int[2] spk_mute;
    unsigned int[2] spk_fmt;
    unsigned int hap_act;
    int irq_gpio;
    unsigned int gpsw;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct arizona_pdata {
    struct gpio_desc * reset;
    struct arizona_micsupp_pdata micvdd;
    struct arizona_ldo1_pdata ldo1;
    int clk32k_src;
    unsigned int irq_flags;
    int gpio_base;
    unsigned int[5] gpio_defaults;
    unsigned int[3] max_channels_clocked;
    bool jd_gpio5;
    bool jd_gpio5_nopull;
    bool jd_invert;
    bool hpdet_acc_id;
    bool hpdet_acc_id_line;
    int hpdet_id_gpio;
    unsigned int hpdet_channel;
    bool micd_software_compare;
    unsigned int micd_detect_debounce;
    int micd_pol_gpio;
    unsigned int micd_bias_start_time;
    unsigned int micd_rate;
    unsigned int micd_dbtime;
    unsigned int micd_timeout;
    bool micd_force_micbias;
    const struct arizona_micd_range * micd_ranges;
    int num_micd_ranges;
    struct arizona_micd_config * micd_configs;
    int num_micd_configs;
    int[4] dmic_ref;
    struct arizona_micbias[3] micbias;
    int[4] inmode;
    int[6] out_mono;
    unsigned int[12] out_vol_limit;
    unsigned int[2] spk_mute;
    unsigned int[2] spk_fmt;
    unsigned int hap_act;
    int irq_gpio;
    unsigned int gpsw;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct arizona_pdata {
    struct gpio_desc * reset;
    struct arizona_micsupp_pdata micvdd;
    struct arizona_ldo1_pdata ldo1;
    int clk32k_src;
    unsigned int irq_flags;
    int gpio_base;
    unsigned int[5] gpio_defaults;
    unsigned int[3] max_channels_clocked;
    bool jd_gpio5;
    bool jd_gpio5_nopull;
    bool jd_invert;
    bool hpdet_acc_id;
    bool hpdet_acc_id_line;
    int hpdet_id_gpio;
    unsigned int hpdet_channel;
    bool micd_software_compare;
    unsigned int micd_detect_debounce;
    int micd_pol_gpio;
    unsigned int micd_bias_start_time;
    unsigned int micd_rate;
    unsigned int micd_dbtime;
    unsigned int micd_timeout;
    bool micd_force_micbias;
    const struct arizona_micd_range * micd_ranges;
    int num_micd_ranges;
    struct arizona_micd_config * micd_configs;
    int num_micd_configs;
    int[4] dmic_ref;
    struct arizona_micbias[3] micbias;
    int[4] inmode;
    int[6] out_mono;
    unsigned int[12] out_vol_limit;
    unsigned int[2] spk_mute;
    unsigned int[2] spk_fmt;
    unsigned int hap_act;
    int irq_gpio;
    unsigned int gpsw;
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct arizona_pdata {
    struct gpio_desc * reset;
    struct arizona_micsupp_pdata micvdd;
    struct arizona_ldo1_pdata ldo1;
    int clk32k_src;
    unsigned int irq_flags;
    int gpio_base;
    unsigned int[5] gpio_defaults;
    unsigned int[3] max_channels_clocked;
    bool jd_gpio5;
    bool jd_gpio5_nopull;
    bool jd_invert;
    bool hpdet_acc_id;
    bool hpdet_acc_id_line;
    int hpdet_id_gpio;
    unsigned int hpdet_channel;
    bool micd_software_compare;
    unsigned int micd_detect_debounce;
    int micd_pol_gpio;
    unsigned int micd_bias_start_time;
    unsigned int micd_rate;
    unsigned int micd_dbtime;
    unsigned int micd_timeout;
    bool micd_force_micbias;
    const struct arizona_micd_range * micd_ranges;
    int num_micd_ranges;
    struct arizona_micd_config * micd_configs;
    int num_micd_configs;
    int[4] dmic_ref;
    struct arizona_micbias[3] micbias;
    int[4] inmode;
    int[6] out_mono;
    unsigned int[12] out_vol_limit;
    unsigned int[2] spk_mute;
    unsigned int[2] spk_fmt;
    unsigned int hap_act;
    int irq_gpio;
    unsigned int gpsw;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct arizona_pdata {
    struct gpio_desc * reset;
    struct arizona_micsupp_pdata micvdd;
    struct arizona_ldo1_pdata ldo1;
    int clk32k_src;
    unsigned int irq_flags;
    int gpio_base;
    unsigned int[5] gpio_defaults;
    unsigned int[3] max_channels_clocked;
    bool jd_gpio5;
    bool jd_gpio5_nopull;
    bool jd_invert;
    bool hpdet_acc_id;
    bool hpdet_acc_id_line;
    int hpdet_id_gpio;
    unsigned int hpdet_channel;
    bool micd_software_compare;
    unsigned int micd_detect_debounce;
    int micd_pol_gpio;
    unsigned int micd_bias_start_time;
    unsigned int micd_rate;
    unsigned int micd_dbtime;
    unsigned int micd_timeout;
    bool micd_force_micbias;
    const struct arizona_micd_range * micd_ranges;
    int num_micd_ranges;
    struct arizona_micd_config * micd_configs;
    int num_micd_configs;
    int[4] dmic_ref;
    struct arizona_micbias[3] micbias;
    int[4] inmode;
    int[6] out_mono;
    unsigned int[12] out_vol_limit;
    unsigned int[2] spk_mute;
    unsigned int[2] spk_fmt;
    unsigned int hap_act;
    int irq_gpio;
    unsigned int gpsw;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct arizona_pdata {
    struct gpio_desc * reset;
    struct arizona_micsupp_pdata micvdd;
    struct arizona_ldo1_pdata ldo1;
    int clk32k_src;
    unsigned int irq_flags;
    int gpio_base;
    unsigned int[5] gpio_defaults;
    unsigned int[3] max_channels_clocked;
    bool jd_gpio5;
    bool jd_gpio5_nopull;
    bool jd_invert;
    bool hpdet_acc_id;
    bool hpdet_acc_id_line;
    int hpdet_id_gpio;
    unsigned int hpdet_channel;
    bool micd_software_compare;
    unsigned int micd_detect_debounce;
    int micd_pol_gpio;
    unsigned int micd_bias_start_time;
    unsigned int micd_rate;
    unsigned int micd_dbtime;
    unsigned int micd_timeout;
    bool micd_force_micbias;
    const struct arizona_micd_range * micd_ranges;
    int num_micd_ranges;
    struct arizona_micd_config * micd_configs;
    int num_micd_configs;
    int[4] dmic_ref;
    struct arizona_micbias[3] micbias;
    int[4] inmode;
    int[6] out_mono;
    unsigned int[12] out_vol_limit;
    unsigned int[2] spk_mute;
    unsigned int[2] spk_fmt;
    unsigned int hap_act;
    int irq_gpio;
    unsigned int gpsw;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct arizona_pdata {
    struct gpio_desc * reset;
    struct arizona_micsupp_pdata micvdd;
    struct arizona_ldo1_pdata ldo1;
    int clk32k_src;
    unsigned int irq_flags;
    int gpio_base;
    unsigned int[5] gpio_defaults;
    unsigned int[3] max_channels_clocked;
    bool jd_gpio5;
    bool jd_gpio5_nopull;
    bool jd_invert;
    bool hpdet_acc_id;
    bool hpdet_acc_id_line;
    int hpdet_id_gpio;
    unsigned int hpdet_channel;
    bool micd_software_compare;
    unsigned int micd_detect_debounce;
    int micd_pol_gpio;
    unsigned int micd_bias_start_time;
    unsigned int micd_rate;
    unsigned int micd_dbtime;
    unsigned int micd_timeout;
    bool micd_force_micbias;
    const struct arizona_micd_range * micd_ranges;
    int num_micd_ranges;
    struct arizona_micd_config * micd_configs;
    int num_micd_configs;
    int[4] dmic_ref;
    struct arizona_micbias[3] micbias;
    int[4] inmode;
    int[6] out_mono;
    unsigned int[12] out_vol_limit;
    unsigned int[2] spk_mute;
    unsigned int[2] spk_fmt;
    unsigned int hap_act;
    int irq_gpio;
    unsigned int gpsw;
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>bool[6] out_mono</code> ➡️ <code>int[6] out_mono</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>int ldoena</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct regulator_init_data * micvdd</code> ➡️ <code>struct arizona_micsupp_pdata micvdd</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct regulator_init_data * ldo1</code> ➡️ <code>struct arizona_ldo1_pdata ldo1</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int[12] out_vol_limit</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>int reset</code> ➡️ <code>struct gpio_desc * reset</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
struct arizona_pdata {
    struct gpio_desc * reset;
    struct arizona_micsupp_pdata micvdd;
    struct arizona_ldo1_pdata ldo1;
    int clk32k_src;
    unsigned int irq_flags;
    int gpio_base;
    unsigned int[5] gpio_defaults;
    unsigned int[3] max_channels_clocked;
    bool jd_gpio5;
    bool jd_gpio5_nopull;
    bool jd_invert;
    bool hpdet_acc_id;
    bool hpdet_acc_id_line;
    int hpdet_id_gpio;
    unsigned int hpdet_channel;
    bool micd_software_compare;
    unsigned int micd_detect_debounce;
    int micd_pol_gpio;
    unsigned int micd_bias_start_time;
    unsigned int micd_rate;
    unsigned int micd_dbtime;
    unsigned int micd_timeout;
    bool micd_force_micbias;
    const struct arizona_micd_range * micd_ranges;
    int num_micd_ranges;
    struct arizona_micd_config * micd_configs;
    int num_micd_configs;
    int[4] dmic_ref;
    struct arizona_micbias[3] micbias;
    int[4] inmode;
    int[6] out_mono;
    unsigned int[12] out_vol_limit;
    unsigned int[2] spk_mute;
    unsigned int[2] spk_fmt;
    unsigned int hap_act;
    int irq_gpio;
    unsigned int gpsw;
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
