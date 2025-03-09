# Function: <code>snd_soc_dapm_stream_event</code>

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
void snd_soc_dapm_stream_event(struct snd_soc_pcm_runtime * rtd, int stream, int event)
```

```json
{
  "name": "snd_soc_dapm_stream_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234517324,
      "name": "snd_soc_dapm_stream_event",
      "external": true,
      "loc": "sound/soc/soc-dapm.c:4437",
      "file": "sound/soc/soc-dapm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "sound/soc/soc-core.c:soc_resume_deferred",
        "sound/soc/soc-core.c:soc_resume_deferred",
        "sound/soc/soc-core.c:snd_soc_suspend",
        "sound/soc/soc-core.c:snd_soc_suspend",
        "sound/soc/soc-pcm.c:soc_pcm_prepare",
        "sound/soc/soc-pcm.c:soc_pcm_close",
        "sound/soc/soc-pcm.c:soc_pcm_close",
        "sound/soc/soc-pcm.c:close_delayed_work",
        "sound/soc/soc-pcm.c:dpcm_dapm_stream_event",
        "sound/soc/soc-pcm.c:dpcm_dapm_stream_event",
        "sound/soc/soc-compress.c:soc_compr_set_params",
        "sound/soc/soc-compress.c:soc_compr_set_params",
        "sound/soc/soc-compress.c:soc_compr_free",
        "sound/soc/soc-compress.c:soc_compr_free",
        "sound/soc/soc-compress.c:close_delayed_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234517324,
      "name": "snd_soc_dapm_stream_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void snd_soc_dapm_stream_event(struct snd_soc_pcm_runtime * rtd, int stream, int event)
```
</details>
</li>
</ul>
