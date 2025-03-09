# Struct: <code>trace_event_raw_mptcp_dump_mpext</code>

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
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct trace_event_raw_mptcp_dump_mpext {
    struct trace_entry ent;
    u64 data_ack;
    u64 data_seq;
    u32 subflow_seq;
    u16 data_len;
    u8 use_map;
    u8 dsn64;
    u8 data_fin;
    u8 use_ack;
    u8 ack64;
    u8 mpc_map;
    u8 frozen;
    u8 reset_transient;
    u8 reset_reason;
    char[0] __data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct trace_event_raw_mptcp_dump_mpext {
    struct trace_entry ent;
    u64 data_ack;
    u64 data_seq;
    u32 subflow_seq;
    u16 data_len;
    u16 csum;
    u8 use_map;
    u8 dsn64;
    u8 data_fin;
    u8 use_ack;
    u8 ack64;
    u8 mpc_map;
    u8 frozen;
    u8 reset_transient;
    u8 reset_reason;
    u8 csum_reqd;
    char[0] __data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct trace_event_raw_mptcp_dump_mpext {
    struct trace_entry ent;
    u64 data_ack;
    u64 data_seq;
    u32 subflow_seq;
    u16 data_len;
    u16 csum;
    u8 use_map;
    u8 dsn64;
    u8 data_fin;
    u8 use_ack;
    u8 ack64;
    u8 mpc_map;
    u8 frozen;
    u8 reset_transient;
    u8 reset_reason;
    u8 csum_reqd;
    u8 infinite_map;
    char[0] __data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct trace_event_raw_mptcp_dump_mpext {
    struct trace_entry ent;
    u64 data_ack;
    u64 data_seq;
    u32 subflow_seq;
    u16 data_len;
    u16 csum;
    u8 use_map;
    u8 dsn64;
    u8 data_fin;
    u8 use_ack;
    u8 ack64;
    u8 mpc_map;
    u8 frozen;
    u8 reset_transient;
    u8 reset_reason;
    u8 csum_reqd;
    u8 infinite_map;
    char[0] __data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct trace_event_raw_mptcp_dump_mpext {
    struct trace_entry ent;
    u64 data_ack;
    u64 data_seq;
    u32 subflow_seq;
    u16 data_len;
    u16 csum;
    u8 use_map;
    u8 dsn64;
    u8 data_fin;
    u8 use_ack;
    u8 ack64;
    u8 mpc_map;
    u8 frozen;
    u8 reset_transient;
    u8 reset_reason;
    u8 csum_reqd;
    u8 infinite_map;
    char[0] __data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct trace_event_raw_mptcp_dump_mpext {
    struct trace_entry ent;
    u64 data_ack;
    u64 data_seq;
    u32 subflow_seq;
    u16 data_len;
    u16 csum;
    u8 use_map;
    u8 dsn64;
    u8 data_fin;
    u8 use_ack;
    u8 ack64;
    u8 mpc_map;
    u8 frozen;
    u8 reset_transient;
    u8 reset_reason;
    u8 csum_reqd;
    u8 infinite_map;
    char[0] __data;
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
struct trace_event_raw_mptcp_dump_mpext {
    struct trace_entry ent;
    u64 data_ack;
    u64 data_seq;
    u32 subflow_seq;
    u16 data_len;
    u8 use_map;
    u8 dsn64;
    u8 data_fin;
    u8 use_ack;
    u8 ack64;
    u8 mpc_map;
    u8 frozen;
    u8 reset_transient;
    u8 reset_reason;
    char[0] __data;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u16 csum</code>
</li>
<li>
<b>Field added. </b>
<code>u8 csum_reqd</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u8 infinite_map</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
