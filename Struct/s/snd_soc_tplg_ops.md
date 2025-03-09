# Struct: <code>snd_soc_tplg_ops</code>

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
struct snd_soc_tplg_ops {
    int (*)(struct snd_soc_component *, int, struct snd_kcontrol_new *, struct snd_soc_tplg_ctl_hdr *) control_load;
    int (*)(struct snd_soc_component *, struct snd_soc_dobj *) control_unload;
    int (*)(struct snd_soc_component *, int, struct snd_soc_dapm_route *) dapm_route_load;
    int (*)(struct snd_soc_component *, struct snd_soc_dobj *) dapm_route_unload;
    int (*)(struct snd_soc_component *, int, struct snd_soc_dapm_widget *, struct snd_soc_tplg_dapm_widget *) widget_load;
    int (*)(struct snd_soc_component *, int, struct snd_soc_dapm_widget *, struct snd_soc_tplg_dapm_widget *) widget_ready;
    int (*)(struct snd_soc_component *, struct snd_soc_dobj *) widget_unload;
    int (*)(struct snd_soc_component *, int, struct snd_soc_dai_driver *, struct snd_soc_tplg_pcm *, struct snd_soc_dai *) dai_load;
    int (*)(struct snd_soc_component *, struct snd_soc_dobj *) dai_unload;
    int (*)(struct snd_soc_component *, int, struct snd_soc_dai_link *, struct snd_soc_tplg_link_config *) link_load;
    int (*)(struct snd_soc_component *, struct snd_soc_dobj *) link_unload;
    int (*)(struct snd_soc_component *, int, struct snd_soc_tplg_hdr *) vendor_load;
    int (*)(struct snd_soc_component *, struct snd_soc_tplg_hdr *) vendor_unload;
    void (*)(struct snd_soc_component *) complete;
    int (*)(struct snd_soc_component *, int, struct snd_soc_tplg_manifest *) manifest;
    const struct snd_soc_tplg_kcontrol_ops * io_ops;
    int io_ops_count;
    const struct snd_soc_tplg_bytes_ext_ops * bytes_ext_ops;
    int bytes_ext_ops_count;
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
struct snd_soc_tplg_ops {
    int (*)(struct snd_soc_component *, int, struct snd_kcontrol_new *, struct snd_soc_tplg_ctl_hdr *) control_load;
    int (*)(struct snd_soc_component *, struct snd_soc_dobj *) control_unload;
    int (*)(struct snd_soc_component *, int, struct snd_soc_dapm_route *) dapm_route_load;
    int (*)(struct snd_soc_component *, struct snd_soc_dobj *) dapm_route_unload;
    int (*)(struct snd_soc_component *, int, struct snd_soc_dapm_widget *, struct snd_soc_tplg_dapm_widget *) widget_load;
    int (*)(struct snd_soc_component *, int, struct snd_soc_dapm_widget *, struct snd_soc_tplg_dapm_widget *) widget_ready;
    int (*)(struct snd_soc_component *, struct snd_soc_dobj *) widget_unload;
    int (*)(struct snd_soc_component *, int, struct snd_soc_dai_driver *, struct snd_soc_tplg_pcm *, struct snd_soc_dai *) dai_load;
    int (*)(struct snd_soc_component *, struct snd_soc_dobj *) dai_unload;
    int (*)(struct snd_soc_component *, int, struct snd_soc_dai_link *, struct snd_soc_tplg_link_config *) link_load;
    int (*)(struct snd_soc_component *, struct snd_soc_dobj *) link_unload;
    int (*)(struct snd_soc_component *, int, struct snd_soc_tplg_hdr *) vendor_load;
    int (*)(struct snd_soc_component *, struct snd_soc_tplg_hdr *) vendor_unload;
    void (*)(struct snd_soc_component *) complete;
    int (*)(struct snd_soc_component *, int, struct snd_soc_tplg_manifest *) manifest;
    const struct snd_soc_tplg_kcontrol_ops * io_ops;
    int io_ops_count;
    const struct snd_soc_tplg_bytes_ext_ops * bytes_ext_ops;
    int bytes_ext_ops_count;
}
```
</details>
</li>
</ul>
