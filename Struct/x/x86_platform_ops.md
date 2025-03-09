# Struct: <code>x86_platform_ops</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct x86_platform_ops {
    long unsigned int (*)() calibrate_tsc;
    void (*)(struct timespec *) get_wallclock;
    int (*)(const struct timespec *) set_wallclock;
    void (*)() iommu_shutdown;
    bool (*)(u64, u64) is_untracked_pat_range;
    void (*)() nmi_init;
    unsigned char (*)() get_nmi_reason;
    int (*)() i8042_detect;
    void (*)() save_sched_clock_state;
    void (*)() restore_sched_clock_state;
    void (*)() apic_post_init;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct x86_platform_ops {
    long unsigned int (*)() calibrate_cpu;
    long unsigned int (*)() calibrate_tsc;
    void (*)(struct timespec *) get_wallclock;
    int (*)(const struct timespec *) set_wallclock;
    void (*)() iommu_shutdown;
    bool (*)(u64, u64) is_untracked_pat_range;
    void (*)() nmi_init;
    unsigned char (*)() get_nmi_reason;
    int (*)() i8042_detect;
    void (*)() save_sched_clock_state;
    void (*)() restore_sched_clock_state;
    void (*)() apic_post_init;
    struct x86_legacy_features legacy;
    void (*)() set_legacy_features;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct x86_platform_ops {
    long unsigned int (*)() calibrate_cpu;
    long unsigned int (*)() calibrate_tsc;
    void (*)(struct timespec *) get_wallclock;
    int (*)(const struct timespec *) set_wallclock;
    void (*)() iommu_shutdown;
    bool (*)(u64, u64) is_untracked_pat_range;
    void (*)() nmi_init;
    unsigned char (*)() get_nmi_reason;
    void (*)() save_sched_clock_state;
    void (*)() restore_sched_clock_state;
    void (*)() apic_post_init;
    struct x86_legacy_features legacy;
    void (*)() set_legacy_features;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct x86_platform_ops {
    long unsigned int (*)() calibrate_cpu;
    long unsigned int (*)() calibrate_tsc;
    void (*)(struct timespec *) get_wallclock;
    int (*)(const struct timespec *) set_wallclock;
    void (*)() iommu_shutdown;
    bool (*)(u64, u64) is_untracked_pat_range;
    void (*)() nmi_init;
    unsigned char (*)() get_nmi_reason;
    void (*)() save_sched_clock_state;
    void (*)() restore_sched_clock_state;
    void (*)() apic_post_init;
    struct x86_legacy_features legacy;
    void (*)() set_legacy_features;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct x86_platform_ops {
    long unsigned int (*)() calibrate_cpu;
    long unsigned int (*)() calibrate_tsc;
    void (*)(struct timespec *) get_wallclock;
    int (*)(const struct timespec *) set_wallclock;
    void (*)() iommu_shutdown;
    bool (*)(u64, u64) is_untracked_pat_range;
    void (*)() nmi_init;
    unsigned char (*)() get_nmi_reason;
    void (*)() save_sched_clock_state;
    void (*)() restore_sched_clock_state;
    void (*)() apic_post_init;
    struct x86_legacy_features legacy;
    void (*)() set_legacy_features;
    struct x86_hyper_runtime hyper;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct x86_platform_ops {
    long unsigned int (*)() calibrate_cpu;
    long unsigned int (*)() calibrate_tsc;
    void (*)(struct timespec64 *) get_wallclock;
    int (*)(const struct timespec64 *) set_wallclock;
    void (*)() iommu_shutdown;
    bool (*)(u64, u64) is_untracked_pat_range;
    void (*)() nmi_init;
    unsigned char (*)() get_nmi_reason;
    void (*)() save_sched_clock_state;
    void (*)() restore_sched_clock_state;
    void (*)() apic_post_init;
    struct x86_legacy_features legacy;
    void (*)() set_legacy_features;
    struct x86_hyper_runtime hyper;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct x86_platform_ops {
    long unsigned int (*)() calibrate_cpu;
    long unsigned int (*)() calibrate_tsc;
    void (*)(struct timespec64 *) get_wallclock;
    int (*)(const struct timespec64 *) set_wallclock;
    void (*)() iommu_shutdown;
    bool (*)(u64, u64) is_untracked_pat_range;
    void (*)() nmi_init;
    unsigned char (*)() get_nmi_reason;
    void (*)() save_sched_clock_state;
    void (*)() restore_sched_clock_state;
    void (*)() apic_post_init;
    struct x86_legacy_features legacy;
    void (*)() set_legacy_features;
    struct x86_hyper_runtime hyper;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct x86_platform_ops {
    long unsigned int (*)() calibrate_cpu;
    long unsigned int (*)() calibrate_tsc;
    void (*)(struct timespec64 *) get_wallclock;
    int (*)(const struct timespec64 *) set_wallclock;
    void (*)() iommu_shutdown;
    bool (*)(u64, u64) is_untracked_pat_range;
    void (*)() nmi_init;
    unsigned char (*)() get_nmi_reason;
    void (*)() save_sched_clock_state;
    void (*)() restore_sched_clock_state;
    void (*)() apic_post_init;
    struct x86_legacy_features legacy;
    void (*)() set_legacy_features;
    struct x86_hyper_runtime hyper;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct x86_platform_ops {
    long unsigned int (*)() calibrate_cpu;
    long unsigned int (*)() calibrate_tsc;
    void (*)(struct timespec64 *) get_wallclock;
    int (*)(const struct timespec64 *) set_wallclock;
    void (*)() iommu_shutdown;
    bool (*)(u64, u64) is_untracked_pat_range;
    void (*)() nmi_init;
    unsigned char (*)() get_nmi_reason;
    void (*)() save_sched_clock_state;
    void (*)() restore_sched_clock_state;
    void (*)() apic_post_init;
    struct x86_legacy_features legacy;
    void (*)() set_legacy_features;
    struct x86_hyper_runtime hyper;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct x86_platform_ops {
    long unsigned int (*)() calibrate_cpu;
    long unsigned int (*)() calibrate_tsc;
    void (*)(struct timespec64 *) get_wallclock;
    int (*)(const struct timespec64 *) set_wallclock;
    void (*)() iommu_shutdown;
    bool (*)(u64, u64) is_untracked_pat_range;
    void (*)() nmi_init;
    unsigned char (*)() get_nmi_reason;
    void (*)() save_sched_clock_state;
    void (*)() restore_sched_clock_state;
    void (*)() apic_post_init;
    struct x86_legacy_features legacy;
    void (*)() set_legacy_features;
    struct x86_hyper_runtime hyper;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct x86_platform_ops {
    long unsigned int (*)() calibrate_cpu;
    long unsigned int (*)() calibrate_tsc;
    void (*)(struct timespec64 *) get_wallclock;
    int (*)(const struct timespec64 *) set_wallclock;
    void (*)() iommu_shutdown;
    bool (*)(u64, u64) is_untracked_pat_range;
    void (*)() nmi_init;
    unsigned char (*)() get_nmi_reason;
    void (*)() save_sched_clock_state;
    void (*)() restore_sched_clock_state;
    void (*)() apic_post_init;
    struct x86_legacy_features legacy;
    void (*)() set_legacy_features;
    struct x86_hyper_runtime hyper;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct x86_platform_ops {
    long unsigned int (*)() calibrate_cpu;
    long unsigned int (*)() calibrate_tsc;
    void (*)(struct timespec64 *) get_wallclock;
    int (*)(const struct timespec64 *) set_wallclock;
    void (*)() iommu_shutdown;
    bool (*)(u64, u64) is_untracked_pat_range;
    void (*)() nmi_init;
    unsigned char (*)() get_nmi_reason;
    void (*)() save_sched_clock_state;
    void (*)() restore_sched_clock_state;
    void (*)() apic_post_init;
    struct x86_legacy_features legacy;
    void (*)() set_legacy_features;
    struct x86_hyper_runtime hyper;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct x86_platform_ops {
    long unsigned int (*)() calibrate_cpu;
    long unsigned int (*)() calibrate_tsc;
    void (*)(struct timespec64 *) get_wallclock;
    int (*)(const struct timespec64 *) set_wallclock;
    void (*)() iommu_shutdown;
    bool (*)(u64, u64) is_untracked_pat_range;
    void (*)() nmi_init;
    unsigned char (*)() get_nmi_reason;
    void (*)() save_sched_clock_state;
    void (*)() restore_sched_clock_state;
    void (*)() apic_post_init;
    struct x86_legacy_features legacy;
    void (*)() set_legacy_features;
    struct x86_hyper_runtime hyper;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct x86_platform_ops {
    long unsigned int (*)() calibrate_cpu;
    long unsigned int (*)() calibrate_tsc;
    void (*)(struct timespec64 *) get_wallclock;
    int (*)(const struct timespec64 *) set_wallclock;
    void (*)() iommu_shutdown;
    bool (*)(u64, u64) is_untracked_pat_range;
    void (*)() nmi_init;
    unsigned char (*)() get_nmi_reason;
    void (*)() save_sched_clock_state;
    void (*)() restore_sched_clock_state;
    void (*)() apic_post_init;
    struct x86_legacy_features legacy;
    void (*)() set_legacy_features;
    struct x86_hyper_runtime hyper;
    struct x86_guest guest;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct x86_platform_ops {
    long unsigned int (*)() calibrate_cpu;
    long unsigned int (*)() calibrate_tsc;
    void (*)(struct timespec64 *) get_wallclock;
    int (*)(const struct timespec64 *) set_wallclock;
    void (*)() iommu_shutdown;
    bool (*)(u64, u64) is_untracked_pat_range;
    void (*)() nmi_init;
    unsigned char (*)() get_nmi_reason;
    void (*)() save_sched_clock_state;
    void (*)() restore_sched_clock_state;
    void (*)() apic_post_init;
    struct x86_legacy_features legacy;
    void (*)() set_legacy_features;
    void (*)() realmode_reserve;
    void (*)() realmode_init;
    struct x86_hyper_runtime hyper;
    struct x86_guest guest;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct x86_platform_ops {
    long unsigned int (*)() calibrate_cpu;
    long unsigned int (*)() calibrate_tsc;
    void (*)(struct timespec64 *) get_wallclock;
    int (*)(const struct timespec64 *) set_wallclock;
    void (*)() iommu_shutdown;
    bool (*)(u64, u64) is_untracked_pat_range;
    void (*)() nmi_init;
    unsigned char (*)() get_nmi_reason;
    void (*)() save_sched_clock_state;
    void (*)() restore_sched_clock_state;
    void (*)() apic_post_init;
    struct x86_legacy_features legacy;
    void (*)() set_legacy_features;
    void (*)() realmode_reserve;
    void (*)() realmode_init;
    struct x86_hyper_runtime hyper;
    struct x86_guest guest;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct x86_platform_ops {
    long unsigned int (*)() calibrate_cpu;
    long unsigned int (*)() calibrate_tsc;
    void (*)(struct timespec64 *) get_wallclock;
    int (*)(const struct timespec64 *) set_wallclock;
    void (*)() iommu_shutdown;
    bool (*)(u64, u64) is_untracked_pat_range;
    void (*)() nmi_init;
    unsigned char (*)() get_nmi_reason;
    void (*)() save_sched_clock_state;
    void (*)() restore_sched_clock_state;
    void (*)() apic_post_init;
    struct x86_legacy_features legacy;
    void (*)() set_legacy_features;
    void (*)() realmode_reserve;
    void (*)() realmode_init;
    struct x86_hyper_runtime hyper;
    struct x86_guest guest;
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct x86_platform_ops {
    long unsigned int (*)() calibrate_cpu;
    long unsigned int (*)() calibrate_tsc;
    void (*)(struct timespec64 *) get_wallclock;
    int (*)(const struct timespec64 *) set_wallclock;
    void (*)() iommu_shutdown;
    bool (*)(u64, u64) is_untracked_pat_range;
    void (*)() nmi_init;
    unsigned char (*)() get_nmi_reason;
    void (*)() save_sched_clock_state;
    void (*)() restore_sched_clock_state;
    void (*)() apic_post_init;
    struct x86_legacy_features legacy;
    void (*)() set_legacy_features;
    struct x86_hyper_runtime hyper;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct x86_platform_ops {
    long unsigned int (*)() calibrate_cpu;
    long unsigned int (*)() calibrate_tsc;
    void (*)(struct timespec64 *) get_wallclock;
    int (*)(const struct timespec64 *) set_wallclock;
    void (*)() iommu_shutdown;
    bool (*)(u64, u64) is_untracked_pat_range;
    void (*)() nmi_init;
    unsigned char (*)() get_nmi_reason;
    void (*)() save_sched_clock_state;
    void (*)() restore_sched_clock_state;
    void (*)() apic_post_init;
    struct x86_legacy_features legacy;
    void (*)() set_legacy_features;
    struct x86_hyper_runtime hyper;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct x86_platform_ops {
    long unsigned int (*)() calibrate_cpu;
    long unsigned int (*)() calibrate_tsc;
    void (*)(struct timespec64 *) get_wallclock;
    int (*)(const struct timespec64 *) set_wallclock;
    void (*)() iommu_shutdown;
    bool (*)(u64, u64) is_untracked_pat_range;
    void (*)() nmi_init;
    unsigned char (*)() get_nmi_reason;
    void (*)() save_sched_clock_state;
    void (*)() restore_sched_clock_state;
    void (*)() apic_post_init;
    struct x86_legacy_features legacy;
    void (*)() set_legacy_features;
    struct x86_hyper_runtime hyper;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct x86_platform_ops {
    long unsigned int (*)() calibrate_cpu;
    long unsigned int (*)() calibrate_tsc;
    void (*)(struct timespec64 *) get_wallclock;
    int (*)(const struct timespec64 *) set_wallclock;
    void (*)() iommu_shutdown;
    bool (*)(u64, u64) is_untracked_pat_range;
    void (*)() nmi_init;
    unsigned char (*)() get_nmi_reason;
    void (*)() save_sched_clock_state;
    void (*)() restore_sched_clock_state;
    void (*)() apic_post_init;
    struct x86_legacy_features legacy;
    void (*)() set_legacy_features;
    struct x86_hyper_runtime hyper;
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
<code>long unsigned int (*)() calibrate_cpu</code>
</li>
<li>
<b>Field added. </b>
<code>struct x86_legacy_features legacy</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)() set_legacy_features</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>int (*)() i8042_detect</code>
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
<code>struct x86_hyper_runtime hyper</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>void (*)(struct timespec *) get_wallclock</code> ➡️ <code>void (*)(struct timespec64 *) get_wallclock</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(const struct timespec *) set_wallclock</code> ➡️ <code>int (*)(const struct timespec64 *) set_wallclock</code>
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
<code>struct x86_guest guest</code>
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
<code>void (*)() realmode_reserve</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)() realmode_init</code>
</li>
</ul>
</details>
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
struct x86_platform_ops {
    long unsigned int (*)() calibrate_cpu;
    long unsigned int (*)() calibrate_tsc;
    void (*)(struct timespec64 *) get_wallclock;
    int (*)(const struct timespec64 *) set_wallclock;
    void (*)() iommu_shutdown;
    bool (*)(u64, u64) is_untracked_pat_range;
    void (*)() nmi_init;
    unsigned char (*)() get_nmi_reason;
    void (*)() save_sched_clock_state;
    void (*)() restore_sched_clock_state;
    void (*)() apic_post_init;
    struct x86_legacy_features legacy;
    void (*)() set_legacy_features;
    struct x86_hyper_runtime hyper;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct x86_platform_ops {
    long unsigned int (*)() calibrate_cpu;
    long unsigned int (*)() calibrate_tsc;
    void (*)(struct timespec64 *) get_wallclock;
    int (*)(const struct timespec64 *) set_wallclock;
    void (*)() iommu_shutdown;
    bool (*)(u64, u64) is_untracked_pat_range;
    void (*)() nmi_init;
    unsigned char (*)() get_nmi_reason;
    void (*)() save_sched_clock_state;
    void (*)() restore_sched_clock_state;
    void (*)() apic_post_init;
    struct x86_legacy_features legacy;
    void (*)() set_legacy_features;
    struct x86_hyper_runtime hyper;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct x86_platform_ops {
    long unsigned int (*)() calibrate_cpu;
    long unsigned int (*)() calibrate_tsc;
    void (*)(struct timespec64 *) get_wallclock;
    int (*)(const struct timespec64 *) set_wallclock;
    void (*)() iommu_shutdown;
    bool (*)(u64, u64) is_untracked_pat_range;
    void (*)() nmi_init;
    unsigned char (*)() get_nmi_reason;
    void (*)() save_sched_clock_state;
    void (*)() restore_sched_clock_state;
    void (*)() apic_post_init;
    struct x86_legacy_features legacy;
    void (*)() set_legacy_features;
    struct x86_hyper_runtime hyper;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct x86_platform_ops {
    long unsigned int (*)() calibrate_cpu;
    long unsigned int (*)() calibrate_tsc;
    void (*)(struct timespec64 *) get_wallclock;
    int (*)(const struct timespec64 *) set_wallclock;
    void (*)() iommu_shutdown;
    bool (*)(u64, u64) is_untracked_pat_range;
    void (*)() nmi_init;
    unsigned char (*)() get_nmi_reason;
    void (*)() save_sched_clock_state;
    void (*)() restore_sched_clock_state;
    void (*)() apic_post_init;
    struct x86_legacy_features legacy;
    void (*)() set_legacy_features;
    struct x86_hyper_runtime hyper;
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
