# Struct: <code>xfrm_mgr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct xfrm_mgr {
    struct list_head list;
    char * id;
    int (*)(struct xfrm_state *, const struct km_event *) notify;
    int (*)(struct xfrm_state *, struct xfrm_tmpl *, struct xfrm_policy *) acquire;
    struct xfrm_policy * (*)(struct sock *, int, u8 *, int, int *) compile_policy;
    int (*)(struct xfrm_state *, xfrm_address_t *, __be16) new_mapping;
    int (*)(struct xfrm_policy *, int, const struct km_event *) notify_policy;
    int (*)(struct net *, u8, struct xfrm_selector *, xfrm_address_t *) report;
    int (*)(const struct xfrm_selector *, u8, u8, const struct xfrm_migrate *, int, const struct xfrm_kmaddress *) migrate;
    bool (*)(const struct km_event *) is_alive;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct xfrm_mgr {
    struct list_head list;
    char * id;
    int (*)(struct xfrm_state *, const struct km_event *) notify;
    int (*)(struct xfrm_state *, struct xfrm_tmpl *, struct xfrm_policy *) acquire;
    struct xfrm_policy * (*)(struct sock *, int, u8 *, int, int *) compile_policy;
    int (*)(struct xfrm_state *, xfrm_address_t *, __be16) new_mapping;
    int (*)(struct xfrm_policy *, int, const struct km_event *) notify_policy;
    int (*)(struct net *, u8, struct xfrm_selector *, xfrm_address_t *) report;
    int (*)(const struct xfrm_selector *, u8, u8, const struct xfrm_migrate *, int, const struct xfrm_kmaddress *) migrate;
    bool (*)(const struct km_event *) is_alive;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct xfrm_mgr {
    struct list_head list;
    char * id;
    int (*)(struct xfrm_state *, const struct km_event *) notify;
    int (*)(struct xfrm_state *, struct xfrm_tmpl *, struct xfrm_policy *) acquire;
    struct xfrm_policy * (*)(struct sock *, int, u8 *, int, int *) compile_policy;
    int (*)(struct xfrm_state *, xfrm_address_t *, __be16) new_mapping;
    int (*)(struct xfrm_policy *, int, const struct km_event *) notify_policy;
    int (*)(struct net *, u8, struct xfrm_selector *, xfrm_address_t *) report;
    int (*)(const struct xfrm_selector *, u8, u8, const struct xfrm_migrate *, int, const struct xfrm_kmaddress *) migrate;
    bool (*)(const struct km_event *) is_alive;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct xfrm_mgr {
    struct list_head list;
    int (*)(struct xfrm_state *, const struct km_event *) notify;
    int (*)(struct xfrm_state *, struct xfrm_tmpl *, struct xfrm_policy *) acquire;
    struct xfrm_policy * (*)(struct sock *, int, u8 *, int, int *) compile_policy;
    int (*)(struct xfrm_state *, xfrm_address_t *, __be16) new_mapping;
    int (*)(struct xfrm_policy *, int, const struct km_event *) notify_policy;
    int (*)(struct net *, u8, struct xfrm_selector *, xfrm_address_t *) report;
    int (*)(const struct xfrm_selector *, u8, u8, const struct xfrm_migrate *, int, const struct xfrm_kmaddress *, const struct xfrm_encap_tmpl *) migrate;
    bool (*)(const struct km_event *) is_alive;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct xfrm_mgr {
    struct list_head list;
    int (*)(struct xfrm_state *, const struct km_event *) notify;
    int (*)(struct xfrm_state *, struct xfrm_tmpl *, struct xfrm_policy *) acquire;
    struct xfrm_policy * (*)(struct sock *, int, u8 *, int, int *) compile_policy;
    int (*)(struct xfrm_state *, xfrm_address_t *, __be16) new_mapping;
    int (*)(struct xfrm_policy *, int, const struct km_event *) notify_policy;
    int (*)(struct net *, u8, struct xfrm_selector *, xfrm_address_t *) report;
    int (*)(const struct xfrm_selector *, u8, u8, const struct xfrm_migrate *, int, const struct xfrm_kmaddress *, const struct xfrm_encap_tmpl *) migrate;
    bool (*)(const struct km_event *) is_alive;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct xfrm_mgr {
    struct list_head list;
    int (*)(struct xfrm_state *, const struct km_event *) notify;
    int (*)(struct xfrm_state *, struct xfrm_tmpl *, struct xfrm_policy *) acquire;
    struct xfrm_policy * (*)(struct sock *, int, u8 *, int, int *) compile_policy;
    int (*)(struct xfrm_state *, xfrm_address_t *, __be16) new_mapping;
    int (*)(struct xfrm_policy *, int, const struct km_event *) notify_policy;
    int (*)(struct net *, u8, struct xfrm_selector *, xfrm_address_t *) report;
    int (*)(const struct xfrm_selector *, u8, u8, const struct xfrm_migrate *, int, const struct xfrm_kmaddress *, const struct xfrm_encap_tmpl *) migrate;
    bool (*)(const struct km_event *) is_alive;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct xfrm_mgr {
    struct list_head list;
    int (*)(struct xfrm_state *, const struct km_event *) notify;
    int (*)(struct xfrm_state *, struct xfrm_tmpl *, struct xfrm_policy *) acquire;
    struct xfrm_policy * (*)(struct sock *, int, u8 *, int, int *) compile_policy;
    int (*)(struct xfrm_state *, xfrm_address_t *, __be16) new_mapping;
    int (*)(struct xfrm_policy *, int, const struct km_event *) notify_policy;
    int (*)(struct net *, u8, struct xfrm_selector *, xfrm_address_t *) report;
    int (*)(const struct xfrm_selector *, u8, u8, const struct xfrm_migrate *, int, const struct xfrm_kmaddress *, const struct xfrm_encap_tmpl *) migrate;
    bool (*)(const struct km_event *) is_alive;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct xfrm_mgr {
    struct list_head list;
    int (*)(struct xfrm_state *, const struct km_event *) notify;
    int (*)(struct xfrm_state *, struct xfrm_tmpl *, struct xfrm_policy *) acquire;
    struct xfrm_policy * (*)(struct sock *, int, u8 *, int, int *) compile_policy;
    int (*)(struct xfrm_state *, xfrm_address_t *, __be16) new_mapping;
    int (*)(struct xfrm_policy *, int, const struct km_event *) notify_policy;
    int (*)(struct net *, u8, struct xfrm_selector *, xfrm_address_t *) report;
    int (*)(const struct xfrm_selector *, u8, u8, const struct xfrm_migrate *, int, const struct xfrm_kmaddress *, const struct xfrm_encap_tmpl *) migrate;
    bool (*)(const struct km_event *) is_alive;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct xfrm_mgr {
    struct list_head list;
    int (*)(struct xfrm_state *, const struct km_event *) notify;
    int (*)(struct xfrm_state *, struct xfrm_tmpl *, struct xfrm_policy *) acquire;
    struct xfrm_policy * (*)(struct sock *, int, u8 *, int, int *) compile_policy;
    int (*)(struct xfrm_state *, xfrm_address_t *, __be16) new_mapping;
    int (*)(struct xfrm_policy *, int, const struct km_event *) notify_policy;
    int (*)(struct net *, u8, struct xfrm_selector *, xfrm_address_t *) report;
    int (*)(const struct xfrm_selector *, u8, u8, const struct xfrm_migrate *, int, const struct xfrm_kmaddress *, const struct xfrm_encap_tmpl *) migrate;
    bool (*)(const struct km_event *) is_alive;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct xfrm_mgr {
    struct list_head list;
    int (*)(struct xfrm_state *, const struct km_event *) notify;
    int (*)(struct xfrm_state *, struct xfrm_tmpl *, struct xfrm_policy *) acquire;
    struct xfrm_policy * (*)(struct sock *, int, u8 *, int, int *) compile_policy;
    int (*)(struct xfrm_state *, xfrm_address_t *, __be16) new_mapping;
    int (*)(struct xfrm_policy *, int, const struct km_event *) notify_policy;
    int (*)(struct net *, u8, struct xfrm_selector *, xfrm_address_t *) report;
    int (*)(const struct xfrm_selector *, u8, u8, const struct xfrm_migrate *, int, const struct xfrm_kmaddress *, const struct xfrm_encap_tmpl *) migrate;
    bool (*)(const struct km_event *) is_alive;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct xfrm_mgr {
    struct list_head list;
    int (*)(struct xfrm_state *, const struct km_event *) notify;
    int (*)(struct xfrm_state *, struct xfrm_tmpl *, struct xfrm_policy *) acquire;
    struct xfrm_policy * (*)(struct sock *, int, u8 *, int, int *) compile_policy;
    int (*)(struct xfrm_state *, xfrm_address_t *, __be16) new_mapping;
    int (*)(struct xfrm_policy *, int, const struct km_event *) notify_policy;
    int (*)(struct net *, u8, struct xfrm_selector *, xfrm_address_t *) report;
    int (*)(const struct xfrm_selector *, u8, u8, const struct xfrm_migrate *, int, const struct xfrm_kmaddress *, const struct xfrm_encap_tmpl *) migrate;
    bool (*)(const struct km_event *) is_alive;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct xfrm_mgr {
    struct list_head list;
    int (*)(struct xfrm_state *, const struct km_event *) notify;
    int (*)(struct xfrm_state *, struct xfrm_tmpl *, struct xfrm_policy *) acquire;
    struct xfrm_policy * (*)(struct sock *, int, u8 *, int, int *) compile_policy;
    int (*)(struct xfrm_state *, xfrm_address_t *, __be16) new_mapping;
    int (*)(struct xfrm_policy *, int, const struct km_event *) notify_policy;
    int (*)(struct net *, u8, struct xfrm_selector *, xfrm_address_t *) report;
    int (*)(const struct xfrm_selector *, u8, u8, const struct xfrm_migrate *, int, const struct xfrm_kmaddress *, const struct xfrm_encap_tmpl *) migrate;
    bool (*)(const struct km_event *) is_alive;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct xfrm_mgr {
    struct list_head list;
    int (*)(struct xfrm_state *, const struct km_event *) notify;
    int (*)(struct xfrm_state *, struct xfrm_tmpl *, struct xfrm_policy *) acquire;
    struct xfrm_policy * (*)(struct sock *, int, u8 *, int, int *) compile_policy;
    int (*)(struct xfrm_state *, xfrm_address_t *, __be16) new_mapping;
    int (*)(struct xfrm_policy *, int, const struct km_event *) notify_policy;
    int (*)(struct net *, u8, struct xfrm_selector *, xfrm_address_t *) report;
    int (*)(const struct xfrm_selector *, u8, u8, const struct xfrm_migrate *, int, const struct xfrm_kmaddress *, const struct xfrm_encap_tmpl *) migrate;
    bool (*)(const struct km_event *) is_alive;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct xfrm_mgr {
    struct list_head list;
    int (*)(struct xfrm_state *, const struct km_event *) notify;
    int (*)(struct xfrm_state *, struct xfrm_tmpl *, struct xfrm_policy *) acquire;
    struct xfrm_policy * (*)(struct sock *, int, u8 *, int, int *) compile_policy;
    int (*)(struct xfrm_state *, xfrm_address_t *, __be16) new_mapping;
    int (*)(struct xfrm_policy *, int, const struct km_event *) notify_policy;
    int (*)(struct net *, u8, struct xfrm_selector *, xfrm_address_t *) report;
    int (*)(const struct xfrm_selector *, u8, u8, const struct xfrm_migrate *, int, const struct xfrm_kmaddress *, const struct xfrm_encap_tmpl *) migrate;
    bool (*)(const struct km_event *) is_alive;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct xfrm_mgr {
    struct list_head list;
    int (*)(struct xfrm_state *, const struct km_event *) notify;
    int (*)(struct xfrm_state *, struct xfrm_tmpl *, struct xfrm_policy *) acquire;
    struct xfrm_policy * (*)(struct sock *, int, u8 *, int, int *) compile_policy;
    int (*)(struct xfrm_state *, xfrm_address_t *, __be16) new_mapping;
    int (*)(struct xfrm_policy *, int, const struct km_event *) notify_policy;
    int (*)(struct net *, u8, struct xfrm_selector *, xfrm_address_t *) report;
    int (*)(const struct xfrm_selector *, u8, u8, const struct xfrm_migrate *, int, const struct xfrm_kmaddress *, const struct xfrm_encap_tmpl *) migrate;
    bool (*)(const struct km_event *) is_alive;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct xfrm_mgr {
    struct list_head list;
    int (*)(struct xfrm_state *, const struct km_event *) notify;
    int (*)(struct xfrm_state *, struct xfrm_tmpl *, struct xfrm_policy *) acquire;
    struct xfrm_policy * (*)(struct sock *, int, u8 *, int, int *) compile_policy;
    int (*)(struct xfrm_state *, xfrm_address_t *, __be16) new_mapping;
    int (*)(struct xfrm_policy *, int, const struct km_event *) notify_policy;
    int (*)(struct net *, u8, struct xfrm_selector *, xfrm_address_t *) report;
    int (*)(const struct xfrm_selector *, u8, u8, const struct xfrm_migrate *, int, const struct xfrm_kmaddress *, const struct xfrm_encap_tmpl *) migrate;
    bool (*)(const struct km_event *) is_alive;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct xfrm_mgr {
    struct list_head list;
    int (*)(struct xfrm_state *, const struct km_event *) notify;
    int (*)(struct xfrm_state *, struct xfrm_tmpl *, struct xfrm_policy *) acquire;
    struct xfrm_policy * (*)(struct sock *, int, u8 *, int, int *) compile_policy;
    int (*)(struct xfrm_state *, xfrm_address_t *, __be16) new_mapping;
    int (*)(struct xfrm_policy *, int, const struct km_event *) notify_policy;
    int (*)(struct net *, u8, struct xfrm_selector *, xfrm_address_t *) report;
    int (*)(const struct xfrm_selector *, u8, u8, const struct xfrm_migrate *, int, const struct xfrm_kmaddress *, const struct xfrm_encap_tmpl *) migrate;
    bool (*)(const struct km_event *) is_alive;
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
struct xfrm_mgr {
    struct list_head list;
    int (*)(struct xfrm_state *, const struct km_event *) notify;
    int (*)(struct xfrm_state *, struct xfrm_tmpl *, struct xfrm_policy *) acquire;
    struct xfrm_policy * (*)(struct sock *, int, u8 *, int, int *) compile_policy;
    int (*)(struct xfrm_state *, xfrm_address_t *, __be16) new_mapping;
    int (*)(struct xfrm_policy *, int, const struct km_event *) notify_policy;
    int (*)(struct net *, u8, struct xfrm_selector *, xfrm_address_t *) report;
    int (*)(const struct xfrm_selector *, u8, u8, const struct xfrm_migrate *, int, const struct xfrm_kmaddress *, const struct xfrm_encap_tmpl *) migrate;
    bool (*)(const struct km_event *) is_alive;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct xfrm_mgr {
    struct list_head list;
    int (*)(struct xfrm_state *, const struct km_event *) notify;
    int (*)(struct xfrm_state *, struct xfrm_tmpl *, struct xfrm_policy *) acquire;
    struct xfrm_policy * (*)(struct sock *, int, u8 *, int, int *) compile_policy;
    int (*)(struct xfrm_state *, xfrm_address_t *, __be16) new_mapping;
    int (*)(struct xfrm_policy *, int, const struct km_event *) notify_policy;
    int (*)(struct net *, u8, struct xfrm_selector *, xfrm_address_t *) report;
    int (*)(const struct xfrm_selector *, u8, u8, const struct xfrm_migrate *, int, const struct xfrm_kmaddress *, const struct xfrm_encap_tmpl *) migrate;
    bool (*)(const struct km_event *) is_alive;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct xfrm_mgr {
    struct list_head list;
    int (*)(struct xfrm_state *, const struct km_event *) notify;
    int (*)(struct xfrm_state *, struct xfrm_tmpl *, struct xfrm_policy *) acquire;
    struct xfrm_policy * (*)(struct sock *, int, u8 *, int, int *) compile_policy;
    int (*)(struct xfrm_state *, xfrm_address_t *, __be16) new_mapping;
    int (*)(struct xfrm_policy *, int, const struct km_event *) notify_policy;
    int (*)(struct net *, u8, struct xfrm_selector *, xfrm_address_t *) report;
    int (*)(const struct xfrm_selector *, u8, u8, const struct xfrm_migrate *, int, const struct xfrm_kmaddress *, const struct xfrm_encap_tmpl *) migrate;
    bool (*)(const struct km_event *) is_alive;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct xfrm_mgr {
    struct list_head list;
    int (*)(struct xfrm_state *, const struct km_event *) notify;
    int (*)(struct xfrm_state *, struct xfrm_tmpl *, struct xfrm_policy *) acquire;
    struct xfrm_policy * (*)(struct sock *, int, u8 *, int, int *) compile_policy;
    int (*)(struct xfrm_state *, xfrm_address_t *, __be16) new_mapping;
    int (*)(struct xfrm_policy *, int, const struct km_event *) notify_policy;
    int (*)(struct net *, u8, struct xfrm_selector *, xfrm_address_t *) report;
    int (*)(const struct xfrm_selector *, u8, u8, const struct xfrm_migrate *, int, const struct xfrm_kmaddress *, const struct xfrm_encap_tmpl *) migrate;
    bool (*)(const struct km_event *) is_alive;
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
struct xfrm_mgr {
    struct list_head list;
    int (*)(struct xfrm_state *, const struct km_event *) notify;
    int (*)(struct xfrm_state *, struct xfrm_tmpl *, struct xfrm_policy *) acquire;
    struct xfrm_policy * (*)(struct sock *, int, u8 *, int, int *) compile_policy;
    int (*)(struct xfrm_state *, xfrm_address_t *, __be16) new_mapping;
    int (*)(struct xfrm_policy *, int, const struct km_event *) notify_policy;
    int (*)(struct net *, u8, struct xfrm_selector *, xfrm_address_t *) report;
    int (*)(const struct xfrm_selector *, u8, u8, const struct xfrm_migrate *, int, const struct xfrm_kmaddress *, const struct xfrm_encap_tmpl *) migrate;
    bool (*)(const struct km_event *) is_alive;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct xfrm_mgr {
    struct list_head list;
    int (*)(struct xfrm_state *, const struct km_event *) notify;
    int (*)(struct xfrm_state *, struct xfrm_tmpl *, struct xfrm_policy *) acquire;
    struct xfrm_policy * (*)(struct sock *, int, u8 *, int, int *) compile_policy;
    int (*)(struct xfrm_state *, xfrm_address_t *, __be16) new_mapping;
    int (*)(struct xfrm_policy *, int, const struct km_event *) notify_policy;
    int (*)(struct net *, u8, struct xfrm_selector *, xfrm_address_t *) report;
    int (*)(const struct xfrm_selector *, u8, u8, const struct xfrm_migrate *, int, const struct xfrm_kmaddress *, const struct xfrm_encap_tmpl *) migrate;
    bool (*)(const struct km_event *) is_alive;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct xfrm_mgr {
    struct list_head list;
    int (*)(struct xfrm_state *, const struct km_event *) notify;
    int (*)(struct xfrm_state *, struct xfrm_tmpl *, struct xfrm_policy *) acquire;
    struct xfrm_policy * (*)(struct sock *, int, u8 *, int, int *) compile_policy;
    int (*)(struct xfrm_state *, xfrm_address_t *, __be16) new_mapping;
    int (*)(struct xfrm_policy *, int, const struct km_event *) notify_policy;
    int (*)(struct net *, u8, struct xfrm_selector *, xfrm_address_t *) report;
    int (*)(const struct xfrm_selector *, u8, u8, const struct xfrm_migrate *, int, const struct xfrm_kmaddress *, const struct xfrm_encap_tmpl *) migrate;
    bool (*)(const struct km_event *) is_alive;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct xfrm_mgr {
    struct list_head list;
    int (*)(struct xfrm_state *, const struct km_event *) notify;
    int (*)(struct xfrm_state *, struct xfrm_tmpl *, struct xfrm_policy *) acquire;
    struct xfrm_policy * (*)(struct sock *, int, u8 *, int, int *) compile_policy;
    int (*)(struct xfrm_state *, xfrm_address_t *, __be16) new_mapping;
    int (*)(struct xfrm_policy *, int, const struct km_event *) notify_policy;
    int (*)(struct net *, u8, struct xfrm_selector *, xfrm_address_t *) report;
    int (*)(const struct xfrm_selector *, u8, u8, const struct xfrm_migrate *, int, const struct xfrm_kmaddress *, const struct xfrm_encap_tmpl *) migrate;
    bool (*)(const struct km_event *) is_alive;
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
<b>Field removed. </b>
<code>char * id</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(const struct xfrm_selector *, u8, u8, const struct xfrm_migrate *, int, const struct xfrm_kmaddress *) migrate</code> ➡️ <code>int (*)(const struct xfrm_selector *, u8, u8, const struct xfrm_migrate *, int, const struct xfrm_kmaddress *, const struct xfrm_encap_tmpl *) migrate</code>
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
