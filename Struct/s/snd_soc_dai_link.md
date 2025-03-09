# Struct: <code>snd_soc_dai_link</code>

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
struct snd_soc_dai_link {
    const char * name;
    const char * stream_name;
    struct snd_soc_dai_link_component * cpus;
    unsigned int num_cpus;
    struct snd_soc_dai_link_component * codecs;
    unsigned int num_codecs;
    struct snd_soc_dai_link_component * platforms;
    unsigned int num_platforms;
    int id;
    const struct snd_soc_pcm_stream * params;
    unsigned int num_params;
    unsigned int dai_fmt;
    enum snd_soc_dpcm_trigger[2] trigger;
    int (*)(struct snd_soc_pcm_runtime *) init;
    int (*)(struct snd_soc_pcm_runtime *, struct snd_pcm_hw_params *) be_hw_params_fixup;
    const struct snd_soc_ops * ops;
    const struct snd_soc_compr_ops * compr_ops;
    bool nonatomic;
    unsigned int playback_only;
    unsigned int capture_only;
    unsigned int ignore_suspend;
    unsigned int symmetric_rates;
    unsigned int symmetric_channels;
    unsigned int symmetric_samplebits;
    unsigned int no_pcm;
    unsigned int dynamic;
    unsigned int dpcm_capture;
    unsigned int dpcm_playback;
    unsigned int dpcm_merged_format;
    unsigned int dpcm_merged_chan;
    unsigned int dpcm_merged_rate;
    unsigned int ignore_pmdown_time;
    unsigned int ignore;
    struct list_head list;
    struct snd_soc_dobj dobj;
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
struct snd_soc_dai_link {
    const char * name;
    const char * stream_name;
    struct snd_soc_dai_link_component * cpus;
    unsigned int num_cpus;
    struct snd_soc_dai_link_component * codecs;
    unsigned int num_codecs;
    struct snd_soc_dai_link_component * platforms;
    unsigned int num_platforms;
    int id;
    const struct snd_soc_pcm_stream * params;
    unsigned int num_params;
    unsigned int dai_fmt;
    enum snd_soc_dpcm_trigger[2] trigger;
    int (*)(struct snd_soc_pcm_runtime *) init;
    int (*)(struct snd_soc_pcm_runtime *, struct snd_pcm_hw_params *) be_hw_params_fixup;
    const struct snd_soc_ops * ops;
    const struct snd_soc_compr_ops * compr_ops;
    bool nonatomic;
    unsigned int playback_only;
    unsigned int capture_only;
    unsigned int ignore_suspend;
    unsigned int symmetric_rates;
    unsigned int symmetric_channels;
    unsigned int symmetric_samplebits;
    unsigned int no_pcm;
    unsigned int dynamic;
    unsigned int dpcm_capture;
    unsigned int dpcm_playback;
    unsigned int dpcm_merged_format;
    unsigned int dpcm_merged_chan;
    unsigned int dpcm_merged_rate;
    unsigned int ignore_pmdown_time;
    unsigned int ignore;
    struct list_head list;
    struct snd_soc_dobj dobj;
}
```
</details>
</li>
</ul>
