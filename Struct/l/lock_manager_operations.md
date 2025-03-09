# Struct: <code>lock_manager_operations</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct lock_manager_operations {
    int (*)(struct file_lock *, struct file_lock *) lm_compare_owner;
    long unsigned int (*)(struct file_lock *) lm_owner_key;
    fl_owner_t (*)(fl_owner_t) lm_get_owner;
    void (*)(fl_owner_t) lm_put_owner;
    void (*)(struct file_lock *) lm_notify;
    int (*)(struct file_lock *, int) lm_grant;
    bool (*)(struct file_lock *) lm_break;
    int (*)(struct file_lock *, int, struct list_head *) lm_change;
    void (*)(struct file_lock *, void * *) lm_setup;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct lock_manager_operations {
    int (*)(struct file_lock *, struct file_lock *) lm_compare_owner;
    long unsigned int (*)(struct file_lock *) lm_owner_key;
    fl_owner_t (*)(fl_owner_t) lm_get_owner;
    void (*)(fl_owner_t) lm_put_owner;
    void (*)(struct file_lock *) lm_notify;
    int (*)(struct file_lock *, int) lm_grant;
    bool (*)(struct file_lock *) lm_break;
    int (*)(struct file_lock *, int, struct list_head *) lm_change;
    void (*)(struct file_lock *, void * *) lm_setup;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct lock_manager_operations {
    int (*)(struct file_lock *, struct file_lock *) lm_compare_owner;
    long unsigned int (*)(struct file_lock *) lm_owner_key;
    fl_owner_t (*)(fl_owner_t) lm_get_owner;
    void (*)(fl_owner_t) lm_put_owner;
    void (*)(struct file_lock *) lm_notify;
    int (*)(struct file_lock *, int) lm_grant;
    bool (*)(struct file_lock *) lm_break;
    int (*)(struct file_lock *, int, struct list_head *) lm_change;
    void (*)(struct file_lock *, void * *) lm_setup;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct lock_manager_operations {
    int (*)(struct file_lock *, struct file_lock *) lm_compare_owner;
    long unsigned int (*)(struct file_lock *) lm_owner_key;
    fl_owner_t (*)(fl_owner_t) lm_get_owner;
    void (*)(fl_owner_t) lm_put_owner;
    void (*)(struct file_lock *) lm_notify;
    int (*)(struct file_lock *, int) lm_grant;
    bool (*)(struct file_lock *) lm_break;
    int (*)(struct file_lock *, int, struct list_head *) lm_change;
    void (*)(struct file_lock *, void * *) lm_setup;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct lock_manager_operations {
    int (*)(struct file_lock *, struct file_lock *) lm_compare_owner;
    long unsigned int (*)(struct file_lock *) lm_owner_key;
    fl_owner_t (*)(fl_owner_t) lm_get_owner;
    void (*)(fl_owner_t) lm_put_owner;
    void (*)(struct file_lock *) lm_notify;
    int (*)(struct file_lock *, int) lm_grant;
    bool (*)(struct file_lock *) lm_break;
    int (*)(struct file_lock *, int, struct list_head *) lm_change;
    void (*)(struct file_lock *, void * *) lm_setup;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct lock_manager_operations {
    int (*)(struct file_lock *, struct file_lock *) lm_compare_owner;
    long unsigned int (*)(struct file_lock *) lm_owner_key;
    fl_owner_t (*)(fl_owner_t) lm_get_owner;
    void (*)(fl_owner_t) lm_put_owner;
    void (*)(struct file_lock *) lm_notify;
    int (*)(struct file_lock *, int) lm_grant;
    bool (*)(struct file_lock *) lm_break;
    int (*)(struct file_lock *, int, struct list_head *) lm_change;
    void (*)(struct file_lock *, void * *) lm_setup;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct lock_manager_operations {
    int (*)(struct file_lock *, struct file_lock *) lm_compare_owner;
    long unsigned int (*)(struct file_lock *) lm_owner_key;
    fl_owner_t (*)(fl_owner_t) lm_get_owner;
    void (*)(fl_owner_t) lm_put_owner;
    void (*)(struct file_lock *) lm_notify;
    int (*)(struct file_lock *, int) lm_grant;
    bool (*)(struct file_lock *) lm_break;
    int (*)(struct file_lock *, int, struct list_head *) lm_change;
    void (*)(struct file_lock *, void * *) lm_setup;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct lock_manager_operations {
    fl_owner_t (*)(fl_owner_t) lm_get_owner;
    void (*)(fl_owner_t) lm_put_owner;
    void (*)(struct file_lock *) lm_notify;
    int (*)(struct file_lock *, int) lm_grant;
    bool (*)(struct file_lock *) lm_break;
    int (*)(struct file_lock *, int, struct list_head *) lm_change;
    void (*)(struct file_lock *, void * *) lm_setup;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct lock_manager_operations {
    fl_owner_t (*)(fl_owner_t) lm_get_owner;
    void (*)(fl_owner_t) lm_put_owner;
    void (*)(struct file_lock *) lm_notify;
    int (*)(struct file_lock *, int) lm_grant;
    bool (*)(struct file_lock *) lm_break;
    int (*)(struct file_lock *, int, struct list_head *) lm_change;
    void (*)(struct file_lock *, void * *) lm_setup;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct lock_manager_operations {
    fl_owner_t (*)(fl_owner_t) lm_get_owner;
    void (*)(fl_owner_t) lm_put_owner;
    void (*)(struct file_lock *) lm_notify;
    int (*)(struct file_lock *, int) lm_grant;
    bool (*)(struct file_lock *) lm_break;
    int (*)(struct file_lock *, int, struct list_head *) lm_change;
    void (*)(struct file_lock *, void * *) lm_setup;
    bool (*)(struct file_lock *) lm_breaker_owns_lease;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct lock_manager_operations {
    fl_owner_t (*)(fl_owner_t) lm_get_owner;
    void (*)(fl_owner_t) lm_put_owner;
    void (*)(struct file_lock *) lm_notify;
    int (*)(struct file_lock *, int) lm_grant;
    bool (*)(struct file_lock *) lm_break;
    int (*)(struct file_lock *, int, struct list_head *) lm_change;
    void (*)(struct file_lock *, void * *) lm_setup;
    bool (*)(struct file_lock *) lm_breaker_owns_lease;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct lock_manager_operations {
    fl_owner_t (*)(fl_owner_t) lm_get_owner;
    void (*)(fl_owner_t) lm_put_owner;
    void (*)(struct file_lock *) lm_notify;
    int (*)(struct file_lock *, int) lm_grant;
    bool (*)(struct file_lock *) lm_break;
    int (*)(struct file_lock *, int, struct list_head *) lm_change;
    void (*)(struct file_lock *, void * *) lm_setup;
    bool (*)(struct file_lock *) lm_breaker_owns_lease;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct lock_manager_operations {
    fl_owner_t (*)(fl_owner_t) lm_get_owner;
    void (*)(fl_owner_t) lm_put_owner;
    void (*)(struct file_lock *) lm_notify;
    int (*)(struct file_lock *, int) lm_grant;
    bool (*)(struct file_lock *) lm_break;
    int (*)(struct file_lock *, int, struct list_head *) lm_change;
    void (*)(struct file_lock *, void * *) lm_setup;
    bool (*)(struct file_lock *) lm_breaker_owns_lease;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct lock_manager_operations {
    void * lm_mod_owner;
    fl_owner_t (*)(fl_owner_t) lm_get_owner;
    void (*)(fl_owner_t) lm_put_owner;
    void (*)(struct file_lock *) lm_notify;
    int (*)(struct file_lock *, int) lm_grant;
    bool (*)(struct file_lock *) lm_break;
    int (*)(struct file_lock *, int, struct list_head *) lm_change;
    void (*)(struct file_lock *, void * *) lm_setup;
    bool (*)(struct file_lock *) lm_breaker_owns_lease;
    bool (*)(struct file_lock *) lm_lock_expirable;
    void (*)() lm_expire_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct lock_manager_operations {
    void * lm_mod_owner;
    fl_owner_t (*)(fl_owner_t) lm_get_owner;
    void (*)(fl_owner_t) lm_put_owner;
    void (*)(struct file_lock *) lm_notify;
    int (*)(struct file_lock *, int) lm_grant;
    bool (*)(struct file_lock *) lm_break;
    int (*)(struct file_lock *, int, struct list_head *) lm_change;
    void (*)(struct file_lock *, void * *) lm_setup;
    bool (*)(struct file_lock *) lm_breaker_owns_lease;
    bool (*)(struct file_lock *) lm_lock_expirable;
    void (*)() lm_expire_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct lock_manager_operations {
    void * lm_mod_owner;
    fl_owner_t (*)(fl_owner_t) lm_get_owner;
    void (*)(fl_owner_t) lm_put_owner;
    void (*)(struct file_lock *) lm_notify;
    int (*)(struct file_lock *, int) lm_grant;
    bool (*)(struct file_lock *) lm_break;
    int (*)(struct file_lock *, int, struct list_head *) lm_change;
    void (*)(struct file_lock *, void * *) lm_setup;
    bool (*)(struct file_lock *) lm_breaker_owns_lease;
    bool (*)(struct file_lock *) lm_lock_expirable;
    void (*)() lm_expire_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct lock_manager_operations {
    void * lm_mod_owner;
    fl_owner_t (*)(fl_owner_t) lm_get_owner;
    void (*)(fl_owner_t) lm_put_owner;
    void (*)(struct file_lock *) lm_notify;
    int (*)(struct file_lock *, int) lm_grant;
    bool (*)(struct file_lock *) lm_break;
    int (*)(struct file_lock *, int, struct list_head *) lm_change;
    void (*)(struct file_lock *, void * *) lm_setup;
    bool (*)(struct file_lock *) lm_breaker_owns_lease;
    bool (*)(struct file_lock *) lm_lock_expirable;
    void (*)() lm_expire_lock;
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
struct lock_manager_operations {
    fl_owner_t (*)(fl_owner_t) lm_get_owner;
    void (*)(fl_owner_t) lm_put_owner;
    void (*)(struct file_lock *) lm_notify;
    int (*)(struct file_lock *, int) lm_grant;
    bool (*)(struct file_lock *) lm_break;
    int (*)(struct file_lock *, int, struct list_head *) lm_change;
    void (*)(struct file_lock *, void * *) lm_setup;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct lock_manager_operations {
    fl_owner_t (*)(fl_owner_t) lm_get_owner;
    void (*)(fl_owner_t) lm_put_owner;
    void (*)(struct file_lock *) lm_notify;
    int (*)(struct file_lock *, int) lm_grant;
    bool (*)(struct file_lock *) lm_break;
    int (*)(struct file_lock *, int, struct list_head *) lm_change;
    void (*)(struct file_lock *, void * *) lm_setup;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct lock_manager_operations {
    fl_owner_t (*)(fl_owner_t) lm_get_owner;
    void (*)(fl_owner_t) lm_put_owner;
    void (*)(struct file_lock *) lm_notify;
    int (*)(struct file_lock *, int) lm_grant;
    bool (*)(struct file_lock *) lm_break;
    int (*)(struct file_lock *, int, struct list_head *) lm_change;
    void (*)(struct file_lock *, void * *) lm_setup;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct lock_manager_operations {
    fl_owner_t (*)(fl_owner_t) lm_get_owner;
    void (*)(fl_owner_t) lm_put_owner;
    void (*)(struct file_lock *) lm_notify;
    int (*)(struct file_lock *, int) lm_grant;
    bool (*)(struct file_lock *) lm_break;
    int (*)(struct file_lock *, int, struct list_head *) lm_change;
    void (*)(struct file_lock *, void * *) lm_setup;
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
struct lock_manager_operations {
    fl_owner_t (*)(fl_owner_t) lm_get_owner;
    void (*)(fl_owner_t) lm_put_owner;
    void (*)(struct file_lock *) lm_notify;
    int (*)(struct file_lock *, int) lm_grant;
    bool (*)(struct file_lock *) lm_break;
    int (*)(struct file_lock *, int, struct list_head *) lm_change;
    void (*)(struct file_lock *, void * *) lm_setup;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct lock_manager_operations {
    fl_owner_t (*)(fl_owner_t) lm_get_owner;
    void (*)(fl_owner_t) lm_put_owner;
    void (*)(struct file_lock *) lm_notify;
    int (*)(struct file_lock *, int) lm_grant;
    bool (*)(struct file_lock *) lm_break;
    int (*)(struct file_lock *, int, struct list_head *) lm_change;
    void (*)(struct file_lock *, void * *) lm_setup;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct lock_manager_operations {
    fl_owner_t (*)(fl_owner_t) lm_get_owner;
    void (*)(fl_owner_t) lm_put_owner;
    void (*)(struct file_lock *) lm_notify;
    int (*)(struct file_lock *, int) lm_grant;
    bool (*)(struct file_lock *) lm_break;
    int (*)(struct file_lock *, int, struct list_head *) lm_change;
    void (*)(struct file_lock *, void * *) lm_setup;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct lock_manager_operations {
    fl_owner_t (*)(fl_owner_t) lm_get_owner;
    void (*)(fl_owner_t) lm_put_owner;
    void (*)(struct file_lock *) lm_notify;
    int (*)(struct file_lock *, int) lm_grant;
    bool (*)(struct file_lock *) lm_break;
    int (*)(struct file_lock *, int, struct list_head *) lm_change;
    void (*)(struct file_lock *, void * *) lm_setup;
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
<b>Field removed. </b>
<code>int (*)(struct file_lock *, struct file_lock *) lm_compare_owner</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int (*)(struct file_lock *) lm_owner_key</code>
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
<code>bool (*)(struct file_lock *) lm_breaker_owns_lease</code>
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>void * lm_mod_owner</code>
</li>
<li>
<b>Field added. </b>
<code>bool (*)(struct file_lock *) lm_lock_expirable</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)() lm_expire_lock</code>
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
