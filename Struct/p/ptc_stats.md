# Struct: <code>ptc_stats</code>

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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct ptc_stats {
    long unsigned int s_giveup;
    long unsigned int s_requestor;
    long unsigned int s_stimeout;
    long unsigned int s_dtimeout;
    long unsigned int s_strongnacks;
    long unsigned int s_time;
    long unsigned int s_retriesok;
    long unsigned int s_ntargcpu;
    long unsigned int s_ntargself;
    long unsigned int s_ntarglocals;
    long unsigned int s_ntargremotes;
    long unsigned int s_ntarglocaluvhub;
    long unsigned int s_ntargremoteuvhub;
    long unsigned int s_ntarguvhub;
    long unsigned int s_ntarguvhub16;
    long unsigned int s_ntarguvhub8;
    long unsigned int s_ntarguvhub4;
    long unsigned int s_ntarguvhub2;
    long unsigned int s_ntarguvhub1;
    long unsigned int s_resets_plug;
    long unsigned int s_resets_timeout;
    long unsigned int s_busy;
    long unsigned int s_throttles;
    long unsigned int s_retry_messages;
    long unsigned int s_bau_reenabled;
    long unsigned int s_bau_disabled;
    long unsigned int s_uv2_wars;
    long unsigned int s_uv2_wars_hw;
    long unsigned int s_uv2_war_waits;
    long unsigned int s_overipilimit;
    long unsigned int s_giveuplimit;
    long unsigned int s_enters;
    long unsigned int s_ipifordisabled;
    long unsigned int s_plugged;
    long unsigned int s_congested;
    long unsigned int d_alltlb;
    long unsigned int d_onetlb;
    long unsigned int d_multmsg;
    long unsigned int d_nomsg;
    long unsigned int d_time;
    long unsigned int d_requestee;
    long unsigned int d_retries;
    long unsigned int d_canceled;
    long unsigned int d_nocanceled;
    long unsigned int d_resets;
    long unsigned int d_rcanceled;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct ptc_stats {
    long unsigned int s_giveup;
    long unsigned int s_requestor;
    long unsigned int s_stimeout;
    long unsigned int s_dtimeout;
    long unsigned int s_strongnacks;
    long unsigned int s_time;
    long unsigned int s_retriesok;
    long unsigned int s_ntargcpu;
    long unsigned int s_ntargself;
    long unsigned int s_ntarglocals;
    long unsigned int s_ntargremotes;
    long unsigned int s_ntarglocaluvhub;
    long unsigned int s_ntargremoteuvhub;
    long unsigned int s_ntarguvhub;
    long unsigned int s_ntarguvhub16;
    long unsigned int s_ntarguvhub8;
    long unsigned int s_ntarguvhub4;
    long unsigned int s_ntarguvhub2;
    long unsigned int s_ntarguvhub1;
    long unsigned int s_resets_plug;
    long unsigned int s_resets_timeout;
    long unsigned int s_busy;
    long unsigned int s_throttles;
    long unsigned int s_retry_messages;
    long unsigned int s_bau_reenabled;
    long unsigned int s_bau_disabled;
    long unsigned int s_uv2_wars;
    long unsigned int s_uv2_wars_hw;
    long unsigned int s_uv2_war_waits;
    long unsigned int s_overipilimit;
    long unsigned int s_giveuplimit;
    long unsigned int s_enters;
    long unsigned int s_ipifordisabled;
    long unsigned int s_plugged;
    long unsigned int s_congested;
    long unsigned int d_alltlb;
    long unsigned int d_onetlb;
    long unsigned int d_multmsg;
    long unsigned int d_nomsg;
    long unsigned int d_time;
    long unsigned int d_requestee;
    long unsigned int d_retries;
    long unsigned int d_canceled;
    long unsigned int d_nocanceled;
    long unsigned int d_resets;
    long unsigned int d_rcanceled;
}
```
</details>
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
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct ptc_stats {
    long unsigned int s_giveup;
    long unsigned int s_requestor;
    long unsigned int s_stimeout;
    long unsigned int s_dtimeout;
    long unsigned int s_strongnacks;
    long unsigned int s_time;
    long unsigned int s_retriesok;
    long unsigned int s_ntargcpu;
    long unsigned int s_ntargself;
    long unsigned int s_ntarglocals;
    long unsigned int s_ntargremotes;
    long unsigned int s_ntarglocaluvhub;
    long unsigned int s_ntargremoteuvhub;
    long unsigned int s_ntarguvhub;
    long unsigned int s_ntarguvhub16;
    long unsigned int s_ntarguvhub8;
    long unsigned int s_ntarguvhub4;
    long unsigned int s_ntarguvhub2;
    long unsigned int s_ntarguvhub1;
    long unsigned int s_resets_plug;
    long unsigned int s_resets_timeout;
    long unsigned int s_busy;
    long unsigned int s_throttles;
    long unsigned int s_retry_messages;
    long unsigned int s_bau_reenabled;
    long unsigned int s_bau_disabled;
    long unsigned int s_uv2_wars;
    long unsigned int s_uv2_wars_hw;
    long unsigned int s_uv2_war_waits;
    long unsigned int s_overipilimit;
    long unsigned int s_giveuplimit;
    long unsigned int s_enters;
    long unsigned int s_ipifordisabled;
    long unsigned int s_plugged;
    long unsigned int s_congested;
    long unsigned int d_alltlb;
    long unsigned int d_onetlb;
    long unsigned int d_multmsg;
    long unsigned int d_nomsg;
    long unsigned int d_time;
    long unsigned int d_requestee;
    long unsigned int d_retries;
    long unsigned int d_canceled;
    long unsigned int d_nocanceled;
    long unsigned int d_resets;
    long unsigned int d_rcanceled;
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
struct ptc_stats {
    long unsigned int s_giveup;
    long unsigned int s_requestor;
    long unsigned int s_stimeout;
    long unsigned int s_dtimeout;
    long unsigned int s_strongnacks;
    long unsigned int s_time;
    long unsigned int s_retriesok;
    long unsigned int s_ntargcpu;
    long unsigned int s_ntargself;
    long unsigned int s_ntarglocals;
    long unsigned int s_ntargremotes;
    long unsigned int s_ntarglocaluvhub;
    long unsigned int s_ntargremoteuvhub;
    long unsigned int s_ntarguvhub;
    long unsigned int s_ntarguvhub16;
    long unsigned int s_ntarguvhub8;
    long unsigned int s_ntarguvhub4;
    long unsigned int s_ntarguvhub2;
    long unsigned int s_ntarguvhub1;
    long unsigned int s_resets_plug;
    long unsigned int s_resets_timeout;
    long unsigned int s_busy;
    long unsigned int s_throttles;
    long unsigned int s_retry_messages;
    long unsigned int s_bau_reenabled;
    long unsigned int s_bau_disabled;
    long unsigned int s_uv2_wars;
    long unsigned int s_uv2_wars_hw;
    long unsigned int s_uv2_war_waits;
    long unsigned int s_overipilimit;
    long unsigned int s_giveuplimit;
    long unsigned int s_enters;
    long unsigned int s_ipifordisabled;
    long unsigned int s_plugged;
    long unsigned int s_congested;
    long unsigned int d_alltlb;
    long unsigned int d_onetlb;
    long unsigned int d_multmsg;
    long unsigned int d_nomsg;
    long unsigned int d_time;
    long unsigned int d_requestee;
    long unsigned int d_retries;
    long unsigned int d_canceled;
    long unsigned int d_nocanceled;
    long unsigned int d_resets;
    long unsigned int d_rcanceled;
}
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
struct ptc_stats {
    long unsigned int s_giveup;
    long unsigned int s_requestor;
    long unsigned int s_stimeout;
    long unsigned int s_dtimeout;
    long unsigned int s_strongnacks;
    long unsigned int s_time;
    long unsigned int s_retriesok;
    long unsigned int s_ntargcpu;
    long unsigned int s_ntargself;
    long unsigned int s_ntarglocals;
    long unsigned int s_ntargremotes;
    long unsigned int s_ntarglocaluvhub;
    long unsigned int s_ntargremoteuvhub;
    long unsigned int s_ntarguvhub;
    long unsigned int s_ntarguvhub16;
    long unsigned int s_ntarguvhub8;
    long unsigned int s_ntarguvhub4;
    long unsigned int s_ntarguvhub2;
    long unsigned int s_ntarguvhub1;
    long unsigned int s_resets_plug;
    long unsigned int s_resets_timeout;
    long unsigned int s_busy;
    long unsigned int s_throttles;
    long unsigned int s_retry_messages;
    long unsigned int s_bau_reenabled;
    long unsigned int s_bau_disabled;
    long unsigned int s_uv2_wars;
    long unsigned int s_uv2_wars_hw;
    long unsigned int s_uv2_war_waits;
    long unsigned int s_overipilimit;
    long unsigned int s_giveuplimit;
    long unsigned int s_enters;
    long unsigned int s_ipifordisabled;
    long unsigned int s_plugged;
    long unsigned int s_congested;
    long unsigned int d_alltlb;
    long unsigned int d_onetlb;
    long unsigned int d_multmsg;
    long unsigned int d_nomsg;
    long unsigned int d_time;
    long unsigned int d_requestee;
    long unsigned int d_retries;
    long unsigned int d_canceled;
    long unsigned int d_nocanceled;
    long unsigned int d_resets;
    long unsigned int d_rcanceled;
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
struct ptc_stats {
    long unsigned int s_giveup;
    long unsigned int s_requestor;
    long unsigned int s_stimeout;
    long unsigned int s_dtimeout;
    long unsigned int s_strongnacks;
    long unsigned int s_time;
    long unsigned int s_retriesok;
    long unsigned int s_ntargcpu;
    long unsigned int s_ntargself;
    long unsigned int s_ntarglocals;
    long unsigned int s_ntargremotes;
    long unsigned int s_ntarglocaluvhub;
    long unsigned int s_ntargremoteuvhub;
    long unsigned int s_ntarguvhub;
    long unsigned int s_ntarguvhub16;
    long unsigned int s_ntarguvhub8;
    long unsigned int s_ntarguvhub4;
    long unsigned int s_ntarguvhub2;
    long unsigned int s_ntarguvhub1;
    long unsigned int s_resets_plug;
    long unsigned int s_resets_timeout;
    long unsigned int s_busy;
    long unsigned int s_throttles;
    long unsigned int s_retry_messages;
    long unsigned int s_bau_reenabled;
    long unsigned int s_bau_disabled;
    long unsigned int s_uv2_wars;
    long unsigned int s_uv2_wars_hw;
    long unsigned int s_uv2_war_waits;
    long unsigned int s_overipilimit;
    long unsigned int s_giveuplimit;
    long unsigned int s_enters;
    long unsigned int s_ipifordisabled;
    long unsigned int s_plugged;
    long unsigned int s_congested;
    long unsigned int d_alltlb;
    long unsigned int d_onetlb;
    long unsigned int d_multmsg;
    long unsigned int d_nomsg;
    long unsigned int d_time;
    long unsigned int d_requestee;
    long unsigned int d_retries;
    long unsigned int d_canceled;
    long unsigned int d_nocanceled;
    long unsigned int d_resets;
    long unsigned int d_rcanceled;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct ptc_stats {
    long unsigned int s_giveup;
    long unsigned int s_requestor;
    long unsigned int s_stimeout;
    long unsigned int s_dtimeout;
    long unsigned int s_strongnacks;
    long unsigned int s_time;
    long unsigned int s_retriesok;
    long unsigned int s_ntargcpu;
    long unsigned int s_ntargself;
    long unsigned int s_ntarglocals;
    long unsigned int s_ntargremotes;
    long unsigned int s_ntarglocaluvhub;
    long unsigned int s_ntargremoteuvhub;
    long unsigned int s_ntarguvhub;
    long unsigned int s_ntarguvhub16;
    long unsigned int s_ntarguvhub8;
    long unsigned int s_ntarguvhub4;
    long unsigned int s_ntarguvhub2;
    long unsigned int s_ntarguvhub1;
    long unsigned int s_resets_plug;
    long unsigned int s_resets_timeout;
    long unsigned int s_busy;
    long unsigned int s_throttles;
    long unsigned int s_retry_messages;
    long unsigned int s_bau_reenabled;
    long unsigned int s_bau_disabled;
    long unsigned int s_uv2_wars;
    long unsigned int s_uv2_wars_hw;
    long unsigned int s_uv2_war_waits;
    long unsigned int s_overipilimit;
    long unsigned int s_giveuplimit;
    long unsigned int s_enters;
    long unsigned int s_ipifordisabled;
    long unsigned int s_plugged;
    long unsigned int s_congested;
    long unsigned int d_alltlb;
    long unsigned int d_onetlb;
    long unsigned int d_multmsg;
    long unsigned int d_nomsg;
    long unsigned int d_time;
    long unsigned int d_requestee;
    long unsigned int d_retries;
    long unsigned int d_canceled;
    long unsigned int d_nocanceled;
    long unsigned int d_resets;
    long unsigned int d_rcanceled;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct ptc_stats {
    long unsigned int s_giveup;
    long unsigned int s_requestor;
    long unsigned int s_stimeout;
    long unsigned int s_dtimeout;
    long unsigned int s_strongnacks;
    long unsigned int s_time;
    long unsigned int s_retriesok;
    long unsigned int s_ntargcpu;
    long unsigned int s_ntargself;
    long unsigned int s_ntarglocals;
    long unsigned int s_ntargremotes;
    long unsigned int s_ntarglocaluvhub;
    long unsigned int s_ntargremoteuvhub;
    long unsigned int s_ntarguvhub;
    long unsigned int s_ntarguvhub16;
    long unsigned int s_ntarguvhub8;
    long unsigned int s_ntarguvhub4;
    long unsigned int s_ntarguvhub2;
    long unsigned int s_ntarguvhub1;
    long unsigned int s_resets_plug;
    long unsigned int s_resets_timeout;
    long unsigned int s_busy;
    long unsigned int s_throttles;
    long unsigned int s_retry_messages;
    long unsigned int s_bau_reenabled;
    long unsigned int s_bau_disabled;
    long unsigned int s_uv2_wars;
    long unsigned int s_uv2_wars_hw;
    long unsigned int s_uv2_war_waits;
    long unsigned int s_overipilimit;
    long unsigned int s_giveuplimit;
    long unsigned int s_enters;
    long unsigned int s_ipifordisabled;
    long unsigned int s_plugged;
    long unsigned int s_congested;
    long unsigned int d_alltlb;
    long unsigned int d_onetlb;
    long unsigned int d_multmsg;
    long unsigned int d_nomsg;
    long unsigned int d_time;
    long unsigned int d_requestee;
    long unsigned int d_retries;
    long unsigned int d_canceled;
    long unsigned int d_nocanceled;
    long unsigned int d_resets;
    long unsigned int d_rcanceled;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct ptc_stats {
    long unsigned int s_giveup;
    long unsigned int s_requestor;
    long unsigned int s_stimeout;
    long unsigned int s_dtimeout;
    long unsigned int s_strongnacks;
    long unsigned int s_time;
    long unsigned int s_retriesok;
    long unsigned int s_ntargcpu;
    long unsigned int s_ntargself;
    long unsigned int s_ntarglocals;
    long unsigned int s_ntargremotes;
    long unsigned int s_ntarglocaluvhub;
    long unsigned int s_ntargremoteuvhub;
    long unsigned int s_ntarguvhub;
    long unsigned int s_ntarguvhub16;
    long unsigned int s_ntarguvhub8;
    long unsigned int s_ntarguvhub4;
    long unsigned int s_ntarguvhub2;
    long unsigned int s_ntarguvhub1;
    long unsigned int s_resets_plug;
    long unsigned int s_resets_timeout;
    long unsigned int s_busy;
    long unsigned int s_throttles;
    long unsigned int s_retry_messages;
    long unsigned int s_bau_reenabled;
    long unsigned int s_bau_disabled;
    long unsigned int s_uv2_wars;
    long unsigned int s_uv2_wars_hw;
    long unsigned int s_uv2_war_waits;
    long unsigned int s_overipilimit;
    long unsigned int s_giveuplimit;
    long unsigned int s_enters;
    long unsigned int s_ipifordisabled;
    long unsigned int s_plugged;
    long unsigned int s_congested;
    long unsigned int d_alltlb;
    long unsigned int d_onetlb;
    long unsigned int d_multmsg;
    long unsigned int d_nomsg;
    long unsigned int d_time;
    long unsigned int d_requestee;
    long unsigned int d_retries;
    long unsigned int d_canceled;
    long unsigned int d_nocanceled;
    long unsigned int d_resets;
    long unsigned int d_rcanceled;
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➖</summary>

```c
struct ptc_stats {
    long unsigned int s_giveup;
    long unsigned int s_requestor;
    long unsigned int s_stimeout;
    long unsigned int s_dtimeout;
    long unsigned int s_strongnacks;
    long unsigned int s_time;
    long unsigned int s_retriesok;
    long unsigned int s_ntargcpu;
    long unsigned int s_ntargself;
    long unsigned int s_ntarglocals;
    long unsigned int s_ntargremotes;
    long unsigned int s_ntarglocaluvhub;
    long unsigned int s_ntargremoteuvhub;
    long unsigned int s_ntarguvhub;
    long unsigned int s_ntarguvhub16;
    long unsigned int s_ntarguvhub8;
    long unsigned int s_ntarguvhub4;
    long unsigned int s_ntarguvhub2;
    long unsigned int s_ntarguvhub1;
    long unsigned int s_resets_plug;
    long unsigned int s_resets_timeout;
    long unsigned int s_busy;
    long unsigned int s_throttles;
    long unsigned int s_retry_messages;
    long unsigned int s_bau_reenabled;
    long unsigned int s_bau_disabled;
    long unsigned int s_uv2_wars;
    long unsigned int s_uv2_wars_hw;
    long unsigned int s_uv2_war_waits;
    long unsigned int s_overipilimit;
    long unsigned int s_giveuplimit;
    long unsigned int s_enters;
    long unsigned int s_ipifordisabled;
    long unsigned int s_plugged;
    long unsigned int s_congested;
    long unsigned int d_alltlb;
    long unsigned int d_onetlb;
    long unsigned int d_multmsg;
    long unsigned int d_nomsg;
    long unsigned int d_time;
    long unsigned int d_requestee;
    long unsigned int d_retries;
    long unsigned int d_canceled;
    long unsigned int d_nocanceled;
    long unsigned int d_resets;
    long unsigned int d_rcanceled;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
struct ptc_stats {
    long unsigned int s_giveup;
    long unsigned int s_requestor;
    long unsigned int s_stimeout;
    long unsigned int s_dtimeout;
    long unsigned int s_strongnacks;
    long unsigned int s_time;
    long unsigned int s_retriesok;
    long unsigned int s_ntargcpu;
    long unsigned int s_ntargself;
    long unsigned int s_ntarglocals;
    long unsigned int s_ntargremotes;
    long unsigned int s_ntarglocaluvhub;
    long unsigned int s_ntargremoteuvhub;
    long unsigned int s_ntarguvhub;
    long unsigned int s_ntarguvhub16;
    long unsigned int s_ntarguvhub8;
    long unsigned int s_ntarguvhub4;
    long unsigned int s_ntarguvhub2;
    long unsigned int s_ntarguvhub1;
    long unsigned int s_resets_plug;
    long unsigned int s_resets_timeout;
    long unsigned int s_busy;
    long unsigned int s_throttles;
    long unsigned int s_retry_messages;
    long unsigned int s_bau_reenabled;
    long unsigned int s_bau_disabled;
    long unsigned int s_uv2_wars;
    long unsigned int s_uv2_wars_hw;
    long unsigned int s_uv2_war_waits;
    long unsigned int s_overipilimit;
    long unsigned int s_giveuplimit;
    long unsigned int s_enters;
    long unsigned int s_ipifordisabled;
    long unsigned int s_plugged;
    long unsigned int s_congested;
    long unsigned int d_alltlb;
    long unsigned int d_onetlb;
    long unsigned int d_multmsg;
    long unsigned int d_nomsg;
    long unsigned int d_time;
    long unsigned int d_requestee;
    long unsigned int d_retries;
    long unsigned int d_canceled;
    long unsigned int d_nocanceled;
    long unsigned int d_resets;
    long unsigned int d_rcanceled;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ➖</summary>

```c
struct ptc_stats {
    long unsigned int s_giveup;
    long unsigned int s_requestor;
    long unsigned int s_stimeout;
    long unsigned int s_dtimeout;
    long unsigned int s_strongnacks;
    long unsigned int s_time;
    long unsigned int s_retriesok;
    long unsigned int s_ntargcpu;
    long unsigned int s_ntargself;
    long unsigned int s_ntarglocals;
    long unsigned int s_ntargremotes;
    long unsigned int s_ntarglocaluvhub;
    long unsigned int s_ntargremoteuvhub;
    long unsigned int s_ntarguvhub;
    long unsigned int s_ntarguvhub16;
    long unsigned int s_ntarguvhub8;
    long unsigned int s_ntarguvhub4;
    long unsigned int s_ntarguvhub2;
    long unsigned int s_ntarguvhub1;
    long unsigned int s_resets_plug;
    long unsigned int s_resets_timeout;
    long unsigned int s_busy;
    long unsigned int s_throttles;
    long unsigned int s_retry_messages;
    long unsigned int s_bau_reenabled;
    long unsigned int s_bau_disabled;
    long unsigned int s_uv2_wars;
    long unsigned int s_uv2_wars_hw;
    long unsigned int s_uv2_war_waits;
    long unsigned int s_overipilimit;
    long unsigned int s_giveuplimit;
    long unsigned int s_enters;
    long unsigned int s_ipifordisabled;
    long unsigned int s_plugged;
    long unsigned int s_congested;
    long unsigned int d_alltlb;
    long unsigned int d_onetlb;
    long unsigned int d_multmsg;
    long unsigned int d_nomsg;
    long unsigned int d_time;
    long unsigned int d_requestee;
    long unsigned int d_retries;
    long unsigned int d_canceled;
    long unsigned int d_nocanceled;
    long unsigned int d_resets;
    long unsigned int d_rcanceled;
}
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
