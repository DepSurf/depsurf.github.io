# Struct: <code>neigh_parms</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct neigh_parms {
    possible_net_t net;
    struct net_device * dev;
    struct list_head list;
    int (*)(struct neighbour *) neigh_setup;
    void (*)(struct neighbour *) neigh_cleanup;
    struct neigh_table * tbl;
    void * sysctl_table;
    int dead;
    atomic_t refcnt;
    struct callback_head callback_head;
    int reachable_time;
    int[13] data;
    long unsigned int[1] data_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct neigh_parms {
    possible_net_t net;
    struct net_device * dev;
    struct list_head list;
    int (*)(struct neighbour *) neigh_setup;
    void (*)(struct neighbour *) neigh_cleanup;
    struct neigh_table * tbl;
    void * sysctl_table;
    int dead;
    atomic_t refcnt;
    struct callback_head callback_head;
    int reachable_time;
    int[13] data;
    long unsigned int[1] data_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct neigh_parms {
    possible_net_t net;
    struct net_device * dev;
    struct list_head list;
    int (*)(struct neighbour *) neigh_setup;
    void (*)(struct neighbour *) neigh_cleanup;
    struct neigh_table * tbl;
    void * sysctl_table;
    int dead;
    atomic_t refcnt;
    struct callback_head callback_head;
    int reachable_time;
    int[13] data;
    long unsigned int[1] data_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct neigh_parms {
    possible_net_t net;
    struct net_device * dev;
    struct list_head list;
    int (*)(struct neighbour *) neigh_setup;
    void (*)(struct neighbour *) neigh_cleanup;
    struct neigh_table * tbl;
    void * sysctl_table;
    int dead;
    refcount_t refcnt;
    struct callback_head callback_head;
    int reachable_time;
    int[13] data;
    long unsigned int[1] data_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct neigh_parms {
    possible_net_t net;
    struct net_device * dev;
    struct list_head list;
    int (*)(struct neighbour *) neigh_setup;
    void (*)(struct neighbour *) neigh_cleanup;
    struct neigh_table * tbl;
    void * sysctl_table;
    int dead;
    refcount_t refcnt;
    struct callback_head callback_head;
    int reachable_time;
    int[13] data;
    long unsigned int[1] data_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct neigh_parms {
    possible_net_t net;
    struct net_device * dev;
    struct list_head list;
    int (*)(struct neighbour *) neigh_setup;
    void (*)(struct neighbour *) neigh_cleanup;
    struct neigh_table * tbl;
    void * sysctl_table;
    int dead;
    refcount_t refcnt;
    struct callback_head callback_head;
    int reachable_time;
    int[13] data;
    long unsigned int[1] data_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct neigh_parms {
    possible_net_t net;
    struct net_device * dev;
    struct list_head list;
    int (*)(struct neighbour *) neigh_setup;
    void (*)(struct neighbour *) neigh_cleanup;
    struct neigh_table * tbl;
    void * sysctl_table;
    int dead;
    refcount_t refcnt;
    struct callback_head callback_head;
    int reachable_time;
    int[13] data;
    long unsigned int[1] data_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct neigh_parms {
    possible_net_t net;
    struct net_device * dev;
    struct list_head list;
    int (*)(struct neighbour *) neigh_setup;
    void (*)(struct neighbour *) neigh_cleanup;
    struct neigh_table * tbl;
    void * sysctl_table;
    int dead;
    refcount_t refcnt;
    struct callback_head callback_head;
    int reachable_time;
    int[13] data;
    long unsigned int[1] data_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct neigh_parms {
    possible_net_t net;
    struct net_device * dev;
    struct list_head list;
    int (*)(struct neighbour *) neigh_setup;
    struct neigh_table * tbl;
    void * sysctl_table;
    int dead;
    refcount_t refcnt;
    struct callback_head callback_head;
    int reachable_time;
    int[13] data;
    long unsigned int[1] data_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct neigh_parms {
    possible_net_t net;
    struct net_device * dev;
    struct list_head list;
    int (*)(struct neighbour *) neigh_setup;
    struct neigh_table * tbl;
    void * sysctl_table;
    int dead;
    refcount_t refcnt;
    struct callback_head callback_head;
    int reachable_time;
    int[13] data;
    long unsigned int[1] data_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct neigh_parms {
    possible_net_t net;
    struct net_device * dev;
    struct list_head list;
    int (*)(struct neighbour *) neigh_setup;
    struct neigh_table * tbl;
    void * sysctl_table;
    int dead;
    refcount_t refcnt;
    struct callback_head callback_head;
    int reachable_time;
    int[13] data;
    long unsigned int[1] data_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct neigh_parms {
    possible_net_t net;
    struct net_device * dev;
    struct list_head list;
    int (*)(struct neighbour *) neigh_setup;
    struct neigh_table * tbl;
    void * sysctl_table;
    int dead;
    refcount_t refcnt;
    struct callback_head callback_head;
    int reachable_time;
    int[13] data;
    long unsigned int[1] data_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct neigh_parms {
    possible_net_t net;
    struct net_device * dev;
    struct list_head list;
    int (*)(struct neighbour *) neigh_setup;
    struct neigh_table * tbl;
    void * sysctl_table;
    int dead;
    refcount_t refcnt;
    struct callback_head callback_head;
    int reachable_time;
    int[13] data;
    long unsigned int[1] data_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct neigh_parms {
    possible_net_t net;
    struct net_device * dev;
    netdevice_tracker dev_tracker;
    struct list_head list;
    int (*)(struct neighbour *) neigh_setup;
    struct neigh_table * tbl;
    void * sysctl_table;
    int dead;
    refcount_t refcnt;
    struct callback_head callback_head;
    int reachable_time;
    int[13] data;
    long unsigned int[1] data_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct neigh_parms {
    possible_net_t net;
    struct net_device * dev;
    netdevice_tracker dev_tracker;
    struct list_head list;
    int (*)(struct neighbour *) neigh_setup;
    struct neigh_table * tbl;
    void * sysctl_table;
    int dead;
    refcount_t refcnt;
    struct callback_head callback_head;
    int reachable_time;
    u32 qlen;
    int[14] data;
    long unsigned int[1] data_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct neigh_parms {
    possible_net_t net;
    struct net_device * dev;
    netdevice_tracker dev_tracker;
    struct list_head list;
    int (*)(struct neighbour *) neigh_setup;
    struct neigh_table * tbl;
    void * sysctl_table;
    int dead;
    refcount_t refcnt;
    struct callback_head callback_head;
    int reachable_time;
    u32 qlen;
    int[14] data;
    long unsigned int[1] data_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct neigh_parms {
    possible_net_t net;
    struct net_device * dev;
    netdevice_tracker dev_tracker;
    struct list_head list;
    int (*)(struct neighbour *) neigh_setup;
    struct neigh_table * tbl;
    void * sysctl_table;
    int dead;
    refcount_t refcnt;
    struct callback_head callback_head;
    int reachable_time;
    u32 qlen;
    int[14] data;
    long unsigned int[1] data_state;
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
struct neigh_parms {
    possible_net_t net;
    struct net_device * dev;
    struct list_head list;
    int (*)(struct neighbour *) neigh_setup;
    struct neigh_table * tbl;
    void * sysctl_table;
    int dead;
    refcount_t refcnt;
    struct callback_head callback_head;
    int reachable_time;
    int[13] data;
    long unsigned int[1] data_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct neigh_parms {
    possible_net_t net;
    struct net_device * dev;
    struct list_head list;
    int (*)(struct neighbour *) neigh_setup;
    struct neigh_table * tbl;
    void * sysctl_table;
    int dead;
    refcount_t refcnt;
    struct callback_head callback_head;
    int reachable_time;
    int[13] data;
    long unsigned int[1] data_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct neigh_parms {
    possible_net_t net;
    struct net_device * dev;
    struct list_head list;
    int (*)(struct neighbour *) neigh_setup;
    struct neigh_table * tbl;
    void * sysctl_table;
    int dead;
    refcount_t refcnt;
    struct callback_head callback_head;
    int reachable_time;
    int[13] data;
    long unsigned int[1] data_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct neigh_parms {
    possible_net_t net;
    struct net_device * dev;
    struct list_head list;
    int (*)(struct neighbour *) neigh_setup;
    struct neigh_table * tbl;
    void * sysctl_table;
    int dead;
    refcount_t refcnt;
    struct callback_head callback_head;
    int reachable_time;
    int[13] data;
    long unsigned int[1] data_state;
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
struct neigh_parms {
    possible_net_t net;
    struct net_device * dev;
    struct list_head list;
    int (*)(struct neighbour *) neigh_setup;
    struct neigh_table * tbl;
    void * sysctl_table;
    int dead;
    refcount_t refcnt;
    struct callback_head callback_head;
    int reachable_time;
    int[13] data;
    long unsigned int[1] data_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct neigh_parms {
    possible_net_t net;
    struct net_device * dev;
    struct list_head list;
    int (*)(struct neighbour *) neigh_setup;
    struct neigh_table * tbl;
    void * sysctl_table;
    int dead;
    refcount_t refcnt;
    struct callback_head callback_head;
    int reachable_time;
    int[13] data;
    long unsigned int[1] data_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct neigh_parms {
    possible_net_t net;
    struct net_device * dev;
    struct list_head list;
    int (*)(struct neighbour *) neigh_setup;
    struct neigh_table * tbl;
    void * sysctl_table;
    int dead;
    refcount_t refcnt;
    struct callback_head callback_head;
    int reachable_time;
    int[13] data;
    long unsigned int[1] data_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct neigh_parms {
    possible_net_t net;
    struct net_device * dev;
    struct list_head list;
    int (*)(struct neighbour *) neigh_setup;
    struct neigh_table * tbl;
    void * sysctl_table;
    int dead;
    refcount_t refcnt;
    struct callback_head callback_head;
    int reachable_time;
    int[13] data;
    long unsigned int[1] data_state;
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
<b>Field type changed. </b>
<code>atomic_t refcnt</code> ➡️ <code>refcount_t refcnt</code>
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
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>void (*)(struct neighbour *) neigh_cleanup</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>netdevice_tracker dev_tracker</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u32 qlen</code>
</li>
<li>
<b>Field type changed. </b>
<code>int[13] data</code> ➡️ <code>int[14] data</code>
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
