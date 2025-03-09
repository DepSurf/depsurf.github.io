# Struct: <code>sctp_pf</code>

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
struct sctp_pf {
    void (*)(struct sctp_ulpevent *, char *, int *) event_msgname;
    void (*)(struct sk_buff *, char *, int *) skb_msgname;
    int (*)(sa_family_t, struct sctp_sock *) af_supported;
    int (*)(const union sctp_addr *, const union sctp_addr *, struct sctp_sock *) cmp_addr;
    int (*)(struct sctp_sock *, union sctp_addr *) bind_verify;
    int (*)(struct sctp_sock *, union sctp_addr *) send_verify;
    int (*)(const struct sctp_sock *, __be16 *) supported_addrs;
    struct sock * (*)(struct sock *, struct sctp_association *, bool) create_accept_sk;
    int (*)(struct sctp_sock *, union sctp_addr *) addr_to_user;
    void (*)(union sctp_addr *, struct sock *) to_sk_saddr;
    void (*)(union sctp_addr *, struct sock *) to_sk_daddr;
    void (*)(struct sock *, struct sock *) copy_ip_options;
    struct sctp_af * af;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct sctp_pf {
    void (*)(struct sctp_ulpevent *, char *, int *) event_msgname;
    void (*)(struct sk_buff *, char *, int *) skb_msgname;
    int (*)(sa_family_t, struct sctp_sock *) af_supported;
    int (*)(const union sctp_addr *, const union sctp_addr *, struct sctp_sock *) cmp_addr;
    int (*)(struct sctp_sock *, union sctp_addr *) bind_verify;
    int (*)(struct sctp_sock *, union sctp_addr *) send_verify;
    int (*)(const struct sctp_sock *, __be16 *) supported_addrs;
    struct sock * (*)(struct sock *, struct sctp_association *, bool) create_accept_sk;
    int (*)(struct sctp_sock *, union sctp_addr *) addr_to_user;
    void (*)(union sctp_addr *, struct sock *) to_sk_saddr;
    void (*)(union sctp_addr *, struct sock *) to_sk_daddr;
    void (*)(struct sock *, struct sock *) copy_ip_options;
    struct sctp_af * af;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct sctp_pf {
    void (*)(struct sctp_ulpevent *, char *, int *) event_msgname;
    void (*)(struct sk_buff *, char *, int *) skb_msgname;
    int (*)(sa_family_t, struct sctp_sock *) af_supported;
    int (*)(const union sctp_addr *, const union sctp_addr *, struct sctp_sock *) cmp_addr;
    int (*)(struct sctp_sock *, union sctp_addr *) bind_verify;
    int (*)(struct sctp_sock *, union sctp_addr *) send_verify;
    int (*)(const struct sctp_sock *, __be16 *) supported_addrs;
    struct sock * (*)(struct sock *, struct sctp_association *, bool) create_accept_sk;
    int (*)(struct sctp_sock *, union sctp_addr *) addr_to_user;
    void (*)(union sctp_addr *, struct sock *) to_sk_saddr;
    void (*)(union sctp_addr *, struct sock *) to_sk_daddr;
    void (*)(struct sock *, struct sock *) copy_ip_options;
    struct sctp_af * af;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct sctp_pf {
    void (*)(struct sctp_ulpevent *, char *, int *) event_msgname;
    void (*)(struct sk_buff *, char *, int *) skb_msgname;
    int (*)(sa_family_t, struct sctp_sock *) af_supported;
    int (*)(const union sctp_addr *, const union sctp_addr *, struct sctp_sock *) cmp_addr;
    int (*)(struct sctp_sock *, union sctp_addr *) bind_verify;
    int (*)(struct sctp_sock *, union sctp_addr *) send_verify;
    int (*)(const struct sctp_sock *, __be16 *) supported_addrs;
    struct sock * (*)(struct sock *, struct sctp_association *, bool) create_accept_sk;
    int (*)(struct sctp_sock *, union sctp_addr *) addr_to_user;
    void (*)(union sctp_addr *, struct sock *) to_sk_saddr;
    void (*)(union sctp_addr *, struct sock *) to_sk_daddr;
    void (*)(struct sock *, struct sock *) copy_ip_options;
    struct sctp_af * af;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct sctp_pf {
    void (*)(struct sctp_ulpevent *, char *, int *) event_msgname;
    void (*)(struct sk_buff *, char *, int *) skb_msgname;
    int (*)(sa_family_t, struct sctp_sock *) af_supported;
    int (*)(const union sctp_addr *, const union sctp_addr *, struct sctp_sock *) cmp_addr;
    int (*)(struct sctp_sock *, union sctp_addr *) bind_verify;
    int (*)(struct sctp_sock *, union sctp_addr *) send_verify;
    int (*)(const struct sctp_sock *, __be16 *) supported_addrs;
    struct sock * (*)(struct sock *, struct sctp_association *, bool) create_accept_sk;
    int (*)(struct sctp_sock *, union sctp_addr *) addr_to_user;
    void (*)(union sctp_addr *, struct sock *) to_sk_saddr;
    void (*)(union sctp_addr *, struct sock *) to_sk_daddr;
    void (*)(struct sock *, struct sock *) copy_ip_options;
    struct sctp_af * af;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct sctp_pf {
    void (*)(struct sctp_ulpevent *, char *, int *) event_msgname;
    void (*)(struct sk_buff *, char *, int *) skb_msgname;
    int (*)(sa_family_t, struct sctp_sock *) af_supported;
    int (*)(const union sctp_addr *, const union sctp_addr *, struct sctp_sock *) cmp_addr;
    int (*)(struct sctp_sock *, union sctp_addr *) bind_verify;
    int (*)(struct sctp_sock *, union sctp_addr *) send_verify;
    int (*)(const struct sctp_sock *, __be16 *) supported_addrs;
    struct sock * (*)(struct sock *, struct sctp_association *, bool) create_accept_sk;
    int (*)(struct sctp_sock *, union sctp_addr *) addr_to_user;
    void (*)(union sctp_addr *, struct sock *) to_sk_saddr;
    void (*)(union sctp_addr *, struct sock *) to_sk_daddr;
    void (*)(struct sock *, struct sock *) copy_ip_options;
    struct sctp_af * af;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct sctp_pf {
    void (*)(struct sctp_ulpevent *, char *, int *) event_msgname;
    void (*)(struct sk_buff *, char *, int *) skb_msgname;
    int (*)(sa_family_t, struct sctp_sock *) af_supported;
    int (*)(const union sctp_addr *, const union sctp_addr *, struct sctp_sock *) cmp_addr;
    int (*)(struct sctp_sock *, union sctp_addr *) bind_verify;
    int (*)(struct sctp_sock *, union sctp_addr *) send_verify;
    int (*)(const struct sctp_sock *, __be16 *) supported_addrs;
    struct sock * (*)(struct sock *, struct sctp_association *, bool) create_accept_sk;
    int (*)(struct sctp_sock *, union sctp_addr *) addr_to_user;
    void (*)(union sctp_addr *, struct sock *) to_sk_saddr;
    void (*)(union sctp_addr *, struct sock *) to_sk_daddr;
    void (*)(struct sock *, struct sock *) copy_ip_options;
    struct sctp_af * af;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct sctp_pf {
    void (*)(struct sctp_ulpevent *, char *, int *) event_msgname;
    void (*)(struct sk_buff *, char *, int *) skb_msgname;
    int (*)(sa_family_t, struct sctp_sock *) af_supported;
    int (*)(const union sctp_addr *, const union sctp_addr *, struct sctp_sock *) cmp_addr;
    int (*)(struct sctp_sock *, union sctp_addr *) bind_verify;
    int (*)(struct sctp_sock *, union sctp_addr *) send_verify;
    int (*)(const struct sctp_sock *, __be16 *) supported_addrs;
    struct sock * (*)(struct sock *, struct sctp_association *, bool) create_accept_sk;
    int (*)(struct sctp_sock *, union sctp_addr *) addr_to_user;
    void (*)(union sctp_addr *, struct sock *) to_sk_saddr;
    void (*)(union sctp_addr *, struct sock *) to_sk_daddr;
    void (*)(struct sock *, struct sock *) copy_ip_options;
    struct sctp_af * af;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct sctp_pf {
    void (*)(struct sctp_ulpevent *, char *, int *) event_msgname;
    void (*)(struct sk_buff *, char *, int *) skb_msgname;
    int (*)(sa_family_t, struct sctp_sock *) af_supported;
    int (*)(const union sctp_addr *, const union sctp_addr *, struct sctp_sock *) cmp_addr;
    int (*)(struct sctp_sock *, union sctp_addr *) bind_verify;
    int (*)(struct sctp_sock *, union sctp_addr *) send_verify;
    int (*)(const struct sctp_sock *, __be16 *) supported_addrs;
    struct sock * (*)(struct sock *, struct sctp_association *, bool) create_accept_sk;
    int (*)(struct sctp_sock *, union sctp_addr *) addr_to_user;
    void (*)(union sctp_addr *, struct sock *) to_sk_saddr;
    void (*)(union sctp_addr *, struct sock *) to_sk_daddr;
    void (*)(struct sock *, struct sock *) copy_ip_options;
    struct sctp_af * af;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct sctp_pf {
    void (*)(struct sctp_ulpevent *, char *, int *) event_msgname;
    void (*)(struct sk_buff *, char *, int *) skb_msgname;
    int (*)(sa_family_t, struct sctp_sock *) af_supported;
    int (*)(const union sctp_addr *, const union sctp_addr *, struct sctp_sock *) cmp_addr;
    int (*)(struct sctp_sock *, union sctp_addr *) bind_verify;
    int (*)(struct sctp_sock *, union sctp_addr *) send_verify;
    int (*)(const struct sctp_sock *, __be16 *) supported_addrs;
    struct sock * (*)(struct sock *, struct sctp_association *, bool) create_accept_sk;
    int (*)(struct sctp_sock *, union sctp_addr *) addr_to_user;
    void (*)(union sctp_addr *, struct sock *) to_sk_saddr;
    void (*)(union sctp_addr *, struct sock *) to_sk_daddr;
    void (*)(struct sock *, struct sock *) copy_ip_options;
    struct sctp_af * af;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct sctp_pf {
    void (*)(struct sctp_ulpevent *, char *, int *) event_msgname;
    void (*)(struct sk_buff *, char *, int *) skb_msgname;
    int (*)(sa_family_t, struct sctp_sock *) af_supported;
    int (*)(const union sctp_addr *, const union sctp_addr *, struct sctp_sock *) cmp_addr;
    int (*)(struct sctp_sock *, union sctp_addr *) bind_verify;
    int (*)(struct sctp_sock *, union sctp_addr *) send_verify;
    int (*)(const struct sctp_sock *, __be16 *) supported_addrs;
    struct sock * (*)(struct sock *, struct sctp_association *, bool) create_accept_sk;
    int (*)(struct sctp_sock *, union sctp_addr *) addr_to_user;
    void (*)(union sctp_addr *, struct sock *) to_sk_saddr;
    void (*)(union sctp_addr *, struct sock *) to_sk_daddr;
    void (*)(struct sock *, struct sock *) copy_ip_options;
    struct sctp_af * af;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct sctp_pf {
    void (*)(struct sctp_ulpevent *, char *, int *) event_msgname;
    void (*)(struct sk_buff *, char *, int *) skb_msgname;
    int (*)(sa_family_t, struct sctp_sock *) af_supported;
    int (*)(const union sctp_addr *, const union sctp_addr *, struct sctp_sock *) cmp_addr;
    int (*)(struct sctp_sock *, union sctp_addr *) bind_verify;
    int (*)(struct sctp_sock *, union sctp_addr *) send_verify;
    int (*)(const struct sctp_sock *, __be16 *) supported_addrs;
    struct sock * (*)(struct sock *, struct sctp_association *, bool) create_accept_sk;
    int (*)(struct sctp_sock *, union sctp_addr *) addr_to_user;
    void (*)(union sctp_addr *, struct sock *) to_sk_saddr;
    void (*)(union sctp_addr *, struct sock *) to_sk_daddr;
    void (*)(struct sock *, struct sock *) copy_ip_options;
    struct sctp_af * af;
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
struct sctp_pf {
    void (*)(struct sctp_ulpevent *, char *, int *) event_msgname;
    void (*)(struct sk_buff *, char *, int *) skb_msgname;
    int (*)(sa_family_t, struct sctp_sock *) af_supported;
    int (*)(const union sctp_addr *, const union sctp_addr *, struct sctp_sock *) cmp_addr;
    int (*)(struct sctp_sock *, union sctp_addr *) bind_verify;
    int (*)(struct sctp_sock *, union sctp_addr *) send_verify;
    int (*)(const struct sctp_sock *, __be16 *) supported_addrs;
    struct sock * (*)(struct sock *, struct sctp_association *, bool) create_accept_sk;
    int (*)(struct sctp_sock *, union sctp_addr *) addr_to_user;
    void (*)(union sctp_addr *, struct sock *) to_sk_saddr;
    void (*)(union sctp_addr *, struct sock *) to_sk_daddr;
    void (*)(struct sock *, struct sock *) copy_ip_options;
    struct sctp_af * af;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct sctp_pf {
    void (*)(struct sctp_ulpevent *, char *, int *) event_msgname;
    void (*)(struct sk_buff *, char *, int *) skb_msgname;
    int (*)(sa_family_t, struct sctp_sock *) af_supported;
    int (*)(const union sctp_addr *, const union sctp_addr *, struct sctp_sock *) cmp_addr;
    int (*)(struct sctp_sock *, union sctp_addr *) bind_verify;
    int (*)(struct sctp_sock *, union sctp_addr *) send_verify;
    int (*)(const struct sctp_sock *, __be16 *) supported_addrs;
    struct sock * (*)(struct sock *, struct sctp_association *, bool) create_accept_sk;
    int (*)(struct sctp_sock *, union sctp_addr *) addr_to_user;
    void (*)(union sctp_addr *, struct sock *) to_sk_saddr;
    void (*)(union sctp_addr *, struct sock *) to_sk_daddr;
    void (*)(struct sock *, struct sock *) copy_ip_options;
    struct sctp_af * af;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct sctp_pf {
    void (*)(struct sctp_ulpevent *, char *, int *) event_msgname;
    void (*)(struct sk_buff *, char *, int *) skb_msgname;
    int (*)(sa_family_t, struct sctp_sock *) af_supported;
    int (*)(const union sctp_addr *, const union sctp_addr *, struct sctp_sock *) cmp_addr;
    int (*)(struct sctp_sock *, union sctp_addr *) bind_verify;
    int (*)(struct sctp_sock *, union sctp_addr *) send_verify;
    int (*)(const struct sctp_sock *, __be16 *) supported_addrs;
    struct sock * (*)(struct sock *, struct sctp_association *, bool) create_accept_sk;
    int (*)(struct sctp_sock *, union sctp_addr *) addr_to_user;
    void (*)(union sctp_addr *, struct sock *) to_sk_saddr;
    void (*)(union sctp_addr *, struct sock *) to_sk_daddr;
    void (*)(struct sock *, struct sock *) copy_ip_options;
    struct sctp_af * af;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct sctp_pf {
    void (*)(struct sctp_ulpevent *, char *, int *) event_msgname;
    void (*)(struct sk_buff *, char *, int *) skb_msgname;
    int (*)(sa_family_t, struct sctp_sock *) af_supported;
    int (*)(const union sctp_addr *, const union sctp_addr *, struct sctp_sock *) cmp_addr;
    int (*)(struct sctp_sock *, union sctp_addr *) bind_verify;
    int (*)(struct sctp_sock *, union sctp_addr *) send_verify;
    int (*)(const struct sctp_sock *, __be16 *) supported_addrs;
    struct sock * (*)(struct sock *, struct sctp_association *, bool) create_accept_sk;
    int (*)(struct sctp_sock *, union sctp_addr *) addr_to_user;
    void (*)(union sctp_addr *, struct sock *) to_sk_saddr;
    void (*)(union sctp_addr *, struct sock *) to_sk_daddr;
    void (*)(struct sock *, struct sock *) copy_ip_options;
    struct sctp_af * af;
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
struct sctp_pf {
    void (*)(struct sctp_ulpevent *, char *, int *) event_msgname;
    void (*)(struct sk_buff *, char *, int *) skb_msgname;
    int (*)(sa_family_t, struct sctp_sock *) af_supported;
    int (*)(const union sctp_addr *, const union sctp_addr *, struct sctp_sock *) cmp_addr;
    int (*)(struct sctp_sock *, union sctp_addr *) bind_verify;
    int (*)(struct sctp_sock *, union sctp_addr *) send_verify;
    int (*)(const struct sctp_sock *, __be16 *) supported_addrs;
    struct sock * (*)(struct sock *, struct sctp_association *, bool) create_accept_sk;
    int (*)(struct sctp_sock *, union sctp_addr *) addr_to_user;
    void (*)(union sctp_addr *, struct sock *) to_sk_saddr;
    void (*)(union sctp_addr *, struct sock *) to_sk_daddr;
    void (*)(struct sock *, struct sock *) copy_ip_options;
    struct sctp_af * af;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct sctp_pf {
    void (*)(struct sctp_ulpevent *, char *, int *) event_msgname;
    void (*)(struct sk_buff *, char *, int *) skb_msgname;
    int (*)(sa_family_t, struct sctp_sock *) af_supported;
    int (*)(const union sctp_addr *, const union sctp_addr *, struct sctp_sock *) cmp_addr;
    int (*)(struct sctp_sock *, union sctp_addr *) bind_verify;
    int (*)(struct sctp_sock *, union sctp_addr *) send_verify;
    int (*)(const struct sctp_sock *, __be16 *) supported_addrs;
    struct sock * (*)(struct sock *, struct sctp_association *, bool) create_accept_sk;
    int (*)(struct sctp_sock *, union sctp_addr *) addr_to_user;
    void (*)(union sctp_addr *, struct sock *) to_sk_saddr;
    void (*)(union sctp_addr *, struct sock *) to_sk_daddr;
    void (*)(struct sock *, struct sock *) copy_ip_options;
    struct sctp_af * af;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct sctp_pf {
    void (*)(struct sctp_ulpevent *, char *, int *) event_msgname;
    void (*)(struct sk_buff *, char *, int *) skb_msgname;
    int (*)(sa_family_t, struct sctp_sock *) af_supported;
    int (*)(const union sctp_addr *, const union sctp_addr *, struct sctp_sock *) cmp_addr;
    int (*)(struct sctp_sock *, union sctp_addr *) bind_verify;
    int (*)(struct sctp_sock *, union sctp_addr *) send_verify;
    int (*)(const struct sctp_sock *, __be16 *) supported_addrs;
    struct sock * (*)(struct sock *, struct sctp_association *, bool) create_accept_sk;
    int (*)(struct sctp_sock *, union sctp_addr *) addr_to_user;
    void (*)(union sctp_addr *, struct sock *) to_sk_saddr;
    void (*)(union sctp_addr *, struct sock *) to_sk_daddr;
    void (*)(struct sock *, struct sock *) copy_ip_options;
    struct sctp_af * af;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct sctp_pf {
    void (*)(struct sctp_ulpevent *, char *, int *) event_msgname;
    void (*)(struct sk_buff *, char *, int *) skb_msgname;
    int (*)(sa_family_t, struct sctp_sock *) af_supported;
    int (*)(const union sctp_addr *, const union sctp_addr *, struct sctp_sock *) cmp_addr;
    int (*)(struct sctp_sock *, union sctp_addr *) bind_verify;
    int (*)(struct sctp_sock *, union sctp_addr *) send_verify;
    int (*)(const struct sctp_sock *, __be16 *) supported_addrs;
    struct sock * (*)(struct sock *, struct sctp_association *, bool) create_accept_sk;
    int (*)(struct sctp_sock *, union sctp_addr *) addr_to_user;
    void (*)(union sctp_addr *, struct sock *) to_sk_saddr;
    void (*)(union sctp_addr *, struct sock *) to_sk_daddr;
    void (*)(struct sock *, struct sock *) copy_ip_options;
    struct sctp_af * af;
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
struct sctp_pf {
    void (*)(struct sctp_ulpevent *, char *, int *) event_msgname;
    void (*)(struct sk_buff *, char *, int *) skb_msgname;
    int (*)(sa_family_t, struct sctp_sock *) af_supported;
    int (*)(const union sctp_addr *, const union sctp_addr *, struct sctp_sock *) cmp_addr;
    int (*)(struct sctp_sock *, union sctp_addr *) bind_verify;
    int (*)(struct sctp_sock *, union sctp_addr *) send_verify;
    int (*)(const struct sctp_sock *, __be16 *) supported_addrs;
    struct sock * (*)(struct sock *, struct sctp_association *, bool) create_accept_sk;
    int (*)(struct sctp_sock *, union sctp_addr *) addr_to_user;
    void (*)(union sctp_addr *, struct sock *) to_sk_saddr;
    void (*)(union sctp_addr *, struct sock *) to_sk_daddr;
    void (*)(struct sock *, struct sock *) copy_ip_options;
    struct sctp_af * af;
}
```
</details>
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
