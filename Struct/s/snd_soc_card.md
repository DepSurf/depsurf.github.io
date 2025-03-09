# Struct: <code>snd_soc_card</code>

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
struct snd_soc_card {
    const char * name;
    const char * long_name;
    const char * driver_name;
    const char * components;
    char[80] dmi_longname;
    char[32] topology_shortname;
    struct device * dev;
    struct snd_card * snd_card;
    struct module * owner;
    struct mutex mutex;
    struct mutex dapm_mutex;
    struct mutex pcm_mutex;
    enum snd_soc_pcm_subclass pcm_subclass;
    spinlock_t dpcm_lock;
    bool instantiated;
    bool topology_shortname_created;
    int (*)(struct snd_soc_card *) probe;
    int (*)(struct snd_soc_card *) late_probe;
    int (*)(struct snd_soc_card *) remove;
    int (*)(struct snd_soc_card *) suspend_pre;
    int (*)(struct snd_soc_card *) suspend_post;
    int (*)(struct snd_soc_card *) resume_pre;
    int (*)(struct snd_soc_card *) resume_post;
    int (*)(struct snd_soc_card *, struct snd_soc_dapm_context *, enum snd_soc_bias_level) set_bias_level;
    int (*)(struct snd_soc_card *, struct snd_soc_dapm_context *, enum snd_soc_bias_level) set_bias_level_post;
    int (*)(struct snd_soc_card *, struct snd_soc_dai_link *) add_dai_link;
    void (*)(struct snd_soc_card *, struct snd_soc_dai_link *) remove_dai_link;
    long int pmdown_time;
    struct snd_soc_dai_link * dai_link;
    int num_links;
    struct list_head dai_link_list;
    struct list_head rtd_list;
    int num_rtd;
    struct snd_soc_codec_conf * codec_conf;
    int num_configs;
    struct snd_soc_aux_dev * aux_dev;
    int num_aux_devs;
    struct list_head aux_comp_list;
    const struct snd_kcontrol_new * controls;
    int num_controls;
    const struct snd_soc_dapm_widget * dapm_widgets;
    int num_dapm_widgets;
    const struct snd_soc_dapm_route * dapm_routes;
    int num_dapm_routes;
    const struct snd_soc_dapm_widget * of_dapm_widgets;
    int num_of_dapm_widgets;
    const struct snd_soc_dapm_route * of_dapm_routes;
    int num_of_dapm_routes;
    bool fully_routed;
    struct list_head component_dev_list;
    struct list_head list;
    struct list_head widgets;
    struct list_head paths;
    struct list_head dapm_list;
    struct list_head dapm_dirty;
    struct list_head dobj_list;
    struct snd_soc_dapm_context dapm;
    struct snd_soc_dapm_stats dapm_stats;
    struct snd_soc_dapm_update * update;
    struct dentry * debugfs_card_root;
    struct work_struct deferred_resume_work;
    u32 pop_time;
    void * drvdata;
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
struct snd_soc_card {
    const char * name;
    const char * long_name;
    const char * driver_name;
    const char * components;
    char[80] dmi_longname;
    char[32] topology_shortname;
    struct device * dev;
    struct snd_card * snd_card;
    struct module * owner;
    struct mutex mutex;
    struct mutex dapm_mutex;
    struct mutex pcm_mutex;
    enum snd_soc_pcm_subclass pcm_subclass;
    spinlock_t dpcm_lock;
    bool instantiated;
    bool topology_shortname_created;
    int (*)(struct snd_soc_card *) probe;
    int (*)(struct snd_soc_card *) late_probe;
    int (*)(struct snd_soc_card *) remove;
    int (*)(struct snd_soc_card *) suspend_pre;
    int (*)(struct snd_soc_card *) suspend_post;
    int (*)(struct snd_soc_card *) resume_pre;
    int (*)(struct snd_soc_card *) resume_post;
    int (*)(struct snd_soc_card *, struct snd_soc_dapm_context *, enum snd_soc_bias_level) set_bias_level;
    int (*)(struct snd_soc_card *, struct snd_soc_dapm_context *, enum snd_soc_bias_level) set_bias_level_post;
    int (*)(struct snd_soc_card *, struct snd_soc_dai_link *) add_dai_link;
    void (*)(struct snd_soc_card *, struct snd_soc_dai_link *) remove_dai_link;
    long int pmdown_time;
    struct snd_soc_dai_link * dai_link;
    int num_links;
    struct list_head dai_link_list;
    struct list_head rtd_list;
    int num_rtd;
    struct snd_soc_codec_conf * codec_conf;
    int num_configs;
    struct snd_soc_aux_dev * aux_dev;
    int num_aux_devs;
    struct list_head aux_comp_list;
    const struct snd_kcontrol_new * controls;
    int num_controls;
    const struct snd_soc_dapm_widget * dapm_widgets;
    int num_dapm_widgets;
    const struct snd_soc_dapm_route * dapm_routes;
    int num_dapm_routes;
    const struct snd_soc_dapm_widget * of_dapm_widgets;
    int num_of_dapm_widgets;
    const struct snd_soc_dapm_route * of_dapm_routes;
    int num_of_dapm_routes;
    bool fully_routed;
    struct list_head component_dev_list;
    struct list_head list;
    struct list_head widgets;
    struct list_head paths;
    struct list_head dapm_list;
    struct list_head dapm_dirty;
    struct list_head dobj_list;
    struct snd_soc_dapm_context dapm;
    struct snd_soc_dapm_stats dapm_stats;
    struct snd_soc_dapm_update * update;
    struct dentry * debugfs_card_root;
    struct work_struct deferred_resume_work;
    u32 pop_time;
    void * drvdata;
}
```
</details>
</li>
</ul>
