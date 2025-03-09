# Struct: <code>inet_sock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct inet_sock {
    struct sock sk;
    struct ipv6_pinfo * pinet6;
    __be32 inet_saddr;
    __s16 uc_ttl;
    __u16 cmsg_flags;
    __be16 inet_sport;
    __u16 inet_id;
    struct ip_options_rcu * inet_opt;
    int rx_dst_ifindex;
    __u8 tos;
    __u8 min_ttl;
    __u8 mc_ttl;
    __u8 pmtudisc;
    __u8 recverr;
    __u8 is_icsk;
    __u8 freebind;
    __u8 hdrincl;
    __u8 mc_loop;
    __u8 transparent;
    __u8 mc_all;
    __u8 nodefrag;
    __u8 bind_address_no_port;
    __u8 rcv_tos;
    __u8 convert_csum;
    int uc_index;
    int mc_index;
    __be32 mc_addr;
    struct ip_mc_socklist * mc_list;
    struct inet_cork_full cork;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct inet_sock {
    struct sock sk;
    struct ipv6_pinfo * pinet6;
    __be32 inet_saddr;
    __s16 uc_ttl;
    __u16 cmsg_flags;
    __be16 inet_sport;
    __u16 inet_id;
    struct ip_options_rcu * inet_opt;
    int rx_dst_ifindex;
    __u8 tos;
    __u8 min_ttl;
    __u8 mc_ttl;
    __u8 pmtudisc;
    __u8 recverr;
    __u8 is_icsk;
    __u8 freebind;
    __u8 hdrincl;
    __u8 mc_loop;
    __u8 transparent;
    __u8 mc_all;
    __u8 nodefrag;
    __u8 bind_address_no_port;
    __u8 rcv_tos;
    __u8 convert_csum;
    int uc_index;
    int mc_index;
    __be32 mc_addr;
    struct ip_mc_socklist * mc_list;
    struct inet_cork_full cork;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct inet_sock {
    struct sock sk;
    struct ipv6_pinfo * pinet6;
    __be32 inet_saddr;
    __s16 uc_ttl;
    __u16 cmsg_flags;
    __be16 inet_sport;
    __u16 inet_id;
    struct ip_options_rcu * inet_opt;
    int rx_dst_ifindex;
    __u8 tos;
    __u8 min_ttl;
    __u8 mc_ttl;
    __u8 pmtudisc;
    __u8 recverr;
    __u8 is_icsk;
    __u8 freebind;
    __u8 hdrincl;
    __u8 mc_loop;
    __u8 transparent;
    __u8 mc_all;
    __u8 nodefrag;
    __u8 bind_address_no_port;
    __u8 rcv_tos;
    __u8 convert_csum;
    int uc_index;
    int mc_index;
    __be32 mc_addr;
    struct ip_mc_socklist * mc_list;
    struct inet_cork_full cork;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct inet_sock {
    struct sock sk;
    struct ipv6_pinfo * pinet6;
    __be32 inet_saddr;
    __s16 uc_ttl;
    __u16 cmsg_flags;
    __be16 inet_sport;
    __u16 inet_id;
    struct ip_options_rcu * inet_opt;
    int rx_dst_ifindex;
    __u8 tos;
    __u8 min_ttl;
    __u8 mc_ttl;
    __u8 pmtudisc;
    __u8 recverr;
    __u8 is_icsk;
    __u8 freebind;
    __u8 hdrincl;
    __u8 mc_loop;
    __u8 transparent;
    __u8 mc_all;
    __u8 nodefrag;
    __u8 bind_address_no_port;
    __u8 defer_connect;
    __u8 rcv_tos;
    __u8 convert_csum;
    int uc_index;
    int mc_index;
    __be32 mc_addr;
    struct ip_mc_socklist * mc_list;
    struct inet_cork_full cork;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct inet_sock {
    struct sock sk;
    struct ipv6_pinfo * pinet6;
    __be32 inet_saddr;
    __s16 uc_ttl;
    __u16 cmsg_flags;
    __be16 inet_sport;
    __u16 inet_id;
    struct ip_options_rcu * inet_opt;
    int rx_dst_ifindex;
    __u8 tos;
    __u8 min_ttl;
    __u8 mc_ttl;
    __u8 pmtudisc;
    __u8 recverr;
    __u8 is_icsk;
    __u8 freebind;
    __u8 hdrincl;
    __u8 mc_loop;
    __u8 transparent;
    __u8 mc_all;
    __u8 nodefrag;
    __u8 bind_address_no_port;
    __u8 defer_connect;
    __u8 rcv_tos;
    __u8 convert_csum;
    int uc_index;
    int mc_index;
    __be32 mc_addr;
    struct ip_mc_socklist * mc_list;
    struct inet_cork_full cork;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct inet_sock {
    struct sock sk;
    struct ipv6_pinfo * pinet6;
    __be32 inet_saddr;
    __s16 uc_ttl;
    __u16 cmsg_flags;
    __be16 inet_sport;
    __u16 inet_id;
    struct ip_options_rcu * inet_opt;
    int rx_dst_ifindex;
    __u8 tos;
    __u8 min_ttl;
    __u8 mc_ttl;
    __u8 pmtudisc;
    __u8 recverr;
    __u8 is_icsk;
    __u8 freebind;
    __u8 hdrincl;
    __u8 mc_loop;
    __u8 transparent;
    __u8 mc_all;
    __u8 nodefrag;
    __u8 bind_address_no_port;
    __u8 defer_connect;
    __u8 rcv_tos;
    __u8 convert_csum;
    int uc_index;
    int mc_index;
    __be32 mc_addr;
    struct ip_mc_socklist * mc_list;
    struct inet_cork_full cork;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct inet_sock {
    struct sock sk;
    struct ipv6_pinfo * pinet6;
    __be32 inet_saddr;
    __s16 uc_ttl;
    __u16 cmsg_flags;
    __be16 inet_sport;
    __u16 inet_id;
    struct ip_options_rcu * inet_opt;
    int rx_dst_ifindex;
    __u8 tos;
    __u8 min_ttl;
    __u8 mc_ttl;
    __u8 pmtudisc;
    __u8 recverr;
    __u8 is_icsk;
    __u8 freebind;
    __u8 hdrincl;
    __u8 mc_loop;
    __u8 transparent;
    __u8 mc_all;
    __u8 nodefrag;
    __u8 bind_address_no_port;
    __u8 defer_connect;
    __u8 rcv_tos;
    __u8 convert_csum;
    int uc_index;
    int mc_index;
    __be32 mc_addr;
    struct ip_mc_socklist * mc_list;
    struct inet_cork_full cork;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct inet_sock {
    struct sock sk;
    struct ipv6_pinfo * pinet6;
    __be32 inet_saddr;
    __s16 uc_ttl;
    __u16 cmsg_flags;
    __be16 inet_sport;
    __u16 inet_id;
    struct ip_options_rcu * inet_opt;
    int rx_dst_ifindex;
    __u8 tos;
    __u8 min_ttl;
    __u8 mc_ttl;
    __u8 pmtudisc;
    __u8 recverr;
    __u8 is_icsk;
    __u8 freebind;
    __u8 hdrincl;
    __u8 mc_loop;
    __u8 transparent;
    __u8 mc_all;
    __u8 nodefrag;
    __u8 bind_address_no_port;
    __u8 defer_connect;
    __u8 rcv_tos;
    __u8 convert_csum;
    int uc_index;
    int mc_index;
    __be32 mc_addr;
    struct ip_mc_socklist * mc_list;
    struct inet_cork_full cork;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct inet_sock {
    struct sock sk;
    struct ipv6_pinfo * pinet6;
    __be32 inet_saddr;
    __s16 uc_ttl;
    __u16 cmsg_flags;
    __be16 inet_sport;
    __u16 inet_id;
    struct ip_options_rcu * inet_opt;
    int rx_dst_ifindex;
    __u8 tos;
    __u8 min_ttl;
    __u8 mc_ttl;
    __u8 pmtudisc;
    __u8 recverr;
    __u8 is_icsk;
    __u8 freebind;
    __u8 hdrincl;
    __u8 mc_loop;
    __u8 transparent;
    __u8 mc_all;
    __u8 nodefrag;
    __u8 bind_address_no_port;
    __u8 defer_connect;
    __u8 rcv_tos;
    __u8 convert_csum;
    int uc_index;
    int mc_index;
    __be32 mc_addr;
    struct ip_mc_socklist * mc_list;
    struct inet_cork_full cork;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct inet_sock {
    struct sock sk;
    struct ipv6_pinfo * pinet6;
    __be32 inet_saddr;
    __s16 uc_ttl;
    __u16 cmsg_flags;
    __be16 inet_sport;
    __u16 inet_id;
    struct ip_options_rcu * inet_opt;
    int rx_dst_ifindex;
    __u8 tos;
    __u8 min_ttl;
    __u8 mc_ttl;
    __u8 pmtudisc;
    __u8 recverr;
    __u8 is_icsk;
    __u8 freebind;
    __u8 hdrincl;
    __u8 mc_loop;
    __u8 transparent;
    __u8 mc_all;
    __u8 nodefrag;
    __u8 bind_address_no_port;
    __u8 defer_connect;
    __u8 rcv_tos;
    __u8 convert_csum;
    int uc_index;
    int mc_index;
    __be32 mc_addr;
    struct ip_mc_socklist * mc_list;
    struct inet_cork_full cork;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct inet_sock {
    struct sock sk;
    struct ipv6_pinfo * pinet6;
    __be32 inet_saddr;
    __s16 uc_ttl;
    __u16 cmsg_flags;
    __be16 inet_sport;
    __u16 inet_id;
    struct ip_options_rcu * inet_opt;
    int rx_dst_ifindex;
    __u8 tos;
    __u8 min_ttl;
    __u8 mc_ttl;
    __u8 pmtudisc;
    __u8 recverr;
    __u8 is_icsk;
    __u8 freebind;
    __u8 hdrincl;
    __u8 mc_loop;
    __u8 transparent;
    __u8 mc_all;
    __u8 nodefrag;
    __u8 bind_address_no_port;
    __u8 recverr_rfc4884;
    __u8 defer_connect;
    __u8 rcv_tos;
    __u8 convert_csum;
    int uc_index;
    int mc_index;
    __be32 mc_addr;
    struct ip_mc_socklist * mc_list;
    struct inet_cork_full cork;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct inet_sock {
    struct sock sk;
    struct ipv6_pinfo * pinet6;
    __be32 inet_saddr;
    __s16 uc_ttl;
    __u16 cmsg_flags;
    __be16 inet_sport;
    __u16 inet_id;
    struct ip_options_rcu * inet_opt;
    int rx_dst_ifindex;
    __u8 tos;
    __u8 min_ttl;
    __u8 mc_ttl;
    __u8 pmtudisc;
    __u8 recverr;
    __u8 is_icsk;
    __u8 freebind;
    __u8 hdrincl;
    __u8 mc_loop;
    __u8 transparent;
    __u8 mc_all;
    __u8 nodefrag;
    __u8 bind_address_no_port;
    __u8 recverr_rfc4884;
    __u8 defer_connect;
    __u8 rcv_tos;
    __u8 convert_csum;
    int uc_index;
    int mc_index;
    __be32 mc_addr;
    struct ip_mc_socklist * mc_list;
    struct inet_cork_full cork;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct inet_sock {
    struct sock sk;
    struct ipv6_pinfo * pinet6;
    __be32 inet_saddr;
    __s16 uc_ttl;
    __u16 cmsg_flags;
    struct ip_options_rcu * inet_opt;
    __be16 inet_sport;
    __u16 inet_id;
    __u8 tos;
    __u8 min_ttl;
    __u8 mc_ttl;
    __u8 pmtudisc;
    __u8 recverr;
    __u8 is_icsk;
    __u8 freebind;
    __u8 hdrincl;
    __u8 mc_loop;
    __u8 transparent;
    __u8 mc_all;
    __u8 nodefrag;
    __u8 bind_address_no_port;
    __u8 recverr_rfc4884;
    __u8 defer_connect;
    __u8 rcv_tos;
    __u8 convert_csum;
    int uc_index;
    int mc_index;
    __be32 mc_addr;
    struct ip_mc_socklist * mc_list;
    struct inet_cork_full cork;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct inet_sock {
    struct sock sk;
    struct ipv6_pinfo * pinet6;
    __be32 inet_saddr;
    __s16 uc_ttl;
    __u16 cmsg_flags;
    struct ip_options_rcu * inet_opt;
    __be16 inet_sport;
    __u16 inet_id;
    __u8 tos;
    __u8 min_ttl;
    __u8 mc_ttl;
    __u8 pmtudisc;
    __u8 recverr;
    __u8 is_icsk;
    __u8 freebind;
    __u8 hdrincl;
    __u8 mc_loop;
    __u8 transparent;
    __u8 mc_all;
    __u8 nodefrag;
    __u8 bind_address_no_port;
    __u8 recverr_rfc4884;
    __u8 defer_connect;
    __u8 rcv_tos;
    __u8 convert_csum;
    int uc_index;
    int mc_index;
    __be32 mc_addr;
    struct ip_mc_socklist * mc_list;
    struct inet_cork_full cork;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct inet_sock {
    struct sock sk;
    struct ipv6_pinfo * pinet6;
    __be32 inet_saddr;
    __s16 uc_ttl;
    __u16 cmsg_flags;
    struct ip_options_rcu * inet_opt;
    __be16 inet_sport;
    __u16 inet_id;
    __u8 tos;
    __u8 min_ttl;
    __u8 mc_ttl;
    __u8 pmtudisc;
    __u8 recverr;
    __u8 is_icsk;
    __u8 freebind;
    __u8 hdrincl;
    __u8 mc_loop;
    __u8 transparent;
    __u8 mc_all;
    __u8 nodefrag;
    __u8 bind_address_no_port;
    __u8 recverr_rfc4884;
    __u8 defer_connect;
    __u8 rcv_tos;
    __u8 convert_csum;
    int uc_index;
    int mc_index;
    __be32 mc_addr;
    struct ip_mc_socklist * mc_list;
    struct inet_cork_full cork;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct inet_sock {
    struct sock sk;
    struct ipv6_pinfo * pinet6;
    __be32 inet_saddr;
    __s16 uc_ttl;
    __u16 cmsg_flags;
    struct ip_options_rcu * inet_opt;
    atomic_t inet_id;
    __be16 inet_sport;
    __u8 tos;
    __u8 min_ttl;
    __u8 mc_ttl;
    __u8 pmtudisc;
    __u8 recverr;
    __u8 is_icsk;
    __u8 freebind;
    __u8 hdrincl;
    __u8 mc_loop;
    __u8 transparent;
    __u8 mc_all;
    __u8 nodefrag;
    __u8 bind_address_no_port;
    __u8 recverr_rfc4884;
    __u8 defer_connect;
    __u8 rcv_tos;
    __u8 convert_csum;
    int uc_index;
    int mc_index;
    __be32 mc_addr;
    struct ip_mc_socklist * mc_list;
    struct inet_cork_full cork;
    struct (anon) local_port_range;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct inet_sock {
    struct sock sk;
    struct ipv6_pinfo * pinet6;
    long unsigned int inet_flags;
    __be32 inet_saddr;
    __s16 uc_ttl;
    __be16 inet_sport;
    struct ip_options_rcu * inet_opt;
    atomic_t inet_id;
    __u8 tos;
    __u8 min_ttl;
    __u8 mc_ttl;
    __u8 pmtudisc;
    __u8 rcv_tos;
    __u8 convert_csum;
    int uc_index;
    int mc_index;
    __be32 mc_addr;
    u32 local_port_range;
    struct ip_mc_socklist * mc_list;
    struct inet_cork_full cork;
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
struct inet_sock {
    struct sock sk;
    struct ipv6_pinfo * pinet6;
    __be32 inet_saddr;
    __s16 uc_ttl;
    __u16 cmsg_flags;
    __be16 inet_sport;
    __u16 inet_id;
    struct ip_options_rcu * inet_opt;
    int rx_dst_ifindex;
    __u8 tos;
    __u8 min_ttl;
    __u8 mc_ttl;
    __u8 pmtudisc;
    __u8 recverr;
    __u8 is_icsk;
    __u8 freebind;
    __u8 hdrincl;
    __u8 mc_loop;
    __u8 transparent;
    __u8 mc_all;
    __u8 nodefrag;
    __u8 bind_address_no_port;
    __u8 defer_connect;
    __u8 rcv_tos;
    __u8 convert_csum;
    int uc_index;
    int mc_index;
    __be32 mc_addr;
    struct ip_mc_socklist * mc_list;
    struct inet_cork_full cork;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct inet_sock {
    struct sock sk;
    struct ipv6_pinfo * pinet6;
    __be32 inet_saddr;
    __s16 uc_ttl;
    __u16 cmsg_flags;
    __be16 inet_sport;
    __u16 inet_id;
    struct ip_options_rcu * inet_opt;
    int rx_dst_ifindex;
    __u8 tos;
    __u8 min_ttl;
    __u8 mc_ttl;
    __u8 pmtudisc;
    __u8 recverr;
    __u8 is_icsk;
    __u8 freebind;
    __u8 hdrincl;
    __u8 mc_loop;
    __u8 transparent;
    __u8 mc_all;
    __u8 nodefrag;
    __u8 bind_address_no_port;
    __u8 defer_connect;
    __u8 rcv_tos;
    __u8 convert_csum;
    int uc_index;
    int mc_index;
    __be32 mc_addr;
    struct ip_mc_socklist * mc_list;
    struct inet_cork_full cork;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct inet_sock {
    struct sock sk;
    struct ipv6_pinfo * pinet6;
    __be32 inet_saddr;
    __s16 uc_ttl;
    __u16 cmsg_flags;
    __be16 inet_sport;
    __u16 inet_id;
    struct ip_options_rcu * inet_opt;
    int rx_dst_ifindex;
    __u8 tos;
    __u8 min_ttl;
    __u8 mc_ttl;
    __u8 pmtudisc;
    __u8 recverr;
    __u8 is_icsk;
    __u8 freebind;
    __u8 hdrincl;
    __u8 mc_loop;
    __u8 transparent;
    __u8 mc_all;
    __u8 nodefrag;
    __u8 bind_address_no_port;
    __u8 defer_connect;
    __u8 rcv_tos;
    __u8 convert_csum;
    int uc_index;
    int mc_index;
    __be32 mc_addr;
    struct ip_mc_socklist * mc_list;
    struct inet_cork_full cork;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct inet_sock {
    struct sock sk;
    struct ipv6_pinfo * pinet6;
    __be32 inet_saddr;
    __s16 uc_ttl;
    __u16 cmsg_flags;
    __be16 inet_sport;
    __u16 inet_id;
    struct ip_options_rcu * inet_opt;
    int rx_dst_ifindex;
    __u8 tos;
    __u8 min_ttl;
    __u8 mc_ttl;
    __u8 pmtudisc;
    __u8 recverr;
    __u8 is_icsk;
    __u8 freebind;
    __u8 hdrincl;
    __u8 mc_loop;
    __u8 transparent;
    __u8 mc_all;
    __u8 nodefrag;
    __u8 bind_address_no_port;
    __u8 defer_connect;
    __u8 rcv_tos;
    __u8 convert_csum;
    int uc_index;
    int mc_index;
    __be32 mc_addr;
    struct ip_mc_socklist * mc_list;
    struct inet_cork_full cork;
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
struct inet_sock {
    struct sock sk;
    struct ipv6_pinfo * pinet6;
    __be32 inet_saddr;
    __s16 uc_ttl;
    __u16 cmsg_flags;
    __be16 inet_sport;
    __u16 inet_id;
    struct ip_options_rcu * inet_opt;
    int rx_dst_ifindex;
    __u8 tos;
    __u8 min_ttl;
    __u8 mc_ttl;
    __u8 pmtudisc;
    __u8 recverr;
    __u8 is_icsk;
    __u8 freebind;
    __u8 hdrincl;
    __u8 mc_loop;
    __u8 transparent;
    __u8 mc_all;
    __u8 nodefrag;
    __u8 bind_address_no_port;
    __u8 defer_connect;
    __u8 rcv_tos;
    __u8 convert_csum;
    int uc_index;
    int mc_index;
    __be32 mc_addr;
    struct ip_mc_socklist * mc_list;
    struct inet_cork_full cork;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct inet_sock {
    struct sock sk;
    struct ipv6_pinfo * pinet6;
    __be32 inet_saddr;
    __s16 uc_ttl;
    __u16 cmsg_flags;
    __be16 inet_sport;
    __u16 inet_id;
    struct ip_options_rcu * inet_opt;
    int rx_dst_ifindex;
    __u8 tos;
    __u8 min_ttl;
    __u8 mc_ttl;
    __u8 pmtudisc;
    __u8 recverr;
    __u8 is_icsk;
    __u8 freebind;
    __u8 hdrincl;
    __u8 mc_loop;
    __u8 transparent;
    __u8 mc_all;
    __u8 nodefrag;
    __u8 bind_address_no_port;
    __u8 defer_connect;
    __u8 rcv_tos;
    __u8 convert_csum;
    int uc_index;
    int mc_index;
    __be32 mc_addr;
    struct ip_mc_socklist * mc_list;
    struct inet_cork_full cork;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct inet_sock {
    struct sock sk;
    struct ipv6_pinfo * pinet6;
    __be32 inet_saddr;
    __s16 uc_ttl;
    __u16 cmsg_flags;
    __be16 inet_sport;
    __u16 inet_id;
    struct ip_options_rcu * inet_opt;
    int rx_dst_ifindex;
    __u8 tos;
    __u8 min_ttl;
    __u8 mc_ttl;
    __u8 pmtudisc;
    __u8 recverr;
    __u8 is_icsk;
    __u8 freebind;
    __u8 hdrincl;
    __u8 mc_loop;
    __u8 transparent;
    __u8 mc_all;
    __u8 nodefrag;
    __u8 bind_address_no_port;
    __u8 defer_connect;
    __u8 rcv_tos;
    __u8 convert_csum;
    int uc_index;
    int mc_index;
    __be32 mc_addr;
    struct ip_mc_socklist * mc_list;
    struct inet_cork_full cork;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct inet_sock {
    struct sock sk;
    struct ipv6_pinfo * pinet6;
    __be32 inet_saddr;
    __s16 uc_ttl;
    __u16 cmsg_flags;
    __be16 inet_sport;
    __u16 inet_id;
    struct ip_options_rcu * inet_opt;
    int rx_dst_ifindex;
    __u8 tos;
    __u8 min_ttl;
    __u8 mc_ttl;
    __u8 pmtudisc;
    __u8 recverr;
    __u8 is_icsk;
    __u8 freebind;
    __u8 hdrincl;
    __u8 mc_loop;
    __u8 transparent;
    __u8 mc_all;
    __u8 nodefrag;
    __u8 bind_address_no_port;
    __u8 defer_connect;
    __u8 rcv_tos;
    __u8 convert_csum;
    int uc_index;
    int mc_index;
    __be32 mc_addr;
    struct ip_mc_socklist * mc_list;
    struct inet_cork_full cork;
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>__u8 defer_connect</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>__u8 recverr_rfc4884</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>int rx_dst_ifindex</code>
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct (anon) local_port_range</code>
</li>
<li>
<b>Field type changed. </b>
<code>__u16 inet_id</code> ➡️ <code>atomic_t inet_id</code>
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
<code>long unsigned int inet_flags</code>
</li>
<li>
<b>Field removed. </b>
<code>__u16 cmsg_flags</code>
</li>
<li>
<b>Field removed. </b>
<code>__u8 recverr</code>
</li>
<li>
<b>Field removed. </b>
<code>__u8 is_icsk</code>
</li>
<li>
<b>Field removed. </b>
<code>__u8 freebind</code>
</li>
<li>
<b>Field removed. </b>
<code>__u8 hdrincl</code>
</li>
<li>
<b>Field removed. </b>
<code>__u8 mc_loop</code>
</li>
<li>
<b>Field removed. </b>
<code>__u8 transparent</code>
</li>
<li>
<b>Field removed. </b>
<code>__u8 mc_all</code>
</li>
<li>
<b>Field removed. </b>
<code>__u8 nodefrag</code>
</li>
<li>
<b>Field removed. </b>
<code>__u8 bind_address_no_port</code>
</li>
<li>
<b>Field removed. </b>
<code>__u8 recverr_rfc4884</code>
</li>
<li>
<b>Field removed. </b>
<code>__u8 defer_connect</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct (anon) local_port_range</code> ➡️ <code>u32 local_port_range</code>
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
