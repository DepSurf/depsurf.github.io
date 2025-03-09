# Struct: <code>snd_soc_component</code>

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
struct snd_soc_component {
    const char * name;
    int id;
    const char * name_prefix;
    struct device * dev;
    struct snd_soc_card * card;
    unsigned int active;
    unsigned int suspended;
    struct list_head list;
    struct list_head card_aux_list;
    struct list_head card_list;
    const struct snd_soc_component_driver * driver;
    struct list_head dai_list;
    int num_dai;
    struct regmap * regmap;
    int val_bytes;
    struct mutex io_mutex;
    struct list_head dobj_list;
    struct snd_soc_dapm_context dapm;
    int (*)(struct snd_soc_component *) init;
    struct dentry * debugfs_root;
    const char * debugfs_prefix;
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
struct snd_soc_component {
    const char * name;
    int id;
    const char * name_prefix;
    struct device * dev;
    struct snd_soc_card * card;
    unsigned int active;
    unsigned int suspended;
    struct list_head list;
    struct list_head card_aux_list;
    struct list_head card_list;
    const struct snd_soc_component_driver * driver;
    struct list_head dai_list;
    int num_dai;
    struct regmap * regmap;
    int val_bytes;
    struct mutex io_mutex;
    struct list_head dobj_list;
    struct snd_soc_dapm_context dapm;
    int (*)(struct snd_soc_component *) init;
    struct dentry * debugfs_root;
    const char * debugfs_prefix;
}
```
</details>
</li>
</ul>
