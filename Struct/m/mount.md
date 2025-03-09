# Struct: <code>mount</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct mount {
    struct hlist_node mnt_hash;
    struct mount * mnt_parent;
    struct dentry * mnt_mountpoint;
    struct vfsmount mnt;
    struct callback_head mnt_rcu;
    struct llist_node mnt_llist;
    struct mnt_pcp * mnt_pcp;
    struct list_head mnt_mounts;
    struct list_head mnt_child;
    struct list_head mnt_instance;
    const char * mnt_devname;
    struct list_head mnt_list;
    struct list_head mnt_expire;
    struct list_head mnt_share;
    struct list_head mnt_slave_list;
    struct list_head mnt_slave;
    struct mount * mnt_master;
    struct mnt_namespace * mnt_ns;
    struct mountpoint * mnt_mp;
    struct hlist_node mnt_mp_list;
    struct hlist_head mnt_fsnotify_marks;
    __u32 mnt_fsnotify_mask;
    int mnt_id;
    int mnt_group_id;
    int mnt_expiry_mark;
    struct hlist_head mnt_pins;
    struct fs_pin mnt_umount;
    struct dentry * mnt_ex_mountpoint;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct mount {
    struct hlist_node mnt_hash;
    struct mount * mnt_parent;
    struct dentry * mnt_mountpoint;
    struct vfsmount mnt;
    struct callback_head mnt_rcu;
    struct llist_node mnt_llist;
    struct mnt_pcp * mnt_pcp;
    struct list_head mnt_mounts;
    struct list_head mnt_child;
    struct list_head mnt_instance;
    const char * mnt_devname;
    struct list_head mnt_list;
    struct list_head mnt_expire;
    struct list_head mnt_share;
    struct list_head mnt_slave_list;
    struct list_head mnt_slave;
    struct mount * mnt_master;
    struct mnt_namespace * mnt_ns;
    struct mountpoint * mnt_mp;
    struct hlist_node mnt_mp_list;
    struct hlist_head mnt_fsnotify_marks;
    __u32 mnt_fsnotify_mask;
    int mnt_id;
    int mnt_group_id;
    int mnt_expiry_mark;
    struct hlist_head mnt_pins;
    struct fs_pin mnt_umount;
    struct dentry * mnt_ex_mountpoint;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct mount {
    struct hlist_node mnt_hash;
    struct mount * mnt_parent;
    struct dentry * mnt_mountpoint;
    struct vfsmount mnt;
    struct callback_head mnt_rcu;
    struct llist_node mnt_llist;
    struct mnt_pcp * mnt_pcp;
    struct list_head mnt_mounts;
    struct list_head mnt_child;
    struct list_head mnt_instance;
    const char * mnt_devname;
    struct list_head mnt_list;
    struct list_head mnt_expire;
    struct list_head mnt_share;
    struct list_head mnt_slave_list;
    struct list_head mnt_slave;
    struct mount * mnt_master;
    struct mnt_namespace * mnt_ns;
    struct mountpoint * mnt_mp;
    struct hlist_node mnt_mp_list;
    struct hlist_head mnt_fsnotify_marks;
    __u32 mnt_fsnotify_mask;
    int mnt_id;
    int mnt_group_id;
    int mnt_expiry_mark;
    struct hlist_head mnt_pins;
    struct fs_pin mnt_umount;
    struct dentry * mnt_ex_mountpoint;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct mount {
    struct hlist_node mnt_hash;
    struct mount * mnt_parent;
    struct dentry * mnt_mountpoint;
    struct vfsmount mnt;
    struct callback_head mnt_rcu;
    struct llist_node mnt_llist;
    struct mnt_pcp * mnt_pcp;
    struct list_head mnt_mounts;
    struct list_head mnt_child;
    struct list_head mnt_instance;
    const char * mnt_devname;
    struct list_head mnt_list;
    struct list_head mnt_expire;
    struct list_head mnt_share;
    struct list_head mnt_slave_list;
    struct list_head mnt_slave;
    struct mount * mnt_master;
    struct mnt_namespace * mnt_ns;
    struct mountpoint * mnt_mp;
    struct hlist_node mnt_mp_list;
    struct list_head mnt_umounting;
    struct fsnotify_mark_connector * mnt_fsnotify_marks;
    __u32 mnt_fsnotify_mask;
    int mnt_id;
    int mnt_group_id;
    int mnt_expiry_mark;
    struct hlist_head mnt_pins;
    struct fs_pin mnt_umount;
    struct dentry * mnt_ex_mountpoint;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct mount {
    struct hlist_node mnt_hash;
    struct mount * mnt_parent;
    struct dentry * mnt_mountpoint;
    struct vfsmount mnt;
    struct callback_head mnt_rcu;
    struct llist_node mnt_llist;
    struct mnt_pcp * mnt_pcp;
    struct list_head mnt_mounts;
    struct list_head mnt_child;
    struct list_head mnt_instance;
    const char * mnt_devname;
    struct list_head mnt_list;
    struct list_head mnt_expire;
    struct list_head mnt_share;
    struct list_head mnt_slave_list;
    struct list_head mnt_slave;
    struct mount * mnt_master;
    struct mnt_namespace * mnt_ns;
    struct mountpoint * mnt_mp;
    struct hlist_node mnt_mp_list;
    struct list_head mnt_umounting;
    struct fsnotify_mark_connector * mnt_fsnotify_marks;
    __u32 mnt_fsnotify_mask;
    int mnt_id;
    int mnt_group_id;
    int mnt_expiry_mark;
    struct hlist_head mnt_pins;
    struct fs_pin mnt_umount;
    struct dentry * mnt_ex_mountpoint;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct mount {
    struct hlist_node mnt_hash;
    struct mount * mnt_parent;
    struct dentry * mnt_mountpoint;
    struct vfsmount mnt;
    struct callback_head mnt_rcu;
    struct llist_node mnt_llist;
    struct mnt_pcp * mnt_pcp;
    struct list_head mnt_mounts;
    struct list_head mnt_child;
    struct list_head mnt_instance;
    const char * mnt_devname;
    struct list_head mnt_list;
    struct list_head mnt_expire;
    struct list_head mnt_share;
    struct list_head mnt_slave_list;
    struct list_head mnt_slave;
    struct mount * mnt_master;
    struct mnt_namespace * mnt_ns;
    struct mountpoint * mnt_mp;
    struct hlist_node mnt_mp_list;
    struct list_head mnt_umounting;
    struct fsnotify_mark_connector * mnt_fsnotify_marks;
    __u32 mnt_fsnotify_mask;
    int mnt_id;
    int mnt_group_id;
    int mnt_expiry_mark;
    struct hlist_head mnt_pins;
    struct fs_pin mnt_umount;
    struct dentry * mnt_ex_mountpoint;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct mount {
    struct hlist_node mnt_hash;
    struct mount * mnt_parent;
    struct dentry * mnt_mountpoint;
    struct vfsmount mnt;
    struct callback_head mnt_rcu;
    struct llist_node mnt_llist;
    struct mnt_pcp * mnt_pcp;
    struct list_head mnt_mounts;
    struct list_head mnt_child;
    struct list_head mnt_instance;
    const char * mnt_devname;
    struct list_head mnt_list;
    struct list_head mnt_expire;
    struct list_head mnt_share;
    struct list_head mnt_slave_list;
    struct list_head mnt_slave;
    struct mount * mnt_master;
    struct mnt_namespace * mnt_ns;
    struct mountpoint * mnt_mp;
    struct hlist_node mnt_mp_list;
    struct list_head mnt_umounting;
    struct fsnotify_mark_connector * mnt_fsnotify_marks;
    __u32 mnt_fsnotify_mask;
    int mnt_id;
    int mnt_group_id;
    int mnt_expiry_mark;
    struct hlist_head mnt_pins;
    struct fs_pin mnt_umount;
    struct dentry * mnt_ex_mountpoint;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct mount {
    struct hlist_node mnt_hash;
    struct mount * mnt_parent;
    struct dentry * mnt_mountpoint;
    struct vfsmount mnt;
    struct callback_head mnt_rcu;
    struct llist_node mnt_llist;
    struct mnt_pcp * mnt_pcp;
    struct list_head mnt_mounts;
    struct list_head mnt_child;
    struct list_head mnt_instance;
    const char * mnt_devname;
    struct list_head mnt_list;
    struct list_head mnt_expire;
    struct list_head mnt_share;
    struct list_head mnt_slave_list;
    struct list_head mnt_slave;
    struct mount * mnt_master;
    struct mnt_namespace * mnt_ns;
    struct mountpoint * mnt_mp;
    struct hlist_node mnt_mp_list;
    struct hlist_node mnt_umount;
    struct list_head mnt_umounting;
    struct fsnotify_mark_connector * mnt_fsnotify_marks;
    __u32 mnt_fsnotify_mask;
    int mnt_id;
    int mnt_group_id;
    int mnt_expiry_mark;
    struct hlist_head mnt_pins;
    struct hlist_head mnt_stuck_children;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct mount {
    struct hlist_node mnt_hash;
    struct mount * mnt_parent;
    struct dentry * mnt_mountpoint;
    struct vfsmount mnt;
    struct callback_head mnt_rcu;
    struct llist_node mnt_llist;
    struct mnt_pcp * mnt_pcp;
    struct list_head mnt_mounts;
    struct list_head mnt_child;
    struct list_head mnt_instance;
    const char * mnt_devname;
    struct list_head mnt_list;
    struct list_head mnt_expire;
    struct list_head mnt_share;
    struct list_head mnt_slave_list;
    struct list_head mnt_slave;
    struct mount * mnt_master;
    struct mnt_namespace * mnt_ns;
    struct mountpoint * mnt_mp;
    struct hlist_node mnt_mp_list;
    struct hlist_node mnt_umount;
    struct list_head mnt_umounting;
    struct fsnotify_mark_connector * mnt_fsnotify_marks;
    __u32 mnt_fsnotify_mask;
    int mnt_id;
    int mnt_group_id;
    int mnt_expiry_mark;
    struct hlist_head mnt_pins;
    struct hlist_head mnt_stuck_children;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct mount {
    struct hlist_node mnt_hash;
    struct mount * mnt_parent;
    struct dentry * mnt_mountpoint;
    struct vfsmount mnt;
    struct callback_head mnt_rcu;
    struct llist_node mnt_llist;
    struct mnt_pcp * mnt_pcp;
    struct list_head mnt_mounts;
    struct list_head mnt_child;
    struct list_head mnt_instance;
    const char * mnt_devname;
    struct list_head mnt_list;
    struct list_head mnt_expire;
    struct list_head mnt_share;
    struct list_head mnt_slave_list;
    struct list_head mnt_slave;
    struct mount * mnt_master;
    struct mnt_namespace * mnt_ns;
    struct mountpoint * mnt_mp;
    struct hlist_node mnt_mp_list;
    struct hlist_node mnt_umount;
    struct list_head mnt_umounting;
    struct fsnotify_mark_connector * mnt_fsnotify_marks;
    __u32 mnt_fsnotify_mask;
    int mnt_id;
    int mnt_group_id;
    int mnt_expiry_mark;
    struct hlist_head mnt_pins;
    struct hlist_head mnt_stuck_children;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct mount {
    struct hlist_node mnt_hash;
    struct mount * mnt_parent;
    struct dentry * mnt_mountpoint;
    struct vfsmount mnt;
    struct callback_head mnt_rcu;
    struct llist_node mnt_llist;
    struct mnt_pcp * mnt_pcp;
    struct list_head mnt_mounts;
    struct list_head mnt_child;
    struct list_head mnt_instance;
    const char * mnt_devname;
    struct list_head mnt_list;
    struct list_head mnt_expire;
    struct list_head mnt_share;
    struct list_head mnt_slave_list;
    struct list_head mnt_slave;
    struct mount * mnt_master;
    struct mnt_namespace * mnt_ns;
    struct mountpoint * mnt_mp;
    struct hlist_node mnt_mp_list;
    struct hlist_node mnt_umount;
    struct list_head mnt_umounting;
    struct fsnotify_mark_connector * mnt_fsnotify_marks;
    __u32 mnt_fsnotify_mask;
    int mnt_id;
    int mnt_group_id;
    int mnt_expiry_mark;
    struct hlist_head mnt_pins;
    struct hlist_head mnt_stuck_children;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct mount {
    struct hlist_node mnt_hash;
    struct mount * mnt_parent;
    struct dentry * mnt_mountpoint;
    struct vfsmount mnt;
    struct callback_head mnt_rcu;
    struct llist_node mnt_llist;
    struct mnt_pcp * mnt_pcp;
    struct list_head mnt_mounts;
    struct list_head mnt_child;
    struct list_head mnt_instance;
    const char * mnt_devname;
    struct list_head mnt_list;
    struct list_head mnt_expire;
    struct list_head mnt_share;
    struct list_head mnt_slave_list;
    struct list_head mnt_slave;
    struct mount * mnt_master;
    struct mnt_namespace * mnt_ns;
    struct mountpoint * mnt_mp;
    struct hlist_node mnt_mp_list;
    struct hlist_node mnt_umount;
    struct list_head mnt_umounting;
    struct fsnotify_mark_connector * mnt_fsnotify_marks;
    __u32 mnt_fsnotify_mask;
    int mnt_id;
    int mnt_group_id;
    int mnt_expiry_mark;
    struct hlist_head mnt_pins;
    struct hlist_head mnt_stuck_children;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct mount {
    struct hlist_node mnt_hash;
    struct mount * mnt_parent;
    struct dentry * mnt_mountpoint;
    struct vfsmount mnt;
    struct callback_head mnt_rcu;
    struct llist_node mnt_llist;
    struct mnt_pcp * mnt_pcp;
    struct list_head mnt_mounts;
    struct list_head mnt_child;
    struct list_head mnt_instance;
    const char * mnt_devname;
    struct list_head mnt_list;
    struct list_head mnt_expire;
    struct list_head mnt_share;
    struct list_head mnt_slave_list;
    struct list_head mnt_slave;
    struct mount * mnt_master;
    struct mnt_namespace * mnt_ns;
    struct mountpoint * mnt_mp;
    struct hlist_node mnt_mp_list;
    struct hlist_node mnt_umount;
    struct list_head mnt_umounting;
    struct fsnotify_mark_connector * mnt_fsnotify_marks;
    __u32 mnt_fsnotify_mask;
    int mnt_id;
    int mnt_group_id;
    int mnt_expiry_mark;
    struct hlist_head mnt_pins;
    struct hlist_head mnt_stuck_children;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct mount {
    struct hlist_node mnt_hash;
    struct mount * mnt_parent;
    struct dentry * mnt_mountpoint;
    struct vfsmount mnt;
    struct callback_head mnt_rcu;
    struct llist_node mnt_llist;
    struct mnt_pcp * mnt_pcp;
    struct list_head mnt_mounts;
    struct list_head mnt_child;
    struct list_head mnt_instance;
    const char * mnt_devname;
    struct list_head mnt_list;
    struct list_head mnt_expire;
    struct list_head mnt_share;
    struct list_head mnt_slave_list;
    struct list_head mnt_slave;
    struct mount * mnt_master;
    struct mnt_namespace * mnt_ns;
    struct mountpoint * mnt_mp;
    struct hlist_node mnt_mp_list;
    struct hlist_node mnt_umount;
    struct list_head mnt_umounting;
    struct fsnotify_mark_connector * mnt_fsnotify_marks;
    __u32 mnt_fsnotify_mask;
    int mnt_id;
    int mnt_group_id;
    int mnt_expiry_mark;
    struct hlist_head mnt_pins;
    struct hlist_head mnt_stuck_children;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct mount {
    struct hlist_node mnt_hash;
    struct mount * mnt_parent;
    struct dentry * mnt_mountpoint;
    struct vfsmount mnt;
    struct callback_head mnt_rcu;
    struct llist_node mnt_llist;
    struct mnt_pcp * mnt_pcp;
    struct list_head mnt_mounts;
    struct list_head mnt_child;
    struct list_head mnt_instance;
    const char * mnt_devname;
    struct list_head mnt_list;
    struct list_head mnt_expire;
    struct list_head mnt_share;
    struct list_head mnt_slave_list;
    struct list_head mnt_slave;
    struct mount * mnt_master;
    struct mnt_namespace * mnt_ns;
    struct mountpoint * mnt_mp;
    struct hlist_node mnt_mp_list;
    struct hlist_node mnt_umount;
    struct list_head mnt_umounting;
    struct fsnotify_mark_connector * mnt_fsnotify_marks;
    __u32 mnt_fsnotify_mask;
    int mnt_id;
    int mnt_group_id;
    int mnt_expiry_mark;
    struct hlist_head mnt_pins;
    struct hlist_head mnt_stuck_children;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct mount {
    struct hlist_node mnt_hash;
    struct mount * mnt_parent;
    struct dentry * mnt_mountpoint;
    struct vfsmount mnt;
    struct callback_head mnt_rcu;
    struct llist_node mnt_llist;
    struct mnt_pcp * mnt_pcp;
    struct list_head mnt_mounts;
    struct list_head mnt_child;
    struct list_head mnt_instance;
    const char * mnt_devname;
    struct list_head mnt_list;
    struct list_head mnt_expire;
    struct list_head mnt_share;
    struct list_head mnt_slave_list;
    struct list_head mnt_slave;
    struct mount * mnt_master;
    struct mnt_namespace * mnt_ns;
    struct mountpoint * mnt_mp;
    struct hlist_node mnt_mp_list;
    struct hlist_node mnt_umount;
    struct list_head mnt_umounting;
    struct fsnotify_mark_connector * mnt_fsnotify_marks;
    __u32 mnt_fsnotify_mask;
    int mnt_id;
    int mnt_group_id;
    int mnt_expiry_mark;
    struct hlist_head mnt_pins;
    struct hlist_head mnt_stuck_children;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct mount {
    struct hlist_node mnt_hash;
    struct mount * mnt_parent;
    struct dentry * mnt_mountpoint;
    struct vfsmount mnt;
    struct callback_head mnt_rcu;
    struct llist_node mnt_llist;
    struct mnt_pcp * mnt_pcp;
    struct list_head mnt_mounts;
    struct list_head mnt_child;
    struct list_head mnt_instance;
    const char * mnt_devname;
    struct rb_node mnt_node;
    struct list_head mnt_list;
    struct list_head mnt_expire;
    struct list_head mnt_share;
    struct list_head mnt_slave_list;
    struct list_head mnt_slave;
    struct mount * mnt_master;
    struct mnt_namespace * mnt_ns;
    struct mountpoint * mnt_mp;
    struct hlist_node mnt_mp_list;
    struct hlist_node mnt_umount;
    struct list_head mnt_umounting;
    struct fsnotify_mark_connector * mnt_fsnotify_marks;
    __u32 mnt_fsnotify_mask;
    int mnt_id;
    u64 mnt_id_unique;
    int mnt_group_id;
    int mnt_expiry_mark;
    struct hlist_head mnt_pins;
    struct hlist_head mnt_stuck_children;
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
struct mount {
    struct hlist_node mnt_hash;
    struct mount * mnt_parent;
    struct dentry * mnt_mountpoint;
    struct vfsmount mnt;
    struct callback_head mnt_rcu;
    struct llist_node mnt_llist;
    struct mnt_pcp * mnt_pcp;
    struct list_head mnt_mounts;
    struct list_head mnt_child;
    struct list_head mnt_instance;
    const char * mnt_devname;
    struct list_head mnt_list;
    struct list_head mnt_expire;
    struct list_head mnt_share;
    struct list_head mnt_slave_list;
    struct list_head mnt_slave;
    struct mount * mnt_master;
    struct mnt_namespace * mnt_ns;
    struct mountpoint * mnt_mp;
    struct hlist_node mnt_mp_list;
    struct hlist_node mnt_umount;
    struct list_head mnt_umounting;
    struct fsnotify_mark_connector * mnt_fsnotify_marks;
    __u32 mnt_fsnotify_mask;
    int mnt_id;
    int mnt_group_id;
    int mnt_expiry_mark;
    struct hlist_head mnt_pins;
    struct hlist_head mnt_stuck_children;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct mount {
    struct hlist_node mnt_hash;
    struct mount * mnt_parent;
    struct dentry * mnt_mountpoint;
    struct vfsmount mnt;
    struct callback_head mnt_rcu;
    struct llist_node mnt_llist;
    struct mnt_pcp * mnt_pcp;
    struct list_head mnt_mounts;
    struct list_head mnt_child;
    struct list_head mnt_instance;
    const char * mnt_devname;
    struct list_head mnt_list;
    struct list_head mnt_expire;
    struct list_head mnt_share;
    struct list_head mnt_slave_list;
    struct list_head mnt_slave;
    struct mount * mnt_master;
    struct mnt_namespace * mnt_ns;
    struct mountpoint * mnt_mp;
    struct hlist_node mnt_mp_list;
    struct hlist_node mnt_umount;
    struct list_head mnt_umounting;
    struct fsnotify_mark_connector * mnt_fsnotify_marks;
    __u32 mnt_fsnotify_mask;
    int mnt_id;
    int mnt_group_id;
    int mnt_expiry_mark;
    struct hlist_head mnt_pins;
    struct hlist_head mnt_stuck_children;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct mount {
    struct hlist_node mnt_hash;
    struct mount * mnt_parent;
    struct dentry * mnt_mountpoint;
    struct vfsmount mnt;
    struct callback_head mnt_rcu;
    struct llist_node mnt_llist;
    struct mnt_pcp * mnt_pcp;
    struct list_head mnt_mounts;
    struct list_head mnt_child;
    struct list_head mnt_instance;
    const char * mnt_devname;
    struct list_head mnt_list;
    struct list_head mnt_expire;
    struct list_head mnt_share;
    struct list_head mnt_slave_list;
    struct list_head mnt_slave;
    struct mount * mnt_master;
    struct mnt_namespace * mnt_ns;
    struct mountpoint * mnt_mp;
    struct hlist_node mnt_mp_list;
    struct hlist_node mnt_umount;
    struct list_head mnt_umounting;
    struct fsnotify_mark_connector * mnt_fsnotify_marks;
    __u32 mnt_fsnotify_mask;
    int mnt_id;
    int mnt_group_id;
    int mnt_expiry_mark;
    struct hlist_head mnt_pins;
    struct hlist_head mnt_stuck_children;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct mount {
    struct hlist_node mnt_hash;
    struct mount * mnt_parent;
    struct dentry * mnt_mountpoint;
    struct vfsmount mnt;
    struct callback_head mnt_rcu;
    struct llist_node mnt_llist;
    struct mnt_pcp * mnt_pcp;
    struct list_head mnt_mounts;
    struct list_head mnt_child;
    struct list_head mnt_instance;
    const char * mnt_devname;
    struct list_head mnt_list;
    struct list_head mnt_expire;
    struct list_head mnt_share;
    struct list_head mnt_slave_list;
    struct list_head mnt_slave;
    struct mount * mnt_master;
    struct mnt_namespace * mnt_ns;
    struct mountpoint * mnt_mp;
    struct hlist_node mnt_mp_list;
    struct hlist_node mnt_umount;
    struct list_head mnt_umounting;
    struct fsnotify_mark_connector * mnt_fsnotify_marks;
    __u32 mnt_fsnotify_mask;
    int mnt_id;
    int mnt_group_id;
    int mnt_expiry_mark;
    struct hlist_head mnt_pins;
    struct hlist_head mnt_stuck_children;
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
struct mount {
    struct hlist_node mnt_hash;
    struct mount * mnt_parent;
    struct dentry * mnt_mountpoint;
    struct vfsmount mnt;
    struct callback_head mnt_rcu;
    struct llist_node mnt_llist;
    struct mnt_pcp * mnt_pcp;
    struct list_head mnt_mounts;
    struct list_head mnt_child;
    struct list_head mnt_instance;
    const char * mnt_devname;
    struct list_head mnt_list;
    struct list_head mnt_expire;
    struct list_head mnt_share;
    struct list_head mnt_slave_list;
    struct list_head mnt_slave;
    struct mount * mnt_master;
    struct mnt_namespace * mnt_ns;
    struct mountpoint * mnt_mp;
    struct hlist_node mnt_mp_list;
    struct hlist_node mnt_umount;
    struct list_head mnt_umounting;
    struct fsnotify_mark_connector * mnt_fsnotify_marks;
    __u32 mnt_fsnotify_mask;
    int mnt_id;
    int mnt_group_id;
    int mnt_expiry_mark;
    struct hlist_head mnt_pins;
    struct hlist_head mnt_stuck_children;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct mount {
    struct hlist_node mnt_hash;
    struct mount * mnt_parent;
    struct dentry * mnt_mountpoint;
    struct vfsmount mnt;
    struct callback_head mnt_rcu;
    struct llist_node mnt_llist;
    struct mnt_pcp * mnt_pcp;
    struct list_head mnt_mounts;
    struct list_head mnt_child;
    struct list_head mnt_instance;
    const char * mnt_devname;
    struct list_head mnt_list;
    struct list_head mnt_expire;
    struct list_head mnt_share;
    struct list_head mnt_slave_list;
    struct list_head mnt_slave;
    struct mount * mnt_master;
    struct mnt_namespace * mnt_ns;
    struct mountpoint * mnt_mp;
    struct hlist_node mnt_mp_list;
    struct hlist_node mnt_umount;
    struct list_head mnt_umounting;
    struct fsnotify_mark_connector * mnt_fsnotify_marks;
    __u32 mnt_fsnotify_mask;
    int mnt_id;
    int mnt_group_id;
    int mnt_expiry_mark;
    struct hlist_head mnt_pins;
    struct hlist_head mnt_stuck_children;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct mount {
    struct hlist_node mnt_hash;
    struct mount * mnt_parent;
    struct dentry * mnt_mountpoint;
    struct vfsmount mnt;
    struct callback_head mnt_rcu;
    struct llist_node mnt_llist;
    struct mnt_pcp * mnt_pcp;
    struct list_head mnt_mounts;
    struct list_head mnt_child;
    struct list_head mnt_instance;
    const char * mnt_devname;
    struct list_head mnt_list;
    struct list_head mnt_expire;
    struct list_head mnt_share;
    struct list_head mnt_slave_list;
    struct list_head mnt_slave;
    struct mount * mnt_master;
    struct mnt_namespace * mnt_ns;
    struct mountpoint * mnt_mp;
    struct hlist_node mnt_mp_list;
    struct hlist_node mnt_umount;
    struct list_head mnt_umounting;
    struct fsnotify_mark_connector * mnt_fsnotify_marks;
    __u32 mnt_fsnotify_mask;
    int mnt_id;
    int mnt_group_id;
    int mnt_expiry_mark;
    struct hlist_head mnt_pins;
    struct hlist_head mnt_stuck_children;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct mount {
    struct hlist_node mnt_hash;
    struct mount * mnt_parent;
    struct dentry * mnt_mountpoint;
    struct vfsmount mnt;
    struct callback_head mnt_rcu;
    struct llist_node mnt_llist;
    struct mnt_pcp * mnt_pcp;
    struct list_head mnt_mounts;
    struct list_head mnt_child;
    struct list_head mnt_instance;
    const char * mnt_devname;
    struct list_head mnt_list;
    struct list_head mnt_expire;
    struct list_head mnt_share;
    struct list_head mnt_slave_list;
    struct list_head mnt_slave;
    struct mount * mnt_master;
    struct mnt_namespace * mnt_ns;
    struct mountpoint * mnt_mp;
    struct hlist_node mnt_mp_list;
    struct hlist_node mnt_umount;
    struct list_head mnt_umounting;
    struct fsnotify_mark_connector * mnt_fsnotify_marks;
    __u32 mnt_fsnotify_mask;
    int mnt_id;
    int mnt_group_id;
    int mnt_expiry_mark;
    struct hlist_head mnt_pins;
    struct hlist_head mnt_stuck_children;
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
<b>Field added. </b>
<code>struct list_head mnt_umounting</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct hlist_head mnt_fsnotify_marks</code> ➡️ <code>struct fsnotify_mark_connector * mnt_fsnotify_marks</code>
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
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct hlist_head mnt_stuck_children</code>
</li>
<li>
<b>Field removed. </b>
<code>struct dentry * mnt_ex_mountpoint</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct fs_pin mnt_umount</code> ➡️ <code>struct hlist_node mnt_umount</code>
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct rb_node mnt_node</code>
</li>
<li>
<b>Field added. </b>
<code>u64 mnt_id_unique</code>
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
