# Struct: <code>fib_rules_ops</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct fib_rules_ops {
    int family;
    struct list_head list;
    int rule_size;
    int addr_size;
    int unresolved_rules;
    int nr_goto_rules;
    int (*)(struct fib_rule *, struct flowi *, int, struct fib_lookup_arg *) action;
    bool (*)(struct fib_rule *, struct fib_lookup_arg *) suppress;
    int (*)(struct fib_rule *, struct flowi *, int) match;
    int (*)(struct fib_rule *, struct sk_buff *, struct fib_rule_hdr *, struct nlattr * *) configure;
    int (*)(struct fib_rule *) delete;
    int (*)(struct fib_rule *, struct fib_rule_hdr *, struct nlattr * *) compare;
    int (*)(struct fib_rule *, struct sk_buff *, struct fib_rule_hdr *) fill;
    size_t (*)(struct fib_rule *) nlmsg_payload;
    void (*)(struct fib_rules_ops *) flush_cache;
    int nlgroup;
    const struct nla_policy * policy;
    struct list_head rules_list;
    struct module * owner;
    struct net * fro_net;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct fib_rules_ops {
    int family;
    struct list_head list;
    int rule_size;
    int addr_size;
    int unresolved_rules;
    int nr_goto_rules;
    int (*)(struct fib_rule *, struct flowi *, int, struct fib_lookup_arg *) action;
    bool (*)(struct fib_rule *, struct fib_lookup_arg *) suppress;
    int (*)(struct fib_rule *, struct flowi *, int) match;
    int (*)(struct fib_rule *, struct sk_buff *, struct fib_rule_hdr *, struct nlattr * *) configure;
    int (*)(struct fib_rule *) delete;
    int (*)(struct fib_rule *, struct fib_rule_hdr *, struct nlattr * *) compare;
    int (*)(struct fib_rule *, struct sk_buff *, struct fib_rule_hdr *) fill;
    size_t (*)(struct fib_rule *) nlmsg_payload;
    void (*)(struct fib_rules_ops *) flush_cache;
    int nlgroup;
    const struct nla_policy * policy;
    struct list_head rules_list;
    struct module * owner;
    struct net * fro_net;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct fib_rules_ops {
    int family;
    struct list_head list;
    int rule_size;
    int addr_size;
    int unresolved_rules;
    int nr_goto_rules;
    int (*)(struct fib_rule *, struct flowi *, int, struct fib_lookup_arg *) action;
    bool (*)(struct fib_rule *, struct fib_lookup_arg *) suppress;
    int (*)(struct fib_rule *, struct flowi *, int) match;
    int (*)(struct fib_rule *, struct sk_buff *, struct fib_rule_hdr *, struct nlattr * *) configure;
    int (*)(struct fib_rule *) delete;
    int (*)(struct fib_rule *, struct fib_rule_hdr *, struct nlattr * *) compare;
    int (*)(struct fib_rule *, struct sk_buff *, struct fib_rule_hdr *) fill;
    size_t (*)(struct fib_rule *) nlmsg_payload;
    void (*)(struct fib_rules_ops *) flush_cache;
    int nlgroup;
    const struct nla_policy * policy;
    struct list_head rules_list;
    struct module * owner;
    struct net * fro_net;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct fib_rules_ops {
    int family;
    struct list_head list;
    int rule_size;
    int addr_size;
    int unresolved_rules;
    int nr_goto_rules;
    int (*)(struct fib_rule *, struct flowi *, int, struct fib_lookup_arg *) action;
    bool (*)(struct fib_rule *, struct fib_lookup_arg *) suppress;
    int (*)(struct fib_rule *, struct flowi *, int) match;
    int (*)(struct fib_rule *, struct sk_buff *, struct fib_rule_hdr *, struct nlattr * *) configure;
    int (*)(struct fib_rule *) delete;
    int (*)(struct fib_rule *, struct fib_rule_hdr *, struct nlattr * *) compare;
    int (*)(struct fib_rule *, struct sk_buff *, struct fib_rule_hdr *) fill;
    size_t (*)(struct fib_rule *) nlmsg_payload;
    void (*)(struct fib_rules_ops *) flush_cache;
    int nlgroup;
    const struct nla_policy * policy;
    struct list_head rules_list;
    struct module * owner;
    struct net * fro_net;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct fib_rules_ops {
    int family;
    struct list_head list;
    int rule_size;
    int addr_size;
    int unresolved_rules;
    int nr_goto_rules;
    unsigned int fib_rules_seq;
    int (*)(struct fib_rule *, struct flowi *, int, struct fib_lookup_arg *) action;
    bool (*)(struct fib_rule *, struct fib_lookup_arg *) suppress;
    int (*)(struct fib_rule *, struct flowi *, int) match;
    int (*)(struct fib_rule *, struct sk_buff *, struct fib_rule_hdr *, struct nlattr * *) configure;
    int (*)(struct fib_rule *) delete;
    int (*)(struct fib_rule *, struct fib_rule_hdr *, struct nlattr * *) compare;
    int (*)(struct fib_rule *, struct sk_buff *, struct fib_rule_hdr *) fill;
    size_t (*)(struct fib_rule *) nlmsg_payload;
    void (*)(struct fib_rules_ops *) flush_cache;
    int nlgroup;
    const struct nla_policy * policy;
    struct list_head rules_list;
    struct module * owner;
    struct net * fro_net;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct fib_rules_ops {
    int family;
    struct list_head list;
    int rule_size;
    int addr_size;
    int unresolved_rules;
    int nr_goto_rules;
    unsigned int fib_rules_seq;
    int (*)(struct fib_rule *, struct flowi *, int, struct fib_lookup_arg *) action;
    bool (*)(struct fib_rule *, struct fib_lookup_arg *) suppress;
    int (*)(struct fib_rule *, struct flowi *, int) match;
    int (*)(struct fib_rule *, struct sk_buff *, struct fib_rule_hdr *, struct nlattr * *, struct netlink_ext_ack *) configure;
    int (*)(struct fib_rule *) delete;
    int (*)(struct fib_rule *, struct fib_rule_hdr *, struct nlattr * *) compare;
    int (*)(struct fib_rule *, struct sk_buff *, struct fib_rule_hdr *) fill;
    size_t (*)(struct fib_rule *) nlmsg_payload;
    void (*)(struct fib_rules_ops *) flush_cache;
    int nlgroup;
    const struct nla_policy * policy;
    struct list_head rules_list;
    struct module * owner;
    struct net * fro_net;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct fib_rules_ops {
    int family;
    struct list_head list;
    int rule_size;
    int addr_size;
    int unresolved_rules;
    int nr_goto_rules;
    unsigned int fib_rules_seq;
    int (*)(struct fib_rule *, struct flowi *, int, struct fib_lookup_arg *) action;
    bool (*)(struct fib_rule *, struct fib_lookup_arg *) suppress;
    int (*)(struct fib_rule *, struct flowi *, int) match;
    int (*)(struct fib_rule *, struct sk_buff *, struct fib_rule_hdr *, struct nlattr * *, struct netlink_ext_ack *) configure;
    int (*)(struct fib_rule *) delete;
    int (*)(struct fib_rule *, struct fib_rule_hdr *, struct nlattr * *) compare;
    int (*)(struct fib_rule *, struct sk_buff *, struct fib_rule_hdr *) fill;
    size_t (*)(struct fib_rule *) nlmsg_payload;
    void (*)(struct fib_rules_ops *) flush_cache;
    int nlgroup;
    const struct nla_policy * policy;
    struct list_head rules_list;
    struct module * owner;
    struct net * fro_net;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct fib_rules_ops {
    int family;
    struct list_head list;
    int rule_size;
    int addr_size;
    int unresolved_rules;
    int nr_goto_rules;
    unsigned int fib_rules_seq;
    int (*)(struct fib_rule *, struct flowi *, int, struct fib_lookup_arg *) action;
    bool (*)(struct fib_rule *, struct fib_lookup_arg *) suppress;
    int (*)(struct fib_rule *, struct flowi *, int) match;
    int (*)(struct fib_rule *, struct sk_buff *, struct fib_rule_hdr *, struct nlattr * *, struct netlink_ext_ack *) configure;
    int (*)(struct fib_rule *) delete;
    int (*)(struct fib_rule *, struct fib_rule_hdr *, struct nlattr * *) compare;
    int (*)(struct fib_rule *, struct sk_buff *, struct fib_rule_hdr *) fill;
    size_t (*)(struct fib_rule *) nlmsg_payload;
    void (*)(struct fib_rules_ops *) flush_cache;
    int nlgroup;
    const struct nla_policy * policy;
    struct list_head rules_list;
    struct module * owner;
    struct net * fro_net;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct fib_rules_ops {
    int family;
    struct list_head list;
    int rule_size;
    int addr_size;
    int unresolved_rules;
    int nr_goto_rules;
    unsigned int fib_rules_seq;
    int (*)(struct fib_rule *, struct flowi *, int, struct fib_lookup_arg *) action;
    bool (*)(struct fib_rule *, struct fib_lookup_arg *) suppress;
    int (*)(struct fib_rule *, struct flowi *, int) match;
    int (*)(struct fib_rule *, struct sk_buff *, struct fib_rule_hdr *, struct nlattr * *, struct netlink_ext_ack *) configure;
    int (*)(struct fib_rule *) delete;
    int (*)(struct fib_rule *, struct fib_rule_hdr *, struct nlattr * *) compare;
    int (*)(struct fib_rule *, struct sk_buff *, struct fib_rule_hdr *) fill;
    size_t (*)(struct fib_rule *) nlmsg_payload;
    void (*)(struct fib_rules_ops *) flush_cache;
    int nlgroup;
    const struct nla_policy * policy;
    struct list_head rules_list;
    struct module * owner;
    struct net * fro_net;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct fib_rules_ops {
    int family;
    struct list_head list;
    int rule_size;
    int addr_size;
    int unresolved_rules;
    int nr_goto_rules;
    unsigned int fib_rules_seq;
    int (*)(struct fib_rule *, struct flowi *, int, struct fib_lookup_arg *) action;
    bool (*)(struct fib_rule *, struct fib_lookup_arg *) suppress;
    int (*)(struct fib_rule *, struct flowi *, int) match;
    int (*)(struct fib_rule *, struct sk_buff *, struct fib_rule_hdr *, struct nlattr * *, struct netlink_ext_ack *) configure;
    int (*)(struct fib_rule *) delete;
    int (*)(struct fib_rule *, struct fib_rule_hdr *, struct nlattr * *) compare;
    int (*)(struct fib_rule *, struct sk_buff *, struct fib_rule_hdr *) fill;
    size_t (*)(struct fib_rule *) nlmsg_payload;
    void (*)(struct fib_rules_ops *) flush_cache;
    int nlgroup;
    const struct nla_policy * policy;
    struct list_head rules_list;
    struct module * owner;
    struct net * fro_net;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct fib_rules_ops {
    int family;
    struct list_head list;
    int rule_size;
    int addr_size;
    int unresolved_rules;
    int nr_goto_rules;
    unsigned int fib_rules_seq;
    int (*)(struct fib_rule *, struct flowi *, int, struct fib_lookup_arg *) action;
    bool (*)(struct fib_rule *, struct fib_lookup_arg *) suppress;
    int (*)(struct fib_rule *, struct flowi *, int) match;
    int (*)(struct fib_rule *, struct sk_buff *, struct fib_rule_hdr *, struct nlattr * *, struct netlink_ext_ack *) configure;
    int (*)(struct fib_rule *) delete;
    int (*)(struct fib_rule *, struct fib_rule_hdr *, struct nlattr * *) compare;
    int (*)(struct fib_rule *, struct sk_buff *, struct fib_rule_hdr *) fill;
    size_t (*)(struct fib_rule *) nlmsg_payload;
    void (*)(struct fib_rules_ops *) flush_cache;
    int nlgroup;
    const struct nla_policy * policy;
    struct list_head rules_list;
    struct module * owner;
    struct net * fro_net;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct fib_rules_ops {
    int family;
    struct list_head list;
    int rule_size;
    int addr_size;
    int unresolved_rules;
    int nr_goto_rules;
    unsigned int fib_rules_seq;
    int (*)(struct fib_rule *, struct flowi *, int, struct fib_lookup_arg *) action;
    bool (*)(struct fib_rule *, struct fib_lookup_arg *) suppress;
    int (*)(struct fib_rule *, struct flowi *, int) match;
    int (*)(struct fib_rule *, struct sk_buff *, struct fib_rule_hdr *, struct nlattr * *, struct netlink_ext_ack *) configure;
    int (*)(struct fib_rule *) delete;
    int (*)(struct fib_rule *, struct fib_rule_hdr *, struct nlattr * *) compare;
    int (*)(struct fib_rule *, struct sk_buff *, struct fib_rule_hdr *) fill;
    size_t (*)(struct fib_rule *) nlmsg_payload;
    void (*)(struct fib_rules_ops *) flush_cache;
    int nlgroup;
    const struct nla_policy * policy;
    struct list_head rules_list;
    struct module * owner;
    struct net * fro_net;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct fib_rules_ops {
    int family;
    struct list_head list;
    int rule_size;
    int addr_size;
    int unresolved_rules;
    int nr_goto_rules;
    unsigned int fib_rules_seq;
    int (*)(struct fib_rule *, struct flowi *, int, struct fib_lookup_arg *) action;
    bool (*)(struct fib_rule *, int, struct fib_lookup_arg *) suppress;
    int (*)(struct fib_rule *, struct flowi *, int) match;
    int (*)(struct fib_rule *, struct sk_buff *, struct fib_rule_hdr *, struct nlattr * *, struct netlink_ext_ack *) configure;
    int (*)(struct fib_rule *) delete;
    int (*)(struct fib_rule *, struct fib_rule_hdr *, struct nlattr * *) compare;
    int (*)(struct fib_rule *, struct sk_buff *, struct fib_rule_hdr *) fill;
    size_t (*)(struct fib_rule *) nlmsg_payload;
    void (*)(struct fib_rules_ops *) flush_cache;
    int nlgroup;
    const struct nla_policy * policy;
    struct list_head rules_list;
    struct module * owner;
    struct net * fro_net;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct fib_rules_ops {
    int family;
    struct list_head list;
    int rule_size;
    int addr_size;
    int unresolved_rules;
    int nr_goto_rules;
    unsigned int fib_rules_seq;
    int (*)(struct fib_rule *, struct flowi *, int, struct fib_lookup_arg *) action;
    bool (*)(struct fib_rule *, int, struct fib_lookup_arg *) suppress;
    int (*)(struct fib_rule *, struct flowi *, int) match;
    int (*)(struct fib_rule *, struct sk_buff *, struct fib_rule_hdr *, struct nlattr * *, struct netlink_ext_ack *) configure;
    int (*)(struct fib_rule *) delete;
    int (*)(struct fib_rule *, struct fib_rule_hdr *, struct nlattr * *) compare;
    int (*)(struct fib_rule *, struct sk_buff *, struct fib_rule_hdr *) fill;
    size_t (*)(struct fib_rule *) nlmsg_payload;
    void (*)(struct fib_rules_ops *) flush_cache;
    int nlgroup;
    struct list_head rules_list;
    struct module * owner;
    struct net * fro_net;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct fib_rules_ops {
    int family;
    struct list_head list;
    int rule_size;
    int addr_size;
    int unresolved_rules;
    int nr_goto_rules;
    unsigned int fib_rules_seq;
    int (*)(struct fib_rule *, struct flowi *, int, struct fib_lookup_arg *) action;
    bool (*)(struct fib_rule *, int, struct fib_lookup_arg *) suppress;
    int (*)(struct fib_rule *, struct flowi *, int) match;
    int (*)(struct fib_rule *, struct sk_buff *, struct fib_rule_hdr *, struct nlattr * *, struct netlink_ext_ack *) configure;
    int (*)(struct fib_rule *) delete;
    int (*)(struct fib_rule *, struct fib_rule_hdr *, struct nlattr * *) compare;
    int (*)(struct fib_rule *, struct sk_buff *, struct fib_rule_hdr *) fill;
    size_t (*)(struct fib_rule *) nlmsg_payload;
    void (*)(struct fib_rules_ops *) flush_cache;
    int nlgroup;
    struct list_head rules_list;
    struct module * owner;
    struct net * fro_net;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct fib_rules_ops {
    int family;
    struct list_head list;
    int rule_size;
    int addr_size;
    int unresolved_rules;
    int nr_goto_rules;
    unsigned int fib_rules_seq;
    int (*)(struct fib_rule *, struct flowi *, int, struct fib_lookup_arg *) action;
    bool (*)(struct fib_rule *, int, struct fib_lookup_arg *) suppress;
    int (*)(struct fib_rule *, struct flowi *, int) match;
    int (*)(struct fib_rule *, struct sk_buff *, struct fib_rule_hdr *, struct nlattr * *, struct netlink_ext_ack *) configure;
    int (*)(struct fib_rule *) delete;
    int (*)(struct fib_rule *, struct fib_rule_hdr *, struct nlattr * *) compare;
    int (*)(struct fib_rule *, struct sk_buff *, struct fib_rule_hdr *) fill;
    size_t (*)(struct fib_rule *) nlmsg_payload;
    void (*)(struct fib_rules_ops *) flush_cache;
    int nlgroup;
    struct list_head rules_list;
    struct module * owner;
    struct net * fro_net;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct fib_rules_ops {
    int family;
    struct list_head list;
    int rule_size;
    int addr_size;
    int unresolved_rules;
    int nr_goto_rules;
    unsigned int fib_rules_seq;
    int (*)(struct fib_rule *, struct flowi *, int, struct fib_lookup_arg *) action;
    bool (*)(struct fib_rule *, int, struct fib_lookup_arg *) suppress;
    int (*)(struct fib_rule *, struct flowi *, int) match;
    int (*)(struct fib_rule *, struct sk_buff *, struct fib_rule_hdr *, struct nlattr * *, struct netlink_ext_ack *) configure;
    int (*)(struct fib_rule *) delete;
    int (*)(struct fib_rule *, struct fib_rule_hdr *, struct nlattr * *) compare;
    int (*)(struct fib_rule *, struct sk_buff *, struct fib_rule_hdr *) fill;
    size_t (*)(struct fib_rule *) nlmsg_payload;
    void (*)(struct fib_rules_ops *) flush_cache;
    int nlgroup;
    struct list_head rules_list;
    struct module * owner;
    struct net * fro_net;
    struct callback_head rcu;
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
struct fib_rules_ops {
    int family;
    struct list_head list;
    int rule_size;
    int addr_size;
    int unresolved_rules;
    int nr_goto_rules;
    unsigned int fib_rules_seq;
    int (*)(struct fib_rule *, struct flowi *, int, struct fib_lookup_arg *) action;
    bool (*)(struct fib_rule *, struct fib_lookup_arg *) suppress;
    int (*)(struct fib_rule *, struct flowi *, int) match;
    int (*)(struct fib_rule *, struct sk_buff *, struct fib_rule_hdr *, struct nlattr * *, struct netlink_ext_ack *) configure;
    int (*)(struct fib_rule *) delete;
    int (*)(struct fib_rule *, struct fib_rule_hdr *, struct nlattr * *) compare;
    int (*)(struct fib_rule *, struct sk_buff *, struct fib_rule_hdr *) fill;
    size_t (*)(struct fib_rule *) nlmsg_payload;
    void (*)(struct fib_rules_ops *) flush_cache;
    int nlgroup;
    const struct nla_policy * policy;
    struct list_head rules_list;
    struct module * owner;
    struct net * fro_net;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct fib_rules_ops {
    int family;
    struct list_head list;
    int rule_size;
    int addr_size;
    int unresolved_rules;
    int nr_goto_rules;
    unsigned int fib_rules_seq;
    int (*)(struct fib_rule *, struct flowi *, int, struct fib_lookup_arg *) action;
    bool (*)(struct fib_rule *, struct fib_lookup_arg *) suppress;
    int (*)(struct fib_rule *, struct flowi *, int) match;
    int (*)(struct fib_rule *, struct sk_buff *, struct fib_rule_hdr *, struct nlattr * *, struct netlink_ext_ack *) configure;
    int (*)(struct fib_rule *) delete;
    int (*)(struct fib_rule *, struct fib_rule_hdr *, struct nlattr * *) compare;
    int (*)(struct fib_rule *, struct sk_buff *, struct fib_rule_hdr *) fill;
    size_t (*)(struct fib_rule *) nlmsg_payload;
    void (*)(struct fib_rules_ops *) flush_cache;
    int nlgroup;
    const struct nla_policy * policy;
    struct list_head rules_list;
    struct module * owner;
    struct net * fro_net;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct fib_rules_ops {
    int family;
    struct list_head list;
    int rule_size;
    int addr_size;
    int unresolved_rules;
    int nr_goto_rules;
    unsigned int fib_rules_seq;
    int (*)(struct fib_rule *, struct flowi *, int, struct fib_lookup_arg *) action;
    bool (*)(struct fib_rule *, struct fib_lookup_arg *) suppress;
    int (*)(struct fib_rule *, struct flowi *, int) match;
    int (*)(struct fib_rule *, struct sk_buff *, struct fib_rule_hdr *, struct nlattr * *, struct netlink_ext_ack *) configure;
    int (*)(struct fib_rule *) delete;
    int (*)(struct fib_rule *, struct fib_rule_hdr *, struct nlattr * *) compare;
    int (*)(struct fib_rule *, struct sk_buff *, struct fib_rule_hdr *) fill;
    size_t (*)(struct fib_rule *) nlmsg_payload;
    void (*)(struct fib_rules_ops *) flush_cache;
    int nlgroup;
    const struct nla_policy * policy;
    struct list_head rules_list;
    struct module * owner;
    struct net * fro_net;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct fib_rules_ops {
    int family;
    struct list_head list;
    int rule_size;
    int addr_size;
    int unresolved_rules;
    int nr_goto_rules;
    unsigned int fib_rules_seq;
    int (*)(struct fib_rule *, struct flowi *, int, struct fib_lookup_arg *) action;
    bool (*)(struct fib_rule *, struct fib_lookup_arg *) suppress;
    int (*)(struct fib_rule *, struct flowi *, int) match;
    int (*)(struct fib_rule *, struct sk_buff *, struct fib_rule_hdr *, struct nlattr * *, struct netlink_ext_ack *) configure;
    int (*)(struct fib_rule *) delete;
    int (*)(struct fib_rule *, struct fib_rule_hdr *, struct nlattr * *) compare;
    int (*)(struct fib_rule *, struct sk_buff *, struct fib_rule_hdr *) fill;
    size_t (*)(struct fib_rule *) nlmsg_payload;
    void (*)(struct fib_rules_ops *) flush_cache;
    int nlgroup;
    const struct nla_policy * policy;
    struct list_head rules_list;
    struct module * owner;
    struct net * fro_net;
    struct callback_head rcu;
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
struct fib_rules_ops {
    int family;
    struct list_head list;
    int rule_size;
    int addr_size;
    int unresolved_rules;
    int nr_goto_rules;
    unsigned int fib_rules_seq;
    int (*)(struct fib_rule *, struct flowi *, int, struct fib_lookup_arg *) action;
    bool (*)(struct fib_rule *, struct fib_lookup_arg *) suppress;
    int (*)(struct fib_rule *, struct flowi *, int) match;
    int (*)(struct fib_rule *, struct sk_buff *, struct fib_rule_hdr *, struct nlattr * *, struct netlink_ext_ack *) configure;
    int (*)(struct fib_rule *) delete;
    int (*)(struct fib_rule *, struct fib_rule_hdr *, struct nlattr * *) compare;
    int (*)(struct fib_rule *, struct sk_buff *, struct fib_rule_hdr *) fill;
    size_t (*)(struct fib_rule *) nlmsg_payload;
    void (*)(struct fib_rules_ops *) flush_cache;
    int nlgroup;
    const struct nla_policy * policy;
    struct list_head rules_list;
    struct module * owner;
    struct net * fro_net;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct fib_rules_ops {
    int family;
    struct list_head list;
    int rule_size;
    int addr_size;
    int unresolved_rules;
    int nr_goto_rules;
    unsigned int fib_rules_seq;
    int (*)(struct fib_rule *, struct flowi *, int, struct fib_lookup_arg *) action;
    bool (*)(struct fib_rule *, struct fib_lookup_arg *) suppress;
    int (*)(struct fib_rule *, struct flowi *, int) match;
    int (*)(struct fib_rule *, struct sk_buff *, struct fib_rule_hdr *, struct nlattr * *, struct netlink_ext_ack *) configure;
    int (*)(struct fib_rule *) delete;
    int (*)(struct fib_rule *, struct fib_rule_hdr *, struct nlattr * *) compare;
    int (*)(struct fib_rule *, struct sk_buff *, struct fib_rule_hdr *) fill;
    size_t (*)(struct fib_rule *) nlmsg_payload;
    void (*)(struct fib_rules_ops *) flush_cache;
    int nlgroup;
    const struct nla_policy * policy;
    struct list_head rules_list;
    struct module * owner;
    struct net * fro_net;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct fib_rules_ops {
    int family;
    struct list_head list;
    int rule_size;
    int addr_size;
    int unresolved_rules;
    int nr_goto_rules;
    unsigned int fib_rules_seq;
    int (*)(struct fib_rule *, struct flowi *, int, struct fib_lookup_arg *) action;
    bool (*)(struct fib_rule *, struct fib_lookup_arg *) suppress;
    int (*)(struct fib_rule *, struct flowi *, int) match;
    int (*)(struct fib_rule *, struct sk_buff *, struct fib_rule_hdr *, struct nlattr * *, struct netlink_ext_ack *) configure;
    int (*)(struct fib_rule *) delete;
    int (*)(struct fib_rule *, struct fib_rule_hdr *, struct nlattr * *) compare;
    int (*)(struct fib_rule *, struct sk_buff *, struct fib_rule_hdr *) fill;
    size_t (*)(struct fib_rule *) nlmsg_payload;
    void (*)(struct fib_rules_ops *) flush_cache;
    int nlgroup;
    const struct nla_policy * policy;
    struct list_head rules_list;
    struct module * owner;
    struct net * fro_net;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct fib_rules_ops {
    int family;
    struct list_head list;
    int rule_size;
    int addr_size;
    int unresolved_rules;
    int nr_goto_rules;
    unsigned int fib_rules_seq;
    int (*)(struct fib_rule *, struct flowi *, int, struct fib_lookup_arg *) action;
    bool (*)(struct fib_rule *, struct fib_lookup_arg *) suppress;
    int (*)(struct fib_rule *, struct flowi *, int) match;
    int (*)(struct fib_rule *, struct sk_buff *, struct fib_rule_hdr *, struct nlattr * *, struct netlink_ext_ack *) configure;
    int (*)(struct fib_rule *) delete;
    int (*)(struct fib_rule *, struct fib_rule_hdr *, struct nlattr * *) compare;
    int (*)(struct fib_rule *, struct sk_buff *, struct fib_rule_hdr *) fill;
    size_t (*)(struct fib_rule *) nlmsg_payload;
    void (*)(struct fib_rules_ops *) flush_cache;
    int nlgroup;
    const struct nla_policy * policy;
    struct list_head rules_list;
    struct module * owner;
    struct net * fro_net;
    struct callback_head rcu;
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
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int fib_rules_seq</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>int (*)(struct fib_rule *, struct sk_buff *, struct fib_rule_hdr *, struct nlattr * *) configure</code> ➡️ <code>int (*)(struct fib_rule *, struct sk_buff *, struct fib_rule_hdr *, struct nlattr * *, struct netlink_ext_ack *) configure</code>
</li>
</ul>
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
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>bool (*)(struct fib_rule *, struct fib_lookup_arg *) suppress</code> ➡️ <code>bool (*)(struct fib_rule *, int, struct fib_lookup_arg *) suppress</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>const struct nla_policy * policy</code>
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
