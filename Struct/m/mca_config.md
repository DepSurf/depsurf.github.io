# Struct: <code>mca_config</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct mca_config {
    bool dont_log_ce;
    bool cmci_disabled;
    bool lmce_disabled;
    bool ignore_ce;
    bool disabled;
    bool ser;
    bool bios_cmci_threshold;
    u8 banks;
    s8 bootlog;
    int tolerant;
    int monarch_timeout;
    int panic_timeout;
    u32 rip_msr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct mca_config {
    bool dont_log_ce;
    bool cmci_disabled;
    bool lmce_disabled;
    bool ignore_ce;
    bool disabled;
    bool ser;
    bool recovery;
    bool bios_cmci_threshold;
    u8 banks;
    s8 bootlog;
    int tolerant;
    int monarch_timeout;
    int panic_timeout;
    u32 rip_msr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct mca_config {
    bool dont_log_ce;
    bool cmci_disabled;
    bool lmce_disabled;
    bool ignore_ce;
    bool disabled;
    bool ser;
    bool recovery;
    bool bios_cmci_threshold;
    u8 banks;
    s8 bootlog;
    int tolerant;
    int monarch_timeout;
    int panic_timeout;
    u32 rip_msr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct mca_config {
    bool dont_log_ce;
    bool cmci_disabled;
    bool lmce_disabled;
    bool ignore_ce;
    bool disabled;
    bool ser;
    bool recovery;
    bool bios_cmci_threshold;
    u8 banks;
    s8 bootlog;
    int tolerant;
    int monarch_timeout;
    int panic_timeout;
    u32 rip_msr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct mca_config {
    bool dont_log_ce;
    bool cmci_disabled;
    bool lmce_disabled;
    bool ignore_ce;
    bool disabled;
    bool ser;
    bool recovery;
    bool bios_cmci_threshold;
    u8 banks;
    s8 bootlog;
    int tolerant;
    int monarch_timeout;
    int panic_timeout;
    u32 rip_msr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct mca_config {
    bool dont_log_ce;
    bool cmci_disabled;
    bool ignore_ce;
    __u64 lmce_disabled;
    __u64 disabled;
    __u64 ser;
    __u64 recovery;
    __u64 bios_cmci_threshold;
    __u64 __reserved;
    u8 banks;
    s8 bootlog;
    int tolerant;
    int monarch_timeout;
    int panic_timeout;
    u32 rip_msr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct mca_config {
    bool dont_log_ce;
    bool cmci_disabled;
    bool ignore_ce;
    __u64 lmce_disabled;
    __u64 disabled;
    __u64 ser;
    __u64 recovery;
    __u64 bios_cmci_threshold;
    __u64 __reserved;
    u8 banks;
    s8 bootlog;
    int tolerant;
    int monarch_timeout;
    int panic_timeout;
    u32 rip_msr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct mca_config {
    bool dont_log_ce;
    bool cmci_disabled;
    bool ignore_ce;
    __u64 lmce_disabled;
    __u64 disabled;
    __u64 ser;
    __u64 recovery;
    __u64 bios_cmci_threshold;
    __u64 __reserved;
    s8 bootlog;
    int tolerant;
    int monarch_timeout;
    int panic_timeout;
    u32 rip_msr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct mca_config {
    bool dont_log_ce;
    bool cmci_disabled;
    bool ignore_ce;
    __u64 lmce_disabled;
    __u64 disabled;
    __u64 ser;
    __u64 recovery;
    __u64 bios_cmci_threshold;
    __u64 __reserved;
    s8 bootlog;
    int tolerant;
    int monarch_timeout;
    int panic_timeout;
    u32 rip_msr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct mca_config {
    bool dont_log_ce;
    bool cmci_disabled;
    bool ignore_ce;
    bool print_all;
    __u64 lmce_disabled;
    __u64 disabled;
    __u64 ser;
    __u64 recovery;
    __u64 bios_cmci_threshold;
    __u64 __reserved;
    s8 bootlog;
    int tolerant;
    int monarch_timeout;
    int panic_timeout;
    u32 rip_msr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct mca_config {
    bool dont_log_ce;
    bool cmci_disabled;
    bool ignore_ce;
    bool print_all;
    __u64 lmce_disabled;
    __u64 disabled;
    __u64 ser;
    __u64 recovery;
    __u64 bios_cmci_threshold;
    __u64 __reserved;
    s8 bootlog;
    int tolerant;
    int monarch_timeout;
    int panic_timeout;
    u32 rip_msr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct mca_config {
    bool dont_log_ce;
    bool cmci_disabled;
    bool ignore_ce;
    bool print_all;
    __u64 lmce_disabled;
    __u64 disabled;
    __u64 ser;
    __u64 recovery;
    __u64 bios_cmci_threshold;
    __u64 __reserved;
    s8 bootlog;
    int tolerant;
    int monarch_timeout;
    int panic_timeout;
    u32 rip_msr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct mca_config {
    bool dont_log_ce;
    bool cmci_disabled;
    bool ignore_ce;
    bool print_all;
    __u64 lmce_disabled;
    __u64 disabled;
    __u64 ser;
    __u64 recovery;
    __u64 bios_cmci_threshold;
    __u64 __reserved;
    s8 bootlog;
    int tolerant;
    int monarch_timeout;
    int panic_timeout;
    u32 rip_msr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct mca_config {
    __u64 lmce_disabled;
    __u64 disabled;
    __u64 ser;
    __u64 recovery;
    __u64 bios_cmci_threshold;
    __u64 initialized;
    __u64 __reserved;
    bool dont_log_ce;
    bool cmci_disabled;
    bool ignore_ce;
    bool print_all;
    int monarch_timeout;
    int panic_timeout;
    u32 rip_msr;
    s8 bootlog;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct mca_config {
    __u64 lmce_disabled;
    __u64 disabled;
    __u64 ser;
    __u64 recovery;
    __u64 bios_cmci_threshold;
    __u64 initialized;
    __u64 __reserved;
    bool dont_log_ce;
    bool cmci_disabled;
    bool ignore_ce;
    bool print_all;
    int monarch_timeout;
    int panic_timeout;
    u32 rip_msr;
    s8 bootlog;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct mca_config {
    __u64 lmce_disabled;
    __u64 disabled;
    __u64 ser;
    __u64 recovery;
    __u64 bios_cmci_threshold;
    __u64 initialized;
    __u64 __reserved;
    bool dont_log_ce;
    bool cmci_disabled;
    bool ignore_ce;
    bool print_all;
    int monarch_timeout;
    int panic_timeout;
    u32 rip_msr;
    s8 bootlog;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct mca_config {
    __u64 lmce_disabled;
    __u64 disabled;
    __u64 ser;
    __u64 recovery;
    __u64 bios_cmci_threshold;
    __u64 initialized;
    __u64 __reserved;
    bool dont_log_ce;
    bool cmci_disabled;
    bool ignore_ce;
    bool print_all;
    int monarch_timeout;
    int panic_timeout;
    u32 rip_msr;
    s8 bootlog;
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
struct mca_config {
    bool dont_log_ce;
    bool cmci_disabled;
    bool ignore_ce;
    __u64 lmce_disabled;
    __u64 disabled;
    __u64 ser;
    __u64 recovery;
    __u64 bios_cmci_threshold;
    __u64 __reserved;
    s8 bootlog;
    int tolerant;
    int monarch_timeout;
    int panic_timeout;
    u32 rip_msr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct mca_config {
    bool dont_log_ce;
    bool cmci_disabled;
    bool ignore_ce;
    __u64 lmce_disabled;
    __u64 disabled;
    __u64 ser;
    __u64 recovery;
    __u64 bios_cmci_threshold;
    __u64 __reserved;
    s8 bootlog;
    int tolerant;
    int monarch_timeout;
    int panic_timeout;
    u32 rip_msr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct mca_config {
    bool dont_log_ce;
    bool cmci_disabled;
    bool ignore_ce;
    __u64 lmce_disabled;
    __u64 disabled;
    __u64 ser;
    __u64 recovery;
    __u64 bios_cmci_threshold;
    __u64 __reserved;
    s8 bootlog;
    int tolerant;
    int monarch_timeout;
    int panic_timeout;
    u32 rip_msr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct mca_config {
    bool dont_log_ce;
    bool cmci_disabled;
    bool ignore_ce;
    __u64 lmce_disabled;
    __u64 disabled;
    __u64 ser;
    __u64 recovery;
    __u64 bios_cmci_threshold;
    __u64 __reserved;
    s8 bootlog;
    int tolerant;
    int monarch_timeout;
    int panic_timeout;
    u32 rip_msr;
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
<code>bool recovery</code>
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
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>__u64 __reserved</code>
</li>
<li>
<b>Field type changed. </b>
<code>bool lmce_disabled</code> ➡️ <code>__u64 lmce_disabled</code>
</li>
<li>
<b>Field type changed. </b>
<code>bool disabled</code> ➡️ <code>__u64 disabled</code>
</li>
<li>
<b>Field type changed. </b>
<code>bool ser</code> ➡️ <code>__u64 ser</code>
</li>
<li>
<b>Field type changed. </b>
<code>bool recovery</code> ➡️ <code>__u64 recovery</code>
</li>
<li>
<b>Field type changed. </b>
<code>bool bios_cmci_threshold</code> ➡️ <code>__u64 bios_cmci_threshold</code>
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
<b>Field removed. </b>
<code>u8 banks</code>
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
<code>bool print_all</code>
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
<code>__u64 initialized</code>
</li>
<li>
<b>Field removed. </b>
<code>int tolerant</code>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
struct mca_config {
    bool dont_log_ce;
    bool cmci_disabled;
    bool ignore_ce;
    __u64 lmce_disabled;
    __u64 disabled;
    __u64 ser;
    __u64 recovery;
    __u64 bios_cmci_threshold;
    __u64 __reserved;
    s8 bootlog;
    int tolerant;
    int monarch_timeout;
    int panic_timeout;
    u32 rip_msr;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct mca_config {
    bool dont_log_ce;
    bool cmci_disabled;
    bool ignore_ce;
    __u64 lmce_disabled;
    __u64 disabled;
    __u64 ser;
    __u64 recovery;
    __u64 bios_cmci_threshold;
    __u64 __reserved;
    s8 bootlog;
    int tolerant;
    int monarch_timeout;
    int panic_timeout;
    u32 rip_msr;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct mca_config {
    bool dont_log_ce;
    bool cmci_disabled;
    bool ignore_ce;
    __u64 lmce_disabled;
    __u64 disabled;
    __u64 ser;
    __u64 recovery;
    __u64 bios_cmci_threshold;
    __u64 __reserved;
    s8 bootlog;
    int tolerant;
    int monarch_timeout;
    int panic_timeout;
    u32 rip_msr;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct mca_config {
    bool dont_log_ce;
    bool cmci_disabled;
    bool ignore_ce;
    __u64 lmce_disabled;
    __u64 disabled;
    __u64 ser;
    __u64 recovery;
    __u64 bios_cmci_threshold;
    __u64 __reserved;
    s8 bootlog;
    int tolerant;
    int monarch_timeout;
    int panic_timeout;
    u32 rip_msr;
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
