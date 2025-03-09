# Struct: <code>user_namespace</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct user_namespace {
    struct uid_gid_map uid_map;
    struct uid_gid_map gid_map;
    struct uid_gid_map projid_map;
    atomic_t count;
    struct user_namespace * parent;
    int level;
    kuid_t owner;
    kgid_t group;
    struct ns_common ns;
    long unsigned int flags;
    struct key * persistent_keyring_register;
    struct rw_semaphore persistent_keyring_register_sem;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct user_namespace {
    struct uid_gid_map uid_map;
    struct uid_gid_map gid_map;
    struct uid_gid_map projid_map;
    atomic_t count;
    struct user_namespace * parent;
    int level;
    kuid_t owner;
    kgid_t group;
    struct ns_common ns;
    long unsigned int flags;
    struct key * persistent_keyring_register;
    struct rw_semaphore persistent_keyring_register_sem;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct user_namespace {
    struct uid_gid_map uid_map;
    struct uid_gid_map gid_map;
    struct uid_gid_map projid_map;
    atomic_t count;
    struct user_namespace * parent;
    int level;
    kuid_t owner;
    kgid_t group;
    struct ns_common ns;
    long unsigned int flags;
    struct key * persistent_keyring_register;
    struct rw_semaphore persistent_keyring_register_sem;
    struct work_struct work;
    struct ctl_table_set set;
    struct ctl_table_header * sysctls;
    struct ucounts * ucounts;
    int[7] ucount_max;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct user_namespace {
    struct uid_gid_map uid_map;
    struct uid_gid_map gid_map;
    struct uid_gid_map projid_map;
    atomic_t count;
    struct user_namespace * parent;
    int level;
    kuid_t owner;
    kgid_t group;
    struct ns_common ns;
    long unsigned int flags;
    struct key * persistent_keyring_register;
    struct rw_semaphore persistent_keyring_register_sem;
    struct work_struct work;
    struct ctl_table_set set;
    struct ctl_table_header * sysctls;
    struct ucounts * ucounts;
    int[9] ucount_max;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct user_namespace {
    struct uid_gid_map uid_map;
    struct uid_gid_map gid_map;
    struct uid_gid_map projid_map;
    atomic_t count;
    struct user_namespace * parent;
    int level;
    kuid_t owner;
    kgid_t group;
    struct ns_common ns;
    long unsigned int flags;
    struct key * persistent_keyring_register;
    struct rw_semaphore persistent_keyring_register_sem;
    struct work_struct work;
    struct ctl_table_set set;
    struct ctl_table_header * sysctls;
    struct ucounts * ucounts;
    int[9] ucount_max;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct user_namespace {
    struct uid_gid_map uid_map;
    struct uid_gid_map gid_map;
    struct uid_gid_map projid_map;
    atomic_t count;
    struct user_namespace * parent;
    int level;
    kuid_t owner;
    kgid_t group;
    struct ns_common ns;
    long unsigned int flags;
    struct key * persistent_keyring_register;
    struct rw_semaphore persistent_keyring_register_sem;
    struct work_struct work;
    struct ctl_table_set set;
    struct ctl_table_header * sysctls;
    struct ucounts * ucounts;
    int[9] ucount_max;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct user_namespace {
    struct uid_gid_map uid_map;
    struct uid_gid_map gid_map;
    struct uid_gid_map projid_map;
    atomic_t count;
    struct user_namespace * parent;
    int level;
    kuid_t owner;
    kgid_t group;
    struct ns_common ns;
    long unsigned int flags;
    struct key * persistent_keyring_register;
    struct rw_semaphore persistent_keyring_register_sem;
    struct work_struct work;
    struct ctl_table_set set;
    struct ctl_table_header * sysctls;
    struct ucounts * ucounts;
    int[9] ucount_max;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct user_namespace {
    struct uid_gid_map uid_map;
    struct uid_gid_map gid_map;
    struct uid_gid_map projid_map;
    atomic_t count;
    struct user_namespace * parent;
    int level;
    kuid_t owner;
    kgid_t group;
    struct ns_common ns;
    long unsigned int flags;
    struct list_head keyring_name_list;
    struct key * user_keyring_register;
    struct rw_semaphore keyring_sem;
    struct key * persistent_keyring_register;
    struct work_struct work;
    struct ctl_table_set set;
    struct ctl_table_header * sysctls;
    struct ucounts * ucounts;
    int[9] ucount_max;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct user_namespace {
    struct uid_gid_map uid_map;
    struct uid_gid_map gid_map;
    struct uid_gid_map projid_map;
    atomic_t count;
    struct user_namespace * parent;
    int level;
    kuid_t owner;
    kgid_t group;
    struct ns_common ns;
    long unsigned int flags;
    struct list_head keyring_name_list;
    struct key * user_keyring_register;
    struct rw_semaphore keyring_sem;
    struct key * persistent_keyring_register;
    struct work_struct work;
    struct ctl_table_set set;
    struct ctl_table_header * sysctls;
    struct ucounts * ucounts;
    int[9] ucount_max;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct user_namespace {
    struct uid_gid_map uid_map;
    struct uid_gid_map gid_map;
    struct uid_gid_map projid_map;
    atomic_t count;
    struct user_namespace * parent;
    int level;
    kuid_t owner;
    kgid_t group;
    struct ns_common ns;
    long unsigned int flags;
    struct list_head keyring_name_list;
    struct key * user_keyring_register;
    struct rw_semaphore keyring_sem;
    struct key * persistent_keyring_register;
    struct work_struct work;
    struct ctl_table_set set;
    struct ctl_table_header * sysctls;
    struct ucounts * ucounts;
    int[10] ucount_max;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct user_namespace {
    struct uid_gid_map uid_map;
    struct uid_gid_map gid_map;
    struct uid_gid_map projid_map;
    struct user_namespace * parent;
    int level;
    kuid_t owner;
    kgid_t group;
    struct ns_common ns;
    long unsigned int flags;
    struct list_head keyring_name_list;
    struct key * user_keyring_register;
    struct rw_semaphore keyring_sem;
    struct key * persistent_keyring_register;
    struct work_struct work;
    struct ctl_table_set set;
    struct ctl_table_header * sysctls;
    struct ucounts * ucounts;
    int[10] ucount_max;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct user_namespace {
    struct uid_gid_map uid_map;
    struct uid_gid_map gid_map;
    struct uid_gid_map projid_map;
    struct user_namespace * parent;
    int level;
    kuid_t owner;
    kgid_t group;
    struct ns_common ns;
    long unsigned int flags;
    bool parent_could_setfcap;
    struct list_head keyring_name_list;
    struct key * user_keyring_register;
    struct rw_semaphore keyring_sem;
    struct key * persistent_keyring_register;
    struct work_struct work;
    struct ctl_table_set set;
    struct ctl_table_header * sysctls;
    struct ucounts * ucounts;
    int[12] ucount_max;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct user_namespace {
    struct uid_gid_map uid_map;
    struct uid_gid_map gid_map;
    struct uid_gid_map projid_map;
    struct user_namespace * parent;
    int level;
    kuid_t owner;
    kgid_t group;
    struct ns_common ns;
    long unsigned int flags;
    bool parent_could_setfcap;
    struct list_head keyring_name_list;
    struct key * user_keyring_register;
    struct rw_semaphore keyring_sem;
    struct key * persistent_keyring_register;
    struct work_struct work;
    struct ctl_table_set set;
    struct ctl_table_header * sysctls;
    struct ucounts * ucounts;
    long int[16] ucount_max;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct user_namespace {
    struct uid_gid_map uid_map;
    struct uid_gid_map gid_map;
    struct uid_gid_map projid_map;
    struct user_namespace * parent;
    int level;
    kuid_t owner;
    kgid_t group;
    struct ns_common ns;
    long unsigned int flags;
    bool parent_could_setfcap;
    struct list_head keyring_name_list;
    struct key * user_keyring_register;
    struct rw_semaphore keyring_sem;
    struct key * persistent_keyring_register;
    struct work_struct work;
    struct ctl_table_set set;
    struct ctl_table_header * sysctls;
    struct ucounts * ucounts;
    long int[16] ucount_max;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct user_namespace {
    struct uid_gid_map uid_map;
    struct uid_gid_map gid_map;
    struct uid_gid_map projid_map;
    struct user_namespace * parent;
    int level;
    kuid_t owner;
    kgid_t group;
    struct ns_common ns;
    long unsigned int flags;
    bool parent_could_setfcap;
    struct list_head keyring_name_list;
    struct key * user_keyring_register;
    struct rw_semaphore keyring_sem;
    struct key * persistent_keyring_register;
    struct work_struct work;
    struct ctl_table_set set;
    struct ctl_table_header * sysctls;
    struct ucounts * ucounts;
    long int[12] ucount_max;
    long int[4] rlimit_max;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct user_namespace {
    struct uid_gid_map uid_map;
    struct uid_gid_map gid_map;
    struct uid_gid_map projid_map;
    struct user_namespace * parent;
    int level;
    kuid_t owner;
    kgid_t group;
    struct ns_common ns;
    long unsigned int flags;
    bool parent_could_setfcap;
    struct list_head keyring_name_list;
    struct key * user_keyring_register;
    struct rw_semaphore keyring_sem;
    struct key * persistent_keyring_register;
    struct work_struct work;
    struct ctl_table_set set;
    struct ctl_table_header * sysctls;
    struct ucounts * ucounts;
    long int[12] ucount_max;
    long int[4] rlimit_max;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct user_namespace {
    struct uid_gid_map uid_map;
    struct uid_gid_map gid_map;
    struct uid_gid_map projid_map;
    struct user_namespace * parent;
    int level;
    kuid_t owner;
    kgid_t group;
    struct ns_common ns;
    long unsigned int flags;
    bool parent_could_setfcap;
    struct list_head keyring_name_list;
    struct key * user_keyring_register;
    struct rw_semaphore keyring_sem;
    struct key * persistent_keyring_register;
    struct work_struct work;
    struct ctl_table_set set;
    struct ctl_table_header * sysctls;
    struct ucounts * ucounts;
    long int[12] ucount_max;
    long int[4] rlimit_max;
    struct binfmt_misc * binfmt_misc;
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
struct user_namespace {
    struct uid_gid_map uid_map;
    struct uid_gid_map gid_map;
    struct uid_gid_map projid_map;
    atomic_t count;
    struct user_namespace * parent;
    int level;
    kuid_t owner;
    kgid_t group;
    struct ns_common ns;
    long unsigned int flags;
    struct list_head keyring_name_list;
    struct key * user_keyring_register;
    struct rw_semaphore keyring_sem;
    struct key * persistent_keyring_register;
    struct work_struct work;
    struct ctl_table_set set;
    struct ctl_table_header * sysctls;
    struct ucounts * ucounts;
    int[9] ucount_max;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct user_namespace {
    struct uid_gid_map uid_map;
    struct uid_gid_map gid_map;
    struct uid_gid_map projid_map;
    atomic_t count;
    struct user_namespace * parent;
    int level;
    kuid_t owner;
    kgid_t group;
    struct ns_common ns;
    long unsigned int flags;
    struct list_head keyring_name_list;
    struct key * user_keyring_register;
    struct rw_semaphore keyring_sem;
    struct key * persistent_keyring_register;
    struct work_struct work;
    struct ctl_table_set set;
    struct ctl_table_header * sysctls;
    struct ucounts * ucounts;
    int[9] ucount_max;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct user_namespace {
    struct uid_gid_map uid_map;
    struct uid_gid_map gid_map;
    struct uid_gid_map projid_map;
    atomic_t count;
    struct user_namespace * parent;
    int level;
    kuid_t owner;
    kgid_t group;
    struct ns_common ns;
    long unsigned int flags;
    struct list_head keyring_name_list;
    struct key * user_keyring_register;
    struct rw_semaphore keyring_sem;
    struct key * persistent_keyring_register;
    struct work_struct work;
    struct ctl_table_set set;
    struct ctl_table_header * sysctls;
    struct ucounts * ucounts;
    int[9] ucount_max;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct user_namespace {
    struct uid_gid_map uid_map;
    struct uid_gid_map gid_map;
    struct uid_gid_map projid_map;
    atomic_t count;
    struct user_namespace * parent;
    int level;
    kuid_t owner;
    kgid_t group;
    struct ns_common ns;
    long unsigned int flags;
    struct list_head keyring_name_list;
    struct key * user_keyring_register;
    struct rw_semaphore keyring_sem;
    struct key * persistent_keyring_register;
    struct work_struct work;
    struct ctl_table_set set;
    struct ctl_table_header * sysctls;
    struct ucounts * ucounts;
    int[9] ucount_max;
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
struct user_namespace {
    struct uid_gid_map uid_map;
    struct uid_gid_map gid_map;
    struct uid_gid_map projid_map;
    atomic_t count;
    struct user_namespace * parent;
    int level;
    kuid_t owner;
    kgid_t group;
    struct ns_common ns;
    long unsigned int flags;
    struct list_head keyring_name_list;
    struct key * user_keyring_register;
    struct rw_semaphore keyring_sem;
    struct key * persistent_keyring_register;
    struct work_struct work;
    struct ctl_table_set set;
    struct ctl_table_header * sysctls;
    struct ucounts * ucounts;
    int[9] ucount_max;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct user_namespace {
    struct uid_gid_map uid_map;
    struct uid_gid_map gid_map;
    struct uid_gid_map projid_map;
    atomic_t count;
    struct user_namespace * parent;
    int level;
    kuid_t owner;
    kgid_t group;
    struct ns_common ns;
    long unsigned int flags;
    struct list_head keyring_name_list;
    struct key * user_keyring_register;
    struct rw_semaphore keyring_sem;
    struct key * persistent_keyring_register;
    struct work_struct work;
    struct ctl_table_set set;
    struct ctl_table_header * sysctls;
    struct ucounts * ucounts;
    int[9] ucount_max;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct user_namespace {
    struct uid_gid_map uid_map;
    struct uid_gid_map gid_map;
    struct uid_gid_map projid_map;
    atomic_t count;
    struct user_namespace * parent;
    int level;
    kuid_t owner;
    kgid_t group;
    struct ns_common ns;
    long unsigned int flags;
    struct list_head keyring_name_list;
    struct key * user_keyring_register;
    struct rw_semaphore keyring_sem;
    struct key * persistent_keyring_register;
    struct work_struct work;
    struct ctl_table_set set;
    struct ctl_table_header * sysctls;
    struct ucounts * ucounts;
    int[9] ucount_max;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct user_namespace {
    struct uid_gid_map uid_map;
    struct uid_gid_map gid_map;
    struct uid_gid_map projid_map;
    atomic_t count;
    struct user_namespace * parent;
    int level;
    kuid_t owner;
    kgid_t group;
    struct ns_common ns;
    long unsigned int flags;
    struct list_head keyring_name_list;
    struct key * user_keyring_register;
    struct rw_semaphore keyring_sem;
    struct key * persistent_keyring_register;
    struct work_struct work;
    struct ctl_table_set set;
    struct ctl_table_header * sysctls;
    struct ucounts * ucounts;
    int[9] ucount_max;
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
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct work_struct work</code>
</li>
<li>
<b>Field added. </b>
<code>struct ctl_table_set set</code>
</li>
<li>
<b>Field added. </b>
<code>struct ctl_table_header * sysctls</code>
</li>
<li>
<b>Field added. </b>
<code>struct ucounts * ucounts</code>
</li>
<li>
<b>Field added. </b>
<code>int[7] ucount_max</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>int[7] ucount_max</code> ➡️ <code>int[9] ucount_max</code>
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
<code>struct list_head keyring_name_list</code>
</li>
<li>
<b>Field added. </b>
<code>struct key * user_keyring_register</code>
</li>
<li>
<b>Field added. </b>
<code>struct rw_semaphore keyring_sem</code>
</li>
<li>
<b>Field removed. </b>
<code>struct rw_semaphore persistent_keyring_register_sem</code>
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
<b>Field type changed. </b>
<code>int[9] ucount_max</code> ➡️ <code>int[10] ucount_max</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>atomic_t count</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool parent_could_setfcap</code>
</li>
<li>
<b>Field type changed. </b>
<code>int[10] ucount_max</code> ➡️ <code>int[12] ucount_max</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>int[12] ucount_max</code> ➡️ <code>long int[16] ucount_max</code>
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
<code>long int[4] rlimit_max</code>
</li>
<li>
<b>Field type changed. </b>
<code>long int[16] ucount_max</code> ➡️ <code>long int[12] ucount_max</code>
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
<code>struct binfmt_misc * binfmt_misc</code>
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
