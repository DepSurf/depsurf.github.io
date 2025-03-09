# Struct: <code>ib_port_data</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct ib_port_data {
    struct ib_device * ib_dev;
    struct ib_port_immutable immutable;
    spinlock_t pkey_list_lock;
    struct list_head pkey_list;
    struct ib_port_cache cache;
    spinlock_t netdev_lock;
    struct net_device * netdev;
    struct hlist_node ndev_hash_link;
    struct rdma_port_counter port_counter;
    struct rdma_hw_stats * hw_stats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct ib_port_data {
    struct ib_device * ib_dev;
    struct ib_port_immutable immutable;
    spinlock_t pkey_list_lock;
    struct list_head pkey_list;
    struct ib_port_cache cache;
    spinlock_t netdev_lock;
    struct net_device * netdev;
    struct hlist_node ndev_hash_link;
    struct rdma_port_counter port_counter;
    struct rdma_hw_stats * hw_stats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct ib_port_data {
    struct ib_device * ib_dev;
    struct ib_port_immutable immutable;
    spinlock_t pkey_list_lock;
    struct list_head pkey_list;
    struct ib_port_cache cache;
    spinlock_t netdev_lock;
    struct net_device * netdev;
    struct hlist_node ndev_hash_link;
    struct rdma_port_counter port_counter;
    struct rdma_hw_stats * hw_stats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct ib_port_data {
    struct ib_device * ib_dev;
    struct ib_port_immutable immutable;
    spinlock_t pkey_list_lock;
    struct list_head pkey_list;
    struct ib_port_cache cache;
    spinlock_t netdev_lock;
    struct net_device * netdev;
    struct hlist_node ndev_hash_link;
    struct rdma_port_counter port_counter;
    struct rdma_hw_stats * hw_stats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct ib_port_data {
    struct ib_device * ib_dev;
    struct ib_port_immutable immutable;
    spinlock_t pkey_list_lock;
    struct list_head pkey_list;
    struct ib_port_cache cache;
    spinlock_t netdev_lock;
    struct net_device * netdev;
    struct hlist_node ndev_hash_link;
    struct rdma_port_counter port_counter;
    struct rdma_hw_stats * hw_stats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct ib_port_data {
    struct ib_device * ib_dev;
    struct ib_port_immutable immutable;
    spinlock_t pkey_list_lock;
    spinlock_t netdev_lock;
    struct list_head pkey_list;
    struct ib_port_cache cache;
    struct net_device * netdev;
    struct hlist_node ndev_hash_link;
    struct rdma_port_counter port_counter;
    struct ib_port * sysfs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct ib_port_data {
    struct ib_device * ib_dev;
    struct ib_port_immutable immutable;
    spinlock_t pkey_list_lock;
    spinlock_t netdev_lock;
    struct list_head pkey_list;
    struct ib_port_cache cache;
    struct net_device * netdev;
    struct hlist_node ndev_hash_link;
    struct rdma_port_counter port_counter;
    struct ib_port * sysfs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct ib_port_data {
    struct ib_device * ib_dev;
    struct ib_port_immutable immutable;
    spinlock_t pkey_list_lock;
    spinlock_t netdev_lock;
    struct list_head pkey_list;
    struct ib_port_cache cache;
    struct net_device * netdev;
    netdevice_tracker netdev_tracker;
    struct hlist_node ndev_hash_link;
    struct rdma_port_counter port_counter;
    struct ib_port * sysfs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct ib_port_data {
    struct ib_device * ib_dev;
    struct ib_port_immutable immutable;
    spinlock_t pkey_list_lock;
    spinlock_t netdev_lock;
    struct list_head pkey_list;
    struct ib_port_cache cache;
    struct net_device * netdev;
    netdevice_tracker netdev_tracker;
    struct hlist_node ndev_hash_link;
    struct rdma_port_counter port_counter;
    struct ib_port * sysfs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct ib_port_data {
    struct ib_device * ib_dev;
    struct ib_port_immutable immutable;
    spinlock_t pkey_list_lock;
    spinlock_t netdev_lock;
    struct list_head pkey_list;
    struct ib_port_cache cache;
    struct net_device * netdev;
    netdevice_tracker netdev_tracker;
    struct hlist_node ndev_hash_link;
    struct rdma_port_counter port_counter;
    struct ib_port * sysfs;
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
struct ib_port_data {
    struct ib_device * ib_dev;
    struct ib_port_immutable immutable;
    spinlock_t pkey_list_lock;
    struct list_head pkey_list;
    struct ib_port_cache cache;
    spinlock_t netdev_lock;
    struct net_device * netdev;
    struct hlist_node ndev_hash_link;
    struct rdma_port_counter port_counter;
    struct rdma_hw_stats * hw_stats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct ib_port_data {
    struct ib_device * ib_dev;
    struct ib_port_immutable immutable;
    spinlock_t pkey_list_lock;
    struct list_head pkey_list;
    struct ib_port_cache cache;
    spinlock_t netdev_lock;
    struct net_device * netdev;
    struct hlist_node ndev_hash_link;
    struct rdma_port_counter port_counter;
    struct rdma_hw_stats * hw_stats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct ib_port_data {
    struct ib_device * ib_dev;
    struct ib_port_immutable immutable;
    spinlock_t pkey_list_lock;
    struct list_head pkey_list;
    struct ib_port_cache cache;
    spinlock_t netdev_lock;
    struct net_device * netdev;
    struct hlist_node ndev_hash_link;
    struct rdma_port_counter port_counter;
    struct rdma_hw_stats * hw_stats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct ib_port_data {
    struct ib_device * ib_dev;
    struct ib_port_immutable immutable;
    spinlock_t pkey_list_lock;
    struct list_head pkey_list;
    struct ib_port_cache cache;
    spinlock_t netdev_lock;
    struct net_device * netdev;
    struct hlist_node ndev_hash_link;
    struct rdma_port_counter port_counter;
    struct rdma_hw_stats * hw_stats;
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
struct ib_port_data {
    struct ib_device * ib_dev;
    struct ib_port_immutable immutable;
    spinlock_t pkey_list_lock;
    struct list_head pkey_list;
    struct ib_port_cache cache;
    spinlock_t netdev_lock;
    struct net_device * netdev;
    struct hlist_node ndev_hash_link;
    struct rdma_port_counter port_counter;
    struct rdma_hw_stats * hw_stats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct ib_port_data {
    struct ib_device * ib_dev;
    struct ib_port_immutable immutable;
    spinlock_t pkey_list_lock;
    struct list_head pkey_list;
    struct ib_port_cache cache;
    spinlock_t netdev_lock;
    struct net_device * netdev;
    struct hlist_node ndev_hash_link;
    struct rdma_port_counter port_counter;
    struct rdma_hw_stats * hw_stats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct ib_port_data {
    struct ib_device * ib_dev;
    struct ib_port_immutable immutable;
    spinlock_t pkey_list_lock;
    struct list_head pkey_list;
    struct ib_port_cache cache;
    spinlock_t netdev_lock;
    struct net_device * netdev;
    struct hlist_node ndev_hash_link;
    struct rdma_port_counter port_counter;
    struct rdma_hw_stats * hw_stats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct ib_port_data {
    struct ib_device * ib_dev;
    struct ib_port_immutable immutable;
    spinlock_t pkey_list_lock;
    struct list_head pkey_list;
    struct ib_port_cache cache;
    spinlock_t netdev_lock;
    struct net_device * netdev;
    struct hlist_node ndev_hash_link;
    struct rdma_port_counter port_counter;
    struct rdma_hw_stats * hw_stats;
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
struct ib_port_data {
    struct ib_device * ib_dev;
    struct ib_port_immutable immutable;
    spinlock_t pkey_list_lock;
    struct list_head pkey_list;
    struct ib_port_cache cache;
    spinlock_t netdev_lock;
    struct net_device * netdev;
    struct hlist_node ndev_hash_link;
    struct rdma_port_counter port_counter;
    struct rdma_hw_stats * hw_stats;
}
```
</details>
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
<b>Field added. </b>
<code>struct ib_port * sysfs</code>
</li>
<li>
<b>Field removed. </b>
<code>struct rdma_hw_stats * hw_stats</code>
</li>
</ul>
</details>
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
<code>netdevice_tracker netdev_tracker</code>
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
