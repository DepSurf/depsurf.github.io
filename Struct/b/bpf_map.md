# Struct: <code>bpf_map</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct bpf_map {
    atomic_t refcnt;
    enum bpf_map_type map_type;
    u32 key_size;
    u32 value_size;
    u32 max_entries;
    u32 pages;
    struct user_struct * user;
    const struct bpf_map_ops * ops;
    struct work_struct work;
    atomic_t usercnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct bpf_map {
    atomic_t refcnt;
    enum bpf_map_type map_type;
    u32 key_size;
    u32 value_size;
    u32 max_entries;
    u32 map_flags;
    u32 pages;
    struct user_struct * user;
    const struct bpf_map_ops * ops;
    struct work_struct work;
    atomic_t usercnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct bpf_map {
    atomic_t refcnt;
    enum bpf_map_type map_type;
    u32 key_size;
    u32 value_size;
    u32 max_entries;
    u32 map_flags;
    u32 pages;
    struct user_struct * user;
    const struct bpf_map_ops * ops;
    struct work_struct work;
    atomic_t usercnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct bpf_map {
    atomic_t refcnt;
    enum bpf_map_type map_type;
    u32 key_size;
    u32 value_size;
    u32 max_entries;
    u32 map_flags;
    u32 pages;
    u32 id;
    struct user_struct * user;
    const struct bpf_map_ops * ops;
    struct work_struct work;
    atomic_t usercnt;
    struct bpf_map * inner_map_meta;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct bpf_map {
    const struct bpf_map_ops * ops;
    struct bpf_map * inner_map_meta;
    void * security;
    enum bpf_map_type map_type;
    u32 key_size;
    u32 value_size;
    u32 max_entries;
    u32 map_flags;
    u32 pages;
    u32 id;
    int numa_node;
    bool unpriv_array;
    struct user_struct * user;
    atomic_t refcnt;
    atomic_t usercnt;
    struct work_struct work;
    char[16] name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct bpf_map {
    const struct bpf_map_ops * ops;
    struct bpf_map * inner_map_meta;
    void * security;
    enum bpf_map_type map_type;
    u32 key_size;
    u32 value_size;
    u32 max_entries;
    u32 map_flags;
    u32 pages;
    u32 id;
    int numa_node;
    u32 btf_key_type_id;
    u32 btf_value_type_id;
    struct btf * btf;
    bool unpriv_array;
    struct user_struct * user;
    atomic_t refcnt;
    atomic_t usercnt;
    struct work_struct work;
    char[16] name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct bpf_map {
    const struct bpf_map_ops * ops;
    struct bpf_map * inner_map_meta;
    void * security;
    enum bpf_map_type map_type;
    u32 key_size;
    u32 value_size;
    u32 max_entries;
    u32 map_flags;
    u32 pages;
    u32 id;
    int numa_node;
    u32 btf_key_type_id;
    u32 btf_value_type_id;
    struct btf * btf;
    bool unpriv_array;
    struct user_struct * user;
    atomic_t refcnt;
    atomic_t usercnt;
    struct work_struct work;
    char[16] name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct bpf_map {
    const struct bpf_map_ops * ops;
    struct bpf_map * inner_map_meta;
    void * security;
    enum bpf_map_type map_type;
    u32 key_size;
    u32 value_size;
    u32 max_entries;
    u32 map_flags;
    int spin_lock_off;
    u32 id;
    int numa_node;
    u32 btf_key_type_id;
    u32 btf_value_type_id;
    struct btf * btf;
    struct bpf_map_memory memory;
    bool unpriv_array;
    bool frozen;
    atomic_t refcnt;
    atomic_t usercnt;
    struct work_struct work;
    char[16] name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct bpf_map {
    const struct bpf_map_ops * ops;
    struct bpf_map * inner_map_meta;
    void * security;
    enum bpf_map_type map_type;
    u32 key_size;
    u32 value_size;
    u32 max_entries;
    u32 map_flags;
    int spin_lock_off;
    u32 id;
    int numa_node;
    u32 btf_key_type_id;
    u32 btf_value_type_id;
    struct btf * btf;
    struct bpf_map_memory memory;
    bool unpriv_array;
    bool frozen;
    atomic_t refcnt;
    atomic_t usercnt;
    struct work_struct work;
    char[16] name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct bpf_map {
    const struct bpf_map_ops * ops;
    struct bpf_map * inner_map_meta;
    void * security;
    enum bpf_map_type map_type;
    u32 key_size;
    u32 value_size;
    u32 max_entries;
    u32 map_flags;
    int spin_lock_off;
    u32 id;
    int numa_node;
    u32 btf_key_type_id;
    u32 btf_value_type_id;
    struct btf * btf;
    struct bpf_map_memory memory;
    char[16] name;
    u32 btf_vmlinux_value_type_id;
    bool bypass_spec_v1;
    bool frozen;
    atomic64_t refcnt;
    atomic64_t usercnt;
    struct work_struct work;
    struct mutex freeze_mutex;
    u64 writecnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct bpf_map {
    const struct bpf_map_ops * ops;
    struct bpf_map * inner_map_meta;
    void * security;
    enum bpf_map_type map_type;
    u32 key_size;
    u32 value_size;
    u32 max_entries;
    u32 map_flags;
    int spin_lock_off;
    u32 id;
    int numa_node;
    u32 btf_key_type_id;
    u32 btf_value_type_id;
    struct btf * btf;
    struct mem_cgroup * memcg;
    char[16] name;
    u32 btf_vmlinux_value_type_id;
    bool bypass_spec_v1;
    bool frozen;
    atomic64_t refcnt;
    atomic64_t usercnt;
    struct work_struct work;
    struct mutex freeze_mutex;
    u64 writecnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct bpf_map {
    const struct bpf_map_ops * ops;
    struct bpf_map * inner_map_meta;
    void * security;
    enum bpf_map_type map_type;
    u32 key_size;
    u32 value_size;
    u32 max_entries;
    u32 map_flags;
    int spin_lock_off;
    u32 id;
    int numa_node;
    u32 btf_key_type_id;
    u32 btf_value_type_id;
    struct btf * btf;
    struct mem_cgroup * memcg;
    char[16] name;
    u32 btf_vmlinux_value_type_id;
    bool bypass_spec_v1;
    bool frozen;
    atomic64_t refcnt;
    atomic64_t usercnt;
    struct work_struct work;
    struct mutex freeze_mutex;
    u64 writecnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct bpf_map {
    const struct bpf_map_ops * ops;
    struct bpf_map * inner_map_meta;
    void * security;
    enum bpf_map_type map_type;
    u32 key_size;
    u32 value_size;
    u32 max_entries;
    u32 map_flags;
    int spin_lock_off;
    int timer_off;
    u32 id;
    int numa_node;
    u32 btf_key_type_id;
    u32 btf_value_type_id;
    struct btf * btf;
    struct mem_cgroup * memcg;
    char[16] name;
    u32 btf_vmlinux_value_type_id;
    bool bypass_spec_v1;
    bool frozen;
    atomic64_t refcnt;
    atomic64_t usercnt;
    struct work_struct work;
    struct mutex freeze_mutex;
    atomic64_t writecnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct bpf_map {
    const struct bpf_map_ops * ops;
    struct bpf_map * inner_map_meta;
    void * security;
    enum bpf_map_type map_type;
    u32 key_size;
    u32 value_size;
    u32 max_entries;
    u64 map_extra;
    u32 map_flags;
    int spin_lock_off;
    struct bpf_map_value_off * kptr_off_tab;
    int timer_off;
    u32 id;
    int numa_node;
    u32 btf_key_type_id;
    u32 btf_value_type_id;
    u32 btf_vmlinux_value_type_id;
    struct btf * btf;
    struct mem_cgroup * memcg;
    char[16] name;
    struct bpf_map_off_arr * off_arr;
    atomic64_t refcnt;
    atomic64_t usercnt;
    struct work_struct work;
    struct mutex freeze_mutex;
    atomic64_t writecnt;
    struct (anon) owner;
    bool bypass_spec_v1;
    bool frozen;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct bpf_map {
    const struct bpf_map_ops * ops;
    struct bpf_map * inner_map_meta;
    void * security;
    enum bpf_map_type map_type;
    u32 key_size;
    u32 value_size;
    u32 max_entries;
    u64 map_extra;
    u32 map_flags;
    u32 id;
    struct btf_record * record;
    int numa_node;
    u32 btf_key_type_id;
    u32 btf_value_type_id;
    u32 btf_vmlinux_value_type_id;
    struct btf * btf;
    struct obj_cgroup * objcg;
    char[16] name;
    struct btf_field_offs * field_offs;
    atomic64_t refcnt;
    atomic64_t usercnt;
    struct work_struct work;
    struct mutex freeze_mutex;
    atomic64_t writecnt;
    struct (anon) owner;
    bool bypass_spec_v1;
    bool frozen;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct bpf_map {
    const struct bpf_map_ops * ops;
    struct bpf_map * inner_map_meta;
    void * security;
    enum bpf_map_type map_type;
    u32 key_size;
    u32 value_size;
    u32 max_entries;
    u64 map_extra;
    u32 map_flags;
    u32 id;
    struct btf_record * record;
    int numa_node;
    u32 btf_key_type_id;
    u32 btf_value_type_id;
    u32 btf_vmlinux_value_type_id;
    struct btf * btf;
    struct obj_cgroup * objcg;
    char[16] name;
    atomic64_t refcnt;
    atomic64_t usercnt;
    struct work_struct work;
    struct mutex freeze_mutex;
    atomic64_t writecnt;
    struct (anon) owner;
    bool bypass_spec_v1;
    bool frozen;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct bpf_map {
    const struct bpf_map_ops * ops;
    struct bpf_map * inner_map_meta;
    void * security;
    enum bpf_map_type map_type;
    u32 key_size;
    u32 value_size;
    u32 max_entries;
    u64 map_extra;
    u32 map_flags;
    u32 id;
    struct btf_record * record;
    int numa_node;
    u32 btf_key_type_id;
    u32 btf_value_type_id;
    u32 btf_vmlinux_value_type_id;
    struct btf * btf;
    struct obj_cgroup * objcg;
    char[16] name;
    atomic64_t refcnt;
    atomic64_t usercnt;
    struct work_struct work;
    struct callback_head rcu;
    struct mutex freeze_mutex;
    atomic64_t writecnt;
    struct (anon) owner;
    bool bypass_spec_v1;
    bool frozen;
    bool free_after_mult_rcu_gp;
    bool free_after_rcu_gp;
    atomic64_t sleepable_refcnt;
    s64 * elem_count;
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
struct bpf_map {
    const struct bpf_map_ops * ops;
    struct bpf_map * inner_map_meta;
    void * security;
    enum bpf_map_type map_type;
    u32 key_size;
    u32 value_size;
    u32 max_entries;
    u32 map_flags;
    int spin_lock_off;
    u32 id;
    int numa_node;
    u32 btf_key_type_id;
    u32 btf_value_type_id;
    struct btf * btf;
    struct bpf_map_memory memory;
    bool unpriv_array;
    bool frozen;
    atomic_t refcnt;
    atomic_t usercnt;
    struct work_struct work;
    char[16] name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct bpf_map {
    const struct bpf_map_ops * ops;
    struct bpf_map * inner_map_meta;
    void * security;
    enum bpf_map_type map_type;
    u32 key_size;
    u32 value_size;
    u32 max_entries;
    u32 map_flags;
    int spin_lock_off;
    u32 id;
    int numa_node;
    u32 btf_key_type_id;
    u32 btf_value_type_id;
    struct btf * btf;
    struct bpf_map_memory memory;
    bool unpriv_array;
    bool frozen;
    atomic_t refcnt;
    atomic_t usercnt;
    struct work_struct work;
    char[16] name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct bpf_map {
    const struct bpf_map_ops * ops;
    struct bpf_map * inner_map_meta;
    void * security;
    enum bpf_map_type map_type;
    u32 key_size;
    u32 value_size;
    u32 max_entries;
    u32 map_flags;
    int spin_lock_off;
    u32 id;
    int numa_node;
    u32 btf_key_type_id;
    u32 btf_value_type_id;
    struct btf * btf;
    struct bpf_map_memory memory;
    bool unpriv_array;
    bool frozen;
    atomic_t refcnt;
    atomic_t usercnt;
    struct work_struct work;
    char[16] name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct bpf_map {
    const struct bpf_map_ops * ops;
    struct bpf_map * inner_map_meta;
    void * security;
    enum bpf_map_type map_type;
    u32 key_size;
    u32 value_size;
    u32 max_entries;
    u32 map_flags;
    int spin_lock_off;
    u32 id;
    int numa_node;
    u32 btf_key_type_id;
    u32 btf_value_type_id;
    struct btf * btf;
    struct bpf_map_memory memory;
    bool unpriv_array;
    bool frozen;
    atomic_t refcnt;
    atomic_t usercnt;
    struct work_struct work;
    char[16] name;
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
struct bpf_map {
    const struct bpf_map_ops * ops;
    struct bpf_map * inner_map_meta;
    void * security;
    enum bpf_map_type map_type;
    u32 key_size;
    u32 value_size;
    u32 max_entries;
    u32 map_flags;
    int spin_lock_off;
    u32 id;
    int numa_node;
    u32 btf_key_type_id;
    u32 btf_value_type_id;
    struct btf * btf;
    struct bpf_map_memory memory;
    bool unpriv_array;
    bool frozen;
    atomic_t refcnt;
    atomic_t usercnt;
    struct work_struct work;
    char[16] name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct bpf_map {
    const struct bpf_map_ops * ops;
    struct bpf_map * inner_map_meta;
    void * security;
    enum bpf_map_type map_type;
    u32 key_size;
    u32 value_size;
    u32 max_entries;
    u32 map_flags;
    int spin_lock_off;
    u32 id;
    int numa_node;
    u32 btf_key_type_id;
    u32 btf_value_type_id;
    struct btf * btf;
    struct bpf_map_memory memory;
    bool unpriv_array;
    bool frozen;
    atomic_t refcnt;
    atomic_t usercnt;
    struct work_struct work;
    char[16] name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct bpf_map {
    const struct bpf_map_ops * ops;
    struct bpf_map * inner_map_meta;
    void * security;
    enum bpf_map_type map_type;
    u32 key_size;
    u32 value_size;
    u32 max_entries;
    u32 map_flags;
    int spin_lock_off;
    u32 id;
    int numa_node;
    u32 btf_key_type_id;
    u32 btf_value_type_id;
    struct btf * btf;
    struct bpf_map_memory memory;
    bool unpriv_array;
    bool frozen;
    atomic_t refcnt;
    atomic_t usercnt;
    struct work_struct work;
    char[16] name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct bpf_map {
    const struct bpf_map_ops * ops;
    struct bpf_map * inner_map_meta;
    void * security;
    enum bpf_map_type map_type;
    u32 key_size;
    u32 value_size;
    u32 max_entries;
    u32 map_flags;
    int spin_lock_off;
    u32 id;
    int numa_node;
    u32 btf_key_type_id;
    u32 btf_value_type_id;
    struct btf * btf;
    struct bpf_map_memory memory;
    bool unpriv_array;
    bool frozen;
    atomic_t refcnt;
    atomic_t usercnt;
    struct work_struct work;
    char[16] name;
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
<code>u32 map_flags</code>
</li>
</ul>
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
<b>Field added. </b>
<code>u32 id</code>
</li>
<li>
<b>Field added. </b>
<code>struct bpf_map * inner_map_meta</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>void * security</code>
</li>
<li>
<b>Field added. </b>
<code>int numa_node</code>
</li>
<li>
<b>Field added. </b>
<code>bool unpriv_array</code>
</li>
<li>
<b>Field added. </b>
<code>char[16] name</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u32 btf_key_type_id</code>
</li>
<li>
<b>Field added. </b>
<code>u32 btf_value_type_id</code>
</li>
<li>
<b>Field added. </b>
<code>struct btf * btf</code>
</li>
</ul>
</details>
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
<code>int spin_lock_off</code>
</li>
<li>
<b>Field added. </b>
<code>struct bpf_map_memory memory</code>
</li>
<li>
<b>Field added. </b>
<code>bool frozen</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 pages</code>
</li>
<li>
<b>Field removed. </b>
<code>struct user_struct * user</code>
</li>
</ul>
</details>
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
<code>u32 btf_vmlinux_value_type_id</code>
</li>
<li>
<b>Field added. </b>
<code>bool bypass_spec_v1</code>
</li>
<li>
<b>Field added. </b>
<code>struct mutex freeze_mutex</code>
</li>
<li>
<b>Field added. </b>
<code>u64 writecnt</code>
</li>
<li>
<b>Field removed. </b>
<code>bool unpriv_array</code>
</li>
<li>
<b>Field type changed. </b>
<code>atomic_t refcnt</code> ➡️ <code>atomic64_t refcnt</code>
</li>
<li>
<b>Field type changed. </b>
<code>atomic_t usercnt</code> ➡️ <code>atomic64_t usercnt</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct mem_cgroup * memcg</code>
</li>
<li>
<b>Field removed. </b>
<code>struct bpf_map_memory memory</code>
</li>
</ul>
</details>
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
<code>int timer_off</code>
</li>
<li>
<b>Field type changed. </b>
<code>u64 writecnt</code> ➡️ <code>atomic64_t writecnt</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u64 map_extra</code>
</li>
<li>
<b>Field added. </b>
<code>struct bpf_map_value_off * kptr_off_tab</code>
</li>
<li>
<b>Field added. </b>
<code>struct bpf_map_off_arr * off_arr</code>
</li>
<li>
<b>Field added. </b>
<code>struct (anon) owner</code>
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
<code>struct btf_record * record</code>
</li>
<li>
<b>Field added. </b>
<code>struct obj_cgroup * objcg</code>
</li>
<li>
<b>Field added. </b>
<code>struct btf_field_offs * field_offs</code>
</li>
<li>
<b>Field removed. </b>
<code>int spin_lock_off</code>
</li>
<li>
<b>Field removed. </b>
<code>struct bpf_map_value_off * kptr_off_tab</code>
</li>
<li>
<b>Field removed. </b>
<code>int timer_off</code>
</li>
<li>
<b>Field removed. </b>
<code>struct mem_cgroup * memcg</code>
</li>
<li>
<b>Field removed. </b>
<code>struct bpf_map_off_arr * off_arr</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>struct btf_field_offs * field_offs</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct callback_head rcu</code>
</li>
<li>
<b>Field added. </b>
<code>bool free_after_mult_rcu_gp</code>
</li>
<li>
<b>Field added. </b>
<code>bool free_after_rcu_gp</code>
</li>
<li>
<b>Field added. </b>
<code>atomic64_t sleepable_refcnt</code>
</li>
<li>
<b>Field added. </b>
<code>s64 * elem_count</code>
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
