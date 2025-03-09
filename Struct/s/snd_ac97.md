# Struct: <code>snd_ac97</code>

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
struct snd_ac97 {
    const struct snd_ac97_build_ops * build_ops;
    void * private_data;
    void (*)(struct snd_ac97 *) private_free;
    struct snd_ac97_bus * bus;
    struct pci_dev * pci;
    struct snd_info_entry * proc;
    struct snd_info_entry * proc_regs;
    short unsigned int subsystem_vendor;
    short unsigned int subsystem_device;
    struct mutex reg_mutex;
    struct mutex page_mutex;
    short unsigned int num;
    short unsigned int addr;
    unsigned int id;
    short unsigned int caps;
    short unsigned int ext_id;
    short unsigned int ext_mid;
    const struct snd_ac97_res_table * res_table;
    unsigned int scaps;
    unsigned int flags;
    unsigned int[6] rates;
    unsigned int spdif_status;
    short unsigned int[128] regs;
    long unsigned int[4] reg_accessed;
    union (anon) spec;
    unsigned char indep_surround;
    unsigned char channel_mode;
    unsigned int power_up;
    struct delayed_work power_work;
    struct device dev;
    struct snd_ac97_gpio_priv * gpio_priv;
    struct snd_pcm_chmap *[2] chmaps;
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
struct snd_ac97 {
    const struct snd_ac97_build_ops * build_ops;
    void * private_data;
    void (*)(struct snd_ac97 *) private_free;
    struct snd_ac97_bus * bus;
    struct pci_dev * pci;
    struct snd_info_entry * proc;
    struct snd_info_entry * proc_regs;
    short unsigned int subsystem_vendor;
    short unsigned int subsystem_device;
    struct mutex reg_mutex;
    struct mutex page_mutex;
    short unsigned int num;
    short unsigned int addr;
    unsigned int id;
    short unsigned int caps;
    short unsigned int ext_id;
    short unsigned int ext_mid;
    const struct snd_ac97_res_table * res_table;
    unsigned int scaps;
    unsigned int flags;
    unsigned int[6] rates;
    unsigned int spdif_status;
    short unsigned int[128] regs;
    long unsigned int[4] reg_accessed;
    union (anon) spec;
    unsigned char indep_surround;
    unsigned char channel_mode;
    unsigned int power_up;
    struct delayed_work power_work;
    struct device dev;
    struct snd_ac97_gpio_priv * gpio_priv;
    struct snd_pcm_chmap *[2] chmaps;
}
```
</details>
</li>
</ul>
