# Struct: <code>dsa_device_ops</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct dsa_device_ops {
    struct sk_buff * (*)(struct sk_buff *, struct net_device *) xmit;
    struct sk_buff * (*)(struct sk_buff *, struct net_device *, struct packet_type *) rcv;
    int (*)(const struct sk_buff *, __be16 *, int *) flow_dissect;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct dsa_device_ops {
    struct sk_buff * (*)(struct sk_buff *, struct net_device *) xmit;
    struct sk_buff * (*)(struct sk_buff *, struct net_device *, struct packet_type *) rcv;
    int (*)(const struct sk_buff *, __be16 *, int *) flow_dissect;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct dsa_device_ops {
    struct sk_buff * (*)(struct sk_buff *, struct net_device *) xmit;
    struct sk_buff * (*)(struct sk_buff *, struct net_device *, struct packet_type *) rcv;
    int (*)(const struct sk_buff *, __be16 *, int *) flow_dissect;
    unsigned int overhead;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct dsa_device_ops {
    struct sk_buff * (*)(struct sk_buff *, struct net_device *) xmit;
    struct sk_buff * (*)(struct sk_buff *, struct net_device *, struct packet_type *) rcv;
    int (*)(const struct sk_buff *, __be16 *, int *) flow_dissect;
    bool (*)(const struct sk_buff *, struct net_device *) filter;
    unsigned int overhead;
    const char * name;
    enum dsa_tag_protocol proto;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct dsa_device_ops {
    struct sk_buff * (*)(struct sk_buff *, struct net_device *) xmit;
    struct sk_buff * (*)(struct sk_buff *, struct net_device *, struct packet_type *) rcv;
    int (*)(const struct sk_buff *, __be16 *, int *) flow_dissect;
    bool (*)(const struct sk_buff *, struct net_device *) filter;
    unsigned int overhead;
    const char * name;
    enum dsa_tag_protocol proto;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct dsa_device_ops {
    struct sk_buff * (*)(struct sk_buff *, struct net_device *) xmit;
    struct sk_buff * (*)(struct sk_buff *, struct net_device *, struct packet_type *) rcv;
    int (*)(const struct sk_buff *, __be16 *, int *) flow_dissect;
    bool (*)(const struct sk_buff *, struct net_device *) filter;
    unsigned int overhead;
    const char * name;
    enum dsa_tag_protocol proto;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct dsa_device_ops {
    struct sk_buff * (*)(struct sk_buff *, struct net_device *) xmit;
    struct sk_buff * (*)(struct sk_buff *, struct net_device *, struct packet_type *) rcv;
    void (*)(const struct sk_buff *, __be16 *, int *) flow_dissect;
    bool (*)(const struct sk_buff *, struct net_device *) filter;
    unsigned int overhead;
    const char * name;
    enum dsa_tag_protocol proto;
    bool promisc_on_master;
    bool tail_tag;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct dsa_device_ops {
    struct sk_buff * (*)(struct sk_buff *, struct net_device *) xmit;
    struct sk_buff * (*)(struct sk_buff *, struct net_device *, struct packet_type *) rcv;
    void (*)(const struct sk_buff *, __be16 *, int *) flow_dissect;
    bool (*)(const struct sk_buff *, struct net_device *) filter;
    unsigned int overhead;
    const char * name;
    enum dsa_tag_protocol proto;
    bool promisc_on_master;
    bool tail_tag;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct dsa_device_ops {
    struct sk_buff * (*)(struct sk_buff *, struct net_device *) xmit;
    struct sk_buff * (*)(struct sk_buff *, struct net_device *) rcv;
    void (*)(const struct sk_buff *, __be16 *, int *) flow_dissect;
    unsigned int needed_headroom;
    unsigned int needed_tailroom;
    const char * name;
    enum dsa_tag_protocol proto;
    bool promisc_on_master;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct dsa_device_ops {
    struct sk_buff * (*)(struct sk_buff *, struct net_device *) xmit;
    struct sk_buff * (*)(struct sk_buff *, struct net_device *) rcv;
    void (*)(const struct sk_buff *, __be16 *, int *) flow_dissect;
    int (*)(struct dsa_switch *) connect;
    void (*)(struct dsa_switch *) disconnect;
    unsigned int needed_headroom;
    unsigned int needed_tailroom;
    const char * name;
    enum dsa_tag_protocol proto;
    bool promisc_on_master;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct dsa_device_ops {
    struct sk_buff * (*)(struct sk_buff *, struct net_device *) xmit;
    struct sk_buff * (*)(struct sk_buff *, struct net_device *) rcv;
    void (*)(const struct sk_buff *, __be16 *, int *) flow_dissect;
    int (*)(struct dsa_switch *) connect;
    void (*)(struct dsa_switch *) disconnect;
    unsigned int needed_headroom;
    unsigned int needed_tailroom;
    const char * name;
    enum dsa_tag_protocol proto;
    bool promisc_on_master;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct dsa_device_ops {
    struct sk_buff * (*)(struct sk_buff *, struct net_device *) xmit;
    struct sk_buff * (*)(struct sk_buff *, struct net_device *) rcv;
    void (*)(const struct sk_buff *, __be16 *, int *) flow_dissect;
    int (*)(struct dsa_switch *) connect;
    void (*)(struct dsa_switch *) disconnect;
    unsigned int needed_headroom;
    unsigned int needed_tailroom;
    const char * name;
    enum dsa_tag_protocol proto;
    bool promisc_on_master;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct dsa_device_ops {
    struct sk_buff * (*)(struct sk_buff *, struct net_device *) xmit;
    struct sk_buff * (*)(struct sk_buff *, struct net_device *) rcv;
    void (*)(const struct sk_buff *, __be16 *, int *) flow_dissect;
    int (*)(struct dsa_switch *) connect;
    void (*)(struct dsa_switch *) disconnect;
    unsigned int needed_headroom;
    unsigned int needed_tailroom;
    const char * name;
    enum dsa_tag_protocol proto;
    bool promisc_on_conduit;
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
struct dsa_device_ops {
    struct sk_buff * (*)(struct sk_buff *, struct net_device *) xmit;
    struct sk_buff * (*)(struct sk_buff *, struct net_device *, struct packet_type *) rcv;
    int (*)(const struct sk_buff *, __be16 *, int *) flow_dissect;
    bool (*)(const struct sk_buff *, struct net_device *) filter;
    unsigned int overhead;
    const char * name;
    enum dsa_tag_protocol proto;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct dsa_device_ops {
    struct sk_buff * (*)(struct sk_buff *, struct net_device *) xmit;
    struct sk_buff * (*)(struct sk_buff *, struct net_device *, struct packet_type *) rcv;
    int (*)(const struct sk_buff *, __be16 *, int *) flow_dissect;
    bool (*)(const struct sk_buff *, struct net_device *) filter;
    unsigned int overhead;
    const char * name;
    enum dsa_tag_protocol proto;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct dsa_device_ops {
    struct sk_buff * (*)(struct sk_buff *, struct net_device *) xmit;
    struct sk_buff * (*)(struct sk_buff *, struct net_device *, struct packet_type *) rcv;
    int (*)(const struct sk_buff *, __be16 *, int *) flow_dissect;
    bool (*)(const struct sk_buff *, struct net_device *) filter;
    unsigned int overhead;
    const char * name;
    enum dsa_tag_protocol proto;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct dsa_device_ops {
    struct sk_buff * (*)(struct sk_buff *, struct net_device *) xmit;
    struct sk_buff * (*)(struct sk_buff *, struct net_device *, struct packet_type *) rcv;
    int (*)(const struct sk_buff *, __be16 *, int *) flow_dissect;
    bool (*)(const struct sk_buff *, struct net_device *) filter;
    unsigned int overhead;
    const char * name;
    enum dsa_tag_protocol proto;
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
struct dsa_device_ops {
    struct sk_buff * (*)(struct sk_buff *, struct net_device *) xmit;
    struct sk_buff * (*)(struct sk_buff *, struct net_device *, struct packet_type *) rcv;
    int (*)(const struct sk_buff *, __be16 *, int *) flow_dissect;
    bool (*)(const struct sk_buff *, struct net_device *) filter;
    unsigned int overhead;
    const char * name;
    enum dsa_tag_protocol proto;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct dsa_device_ops {
    struct sk_buff * (*)(struct sk_buff *, struct net_device *) xmit;
    struct sk_buff * (*)(struct sk_buff *, struct net_device *, struct packet_type *) rcv;
    int (*)(const struct sk_buff *, __be16 *, int *) flow_dissect;
    bool (*)(const struct sk_buff *, struct net_device *) filter;
    unsigned int overhead;
    const char * name;
    enum dsa_tag_protocol proto;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct dsa_device_ops {
    struct sk_buff * (*)(struct sk_buff *, struct net_device *) xmit;
    struct sk_buff * (*)(struct sk_buff *, struct net_device *, struct packet_type *) rcv;
    int (*)(const struct sk_buff *, __be16 *, int *) flow_dissect;
    bool (*)(const struct sk_buff *, struct net_device *) filter;
    unsigned int overhead;
    const char * name;
    enum dsa_tag_protocol proto;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct dsa_device_ops {
    struct sk_buff * (*)(struct sk_buff *, struct net_device *) xmit;
    struct sk_buff * (*)(struct sk_buff *, struct net_device *, struct packet_type *) rcv;
    int (*)(const struct sk_buff *, __be16 *, int *) flow_dissect;
    bool (*)(const struct sk_buff *, struct net_device *) filter;
    unsigned int overhead;
    const char * name;
    enum dsa_tag_protocol proto;
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
struct dsa_device_ops {
    struct sk_buff * (*)(struct sk_buff *, struct net_device *) xmit;
    struct sk_buff * (*)(struct sk_buff *, struct net_device *, struct packet_type *) rcv;
    int (*)(const struct sk_buff *, __be16 *, int *) flow_dissect;
}
```
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int overhead</code>
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
<code>bool (*)(const struct sk_buff *, struct net_device *) filter</code>
</li>
<li>
<b>Field added. </b>
<code>const char * name</code>
</li>
<li>
<b>Field added. </b>
<code>enum dsa_tag_protocol proto</code>
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool promisc_on_master</code>
</li>
<li>
<b>Field added. </b>
<code>bool tail_tag</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(const struct sk_buff *, __be16 *, int *) flow_dissect</code> ➡️ <code>void (*)(const struct sk_buff *, __be16 *, int *) flow_dissect</code>
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
<b>Field added. </b>
<code>unsigned int needed_headroom</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int needed_tailroom</code>
</li>
<li>
<b>Field removed. </b>
<code>bool (*)(const struct sk_buff *, struct net_device *) filter</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int overhead</code>
</li>
<li>
<b>Field removed. </b>
<code>bool tail_tag</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct sk_buff * (*)(struct sk_buff *, struct net_device *, struct packet_type *) rcv</code> ➡️ <code>struct sk_buff * (*)(struct sk_buff *, struct net_device *) rcv</code>
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
<code>int (*)(struct dsa_switch *) connect</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct dsa_switch *) disconnect</code>
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool promisc_on_conduit</code>
</li>
<li>
<b>Field removed. </b>
<code>bool promisc_on_master</code>
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
