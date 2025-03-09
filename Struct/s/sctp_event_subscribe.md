# Struct: <code>sctp_event_subscribe</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct sctp_event_subscribe {
    __u8 sctp_data_io_event;
    __u8 sctp_association_event;
    __u8 sctp_address_event;
    __u8 sctp_send_failure_event;
    __u8 sctp_peer_error_event;
    __u8 sctp_shutdown_event;
    __u8 sctp_partial_delivery_event;
    __u8 sctp_adaptation_layer_event;
    __u8 sctp_authentication_event;
    __u8 sctp_sender_dry_event;
    __u8 sctp_stream_reset_event;
    __u8 sctp_assoc_reset_event;
    __u8 sctp_stream_change_event;
}
```
</details>
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
struct sctp_event_subscribe {
    __u8 sctp_data_io_event;
    __u8 sctp_association_event;
    __u8 sctp_address_event;
    __u8 sctp_send_failure_event;
    __u8 sctp_peer_error_event;
    __u8 sctp_shutdown_event;
    __u8 sctp_partial_delivery_event;
    __u8 sctp_adaptation_layer_event;
    __u8 sctp_authentication_event;
    __u8 sctp_sender_dry_event;
    __u8 sctp_stream_reset_event;
    __u8 sctp_assoc_reset_event;
    __u8 sctp_stream_change_event;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
struct sctp_event_subscribe {
    __u8 sctp_data_io_event;
    __u8 sctp_association_event;
    __u8 sctp_address_event;
    __u8 sctp_send_failure_event;
    __u8 sctp_peer_error_event;
    __u8 sctp_shutdown_event;
    __u8 sctp_partial_delivery_event;
    __u8 sctp_adaptation_layer_event;
    __u8 sctp_authentication_event;
    __u8 sctp_sender_dry_event;
    __u8 sctp_stream_reset_event;
    __u8 sctp_assoc_reset_event;
    __u8 sctp_stream_change_event;
}
```
</details>
</li>
</ul>
