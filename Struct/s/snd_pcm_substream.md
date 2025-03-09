# Struct: <code>snd_pcm_substream</code>

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
struct snd_pcm_substream {
    struct snd_pcm * pcm;
    struct snd_pcm_str * pstr;
    void * private_data;
    int number;
    char[32] name;
    int stream;
    struct pm_qos_request latency_pm_qos_req;
    size_t buffer_bytes_max;
    struct snd_dma_buffer dma_buffer;
    size_t dma_max;
    const struct snd_pcm_ops * ops;
    struct snd_pcm_runtime * runtime;
    struct snd_timer * timer;
    unsigned int timer_running;
    long int wait_time;
    struct snd_pcm_substream * next;
    struct list_head link_list;
    struct snd_pcm_group self_group;
    struct snd_pcm_group * group;
    int ref_count;
    atomic_t mmap_count;
    unsigned int f_flags;
    void (*)(struct snd_pcm_substream *) pcm_release;
    struct pid * pid;
    struct snd_info_entry * proc_root;
    unsigned int hw_opened;
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
struct snd_pcm_substream {
    struct snd_pcm * pcm;
    struct snd_pcm_str * pstr;
    void * private_data;
    int number;
    char[32] name;
    int stream;
    struct pm_qos_request latency_pm_qos_req;
    size_t buffer_bytes_max;
    struct snd_dma_buffer dma_buffer;
    size_t dma_max;
    const struct snd_pcm_ops * ops;
    struct snd_pcm_runtime * runtime;
    struct snd_timer * timer;
    unsigned int timer_running;
    long int wait_time;
    struct snd_pcm_substream * next;
    struct list_head link_list;
    struct snd_pcm_group self_group;
    struct snd_pcm_group * group;
    int ref_count;
    atomic_t mmap_count;
    unsigned int f_flags;
    void (*)(struct snd_pcm_substream *) pcm_release;
    struct pid * pid;
    struct snd_info_entry * proc_root;
    unsigned int hw_opened;
}
```
</details>
</li>
</ul>
