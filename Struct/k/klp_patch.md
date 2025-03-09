# Struct: <code>klp_patch</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct klp_patch {
    struct module * mod;
    struct klp_object * objs;
    struct list_head list;
    struct kobject kobj;
    enum klp_state state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct klp_patch {
    struct module * mod;
    struct klp_object * objs;
    struct list_head list;
    struct kobject kobj;
    enum klp_state state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct klp_patch {
    struct module * mod;
    struct klp_object * objs;
    struct list_head list;
    struct kobject kobj;
    enum klp_state state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct klp_patch {
    struct module * mod;
    struct klp_object * objs;
    bool immediate;
    struct list_head list;
    struct kobject kobj;
    bool enabled;
    struct completion finish;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct klp_patch {
    struct module * mod;
    struct klp_object * objs;
    bool immediate;
    struct list_head list;
    struct kobject kobj;
    bool enabled;
    struct completion finish;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct klp_patch {
    struct module * mod;
    struct klp_object * objs;
    struct list_head list;
    struct kobject kobj;
    bool enabled;
    struct completion finish;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct klp_patch {
    struct module * mod;
    struct klp_object * objs;
    struct list_head list;
    struct kobject kobj;
    bool enabled;
    struct completion finish;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct klp_patch {
    struct module * mod;
    struct klp_object * objs;
    bool replace;
    struct list_head list;
    struct kobject kobj;
    struct list_head obj_list;
    bool enabled;
    bool forced;
    struct work_struct free_work;
    struct completion finish;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct klp_patch {
    struct module * mod;
    struct klp_object * objs;
    bool replace;
    struct list_head list;
    struct kobject kobj;
    struct list_head obj_list;
    bool enabled;
    bool forced;
    struct work_struct free_work;
    struct completion finish;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct klp_patch {
    struct module * mod;
    struct klp_object * objs;
    struct klp_state * states;
    bool replace;
    struct list_head list;
    struct kobject kobj;
    struct list_head obj_list;
    bool enabled;
    bool forced;
    struct work_struct free_work;
    struct completion finish;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct klp_patch {
    struct module * mod;
    struct klp_object * objs;
    struct klp_state * states;
    bool replace;
    struct list_head list;
    struct kobject kobj;
    struct list_head obj_list;
    bool enabled;
    bool forced;
    struct work_struct free_work;
    struct completion finish;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct klp_patch {
    struct module * mod;
    struct klp_object * objs;
    struct klp_state * states;
    bool replace;
    struct list_head list;
    struct kobject kobj;
    struct list_head obj_list;
    bool enabled;
    bool forced;
    struct work_struct free_work;
    struct completion finish;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct klp_patch {
    struct module * mod;
    struct klp_object * objs;
    struct klp_state * states;
    bool replace;
    struct list_head list;
    struct kobject kobj;
    struct list_head obj_list;
    bool enabled;
    bool forced;
    struct work_struct free_work;
    struct completion finish;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct klp_patch {
    struct module * mod;
    struct klp_object * objs;
    struct klp_state * states;
    bool replace;
    struct list_head list;
    struct kobject kobj;
    struct list_head obj_list;
    bool enabled;
    bool forced;
    struct work_struct free_work;
    struct completion finish;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct klp_patch {
    struct module * mod;
    struct klp_object * objs;
    struct klp_state * states;
    bool replace;
    struct list_head list;
    struct kobject kobj;
    struct list_head obj_list;
    bool enabled;
    bool forced;
    struct work_struct free_work;
    struct completion finish;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct klp_patch {
    struct module * mod;
    struct klp_object * objs;
    struct klp_state * states;
    bool replace;
    struct list_head list;
    struct kobject kobj;
    struct list_head obj_list;
    bool enabled;
    bool forced;
    struct work_struct free_work;
    struct completion finish;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct klp_patch {
    struct module * mod;
    struct klp_object * objs;
    struct klp_state * states;
    bool replace;
    struct list_head list;
    struct kobject kobj;
    struct list_head obj_list;
    bool enabled;
    bool forced;
    struct work_struct free_work;
    struct completion finish;
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
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct klp_patch {
    struct module * mod;
    struct klp_object * objs;
    bool replace;
    struct list_head list;
    struct kobject kobj;
    struct list_head obj_list;
    bool enabled;
    bool forced;
    struct work_struct free_work;
    struct completion finish;
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct klp_patch {
    struct module * mod;
    struct klp_object * objs;
    bool replace;
    struct list_head list;
    struct kobject kobj;
    struct list_head obj_list;
    bool enabled;
    bool forced;
    struct work_struct free_work;
    struct completion finish;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct klp_patch {
    struct module * mod;
    struct klp_object * objs;
    bool replace;
    struct list_head list;
    struct kobject kobj;
    struct list_head obj_list;
    bool enabled;
    bool forced;
    struct work_struct free_work;
    struct completion finish;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct klp_patch {
    struct module * mod;
    struct klp_object * objs;
    bool replace;
    struct list_head list;
    struct kobject kobj;
    struct list_head obj_list;
    bool enabled;
    bool forced;
    struct work_struct free_work;
    struct completion finish;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct klp_patch {
    struct module * mod;
    struct klp_object * objs;
    bool replace;
    struct list_head list;
    struct kobject kobj;
    struct list_head obj_list;
    bool enabled;
    bool forced;
    struct work_struct free_work;
    struct completion finish;
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
<code>bool immediate</code>
</li>
<li>
<b>Field added. </b>
<code>bool enabled</code>
</li>
<li>
<b>Field added. </b>
<code>struct completion finish</code>
</li>
<li>
<b>Field removed. </b>
<code>enum klp_state state</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>bool immediate</code>
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
<code>bool replace</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head obj_list</code>
</li>
<li>
<b>Field added. </b>
<code>bool forced</code>
</li>
<li>
<b>Field added. </b>
<code>struct work_struct free_work</code>
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
<code>struct klp_state * states</code>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
struct klp_patch {
    struct module * mod;
    struct klp_object * objs;
    bool replace;
    struct list_head list;
    struct kobject kobj;
    struct list_head obj_list;
    bool enabled;
    bool forced;
    struct work_struct free_work;
    struct completion finish;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct klp_patch {
    struct module * mod;
    struct klp_object * objs;
    bool replace;
    struct list_head list;
    struct kobject kobj;
    struct list_head obj_list;
    bool enabled;
    bool forced;
    struct work_struct free_work;
    struct completion finish;
}
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct klp_patch {
    struct module * mod;
    struct klp_object * objs;
    bool replace;
    struct list_head list;
    struct kobject kobj;
    struct list_head obj_list;
    bool enabled;
    bool forced;
    struct work_struct free_work;
    struct completion finish;
}
```
</details>
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
