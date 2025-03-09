# Struct: <code>tcp_timewait_sock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct tcp_timewait_sock {
    struct inet_timewait_sock tw_sk;
    u32 tw_rcv_wnd;
    u32 tw_ts_offset;
    u32 tw_ts_recent;
    u32 tw_last_oow_ack_time;
    long int tw_ts_recent_stamp;
    struct tcp_md5sig_key * tw_md5_key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct tcp_timewait_sock {
    struct inet_timewait_sock tw_sk;
    u32 tw_rcv_wnd;
    u32 tw_ts_offset;
    u32 tw_ts_recent;
    u32 tw_last_oow_ack_time;
    long int tw_ts_recent_stamp;
    struct tcp_md5sig_key * tw_md5_key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct tcp_timewait_sock {
    struct inet_timewait_sock tw_sk;
    u32 tw_rcv_wnd;
    u32 tw_ts_offset;
    u32 tw_ts_recent;
    u32 tw_last_oow_ack_time;
    long int tw_ts_recent_stamp;
    struct tcp_md5sig_key * tw_md5_key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct tcp_timewait_sock {
    struct inet_timewait_sock tw_sk;
    u32 tw_rcv_wnd;
    u32 tw_ts_offset;
    u32 tw_ts_recent;
    u32 tw_last_oow_ack_time;
    long int tw_ts_recent_stamp;
    struct tcp_md5sig_key * tw_md5_key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct tcp_timewait_sock {
    struct inet_timewait_sock tw_sk;
    u32 tw_rcv_wnd;
    u32 tw_ts_offset;
    u32 tw_ts_recent;
    u32 tw_last_oow_ack_time;
    long int tw_ts_recent_stamp;
    struct tcp_md5sig_key * tw_md5_key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct tcp_timewait_sock {
    struct inet_timewait_sock tw_sk;
    u32 tw_rcv_wnd;
    u32 tw_ts_offset;
    u32 tw_ts_recent;
    u32 tw_last_oow_ack_time;
    long int tw_ts_recent_stamp;
    struct tcp_md5sig_key * tw_md5_key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct tcp_timewait_sock {
    struct inet_timewait_sock tw_sk;
    u32 tw_rcv_wnd;
    u32 tw_ts_offset;
    u32 tw_ts_recent;
    u32 tw_last_oow_ack_time;
    int tw_ts_recent_stamp;
    struct tcp_md5sig_key * tw_md5_key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct tcp_timewait_sock {
    struct inet_timewait_sock tw_sk;
    u32 tw_rcv_wnd;
    u32 tw_ts_offset;
    u32 tw_ts_recent;
    u32 tw_last_oow_ack_time;
    int tw_ts_recent_stamp;
    u32 tw_tx_delay;
    struct tcp_md5sig_key * tw_md5_key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct tcp_timewait_sock {
    struct inet_timewait_sock tw_sk;
    u32 tw_rcv_wnd;
    u32 tw_ts_offset;
    u32 tw_ts_recent;
    u32 tw_last_oow_ack_time;
    int tw_ts_recent_stamp;
    u32 tw_tx_delay;
    struct tcp_md5sig_key * tw_md5_key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct tcp_timewait_sock {
    struct inet_timewait_sock tw_sk;
    u32 tw_rcv_wnd;
    u32 tw_ts_offset;
    u32 tw_ts_recent;
    u32 tw_last_oow_ack_time;
    int tw_ts_recent_stamp;
    u32 tw_tx_delay;
    struct tcp_md5sig_key * tw_md5_key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct tcp_timewait_sock {
    struct inet_timewait_sock tw_sk;
    u32 tw_rcv_wnd;
    u32 tw_ts_offset;
    u32 tw_ts_recent;
    u32 tw_last_oow_ack_time;
    int tw_ts_recent_stamp;
    u32 tw_tx_delay;
    struct tcp_md5sig_key * tw_md5_key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct tcp_timewait_sock {
    struct inet_timewait_sock tw_sk;
    u32 tw_rcv_wnd;
    u32 tw_ts_offset;
    u32 tw_ts_recent;
    u32 tw_last_oow_ack_time;
    int tw_ts_recent_stamp;
    u32 tw_tx_delay;
    struct tcp_md5sig_key * tw_md5_key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct tcp_timewait_sock {
    struct inet_timewait_sock tw_sk;
    u32 tw_rcv_wnd;
    u32 tw_ts_offset;
    u32 tw_ts_recent;
    u32 tw_last_oow_ack_time;
    int tw_ts_recent_stamp;
    u32 tw_tx_delay;
    struct tcp_md5sig_key * tw_md5_key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct tcp_timewait_sock {
    struct inet_timewait_sock tw_sk;
    u32 tw_rcv_wnd;
    u32 tw_ts_offset;
    u32 tw_ts_recent;
    u32 tw_last_oow_ack_time;
    int tw_ts_recent_stamp;
    u32 tw_tx_delay;
    struct tcp_md5sig_key * tw_md5_key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct tcp_timewait_sock {
    struct inet_timewait_sock tw_sk;
    u32 tw_rcv_wnd;
    u32 tw_ts_offset;
    u32 tw_ts_recent;
    u32 tw_last_oow_ack_time;
    int tw_ts_recent_stamp;
    u32 tw_tx_delay;
    struct tcp_md5sig_key * tw_md5_key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct tcp_timewait_sock {
    struct inet_timewait_sock tw_sk;
    u32 tw_rcv_wnd;
    u32 tw_ts_offset;
    u32 tw_ts_recent;
    u32 tw_last_oow_ack_time;
    int tw_ts_recent_stamp;
    u32 tw_tx_delay;
    struct tcp_md5sig_key * tw_md5_key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct tcp_timewait_sock {
    struct inet_timewait_sock tw_sk;
    u32 tw_rcv_wnd;
    u32 tw_ts_offset;
    u32 tw_ts_recent;
    u32 tw_last_oow_ack_time;
    int tw_ts_recent_stamp;
    u32 tw_tx_delay;
    struct tcp_md5sig_key * tw_md5_key;
    struct tcp_ao_info * ao_info;
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct tcp_timewait_sock {
    struct inet_timewait_sock tw_sk;
    u32 tw_rcv_wnd;
    u32 tw_ts_offset;
    u32 tw_ts_recent;
    u32 tw_last_oow_ack_time;
    int tw_ts_recent_stamp;
    u32 tw_tx_delay;
    struct tcp_md5sig_key * tw_md5_key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct tcp_timewait_sock {
    struct inet_timewait_sock tw_sk;
    u32 tw_rcv_wnd;
    u32 tw_ts_offset;
    u32 tw_ts_recent;
    u32 tw_last_oow_ack_time;
    int tw_ts_recent_stamp;
    u32 tw_tx_delay;
    struct tcp_md5sig_key * tw_md5_key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct tcp_timewait_sock {
    struct inet_timewait_sock tw_sk;
    u32 tw_rcv_wnd;
    u32 tw_ts_offset;
    u32 tw_ts_recent;
    u32 tw_last_oow_ack_time;
    int tw_ts_recent_stamp;
    u32 tw_tx_delay;
    struct tcp_md5sig_key * tw_md5_key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct tcp_timewait_sock {
    struct inet_timewait_sock tw_sk;
    u32 tw_rcv_wnd;
    u32 tw_ts_offset;
    u32 tw_ts_recent;
    u32 tw_last_oow_ack_time;
    int tw_ts_recent_stamp;
    u32 tw_tx_delay;
    struct tcp_md5sig_key * tw_md5_key;
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct tcp_timewait_sock {
    struct inet_timewait_sock tw_sk;
    u32 tw_rcv_wnd;
    u32 tw_ts_offset;
    u32 tw_ts_recent;
    u32 tw_last_oow_ack_time;
    int tw_ts_recent_stamp;
    u32 tw_tx_delay;
    struct tcp_md5sig_key * tw_md5_key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct tcp_timewait_sock {
    struct inet_timewait_sock tw_sk;
    u32 tw_rcv_wnd;
    u32 tw_ts_offset;
    u32 tw_ts_recent;
    u32 tw_last_oow_ack_time;
    int tw_ts_recent_stamp;
    u32 tw_tx_delay;
    struct tcp_md5sig_key * tw_md5_key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct tcp_timewait_sock {
    struct inet_timewait_sock tw_sk;
    u32 tw_rcv_wnd;
    u32 tw_ts_offset;
    u32 tw_ts_recent;
    u32 tw_last_oow_ack_time;
    int tw_ts_recent_stamp;
    u32 tw_tx_delay;
    struct tcp_md5sig_key * tw_md5_key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct tcp_timewait_sock {
    struct inet_timewait_sock tw_sk;
    u32 tw_rcv_wnd;
    u32 tw_ts_offset;
    u32 tw_ts_recent;
    u32 tw_last_oow_ack_time;
    int tw_ts_recent_stamp;
    u32 tw_tx_delay;
    struct tcp_md5sig_key * tw_md5_key;
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>long int tw_ts_recent_stamp</code> ➡️ <code>int tw_ts_recent_stamp</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u32 tw_tx_delay</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct tcp_ao_info * ao_info</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
