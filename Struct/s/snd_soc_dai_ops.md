# Struct: <code>snd_soc_dai_ops</code>

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
struct snd_soc_dai_ops {
    int (*)(struct snd_soc_dai *, int, unsigned int, int) set_sysclk;
    int (*)(struct snd_soc_dai *, int, int, unsigned int, unsigned int) set_pll;
    int (*)(struct snd_soc_dai *, int, int) set_clkdiv;
    int (*)(struct snd_soc_dai *, unsigned int) set_bclk_ratio;
    int (*)(struct snd_soc_dai *, unsigned int) set_fmt;
    int (*)(unsigned int, unsigned int *, unsigned int *) xlate_tdm_slot_mask;
    int (*)(struct snd_soc_dai *, unsigned int, unsigned int, int, int) set_tdm_slot;
    int (*)(struct snd_soc_dai *, unsigned int, unsigned int *, unsigned int, unsigned int *) set_channel_map;
    int (*)(struct snd_soc_dai *, unsigned int *, unsigned int *, unsigned int *, unsigned int *) get_channel_map;
    int (*)(struct snd_soc_dai *, int) set_tristate;
    int (*)(struct snd_soc_dai *, void *, int) set_sdw_stream;
    int (*)(struct snd_soc_dai *, int) digital_mute;
    int (*)(struct snd_soc_dai *, int, int) mute_stream;
    int (*)(struct snd_pcm_substream *, struct snd_soc_dai *) startup;
    void (*)(struct snd_pcm_substream *, struct snd_soc_dai *) shutdown;
    int (*)(struct snd_pcm_substream *, struct snd_pcm_hw_params *, struct snd_soc_dai *) hw_params;
    int (*)(struct snd_pcm_substream *, struct snd_soc_dai *) hw_free;
    int (*)(struct snd_pcm_substream *, struct snd_soc_dai *) prepare;
    int (*)(struct snd_pcm_substream *, int, struct snd_soc_dai *) trigger;
    int (*)(struct snd_pcm_substream *, int, struct snd_soc_dai *) bespoke_trigger;
    snd_pcm_sframes_t (*)(struct snd_pcm_substream *, struct snd_soc_dai *) delay;
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
struct snd_soc_dai_ops {
    int (*)(struct snd_soc_dai *, int, unsigned int, int) set_sysclk;
    int (*)(struct snd_soc_dai *, int, int, unsigned int, unsigned int) set_pll;
    int (*)(struct snd_soc_dai *, int, int) set_clkdiv;
    int (*)(struct snd_soc_dai *, unsigned int) set_bclk_ratio;
    int (*)(struct snd_soc_dai *, unsigned int) set_fmt;
    int (*)(unsigned int, unsigned int *, unsigned int *) xlate_tdm_slot_mask;
    int (*)(struct snd_soc_dai *, unsigned int, unsigned int, int, int) set_tdm_slot;
    int (*)(struct snd_soc_dai *, unsigned int, unsigned int *, unsigned int, unsigned int *) set_channel_map;
    int (*)(struct snd_soc_dai *, unsigned int *, unsigned int *, unsigned int *, unsigned int *) get_channel_map;
    int (*)(struct snd_soc_dai *, int) set_tristate;
    int (*)(struct snd_soc_dai *, void *, int) set_sdw_stream;
    int (*)(struct snd_soc_dai *, int) digital_mute;
    int (*)(struct snd_soc_dai *, int, int) mute_stream;
    int (*)(struct snd_pcm_substream *, struct snd_soc_dai *) startup;
    void (*)(struct snd_pcm_substream *, struct snd_soc_dai *) shutdown;
    int (*)(struct snd_pcm_substream *, struct snd_pcm_hw_params *, struct snd_soc_dai *) hw_params;
    int (*)(struct snd_pcm_substream *, struct snd_soc_dai *) hw_free;
    int (*)(struct snd_pcm_substream *, struct snd_soc_dai *) prepare;
    int (*)(struct snd_pcm_substream *, int, struct snd_soc_dai *) trigger;
    int (*)(struct snd_pcm_substream *, int, struct snd_soc_dai *) bespoke_trigger;
    snd_pcm_sframes_t (*)(struct snd_pcm_substream *, struct snd_soc_dai *) delay;
}
```
</details>
</li>
</ul>
