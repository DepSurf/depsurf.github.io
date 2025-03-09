# Struct: <code>nvmf_ctrl_options</code>

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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct nvmf_ctrl_options {
    unsigned int mask;
    char * transport;
    char * subsysnqn;
    char * traddr;
    char * trsvcid;
    char * host_traddr;
    size_t queue_size;
    unsigned int nr_io_queues;
    unsigned int reconnect_delay;
    bool discovery_nqn;
    bool duplicate_connect;
    unsigned int kato;
    struct nvmf_host * host;
    int max_reconnects;
    bool disable_sqflow;
    bool hdr_digest;
    bool data_digest;
    unsigned int nr_write_queues;
    unsigned int nr_poll_queues;
    int tos;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct nvmf_ctrl_options {
    unsigned int mask;
    char * transport;
    char * subsysnqn;
    char * traddr;
    char * trsvcid;
    char * host_traddr;
    size_t queue_size;
    unsigned int nr_io_queues;
    unsigned int reconnect_delay;
    bool discovery_nqn;
    bool duplicate_connect;
    unsigned int kato;
    struct nvmf_host * host;
    int max_reconnects;
    bool disable_sqflow;
    bool hdr_digest;
    bool data_digest;
    unsigned int nr_write_queues;
    unsigned int nr_poll_queues;
    int tos;
}
```
</details>
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➕</summary>

```c
struct nvmf_ctrl_options {
    unsigned int mask;
    char * transport;
    char * subsysnqn;
    char * traddr;
    char * trsvcid;
    char * host_traddr;
    size_t queue_size;
    unsigned int nr_io_queues;
    unsigned int reconnect_delay;
    bool discovery_nqn;
    bool duplicate_connect;
    unsigned int kato;
    struct nvmf_host * host;
    int max_reconnects;
    bool disable_sqflow;
    bool hdr_digest;
    bool data_digest;
    unsigned int nr_write_queues;
    unsigned int nr_poll_queues;
    int tos;
}
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➕</summary>

```c
struct nvmf_ctrl_options {
    unsigned int mask;
    char * transport;
    char * subsysnqn;
    char * traddr;
    char * trsvcid;
    char * host_traddr;
    size_t queue_size;
    unsigned int nr_io_queues;
    unsigned int reconnect_delay;
    bool discovery_nqn;
    bool duplicate_connect;
    unsigned int kato;
    struct nvmf_host * host;
    int max_reconnects;
    bool disable_sqflow;
    bool hdr_digest;
    bool data_digest;
    unsigned int nr_write_queues;
    unsigned int nr_poll_queues;
    int tos;
}
```
</details>
</li>
</ul>
