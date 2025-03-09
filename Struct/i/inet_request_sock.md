# Struct: <code>inet_request_sock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct inet_request_sock {
    struct request_sock req;
    u16 snd_wscale;
    u16 rcv_wscale;
    u16 tstamp_ok;
    u16 sack_ok;
    u16 wscale_ok;
    u16 ecn_ok;
    u16 acked;
    u16 no_srccheck;
    u32 ir_mark;
    struct ip_options_rcu * opt;
    struct sk_buff * pktopts;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct inet_request_sock {
    struct request_sock req;
    u16 snd_wscale;
    u16 rcv_wscale;
    u16 tstamp_ok;
    u16 sack_ok;
    u16 wscale_ok;
    u16 ecn_ok;
    u16 acked;
    u16 no_srccheck;
    u32 ir_mark;
    struct ip_options_rcu * opt;
    struct ipv6_txoptions * ipv6_opt;
    struct sk_buff * pktopts;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct inet_request_sock {
    struct request_sock req;
    u16 snd_wscale;
    u16 rcv_wscale;
    u16 tstamp_ok;
    u16 sack_ok;
    u16 wscale_ok;
    u16 ecn_ok;
    u16 acked;
    u16 no_srccheck;
    u32 ir_mark;
    struct ip_options_rcu * opt;
    struct ipv6_txoptions * ipv6_opt;
    struct sk_buff * pktopts;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct inet_request_sock {
    struct request_sock req;
    u16 snd_wscale;
    u16 rcv_wscale;
    u16 tstamp_ok;
    u16 sack_ok;
    u16 wscale_ok;
    u16 ecn_ok;
    u16 acked;
    u16 no_srccheck;
    u32 ir_mark;
    struct ip_options_rcu * opt;
    struct ipv6_txoptions * ipv6_opt;
    struct sk_buff * pktopts;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct inet_request_sock {
    struct request_sock req;
    u16 snd_wscale;
    u16 rcv_wscale;
    u16 tstamp_ok;
    u16 sack_ok;
    u16 wscale_ok;
    u16 ecn_ok;
    u16 acked;
    u16 no_srccheck;
    u16 smc_ok;
    u32 ir_mark;
    struct ip_options_rcu * ireq_opt;
    struct ipv6_txoptions * ipv6_opt;
    struct sk_buff * pktopts;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct inet_request_sock {
    struct request_sock req;
    u16 snd_wscale;
    u16 rcv_wscale;
    u16 tstamp_ok;
    u16 sack_ok;
    u16 wscale_ok;
    u16 ecn_ok;
    u16 acked;
    u16 no_srccheck;
    u16 smc_ok;
    u32 ir_mark;
    struct ip_options_rcu * ireq_opt;
    struct ipv6_txoptions * ipv6_opt;
    struct sk_buff * pktopts;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct inet_request_sock {
    struct request_sock req;
    u16 snd_wscale;
    u16 rcv_wscale;
    u16 tstamp_ok;
    u16 sack_ok;
    u16 wscale_ok;
    u16 ecn_ok;
    u16 acked;
    u16 no_srccheck;
    u16 smc_ok;
    u32 ir_mark;
    struct ip_options_rcu * ireq_opt;
    struct ipv6_txoptions * ipv6_opt;
    struct sk_buff * pktopts;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct inet_request_sock {
    struct request_sock req;
    u16 snd_wscale;
    u16 rcv_wscale;
    u16 tstamp_ok;
    u16 sack_ok;
    u16 wscale_ok;
    u16 ecn_ok;
    u16 acked;
    u16 no_srccheck;
    u16 smc_ok;
    u32 ir_mark;
    struct ip_options_rcu * ireq_opt;
    struct ipv6_txoptions * ipv6_opt;
    struct sk_buff * pktopts;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct inet_request_sock {
    struct request_sock req;
    u16 snd_wscale;
    u16 rcv_wscale;
    u16 tstamp_ok;
    u16 sack_ok;
    u16 wscale_ok;
    u16 ecn_ok;
    u16 acked;
    u16 no_srccheck;
    u16 smc_ok;
    u32 ir_mark;
    struct ip_options_rcu * ireq_opt;
    struct ipv6_txoptions * ipv6_opt;
    struct sk_buff * pktopts;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct inet_request_sock {
    struct request_sock req;
    u16 snd_wscale;
    u16 rcv_wscale;
    u16 tstamp_ok;
    u16 sack_ok;
    u16 wscale_ok;
    u16 ecn_ok;
    u16 acked;
    u16 no_srccheck;
    u16 smc_ok;
    u32 ir_mark;
    struct ip_options_rcu * ireq_opt;
    struct ipv6_txoptions * ipv6_opt;
    struct sk_buff * pktopts;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct inet_request_sock {
    struct request_sock req;
    u16 snd_wscale;
    u16 rcv_wscale;
    u16 tstamp_ok;
    u16 sack_ok;
    u16 wscale_ok;
    u16 ecn_ok;
    u16 acked;
    u16 no_srccheck;
    u16 smc_ok;
    u32 ir_mark;
    struct ip_options_rcu * ireq_opt;
    struct ipv6_txoptions * ipv6_opt;
    struct sk_buff * pktopts;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct inet_request_sock {
    struct request_sock req;
    u16 snd_wscale;
    u16 rcv_wscale;
    u16 tstamp_ok;
    u16 sack_ok;
    u16 wscale_ok;
    u16 ecn_ok;
    u16 acked;
    u16 no_srccheck;
    u16 smc_ok;
    u32 ir_mark;
    struct ip_options_rcu * ireq_opt;
    struct ipv6_txoptions * ipv6_opt;
    struct sk_buff * pktopts;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct inet_request_sock {
    struct request_sock req;
    u16 snd_wscale;
    u16 rcv_wscale;
    u16 tstamp_ok;
    u16 sack_ok;
    u16 wscale_ok;
    u16 ecn_ok;
    u16 acked;
    u16 no_srccheck;
    u16 smc_ok;
    u32 ir_mark;
    struct ip_options_rcu * ireq_opt;
    struct ipv6_txoptions * ipv6_opt;
    struct sk_buff * pktopts;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct inet_request_sock {
    struct request_sock req;
    u16 snd_wscale;
    u16 rcv_wscale;
    u16 tstamp_ok;
    u16 sack_ok;
    u16 wscale_ok;
    u16 ecn_ok;
    u16 acked;
    u16 no_srccheck;
    u16 smc_ok;
    u32 ir_mark;
    struct ip_options_rcu * ireq_opt;
    struct ipv6_txoptions * ipv6_opt;
    struct sk_buff * pktopts;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct inet_request_sock {
    struct request_sock req;
    u16 snd_wscale;
    u16 rcv_wscale;
    u16 tstamp_ok;
    u16 sack_ok;
    u16 wscale_ok;
    u16 ecn_ok;
    u16 acked;
    u16 no_srccheck;
    u16 smc_ok;
    u32 ir_mark;
    struct ip_options_rcu * ireq_opt;
    struct ipv6_txoptions * ipv6_opt;
    struct sk_buff * pktopts;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct inet_request_sock {
    struct request_sock req;
    u16 snd_wscale;
    u16 rcv_wscale;
    u16 tstamp_ok;
    u16 sack_ok;
    u16 wscale_ok;
    u16 ecn_ok;
    u16 acked;
    u16 no_srccheck;
    u16 smc_ok;
    u32 ir_mark;
    struct ip_options_rcu * ireq_opt;
    struct ipv6_txoptions * ipv6_opt;
    struct sk_buff * pktopts;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct inet_request_sock {
    struct request_sock req;
    u16 snd_wscale;
    u16 rcv_wscale;
    u16 tstamp_ok;
    u16 sack_ok;
    u16 wscale_ok;
    u16 ecn_ok;
    u16 acked;
    u16 no_srccheck;
    u16 smc_ok;
    u32 ir_mark;
    struct ip_options_rcu * ireq_opt;
    struct ipv6_txoptions * ipv6_opt;
    struct sk_buff * pktopts;
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
struct inet_request_sock {
    struct request_sock req;
    u16 snd_wscale;
    u16 rcv_wscale;
    u16 tstamp_ok;
    u16 sack_ok;
    u16 wscale_ok;
    u16 ecn_ok;
    u16 acked;
    u16 no_srccheck;
    u16 smc_ok;
    u32 ir_mark;
    struct ip_options_rcu * ireq_opt;
    struct ipv6_txoptions * ipv6_opt;
    struct sk_buff * pktopts;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct inet_request_sock {
    struct request_sock req;
    u16 snd_wscale;
    u16 rcv_wscale;
    u16 tstamp_ok;
    u16 sack_ok;
    u16 wscale_ok;
    u16 ecn_ok;
    u16 acked;
    u16 no_srccheck;
    u16 smc_ok;
    u32 ir_mark;
    struct ip_options_rcu * ireq_opt;
    struct ipv6_txoptions * ipv6_opt;
    struct sk_buff * pktopts;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct inet_request_sock {
    struct request_sock req;
    u16 snd_wscale;
    u16 rcv_wscale;
    u16 tstamp_ok;
    u16 sack_ok;
    u16 wscale_ok;
    u16 ecn_ok;
    u16 acked;
    u16 no_srccheck;
    u16 smc_ok;
    u32 ir_mark;
    struct ip_options_rcu * ireq_opt;
    struct ipv6_txoptions * ipv6_opt;
    struct sk_buff * pktopts;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct inet_request_sock {
    struct request_sock req;
    u16 snd_wscale;
    u16 rcv_wscale;
    u16 tstamp_ok;
    u16 sack_ok;
    u16 wscale_ok;
    u16 ecn_ok;
    u16 acked;
    u16 no_srccheck;
    u16 smc_ok;
    u32 ir_mark;
    struct ip_options_rcu * ireq_opt;
    struct ipv6_txoptions * ipv6_opt;
    struct sk_buff * pktopts;
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
struct inet_request_sock {
    struct request_sock req;
    u16 snd_wscale;
    u16 rcv_wscale;
    u16 tstamp_ok;
    u16 sack_ok;
    u16 wscale_ok;
    u16 ecn_ok;
    u16 acked;
    u16 no_srccheck;
    u16 smc_ok;
    u32 ir_mark;
    struct ip_options_rcu * ireq_opt;
    struct ipv6_txoptions * ipv6_opt;
    struct sk_buff * pktopts;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct inet_request_sock {
    struct request_sock req;
    u16 snd_wscale;
    u16 rcv_wscale;
    u16 tstamp_ok;
    u16 sack_ok;
    u16 wscale_ok;
    u16 ecn_ok;
    u16 acked;
    u16 no_srccheck;
    u16 smc_ok;
    u32 ir_mark;
    struct ip_options_rcu * ireq_opt;
    struct ipv6_txoptions * ipv6_opt;
    struct sk_buff * pktopts;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct inet_request_sock {
    struct request_sock req;
    u16 snd_wscale;
    u16 rcv_wscale;
    u16 tstamp_ok;
    u16 sack_ok;
    u16 wscale_ok;
    u16 ecn_ok;
    u16 acked;
    u16 no_srccheck;
    u16 smc_ok;
    u32 ir_mark;
    struct ip_options_rcu * ireq_opt;
    struct ipv6_txoptions * ipv6_opt;
    struct sk_buff * pktopts;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct inet_request_sock {
    struct request_sock req;
    u16 snd_wscale;
    u16 rcv_wscale;
    u16 tstamp_ok;
    u16 sack_ok;
    u16 wscale_ok;
    u16 ecn_ok;
    u16 acked;
    u16 no_srccheck;
    u16 smc_ok;
    u32 ir_mark;
    struct ip_options_rcu * ireq_opt;
    struct ipv6_txoptions * ipv6_opt;
    struct sk_buff * pktopts;
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct ipv6_txoptions * ipv6_opt</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u16 smc_ok</code>
</li>
<li>
<b>Field added. </b>
<code>struct ip_options_rcu * ireq_opt</code>
</li>
<li>
<b>Field removed. </b>
<code>struct ip_options_rcu * opt</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
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
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
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
