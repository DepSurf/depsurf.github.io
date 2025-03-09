# Struct: <code>nfs_access_entry</code>

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
struct nfs_access_entry {
    struct rb_node rb_node;
    struct list_head lru;
    long unsigned int jiffies;
    struct rpc_cred * cred;
    int mask;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct nfs_access_entry {
    struct rb_node rb_node;
    struct list_head lru;
    long unsigned int jiffies;
    struct rpc_cred * cred;
    int mask;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct nfs_access_entry {
    struct rb_node rb_node;
    struct list_head lru;
    long unsigned int jiffies;
    struct rpc_cred * cred;
    __u32 mask;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct nfs_access_entry {
    struct rb_node rb_node;
    struct list_head lru;
    struct rpc_cred * cred;
    __u32 mask;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct nfs_access_entry {
    struct rb_node rb_node;
    struct list_head lru;
    struct rpc_cred * cred;
    __u32 mask;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct nfs_access_entry {
    struct rb_node rb_node;
    struct list_head lru;
    const struct cred * cred;
    __u32 mask;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct nfs_access_entry {
    struct rb_node rb_node;
    struct list_head lru;
    const struct cred * cred;
    __u32 mask;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct nfs_access_entry {
    struct rb_node rb_node;
    struct list_head lru;
    const struct cred * cred;
    __u32 mask;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct nfs_access_entry {
    struct rb_node rb_node;
    struct list_head lru;
    const struct cred * cred;
    __u32 mask;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct nfs_access_entry {
    struct rb_node rb_node;
    struct list_head lru;
    const struct cred * cred;
    __u32 mask;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct nfs_access_entry {
    struct rb_node rb_node;
    struct list_head lru;
    kuid_t fsuid;
    kgid_t fsgid;
    struct group_info * group_info;
    __u32 mask;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct nfs_access_entry {
    struct rb_node rb_node;
    struct list_head lru;
    kuid_t fsuid;
    kgid_t fsgid;
    struct group_info * group_info;
    u64 timestamp;
    __u32 mask;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct nfs_access_entry {
    struct rb_node rb_node;
    struct list_head lru;
    kuid_t fsuid;
    kgid_t fsgid;
    struct group_info * group_info;
    u64 timestamp;
    __u32 mask;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct nfs_access_entry {
    struct rb_node rb_node;
    struct list_head lru;
    kuid_t fsuid;
    kgid_t fsgid;
    struct group_info * group_info;
    u64 timestamp;
    __u32 mask;
    struct callback_head callback_head;
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
struct nfs_access_entry {
    struct rb_node rb_node;
    struct list_head lru;
    const struct cred * cred;
    __u32 mask;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct nfs_access_entry {
    struct rb_node rb_node;
    struct list_head lru;
    const struct cred * cred;
    __u32 mask;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct nfs_access_entry {
    struct rb_node rb_node;
    struct list_head lru;
    const struct cred * cred;
    __u32 mask;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct nfs_access_entry {
    struct rb_node rb_node;
    struct list_head lru;
    const struct cred * cred;
    __u32 mask;
    struct callback_head callback_head;
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
struct nfs_access_entry {
    struct rb_node rb_node;
    struct list_head lru;
    const struct cred * cred;
    __u32 mask;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct nfs_access_entry {
    struct rb_node rb_node;
    struct list_head lru;
    const struct cred * cred;
    __u32 mask;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct nfs_access_entry {
    struct rb_node rb_node;
    struct list_head lru;
    const struct cred * cred;
    __u32 mask;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct nfs_access_entry {
    struct rb_node rb_node;
    struct list_head lru;
    const struct cred * cred;
    __u32 mask;
    struct callback_head callback_head;
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
struct nfs_access_entry {
    struct rb_node rb_node;
    struct list_head lru;
    long unsigned int jiffies;
    struct rpc_cred * cred;
    int mask;
    struct callback_head callback_head;
}
```
</details>
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
<code>int mask</code> ➡️ <code>__u32 mask</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>long unsigned int jiffies</code>
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
<b>Field type changed. </b>
<code>struct rpc_cred * cred</code> ➡️ <code>const struct cred * cred</code>
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
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
struct nfs_access_entry {
    struct rb_node rb_node;
    struct list_head lru;
    const struct cred * cred;
    __u32 mask;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
struct nfs_access_entry {
    struct rb_node rb_node;
    struct list_head lru;
    const struct cred * cred;
    __u32 mask;
    struct callback_head callback_head;
}
```
</details>
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
<code>kuid_t fsuid</code>
</li>
<li>
<b>Field added. </b>
<code>kgid_t fsgid</code>
</li>
<li>
<b>Field added. </b>
<code>struct group_info * group_info</code>
</li>
<li>
<b>Field removed. </b>
<code>const struct cred * cred</code>
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
<code>u64 timestamp</code>
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
