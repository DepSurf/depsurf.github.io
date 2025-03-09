# Struct: <code>inet_timewait_sock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct inet_timewait_sock {
    struct sock_common __tw_common;
    int tw_timeout;
    volatile unsigned char tw_substate;
    unsigned char tw_rcv_wscale;
    __be16 tw_sport;
    unsigned int tw_kill;
    unsigned int tw_transparent;
    unsigned int tw_flowlabel;
    unsigned int tw_pad;
    unsigned int tw_tos;
    struct timer_list tw_timer;
    struct inet_bind_bucket * tw_tb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct inet_timewait_sock {
    struct sock_common __tw_common;
    int tw_timeout;
    volatile unsigned char tw_substate;
    unsigned char tw_rcv_wscale;
    __be16 tw_sport;
    unsigned int tw_kill;
    unsigned int tw_transparent;
    unsigned int tw_flowlabel;
    unsigned int tw_pad;
    unsigned int tw_tos;
    struct timer_list tw_timer;
    struct inet_bind_bucket * tw_tb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct inet_timewait_sock {
    struct sock_common __tw_common;
    int tw_timeout;
    volatile unsigned char tw_substate;
    unsigned char tw_rcv_wscale;
    __be16 tw_sport;
    unsigned int tw_kill;
    unsigned int tw_transparent;
    unsigned int tw_flowlabel;
    unsigned int tw_pad;
    unsigned int tw_tos;
    struct timer_list tw_timer;
    struct inet_bind_bucket * tw_tb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct inet_timewait_sock {
    struct sock_common __tw_common;
    int tw_timeout;
    volatile unsigned char tw_substate;
    unsigned char tw_rcv_wscale;
    __be16 tw_sport;
    unsigned int tw_kill;
    unsigned int tw_transparent;
    unsigned int tw_flowlabel;
    unsigned int tw_pad;
    unsigned int tw_tos;
    struct timer_list tw_timer;
    struct inet_bind_bucket * tw_tb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct inet_timewait_sock {
    struct sock_common __tw_common;
    int tw_timeout;
    volatile unsigned char tw_substate;
    unsigned char tw_rcv_wscale;
    __be16 tw_sport;
    unsigned int tw_kill;
    unsigned int tw_transparent;
    unsigned int tw_flowlabel;
    unsigned int tw_pad;
    unsigned int tw_tos;
    struct timer_list tw_timer;
    struct inet_bind_bucket * tw_tb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct inet_timewait_sock {
    struct sock_common __tw_common;
    __u32 tw_mark;
    volatile unsigned char tw_substate;
    unsigned char tw_rcv_wscale;
    __be16 tw_sport;
    unsigned int tw_kill;
    unsigned int tw_transparent;
    unsigned int tw_flowlabel;
    unsigned int tw_pad;
    unsigned int tw_tos;
    struct timer_list tw_timer;
    struct inet_bind_bucket * tw_tb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct inet_timewait_sock {
    struct sock_common __tw_common;
    __u32 tw_mark;
    volatile unsigned char tw_substate;
    unsigned char tw_rcv_wscale;
    __be16 tw_sport;
    unsigned int tw_kill;
    unsigned int tw_transparent;
    unsigned int tw_flowlabel;
    unsigned int tw_pad;
    unsigned int tw_tos;
    struct timer_list tw_timer;
    struct inet_bind_bucket * tw_tb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct inet_timewait_sock {
    struct sock_common __tw_common;
    __u32 tw_mark;
    volatile unsigned char tw_substate;
    unsigned char tw_rcv_wscale;
    __be16 tw_sport;
    unsigned int tw_kill;
    unsigned int tw_transparent;
    unsigned int tw_flowlabel;
    unsigned int tw_pad;
    unsigned int tw_tos;
    u32 tw_txhash;
    struct timer_list tw_timer;
    struct inet_bind_bucket * tw_tb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct inet_timewait_sock {
    struct sock_common __tw_common;
    __u32 tw_mark;
    volatile unsigned char tw_substate;
    unsigned char tw_rcv_wscale;
    __be16 tw_sport;
    unsigned int tw_kill;
    unsigned int tw_transparent;
    unsigned int tw_flowlabel;
    unsigned int tw_pad;
    unsigned int tw_tos;
    u32 tw_txhash;
    u32 tw_priority;
    struct timer_list tw_timer;
    struct inet_bind_bucket * tw_tb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct inet_timewait_sock {
    struct sock_common __tw_common;
    __u32 tw_mark;
    volatile unsigned char tw_substate;
    unsigned char tw_rcv_wscale;
    __be16 tw_sport;
    unsigned int tw_kill;
    unsigned int tw_transparent;
    unsigned int tw_flowlabel;
    unsigned int tw_pad;
    unsigned int tw_tos;
    u32 tw_txhash;
    u32 tw_priority;
    struct timer_list tw_timer;
    struct inet_bind_bucket * tw_tb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct inet_timewait_sock {
    struct sock_common __tw_common;
    __u32 tw_mark;
    volatile unsigned char tw_substate;
    unsigned char tw_rcv_wscale;
    __be16 tw_sport;
    unsigned int tw_kill;
    unsigned int tw_transparent;
    unsigned int tw_flowlabel;
    unsigned int tw_pad;
    unsigned int tw_tos;
    u32 tw_txhash;
    u32 tw_priority;
    struct timer_list tw_timer;
    struct inet_bind_bucket * tw_tb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct inet_timewait_sock {
    struct sock_common __tw_common;
    __u32 tw_mark;
    volatile unsigned char tw_substate;
    unsigned char tw_rcv_wscale;
    __be16 tw_sport;
    unsigned int tw_kill;
    unsigned int tw_transparent;
    unsigned int tw_flowlabel;
    unsigned int tw_pad;
    unsigned int tw_tos;
    u32 tw_txhash;
    u32 tw_priority;
    struct timer_list tw_timer;
    struct inet_bind_bucket * tw_tb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct inet_timewait_sock {
    struct sock_common __tw_common;
    __u32 tw_mark;
    volatile unsigned char tw_substate;
    unsigned char tw_rcv_wscale;
    __be16 tw_sport;
    unsigned int tw_kill;
    unsigned int tw_transparent;
    unsigned int tw_flowlabel;
    unsigned int tw_pad;
    unsigned int tw_tos;
    u32 tw_txhash;
    u32 tw_priority;
    struct timer_list tw_timer;
    struct inet_bind_bucket * tw_tb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct inet_timewait_sock {
    struct sock_common __tw_common;
    __u32 tw_mark;
    volatile unsigned char tw_substate;
    unsigned char tw_rcv_wscale;
    __be16 tw_sport;
    unsigned int tw_transparent;
    unsigned int tw_flowlabel;
    unsigned int tw_pad;
    unsigned int tw_tos;
    u32 tw_txhash;
    u32 tw_priority;
    struct timer_list tw_timer;
    struct inet_bind_bucket * tw_tb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct inet_timewait_sock {
    struct sock_common __tw_common;
    __u32 tw_mark;
    volatile unsigned char tw_substate;
    unsigned char tw_rcv_wscale;
    __be16 tw_sport;
    unsigned int tw_transparent;
    unsigned int tw_flowlabel;
    unsigned int tw_pad;
    unsigned int tw_tos;
    u32 tw_txhash;
    u32 tw_priority;
    struct timer_list tw_timer;
    struct inet_bind_bucket * tw_tb;
    struct inet_bind2_bucket * tw_tb2;
    struct hlist_node tw_bind2_node;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct inet_timewait_sock {
    struct sock_common __tw_common;
    __u32 tw_mark;
    volatile unsigned char tw_substate;
    unsigned char tw_rcv_wscale;
    __be16 tw_sport;
    unsigned int tw_transparent;
    unsigned int tw_flowlabel;
    unsigned int tw_pad;
    unsigned int tw_tos;
    u32 tw_txhash;
    u32 tw_priority;
    struct timer_list tw_timer;
    struct inet_bind_bucket * tw_tb;
    struct inet_bind2_bucket * tw_tb2;
    struct hlist_node tw_bind2_node;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct inet_timewait_sock {
    struct sock_common __tw_common;
    __u32 tw_mark;
    volatile unsigned char tw_substate;
    unsigned char tw_rcv_wscale;
    __be16 tw_sport;
    unsigned int tw_transparent;
    unsigned int tw_flowlabel;
    unsigned int tw_usec_ts;
    unsigned int tw_pad;
    unsigned int tw_tos;
    u32 tw_txhash;
    u32 tw_priority;
    struct timer_list tw_timer;
    struct inet_bind_bucket * tw_tb;
    struct inet_bind2_bucket * tw_tb2;
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
struct inet_timewait_sock {
    struct sock_common __tw_common;
    __u32 tw_mark;
    volatile unsigned char tw_substate;
    unsigned char tw_rcv_wscale;
    __be16 tw_sport;
    unsigned int tw_kill;
    unsigned int tw_transparent;
    unsigned int tw_flowlabel;
    unsigned int tw_pad;
    unsigned int tw_tos;
    u32 tw_txhash;
    u32 tw_priority;
    struct timer_list tw_timer;
    struct inet_bind_bucket * tw_tb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct inet_timewait_sock {
    struct sock_common __tw_common;
    __u32 tw_mark;
    volatile unsigned char tw_substate;
    unsigned char tw_rcv_wscale;
    __be16 tw_sport;
    unsigned int tw_kill;
    unsigned int tw_transparent;
    unsigned int tw_flowlabel;
    unsigned int tw_pad;
    unsigned int tw_tos;
    u32 tw_txhash;
    u32 tw_priority;
    struct timer_list tw_timer;
    struct inet_bind_bucket * tw_tb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct inet_timewait_sock {
    struct sock_common __tw_common;
    __u32 tw_mark;
    volatile unsigned char tw_substate;
    unsigned char tw_rcv_wscale;
    __be16 tw_sport;
    unsigned int tw_kill;
    unsigned int tw_transparent;
    unsigned int tw_flowlabel;
    unsigned int tw_pad;
    unsigned int tw_tos;
    u32 tw_txhash;
    u32 tw_priority;
    struct timer_list tw_timer;
    struct inet_bind_bucket * tw_tb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct inet_timewait_sock {
    struct sock_common __tw_common;
    __u32 tw_mark;
    volatile unsigned char tw_substate;
    unsigned char tw_rcv_wscale;
    __be16 tw_sport;
    unsigned int tw_kill;
    unsigned int tw_transparent;
    unsigned int tw_flowlabel;
    unsigned int tw_pad;
    unsigned int tw_tos;
    u32 tw_txhash;
    u32 tw_priority;
    struct timer_list tw_timer;
    struct inet_bind_bucket * tw_tb;
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
struct inet_timewait_sock {
    struct sock_common __tw_common;
    __u32 tw_mark;
    volatile unsigned char tw_substate;
    unsigned char tw_rcv_wscale;
    __be16 tw_sport;
    unsigned int tw_kill;
    unsigned int tw_transparent;
    unsigned int tw_flowlabel;
    unsigned int tw_pad;
    unsigned int tw_tos;
    u32 tw_txhash;
    u32 tw_priority;
    struct timer_list tw_timer;
    struct inet_bind_bucket * tw_tb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct inet_timewait_sock {
    struct sock_common __tw_common;
    __u32 tw_mark;
    volatile unsigned char tw_substate;
    unsigned char tw_rcv_wscale;
    __be16 tw_sport;
    unsigned int tw_kill;
    unsigned int tw_transparent;
    unsigned int tw_flowlabel;
    unsigned int tw_pad;
    unsigned int tw_tos;
    u32 tw_txhash;
    u32 tw_priority;
    struct timer_list tw_timer;
    struct inet_bind_bucket * tw_tb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct inet_timewait_sock {
    struct sock_common __tw_common;
    __u32 tw_mark;
    volatile unsigned char tw_substate;
    unsigned char tw_rcv_wscale;
    __be16 tw_sport;
    unsigned int tw_kill;
    unsigned int tw_transparent;
    unsigned int tw_flowlabel;
    unsigned int tw_pad;
    unsigned int tw_tos;
    u32 tw_txhash;
    u32 tw_priority;
    struct timer_list tw_timer;
    struct inet_bind_bucket * tw_tb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct inet_timewait_sock {
    struct sock_common __tw_common;
    __u32 tw_mark;
    volatile unsigned char tw_substate;
    unsigned char tw_rcv_wscale;
    __be16 tw_sport;
    unsigned int tw_kill;
    unsigned int tw_transparent;
    unsigned int tw_flowlabel;
    unsigned int tw_pad;
    unsigned int tw_tos;
    u32 tw_txhash;
    u32 tw_priority;
    struct timer_list tw_timer;
    struct inet_bind_bucket * tw_tb;
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
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>__u32 tw_mark</code>
</li>
<li>
<b>Field removed. </b>
<code>int tw_timeout</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u32 tw_txhash</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u32 tw_priority</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>unsigned int tw_kill</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct inet_bind2_bucket * tw_tb2</code>
</li>
<li>
<b>Field added. </b>
<code>struct hlist_node tw_bind2_node</code>
</li>
</ul>
</details>
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
<code>unsigned int tw_usec_ts</code>
</li>
<li>
<b>Field removed. </b>
<code>struct hlist_node tw_bind2_node</code>
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
