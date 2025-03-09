# Struct: <code>snd_soc_dapm_widget</code>

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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct snd_soc_dapm_widget {
    enum snd_soc_dapm_type id;
    const char * name;
    const char * sname;
    struct list_head list;
    struct snd_soc_dapm_context * dapm;
    void * priv;
    struct regulator * regulator;
    struct pinctrl * pinctrl;
    int reg;
    unsigned char shift;
    unsigned int mask;
    unsigned int on_val;
    unsigned int off_val;
    unsigned char power;
    unsigned char active;
    unsigned char connected;
    unsigned char new;
    unsigned char force;
    unsigned char ignore_suspend;
    unsigned char new_power;
    unsigned char power_checked;
    unsigned char is_supply;
    unsigned char is_ep;
    int subseq;
    int (*)(struct snd_soc_dapm_widget *) power_check;
    short unsigned int event_flags;
    int (*)(struct snd_soc_dapm_widget *, struct snd_kcontrol *, int) event;
    int num_kcontrols;
    const struct snd_kcontrol_new * kcontrol_news;
    struct snd_kcontrol * * kcontrols;
    struct snd_soc_dobj dobj;
    struct list_head[2] edges;
    struct list_head work_list;
    struct list_head power_list;
    struct list_head dirty;
    int[2] endpoints;
    struct clk * clk;
    int channel;
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
struct snd_soc_dapm_widget {
    enum snd_soc_dapm_type id;
    const char * name;
    const char * sname;
    struct list_head list;
    struct snd_soc_dapm_context * dapm;
    void * priv;
    struct regulator * regulator;
    struct pinctrl * pinctrl;
    int reg;
    unsigned char shift;
    unsigned int mask;
    unsigned int on_val;
    unsigned int off_val;
    unsigned char power;
    unsigned char active;
    unsigned char connected;
    unsigned char new;
    unsigned char force;
    unsigned char ignore_suspend;
    unsigned char new_power;
    unsigned char power_checked;
    unsigned char is_supply;
    unsigned char is_ep;
    int subseq;
    int (*)(struct snd_soc_dapm_widget *) power_check;
    short unsigned int event_flags;
    int (*)(struct snd_soc_dapm_widget *, struct snd_kcontrol *, int) event;
    int num_kcontrols;
    const struct snd_kcontrol_new * kcontrol_news;
    struct snd_kcontrol * * kcontrols;
    struct snd_soc_dobj dobj;
    struct list_head[2] edges;
    struct list_head work_list;
    struct list_head power_list;
    struct list_head dirty;
    int[2] endpoints;
    struct clk * clk;
    int channel;
}
```
</details>
</li>
</ul>
