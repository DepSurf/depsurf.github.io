# Struct: <code>mptcp_out_options</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct mptcp_out_options {
    u16 suboptions;
    u64 sndr_key;
    u64 rcvr_key;
    struct in_addr addr;
    struct in6_addr addr6;
    u8 addr_id;
    u64 ahmac;
    u8 rm_id;
    u8 join_id;
    u8 backup;
    u32 nonce;
    u64 thmac;
    u32 token;
    u8[20] hmac;
    struct mptcp_ext ext_copy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct mptcp_out_options {
    u16 suboptions;
    u64 sndr_key;
    u64 rcvr_key;
    struct in_addr addr;
    struct in6_addr addr6;
    u8 addr_id;
    u16 port;
    u64 ahmac;
    u8 rm_id;
    u8 join_id;
    u8 backup;
    u32 nonce;
    u64 thmac;
    u32 token;
    u8[20] hmac;
    struct mptcp_ext ext_copy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct mptcp_out_options {
    u16 suboptions;
    u64 sndr_key;
    u64 rcvr_key;
    u64 ahmac;
    struct mptcp_addr_info addr;
    struct mptcp_rm_list rm_list;
    u8 join_id;
    u8 backup;
    u8 reset_reason;
    u8 reset_transient;
    u32 nonce;
    u64 thmac;
    u32 token;
    u8[20] hmac;
    struct mptcp_ext ext_copy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct mptcp_out_options {
    u16 suboptions;
    struct mptcp_rm_list rm_list;
    u8 join_id;
    u8 backup;
    u8 reset_reason;
    u8 reset_transient;
    u8 csum_reqd;
    u8 allow_join_id0;
    u64 sndr_key;
    u64 rcvr_key;
    u64 data_seq;
    u32 subflow_seq;
    u16 data_len;
    __sum16 csum;
    struct mptcp_addr_info addr;
    u64 ahmac;
    struct mptcp_ext ext_copy;
    u64 fail_seq;
    u32 nonce;
    u32 token;
    u64 thmac;
    u8[20] hmac;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct mptcp_out_options {
    u16 suboptions;
    struct mptcp_rm_list rm_list;
    u8 join_id;
    u8 backup;
    u8 reset_reason;
    u8 reset_transient;
    u8 csum_reqd;
    u8 allow_join_id0;
    u64 sndr_key;
    u64 rcvr_key;
    u64 data_seq;
    u32 subflow_seq;
    u16 data_len;
    __sum16 csum;
    struct mptcp_addr_info addr;
    u64 ahmac;
    struct mptcp_ext ext_copy;
    u64 fail_seq;
    u32 nonce;
    u32 token;
    u64 thmac;
    u8[20] hmac;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct mptcp_out_options {
    u16 suboptions;
    struct mptcp_rm_list rm_list;
    u8 join_id;
    u8 backup;
    u8 reset_reason;
    u8 reset_transient;
    u8 csum_reqd;
    u8 allow_join_id0;
    u64 sndr_key;
    u64 rcvr_key;
    u64 data_seq;
    u32 subflow_seq;
    u16 data_len;
    __sum16 csum;
    struct mptcp_addr_info addr;
    u64 ahmac;
    struct mptcp_ext ext_copy;
    u64 fail_seq;
    u32 nonce;
    u32 token;
    u64 thmac;
    u8[20] hmac;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct mptcp_out_options {
    u16 suboptions;
    struct mptcp_rm_list rm_list;
    u8 join_id;
    u8 backup;
    u8 reset_reason;
    u8 reset_transient;
    u8 csum_reqd;
    u8 allow_join_id0;
    u64 sndr_key;
    u64 rcvr_key;
    u64 data_seq;
    u32 subflow_seq;
    u16 data_len;
    __sum16 csum;
    struct mptcp_addr_info addr;
    u64 ahmac;
    struct mptcp_ext ext_copy;
    u64 fail_seq;
    u32 nonce;
    u32 token;
    u64 thmac;
    u8[20] hmac;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct mptcp_out_options {
    u16 suboptions;
    struct mptcp_rm_list rm_list;
    u8 join_id;
    u8 backup;
    u8 reset_reason;
    u8 reset_transient;
    u8 csum_reqd;
    u8 allow_join_id0;
    u64 sndr_key;
    u64 rcvr_key;
    u64 data_seq;
    u32 subflow_seq;
    u16 data_len;
    __sum16 csum;
    struct mptcp_addr_info addr;
    u64 ahmac;
    struct mptcp_ext ext_copy;
    u64 fail_seq;
    u32 nonce;
    u32 token;
    u64 thmac;
    u8[20] hmac;
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
struct mptcp_out_options {
    u16 suboptions;
    u64 sndr_key;
    u64 rcvr_key;
    struct in_addr addr;
    struct in6_addr addr6;
    u8 addr_id;
    u64 ahmac;
    u8 rm_id;
    u8 join_id;
    u8 backup;
    u32 nonce;
    u64 thmac;
    u32 token;
    u8[20] hmac;
    struct mptcp_ext ext_copy;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u16 port</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct mptcp_rm_list rm_list</code>
</li>
<li>
<b>Field added. </b>
<code>u8 reset_reason</code>
</li>
<li>
<b>Field added. </b>
<code>u8 reset_transient</code>
</li>
<li>
<b>Field removed. </b>
<code>struct in6_addr addr6</code>
</li>
<li>
<b>Field removed. </b>
<code>u8 addr_id</code>
</li>
<li>
<b>Field removed. </b>
<code>u16 port</code>
</li>
<li>
<b>Field removed. </b>
<code>u8 rm_id</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct in_addr addr</code> ➡️ <code>struct mptcp_addr_info addr</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u8 csum_reqd</code>
</li>
<li>
<b>Field added. </b>
<code>u8 allow_join_id0</code>
</li>
<li>
<b>Field added. </b>
<code>u64 data_seq</code>
</li>
<li>
<b>Field added. </b>
<code>u32 subflow_seq</code>
</li>
<li>
<b>Field added. </b>
<code>u16 data_len</code>
</li>
<li>
<b>Field added. </b>
<code>__sum16 csum</code>
</li>
<li>
<b>Field added. </b>
<code>u64 fail_seq</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
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
