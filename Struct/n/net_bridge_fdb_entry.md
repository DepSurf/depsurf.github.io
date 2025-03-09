# Struct: <code>net_bridge_fdb_entry</code>

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
struct net_bridge_fdb_entry {
    struct hlist_node hlist;
    struct net_bridge_port * dst;
    mac_addr addr;
    __u16 vlan_id;
    unsigned char is_local;
    unsigned char is_static;
    unsigned char added_by_user;
    unsigned char added_by_external_learn;
    unsigned char offloaded;
    long unsigned int updated;
    long unsigned int used;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct net_bridge_fdb_entry {
    struct rhash_head rhnode;
    struct net_bridge_port * dst;
    struct net_bridge_fdb_key key;
    struct hlist_node fdb_node;
    unsigned char is_local;
    unsigned char is_static;
    unsigned char added_by_user;
    unsigned char added_by_external_learn;
    unsigned char offloaded;
    long unsigned int updated;
    long unsigned int used;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct net_bridge_fdb_entry {
    struct rhash_head rhnode;
    struct net_bridge_port * dst;
    struct net_bridge_fdb_key key;
    struct hlist_node fdb_node;
    unsigned char is_local;
    unsigned char is_static;
    unsigned char is_sticky;
    unsigned char added_by_user;
    unsigned char added_by_external_learn;
    unsigned char offloaded;
    long unsigned int updated;
    long unsigned int used;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct net_bridge_fdb_entry {
    struct rhash_head rhnode;
    struct net_bridge_port * dst;
    struct net_bridge_fdb_key key;
    struct hlist_node fdb_node;
    unsigned char is_local;
    unsigned char is_static;
    unsigned char is_sticky;
    unsigned char added_by_user;
    unsigned char added_by_external_learn;
    unsigned char offloaded;
    long unsigned int updated;
    long unsigned int used;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct net_bridge_fdb_entry {
    struct rhash_head rhnode;
    struct net_bridge_port * dst;
    struct net_bridge_fdb_key key;
    struct hlist_node fdb_node;
    unsigned char is_local;
    unsigned char is_static;
    unsigned char is_sticky;
    unsigned char added_by_user;
    unsigned char added_by_external_learn;
    unsigned char offloaded;
    long unsigned int updated;
    long unsigned int used;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct net_bridge_fdb_entry {
    struct rhash_head rhnode;
    struct net_bridge_port * dst;
    struct net_bridge_fdb_key key;
    struct hlist_node fdb_node;
    long unsigned int flags;
    long unsigned int updated;
    long unsigned int used;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct net_bridge_fdb_entry {
    struct rhash_head rhnode;
    struct net_bridge_port * dst;
    struct net_bridge_fdb_key key;
    struct hlist_node fdb_node;
    long unsigned int flags;
    long unsigned int updated;
    long unsigned int used;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct net_bridge_fdb_entry {
    struct rhash_head rhnode;
    struct net_bridge_port * dst;
    struct net_bridge_fdb_key key;
    struct hlist_node fdb_node;
    long unsigned int flags;
    long unsigned int updated;
    long unsigned int used;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct net_bridge_fdb_entry {
    struct rhash_head rhnode;
    struct net_bridge_port * dst;
    struct net_bridge_fdb_key key;
    struct hlist_node fdb_node;
    long unsigned int flags;
    long unsigned int updated;
    long unsigned int used;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct net_bridge_fdb_entry {
    struct rhash_head rhnode;
    struct net_bridge_port * dst;
    struct net_bridge_fdb_key key;
    struct hlist_node fdb_node;
    long unsigned int flags;
    long unsigned int updated;
    long unsigned int used;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct net_bridge_fdb_entry {
    struct rhash_head rhnode;
    struct net_bridge_port * dst;
    struct net_bridge_fdb_key key;
    struct hlist_node fdb_node;
    long unsigned int flags;
    long unsigned int updated;
    long unsigned int used;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct net_bridge_fdb_entry {
    struct rhash_head rhnode;
    struct net_bridge_port * dst;
    struct net_bridge_fdb_key key;
    struct hlist_node fdb_node;
    long unsigned int flags;
    long unsigned int updated;
    long unsigned int used;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct net_bridge_fdb_entry {
    struct rhash_head rhnode;
    struct net_bridge_port * dst;
    struct net_bridge_fdb_key key;
    struct hlist_node fdb_node;
    long unsigned int flags;
    long unsigned int updated;
    long unsigned int used;
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
struct net_bridge_fdb_entry {
    struct rhash_head rhnode;
    struct net_bridge_port * dst;
    struct net_bridge_fdb_key key;
    struct hlist_node fdb_node;
    unsigned char is_local;
    unsigned char is_static;
    unsigned char is_sticky;
    unsigned char added_by_user;
    unsigned char added_by_external_learn;
    unsigned char offloaded;
    long unsigned int updated;
    long unsigned int used;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct net_bridge_fdb_entry {
    struct rhash_head rhnode;
    struct net_bridge_port * dst;
    struct net_bridge_fdb_key key;
    struct hlist_node fdb_node;
    unsigned char is_local;
    unsigned char is_static;
    unsigned char is_sticky;
    unsigned char added_by_user;
    unsigned char added_by_external_learn;
    unsigned char offloaded;
    long unsigned int updated;
    long unsigned int used;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct net_bridge_fdb_entry {
    struct rhash_head rhnode;
    struct net_bridge_port * dst;
    struct net_bridge_fdb_key key;
    struct hlist_node fdb_node;
    unsigned char is_local;
    unsigned char is_static;
    unsigned char is_sticky;
    unsigned char added_by_user;
    unsigned char added_by_external_learn;
    unsigned char offloaded;
    long unsigned int updated;
    long unsigned int used;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct net_bridge_fdb_entry {
    struct rhash_head rhnode;
    struct net_bridge_port * dst;
    struct net_bridge_fdb_key key;
    struct hlist_node fdb_node;
    unsigned char is_local;
    unsigned char is_static;
    unsigned char is_sticky;
    unsigned char added_by_user;
    unsigned char added_by_external_learn;
    unsigned char offloaded;
    long unsigned int updated;
    long unsigned int used;
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
struct net_bridge_fdb_entry {
    struct rhash_head rhnode;
    struct net_bridge_port * dst;
    struct net_bridge_fdb_key key;
    struct hlist_node fdb_node;
    unsigned char is_local;
    unsigned char is_static;
    unsigned char is_sticky;
    unsigned char added_by_user;
    unsigned char added_by_external_learn;
    unsigned char offloaded;
    long unsigned int updated;
    long unsigned int used;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct net_bridge_fdb_entry {
    struct rhash_head rhnode;
    struct net_bridge_port * dst;
    struct net_bridge_fdb_key key;
    struct hlist_node fdb_node;
    unsigned char is_local;
    unsigned char is_static;
    unsigned char is_sticky;
    unsigned char added_by_user;
    unsigned char added_by_external_learn;
    unsigned char offloaded;
    long unsigned int updated;
    long unsigned int used;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct net_bridge_fdb_entry {
    struct rhash_head rhnode;
    struct net_bridge_port * dst;
    struct net_bridge_fdb_key key;
    struct hlist_node fdb_node;
    unsigned char is_local;
    unsigned char is_static;
    unsigned char is_sticky;
    unsigned char added_by_user;
    unsigned char added_by_external_learn;
    unsigned char offloaded;
    long unsigned int updated;
    long unsigned int used;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct net_bridge_fdb_entry {
    struct rhash_head rhnode;
    struct net_bridge_port * dst;
    struct net_bridge_fdb_key key;
    struct hlist_node fdb_node;
    unsigned char is_local;
    unsigned char is_static;
    unsigned char is_sticky;
    unsigned char added_by_user;
    unsigned char added_by_external_learn;
    unsigned char offloaded;
    long unsigned int updated;
    long unsigned int used;
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
<details>
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
struct net_bridge_fdb_entry {
    struct hlist_node hlist;
    struct net_bridge_port * dst;
    mac_addr addr;
    __u16 vlan_id;
    unsigned char is_local;
    unsigned char is_static;
    unsigned char added_by_user;
    unsigned char added_by_external_learn;
    unsigned char offloaded;
    long unsigned int updated;
    long unsigned int used;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct rhash_head rhnode</code>
</li>
<li>
<b>Field added. </b>
<code>struct net_bridge_fdb_key key</code>
</li>
<li>
<b>Field added. </b>
<code>struct hlist_node fdb_node</code>
</li>
<li>
<b>Field removed. </b>
<code>struct hlist_node hlist</code>
</li>
<li>
<b>Field removed. </b>
<code>mac_addr addr</code>
</li>
<li>
<b>Field removed. </b>
<code>__u16 vlan_id</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned char is_sticky</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>long unsigned int flags</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned char is_local</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned char is_static</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned char is_sticky</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned char added_by_user</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned char added_by_external_learn</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned char offloaded</code>
</li>
</ul>
</details>
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
