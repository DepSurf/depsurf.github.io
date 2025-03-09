# Struct: <code>neigh_table</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct neigh_table {
    int family;
    int entry_size;
    int key_len;
    __be16 protocol;
    __u32 (*)(const void *, const struct net_device *, __u32 *) hash;
    bool (*)(const struct neighbour *, const void *) key_eq;
    int (*)(struct neighbour *) constructor;
    int (*)(struct pneigh_entry *) pconstructor;
    void (*)(struct pneigh_entry *) pdestructor;
    void (*)(struct sk_buff *) proxy_redo;
    char * id;
    struct neigh_parms parms;
    struct list_head parms_list;
    int gc_interval;
    int gc_thresh1;
    int gc_thresh2;
    int gc_thresh3;
    long unsigned int last_flush;
    struct delayed_work gc_work;
    struct timer_list proxy_timer;
    struct sk_buff_head proxy_queue;
    atomic_t entries;
    rwlock_t lock;
    long unsigned int last_rand;
    struct neigh_statistics * stats;
    struct neigh_hash_table * nht;
    struct pneigh_entry * * phash_buckets;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct neigh_table {
    int family;
    int entry_size;
    int key_len;
    __be16 protocol;
    __u32 (*)(const void *, const struct net_device *, __u32 *) hash;
    bool (*)(const struct neighbour *, const void *) key_eq;
    int (*)(struct neighbour *) constructor;
    int (*)(struct pneigh_entry *) pconstructor;
    void (*)(struct pneigh_entry *) pdestructor;
    void (*)(struct sk_buff *) proxy_redo;
    char * id;
    struct neigh_parms parms;
    struct list_head parms_list;
    int gc_interval;
    int gc_thresh1;
    int gc_thresh2;
    int gc_thresh3;
    long unsigned int last_flush;
    struct delayed_work gc_work;
    struct timer_list proxy_timer;
    struct sk_buff_head proxy_queue;
    atomic_t entries;
    rwlock_t lock;
    long unsigned int last_rand;
    struct neigh_statistics * stats;
    struct neigh_hash_table * nht;
    struct pneigh_entry * * phash_buckets;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct neigh_table {
    int family;
    int entry_size;
    int key_len;
    __be16 protocol;
    __u32 (*)(const void *, const struct net_device *, __u32 *) hash;
    bool (*)(const struct neighbour *, const void *) key_eq;
    int (*)(struct neighbour *) constructor;
    int (*)(struct pneigh_entry *) pconstructor;
    void (*)(struct pneigh_entry *) pdestructor;
    void (*)(struct sk_buff *) proxy_redo;
    char * id;
    struct neigh_parms parms;
    struct list_head parms_list;
    int gc_interval;
    int gc_thresh1;
    int gc_thresh2;
    int gc_thresh3;
    long unsigned int last_flush;
    struct delayed_work gc_work;
    struct timer_list proxy_timer;
    struct sk_buff_head proxy_queue;
    atomic_t entries;
    rwlock_t lock;
    long unsigned int last_rand;
    struct neigh_statistics * stats;
    struct neigh_hash_table * nht;
    struct pneigh_entry * * phash_buckets;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct neigh_table {
    int family;
    int entry_size;
    int key_len;
    __be16 protocol;
    __u32 (*)(const void *, const struct net_device *, __u32 *) hash;
    bool (*)(const struct neighbour *, const void *) key_eq;
    int (*)(struct neighbour *) constructor;
    int (*)(struct pneigh_entry *) pconstructor;
    void (*)(struct pneigh_entry *) pdestructor;
    void (*)(struct sk_buff *) proxy_redo;
    char * id;
    struct neigh_parms parms;
    struct list_head parms_list;
    int gc_interval;
    int gc_thresh1;
    int gc_thresh2;
    int gc_thresh3;
    long unsigned int last_flush;
    struct delayed_work gc_work;
    struct timer_list proxy_timer;
    struct sk_buff_head proxy_queue;
    atomic_t entries;
    rwlock_t lock;
    long unsigned int last_rand;
    struct neigh_statistics * stats;
    struct neigh_hash_table * nht;
    struct pneigh_entry * * phash_buckets;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct neigh_table {
    int family;
    unsigned int entry_size;
    unsigned int key_len;
    __be16 protocol;
    __u32 (*)(const void *, const struct net_device *, __u32 *) hash;
    bool (*)(const struct neighbour *, const void *) key_eq;
    int (*)(struct neighbour *) constructor;
    int (*)(struct pneigh_entry *) pconstructor;
    void (*)(struct pneigh_entry *) pdestructor;
    void (*)(struct sk_buff *) proxy_redo;
    char * id;
    struct neigh_parms parms;
    struct list_head parms_list;
    int gc_interval;
    int gc_thresh1;
    int gc_thresh2;
    int gc_thresh3;
    long unsigned int last_flush;
    struct delayed_work gc_work;
    struct timer_list proxy_timer;
    struct sk_buff_head proxy_queue;
    atomic_t entries;
    rwlock_t lock;
    long unsigned int last_rand;
    struct neigh_statistics * stats;
    struct neigh_hash_table * nht;
    struct pneigh_entry * * phash_buckets;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct neigh_table {
    int family;
    unsigned int entry_size;
    unsigned int key_len;
    __be16 protocol;
    __u32 (*)(const void *, const struct net_device *, __u32 *) hash;
    bool (*)(const struct neighbour *, const void *) key_eq;
    int (*)(struct neighbour *) constructor;
    int (*)(struct pneigh_entry *) pconstructor;
    void (*)(struct pneigh_entry *) pdestructor;
    void (*)(struct sk_buff *) proxy_redo;
    char * id;
    struct neigh_parms parms;
    struct list_head parms_list;
    int gc_interval;
    int gc_thresh1;
    int gc_thresh2;
    int gc_thresh3;
    long unsigned int last_flush;
    struct delayed_work gc_work;
    struct timer_list proxy_timer;
    struct sk_buff_head proxy_queue;
    atomic_t entries;
    rwlock_t lock;
    long unsigned int last_rand;
    struct neigh_statistics * stats;
    struct neigh_hash_table * nht;
    struct pneigh_entry * * phash_buckets;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct neigh_table {
    int family;
    unsigned int entry_size;
    unsigned int key_len;
    __be16 protocol;
    __u32 (*)(const void *, const struct net_device *, __u32 *) hash;
    bool (*)(const struct neighbour *, const void *) key_eq;
    int (*)(struct neighbour *) constructor;
    int (*)(struct pneigh_entry *) pconstructor;
    void (*)(struct pneigh_entry *) pdestructor;
    void (*)(struct sk_buff *) proxy_redo;
    char * id;
    struct neigh_parms parms;
    struct list_head parms_list;
    int gc_interval;
    int gc_thresh1;
    int gc_thresh2;
    int gc_thresh3;
    long unsigned int last_flush;
    struct delayed_work gc_work;
    struct timer_list proxy_timer;
    struct sk_buff_head proxy_queue;
    atomic_t entries;
    atomic_t gc_entries;
    struct list_head gc_list;
    rwlock_t lock;
    long unsigned int last_rand;
    struct neigh_statistics * stats;
    struct neigh_hash_table * nht;
    struct pneigh_entry * * phash_buckets;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct neigh_table {
    int family;
    unsigned int entry_size;
    unsigned int key_len;
    __be16 protocol;
    __u32 (*)(const void *, const struct net_device *, __u32 *) hash;
    bool (*)(const struct neighbour *, const void *) key_eq;
    int (*)(struct neighbour *) constructor;
    int (*)(struct pneigh_entry *) pconstructor;
    void (*)(struct pneigh_entry *) pdestructor;
    void (*)(struct sk_buff *) proxy_redo;
    bool (*)(const struct net_device *, struct netlink_ext_ack *) allow_add;
    char * id;
    struct neigh_parms parms;
    struct list_head parms_list;
    int gc_interval;
    int gc_thresh1;
    int gc_thresh2;
    int gc_thresh3;
    long unsigned int last_flush;
    struct delayed_work gc_work;
    struct timer_list proxy_timer;
    struct sk_buff_head proxy_queue;
    atomic_t entries;
    atomic_t gc_entries;
    struct list_head gc_list;
    rwlock_t lock;
    long unsigned int last_rand;
    struct neigh_statistics * stats;
    struct neigh_hash_table * nht;
    struct pneigh_entry * * phash_buckets;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct neigh_table {
    int family;
    unsigned int entry_size;
    unsigned int key_len;
    __be16 protocol;
    __u32 (*)(const void *, const struct net_device *, __u32 *) hash;
    bool (*)(const struct neighbour *, const void *) key_eq;
    int (*)(struct neighbour *) constructor;
    int (*)(struct pneigh_entry *) pconstructor;
    void (*)(struct pneigh_entry *) pdestructor;
    void (*)(struct sk_buff *) proxy_redo;
    bool (*)(const struct net_device *, struct netlink_ext_ack *) allow_add;
    char * id;
    struct neigh_parms parms;
    struct list_head parms_list;
    int gc_interval;
    int gc_thresh1;
    int gc_thresh2;
    int gc_thresh3;
    long unsigned int last_flush;
    struct delayed_work gc_work;
    struct timer_list proxy_timer;
    struct sk_buff_head proxy_queue;
    atomic_t entries;
    atomic_t gc_entries;
    struct list_head gc_list;
    rwlock_t lock;
    long unsigned int last_rand;
    struct neigh_statistics * stats;
    struct neigh_hash_table * nht;
    struct pneigh_entry * * phash_buckets;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct neigh_table {
    int family;
    unsigned int entry_size;
    unsigned int key_len;
    __be16 protocol;
    __u32 (*)(const void *, const struct net_device *, __u32 *) hash;
    bool (*)(const struct neighbour *, const void *) key_eq;
    int (*)(struct neighbour *) constructor;
    int (*)(struct pneigh_entry *) pconstructor;
    void (*)(struct pneigh_entry *) pdestructor;
    void (*)(struct sk_buff *) proxy_redo;
    bool (*)(const struct net_device *, struct netlink_ext_ack *) allow_add;
    char * id;
    struct neigh_parms parms;
    struct list_head parms_list;
    int gc_interval;
    int gc_thresh1;
    int gc_thresh2;
    int gc_thresh3;
    long unsigned int last_flush;
    struct delayed_work gc_work;
    struct timer_list proxy_timer;
    struct sk_buff_head proxy_queue;
    atomic_t entries;
    atomic_t gc_entries;
    struct list_head gc_list;
    rwlock_t lock;
    long unsigned int last_rand;
    struct neigh_statistics * stats;
    struct neigh_hash_table * nht;
    struct pneigh_entry * * phash_buckets;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct neigh_table {
    int family;
    unsigned int entry_size;
    unsigned int key_len;
    __be16 protocol;
    __u32 (*)(const void *, const struct net_device *, __u32 *) hash;
    bool (*)(const struct neighbour *, const void *) key_eq;
    int (*)(struct neighbour *) constructor;
    int (*)(struct pneigh_entry *) pconstructor;
    void (*)(struct pneigh_entry *) pdestructor;
    void (*)(struct sk_buff *) proxy_redo;
    int (*)(const void *) is_multicast;
    bool (*)(const struct net_device *, struct netlink_ext_ack *) allow_add;
    char * id;
    struct neigh_parms parms;
    struct list_head parms_list;
    int gc_interval;
    int gc_thresh1;
    int gc_thresh2;
    int gc_thresh3;
    long unsigned int last_flush;
    struct delayed_work gc_work;
    struct timer_list proxy_timer;
    struct sk_buff_head proxy_queue;
    atomic_t entries;
    atomic_t gc_entries;
    struct list_head gc_list;
    rwlock_t lock;
    long unsigned int last_rand;
    struct neigh_statistics * stats;
    struct neigh_hash_table * nht;
    struct pneigh_entry * * phash_buckets;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct neigh_table {
    int family;
    unsigned int entry_size;
    unsigned int key_len;
    __be16 protocol;
    __u32 (*)(const void *, const struct net_device *, __u32 *) hash;
    bool (*)(const struct neighbour *, const void *) key_eq;
    int (*)(struct neighbour *) constructor;
    int (*)(struct pneigh_entry *) pconstructor;
    void (*)(struct pneigh_entry *) pdestructor;
    void (*)(struct sk_buff *) proxy_redo;
    int (*)(const void *) is_multicast;
    bool (*)(const struct net_device *, struct netlink_ext_ack *) allow_add;
    char * id;
    struct neigh_parms parms;
    struct list_head parms_list;
    int gc_interval;
    int gc_thresh1;
    int gc_thresh2;
    int gc_thresh3;
    long unsigned int last_flush;
    struct delayed_work gc_work;
    struct timer_list proxy_timer;
    struct sk_buff_head proxy_queue;
    atomic_t entries;
    atomic_t gc_entries;
    struct list_head gc_list;
    rwlock_t lock;
    long unsigned int last_rand;
    struct neigh_statistics * stats;
    struct neigh_hash_table * nht;
    struct pneigh_entry * * phash_buckets;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct neigh_table {
    int family;
    unsigned int entry_size;
    unsigned int key_len;
    __be16 protocol;
    __u32 (*)(const void *, const struct net_device *, __u32 *) hash;
    bool (*)(const struct neighbour *, const void *) key_eq;
    int (*)(struct neighbour *) constructor;
    int (*)(struct pneigh_entry *) pconstructor;
    void (*)(struct pneigh_entry *) pdestructor;
    void (*)(struct sk_buff *) proxy_redo;
    int (*)(const void *) is_multicast;
    bool (*)(const struct net_device *, struct netlink_ext_ack *) allow_add;
    char * id;
    struct neigh_parms parms;
    struct list_head parms_list;
    int gc_interval;
    int gc_thresh1;
    int gc_thresh2;
    int gc_thresh3;
    long unsigned int last_flush;
    struct delayed_work gc_work;
    struct timer_list proxy_timer;
    struct sk_buff_head proxy_queue;
    atomic_t entries;
    atomic_t gc_entries;
    struct list_head gc_list;
    rwlock_t lock;
    long unsigned int last_rand;
    struct neigh_statistics * stats;
    struct neigh_hash_table * nht;
    struct pneigh_entry * * phash_buckets;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct neigh_table {
    int family;
    unsigned int entry_size;
    unsigned int key_len;
    __be16 protocol;
    __u32 (*)(const void *, const struct net_device *, __u32 *) hash;
    bool (*)(const struct neighbour *, const void *) key_eq;
    int (*)(struct neighbour *) constructor;
    int (*)(struct pneigh_entry *) pconstructor;
    void (*)(struct pneigh_entry *) pdestructor;
    void (*)(struct sk_buff *) proxy_redo;
    int (*)(const void *) is_multicast;
    bool (*)(const struct net_device *, struct netlink_ext_ack *) allow_add;
    char * id;
    struct neigh_parms parms;
    struct list_head parms_list;
    int gc_interval;
    int gc_thresh1;
    int gc_thresh2;
    int gc_thresh3;
    long unsigned int last_flush;
    struct delayed_work gc_work;
    struct delayed_work managed_work;
    struct timer_list proxy_timer;
    struct sk_buff_head proxy_queue;
    atomic_t entries;
    atomic_t gc_entries;
    struct list_head gc_list;
    struct list_head managed_list;
    rwlock_t lock;
    long unsigned int last_rand;
    struct neigh_statistics * stats;
    struct neigh_hash_table * nht;
    struct pneigh_entry * * phash_buckets;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct neigh_table {
    int family;
    unsigned int entry_size;
    unsigned int key_len;
    __be16 protocol;
    __u32 (*)(const void *, const struct net_device *, __u32 *) hash;
    bool (*)(const struct neighbour *, const void *) key_eq;
    int (*)(struct neighbour *) constructor;
    int (*)(struct pneigh_entry *) pconstructor;
    void (*)(struct pneigh_entry *) pdestructor;
    void (*)(struct sk_buff *) proxy_redo;
    int (*)(const void *) is_multicast;
    bool (*)(const struct net_device *, struct netlink_ext_ack *) allow_add;
    char * id;
    struct neigh_parms parms;
    struct list_head parms_list;
    int gc_interval;
    int gc_thresh1;
    int gc_thresh2;
    int gc_thresh3;
    long unsigned int last_flush;
    struct delayed_work gc_work;
    struct delayed_work managed_work;
    struct timer_list proxy_timer;
    struct sk_buff_head proxy_queue;
    atomic_t entries;
    atomic_t gc_entries;
    struct list_head gc_list;
    struct list_head managed_list;
    rwlock_t lock;
    long unsigned int last_rand;
    struct neigh_statistics * stats;
    struct neigh_hash_table * nht;
    struct pneigh_entry * * phash_buckets;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct neigh_table {
    int family;
    unsigned int entry_size;
    unsigned int key_len;
    __be16 protocol;
    __u32 (*)(const void *, const struct net_device *, __u32 *) hash;
    bool (*)(const struct neighbour *, const void *) key_eq;
    int (*)(struct neighbour *) constructor;
    int (*)(struct pneigh_entry *) pconstructor;
    void (*)(struct pneigh_entry *) pdestructor;
    void (*)(struct sk_buff *) proxy_redo;
    int (*)(const void *) is_multicast;
    bool (*)(const struct net_device *, struct netlink_ext_ack *) allow_add;
    char * id;
    struct neigh_parms parms;
    struct list_head parms_list;
    int gc_interval;
    int gc_thresh1;
    int gc_thresh2;
    int gc_thresh3;
    long unsigned int last_flush;
    struct delayed_work gc_work;
    struct delayed_work managed_work;
    struct timer_list proxy_timer;
    struct sk_buff_head proxy_queue;
    atomic_t entries;
    atomic_t gc_entries;
    struct list_head gc_list;
    struct list_head managed_list;
    rwlock_t lock;
    long unsigned int last_rand;
    struct neigh_statistics * stats;
    struct neigh_hash_table * nht;
    struct pneigh_entry * * phash_buckets;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct neigh_table {
    int family;
    unsigned int entry_size;
    unsigned int key_len;
    __be16 protocol;
    __u32 (*)(const void *, const struct net_device *, __u32 *) hash;
    bool (*)(const struct neighbour *, const void *) key_eq;
    int (*)(struct neighbour *) constructor;
    int (*)(struct pneigh_entry *) pconstructor;
    void (*)(struct pneigh_entry *) pdestructor;
    void (*)(struct sk_buff *) proxy_redo;
    int (*)(const void *) is_multicast;
    bool (*)(const struct net_device *, struct netlink_ext_ack *) allow_add;
    char * id;
    struct neigh_parms parms;
    struct list_head parms_list;
    int gc_interval;
    int gc_thresh1;
    int gc_thresh2;
    int gc_thresh3;
    long unsigned int last_flush;
    struct delayed_work gc_work;
    struct delayed_work managed_work;
    struct timer_list proxy_timer;
    struct sk_buff_head proxy_queue;
    atomic_t entries;
    atomic_t gc_entries;
    struct list_head gc_list;
    struct list_head managed_list;
    rwlock_t lock;
    long unsigned int last_rand;
    struct neigh_statistics * stats;
    struct neigh_hash_table * nht;
    struct pneigh_entry * * phash_buckets;
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
struct neigh_table {
    int family;
    unsigned int entry_size;
    unsigned int key_len;
    __be16 protocol;
    __u32 (*)(const void *, const struct net_device *, __u32 *) hash;
    bool (*)(const struct neighbour *, const void *) key_eq;
    int (*)(struct neighbour *) constructor;
    int (*)(struct pneigh_entry *) pconstructor;
    void (*)(struct pneigh_entry *) pdestructor;
    void (*)(struct sk_buff *) proxy_redo;
    bool (*)(const struct net_device *, struct netlink_ext_ack *) allow_add;
    char * id;
    struct neigh_parms parms;
    struct list_head parms_list;
    int gc_interval;
    int gc_thresh1;
    int gc_thresh2;
    int gc_thresh3;
    long unsigned int last_flush;
    struct delayed_work gc_work;
    struct timer_list proxy_timer;
    struct sk_buff_head proxy_queue;
    atomic_t entries;
    atomic_t gc_entries;
    struct list_head gc_list;
    rwlock_t lock;
    long unsigned int last_rand;
    struct neigh_statistics * stats;
    struct neigh_hash_table * nht;
    struct pneigh_entry * * phash_buckets;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct neigh_table {
    int family;
    unsigned int entry_size;
    unsigned int key_len;
    __be16 protocol;
    __u32 (*)(const void *, const struct net_device *, __u32 *) hash;
    bool (*)(const struct neighbour *, const void *) key_eq;
    int (*)(struct neighbour *) constructor;
    int (*)(struct pneigh_entry *) pconstructor;
    void (*)(struct pneigh_entry *) pdestructor;
    void (*)(struct sk_buff *) proxy_redo;
    bool (*)(const struct net_device *, struct netlink_ext_ack *) allow_add;
    char * id;
    struct neigh_parms parms;
    struct list_head parms_list;
    int gc_interval;
    int gc_thresh1;
    int gc_thresh2;
    int gc_thresh3;
    long unsigned int last_flush;
    struct delayed_work gc_work;
    struct timer_list proxy_timer;
    struct sk_buff_head proxy_queue;
    atomic_t entries;
    atomic_t gc_entries;
    struct list_head gc_list;
    rwlock_t lock;
    long unsigned int last_rand;
    struct neigh_statistics * stats;
    struct neigh_hash_table * nht;
    struct pneigh_entry * * phash_buckets;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct neigh_table {
    int family;
    unsigned int entry_size;
    unsigned int key_len;
    __be16 protocol;
    __u32 (*)(const void *, const struct net_device *, __u32 *) hash;
    bool (*)(const struct neighbour *, const void *) key_eq;
    int (*)(struct neighbour *) constructor;
    int (*)(struct pneigh_entry *) pconstructor;
    void (*)(struct pneigh_entry *) pdestructor;
    void (*)(struct sk_buff *) proxy_redo;
    bool (*)(const struct net_device *, struct netlink_ext_ack *) allow_add;
    char * id;
    struct neigh_parms parms;
    struct list_head parms_list;
    int gc_interval;
    int gc_thresh1;
    int gc_thresh2;
    int gc_thresh3;
    long unsigned int last_flush;
    struct delayed_work gc_work;
    struct timer_list proxy_timer;
    struct sk_buff_head proxy_queue;
    atomic_t entries;
    atomic_t gc_entries;
    struct list_head gc_list;
    rwlock_t lock;
    long unsigned int last_rand;
    struct neigh_statistics * stats;
    struct neigh_hash_table * nht;
    struct pneigh_entry * * phash_buckets;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct neigh_table {
    int family;
    unsigned int entry_size;
    unsigned int key_len;
    __be16 protocol;
    __u32 (*)(const void *, const struct net_device *, __u32 *) hash;
    bool (*)(const struct neighbour *, const void *) key_eq;
    int (*)(struct neighbour *) constructor;
    int (*)(struct pneigh_entry *) pconstructor;
    void (*)(struct pneigh_entry *) pdestructor;
    void (*)(struct sk_buff *) proxy_redo;
    bool (*)(const struct net_device *, struct netlink_ext_ack *) allow_add;
    char * id;
    struct neigh_parms parms;
    struct list_head parms_list;
    int gc_interval;
    int gc_thresh1;
    int gc_thresh2;
    int gc_thresh3;
    long unsigned int last_flush;
    struct delayed_work gc_work;
    struct timer_list proxy_timer;
    struct sk_buff_head proxy_queue;
    atomic_t entries;
    atomic_t gc_entries;
    struct list_head gc_list;
    rwlock_t lock;
    long unsigned int last_rand;
    struct neigh_statistics * stats;
    struct neigh_hash_table * nht;
    struct pneigh_entry * * phash_buckets;
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
struct neigh_table {
    int family;
    unsigned int entry_size;
    unsigned int key_len;
    __be16 protocol;
    __u32 (*)(const void *, const struct net_device *, __u32 *) hash;
    bool (*)(const struct neighbour *, const void *) key_eq;
    int (*)(struct neighbour *) constructor;
    int (*)(struct pneigh_entry *) pconstructor;
    void (*)(struct pneigh_entry *) pdestructor;
    void (*)(struct sk_buff *) proxy_redo;
    bool (*)(const struct net_device *, struct netlink_ext_ack *) allow_add;
    char * id;
    struct neigh_parms parms;
    struct list_head parms_list;
    int gc_interval;
    int gc_thresh1;
    int gc_thresh2;
    int gc_thresh3;
    long unsigned int last_flush;
    struct delayed_work gc_work;
    struct timer_list proxy_timer;
    struct sk_buff_head proxy_queue;
    atomic_t entries;
    atomic_t gc_entries;
    struct list_head gc_list;
    rwlock_t lock;
    long unsigned int last_rand;
    struct neigh_statistics * stats;
    struct neigh_hash_table * nht;
    struct pneigh_entry * * phash_buckets;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct neigh_table {
    int family;
    unsigned int entry_size;
    unsigned int key_len;
    __be16 protocol;
    __u32 (*)(const void *, const struct net_device *, __u32 *) hash;
    bool (*)(const struct neighbour *, const void *) key_eq;
    int (*)(struct neighbour *) constructor;
    int (*)(struct pneigh_entry *) pconstructor;
    void (*)(struct pneigh_entry *) pdestructor;
    void (*)(struct sk_buff *) proxy_redo;
    bool (*)(const struct net_device *, struct netlink_ext_ack *) allow_add;
    char * id;
    struct neigh_parms parms;
    struct list_head parms_list;
    int gc_interval;
    int gc_thresh1;
    int gc_thresh2;
    int gc_thresh3;
    long unsigned int last_flush;
    struct delayed_work gc_work;
    struct timer_list proxy_timer;
    struct sk_buff_head proxy_queue;
    atomic_t entries;
    atomic_t gc_entries;
    struct list_head gc_list;
    rwlock_t lock;
    long unsigned int last_rand;
    struct neigh_statistics * stats;
    struct neigh_hash_table * nht;
    struct pneigh_entry * * phash_buckets;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct neigh_table {
    int family;
    unsigned int entry_size;
    unsigned int key_len;
    __be16 protocol;
    __u32 (*)(const void *, const struct net_device *, __u32 *) hash;
    bool (*)(const struct neighbour *, const void *) key_eq;
    int (*)(struct neighbour *) constructor;
    int (*)(struct pneigh_entry *) pconstructor;
    void (*)(struct pneigh_entry *) pdestructor;
    void (*)(struct sk_buff *) proxy_redo;
    bool (*)(const struct net_device *, struct netlink_ext_ack *) allow_add;
    char * id;
    struct neigh_parms parms;
    struct list_head parms_list;
    int gc_interval;
    int gc_thresh1;
    int gc_thresh2;
    int gc_thresh3;
    long unsigned int last_flush;
    struct delayed_work gc_work;
    struct timer_list proxy_timer;
    struct sk_buff_head proxy_queue;
    atomic_t entries;
    atomic_t gc_entries;
    struct list_head gc_list;
    rwlock_t lock;
    long unsigned int last_rand;
    struct neigh_statistics * stats;
    struct neigh_hash_table * nht;
    struct pneigh_entry * * phash_buckets;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct neigh_table {
    int family;
    unsigned int entry_size;
    unsigned int key_len;
    __be16 protocol;
    __u32 (*)(const void *, const struct net_device *, __u32 *) hash;
    bool (*)(const struct neighbour *, const void *) key_eq;
    int (*)(struct neighbour *) constructor;
    int (*)(struct pneigh_entry *) pconstructor;
    void (*)(struct pneigh_entry *) pdestructor;
    void (*)(struct sk_buff *) proxy_redo;
    bool (*)(const struct net_device *, struct netlink_ext_ack *) allow_add;
    char * id;
    struct neigh_parms parms;
    struct list_head parms_list;
    int gc_interval;
    int gc_thresh1;
    int gc_thresh2;
    int gc_thresh3;
    long unsigned int last_flush;
    struct delayed_work gc_work;
    struct timer_list proxy_timer;
    struct sk_buff_head proxy_queue;
    atomic_t entries;
    atomic_t gc_entries;
    struct list_head gc_list;
    rwlock_t lock;
    long unsigned int last_rand;
    struct neigh_statistics * stats;
    struct neigh_hash_table * nht;
    struct pneigh_entry * * phash_buckets;
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
<b>Field type changed. </b>
<code>int entry_size</code> ➡️ <code>unsigned int entry_size</code>
</li>
<li>
<b>Field type changed. </b>
<code>int key_len</code> ➡️ <code>unsigned int key_len</code>
</li>
</ul>
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
<code>atomic_t gc_entries</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head gc_list</code>
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
<code>bool (*)(const struct net_device *, struct netlink_ext_ack *) allow_add</code>
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
<code>int (*)(const void *) is_multicast</code>
</li>
</ul>
</details>
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
<b>Field added. </b>
<code>struct delayed_work managed_work</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head managed_list</code>
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
