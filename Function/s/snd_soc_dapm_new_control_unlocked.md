# Function: <code>snd_soc_dapm_new_control_unlocked</code>

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
struct snd_soc_dapm_widget * snd_soc_dapm_new_control_unlocked(struct snd_soc_dapm_context * dapm, const struct snd_soc_dapm_widget * widget)
```

```json
{
  "name": "snd_soc_dapm_new_control_unlocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234511112,
      "name": "snd_soc_dapm_new_control_unlocked",
      "external": true,
      "loc": "sound/soc/soc-dapm.c:3574",
      "file": "sound/soc/soc-dapm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "sound/soc/soc-dapm.c:snd_soc_dapm_new_dai_widgets",
        "sound/soc/soc-dapm.c:snd_soc_dapm_new_dai_widgets",
        "sound/soc/soc-dapm.c:snd_soc_dapm_new_dai",
        "sound/soc/soc-dapm.c:snd_soc_dapm_new_controls",
        "sound/soc/soc-dapm.c:snd_soc_dapm_new_control",
        "sound/soc/soc-topology.c:soc_tplg_dapm_widget_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234511112,
      "name": "snd_soc_dapm_new_control_unlocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 928
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
struct snd_soc_dapm_widget * snd_soc_dapm_new_control_unlocked(struct snd_soc_dapm_context * dapm, const struct snd_soc_dapm_widget * widget)
```
</details>
</li>
</ul>
