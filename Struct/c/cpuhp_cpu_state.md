# Struct: <code>cpuhp_cpu_state</code>

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
struct cpuhp_cpu_state {
    enum cpuhp_state state;
    enum cpuhp_state target;
    struct task_struct * thread;
    bool should_run;
    bool rollback;
    enum cpuhp_state cb_state;
    int (*)(unsigned int) cb;
    int result;
    struct completion done;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct cpuhp_cpu_state {
    enum cpuhp_state state;
    enum cpuhp_state target;
    struct task_struct * thread;
    bool should_run;
    bool rollback;
    bool single;
    bool bringup;
    struct hlist_node * node;
    enum cpuhp_state cb_state;
    int result;
    struct completion done;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct cpuhp_cpu_state {
    enum cpuhp_state state;
    enum cpuhp_state target;
    struct task_struct * thread;
    bool should_run;
    bool rollback;
    bool single;
    bool bringup;
    struct hlist_node * node;
    enum cpuhp_state cb_state;
    int result;
    struct completion done;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct cpuhp_cpu_state {
    enum cpuhp_state state;
    enum cpuhp_state target;
    enum cpuhp_state fail;
    struct task_struct * thread;
    bool should_run;
    bool rollback;
    bool single;
    bool bringup;
    struct hlist_node * node;
    struct hlist_node * last;
    enum cpuhp_state cb_state;
    int result;
    struct completion done_up;
    struct completion done_down;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct cpuhp_cpu_state {
    enum cpuhp_state state;
    enum cpuhp_state target;
    enum cpuhp_state fail;
    struct task_struct * thread;
    bool should_run;
    bool rollback;
    bool single;
    bool bringup;
    bool booted_once;
    struct hlist_node * node;
    struct hlist_node * last;
    enum cpuhp_state cb_state;
    int result;
    struct completion done_up;
    struct completion done_down;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct cpuhp_cpu_state {
    enum cpuhp_state state;
    enum cpuhp_state target;
    enum cpuhp_state fail;
    struct task_struct * thread;
    bool should_run;
    bool rollback;
    bool single;
    bool bringup;
    bool booted_once;
    struct hlist_node * node;
    struct hlist_node * last;
    enum cpuhp_state cb_state;
    int result;
    struct completion done_up;
    struct completion done_down;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct cpuhp_cpu_state {
    enum cpuhp_state state;
    enum cpuhp_state target;
    enum cpuhp_state fail;
    struct task_struct * thread;
    bool should_run;
    bool rollback;
    bool single;
    bool bringup;
    bool booted_once;
    struct hlist_node * node;
    struct hlist_node * last;
    enum cpuhp_state cb_state;
    int result;
    struct completion done_up;
    struct completion done_down;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct cpuhp_cpu_state {
    enum cpuhp_state state;
    enum cpuhp_state target;
    enum cpuhp_state fail;
    struct task_struct * thread;
    bool should_run;
    bool rollback;
    bool single;
    bool bringup;
    struct hlist_node * node;
    struct hlist_node * last;
    enum cpuhp_state cb_state;
    int result;
    struct completion done_up;
    struct completion done_down;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct cpuhp_cpu_state {
    enum cpuhp_state state;
    enum cpuhp_state target;
    enum cpuhp_state fail;
    struct task_struct * thread;
    bool should_run;
    bool rollback;
    bool single;
    bool bringup;
    struct hlist_node * node;
    struct hlist_node * last;
    enum cpuhp_state cb_state;
    int result;
    struct completion done_up;
    struct completion done_down;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct cpuhp_cpu_state {
    enum cpuhp_state state;
    enum cpuhp_state target;
    enum cpuhp_state fail;
    struct task_struct * thread;
    bool should_run;
    bool rollback;
    bool single;
    bool bringup;
    struct hlist_node * node;
    struct hlist_node * last;
    enum cpuhp_state cb_state;
    int result;
    struct completion done_up;
    struct completion done_down;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct cpuhp_cpu_state {
    enum cpuhp_state state;
    enum cpuhp_state target;
    enum cpuhp_state fail;
    struct task_struct * thread;
    bool should_run;
    bool rollback;
    bool single;
    bool bringup;
    int cpu;
    struct hlist_node * node;
    struct hlist_node * last;
    enum cpuhp_state cb_state;
    int result;
    struct completion done_up;
    struct completion done_down;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct cpuhp_cpu_state {
    enum cpuhp_state state;
    enum cpuhp_state target;
    enum cpuhp_state fail;
    struct task_struct * thread;
    bool should_run;
    bool rollback;
    bool single;
    bool bringup;
    int cpu;
    struct hlist_node * node;
    struct hlist_node * last;
    enum cpuhp_state cb_state;
    int result;
    struct completion done_up;
    struct completion done_down;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct cpuhp_cpu_state {
    enum cpuhp_state state;
    enum cpuhp_state target;
    enum cpuhp_state fail;
    struct task_struct * thread;
    bool should_run;
    bool rollback;
    bool single;
    bool bringup;
    struct hlist_node * node;
    struct hlist_node * last;
    enum cpuhp_state cb_state;
    int result;
    struct completion done_up;
    struct completion done_down;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct cpuhp_cpu_state {
    enum cpuhp_state state;
    enum cpuhp_state target;
    enum cpuhp_state fail;
    struct task_struct * thread;
    bool should_run;
    bool rollback;
    bool single;
    bool bringup;
    struct hlist_node * node;
    struct hlist_node * last;
    enum cpuhp_state cb_state;
    int result;
    struct completion done_up;
    struct completion done_down;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct cpuhp_cpu_state {
    enum cpuhp_state state;
    enum cpuhp_state target;
    enum cpuhp_state fail;
    struct task_struct * thread;
    bool should_run;
    bool rollback;
    bool single;
    bool bringup;
    struct hlist_node * node;
    struct hlist_node * last;
    enum cpuhp_state cb_state;
    int result;
    atomic_t ap_sync_state;
    struct completion done_up;
    struct completion done_down;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct cpuhp_cpu_state {
    enum cpuhp_state state;
    enum cpuhp_state target;
    enum cpuhp_state fail;
    struct task_struct * thread;
    bool should_run;
    bool rollback;
    bool single;
    bool bringup;
    struct hlist_node * node;
    struct hlist_node * last;
    enum cpuhp_state cb_state;
    int result;
    atomic_t ap_sync_state;
    struct completion done_up;
    struct completion done_down;
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
struct cpuhp_cpu_state {
    enum cpuhp_state state;
    enum cpuhp_state target;
    enum cpuhp_state fail;
    struct task_struct * thread;
    bool should_run;
    bool rollback;
    bool single;
    bool bringup;
    struct hlist_node * node;
    struct hlist_node * last;
    enum cpuhp_state cb_state;
    int result;
    struct completion done_up;
    struct completion done_down;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct cpuhp_cpu_state {
    enum cpuhp_state state;
    enum cpuhp_state target;
    enum cpuhp_state fail;
    struct task_struct * thread;
    bool should_run;
    bool rollback;
    bool single;
    bool bringup;
    struct hlist_node * node;
    struct hlist_node * last;
    enum cpuhp_state cb_state;
    int result;
    struct completion done_up;
    struct completion done_down;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct cpuhp_cpu_state {
    enum cpuhp_state state;
    enum cpuhp_state target;
    enum cpuhp_state fail;
    struct task_struct * thread;
    bool should_run;
    bool rollback;
    bool single;
    bool bringup;
    struct hlist_node * node;
    struct hlist_node * last;
    enum cpuhp_state cb_state;
    int result;
    struct completion done_up;
    struct completion done_down;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct cpuhp_cpu_state {
    enum cpuhp_state state;
    enum cpuhp_state target;
    enum cpuhp_state fail;
    struct task_struct * thread;
    bool should_run;
    bool rollback;
    bool single;
    bool bringup;
    struct hlist_node * node;
    struct hlist_node * last;
    enum cpuhp_state cb_state;
    int result;
    struct completion done_up;
    struct completion done_down;
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
struct cpuhp_cpu_state {
    enum cpuhp_state state;
    enum cpuhp_state target;
    enum cpuhp_state fail;
    struct task_struct * thread;
    bool should_run;
    bool rollback;
    bool single;
    bool bringup;
    struct hlist_node * node;
    struct hlist_node * last;
    enum cpuhp_state cb_state;
    int result;
    struct completion done_up;
    struct completion done_down;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct cpuhp_cpu_state {
    enum cpuhp_state state;
    enum cpuhp_state target;
    enum cpuhp_state fail;
    struct task_struct * thread;
    bool should_run;
    bool rollback;
    bool single;
    bool bringup;
    struct hlist_node * node;
    struct hlist_node * last;
    enum cpuhp_state cb_state;
    int result;
    struct completion done_up;
    struct completion done_down;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct cpuhp_cpu_state {
    enum cpuhp_state state;
    enum cpuhp_state target;
    enum cpuhp_state fail;
    struct task_struct * thread;
    bool should_run;
    bool rollback;
    bool single;
    bool bringup;
    struct hlist_node * node;
    struct hlist_node * last;
    enum cpuhp_state cb_state;
    int result;
    struct completion done_up;
    struct completion done_down;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct cpuhp_cpu_state {
    enum cpuhp_state state;
    enum cpuhp_state target;
    enum cpuhp_state fail;
    struct task_struct * thread;
    bool should_run;
    bool rollback;
    bool single;
    bool bringup;
    struct hlist_node * node;
    struct hlist_node * last;
    enum cpuhp_state cb_state;
    int result;
    struct completion done_up;
    struct completion done_down;
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
struct cpuhp_cpu_state {
    enum cpuhp_state state;
    enum cpuhp_state target;
    struct task_struct * thread;
    bool should_run;
    bool rollback;
    enum cpuhp_state cb_state;
    int (*)(unsigned int) cb;
    int result;
    struct completion done;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool single</code>
</li>
<li>
<b>Field added. </b>
<code>bool bringup</code>
</li>
<li>
<b>Field added. </b>
<code>struct hlist_node * node</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(unsigned int) cb</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>enum cpuhp_state fail</code>
</li>
<li>
<b>Field added. </b>
<code>struct hlist_node * last</code>
</li>
<li>
<b>Field added. </b>
<code>struct completion done_up</code>
</li>
<li>
<b>Field added. </b>
<code>struct completion done_down</code>
</li>
<li>
<b>Field removed. </b>
<code>struct completion done</code>
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
<code>bool booted_once</code>
</li>
</ul>
</details>
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
<code>bool booted_once</code>
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
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int cpu</code>
</li>
</ul>
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
<b>Field removed. </b>
<code>int cpu</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>atomic_t ap_sync_state</code>
</li>
</ul>
</details>
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
