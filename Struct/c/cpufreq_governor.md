# Struct: <code>cpufreq_governor</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct cpufreq_governor {
    char[16] name;
    int initialized;
    int (*)(struct cpufreq_policy *, unsigned int) governor;
    ssize_t (*)(struct cpufreq_policy *, char *) show_setspeed;
    int (*)(struct cpufreq_policy *, unsigned int) store_setspeed;
    unsigned int max_transition_latency;
    struct list_head governor_list;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct cpufreq_governor {
    char[16] name;
    int (*)(struct cpufreq_policy *) init;
    void (*)(struct cpufreq_policy *) exit;
    int (*)(struct cpufreq_policy *) start;
    void (*)(struct cpufreq_policy *) stop;
    void (*)(struct cpufreq_policy *) limits;
    ssize_t (*)(struct cpufreq_policy *, char *) show_setspeed;
    int (*)(struct cpufreq_policy *, unsigned int) store_setspeed;
    unsigned int max_transition_latency;
    struct list_head governor_list;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct cpufreq_governor {
    char[16] name;
    int (*)(struct cpufreq_policy *) init;
    void (*)(struct cpufreq_policy *) exit;
    int (*)(struct cpufreq_policy *) start;
    void (*)(struct cpufreq_policy *) stop;
    void (*)(struct cpufreq_policy *) limits;
    ssize_t (*)(struct cpufreq_policy *, char *) show_setspeed;
    int (*)(struct cpufreq_policy *, unsigned int) store_setspeed;
    unsigned int max_transition_latency;
    struct list_head governor_list;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct cpufreq_governor {
    char[16] name;
    int (*)(struct cpufreq_policy *) init;
    void (*)(struct cpufreq_policy *) exit;
    int (*)(struct cpufreq_policy *) start;
    void (*)(struct cpufreq_policy *) stop;
    void (*)(struct cpufreq_policy *) limits;
    ssize_t (*)(struct cpufreq_policy *, char *) show_setspeed;
    int (*)(struct cpufreq_policy *, unsigned int) store_setspeed;
    unsigned int max_transition_latency;
    struct list_head governor_list;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct cpufreq_governor {
    char[16] name;
    int (*)(struct cpufreq_policy *) init;
    void (*)(struct cpufreq_policy *) exit;
    int (*)(struct cpufreq_policy *) start;
    void (*)(struct cpufreq_policy *) stop;
    void (*)(struct cpufreq_policy *) limits;
    ssize_t (*)(struct cpufreq_policy *, char *) show_setspeed;
    int (*)(struct cpufreq_policy *, unsigned int) store_setspeed;
    bool dynamic_switching;
    struct list_head governor_list;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct cpufreq_governor {
    char[16] name;
    int (*)(struct cpufreq_policy *) init;
    void (*)(struct cpufreq_policy *) exit;
    int (*)(struct cpufreq_policy *) start;
    void (*)(struct cpufreq_policy *) stop;
    void (*)(struct cpufreq_policy *) limits;
    ssize_t (*)(struct cpufreq_policy *, char *) show_setspeed;
    int (*)(struct cpufreq_policy *, unsigned int) store_setspeed;
    bool dynamic_switching;
    struct list_head governor_list;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct cpufreq_governor {
    char[16] name;
    int (*)(struct cpufreq_policy *) init;
    void (*)(struct cpufreq_policy *) exit;
    int (*)(struct cpufreq_policy *) start;
    void (*)(struct cpufreq_policy *) stop;
    void (*)(struct cpufreq_policy *) limits;
    ssize_t (*)(struct cpufreq_policy *, char *) show_setspeed;
    int (*)(struct cpufreq_policy *, unsigned int) store_setspeed;
    bool dynamic_switching;
    struct list_head governor_list;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct cpufreq_governor {
    char[16] name;
    int (*)(struct cpufreq_policy *) init;
    void (*)(struct cpufreq_policy *) exit;
    int (*)(struct cpufreq_policy *) start;
    void (*)(struct cpufreq_policy *) stop;
    void (*)(struct cpufreq_policy *) limits;
    ssize_t (*)(struct cpufreq_policy *, char *) show_setspeed;
    int (*)(struct cpufreq_policy *, unsigned int) store_setspeed;
    bool dynamic_switching;
    struct list_head governor_list;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct cpufreq_governor {
    char[16] name;
    int (*)(struct cpufreq_policy *) init;
    void (*)(struct cpufreq_policy *) exit;
    int (*)(struct cpufreq_policy *) start;
    void (*)(struct cpufreq_policy *) stop;
    void (*)(struct cpufreq_policy *) limits;
    ssize_t (*)(struct cpufreq_policy *, char *) show_setspeed;
    int (*)(struct cpufreq_policy *, unsigned int) store_setspeed;
    bool dynamic_switching;
    struct list_head governor_list;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct cpufreq_governor {
    char[16] name;
    int (*)(struct cpufreq_policy *) init;
    void (*)(struct cpufreq_policy *) exit;
    int (*)(struct cpufreq_policy *) start;
    void (*)(struct cpufreq_policy *) stop;
    void (*)(struct cpufreq_policy *) limits;
    ssize_t (*)(struct cpufreq_policy *, char *) show_setspeed;
    int (*)(struct cpufreq_policy *, unsigned int) store_setspeed;
    bool dynamic_switching;
    struct list_head governor_list;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct cpufreq_governor {
    char[16] name;
    int (*)(struct cpufreq_policy *) init;
    void (*)(struct cpufreq_policy *) exit;
    int (*)(struct cpufreq_policy *) start;
    void (*)(struct cpufreq_policy *) stop;
    void (*)(struct cpufreq_policy *) limits;
    ssize_t (*)(struct cpufreq_policy *, char *) show_setspeed;
    int (*)(struct cpufreq_policy *, unsigned int) store_setspeed;
    struct list_head governor_list;
    struct module * owner;
    u8 flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct cpufreq_governor {
    char[16] name;
    int (*)(struct cpufreq_policy *) init;
    void (*)(struct cpufreq_policy *) exit;
    int (*)(struct cpufreq_policy *) start;
    void (*)(struct cpufreq_policy *) stop;
    void (*)(struct cpufreq_policy *) limits;
    ssize_t (*)(struct cpufreq_policy *, char *) show_setspeed;
    int (*)(struct cpufreq_policy *, unsigned int) store_setspeed;
    struct list_head governor_list;
    struct module * owner;
    u8 flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct cpufreq_governor {
    char[16] name;
    int (*)(struct cpufreq_policy *) init;
    void (*)(struct cpufreq_policy *) exit;
    int (*)(struct cpufreq_policy *) start;
    void (*)(struct cpufreq_policy *) stop;
    void (*)(struct cpufreq_policy *) limits;
    ssize_t (*)(struct cpufreq_policy *, char *) show_setspeed;
    int (*)(struct cpufreq_policy *, unsigned int) store_setspeed;
    struct list_head governor_list;
    struct module * owner;
    u8 flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct cpufreq_governor {
    char[16] name;
    int (*)(struct cpufreq_policy *) init;
    void (*)(struct cpufreq_policy *) exit;
    int (*)(struct cpufreq_policy *) start;
    void (*)(struct cpufreq_policy *) stop;
    void (*)(struct cpufreq_policy *) limits;
    ssize_t (*)(struct cpufreq_policy *, char *) show_setspeed;
    int (*)(struct cpufreq_policy *, unsigned int) store_setspeed;
    struct list_head governor_list;
    struct module * owner;
    u8 flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct cpufreq_governor {
    char[16] name;
    int (*)(struct cpufreq_policy *) init;
    void (*)(struct cpufreq_policy *) exit;
    int (*)(struct cpufreq_policy *) start;
    void (*)(struct cpufreq_policy *) stop;
    void (*)(struct cpufreq_policy *) limits;
    ssize_t (*)(struct cpufreq_policy *, char *) show_setspeed;
    int (*)(struct cpufreq_policy *, unsigned int) store_setspeed;
    struct list_head governor_list;
    struct module * owner;
    u8 flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct cpufreq_governor {
    char[16] name;
    int (*)(struct cpufreq_policy *) init;
    void (*)(struct cpufreq_policy *) exit;
    int (*)(struct cpufreq_policy *) start;
    void (*)(struct cpufreq_policy *) stop;
    void (*)(struct cpufreq_policy *) limits;
    ssize_t (*)(struct cpufreq_policy *, char *) show_setspeed;
    int (*)(struct cpufreq_policy *, unsigned int) store_setspeed;
    struct list_head governor_list;
    struct module * owner;
    u8 flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct cpufreq_governor {
    char[16] name;
    int (*)(struct cpufreq_policy *) init;
    void (*)(struct cpufreq_policy *) exit;
    int (*)(struct cpufreq_policy *) start;
    void (*)(struct cpufreq_policy *) stop;
    void (*)(struct cpufreq_policy *) limits;
    ssize_t (*)(struct cpufreq_policy *, char *) show_setspeed;
    int (*)(struct cpufreq_policy *, unsigned int) store_setspeed;
    struct list_head governor_list;
    struct module * owner;
    u8 flags;
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
struct cpufreq_governor {
    char[16] name;
    int (*)(struct cpufreq_policy *) init;
    void (*)(struct cpufreq_policy *) exit;
    int (*)(struct cpufreq_policy *) start;
    void (*)(struct cpufreq_policy *) stop;
    void (*)(struct cpufreq_policy *) limits;
    ssize_t (*)(struct cpufreq_policy *, char *) show_setspeed;
    int (*)(struct cpufreq_policy *, unsigned int) store_setspeed;
    bool dynamic_switching;
    struct list_head governor_list;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct cpufreq_governor {
    char[16] name;
    int (*)(struct cpufreq_policy *) init;
    void (*)(struct cpufreq_policy *) exit;
    int (*)(struct cpufreq_policy *) start;
    void (*)(struct cpufreq_policy *) stop;
    void (*)(struct cpufreq_policy *) limits;
    ssize_t (*)(struct cpufreq_policy *, char *) show_setspeed;
    int (*)(struct cpufreq_policy *, unsigned int) store_setspeed;
    bool dynamic_switching;
    struct list_head governor_list;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct cpufreq_governor {
    char[16] name;
    int (*)(struct cpufreq_policy *) init;
    void (*)(struct cpufreq_policy *) exit;
    int (*)(struct cpufreq_policy *) start;
    void (*)(struct cpufreq_policy *) stop;
    void (*)(struct cpufreq_policy *) limits;
    ssize_t (*)(struct cpufreq_policy *, char *) show_setspeed;
    int (*)(struct cpufreq_policy *, unsigned int) store_setspeed;
    bool dynamic_switching;
    struct list_head governor_list;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct cpufreq_governor {
    char[16] name;
    int (*)(struct cpufreq_policy *) init;
    void (*)(struct cpufreq_policy *) exit;
    int (*)(struct cpufreq_policy *) start;
    void (*)(struct cpufreq_policy *) stop;
    void (*)(struct cpufreq_policy *) limits;
    ssize_t (*)(struct cpufreq_policy *, char *) show_setspeed;
    int (*)(struct cpufreq_policy *, unsigned int) store_setspeed;
    bool dynamic_switching;
    struct list_head governor_list;
    struct module * owner;
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
struct cpufreq_governor {
    char[16] name;
    int (*)(struct cpufreq_policy *) init;
    void (*)(struct cpufreq_policy *) exit;
    int (*)(struct cpufreq_policy *) start;
    void (*)(struct cpufreq_policy *) stop;
    void (*)(struct cpufreq_policy *) limits;
    ssize_t (*)(struct cpufreq_policy *, char *) show_setspeed;
    int (*)(struct cpufreq_policy *, unsigned int) store_setspeed;
    bool dynamic_switching;
    struct list_head governor_list;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct cpufreq_governor {
    char[16] name;
    int (*)(struct cpufreq_policy *) init;
    void (*)(struct cpufreq_policy *) exit;
    int (*)(struct cpufreq_policy *) start;
    void (*)(struct cpufreq_policy *) stop;
    void (*)(struct cpufreq_policy *) limits;
    ssize_t (*)(struct cpufreq_policy *, char *) show_setspeed;
    int (*)(struct cpufreq_policy *, unsigned int) store_setspeed;
    bool dynamic_switching;
    struct list_head governor_list;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct cpufreq_governor {
    char[16] name;
    int (*)(struct cpufreq_policy *) init;
    void (*)(struct cpufreq_policy *) exit;
    int (*)(struct cpufreq_policy *) start;
    void (*)(struct cpufreq_policy *) stop;
    void (*)(struct cpufreq_policy *) limits;
    ssize_t (*)(struct cpufreq_policy *, char *) show_setspeed;
    int (*)(struct cpufreq_policy *, unsigned int) store_setspeed;
    bool dynamic_switching;
    struct list_head governor_list;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct cpufreq_governor {
    char[16] name;
    int (*)(struct cpufreq_policy *) init;
    void (*)(struct cpufreq_policy *) exit;
    int (*)(struct cpufreq_policy *) start;
    void (*)(struct cpufreq_policy *) stop;
    void (*)(struct cpufreq_policy *) limits;
    ssize_t (*)(struct cpufreq_policy *, char *) show_setspeed;
    int (*)(struct cpufreq_policy *, unsigned int) store_setspeed;
    bool dynamic_switching;
    struct list_head governor_list;
    struct module * owner;
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
<code>int (*)(struct cpufreq_policy *) init</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct cpufreq_policy *) exit</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct cpufreq_policy *) start</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct cpufreq_policy *) stop</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct cpufreq_policy *) limits</code>
</li>
<li>
<b>Field removed. </b>
<code>int initialized</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct cpufreq_policy *, unsigned int) governor</code>
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
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool dynamic_switching</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int max_transition_latency</code>
</li>
</ul>
</details>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u8 flags</code>
</li>
<li>
<b>Field removed. </b>
<code>bool dynamic_switching</code>
</li>
</ul>
</details>
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
