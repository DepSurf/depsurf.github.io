# Struct: <code>mptcp_info</code>

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
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct mptcp_info {
    __u8 mptcpi_subflows;
    __u8 mptcpi_add_addr_signal;
    __u8 mptcpi_add_addr_accepted;
    __u8 mptcpi_subflows_max;
    __u8 mptcpi_add_addr_signal_max;
    __u8 mptcpi_add_addr_accepted_max;
    __u32 mptcpi_flags;
    __u32 mptcpi_token;
    __u64 mptcpi_write_seq;
    __u64 mptcpi_snd_una;
    __u64 mptcpi_rcv_nxt;
    __u8 mptcpi_local_addr_used;
    __u8 mptcpi_local_addr_max;
    __u8 mptcpi_csum_enabled;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct mptcp_info {
    __u8 mptcpi_subflows;
    __u8 mptcpi_add_addr_signal;
    __u8 mptcpi_add_addr_accepted;
    __u8 mptcpi_subflows_max;
    __u8 mptcpi_add_addr_signal_max;
    __u8 mptcpi_add_addr_accepted_max;
    __u32 mptcpi_flags;
    __u32 mptcpi_token;
    __u64 mptcpi_write_seq;
    __u64 mptcpi_snd_una;
    __u64 mptcpi_rcv_nxt;
    __u8 mptcpi_local_addr_used;
    __u8 mptcpi_local_addr_max;
    __u8 mptcpi_csum_enabled;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct mptcp_info {
    __u8 mptcpi_subflows;
    __u8 mptcpi_add_addr_signal;
    __u8 mptcpi_add_addr_accepted;
    __u8 mptcpi_subflows_max;
    __u8 mptcpi_add_addr_signal_max;
    __u8 mptcpi_add_addr_accepted_max;
    __u32 mptcpi_flags;
    __u32 mptcpi_token;
    __u64 mptcpi_write_seq;
    __u64 mptcpi_snd_una;
    __u64 mptcpi_rcv_nxt;
    __u8 mptcpi_local_addr_used;
    __u8 mptcpi_local_addr_max;
    __u8 mptcpi_csum_enabled;
    __u32 mptcpi_retransmits;
    __u64 mptcpi_bytes_retrans;
    __u64 mptcpi_bytes_sent;
    __u64 mptcpi_bytes_received;
    __u64 mptcpi_bytes_acked;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct mptcp_info {
    __u8 mptcpi_subflows;
    __u8 mptcpi_add_addr_signal;
    __u8 mptcpi_add_addr_accepted;
    __u8 mptcpi_subflows_max;
    __u8 mptcpi_add_addr_signal_max;
    __u8 mptcpi_add_addr_accepted_max;
    __u32 mptcpi_flags;
    __u32 mptcpi_token;
    __u64 mptcpi_write_seq;
    __u64 mptcpi_snd_una;
    __u64 mptcpi_rcv_nxt;
    __u8 mptcpi_local_addr_used;
    __u8 mptcpi_local_addr_max;
    __u8 mptcpi_csum_enabled;
    __u32 mptcpi_retransmits;
    __u64 mptcpi_bytes_retrans;
    __u64 mptcpi_bytes_sent;
    __u64 mptcpi_bytes_received;
    __u64 mptcpi_bytes_acked;
    __u8 mptcpi_subflows_total;
}
```
</details>
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
struct mptcp_info {
    __u8 mptcpi_subflows;
    __u8 mptcpi_add_addr_signal;
    __u8 mptcpi_add_addr_accepted;
    __u8 mptcpi_subflows_max;
    __u8 mptcpi_add_addr_signal_max;
    __u8 mptcpi_add_addr_accepted_max;
    __u32 mptcpi_flags;
    __u32 mptcpi_token;
    __u64 mptcpi_write_seq;
    __u64 mptcpi_snd_una;
    __u64 mptcpi_rcv_nxt;
    __u8 mptcpi_local_addr_used;
    __u8 mptcpi_local_addr_max;
    __u8 mptcpi_csum_enabled;
}
```
</details>
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>__u32 mptcpi_retransmits</code>
</li>
<li>
<b>Field added. </b>
<code>__u64 mptcpi_bytes_retrans</code>
</li>
<li>
<b>Field added. </b>
<code>__u64 mptcpi_bytes_sent</code>
</li>
<li>
<b>Field added. </b>
<code>__u64 mptcpi_bytes_received</code>
</li>
<li>
<b>Field added. </b>
<code>__u64 mptcpi_bytes_acked</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>__u8 mptcpi_subflows_total</code>
</li>
</ul>
</details>
</li>
</ul>
