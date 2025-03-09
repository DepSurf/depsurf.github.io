# Struct: <code>sdw_dpn_prop</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct sdw_dpn_prop {
    u32 num;
    u32 max_word;
    u32 min_word;
    u32 num_words;
    u32 * words;
    enum sdw_dpn_type type;
    u32 max_grouping;
    bool simple_ch_prep_sm;
    u32 ch_prep_timeout;
    u32 imp_def_interrupts;
    u32 max_ch;
    u32 min_ch;
    u32 num_ch;
    u32 * ch;
    u32 num_ch_combinations;
    u32 * ch_combinations;
    u32 modes;
    u32 max_async_buffer;
    bool block_pack_mode;
    u32 port_encoding;
    struct sdw_dpn_audio_mode * audio_modes;
}
```
</details>
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
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
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
struct sdw_dpn_prop {
    u32 num;
    u32 max_word;
    u32 min_word;
    u32 num_words;
    u32 * words;
    enum sdw_dpn_type type;
    u32 max_grouping;
    bool simple_ch_prep_sm;
    u32 ch_prep_timeout;
    u32 imp_def_interrupts;
    u32 max_ch;
    u32 min_ch;
    u32 num_ch;
    u32 * ch;
    u32 num_ch_combinations;
    u32 * ch_combinations;
    u32 modes;
    u32 max_async_buffer;
    bool block_pack_mode;
    u32 port_encoding;
    struct sdw_dpn_audio_mode * audio_modes;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➖</summary>

```c
struct sdw_dpn_prop {
    u32 num;
    u32 max_word;
    u32 min_word;
    u32 num_words;
    u32 * words;
    enum sdw_dpn_type type;
    u32 max_grouping;
    bool simple_ch_prep_sm;
    u32 ch_prep_timeout;
    u32 imp_def_interrupts;
    u32 max_ch;
    u32 min_ch;
    u32 num_ch;
    u32 * ch;
    u32 num_ch_combinations;
    u32 * ch_combinations;
    u32 modes;
    u32 max_async_buffer;
    bool block_pack_mode;
    u32 port_encoding;
    struct sdw_dpn_audio_mode * audio_modes;
}
```
</details>
</li>
</ul>
