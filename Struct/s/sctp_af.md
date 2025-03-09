# Struct: <code>sctp_af</code>

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
struct sctp_af {
    int (*)(struct sk_buff *, struct sctp_transport *) sctp_xmit;
    int (*)(struct sock *, int, int, char *, unsigned int) setsockopt;
    int (*)(struct sock *, int, int, char *, int *) getsockopt;
    int (*)(struct sock *, int, int, char *, unsigned int) compat_setsockopt;
    int (*)(struct sock *, int, int, char *, int *) compat_getsockopt;
    void (*)(struct sctp_transport *, union sctp_addr *, struct flowi *, struct sock *) get_dst;
    void (*)(struct sctp_sock *, struct sctp_transport *, struct flowi *) get_saddr;
    void (*)(struct list_head *, struct net_device *) copy_addrlist;
    int (*)(const union sctp_addr *, const union sctp_addr *) cmp_addr;
    void (*)(union sctp_addr *, union sctp_addr *) addr_copy;
    void (*)(union sctp_addr *, struct sk_buff *, int) from_skb;
    void (*)(union sctp_addr *, struct sock *) from_sk;
    void (*)(union sctp_addr *, union sctp_addr_param *, __be16, int) from_addr_param;
    int (*)(const union sctp_addr *, union sctp_addr_param *) to_addr_param;
    int (*)(union sctp_addr *, struct sctp_sock *, const struct sk_buff *) addr_valid;
    enum sctp_scope (*)(union sctp_addr *) scope;
    void (*)(union sctp_addr *, __be16) inaddr_any;
    int (*)(const union sctp_addr *) is_any;
    int (*)(union sctp_addr *, struct sctp_sock *) available;
    int (*)(const struct sk_buff *) skb_iif;
    int (*)(const struct sk_buff *) is_ce;
    void (*)(struct seq_file *, union sctp_addr *) seq_dump_addr;
    void (*)(struct sock *) ecn_capable;
    __u16 net_header_len;
    int sockaddr_len;
    int (*)(struct sock *) ip_options_len;
    sa_family_t sa_family;
    struct list_head list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct sctp_af {
    int (*)(struct sk_buff *, struct sctp_transport *) sctp_xmit;
    int (*)(struct sock *, int, int, char *, unsigned int) setsockopt;
    int (*)(struct sock *, int, int, char *, int *) getsockopt;
    int (*)(struct sock *, int, int, char *, unsigned int) compat_setsockopt;
    int (*)(struct sock *, int, int, char *, int *) compat_getsockopt;
    void (*)(struct sctp_transport *, union sctp_addr *, struct flowi *, struct sock *) get_dst;
    void (*)(struct sctp_sock *, struct sctp_transport *, struct flowi *) get_saddr;
    void (*)(struct list_head *, struct net_device *) copy_addrlist;
    int (*)(const union sctp_addr *, const union sctp_addr *) cmp_addr;
    void (*)(union sctp_addr *, union sctp_addr *) addr_copy;
    void (*)(union sctp_addr *, struct sk_buff *, int) from_skb;
    void (*)(union sctp_addr *, struct sock *) from_sk;
    void (*)(union sctp_addr *, union sctp_addr_param *, __be16, int) from_addr_param;
    int (*)(const union sctp_addr *, union sctp_addr_param *) to_addr_param;
    int (*)(union sctp_addr *, struct sctp_sock *, const struct sk_buff *) addr_valid;
    enum sctp_scope (*)(union sctp_addr *) scope;
    void (*)(union sctp_addr *, __be16) inaddr_any;
    int (*)(const union sctp_addr *) is_any;
    int (*)(union sctp_addr *, struct sctp_sock *) available;
    int (*)(const struct sk_buff *) skb_iif;
    int (*)(const struct sk_buff *) is_ce;
    void (*)(struct seq_file *, union sctp_addr *) seq_dump_addr;
    void (*)(struct sock *) ecn_capable;
    __u16 net_header_len;
    int sockaddr_len;
    int (*)(struct sock *) ip_options_len;
    sa_family_t sa_family;
    struct list_head list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct sctp_af {
    int (*)(struct sk_buff *, struct sctp_transport *) sctp_xmit;
    int (*)(struct sock *, int, int, char *, unsigned int) setsockopt;
    int (*)(struct sock *, int, int, char *, int *) getsockopt;
    int (*)(struct sock *, int, int, char *, unsigned int) compat_setsockopt;
    int (*)(struct sock *, int, int, char *, int *) compat_getsockopt;
    void (*)(struct sctp_transport *, union sctp_addr *, struct flowi *, struct sock *) get_dst;
    void (*)(struct sctp_sock *, struct sctp_transport *, struct flowi *) get_saddr;
    void (*)(struct list_head *, struct net_device *) copy_addrlist;
    int (*)(const union sctp_addr *, const union sctp_addr *) cmp_addr;
    void (*)(union sctp_addr *, union sctp_addr *) addr_copy;
    void (*)(union sctp_addr *, struct sk_buff *, int) from_skb;
    void (*)(union sctp_addr *, struct sock *) from_sk;
    void (*)(union sctp_addr *, union sctp_addr_param *, __be16, int) from_addr_param;
    int (*)(const union sctp_addr *, union sctp_addr_param *) to_addr_param;
    int (*)(union sctp_addr *, struct sctp_sock *, const struct sk_buff *) addr_valid;
    enum sctp_scope (*)(union sctp_addr *) scope;
    void (*)(union sctp_addr *, __be16) inaddr_any;
    int (*)(const union sctp_addr *) is_any;
    int (*)(union sctp_addr *, struct sctp_sock *) available;
    int (*)(const struct sk_buff *) skb_iif;
    int (*)(const struct sk_buff *) is_ce;
    void (*)(struct seq_file *, union sctp_addr *) seq_dump_addr;
    void (*)(struct sock *) ecn_capable;
    __u16 net_header_len;
    int sockaddr_len;
    int (*)(struct sock *) ip_options_len;
    sa_family_t sa_family;
    struct list_head list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct sctp_af {
    int (*)(struct sk_buff *, struct sctp_transport *) sctp_xmit;
    int (*)(struct sock *, int, int, char *, unsigned int) setsockopt;
    int (*)(struct sock *, int, int, char *, int *) getsockopt;
    int (*)(struct sock *, int, int, char *, unsigned int) compat_setsockopt;
    int (*)(struct sock *, int, int, char *, int *) compat_getsockopt;
    void (*)(struct sctp_transport *, union sctp_addr *, struct flowi *, struct sock *) get_dst;
    void (*)(struct sctp_sock *, struct sctp_transport *, struct flowi *) get_saddr;
    void (*)(struct list_head *, struct net_device *) copy_addrlist;
    int (*)(const union sctp_addr *, const union sctp_addr *) cmp_addr;
    void (*)(union sctp_addr *, union sctp_addr *) addr_copy;
    void (*)(union sctp_addr *, struct sk_buff *, int) from_skb;
    void (*)(union sctp_addr *, struct sock *) from_sk;
    void (*)(union sctp_addr *, union sctp_addr_param *, __be16, int) from_addr_param;
    int (*)(const union sctp_addr *, union sctp_addr_param *) to_addr_param;
    int (*)(union sctp_addr *, struct sctp_sock *, const struct sk_buff *) addr_valid;
    enum sctp_scope (*)(union sctp_addr *) scope;
    void (*)(union sctp_addr *, __be16) inaddr_any;
    int (*)(const union sctp_addr *) is_any;
    int (*)(union sctp_addr *, struct sctp_sock *) available;
    int (*)(const struct sk_buff *) skb_iif;
    int (*)(const struct sk_buff *) is_ce;
    void (*)(struct seq_file *, union sctp_addr *) seq_dump_addr;
    void (*)(struct sock *) ecn_capable;
    __u16 net_header_len;
    int sockaddr_len;
    int (*)(struct sock *) ip_options_len;
    sa_family_t sa_family;
    struct list_head list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct sctp_af {
    int (*)(struct sk_buff *, struct sctp_transport *) sctp_xmit;
    int (*)(struct sock *, int, int, char *, unsigned int) setsockopt;
    int (*)(struct sock *, int, int, char *, int *) getsockopt;
    int (*)(struct sock *, int, int, char *, unsigned int) compat_setsockopt;
    int (*)(struct sock *, int, int, char *, int *) compat_getsockopt;
    void (*)(struct sctp_transport *, union sctp_addr *, struct flowi *, struct sock *) get_dst;
    void (*)(struct sctp_sock *, struct sctp_transport *, struct flowi *) get_saddr;
    void (*)(struct list_head *, struct net_device *) copy_addrlist;
    int (*)(const union sctp_addr *, const union sctp_addr *) cmp_addr;
    void (*)(union sctp_addr *, union sctp_addr *) addr_copy;
    void (*)(union sctp_addr *, struct sk_buff *, int) from_skb;
    void (*)(union sctp_addr *, struct sock *) from_sk;
    void (*)(union sctp_addr *, union sctp_addr_param *, __be16, int) from_addr_param;
    int (*)(const union sctp_addr *, union sctp_addr_param *) to_addr_param;
    int (*)(union sctp_addr *, struct sctp_sock *, const struct sk_buff *) addr_valid;
    enum sctp_scope (*)(union sctp_addr *) scope;
    void (*)(union sctp_addr *, __be16) inaddr_any;
    int (*)(const union sctp_addr *) is_any;
    int (*)(union sctp_addr *, struct sctp_sock *) available;
    int (*)(const struct sk_buff *) skb_iif;
    int (*)(const struct sk_buff *) is_ce;
    void (*)(struct seq_file *, union sctp_addr *) seq_dump_addr;
    void (*)(struct sock *) ecn_capable;
    __u16 net_header_len;
    int sockaddr_len;
    int (*)(struct sock *) ip_options_len;
    sa_family_t sa_family;
    struct list_head list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct sctp_af {
    int (*)(struct sk_buff *, struct sctp_transport *) sctp_xmit;
    int (*)(struct sock *, int, int, sockptr_t, unsigned int) setsockopt;
    int (*)(struct sock *, int, int, char *, int *) getsockopt;
    void (*)(struct sctp_transport *, union sctp_addr *, struct flowi *, struct sock *) get_dst;
    void (*)(struct sctp_sock *, struct sctp_transport *, struct flowi *) get_saddr;
    void (*)(struct list_head *, struct net_device *) copy_addrlist;
    int (*)(const union sctp_addr *, const union sctp_addr *) cmp_addr;
    void (*)(union sctp_addr *, union sctp_addr *) addr_copy;
    void (*)(union sctp_addr *, struct sk_buff *, int) from_skb;
    void (*)(union sctp_addr *, struct sock *) from_sk;
    void (*)(union sctp_addr *, union sctp_addr_param *, __be16, int) from_addr_param;
    int (*)(const union sctp_addr *, union sctp_addr_param *) to_addr_param;
    int (*)(union sctp_addr *, struct sctp_sock *, const struct sk_buff *) addr_valid;
    enum sctp_scope (*)(union sctp_addr *) scope;
    void (*)(union sctp_addr *, __be16) inaddr_any;
    int (*)(const union sctp_addr *) is_any;
    int (*)(union sctp_addr *, struct sctp_sock *) available;
    int (*)(const struct sk_buff *) skb_iif;
    int (*)(const struct sk_buff *) is_ce;
    void (*)(struct seq_file *, union sctp_addr *) seq_dump_addr;
    void (*)(struct sock *) ecn_capable;
    __u16 net_header_len;
    int sockaddr_len;
    int (*)(struct sock *) ip_options_len;
    sa_family_t sa_family;
    struct list_head list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct sctp_af {
    int (*)(struct sk_buff *, struct sctp_transport *) sctp_xmit;
    int (*)(struct sock *, int, int, sockptr_t, unsigned int) setsockopt;
    int (*)(struct sock *, int, int, char *, int *) getsockopt;
    void (*)(struct sctp_transport *, union sctp_addr *, struct flowi *, struct sock *) get_dst;
    void (*)(struct sctp_sock *, struct sctp_transport *, struct flowi *) get_saddr;
    void (*)(struct list_head *, struct net_device *) copy_addrlist;
    int (*)(const union sctp_addr *, const union sctp_addr *) cmp_addr;
    void (*)(union sctp_addr *, union sctp_addr *) addr_copy;
    void (*)(union sctp_addr *, struct sk_buff *, int) from_skb;
    void (*)(union sctp_addr *, struct sock *) from_sk;
    bool (*)(union sctp_addr *, union sctp_addr_param *, __be16, int) from_addr_param;
    int (*)(const union sctp_addr *, union sctp_addr_param *) to_addr_param;
    int (*)(union sctp_addr *, struct sctp_sock *, const struct sk_buff *) addr_valid;
    enum sctp_scope (*)(union sctp_addr *) scope;
    void (*)(union sctp_addr *, __be16) inaddr_any;
    int (*)(const union sctp_addr *) is_any;
    int (*)(union sctp_addr *, struct sctp_sock *) available;
    int (*)(const struct sk_buff *) skb_iif;
    int (*)(const struct sk_buff *) is_ce;
    void (*)(struct seq_file *, union sctp_addr *) seq_dump_addr;
    void (*)(struct sock *) ecn_capable;
    __u16 net_header_len;
    int sockaddr_len;
    int (*)(struct sock *) ip_options_len;
    sa_family_t sa_family;
    struct list_head list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct sctp_af {
    int (*)(struct sk_buff *, struct sctp_transport *) sctp_xmit;
    int (*)(struct sock *, int, int, sockptr_t, unsigned int) setsockopt;
    int (*)(struct sock *, int, int, char *, int *) getsockopt;
    void (*)(struct sctp_transport *, union sctp_addr *, struct flowi *, struct sock *) get_dst;
    void (*)(struct sctp_sock *, struct sctp_transport *, struct flowi *) get_saddr;
    void (*)(struct list_head *, struct net_device *) copy_addrlist;
    int (*)(const union sctp_addr *, const union sctp_addr *) cmp_addr;
    void (*)(union sctp_addr *, union sctp_addr *) addr_copy;
    void (*)(union sctp_addr *, struct sk_buff *, int) from_skb;
    void (*)(union sctp_addr *, struct sock *) from_sk;
    bool (*)(union sctp_addr *, union sctp_addr_param *, __be16, int) from_addr_param;
    int (*)(const union sctp_addr *, union sctp_addr_param *) to_addr_param;
    int (*)(union sctp_addr *, struct sctp_sock *, const struct sk_buff *) addr_valid;
    enum sctp_scope (*)(union sctp_addr *) scope;
    void (*)(union sctp_addr *, __be16) inaddr_any;
    int (*)(const union sctp_addr *) is_any;
    int (*)(union sctp_addr *, struct sctp_sock *) available;
    int (*)(const struct sk_buff *) skb_iif;
    int (*)(const struct sk_buff *) is_ce;
    void (*)(struct seq_file *, union sctp_addr *) seq_dump_addr;
    void (*)(struct sock *) ecn_capable;
    __u16 net_header_len;
    int sockaddr_len;
    int (*)(struct sock *) ip_options_len;
    sa_family_t sa_family;
    struct list_head list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct sctp_af {
    int (*)(struct sk_buff *, struct sctp_transport *) sctp_xmit;
    int (*)(struct sock *, int, int, sockptr_t, unsigned int) setsockopt;
    int (*)(struct sock *, int, int, char *, int *) getsockopt;
    void (*)(struct sctp_transport *, union sctp_addr *, struct flowi *, struct sock *) get_dst;
    void (*)(struct sctp_sock *, struct sctp_transport *, struct flowi *) get_saddr;
    void (*)(struct list_head *, struct net_device *) copy_addrlist;
    int (*)(const union sctp_addr *, const union sctp_addr *) cmp_addr;
    void (*)(union sctp_addr *, union sctp_addr *) addr_copy;
    void (*)(union sctp_addr *, struct sk_buff *, int) from_skb;
    void (*)(union sctp_addr *, struct sock *) from_sk;
    bool (*)(union sctp_addr *, union sctp_addr_param *, __be16, int) from_addr_param;
    int (*)(const union sctp_addr *, union sctp_addr_param *) to_addr_param;
    int (*)(union sctp_addr *, struct sctp_sock *, const struct sk_buff *) addr_valid;
    enum sctp_scope (*)(union sctp_addr *) scope;
    void (*)(union sctp_addr *, __be16) inaddr_any;
    int (*)(const union sctp_addr *) is_any;
    int (*)(union sctp_addr *, struct sctp_sock *) available;
    int (*)(const struct sk_buff *) skb_iif;
    int (*)(const struct sk_buff *) is_ce;
    void (*)(struct seq_file *, union sctp_addr *) seq_dump_addr;
    void (*)(struct sock *) ecn_capable;
    __u16 net_header_len;
    int sockaddr_len;
    int (*)(struct sock *) ip_options_len;
    sa_family_t sa_family;
    struct list_head list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct sctp_af {
    int (*)(struct sk_buff *, struct sctp_transport *) sctp_xmit;
    int (*)(struct sock *, int, int, sockptr_t, unsigned int) setsockopt;
    int (*)(struct sock *, int, int, char *, int *) getsockopt;
    void (*)(struct sctp_transport *, union sctp_addr *, struct flowi *, struct sock *) get_dst;
    void (*)(struct sctp_sock *, struct sctp_transport *, struct flowi *) get_saddr;
    void (*)(struct list_head *, struct net_device *) copy_addrlist;
    int (*)(const union sctp_addr *, const union sctp_addr *) cmp_addr;
    void (*)(union sctp_addr *, union sctp_addr *) addr_copy;
    void (*)(union sctp_addr *, struct sk_buff *, int) from_skb;
    void (*)(union sctp_addr *, struct sock *) from_sk;
    bool (*)(union sctp_addr *, union sctp_addr_param *, __be16, int) from_addr_param;
    int (*)(const union sctp_addr *, union sctp_addr_param *) to_addr_param;
    int (*)(union sctp_addr *, struct sctp_sock *, const struct sk_buff *) addr_valid;
    enum sctp_scope (*)(union sctp_addr *) scope;
    void (*)(union sctp_addr *, __be16) inaddr_any;
    int (*)(const union sctp_addr *) is_any;
    int (*)(union sctp_addr *, struct sctp_sock *) available;
    int (*)(const struct sk_buff *) skb_iif;
    int (*)(const struct sk_buff *) skb_sdif;
    int (*)(const struct sk_buff *) is_ce;
    void (*)(struct seq_file *, union sctp_addr *) seq_dump_addr;
    void (*)(struct sock *) ecn_capable;
    __u16 net_header_len;
    int sockaddr_len;
    int (*)(struct sock *) ip_options_len;
    sa_family_t sa_family;
    struct list_head list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct sctp_af {
    int (*)(struct sk_buff *, struct sctp_transport *) sctp_xmit;
    int (*)(struct sock *, int, int, sockptr_t, unsigned int) setsockopt;
    int (*)(struct sock *, int, int, char *, int *) getsockopt;
    void (*)(struct sctp_transport *, union sctp_addr *, struct flowi *, struct sock *) get_dst;
    void (*)(struct sctp_sock *, struct sctp_transport *, struct flowi *) get_saddr;
    void (*)(struct list_head *, struct net_device *) copy_addrlist;
    int (*)(const union sctp_addr *, const union sctp_addr *) cmp_addr;
    void (*)(union sctp_addr *, union sctp_addr *) addr_copy;
    void (*)(union sctp_addr *, struct sk_buff *, int) from_skb;
    void (*)(union sctp_addr *, struct sock *) from_sk;
    bool (*)(union sctp_addr *, union sctp_addr_param *, __be16, int) from_addr_param;
    int (*)(const union sctp_addr *, union sctp_addr_param *) to_addr_param;
    int (*)(union sctp_addr *, struct sctp_sock *, const struct sk_buff *) addr_valid;
    enum sctp_scope (*)(union sctp_addr *) scope;
    void (*)(union sctp_addr *, __be16) inaddr_any;
    int (*)(const union sctp_addr *) is_any;
    int (*)(union sctp_addr *, struct sctp_sock *) available;
    int (*)(const struct sk_buff *) skb_iif;
    int (*)(const struct sk_buff *) skb_sdif;
    int (*)(const struct sk_buff *) is_ce;
    void (*)(struct seq_file *, union sctp_addr *) seq_dump_addr;
    void (*)(struct sock *) ecn_capable;
    __u16 net_header_len;
    int sockaddr_len;
    int (*)(struct sock *) ip_options_len;
    sa_family_t sa_family;
    struct list_head list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct sctp_af {
    int (*)(struct sk_buff *, struct sctp_transport *) sctp_xmit;
    int (*)(struct sock *, int, int, sockptr_t, unsigned int) setsockopt;
    int (*)(struct sock *, int, int, char *, int *) getsockopt;
    void (*)(struct sctp_transport *, union sctp_addr *, struct flowi *, struct sock *) get_dst;
    void (*)(struct sctp_sock *, struct sctp_transport *, struct flowi *) get_saddr;
    void (*)(struct list_head *, struct net_device *) copy_addrlist;
    int (*)(const union sctp_addr *, const union sctp_addr *) cmp_addr;
    void (*)(union sctp_addr *, union sctp_addr *) addr_copy;
    void (*)(union sctp_addr *, struct sk_buff *, int) from_skb;
    void (*)(union sctp_addr *, struct sock *) from_sk;
    bool (*)(union sctp_addr *, union sctp_addr_param *, __be16, int) from_addr_param;
    int (*)(const union sctp_addr *, union sctp_addr_param *) to_addr_param;
    int (*)(union sctp_addr *, struct sctp_sock *, const struct sk_buff *) addr_valid;
    enum sctp_scope (*)(union sctp_addr *) scope;
    void (*)(union sctp_addr *, __be16) inaddr_any;
    int (*)(const union sctp_addr *) is_any;
    int (*)(union sctp_addr *, struct sctp_sock *) available;
    int (*)(const struct sk_buff *) skb_iif;
    int (*)(const struct sk_buff *) skb_sdif;
    int (*)(const struct sk_buff *) is_ce;
    void (*)(struct seq_file *, union sctp_addr *) seq_dump_addr;
    void (*)(struct sock *) ecn_capable;
    __u16 net_header_len;
    int sockaddr_len;
    int (*)(struct sock *) ip_options_len;
    sa_family_t sa_family;
    struct list_head list;
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
struct sctp_af {
    int (*)(struct sk_buff *, struct sctp_transport *) sctp_xmit;
    int (*)(struct sock *, int, int, char *, unsigned int) setsockopt;
    int (*)(struct sock *, int, int, char *, int *) getsockopt;
    int (*)(struct sock *, int, int, char *, unsigned int) compat_setsockopt;
    int (*)(struct sock *, int, int, char *, int *) compat_getsockopt;
    void (*)(struct sctp_transport *, union sctp_addr *, struct flowi *, struct sock *) get_dst;
    void (*)(struct sctp_sock *, struct sctp_transport *, struct flowi *) get_saddr;
    void (*)(struct list_head *, struct net_device *) copy_addrlist;
    int (*)(const union sctp_addr *, const union sctp_addr *) cmp_addr;
    void (*)(union sctp_addr *, union sctp_addr *) addr_copy;
    void (*)(union sctp_addr *, struct sk_buff *, int) from_skb;
    void (*)(union sctp_addr *, struct sock *) from_sk;
    void (*)(union sctp_addr *, union sctp_addr_param *, __be16, int) from_addr_param;
    int (*)(const union sctp_addr *, union sctp_addr_param *) to_addr_param;
    int (*)(union sctp_addr *, struct sctp_sock *, const struct sk_buff *) addr_valid;
    enum sctp_scope (*)(union sctp_addr *) scope;
    void (*)(union sctp_addr *, __be16) inaddr_any;
    int (*)(const union sctp_addr *) is_any;
    int (*)(union sctp_addr *, struct sctp_sock *) available;
    int (*)(const struct sk_buff *) skb_iif;
    int (*)(const struct sk_buff *) is_ce;
    void (*)(struct seq_file *, union sctp_addr *) seq_dump_addr;
    void (*)(struct sock *) ecn_capable;
    __u16 net_header_len;
    int sockaddr_len;
    int (*)(struct sock *) ip_options_len;
    sa_family_t sa_family;
    struct list_head list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct sctp_af {
    int (*)(struct sk_buff *, struct sctp_transport *) sctp_xmit;
    int (*)(struct sock *, int, int, char *, unsigned int) setsockopt;
    int (*)(struct sock *, int, int, char *, int *) getsockopt;
    int (*)(struct sock *, int, int, char *, unsigned int) compat_setsockopt;
    int (*)(struct sock *, int, int, char *, int *) compat_getsockopt;
    void (*)(struct sctp_transport *, union sctp_addr *, struct flowi *, struct sock *) get_dst;
    void (*)(struct sctp_sock *, struct sctp_transport *, struct flowi *) get_saddr;
    void (*)(struct list_head *, struct net_device *) copy_addrlist;
    int (*)(const union sctp_addr *, const union sctp_addr *) cmp_addr;
    void (*)(union sctp_addr *, union sctp_addr *) addr_copy;
    void (*)(union sctp_addr *, struct sk_buff *, int) from_skb;
    void (*)(union sctp_addr *, struct sock *) from_sk;
    void (*)(union sctp_addr *, union sctp_addr_param *, __be16, int) from_addr_param;
    int (*)(const union sctp_addr *, union sctp_addr_param *) to_addr_param;
    int (*)(union sctp_addr *, struct sctp_sock *, const struct sk_buff *) addr_valid;
    enum sctp_scope (*)(union sctp_addr *) scope;
    void (*)(union sctp_addr *, __be16) inaddr_any;
    int (*)(const union sctp_addr *) is_any;
    int (*)(union sctp_addr *, struct sctp_sock *) available;
    int (*)(const struct sk_buff *) skb_iif;
    int (*)(const struct sk_buff *) is_ce;
    void (*)(struct seq_file *, union sctp_addr *) seq_dump_addr;
    void (*)(struct sock *) ecn_capable;
    __u16 net_header_len;
    int sockaddr_len;
    int (*)(struct sock *) ip_options_len;
    sa_family_t sa_family;
    struct list_head list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct sctp_af {
    int (*)(struct sk_buff *, struct sctp_transport *) sctp_xmit;
    int (*)(struct sock *, int, int, char *, unsigned int) setsockopt;
    int (*)(struct sock *, int, int, char *, int *) getsockopt;
    int (*)(struct sock *, int, int, char *, unsigned int) compat_setsockopt;
    int (*)(struct sock *, int, int, char *, int *) compat_getsockopt;
    void (*)(struct sctp_transport *, union sctp_addr *, struct flowi *, struct sock *) get_dst;
    void (*)(struct sctp_sock *, struct sctp_transport *, struct flowi *) get_saddr;
    void (*)(struct list_head *, struct net_device *) copy_addrlist;
    int (*)(const union sctp_addr *, const union sctp_addr *) cmp_addr;
    void (*)(union sctp_addr *, union sctp_addr *) addr_copy;
    void (*)(union sctp_addr *, struct sk_buff *, int) from_skb;
    void (*)(union sctp_addr *, struct sock *) from_sk;
    void (*)(union sctp_addr *, union sctp_addr_param *, __be16, int) from_addr_param;
    int (*)(const union sctp_addr *, union sctp_addr_param *) to_addr_param;
    int (*)(union sctp_addr *, struct sctp_sock *, const struct sk_buff *) addr_valid;
    enum sctp_scope (*)(union sctp_addr *) scope;
    void (*)(union sctp_addr *, __be16) inaddr_any;
    int (*)(const union sctp_addr *) is_any;
    int (*)(union sctp_addr *, struct sctp_sock *) available;
    int (*)(const struct sk_buff *) skb_iif;
    int (*)(const struct sk_buff *) is_ce;
    void (*)(struct seq_file *, union sctp_addr *) seq_dump_addr;
    void (*)(struct sock *) ecn_capable;
    __u16 net_header_len;
    int sockaddr_len;
    int (*)(struct sock *) ip_options_len;
    sa_family_t sa_family;
    struct list_head list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct sctp_af {
    int (*)(struct sk_buff *, struct sctp_transport *) sctp_xmit;
    int (*)(struct sock *, int, int, char *, unsigned int) setsockopt;
    int (*)(struct sock *, int, int, char *, int *) getsockopt;
    int (*)(struct sock *, int, int, char *, unsigned int) compat_setsockopt;
    int (*)(struct sock *, int, int, char *, int *) compat_getsockopt;
    void (*)(struct sctp_transport *, union sctp_addr *, struct flowi *, struct sock *) get_dst;
    void (*)(struct sctp_sock *, struct sctp_transport *, struct flowi *) get_saddr;
    void (*)(struct list_head *, struct net_device *) copy_addrlist;
    int (*)(const union sctp_addr *, const union sctp_addr *) cmp_addr;
    void (*)(union sctp_addr *, union sctp_addr *) addr_copy;
    void (*)(union sctp_addr *, struct sk_buff *, int) from_skb;
    void (*)(union sctp_addr *, struct sock *) from_sk;
    void (*)(union sctp_addr *, union sctp_addr_param *, __be16, int) from_addr_param;
    int (*)(const union sctp_addr *, union sctp_addr_param *) to_addr_param;
    int (*)(union sctp_addr *, struct sctp_sock *, const struct sk_buff *) addr_valid;
    enum sctp_scope (*)(union sctp_addr *) scope;
    void (*)(union sctp_addr *, __be16) inaddr_any;
    int (*)(const union sctp_addr *) is_any;
    int (*)(union sctp_addr *, struct sctp_sock *) available;
    int (*)(const struct sk_buff *) skb_iif;
    int (*)(const struct sk_buff *) is_ce;
    void (*)(struct seq_file *, union sctp_addr *) seq_dump_addr;
    void (*)(struct sock *) ecn_capable;
    __u16 net_header_len;
    int sockaddr_len;
    int (*)(struct sock *) ip_options_len;
    sa_family_t sa_family;
    struct list_head list;
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
struct sctp_af {
    int (*)(struct sk_buff *, struct sctp_transport *) sctp_xmit;
    int (*)(struct sock *, int, int, char *, unsigned int) setsockopt;
    int (*)(struct sock *, int, int, char *, int *) getsockopt;
    int (*)(struct sock *, int, int, char *, unsigned int) compat_setsockopt;
    int (*)(struct sock *, int, int, char *, int *) compat_getsockopt;
    void (*)(struct sctp_transport *, union sctp_addr *, struct flowi *, struct sock *) get_dst;
    void (*)(struct sctp_sock *, struct sctp_transport *, struct flowi *) get_saddr;
    void (*)(struct list_head *, struct net_device *) copy_addrlist;
    int (*)(const union sctp_addr *, const union sctp_addr *) cmp_addr;
    void (*)(union sctp_addr *, union sctp_addr *) addr_copy;
    void (*)(union sctp_addr *, struct sk_buff *, int) from_skb;
    void (*)(union sctp_addr *, struct sock *) from_sk;
    void (*)(union sctp_addr *, union sctp_addr_param *, __be16, int) from_addr_param;
    int (*)(const union sctp_addr *, union sctp_addr_param *) to_addr_param;
    int (*)(union sctp_addr *, struct sctp_sock *, const struct sk_buff *) addr_valid;
    enum sctp_scope (*)(union sctp_addr *) scope;
    void (*)(union sctp_addr *, __be16) inaddr_any;
    int (*)(const union sctp_addr *) is_any;
    int (*)(union sctp_addr *, struct sctp_sock *) available;
    int (*)(const struct sk_buff *) skb_iif;
    int (*)(const struct sk_buff *) is_ce;
    void (*)(struct seq_file *, union sctp_addr *) seq_dump_addr;
    void (*)(struct sock *) ecn_capable;
    __u16 net_header_len;
    int sockaddr_len;
    int (*)(struct sock *) ip_options_len;
    sa_family_t sa_family;
    struct list_head list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct sctp_af {
    int (*)(struct sk_buff *, struct sctp_transport *) sctp_xmit;
    int (*)(struct sock *, int, int, char *, unsigned int) setsockopt;
    int (*)(struct sock *, int, int, char *, int *) getsockopt;
    int (*)(struct sock *, int, int, char *, unsigned int) compat_setsockopt;
    int (*)(struct sock *, int, int, char *, int *) compat_getsockopt;
    void (*)(struct sctp_transport *, union sctp_addr *, struct flowi *, struct sock *) get_dst;
    void (*)(struct sctp_sock *, struct sctp_transport *, struct flowi *) get_saddr;
    void (*)(struct list_head *, struct net_device *) copy_addrlist;
    int (*)(const union sctp_addr *, const union sctp_addr *) cmp_addr;
    void (*)(union sctp_addr *, union sctp_addr *) addr_copy;
    void (*)(union sctp_addr *, struct sk_buff *, int) from_skb;
    void (*)(union sctp_addr *, struct sock *) from_sk;
    void (*)(union sctp_addr *, union sctp_addr_param *, __be16, int) from_addr_param;
    int (*)(const union sctp_addr *, union sctp_addr_param *) to_addr_param;
    int (*)(union sctp_addr *, struct sctp_sock *, const struct sk_buff *) addr_valid;
    enum sctp_scope (*)(union sctp_addr *) scope;
    void (*)(union sctp_addr *, __be16) inaddr_any;
    int (*)(const union sctp_addr *) is_any;
    int (*)(union sctp_addr *, struct sctp_sock *) available;
    int (*)(const struct sk_buff *) skb_iif;
    int (*)(const struct sk_buff *) is_ce;
    void (*)(struct seq_file *, union sctp_addr *) seq_dump_addr;
    void (*)(struct sock *) ecn_capable;
    __u16 net_header_len;
    int sockaddr_len;
    int (*)(struct sock *) ip_options_len;
    sa_family_t sa_family;
    struct list_head list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct sctp_af {
    int (*)(struct sk_buff *, struct sctp_transport *) sctp_xmit;
    int (*)(struct sock *, int, int, char *, unsigned int) setsockopt;
    int (*)(struct sock *, int, int, char *, int *) getsockopt;
    int (*)(struct sock *, int, int, char *, unsigned int) compat_setsockopt;
    int (*)(struct sock *, int, int, char *, int *) compat_getsockopt;
    void (*)(struct sctp_transport *, union sctp_addr *, struct flowi *, struct sock *) get_dst;
    void (*)(struct sctp_sock *, struct sctp_transport *, struct flowi *) get_saddr;
    void (*)(struct list_head *, struct net_device *) copy_addrlist;
    int (*)(const union sctp_addr *, const union sctp_addr *) cmp_addr;
    void (*)(union sctp_addr *, union sctp_addr *) addr_copy;
    void (*)(union sctp_addr *, struct sk_buff *, int) from_skb;
    void (*)(union sctp_addr *, struct sock *) from_sk;
    void (*)(union sctp_addr *, union sctp_addr_param *, __be16, int) from_addr_param;
    int (*)(const union sctp_addr *, union sctp_addr_param *) to_addr_param;
    int (*)(union sctp_addr *, struct sctp_sock *, const struct sk_buff *) addr_valid;
    enum sctp_scope (*)(union sctp_addr *) scope;
    void (*)(union sctp_addr *, __be16) inaddr_any;
    int (*)(const union sctp_addr *) is_any;
    int (*)(union sctp_addr *, struct sctp_sock *) available;
    int (*)(const struct sk_buff *) skb_iif;
    int (*)(const struct sk_buff *) is_ce;
    void (*)(struct seq_file *, union sctp_addr *) seq_dump_addr;
    void (*)(struct sock *) ecn_capable;
    __u16 net_header_len;
    int sockaddr_len;
    int (*)(struct sock *) ip_options_len;
    sa_family_t sa_family;
    struct list_head list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct sctp_af {
    int (*)(struct sk_buff *, struct sctp_transport *) sctp_xmit;
    int (*)(struct sock *, int, int, char *, unsigned int) setsockopt;
    int (*)(struct sock *, int, int, char *, int *) getsockopt;
    int (*)(struct sock *, int, int, char *, unsigned int) compat_setsockopt;
    int (*)(struct sock *, int, int, char *, int *) compat_getsockopt;
    void (*)(struct sctp_transport *, union sctp_addr *, struct flowi *, struct sock *) get_dst;
    void (*)(struct sctp_sock *, struct sctp_transport *, struct flowi *) get_saddr;
    void (*)(struct list_head *, struct net_device *) copy_addrlist;
    int (*)(const union sctp_addr *, const union sctp_addr *) cmp_addr;
    void (*)(union sctp_addr *, union sctp_addr *) addr_copy;
    void (*)(union sctp_addr *, struct sk_buff *, int) from_skb;
    void (*)(union sctp_addr *, struct sock *) from_sk;
    void (*)(union sctp_addr *, union sctp_addr_param *, __be16, int) from_addr_param;
    int (*)(const union sctp_addr *, union sctp_addr_param *) to_addr_param;
    int (*)(union sctp_addr *, struct sctp_sock *, const struct sk_buff *) addr_valid;
    enum sctp_scope (*)(union sctp_addr *) scope;
    void (*)(union sctp_addr *, __be16) inaddr_any;
    int (*)(const union sctp_addr *) is_any;
    int (*)(union sctp_addr *, struct sctp_sock *) available;
    int (*)(const struct sk_buff *) skb_iif;
    int (*)(const struct sk_buff *) is_ce;
    void (*)(struct seq_file *, union sctp_addr *) seq_dump_addr;
    void (*)(struct sock *) ecn_capable;
    __u16 net_header_len;
    int sockaddr_len;
    int (*)(struct sock *) ip_options_len;
    sa_family_t sa_family;
    struct list_head list;
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
struct sctp_af {
    int (*)(struct sk_buff *, struct sctp_transport *) sctp_xmit;
    int (*)(struct sock *, int, int, char *, unsigned int) setsockopt;
    int (*)(struct sock *, int, int, char *, int *) getsockopt;
    int (*)(struct sock *, int, int, char *, unsigned int) compat_setsockopt;
    int (*)(struct sock *, int, int, char *, int *) compat_getsockopt;
    void (*)(struct sctp_transport *, union sctp_addr *, struct flowi *, struct sock *) get_dst;
    void (*)(struct sctp_sock *, struct sctp_transport *, struct flowi *) get_saddr;
    void (*)(struct list_head *, struct net_device *) copy_addrlist;
    int (*)(const union sctp_addr *, const union sctp_addr *) cmp_addr;
    void (*)(union sctp_addr *, union sctp_addr *) addr_copy;
    void (*)(union sctp_addr *, struct sk_buff *, int) from_skb;
    void (*)(union sctp_addr *, struct sock *) from_sk;
    void (*)(union sctp_addr *, union sctp_addr_param *, __be16, int) from_addr_param;
    int (*)(const union sctp_addr *, union sctp_addr_param *) to_addr_param;
    int (*)(union sctp_addr *, struct sctp_sock *, const struct sk_buff *) addr_valid;
    enum sctp_scope (*)(union sctp_addr *) scope;
    void (*)(union sctp_addr *, __be16) inaddr_any;
    int (*)(const union sctp_addr *) is_any;
    int (*)(union sctp_addr *, struct sctp_sock *) available;
    int (*)(const struct sk_buff *) skb_iif;
    int (*)(const struct sk_buff *) is_ce;
    void (*)(struct seq_file *, union sctp_addr *) seq_dump_addr;
    void (*)(struct sock *) ecn_capable;
    __u16 net_header_len;
    int sockaddr_len;
    int (*)(struct sock *) ip_options_len;
    sa_family_t sa_family;
    struct list_head list;
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>int (*)(struct sock *, int, int, char *, unsigned int) compat_setsockopt</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct sock *, int, int, char *, int *) compat_getsockopt</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct sock *, int, int, char *, unsigned int) setsockopt</code> ➡️ <code>int (*)(struct sock *, int, int, sockptr_t, unsigned int) setsockopt</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>void (*)(union sctp_addr *, union sctp_addr_param *, __be16, int) from_addr_param</code> ➡️ <code>bool (*)(union sctp_addr *, union sctp_addr_param *, __be16, int) from_addr_param</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(const struct sk_buff *) skb_sdif</code>
</li>
</ul>
</details>
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
