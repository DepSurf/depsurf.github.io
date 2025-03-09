# Struct: <code>pl08x_platform_data</code>

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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct pl08x_platform_data {
    struct pl08x_channel_data * slave_channels;
    unsigned int num_slave_channels;
    enum pl08x_burst_size memcpy_burst_size;
    enum pl08x_bus_width memcpy_bus_width;
    bool memcpy_prot_buff;
    bool memcpy_prot_cache;
    int (*)(const struct pl08x_channel_data *) get_xfer_signal;
    void (*)(const struct pl08x_channel_data *, int) put_xfer_signal;
    u8 lli_buses;
    u8 mem_buses;
    const struct dma_slave_map * slave_map;
    int slave_map_len;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct pl08x_platform_data {
    struct pl08x_channel_data * slave_channels;
    unsigned int num_slave_channels;
    enum pl08x_burst_size memcpy_burst_size;
    enum pl08x_bus_width memcpy_bus_width;
    bool memcpy_prot_buff;
    bool memcpy_prot_cache;
    int (*)(const struct pl08x_channel_data *) get_xfer_signal;
    void (*)(const struct pl08x_channel_data *, int) put_xfer_signal;
    u8 lli_buses;
    u8 mem_buses;
    const struct dma_slave_map * slave_map;
    int slave_map_len;
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
struct pl08x_platform_data {
    struct pl08x_channel_data * slave_channels;
    unsigned int num_slave_channels;
    enum pl08x_burst_size memcpy_burst_size;
    enum pl08x_bus_width memcpy_bus_width;
    bool memcpy_prot_buff;
    bool memcpy_prot_cache;
    int (*)(const struct pl08x_channel_data *) get_xfer_signal;
    void (*)(const struct pl08x_channel_data *, int) put_xfer_signal;
    u8 lli_buses;
    u8 mem_buses;
    const struct dma_slave_map * slave_map;
    int slave_map_len;
}
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
struct pl08x_platform_data {
    struct pl08x_channel_data * slave_channels;
    unsigned int num_slave_channels;
    enum pl08x_burst_size memcpy_burst_size;
    enum pl08x_bus_width memcpy_bus_width;
    bool memcpy_prot_buff;
    bool memcpy_prot_cache;
    int (*)(const struct pl08x_channel_data *) get_xfer_signal;
    void (*)(const struct pl08x_channel_data *, int) put_xfer_signal;
    u8 lli_buses;
    u8 mem_buses;
    const struct dma_slave_map * slave_map;
    int slave_map_len;
}
```
</details>
</li>
</ul>
