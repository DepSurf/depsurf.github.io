# Struct: <code>clocksource</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct clocksource {
    cycle_t (*)(struct clocksource *) read;
    cycle_t mask;
    u32 mult;
    u32 shift;
    u64 max_idle_ns;
    u32 maxadj;
    struct arch_clocksource_data archdata;
    u64 max_cycles;
    const char * name;
    struct list_head list;
    int rating;
    int (*)(struct clocksource *) enable;
    void (*)(struct clocksource *) disable;
    long unsigned int flags;
    void (*)(struct clocksource *) suspend;
    void (*)(struct clocksource *) resume;
    struct list_head wd_list;
    cycle_t cs_last;
    cycle_t wd_last;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct clocksource {
    cycle_t (*)(struct clocksource *) read;
    cycle_t mask;
    u32 mult;
    u32 shift;
    u64 max_idle_ns;
    u32 maxadj;
    struct arch_clocksource_data archdata;
    u64 max_cycles;
    const char * name;
    struct list_head list;
    int rating;
    int (*)(struct clocksource *) enable;
    void (*)(struct clocksource *) disable;
    long unsigned int flags;
    void (*)(struct clocksource *) suspend;
    void (*)(struct clocksource *) resume;
    struct list_head wd_list;
    cycle_t cs_last;
    cycle_t wd_last;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct clocksource {
    u64 (*)(struct clocksource *) read;
    u64 mask;
    u32 mult;
    u32 shift;
    u64 max_idle_ns;
    u32 maxadj;
    struct arch_clocksource_data archdata;
    u64 max_cycles;
    const char * name;
    struct list_head list;
    int rating;
    int (*)(struct clocksource *) enable;
    void (*)(struct clocksource *) disable;
    long unsigned int flags;
    void (*)(struct clocksource *) suspend;
    void (*)(struct clocksource *) resume;
    struct list_head wd_list;
    u64 cs_last;
    u64 wd_last;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct clocksource {
    u64 (*)(struct clocksource *) read;
    u64 mask;
    u32 mult;
    u32 shift;
    u64 max_idle_ns;
    u32 maxadj;
    struct arch_clocksource_data archdata;
    u64 max_cycles;
    const char * name;
    struct list_head list;
    int rating;
    int (*)(struct clocksource *) enable;
    void (*)(struct clocksource *) disable;
    long unsigned int flags;
    void (*)(struct clocksource *) suspend;
    void (*)(struct clocksource *) resume;
    void (*)(struct clocksource *) mark_unstable;
    void (*)(struct clocksource *) tick_stable;
    struct list_head wd_list;
    u64 cs_last;
    u64 wd_last;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct clocksource {
    u64 (*)(struct clocksource *) read;
    u64 mask;
    u32 mult;
    u32 shift;
    u64 max_idle_ns;
    u32 maxadj;
    struct arch_clocksource_data archdata;
    u64 max_cycles;
    const char * name;
    struct list_head list;
    int rating;
    int (*)(struct clocksource *) enable;
    void (*)(struct clocksource *) disable;
    long unsigned int flags;
    void (*)(struct clocksource *) suspend;
    void (*)(struct clocksource *) resume;
    void (*)(struct clocksource *) mark_unstable;
    void (*)(struct clocksource *) tick_stable;
    struct list_head wd_list;
    u64 cs_last;
    u64 wd_last;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct clocksource {
    u64 (*)(struct clocksource *) read;
    u64 mask;
    u32 mult;
    u32 shift;
    u64 max_idle_ns;
    u32 maxadj;
    struct arch_clocksource_data archdata;
    u64 max_cycles;
    const char * name;
    struct list_head list;
    int rating;
    int (*)(struct clocksource *) enable;
    void (*)(struct clocksource *) disable;
    long unsigned int flags;
    void (*)(struct clocksource *) suspend;
    void (*)(struct clocksource *) resume;
    void (*)(struct clocksource *) mark_unstable;
    void (*)(struct clocksource *) tick_stable;
    struct list_head wd_list;
    u64 cs_last;
    u64 wd_last;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct clocksource {
    u64 (*)(struct clocksource *) read;
    u64 mask;
    u32 mult;
    u32 shift;
    u64 max_idle_ns;
    u32 maxadj;
    struct arch_clocksource_data archdata;
    u64 max_cycles;
    const char * name;
    struct list_head list;
    int rating;
    int (*)(struct clocksource *) enable;
    void (*)(struct clocksource *) disable;
    long unsigned int flags;
    void (*)(struct clocksource *) suspend;
    void (*)(struct clocksource *) resume;
    void (*)(struct clocksource *) mark_unstable;
    void (*)(struct clocksource *) tick_stable;
    struct list_head wd_list;
    u64 cs_last;
    u64 wd_last;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct clocksource {
    u64 (*)(struct clocksource *) read;
    u64 mask;
    u32 mult;
    u32 shift;
    u64 max_idle_ns;
    u32 maxadj;
    struct arch_clocksource_data archdata;
    u64 max_cycles;
    const char * name;
    struct list_head list;
    int rating;
    int (*)(struct clocksource *) enable;
    void (*)(struct clocksource *) disable;
    long unsigned int flags;
    void (*)(struct clocksource *) suspend;
    void (*)(struct clocksource *) resume;
    void (*)(struct clocksource *) mark_unstable;
    void (*)(struct clocksource *) tick_stable;
    struct list_head wd_list;
    u64 cs_last;
    u64 wd_last;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct clocksource {
    u64 (*)(struct clocksource *) read;
    u64 mask;
    u32 mult;
    u32 shift;
    u64 max_idle_ns;
    u32 maxadj;
    struct arch_clocksource_data archdata;
    u64 max_cycles;
    const char * name;
    struct list_head list;
    int rating;
    int (*)(struct clocksource *) enable;
    void (*)(struct clocksource *) disable;
    long unsigned int flags;
    void (*)(struct clocksource *) suspend;
    void (*)(struct clocksource *) resume;
    void (*)(struct clocksource *) mark_unstable;
    void (*)(struct clocksource *) tick_stable;
    struct list_head wd_list;
    u64 cs_last;
    u64 wd_last;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct clocksource {
    u64 (*)(struct clocksource *) read;
    u64 mask;
    u32 mult;
    u32 shift;
    u64 max_idle_ns;
    u32 maxadj;
    u64 max_cycles;
    const char * name;
    struct list_head list;
    int rating;
    enum vdso_clock_mode vdso_clock_mode;
    long unsigned int flags;
    int (*)(struct clocksource *) enable;
    void (*)(struct clocksource *) disable;
    void (*)(struct clocksource *) suspend;
    void (*)(struct clocksource *) resume;
    void (*)(struct clocksource *) mark_unstable;
    void (*)(struct clocksource *) tick_stable;
    struct list_head wd_list;
    u64 cs_last;
    u64 wd_last;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct clocksource {
    u64 (*)(struct clocksource *) read;
    u64 mask;
    u32 mult;
    u32 shift;
    u64 max_idle_ns;
    u32 maxadj;
    u64 max_cycles;
    const char * name;
    struct list_head list;
    int rating;
    enum vdso_clock_mode vdso_clock_mode;
    long unsigned int flags;
    int (*)(struct clocksource *) enable;
    void (*)(struct clocksource *) disable;
    void (*)(struct clocksource *) suspend;
    void (*)(struct clocksource *) resume;
    void (*)(struct clocksource *) mark_unstable;
    void (*)(struct clocksource *) tick_stable;
    struct list_head wd_list;
    u64 cs_last;
    u64 wd_last;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct clocksource {
    u64 (*)(struct clocksource *) read;
    u64 mask;
    u32 mult;
    u32 shift;
    u64 max_idle_ns;
    u32 maxadj;
    u64 max_cycles;
    const char * name;
    struct list_head list;
    int rating;
    enum clocksource_ids id;
    enum vdso_clock_mode vdso_clock_mode;
    long unsigned int flags;
    int (*)(struct clocksource *) enable;
    void (*)(struct clocksource *) disable;
    void (*)(struct clocksource *) suspend;
    void (*)(struct clocksource *) resume;
    void (*)(struct clocksource *) mark_unstable;
    void (*)(struct clocksource *) tick_stable;
    struct list_head wd_list;
    u64 cs_last;
    u64 wd_last;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct clocksource {
    u64 (*)(struct clocksource *) read;
    u64 mask;
    u32 mult;
    u32 shift;
    u64 max_idle_ns;
    u32 maxadj;
    u32 uncertainty_margin;
    u64 max_cycles;
    const char * name;
    struct list_head list;
    int rating;
    enum clocksource_ids id;
    enum vdso_clock_mode vdso_clock_mode;
    long unsigned int flags;
    int (*)(struct clocksource *) enable;
    void (*)(struct clocksource *) disable;
    void (*)(struct clocksource *) suspend;
    void (*)(struct clocksource *) resume;
    void (*)(struct clocksource *) mark_unstable;
    void (*)(struct clocksource *) tick_stable;
    struct list_head wd_list;
    u64 cs_last;
    u64 wd_last;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct clocksource {
    u64 (*)(struct clocksource *) read;
    u64 mask;
    u32 mult;
    u32 shift;
    u64 max_idle_ns;
    u32 maxadj;
    u32 uncertainty_margin;
    u64 max_cycles;
    const char * name;
    struct list_head list;
    int rating;
    enum clocksource_ids id;
    enum vdso_clock_mode vdso_clock_mode;
    long unsigned int flags;
    int (*)(struct clocksource *) enable;
    void (*)(struct clocksource *) disable;
    void (*)(struct clocksource *) suspend;
    void (*)(struct clocksource *) resume;
    void (*)(struct clocksource *) mark_unstable;
    void (*)(struct clocksource *) tick_stable;
    struct list_head wd_list;
    u64 cs_last;
    u64 wd_last;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct clocksource {
    u64 (*)(struct clocksource *) read;
    u64 mask;
    u32 mult;
    u32 shift;
    u64 max_idle_ns;
    u32 maxadj;
    u32 uncertainty_margin;
    u64 max_cycles;
    const char * name;
    struct list_head list;
    int rating;
    enum clocksource_ids id;
    enum vdso_clock_mode vdso_clock_mode;
    long unsigned int flags;
    int (*)(struct clocksource *) enable;
    void (*)(struct clocksource *) disable;
    void (*)(struct clocksource *) suspend;
    void (*)(struct clocksource *) resume;
    void (*)(struct clocksource *) mark_unstable;
    void (*)(struct clocksource *) tick_stable;
    struct list_head wd_list;
    u64 cs_last;
    u64 wd_last;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct clocksource {
    u64 (*)(struct clocksource *) read;
    u64 mask;
    u32 mult;
    u32 shift;
    u64 max_idle_ns;
    u32 maxadj;
    u32 uncertainty_margin;
    u64 max_cycles;
    const char * name;
    struct list_head list;
    int rating;
    enum clocksource_ids id;
    enum vdso_clock_mode vdso_clock_mode;
    long unsigned int flags;
    int (*)(struct clocksource *) enable;
    void (*)(struct clocksource *) disable;
    void (*)(struct clocksource *) suspend;
    void (*)(struct clocksource *) resume;
    void (*)(struct clocksource *) mark_unstable;
    void (*)(struct clocksource *) tick_stable;
    struct list_head wd_list;
    u64 cs_last;
    u64 wd_last;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct clocksource {
    u64 (*)(struct clocksource *) read;
    u64 mask;
    u32 mult;
    u32 shift;
    u64 max_idle_ns;
    u32 maxadj;
    u32 uncertainty_margin;
    u64 max_cycles;
    const char * name;
    struct list_head list;
    int rating;
    enum clocksource_ids id;
    enum vdso_clock_mode vdso_clock_mode;
    long unsigned int flags;
    int (*)(struct clocksource *) enable;
    void (*)(struct clocksource *) disable;
    void (*)(struct clocksource *) suspend;
    void (*)(struct clocksource *) resume;
    void (*)(struct clocksource *) mark_unstable;
    void (*)(struct clocksource *) tick_stable;
    struct list_head wd_list;
    u64 cs_last;
    u64 wd_last;
    struct module * owner;
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
struct clocksource {
    u64 (*)(struct clocksource *) read;
    u64 mask;
    u32 mult;
    u32 shift;
    u64 max_idle_ns;
    u32 maxadj;
    struct arch_clocksource_data archdata;
    u64 max_cycles;
    const char * name;
    struct list_head list;
    int rating;
    int (*)(struct clocksource *) enable;
    void (*)(struct clocksource *) disable;
    long unsigned int flags;
    void (*)(struct clocksource *) suspend;
    void (*)(struct clocksource *) resume;
    void (*)(struct clocksource *) mark_unstable;
    void (*)(struct clocksource *) tick_stable;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct clocksource {
    u64 (*)(struct clocksource *) read;
    u64 mask;
    u32 mult;
    u32 shift;
    u64 max_idle_ns;
    u32 maxadj;
    struct arch_clocksource_data archdata;
    u64 max_cycles;
    const char * name;
    struct list_head list;
    int rating;
    int (*)(struct clocksource *) enable;
    void (*)(struct clocksource *) disable;
    long unsigned int flags;
    void (*)(struct clocksource *) suspend;
    void (*)(struct clocksource *) resume;
    void (*)(struct clocksource *) mark_unstable;
    void (*)(struct clocksource *) tick_stable;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct clocksource {
    u64 (*)(struct clocksource *) read;
    u64 mask;
    u32 mult;
    u32 shift;
    u64 max_idle_ns;
    u32 maxadj;
    u64 max_cycles;
    const char * name;
    struct list_head list;
    int rating;
    int (*)(struct clocksource *) enable;
    void (*)(struct clocksource *) disable;
    long unsigned int flags;
    void (*)(struct clocksource *) suspend;
    void (*)(struct clocksource *) resume;
    void (*)(struct clocksource *) mark_unstable;
    void (*)(struct clocksource *) tick_stable;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct clocksource {
    u64 (*)(struct clocksource *) read;
    u64 mask;
    u32 mult;
    u32 shift;
    u64 max_idle_ns;
    u32 maxadj;
    u64 max_cycles;
    const char * name;
    struct list_head list;
    int rating;
    int (*)(struct clocksource *) enable;
    void (*)(struct clocksource *) disable;
    long unsigned int flags;
    void (*)(struct clocksource *) suspend;
    void (*)(struct clocksource *) resume;
    void (*)(struct clocksource *) mark_unstable;
    void (*)(struct clocksource *) tick_stable;
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
struct clocksource {
    u64 (*)(struct clocksource *) read;
    u64 mask;
    u32 mult;
    u32 shift;
    u64 max_idle_ns;
    u32 maxadj;
    struct arch_clocksource_data archdata;
    u64 max_cycles;
    const char * name;
    struct list_head list;
    int rating;
    int (*)(struct clocksource *) enable;
    void (*)(struct clocksource *) disable;
    long unsigned int flags;
    void (*)(struct clocksource *) suspend;
    void (*)(struct clocksource *) resume;
    void (*)(struct clocksource *) mark_unstable;
    void (*)(struct clocksource *) tick_stable;
    struct list_head wd_list;
    u64 cs_last;
    u64 wd_last;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct clocksource {
    u64 (*)(struct clocksource *) read;
    u64 mask;
    u32 mult;
    u32 shift;
    u64 max_idle_ns;
    u32 maxadj;
    struct arch_clocksource_data archdata;
    u64 max_cycles;
    const char * name;
    struct list_head list;
    int rating;
    int (*)(struct clocksource *) enable;
    void (*)(struct clocksource *) disable;
    long unsigned int flags;
    void (*)(struct clocksource *) suspend;
    void (*)(struct clocksource *) resume;
    void (*)(struct clocksource *) mark_unstable;
    void (*)(struct clocksource *) tick_stable;
    struct list_head wd_list;
    u64 cs_last;
    u64 wd_last;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct clocksource {
    u64 (*)(struct clocksource *) read;
    u64 mask;
    u32 mult;
    u32 shift;
    u64 max_idle_ns;
    u32 maxadj;
    struct arch_clocksource_data archdata;
    u64 max_cycles;
    const char * name;
    struct list_head list;
    int rating;
    int (*)(struct clocksource *) enable;
    void (*)(struct clocksource *) disable;
    long unsigned int flags;
    void (*)(struct clocksource *) suspend;
    void (*)(struct clocksource *) resume;
    void (*)(struct clocksource *) mark_unstable;
    void (*)(struct clocksource *) tick_stable;
    struct list_head wd_list;
    u64 cs_last;
    u64 wd_last;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct clocksource {
    u64 (*)(struct clocksource *) read;
    u64 mask;
    u32 mult;
    u32 shift;
    u64 max_idle_ns;
    u32 maxadj;
    struct arch_clocksource_data archdata;
    u64 max_cycles;
    const char * name;
    struct list_head list;
    int rating;
    int (*)(struct clocksource *) enable;
    void (*)(struct clocksource *) disable;
    long unsigned int flags;
    void (*)(struct clocksource *) suspend;
    void (*)(struct clocksource *) resume;
    void (*)(struct clocksource *) mark_unstable;
    void (*)(struct clocksource *) tick_stable;
    struct list_head wd_list;
    u64 cs_last;
    u64 wd_last;
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>cycle_t (*)(struct clocksource *) read</code> ➡️ <code>u64 (*)(struct clocksource *) read</code>
</li>
<li>
<b>Field type changed. </b>
<code>cycle_t mask</code> ➡️ <code>u64 mask</code>
</li>
<li>
<b>Field type changed. </b>
<code>cycle_t cs_last</code> ➡️ <code>u64 cs_last</code>
</li>
<li>
<b>Field type changed. </b>
<code>cycle_t wd_last</code> ➡️ <code>u64 wd_last</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>void (*)(struct clocksource *) mark_unstable</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct clocksource *) tick_stable</code>
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
<b>Field added. </b>
<code>enum vdso_clock_mode vdso_clock_mode</code>
</li>
<li>
<b>Field removed. </b>
<code>struct arch_clocksource_data archdata</code>
</li>
</ul>
</details>
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
<code>enum clocksource_ids id</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u32 uncertainty_margin</code>
</li>
</ul>
</details>
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
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>struct list_head wd_list</code>
</li>
<li>
<b>Field removed. </b>
<code>u64 cs_last</code>
</li>
<li>
<b>Field removed. </b>
<code>u64 wd_last</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>struct list_head wd_list</code>
</li>
<li>
<b>Field removed. </b>
<code>u64 cs_last</code>
</li>
<li>
<b>Field removed. </b>
<code>u64 wd_last</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>struct arch_clocksource_data archdata</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head wd_list</code>
</li>
<li>
<b>Field removed. </b>
<code>u64 cs_last</code>
</li>
<li>
<b>Field removed. </b>
<code>u64 wd_last</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>struct arch_clocksource_data archdata</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head wd_list</code>
</li>
<li>
<b>Field removed. </b>
<code>u64 cs_last</code>
</li>
<li>
<b>Field removed. </b>
<code>u64 wd_last</code>
</li>
</ul>
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
