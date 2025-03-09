# Function: <code>snd_soc_component_update_bits</code>

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
int snd_soc_component_update_bits(struct snd_soc_component * component, unsigned int reg, unsigned int mask, unsigned int val)
```

```json
{
  "name": "snd_soc_component_update_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234551516,
      "name": "snd_soc_component_update_bits",
      "external": true,
      "loc": "sound/soc/soc-io.c:109",
      "file": "sound/soc/soc-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "sound/soc/soc-dapm.c:dapm_power_widgets",
        "sound/soc/soc-dapm.c:dapm_power_widgets",
        "sound/soc/soc-dapm.c:dapm_seq_run_coalesced",
        "sound/soc/soc-ops.c:snd_soc_put_strobe",
        "sound/soc/soc-ops.c:snd_soc_put_strobe",
        "sound/soc/soc-ops.c:snd_soc_put_xr_sx",
        "sound/soc/soc-ops.c:snd_soc_put_volsw_range",
        "sound/soc/soc-ops.c:snd_soc_put_volsw_range",
        "sound/soc/soc-ops.c:snd_soc_put_volsw_sx",
        "sound/soc/soc-ops.c:snd_soc_put_volsw_sx",
        "sound/soc/soc-ops.c:snd_soc_put_volsw",
        "sound/soc/soc-ops.c:snd_soc_put_volsw",
        "sound/soc/soc-ops.c:snd_soc_put_volsw",
        "sound/soc/soc-ops.c:snd_soc_put_enum_double",
        "sound/soc/soc-ac97.c:snd_soc_ac97_gpio_direction_out",
        "sound/soc/soc-ac97.c:snd_soc_ac97_gpio_direction_in",
        "sound/soc/codecs/sgtl5000.c:sgtl5000_probe",
        "sound/soc/codecs/sgtl5000.c:sgtl5000_probe",
        "sound/soc/codecs/sgtl5000.c:sgtl5000_probe",
        "sound/soc/codecs/sgtl5000.c:sgtl5000_probe",
        "sound/soc/codecs/sgtl5000.c:sgtl5000_probe",
        "sound/soc/codecs/sgtl5000.c:sgtl5000_probe",
        "sound/soc/codecs/sgtl5000.c:sgtl5000_probe",
        "sound/soc/codecs/sgtl5000.c:sgtl5000_probe",
        "sound/soc/codecs/sgtl5000.c:sgtl5000_probe",
        "sound/soc/codecs/sgtl5000.c:sgtl5000_probe",
        "sound/soc/codecs/sgtl5000.c:sgtl5000_probe",
        "sound/soc/codecs/sgtl5000.c:sgtl5000_pcm_hw_params",
        "sound/soc/codecs/sgtl5000.c:sgtl5000_pcm_hw_params",
        "sound/soc/codecs/sgtl5000.c:sgtl5000_set_clock",
        "sound/soc/codecs/sgtl5000.c:sgtl5000_set_clock",
        "sound/soc/codecs/sgtl5000.c:sgtl5000_set_clock",
        "sound/soc/codecs/sgtl5000.c:sgtl5000_digital_mute",
        "sound/soc/codecs/sgtl5000.c:vag_and_mute_control",
        "sound/soc/codecs/sgtl5000.c:vag_and_mute_control",
        "sound/soc/codecs/sgtl5000.c:vag_and_mute_control",
        "sound/soc/codecs/sgtl5000.c:vag_and_mute_control",
        "sound/soc/codecs/sgtl5000.c:vag_and_mute_control",
        "sound/soc/codecs/sgtl5000.c:mic_bias_event",
        "sound/soc/codecs/sgtl5000.c:mic_bias_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234551516,
      "name": "snd_soc_component_update_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
int snd_soc_component_update_bits(struct snd_soc_component * component, unsigned int reg, unsigned int mask, unsigned int val)
```
</details>
</li>
</ul>
