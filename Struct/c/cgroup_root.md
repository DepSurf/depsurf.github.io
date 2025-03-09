# Struct: <code>cgroup_root</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct cgroup_root {
    struct kernfs_root * kf_root;
    struct kref kref;
    unsigned int subsys_mask;
    int hierarchy_id;
    struct cgroup cgrp;
    atomic_t nr_cgrps;
    struct list_head root_list;
    unsigned int flags;
    struct idr cgroup_idr;
    char[4096] release_agent_path;
    char[64] name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct cgroup_root {
    struct kernfs_root * kf_root;
    unsigned int subsys_mask;
    int hierarchy_id;
    struct cgroup cgrp;
    int cgrp_ancestor_id_storage;
    atomic_t nr_cgrps;
    struct list_head root_list;
    unsigned int flags;
    struct idr cgroup_idr;
    char[4096] release_agent_path;
    char[64] name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct cgroup_root {
    struct kernfs_root * kf_root;
    unsigned int subsys_mask;
    int hierarchy_id;
    struct cgroup cgrp;
    int cgrp_ancestor_id_storage;
    atomic_t nr_cgrps;
    struct list_head root_list;
    unsigned int flags;
    struct idr cgroup_idr;
    char[4096] release_agent_path;
    char[64] name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct cgroup_root {
    struct kernfs_root * kf_root;
    unsigned int subsys_mask;
    int hierarchy_id;
    struct cgroup cgrp;
    int cgrp_ancestor_id_storage;
    atomic_t nr_cgrps;
    struct list_head root_list;
    unsigned int flags;
    struct idr cgroup_idr;
    char[4096] release_agent_path;
    char[64] name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct cgroup_root {
    struct kernfs_root * kf_root;
    unsigned int subsys_mask;
    int hierarchy_id;
    struct cgroup cgrp;
    int cgrp_ancestor_id_storage;
    atomic_t nr_cgrps;
    struct list_head root_list;
    unsigned int flags;
    struct idr cgroup_idr;
    char[4096] release_agent_path;
    char[64] name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct cgroup_root {
    struct kernfs_root * kf_root;
    unsigned int subsys_mask;
    int hierarchy_id;
    struct cgroup cgrp;
    int cgrp_ancestor_id_storage;
    atomic_t nr_cgrps;
    struct list_head root_list;
    unsigned int flags;
    struct idr cgroup_idr;
    char[4096] release_agent_path;
    char[64] name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct cgroup_root {
    struct kernfs_root * kf_root;
    unsigned int subsys_mask;
    int hierarchy_id;
    struct cgroup cgrp;
    int cgrp_ancestor_id_storage;
    atomic_t nr_cgrps;
    struct list_head root_list;
    unsigned int flags;
    struct idr cgroup_idr;
    char[4096] release_agent_path;
    char[64] name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct cgroup_root {
    struct kernfs_root * kf_root;
    unsigned int subsys_mask;
    int hierarchy_id;
    struct cgroup cgrp;
    int cgrp_ancestor_id_storage;
    atomic_t nr_cgrps;
    struct list_head root_list;
    unsigned int flags;
    struct idr cgroup_idr;
    char[4096] release_agent_path;
    char[64] name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct cgroup_root {
    struct kernfs_root * kf_root;
    unsigned int subsys_mask;
    int hierarchy_id;
    struct cgroup cgrp;
    int cgrp_ancestor_id_storage;
    atomic_t nr_cgrps;
    struct list_head root_list;
    unsigned int flags;
    struct idr cgroup_idr;
    char[4096] release_agent_path;
    char[64] name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct cgroup_root {
    struct kernfs_root * kf_root;
    unsigned int subsys_mask;
    int hierarchy_id;
    struct cgroup cgrp;
    u64 cgrp_ancestor_id_storage;
    atomic_t nr_cgrps;
    struct list_head root_list;
    unsigned int flags;
    char[4096] release_agent_path;
    char[64] name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct cgroup_root {
    struct kernfs_root * kf_root;
    unsigned int subsys_mask;
    int hierarchy_id;
    struct cgroup cgrp;
    u64 cgrp_ancestor_id_storage;
    atomic_t nr_cgrps;
    struct list_head root_list;
    unsigned int flags;
    char[4096] release_agent_path;
    char[64] name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct cgroup_root {
    struct kernfs_root * kf_root;
    unsigned int subsys_mask;
    int hierarchy_id;
    struct cgroup cgrp;
    u64 cgrp_ancestor_id_storage;
    atomic_t nr_cgrps;
    struct list_head root_list;
    unsigned int flags;
    char[4096] release_agent_path;
    char[64] name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct cgroup_root {
    struct kernfs_root * kf_root;
    unsigned int subsys_mask;
    int hierarchy_id;
    struct cgroup cgrp;
    u64 cgrp_ancestor_id_storage;
    atomic_t nr_cgrps;
    struct list_head root_list;
    unsigned int flags;
    char[4096] release_agent_path;
    char[64] name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct cgroup_root {
    struct kernfs_root * kf_root;
    unsigned int subsys_mask;
    int hierarchy_id;
    struct cgroup cgrp;
    u64 cgrp_ancestor_id_storage;
    atomic_t nr_cgrps;
    struct list_head root_list;
    unsigned int flags;
    char[4096] release_agent_path;
    char[64] name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct cgroup_root {
    struct kernfs_root * kf_root;
    unsigned int subsys_mask;
    int hierarchy_id;
    struct cgroup cgrp;
    struct cgroup * cgrp_ancestor_storage;
    atomic_t nr_cgrps;
    struct list_head root_list;
    unsigned int flags;
    char[4096] release_agent_path;
    char[64] name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct cgroup_root {
    struct kernfs_root * kf_root;
    unsigned int subsys_mask;
    int hierarchy_id;
    struct cgroup cgrp;
    struct cgroup * cgrp_ancestor_storage;
    atomic_t nr_cgrps;
    struct list_head root_list;
    unsigned int flags;
    char[4096] release_agent_path;
    char[64] name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct cgroup_root {
    struct kernfs_root * kf_root;
    unsigned int subsys_mask;
    int hierarchy_id;
    struct list_head root_list;
    struct callback_head rcu;
    struct cgroup cgrp;
    struct cgroup * cgrp_ancestor_storage;
    atomic_t nr_cgrps;
    unsigned int flags;
    char[4096] release_agent_path;
    char[64] name;
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
struct cgroup_root {
    struct kernfs_root * kf_root;
    unsigned int subsys_mask;
    int hierarchy_id;
    struct cgroup cgrp;
    int cgrp_ancestor_id_storage;
    atomic_t nr_cgrps;
    struct list_head root_list;
    unsigned int flags;
    struct idr cgroup_idr;
    char[4096] release_agent_path;
    char[64] name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct cgroup_root {
    struct kernfs_root * kf_root;
    unsigned int subsys_mask;
    int hierarchy_id;
    struct cgroup cgrp;
    int cgrp_ancestor_id_storage;
    atomic_t nr_cgrps;
    struct list_head root_list;
    unsigned int flags;
    struct idr cgroup_idr;
    char[4096] release_agent_path;
    char[64] name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct cgroup_root {
    struct kernfs_root * kf_root;
    unsigned int subsys_mask;
    int hierarchy_id;
    struct cgroup cgrp;
    int cgrp_ancestor_id_storage;
    atomic_t nr_cgrps;
    struct list_head root_list;
    unsigned int flags;
    struct idr cgroup_idr;
    char[4096] release_agent_path;
    char[64] name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct cgroup_root {
    struct kernfs_root * kf_root;
    unsigned int subsys_mask;
    int hierarchy_id;
    struct cgroup cgrp;
    int cgrp_ancestor_id_storage;
    atomic_t nr_cgrps;
    struct list_head root_list;
    unsigned int flags;
    struct idr cgroup_idr;
    char[4096] release_agent_path;
    char[64] name;
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
struct cgroup_root {
    struct kernfs_root * kf_root;
    unsigned int subsys_mask;
    int hierarchy_id;
    struct cgroup cgrp;
    int cgrp_ancestor_id_storage;
    atomic_t nr_cgrps;
    struct list_head root_list;
    unsigned int flags;
    struct idr cgroup_idr;
    char[4096] release_agent_path;
    char[64] name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct cgroup_root {
    struct kernfs_root * kf_root;
    unsigned int subsys_mask;
    int hierarchy_id;
    struct cgroup cgrp;
    int cgrp_ancestor_id_storage;
    atomic_t nr_cgrps;
    struct list_head root_list;
    unsigned int flags;
    struct idr cgroup_idr;
    char[4096] release_agent_path;
    char[64] name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct cgroup_root {
    struct kernfs_root * kf_root;
    unsigned int subsys_mask;
    int hierarchy_id;
    struct cgroup cgrp;
    int cgrp_ancestor_id_storage;
    atomic_t nr_cgrps;
    struct list_head root_list;
    unsigned int flags;
    struct idr cgroup_idr;
    char[4096] release_agent_path;
    char[64] name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct cgroup_root {
    struct kernfs_root * kf_root;
    unsigned int subsys_mask;
    int hierarchy_id;
    struct cgroup cgrp;
    int cgrp_ancestor_id_storage;
    atomic_t nr_cgrps;
    struct list_head root_list;
    unsigned int flags;
    struct idr cgroup_idr;
    char[4096] release_agent_path;
    char[64] name;
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int cgrp_ancestor_id_storage</code>
</li>
<li>
<b>Field removed. </b>
<code>struct kref kref</code>
</li>
</ul>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>struct idr cgroup_idr</code>
</li>
<li>
<b>Field type changed. </b>
<code>int cgrp_ancestor_id_storage</code> ➡️ <code>u64 cgrp_ancestor_id_storage</code>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct cgroup * cgrp_ancestor_storage</code>
</li>
<li>
<b>Field removed. </b>
<code>u64 cgrp_ancestor_id_storage</code>
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
<code>struct callback_head rcu</code>
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
