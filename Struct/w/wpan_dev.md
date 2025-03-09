# Struct: <code>wpan_dev</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct wpan_dev {
    struct wpan_phy * wpan_phy;
    int iftype;
    struct list_head list;
    struct net_device * netdev;
    const struct wpan_dev_header_ops * header_ops;
    struct net_device * lowpan_dev;
    u32 identifier;
    __le16 pan_id;
    __le16 short_addr;
    __le64 extended_addr;
    atomic_t bsn;
    atomic_t dsn;
    u8 min_be;
    u8 max_be;
    u8 csma_retries;
    s8 frame_retries;
    bool lbt;
    bool promiscuous_mode;
    bool ackreq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct wpan_dev {
    struct wpan_phy * wpan_phy;
    int iftype;
    struct list_head list;
    struct net_device * netdev;
    const struct wpan_dev_header_ops * header_ops;
    struct net_device * lowpan_dev;
    u32 identifier;
    __le16 pan_id;
    __le16 short_addr;
    __le64 extended_addr;
    atomic_t bsn;
    atomic_t dsn;
    u8 min_be;
    u8 max_be;
    u8 csma_retries;
    s8 frame_retries;
    bool lbt;
    bool promiscuous_mode;
    bool ackreq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct wpan_dev {
    struct wpan_phy * wpan_phy;
    int iftype;
    struct list_head list;
    struct net_device * netdev;
    const struct wpan_dev_header_ops * header_ops;
    struct net_device * lowpan_dev;
    u32 identifier;
    __le16 pan_id;
    __le16 short_addr;
    __le64 extended_addr;
    atomic_t bsn;
    atomic_t dsn;
    u8 min_be;
    u8 max_be;
    u8 csma_retries;
    s8 frame_retries;
    bool lbt;
    bool promiscuous_mode;
    bool ackreq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct wpan_dev {
    struct wpan_phy * wpan_phy;
    int iftype;
    struct list_head list;
    struct net_device * netdev;
    const struct wpan_dev_header_ops * header_ops;
    struct net_device * lowpan_dev;
    u32 identifier;
    __le16 pan_id;
    __le16 short_addr;
    __le64 extended_addr;
    atomic_t bsn;
    atomic_t dsn;
    u8 min_be;
    u8 max_be;
    u8 csma_retries;
    s8 frame_retries;
    bool lbt;
    bool promiscuous_mode;
    bool ackreq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct wpan_dev {
    struct wpan_phy * wpan_phy;
    int iftype;
    struct list_head list;
    struct net_device * netdev;
    const struct wpan_dev_header_ops * header_ops;
    struct net_device * lowpan_dev;
    u32 identifier;
    __le16 pan_id;
    __le16 short_addr;
    __le64 extended_addr;
    atomic_t bsn;
    atomic_t dsn;
    u8 min_be;
    u8 max_be;
    u8 csma_retries;
    s8 frame_retries;
    bool lbt;
    bool promiscuous_mode;
    bool ackreq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct wpan_dev {
    struct wpan_phy * wpan_phy;
    int iftype;
    struct list_head list;
    struct net_device * netdev;
    const struct wpan_dev_header_ops * header_ops;
    struct net_device * lowpan_dev;
    u32 identifier;
    __le16 pan_id;
    __le16 short_addr;
    __le64 extended_addr;
    atomic_t bsn;
    atomic_t dsn;
    u8 min_be;
    u8 max_be;
    u8 csma_retries;
    s8 frame_retries;
    bool lbt;
    bool promiscuous_mode;
    bool ackreq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct wpan_dev {
    struct wpan_phy * wpan_phy;
    int iftype;
    struct list_head list;
    struct net_device * netdev;
    const struct wpan_dev_header_ops * header_ops;
    struct net_device * lowpan_dev;
    u32 identifier;
    __le16 pan_id;
    __le16 short_addr;
    __le64 extended_addr;
    atomic_t bsn;
    atomic_t dsn;
    u8 min_be;
    u8 max_be;
    u8 csma_retries;
    s8 frame_retries;
    bool lbt;
    bool promiscuous_mode;
    bool ackreq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct wpan_dev {
    struct wpan_phy * wpan_phy;
    int iftype;
    struct list_head list;
    struct net_device * netdev;
    const struct wpan_dev_header_ops * header_ops;
    struct net_device * lowpan_dev;
    u32 identifier;
    __le16 pan_id;
    __le16 short_addr;
    __le64 extended_addr;
    atomic_t bsn;
    atomic_t dsn;
    u8 min_be;
    u8 max_be;
    u8 csma_retries;
    s8 frame_retries;
    bool lbt;
    bool promiscuous_mode;
    bool ackreq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct wpan_dev {
    struct wpan_phy * wpan_phy;
    int iftype;
    struct list_head list;
    struct net_device * netdev;
    const struct wpan_dev_header_ops * header_ops;
    struct net_device * lowpan_dev;
    u32 identifier;
    __le16 pan_id;
    __le16 short_addr;
    __le64 extended_addr;
    atomic_t bsn;
    atomic_t dsn;
    u8 min_be;
    u8 max_be;
    u8 csma_retries;
    s8 frame_retries;
    bool lbt;
    bool promiscuous_mode;
    bool ackreq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct wpan_dev {
    struct wpan_phy * wpan_phy;
    int iftype;
    struct list_head list;
    struct net_device * netdev;
    const struct wpan_dev_header_ops * header_ops;
    struct net_device * lowpan_dev;
    u32 identifier;
    __le16 pan_id;
    __le16 short_addr;
    __le64 extended_addr;
    atomic_t bsn;
    atomic_t dsn;
    u8 min_be;
    u8 max_be;
    u8 csma_retries;
    s8 frame_retries;
    bool lbt;
    bool promiscuous_mode;
    bool ackreq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct wpan_dev {
    struct wpan_phy * wpan_phy;
    int iftype;
    struct list_head list;
    struct net_device * netdev;
    const struct wpan_dev_header_ops * header_ops;
    struct net_device * lowpan_dev;
    u32 identifier;
    __le16 pan_id;
    __le16 short_addr;
    __le64 extended_addr;
    atomic_t bsn;
    atomic_t dsn;
    u8 min_be;
    u8 max_be;
    u8 csma_retries;
    s8 frame_retries;
    bool lbt;
    bool promiscuous_mode;
    bool ackreq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct wpan_dev {
    struct wpan_phy * wpan_phy;
    int iftype;
    struct list_head list;
    struct net_device * netdev;
    const struct wpan_dev_header_ops * header_ops;
    struct net_device * lowpan_dev;
    u32 identifier;
    __le16 pan_id;
    __le16 short_addr;
    __le64 extended_addr;
    atomic_t bsn;
    atomic_t dsn;
    u8 min_be;
    u8 max_be;
    u8 csma_retries;
    s8 frame_retries;
    bool lbt;
    bool promiscuous_mode;
    bool ackreq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct wpan_dev {
    struct wpan_phy * wpan_phy;
    int iftype;
    struct list_head list;
    struct net_device * netdev;
    const struct wpan_dev_header_ops * header_ops;
    struct net_device * lowpan_dev;
    u32 identifier;
    __le16 pan_id;
    __le16 short_addr;
    __le64 extended_addr;
    atomic_t bsn;
    atomic_t dsn;
    u8 min_be;
    u8 max_be;
    u8 csma_retries;
    s8 frame_retries;
    bool lbt;
    bool promiscuous_mode;
    bool ackreq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct wpan_dev {
    struct wpan_phy * wpan_phy;
    int iftype;
    struct list_head list;
    struct net_device * netdev;
    const struct wpan_dev_header_ops * header_ops;
    struct net_device * lowpan_dev;
    u32 identifier;
    __le16 pan_id;
    __le16 short_addr;
    __le64 extended_addr;
    atomic_t bsn;
    atomic_t dsn;
    u8 min_be;
    u8 max_be;
    u8 csma_retries;
    s8 frame_retries;
    bool lbt;
    bool ackreq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct wpan_dev {
    struct wpan_phy * wpan_phy;
    int iftype;
    struct list_head list;
    struct net_device * netdev;
    const struct wpan_dev_header_ops * header_ops;
    struct net_device * lowpan_dev;
    u32 identifier;
    __le16 pan_id;
    __le16 short_addr;
    __le64 extended_addr;
    atomic_t bsn;
    atomic_t dsn;
    u8 min_be;
    u8 max_be;
    u8 csma_retries;
    s8 frame_retries;
    bool lbt;
    bool ackreq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct wpan_dev {
    struct wpan_phy * wpan_phy;
    int iftype;
    struct list_head list;
    struct net_device * netdev;
    const struct wpan_dev_header_ops * header_ops;
    struct net_device * lowpan_dev;
    u32 identifier;
    __le16 pan_id;
    __le16 short_addr;
    __le64 extended_addr;
    atomic_t bsn;
    atomic_t dsn;
    u8 min_be;
    u8 max_be;
    u8 csma_retries;
    s8 frame_retries;
    bool lbt;
    bool ackreq;
    struct mutex association_lock;
    struct ieee802154_pan_device * parent;
    struct list_head children;
    unsigned int max_associations;
    unsigned int nchildren;
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
struct wpan_dev {
    struct wpan_phy * wpan_phy;
    int iftype;
    struct list_head list;
    struct net_device * netdev;
    const struct wpan_dev_header_ops * header_ops;
    struct net_device * lowpan_dev;
    u32 identifier;
    __le16 pan_id;
    __le16 short_addr;
    __le64 extended_addr;
    atomic_t bsn;
    atomic_t dsn;
    u8 min_be;
    u8 max_be;
    u8 csma_retries;
    s8 frame_retries;
    bool lbt;
    bool promiscuous_mode;
    bool ackreq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct wpan_dev {
    struct wpan_phy * wpan_phy;
    int iftype;
    struct list_head list;
    struct net_device * netdev;
    const struct wpan_dev_header_ops * header_ops;
    struct net_device * lowpan_dev;
    u32 identifier;
    __le16 pan_id;
    __le16 short_addr;
    __le64 extended_addr;
    atomic_t bsn;
    atomic_t dsn;
    u8 min_be;
    u8 max_be;
    u8 csma_retries;
    s8 frame_retries;
    bool lbt;
    bool promiscuous_mode;
    bool ackreq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct wpan_dev {
    struct wpan_phy * wpan_phy;
    int iftype;
    struct list_head list;
    struct net_device * netdev;
    const struct wpan_dev_header_ops * header_ops;
    struct net_device * lowpan_dev;
    u32 identifier;
    __le16 pan_id;
    __le16 short_addr;
    __le64 extended_addr;
    atomic_t bsn;
    atomic_t dsn;
    u8 min_be;
    u8 max_be;
    u8 csma_retries;
    s8 frame_retries;
    bool lbt;
    bool promiscuous_mode;
    bool ackreq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct wpan_dev {
    struct wpan_phy * wpan_phy;
    int iftype;
    struct list_head list;
    struct net_device * netdev;
    const struct wpan_dev_header_ops * header_ops;
    struct net_device * lowpan_dev;
    u32 identifier;
    __le16 pan_id;
    __le16 short_addr;
    __le64 extended_addr;
    atomic_t bsn;
    atomic_t dsn;
    u8 min_be;
    u8 max_be;
    u8 csma_retries;
    s8 frame_retries;
    bool lbt;
    bool promiscuous_mode;
    bool ackreq;
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
struct wpan_dev {
    struct wpan_phy * wpan_phy;
    int iftype;
    struct list_head list;
    struct net_device * netdev;
    const struct wpan_dev_header_ops * header_ops;
    struct net_device * lowpan_dev;
    u32 identifier;
    __le16 pan_id;
    __le16 short_addr;
    __le64 extended_addr;
    atomic_t bsn;
    atomic_t dsn;
    u8 min_be;
    u8 max_be;
    u8 csma_retries;
    s8 frame_retries;
    bool lbt;
    bool promiscuous_mode;
    bool ackreq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct wpan_dev {
    struct wpan_phy * wpan_phy;
    int iftype;
    struct list_head list;
    struct net_device * netdev;
    const struct wpan_dev_header_ops * header_ops;
    struct net_device * lowpan_dev;
    u32 identifier;
    __le16 pan_id;
    __le16 short_addr;
    __le64 extended_addr;
    atomic_t bsn;
    atomic_t dsn;
    u8 min_be;
    u8 max_be;
    u8 csma_retries;
    s8 frame_retries;
    bool lbt;
    bool promiscuous_mode;
    bool ackreq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct wpan_dev {
    struct wpan_phy * wpan_phy;
    int iftype;
    struct list_head list;
    struct net_device * netdev;
    const struct wpan_dev_header_ops * header_ops;
    struct net_device * lowpan_dev;
    u32 identifier;
    __le16 pan_id;
    __le16 short_addr;
    __le64 extended_addr;
    atomic_t bsn;
    atomic_t dsn;
    u8 min_be;
    u8 max_be;
    u8 csma_retries;
    s8 frame_retries;
    bool lbt;
    bool promiscuous_mode;
    bool ackreq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct wpan_dev {
    struct wpan_phy * wpan_phy;
    int iftype;
    struct list_head list;
    struct net_device * netdev;
    const struct wpan_dev_header_ops * header_ops;
    struct net_device * lowpan_dev;
    u32 identifier;
    __le16 pan_id;
    __le16 short_addr;
    __le64 extended_addr;
    atomic_t bsn;
    atomic_t dsn;
    u8 min_be;
    u8 max_be;
    u8 csma_retries;
    s8 frame_retries;
    bool lbt;
    bool promiscuous_mode;
    bool ackreq;
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
struct wpan_dev {
    struct wpan_phy * wpan_phy;
    int iftype;
    struct list_head list;
    struct net_device * netdev;
    const struct wpan_dev_header_ops * header_ops;
    struct net_device * lowpan_dev;
    u32 identifier;
    __le16 pan_id;
    __le16 short_addr;
    __le64 extended_addr;
    atomic_t bsn;
    atomic_t dsn;
    u8 min_be;
    u8 max_be;
    u8 csma_retries;
    s8 frame_retries;
    bool lbt;
    bool promiscuous_mode;
    bool ackreq;
}
```
</details>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>bool promiscuous_mode</code>
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
<code>struct mutex association_lock</code>
</li>
<li>
<b>Field added. </b>
<code>struct ieee802154_pan_device * parent</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head children</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int max_associations</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int nchildren</code>
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
