# Struct: <code>snd_soc_component_driver</code>

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
struct snd_soc_component_driver {
    const char * name;
    const struct snd_kcontrol_new * controls;
    unsigned int num_controls;
    const struct snd_soc_dapm_widget * dapm_widgets;
    unsigned int num_dapm_widgets;
    const struct snd_soc_dapm_route * dapm_routes;
    unsigned int num_dapm_routes;
    int (*)(struct snd_soc_component *) probe;
    void (*)(struct snd_soc_component *) remove;
    int (*)(struct snd_soc_component *) suspend;
    int (*)(struct snd_soc_component *) resume;
    unsigned int (*)(struct snd_soc_component *, unsigned int) read;
    int (*)(struct snd_soc_component *, unsigned int, unsigned int) write;
    int (*)(struct snd_soc_pcm_runtime *) pcm_new;
    void (*)(struct snd_pcm *) pcm_free;
    int (*)(struct snd_soc_component *, int, int, unsigned int, int) set_sysclk;
    int (*)(struct snd_soc_component *, int, int, unsigned int, unsigned int) set_pll;
    int (*)(struct snd_soc_component *, struct snd_soc_jack *, void *) set_jack;
    int (*)(struct snd_soc_component *, struct of_phandle_args *, const char * *) of_xlate_dai_name;
    int (*)(struct snd_soc_component *, struct device_node *) of_xlate_dai_id;
    void (*)(struct snd_soc_component *, enum snd_soc_dapm_type, int) seq_notifier;
    int (*)(struct snd_soc_component *, int) stream_event;
    int (*)(struct snd_soc_component *, enum snd_soc_bias_level) set_bias_level;
    const struct snd_pcm_ops * ops;
    const struct snd_compr_ops * compr_ops;
    int probe_order;
    int remove_order;
    unsigned int module_get_upon_open;
    unsigned int idle_bias_on;
    unsigned int suspend_bias_off;
    unsigned int use_pmdown_time;
    unsigned int endianness;
    unsigned int non_legacy_dai_naming;
    const char * ignore_machine;
    const char * topology_name_prefix;
    int (*)(struct snd_soc_pcm_runtime *, struct snd_pcm_hw_params *) be_hw_params_fixup;
    bool use_dai_pcm_id;
    int be_pcm_base;
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
struct snd_soc_component_driver {
    const char * name;
    const struct snd_kcontrol_new * controls;
    unsigned int num_controls;
    const struct snd_soc_dapm_widget * dapm_widgets;
    unsigned int num_dapm_widgets;
    const struct snd_soc_dapm_route * dapm_routes;
    unsigned int num_dapm_routes;
    int (*)(struct snd_soc_component *) probe;
    void (*)(struct snd_soc_component *) remove;
    int (*)(struct snd_soc_component *) suspend;
    int (*)(struct snd_soc_component *) resume;
    unsigned int (*)(struct snd_soc_component *, unsigned int) read;
    int (*)(struct snd_soc_component *, unsigned int, unsigned int) write;
    int (*)(struct snd_soc_pcm_runtime *) pcm_new;
    void (*)(struct snd_pcm *) pcm_free;
    int (*)(struct snd_soc_component *, int, int, unsigned int, int) set_sysclk;
    int (*)(struct snd_soc_component *, int, int, unsigned int, unsigned int) set_pll;
    int (*)(struct snd_soc_component *, struct snd_soc_jack *, void *) set_jack;
    int (*)(struct snd_soc_component *, struct of_phandle_args *, const char * *) of_xlate_dai_name;
    int (*)(struct snd_soc_component *, struct device_node *) of_xlate_dai_id;
    void (*)(struct snd_soc_component *, enum snd_soc_dapm_type, int) seq_notifier;
    int (*)(struct snd_soc_component *, int) stream_event;
    int (*)(struct snd_soc_component *, enum snd_soc_bias_level) set_bias_level;
    const struct snd_pcm_ops * ops;
    const struct snd_compr_ops * compr_ops;
    int probe_order;
    int remove_order;
    unsigned int module_get_upon_open;
    unsigned int idle_bias_on;
    unsigned int suspend_bias_off;
    unsigned int use_pmdown_time;
    unsigned int endianness;
    unsigned int non_legacy_dai_naming;
    const char * ignore_machine;
    const char * topology_name_prefix;
    int (*)(struct snd_soc_pcm_runtime *, struct snd_pcm_hw_params *) be_hw_params_fixup;
    bool use_dai_pcm_id;
    int be_pcm_base;
}
```
</details>
</li>
</ul>
