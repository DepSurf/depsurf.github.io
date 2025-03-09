# Struct: <code>hmm</code>

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
struct hmm {
    struct mm_struct * mm;
    spinlock_t lock;
    atomic_t sequence;
    struct list_head ranges;
    struct list_head mirrors;
    struct mmu_notifier mmu_notifier;
    struct rw_semaphore mirrors_sem;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct hmm {
    struct mm_struct * mm;
    spinlock_t lock;
    atomic_t sequence;
    struct list_head ranges;
    struct list_head mirrors;
    struct mmu_notifier mmu_notifier;
    struct rw_semaphore mirrors_sem;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct hmm {
    struct mm_struct * mm;
    spinlock_t lock;
    struct list_head ranges;
    struct list_head mirrors;
    struct mmu_notifier mmu_notifier;
    struct rw_semaphore mirrors_sem;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct hmm {
    struct mm_struct * mm;
    struct kref kref;
    spinlock_t ranges_lock;
    struct list_head ranges;
    struct list_head mirrors;
    struct mmu_notifier mmu_notifier;
    struct rw_semaphore mirrors_sem;
    wait_queue_head_t wq;
    struct callback_head rcu;
    long int notifiers;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct hmm {
    struct mmu_notifier mmu_notifier;
    spinlock_t ranges_lock;
    struct list_head ranges;
    struct list_head mirrors;
    struct rw_semaphore mirrors_sem;
    wait_queue_head_t wq;
    long int notifiers;
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
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct hmm {
    struct mmu_notifier mmu_notifier;
    spinlock_t ranges_lock;
    struct list_head ranges;
    struct list_head mirrors;
    struct rw_semaphore mirrors_sem;
    wait_queue_head_t wq;
    long int notifiers;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct hmm {
    struct mmu_notifier mmu_notifier;
    spinlock_t ranges_lock;
    struct list_head ranges;
    struct list_head mirrors;
    struct rw_semaphore mirrors_sem;
    wait_queue_head_t wq;
    long int notifiers;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct hmm {
    struct mmu_notifier mmu_notifier;
    spinlock_t ranges_lock;
    struct list_head ranges;
    struct list_head mirrors;
    struct rw_semaphore mirrors_sem;
    wait_queue_head_t wq;
    long int notifiers;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct hmm {
    struct mmu_notifier mmu_notifier;
    spinlock_t ranges_lock;
    struct list_head ranges;
    struct list_head mirrors;
    struct rw_semaphore mirrors_sem;
    wait_queue_head_t wq;
    long int notifiers;
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
struct hmm {
    struct mmu_notifier mmu_notifier;
    spinlock_t ranges_lock;
    struct list_head ranges;
    struct list_head mirrors;
    struct rw_semaphore mirrors_sem;
    wait_queue_head_t wq;
    long int notifiers;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct hmm {
    struct mmu_notifier mmu_notifier;
    spinlock_t ranges_lock;
    struct list_head ranges;
    struct list_head mirrors;
    struct rw_semaphore mirrors_sem;
    wait_queue_head_t wq;
    long int notifiers;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct hmm {
    struct mmu_notifier mmu_notifier;
    spinlock_t ranges_lock;
    struct list_head ranges;
    struct list_head mirrors;
    struct rw_semaphore mirrors_sem;
    wait_queue_head_t wq;
    long int notifiers;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct hmm {
    struct mmu_notifier mmu_notifier;
    spinlock_t ranges_lock;
    struct list_head ranges;
    struct list_head mirrors;
    struct rw_semaphore mirrors_sem;
    wait_queue_head_t wq;
    long int notifiers;
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
struct hmm {
    struct mm_struct * mm;
    spinlock_t lock;
    atomic_t sequence;
    struct list_head ranges;
    struct list_head mirrors;
    struct mmu_notifier mmu_notifier;
    struct rw_semaphore mirrors_sem;
}
```
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
<b>Field removed. </b>
<code>atomic_t sequence</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct kref kref</code>
</li>
<li>
<b>Field added. </b>
<code>spinlock_t ranges_lock</code>
</li>
<li>
<b>Field added. </b>
<code>wait_queue_head_t wq</code>
</li>
<li>
<b>Field added. </b>
<code>struct callback_head rcu</code>
</li>
<li>
<b>Field added. </b>
<code>long int notifiers</code>
</li>
<li>
<b>Field removed. </b>
<code>spinlock_t lock</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>struct mm_struct * mm</code>
</li>
<li>
<b>Field removed. </b>
<code>struct kref kref</code>
</li>
<li>
<b>Field removed. </b>
<code>struct callback_head rcu</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
struct hmm {
    struct mmu_notifier mmu_notifier;
    spinlock_t ranges_lock;
    struct list_head ranges;
    struct list_head mirrors;
    struct rw_semaphore mirrors_sem;
    wait_queue_head_t wq;
    long int notifiers;
}
```
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
