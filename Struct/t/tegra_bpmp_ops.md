# Struct: <code>tegra_bpmp_ops</code>

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
struct tegra_bpmp_ops {
    int (*)(struct tegra_bpmp *) init;
    void (*)(struct tegra_bpmp *) deinit;
    bool (*)(struct tegra_bpmp_channel *) is_response_ready;
    bool (*)(struct tegra_bpmp_channel *) is_request_ready;
    int (*)(struct tegra_bpmp_channel *) ack_response;
    int (*)(struct tegra_bpmp_channel *) ack_request;
    bool (*)(struct tegra_bpmp_channel *) is_response_channel_free;
    bool (*)(struct tegra_bpmp_channel *) is_request_channel_free;
    int (*)(struct tegra_bpmp_channel *) post_response;
    int (*)(struct tegra_bpmp_channel *) post_request;
    int (*)(struct tegra_bpmp *) ring_doorbell;
    int (*)(struct tegra_bpmp *) resume;
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
struct tegra_bpmp_ops {
    int (*)(struct tegra_bpmp *) init;
    void (*)(struct tegra_bpmp *) deinit;
    bool (*)(struct tegra_bpmp_channel *) is_response_ready;
    bool (*)(struct tegra_bpmp_channel *) is_request_ready;
    int (*)(struct tegra_bpmp_channel *) ack_response;
    int (*)(struct tegra_bpmp_channel *) ack_request;
    bool (*)(struct tegra_bpmp_channel *) is_response_channel_free;
    bool (*)(struct tegra_bpmp_channel *) is_request_channel_free;
    int (*)(struct tegra_bpmp_channel *) post_response;
    int (*)(struct tegra_bpmp_channel *) post_request;
    int (*)(struct tegra_bpmp *) ring_doorbell;
    int (*)(struct tegra_bpmp *) resume;
}
```
</details>
</li>
</ul>
