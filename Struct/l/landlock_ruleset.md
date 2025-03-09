# Struct: <code>landlock_ruleset</code>

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
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
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
struct landlock_ruleset {
    struct rb_root root;
    struct landlock_hierarchy * hierarchy;
    struct work_struct work_free;
    struct mutex lock;
    refcount_t usage;
    u32 num_rules;
    u32 num_layers;
    u16[0] fs_access_masks;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct landlock_ruleset {
    struct rb_root root;
    struct landlock_hierarchy * hierarchy;
    struct work_struct work_free;
    struct mutex lock;
    refcount_t usage;
    u32 num_rules;
    u32 num_layers;
    u16[0] fs_access_masks;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct landlock_ruleset {
    struct rb_root root;
    struct landlock_hierarchy * hierarchy;
    struct work_struct work_free;
    struct mutex lock;
    refcount_t usage;
    u32 num_rules;
    u32 num_layers;
    access_mask_t[0] fs_access_masks;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct landlock_ruleset {
    struct rb_root root;
    struct landlock_hierarchy * hierarchy;
    struct work_struct work_free;
    struct mutex lock;
    refcount_t usage;
    u32 num_rules;
    u32 num_layers;
    access_mask_t[0] fs_access_masks;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct landlock_ruleset {
    struct rb_root root;
    struct landlock_hierarchy * hierarchy;
    struct work_struct work_free;
    struct mutex lock;
    refcount_t usage;
    u32 num_rules;
    u32 num_layers;
    access_mask_t[0] fs_access_masks;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct landlock_ruleset {
    struct rb_root root_inode;
    struct rb_root root_net_port;
    struct landlock_hierarchy * hierarchy;
    struct work_struct work_free;
    struct mutex lock;
    refcount_t usage;
    u32 num_rules;
    u32 num_layers;
    access_masks_t[0] access_masks;
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
struct landlock_ruleset {
    struct rb_root root;
    struct landlock_hierarchy * hierarchy;
    struct work_struct work_free;
    struct mutex lock;
    refcount_t usage;
    u32 num_rules;
    u32 num_layers;
    u16[0] fs_access_masks;
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
<b>Field type changed. </b>
<code>u16[0] fs_access_masks</code> ➡️ <code>access_mask_t[0] fs_access_masks</code>
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
<code>struct rb_root root_inode</code>
</li>
<li>
<b>Field added. </b>
<code>struct rb_root root_net_port</code>
</li>
<li>
<b>Field added. </b>
<code>access_masks_t[0] access_masks</code>
</li>
<li>
<b>Field removed. </b>
<code>struct rb_root root</code>
</li>
<li>
<b>Field removed. </b>
<code>access_mask_t[0] fs_access_masks</code>
</li>
</ul>
</details>
</li>
</ul>
