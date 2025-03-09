# Struct: <code>tick_sched</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct tick_sched {
    struct hrtimer sched_timer;
    long unsigned int check_clocks;
    enum tick_nohz_mode nohz_mode;
    ktime_t last_tick;
    int inidle;
    int tick_stopped;
    long unsigned int idle_jiffies;
    long unsigned int idle_calls;
    long unsigned int idle_sleeps;
    int idle_active;
    ktime_t idle_entrytime;
    ktime_t idle_waketime;
    ktime_t idle_exittime;
    ktime_t idle_sleeptime;
    ktime_t iowait_sleeptime;
    ktime_t sleep_length;
    long unsigned int last_jiffies;
    u64 next_timer;
    ktime_t idle_expires;
    int do_timer_last;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct tick_sched {
    struct hrtimer sched_timer;
    long unsigned int check_clocks;
    enum tick_nohz_mode nohz_mode;
    ktime_t last_tick;
    int inidle;
    int tick_stopped;
    long unsigned int idle_jiffies;
    long unsigned int idle_calls;
    long unsigned int idle_sleeps;
    int idle_active;
    ktime_t idle_entrytime;
    ktime_t idle_waketime;
    ktime_t idle_exittime;
    ktime_t idle_sleeptime;
    ktime_t iowait_sleeptime;
    ktime_t sleep_length;
    long unsigned int last_jiffies;
    u64 next_timer;
    ktime_t idle_expires;
    int do_timer_last;
    atomic_t tick_dep_mask;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct tick_sched {
    struct hrtimer sched_timer;
    long unsigned int check_clocks;
    enum tick_nohz_mode nohz_mode;
    ktime_t last_tick;
    int inidle;
    int tick_stopped;
    long unsigned int idle_jiffies;
    long unsigned int idle_calls;
    long unsigned int idle_sleeps;
    int idle_active;
    ktime_t idle_entrytime;
    ktime_t idle_waketime;
    ktime_t idle_exittime;
    ktime_t idle_sleeptime;
    ktime_t iowait_sleeptime;
    ktime_t sleep_length;
    long unsigned int last_jiffies;
    u64 next_timer;
    ktime_t idle_expires;
    int do_timer_last;
    atomic_t tick_dep_mask;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct tick_sched {
    struct hrtimer sched_timer;
    long unsigned int check_clocks;
    enum tick_nohz_mode nohz_mode;
    ktime_t last_tick;
    ktime_t next_tick;
    int inidle;
    int tick_stopped;
    long unsigned int idle_jiffies;
    long unsigned int idle_calls;
    long unsigned int idle_sleeps;
    int idle_active;
    ktime_t idle_entrytime;
    ktime_t idle_waketime;
    ktime_t idle_exittime;
    ktime_t idle_sleeptime;
    ktime_t iowait_sleeptime;
    ktime_t sleep_length;
    long unsigned int last_jiffies;
    u64 next_timer;
    ktime_t idle_expires;
    int do_timer_last;
    atomic_t tick_dep_mask;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct tick_sched {
    struct hrtimer sched_timer;
    long unsigned int check_clocks;
    enum tick_nohz_mode nohz_mode;
    ktime_t last_tick;
    ktime_t next_tick;
    int inidle;
    int tick_stopped;
    long unsigned int idle_jiffies;
    long unsigned int idle_calls;
    long unsigned int idle_sleeps;
    int idle_active;
    ktime_t idle_entrytime;
    ktime_t idle_waketime;
    ktime_t idle_exittime;
    ktime_t idle_sleeptime;
    ktime_t iowait_sleeptime;
    ktime_t sleep_length;
    long unsigned int last_jiffies;
    u64 next_timer;
    ktime_t idle_expires;
    int do_timer_last;
    atomic_t tick_dep_mask;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct tick_sched {
    struct hrtimer sched_timer;
    long unsigned int check_clocks;
    enum tick_nohz_mode nohz_mode;
    unsigned int inidle;
    unsigned int tick_stopped;
    unsigned int idle_active;
    unsigned int do_timer_last;
    unsigned int got_idle_tick;
    ktime_t last_tick;
    ktime_t next_tick;
    long unsigned int idle_jiffies;
    long unsigned int idle_calls;
    long unsigned int idle_sleeps;
    ktime_t idle_entrytime;
    ktime_t idle_waketime;
    ktime_t idle_exittime;
    ktime_t idle_sleeptime;
    ktime_t iowait_sleeptime;
    long unsigned int last_jiffies;
    u64 timer_expires;
    u64 timer_expires_base;
    u64 next_timer;
    ktime_t idle_expires;
    atomic_t tick_dep_mask;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct tick_sched {
    struct hrtimer sched_timer;
    long unsigned int check_clocks;
    enum tick_nohz_mode nohz_mode;
    unsigned int inidle;
    unsigned int tick_stopped;
    unsigned int idle_active;
    unsigned int do_timer_last;
    unsigned int got_idle_tick;
    ktime_t last_tick;
    ktime_t next_tick;
    long unsigned int idle_jiffies;
    long unsigned int idle_calls;
    long unsigned int idle_sleeps;
    ktime_t idle_entrytime;
    ktime_t idle_waketime;
    ktime_t idle_exittime;
    ktime_t idle_sleeptime;
    ktime_t iowait_sleeptime;
    long unsigned int last_jiffies;
    u64 timer_expires;
    u64 timer_expires_base;
    u64 next_timer;
    ktime_t idle_expires;
    atomic_t tick_dep_mask;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct tick_sched {
    struct hrtimer sched_timer;
    long unsigned int check_clocks;
    enum tick_nohz_mode nohz_mode;
    unsigned int inidle;
    unsigned int tick_stopped;
    unsigned int idle_active;
    unsigned int do_timer_last;
    unsigned int got_idle_tick;
    ktime_t last_tick;
    ktime_t next_tick;
    long unsigned int idle_jiffies;
    long unsigned int idle_calls;
    long unsigned int idle_sleeps;
    ktime_t idle_entrytime;
    ktime_t idle_waketime;
    ktime_t idle_exittime;
    ktime_t idle_sleeptime;
    ktime_t iowait_sleeptime;
    long unsigned int last_jiffies;
    u64 timer_expires;
    u64 timer_expires_base;
    u64 next_timer;
    ktime_t idle_expires;
    atomic_t tick_dep_mask;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct tick_sched {
    struct hrtimer sched_timer;
    long unsigned int check_clocks;
    enum tick_nohz_mode nohz_mode;
    unsigned int inidle;
    unsigned int tick_stopped;
    unsigned int idle_active;
    unsigned int do_timer_last;
    unsigned int got_idle_tick;
    ktime_t last_tick;
    ktime_t next_tick;
    long unsigned int idle_jiffies;
    long unsigned int idle_calls;
    long unsigned int idle_sleeps;
    ktime_t idle_entrytime;
    ktime_t idle_waketime;
    ktime_t idle_exittime;
    ktime_t idle_sleeptime;
    ktime_t iowait_sleeptime;
    long unsigned int last_jiffies;
    u64 timer_expires;
    u64 timer_expires_base;
    u64 next_timer;
    ktime_t idle_expires;
    atomic_t tick_dep_mask;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct tick_sched {
    struct hrtimer sched_timer;
    long unsigned int check_clocks;
    enum tick_nohz_mode nohz_mode;
    unsigned int inidle;
    unsigned int tick_stopped;
    unsigned int idle_active;
    unsigned int do_timer_last;
    unsigned int got_idle_tick;
    ktime_t last_tick;
    ktime_t next_tick;
    long unsigned int idle_jiffies;
    long unsigned int idle_calls;
    long unsigned int idle_sleeps;
    ktime_t idle_entrytime;
    ktime_t idle_waketime;
    ktime_t idle_exittime;
    ktime_t idle_sleeptime;
    ktime_t iowait_sleeptime;
    long unsigned int last_jiffies;
    u64 timer_expires;
    u64 timer_expires_base;
    u64 next_timer;
    ktime_t idle_expires;
    atomic_t tick_dep_mask;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct tick_sched {
    struct hrtimer sched_timer;
    long unsigned int check_clocks;
    enum tick_nohz_mode nohz_mode;
    unsigned int inidle;
    unsigned int tick_stopped;
    unsigned int idle_active;
    unsigned int do_timer_last;
    unsigned int got_idle_tick;
    ktime_t last_tick;
    ktime_t next_tick;
    long unsigned int idle_jiffies;
    long unsigned int idle_calls;
    long unsigned int idle_sleeps;
    ktime_t idle_entrytime;
    ktime_t idle_waketime;
    ktime_t idle_exittime;
    ktime_t idle_sleeptime;
    ktime_t iowait_sleeptime;
    long unsigned int last_jiffies;
    u64 timer_expires;
    u64 timer_expires_base;
    u64 next_timer;
    ktime_t idle_expires;
    atomic_t tick_dep_mask;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct tick_sched {
    struct hrtimer sched_timer;
    long unsigned int check_clocks;
    enum tick_nohz_mode nohz_mode;
    unsigned int inidle;
    unsigned int tick_stopped;
    unsigned int idle_active;
    unsigned int do_timer_last;
    unsigned int got_idle_tick;
    ktime_t last_tick;
    ktime_t next_tick;
    long unsigned int idle_jiffies;
    long unsigned int idle_calls;
    long unsigned int idle_sleeps;
    ktime_t idle_entrytime;
    ktime_t idle_waketime;
    ktime_t idle_exittime;
    ktime_t idle_sleeptime;
    ktime_t iowait_sleeptime;
    long unsigned int last_jiffies;
    u64 timer_expires;
    u64 timer_expires_base;
    u64 next_timer;
    ktime_t idle_expires;
    atomic_t tick_dep_mask;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct tick_sched {
    struct hrtimer sched_timer;
    long unsigned int check_clocks;
    enum tick_nohz_mode nohz_mode;
    unsigned int inidle;
    unsigned int tick_stopped;
    unsigned int idle_active;
    unsigned int do_timer_last;
    unsigned int got_idle_tick;
    ktime_t last_tick;
    ktime_t next_tick;
    long unsigned int idle_jiffies;
    long unsigned int idle_calls;
    long unsigned int idle_sleeps;
    ktime_t idle_entrytime;
    ktime_t idle_waketime;
    ktime_t idle_exittime;
    ktime_t idle_sleeptime;
    ktime_t iowait_sleeptime;
    long unsigned int last_jiffies;
    u64 timer_expires;
    u64 timer_expires_base;
    u64 next_timer;
    ktime_t idle_expires;
    atomic_t tick_dep_mask;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct tick_sched {
    struct hrtimer sched_timer;
    long unsigned int check_clocks;
    enum tick_nohz_mode nohz_mode;
    unsigned int inidle;
    unsigned int tick_stopped;
    unsigned int idle_active;
    unsigned int do_timer_last;
    unsigned int got_idle_tick;
    ktime_t last_tick;
    ktime_t next_tick;
    long unsigned int idle_jiffies;
    long unsigned int idle_calls;
    long unsigned int idle_sleeps;
    ktime_t idle_entrytime;
    ktime_t idle_waketime;
    ktime_t idle_exittime;
    ktime_t idle_sleeptime;
    ktime_t iowait_sleeptime;
    long unsigned int last_jiffies;
    u64 timer_expires;
    u64 timer_expires_base;
    u64 next_timer;
    ktime_t idle_expires;
    atomic_t tick_dep_mask;
    long unsigned int last_tick_jiffies;
    unsigned int stalled_jiffies;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct tick_sched {
    struct hrtimer sched_timer;
    long unsigned int check_clocks;
    enum tick_nohz_mode nohz_mode;
    unsigned int inidle;
    unsigned int tick_stopped;
    unsigned int idle_active;
    unsigned int do_timer_last;
    unsigned int got_idle_tick;
    ktime_t last_tick;
    ktime_t next_tick;
    long unsigned int idle_jiffies;
    long unsigned int idle_calls;
    long unsigned int idle_sleeps;
    ktime_t idle_entrytime;
    ktime_t idle_waketime;
    ktime_t idle_exittime;
    ktime_t idle_sleeptime;
    ktime_t iowait_sleeptime;
    long unsigned int last_jiffies;
    u64 timer_expires;
    u64 timer_expires_base;
    u64 next_timer;
    ktime_t idle_expires;
    atomic_t tick_dep_mask;
    long unsigned int last_tick_jiffies;
    unsigned int stalled_jiffies;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct tick_sched {
    unsigned int inidle;
    unsigned int tick_stopped;
    unsigned int idle_active;
    unsigned int do_timer_last;
    unsigned int got_idle_tick;
    unsigned int stalled_jiffies;
    long unsigned int last_tick_jiffies;
    struct hrtimer sched_timer;
    ktime_t last_tick;
    ktime_t next_tick;
    long unsigned int idle_jiffies;
    ktime_t idle_waketime;
    seqcount_t idle_sleeptime_seq;
    ktime_t idle_entrytime;
    enum tick_nohz_mode nohz_mode;
    long unsigned int last_jiffies;
    u64 timer_expires_base;
    u64 timer_expires;
    u64 next_timer;
    ktime_t idle_expires;
    long unsigned int idle_calls;
    long unsigned int idle_sleeps;
    ktime_t idle_exittime;
    ktime_t idle_sleeptime;
    ktime_t iowait_sleeptime;
    atomic_t tick_dep_mask;
    long unsigned int check_clocks;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct tick_sched {
    unsigned int inidle;
    unsigned int tick_stopped;
    unsigned int idle_active;
    unsigned int do_timer_last;
    unsigned int got_idle_tick;
    unsigned int stalled_jiffies;
    long unsigned int last_tick_jiffies;
    struct hrtimer sched_timer;
    ktime_t last_tick;
    ktime_t next_tick;
    long unsigned int idle_jiffies;
    ktime_t idle_waketime;
    seqcount_t idle_sleeptime_seq;
    ktime_t idle_entrytime;
    enum tick_nohz_mode nohz_mode;
    long unsigned int last_jiffies;
    u64 timer_expires_base;
    u64 timer_expires;
    u64 next_timer;
    ktime_t idle_expires;
    long unsigned int idle_calls;
    long unsigned int idle_sleeps;
    ktime_t idle_exittime;
    ktime_t idle_sleeptime;
    ktime_t iowait_sleeptime;
    atomic_t tick_dep_mask;
    long unsigned int check_clocks;
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
struct tick_sched {
    struct hrtimer sched_timer;
    long unsigned int check_clocks;
    enum tick_nohz_mode nohz_mode;
    unsigned int inidle;
    unsigned int tick_stopped;
    unsigned int idle_active;
    unsigned int do_timer_last;
    unsigned int got_idle_tick;
    ktime_t last_tick;
    ktime_t next_tick;
    long unsigned int idle_jiffies;
    long unsigned int idle_calls;
    long unsigned int idle_sleeps;
    ktime_t idle_entrytime;
    ktime_t idle_waketime;
    ktime_t idle_exittime;
    ktime_t idle_sleeptime;
    ktime_t iowait_sleeptime;
    long unsigned int last_jiffies;
    u64 timer_expires;
    u64 timer_expires_base;
    u64 next_timer;
    ktime_t idle_expires;
    atomic_t tick_dep_mask;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct tick_sched {
    struct hrtimer sched_timer;
    long unsigned int check_clocks;
    enum tick_nohz_mode nohz_mode;
    unsigned int inidle;
    unsigned int tick_stopped;
    unsigned int idle_active;
    unsigned int do_timer_last;
    unsigned int got_idle_tick;
    ktime_t last_tick;
    ktime_t next_tick;
    long unsigned int idle_jiffies;
    long unsigned int idle_calls;
    long unsigned int idle_sleeps;
    ktime_t idle_entrytime;
    ktime_t idle_waketime;
    ktime_t idle_exittime;
    ktime_t idle_sleeptime;
    ktime_t iowait_sleeptime;
    long unsigned int last_jiffies;
    u64 timer_expires;
    u64 timer_expires_base;
    u64 next_timer;
    ktime_t idle_expires;
    atomic_t tick_dep_mask;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct tick_sched {
    struct hrtimer sched_timer;
    long unsigned int check_clocks;
    enum tick_nohz_mode nohz_mode;
    unsigned int inidle;
    unsigned int tick_stopped;
    unsigned int idle_active;
    unsigned int do_timer_last;
    unsigned int got_idle_tick;
    ktime_t last_tick;
    ktime_t next_tick;
    long unsigned int idle_jiffies;
    long unsigned int idle_calls;
    long unsigned int idle_sleeps;
    ktime_t idle_entrytime;
    ktime_t idle_waketime;
    ktime_t idle_exittime;
    ktime_t idle_sleeptime;
    ktime_t iowait_sleeptime;
    long unsigned int last_jiffies;
    u64 timer_expires;
    u64 timer_expires_base;
    u64 next_timer;
    ktime_t idle_expires;
    atomic_t tick_dep_mask;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct tick_sched {
    struct hrtimer sched_timer;
    long unsigned int check_clocks;
    enum tick_nohz_mode nohz_mode;
    unsigned int inidle;
    unsigned int tick_stopped;
    unsigned int idle_active;
    unsigned int do_timer_last;
    unsigned int got_idle_tick;
    ktime_t last_tick;
    ktime_t next_tick;
    long unsigned int idle_jiffies;
    long unsigned int idle_calls;
    long unsigned int idle_sleeps;
    ktime_t idle_entrytime;
    ktime_t idle_waketime;
    ktime_t idle_exittime;
    ktime_t idle_sleeptime;
    ktime_t iowait_sleeptime;
    long unsigned int last_jiffies;
    u64 timer_expires;
    u64 timer_expires_base;
    u64 next_timer;
    ktime_t idle_expires;
    atomic_t tick_dep_mask;
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
struct tick_sched {
    struct hrtimer sched_timer;
    long unsigned int check_clocks;
    enum tick_nohz_mode nohz_mode;
    unsigned int inidle;
    unsigned int tick_stopped;
    unsigned int idle_active;
    unsigned int do_timer_last;
    unsigned int got_idle_tick;
    ktime_t last_tick;
    ktime_t next_tick;
    long unsigned int idle_jiffies;
    long unsigned int idle_calls;
    long unsigned int idle_sleeps;
    ktime_t idle_entrytime;
    ktime_t idle_waketime;
    ktime_t idle_exittime;
    ktime_t idle_sleeptime;
    ktime_t iowait_sleeptime;
    long unsigned int last_jiffies;
    u64 timer_expires;
    u64 timer_expires_base;
    u64 next_timer;
    ktime_t idle_expires;
    atomic_t tick_dep_mask;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct tick_sched {
    struct hrtimer sched_timer;
    long unsigned int check_clocks;
    enum tick_nohz_mode nohz_mode;
    unsigned int inidle;
    unsigned int tick_stopped;
    unsigned int idle_active;
    unsigned int do_timer_last;
    unsigned int got_idle_tick;
    ktime_t last_tick;
    ktime_t next_tick;
    long unsigned int idle_jiffies;
    long unsigned int idle_calls;
    long unsigned int idle_sleeps;
    ktime_t idle_entrytime;
    ktime_t idle_waketime;
    ktime_t idle_exittime;
    ktime_t idle_sleeptime;
    ktime_t iowait_sleeptime;
    long unsigned int last_jiffies;
    u64 timer_expires;
    u64 timer_expires_base;
    u64 next_timer;
    ktime_t idle_expires;
    atomic_t tick_dep_mask;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct tick_sched {
    struct hrtimer sched_timer;
    long unsigned int check_clocks;
    enum tick_nohz_mode nohz_mode;
    unsigned int inidle;
    unsigned int tick_stopped;
    unsigned int idle_active;
    unsigned int do_timer_last;
    unsigned int got_idle_tick;
    ktime_t last_tick;
    ktime_t next_tick;
    long unsigned int idle_jiffies;
    long unsigned int idle_calls;
    long unsigned int idle_sleeps;
    ktime_t idle_entrytime;
    ktime_t idle_waketime;
    ktime_t idle_exittime;
    ktime_t idle_sleeptime;
    ktime_t iowait_sleeptime;
    long unsigned int last_jiffies;
    u64 timer_expires;
    u64 timer_expires_base;
    u64 next_timer;
    ktime_t idle_expires;
    atomic_t tick_dep_mask;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct tick_sched {
    struct hrtimer sched_timer;
    long unsigned int check_clocks;
    enum tick_nohz_mode nohz_mode;
    unsigned int inidle;
    unsigned int tick_stopped;
    unsigned int idle_active;
    unsigned int do_timer_last;
    unsigned int got_idle_tick;
    ktime_t last_tick;
    ktime_t next_tick;
    long unsigned int idle_jiffies;
    long unsigned int idle_calls;
    long unsigned int idle_sleeps;
    ktime_t idle_entrytime;
    ktime_t idle_waketime;
    ktime_t idle_exittime;
    ktime_t idle_sleeptime;
    ktime_t iowait_sleeptime;
    long unsigned int last_jiffies;
    u64 timer_expires;
    u64 timer_expires_base;
    u64 next_timer;
    ktime_t idle_expires;
    atomic_t tick_dep_mask;
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
<code>atomic_t tick_dep_mask</code>
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
<code>ktime_t next_tick</code>
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
<b>Field added. </b>
<code>unsigned int got_idle_tick</code>
</li>
<li>
<b>Field added. </b>
<code>u64 timer_expires</code>
</li>
<li>
<b>Field added. </b>
<code>u64 timer_expires_base</code>
</li>
<li>
<b>Field removed. </b>
<code>ktime_t sleep_length</code>
</li>
<li>
<b>Field type changed. </b>
<code>int inidle</code> ➡️ <code>unsigned int inidle</code>
</li>
<li>
<b>Field type changed. </b>
<code>int tick_stopped</code> ➡️ <code>unsigned int tick_stopped</code>
</li>
<li>
<b>Field type changed. </b>
<code>int idle_active</code> ➡️ <code>unsigned int idle_active</code>
</li>
<li>
<b>Field type changed. </b>
<code>int do_timer_last</code> ➡️ <code>unsigned int do_timer_last</code>
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>long unsigned int last_tick_jiffies</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int stalled_jiffies</code>
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
<code>seqcount_t idle_sleeptime_seq</code>
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
