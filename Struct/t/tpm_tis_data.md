# Struct: <code>tpm_tis_data</code>

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
struct tpm_tis_data {
    u16 manufacturer_id;
    int locality;
    int irq;
    bool irq_tested;
    unsigned int flags;
    wait_queue_head_t int_queue;
    wait_queue_head_t read_queue;
    const struct tpm_tis_phy_ops * phy_ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct tpm_tis_data {
    u16 manufacturer_id;
    int locality;
    int irq;
    bool irq_tested;
    unsigned int flags;
    wait_queue_head_t int_queue;
    wait_queue_head_t read_queue;
    const struct tpm_tis_phy_ops * phy_ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct tpm_tis_data {
    u16 manufacturer_id;
    int locality;
    int irq;
    bool irq_tested;
    unsigned int flags;
    wait_queue_head_t int_queue;
    wait_queue_head_t read_queue;
    const struct tpm_tis_phy_ops * phy_ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct tpm_tis_data {
    u16 manufacturer_id;
    int locality;
    int irq;
    bool irq_tested;
    unsigned int flags;
    void * ilb_base_addr;
    u16 clkrun_enabled;
    wait_queue_head_t int_queue;
    wait_queue_head_t read_queue;
    const struct tpm_tis_phy_ops * phy_ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct tpm_tis_data {
    u16 manufacturer_id;
    int locality;
    int irq;
    bool irq_tested;
    unsigned int flags;
    void * ilb_base_addr;
    u16 clkrun_enabled;
    wait_queue_head_t int_queue;
    wait_queue_head_t read_queue;
    const struct tpm_tis_phy_ops * phy_ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct tpm_tis_data {
    u16 manufacturer_id;
    int locality;
    int irq;
    bool irq_tested;
    unsigned int flags;
    void * ilb_base_addr;
    u16 clkrun_enabled;
    wait_queue_head_t int_queue;
    wait_queue_head_t read_queue;
    const struct tpm_tis_phy_ops * phy_ops;
    short unsigned int rng_quality;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct tpm_tis_data {
    u16 manufacturer_id;
    int locality;
    int irq;
    bool irq_tested;
    unsigned int flags;
    void * ilb_base_addr;
    u16 clkrun_enabled;
    wait_queue_head_t int_queue;
    wait_queue_head_t read_queue;
    const struct tpm_tis_phy_ops * phy_ops;
    short unsigned int rng_quality;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct tpm_tis_data {
    u16 manufacturer_id;
    int locality;
    int irq;
    bool irq_tested;
    unsigned int flags;
    void * ilb_base_addr;
    u16 clkrun_enabled;
    wait_queue_head_t int_queue;
    wait_queue_head_t read_queue;
    const struct tpm_tis_phy_ops * phy_ops;
    short unsigned int rng_quality;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct tpm_tis_data {
    u16 manufacturer_id;
    int locality;
    int irq;
    bool irq_tested;
    unsigned int flags;
    void * ilb_base_addr;
    u16 clkrun_enabled;
    wait_queue_head_t int_queue;
    wait_queue_head_t read_queue;
    const struct tpm_tis_phy_ops * phy_ops;
    short unsigned int rng_quality;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct tpm_tis_data {
    u16 manufacturer_id;
    int locality;
    int irq;
    bool irq_tested;
    unsigned int flags;
    void * ilb_base_addr;
    u16 clkrun_enabled;
    wait_queue_head_t int_queue;
    wait_queue_head_t read_queue;
    const struct tpm_tis_phy_ops * phy_ops;
    short unsigned int rng_quality;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct tpm_tis_data {
    u16 manufacturer_id;
    int locality;
    int irq;
    bool irq_tested;
    long unsigned int flags;
    void * ilb_base_addr;
    u16 clkrun_enabled;
    wait_queue_head_t int_queue;
    wait_queue_head_t read_queue;
    const struct tpm_tis_phy_ops * phy_ops;
    short unsigned int rng_quality;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct tpm_tis_data {
    u16 manufacturer_id;
    int locality;
    int irq;
    bool irq_tested;
    long unsigned int flags;
    void * ilb_base_addr;
    u16 clkrun_enabled;
    wait_queue_head_t int_queue;
    wait_queue_head_t read_queue;
    const struct tpm_tis_phy_ops * phy_ops;
    short unsigned int rng_quality;
    unsigned int timeout_min;
    unsigned int timeout_max;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct tpm_tis_data {
    u16 manufacturer_id;
    int locality;
    int irq;
    bool irq_tested;
    long unsigned int flags;
    void * ilb_base_addr;
    u16 clkrun_enabled;
    wait_queue_head_t int_queue;
    wait_queue_head_t read_queue;
    const struct tpm_tis_phy_ops * phy_ops;
    short unsigned int rng_quality;
    unsigned int timeout_min;
    unsigned int timeout_max;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct tpm_tis_data {
    u16 manufacturer_id;
    int locality;
    int irq;
    bool irq_tested;
    long unsigned int flags;
    void * ilb_base_addr;
    u16 clkrun_enabled;
    wait_queue_head_t int_queue;
    wait_queue_head_t read_queue;
    const struct tpm_tis_phy_ops * phy_ops;
    short unsigned int rng_quality;
    unsigned int timeout_min;
    unsigned int timeout_max;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct tpm_tis_data {
    struct tpm_chip * chip;
    u16 manufacturer_id;
    struct mutex locality_count_mutex;
    unsigned int locality_count;
    int locality;
    int irq;
    struct work_struct free_irq_work;
    long unsigned int last_unhandled_irq;
    unsigned int unhandled_irqs;
    unsigned int int_mask;
    long unsigned int flags;
    void * ilb_base_addr;
    u16 clkrun_enabled;
    wait_queue_head_t int_queue;
    wait_queue_head_t read_queue;
    const struct tpm_tis_phy_ops * phy_ops;
    short unsigned int rng_quality;
    unsigned int timeout_min;
    unsigned int timeout_max;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct tpm_tis_data {
    struct tpm_chip * chip;
    u16 manufacturer_id;
    struct mutex locality_count_mutex;
    unsigned int locality_count;
    int locality;
    int irq;
    struct work_struct free_irq_work;
    long unsigned int last_unhandled_irq;
    unsigned int unhandled_irqs;
    unsigned int int_mask;
    long unsigned int flags;
    void * ilb_base_addr;
    u16 clkrun_enabled;
    wait_queue_head_t int_queue;
    wait_queue_head_t read_queue;
    const struct tpm_tis_phy_ops * phy_ops;
    short unsigned int rng_quality;
    unsigned int timeout_min;
    unsigned int timeout_max;
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
struct tpm_tis_data {
    u16 manufacturer_id;
    int locality;
    int irq;
    bool irq_tested;
    unsigned int flags;
    void * ilb_base_addr;
    u16 clkrun_enabled;
    wait_queue_head_t int_queue;
    wait_queue_head_t read_queue;
    const struct tpm_tis_phy_ops * phy_ops;
    short unsigned int rng_quality;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct tpm_tis_data {
    u16 manufacturer_id;
    int locality;
    int irq;
    bool irq_tested;
    unsigned int flags;
    void * ilb_base_addr;
    u16 clkrun_enabled;
    wait_queue_head_t int_queue;
    wait_queue_head_t read_queue;
    const struct tpm_tis_phy_ops * phy_ops;
    short unsigned int rng_quality;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct tpm_tis_data {
    u16 manufacturer_id;
    int locality;
    int irq;
    bool irq_tested;
    unsigned int flags;
    void * ilb_base_addr;
    u16 clkrun_enabled;
    wait_queue_head_t int_queue;
    wait_queue_head_t read_queue;
    const struct tpm_tis_phy_ops * phy_ops;
    short unsigned int rng_quality;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct tpm_tis_data {
    u16 manufacturer_id;
    int locality;
    int irq;
    bool irq_tested;
    unsigned int flags;
    void * ilb_base_addr;
    u16 clkrun_enabled;
    wait_queue_head_t int_queue;
    wait_queue_head_t read_queue;
    const struct tpm_tis_phy_ops * phy_ops;
    short unsigned int rng_quality;
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
struct tpm_tis_data {
    u16 manufacturer_id;
    int locality;
    int irq;
    bool irq_tested;
    unsigned int flags;
    void * ilb_base_addr;
    u16 clkrun_enabled;
    wait_queue_head_t int_queue;
    wait_queue_head_t read_queue;
    const struct tpm_tis_phy_ops * phy_ops;
    short unsigned int rng_quality;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct tpm_tis_data {
    u16 manufacturer_id;
    int locality;
    int irq;
    bool irq_tested;
    unsigned int flags;
    void * ilb_base_addr;
    u16 clkrun_enabled;
    wait_queue_head_t int_queue;
    wait_queue_head_t read_queue;
    const struct tpm_tis_phy_ops * phy_ops;
    short unsigned int rng_quality;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct tpm_tis_data {
    u16 manufacturer_id;
    int locality;
    int irq;
    bool irq_tested;
    unsigned int flags;
    void * ilb_base_addr;
    u16 clkrun_enabled;
    wait_queue_head_t int_queue;
    wait_queue_head_t read_queue;
    const struct tpm_tis_phy_ops * phy_ops;
    short unsigned int rng_quality;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct tpm_tis_data {
    u16 manufacturer_id;
    int locality;
    int irq;
    bool irq_tested;
    unsigned int flags;
    void * ilb_base_addr;
    u16 clkrun_enabled;
    wait_queue_head_t int_queue;
    wait_queue_head_t read_queue;
    const struct tpm_tis_phy_ops * phy_ops;
    short unsigned int rng_quality;
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
struct tpm_tis_data {
    u16 manufacturer_id;
    int locality;
    int irq;
    bool irq_tested;
    unsigned int flags;
    wait_queue_head_t int_queue;
    wait_queue_head_t read_queue;
    const struct tpm_tis_phy_ops * phy_ops;
}
```
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
<code>void * ilb_base_addr</code>
</li>
<li>
<b>Field added. </b>
<code>u16 clkrun_enabled</code>
</li>
</ul>
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
<b>Field added. </b>
<code>short unsigned int rng_quality</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>unsigned int flags</code> ➡️ <code>long unsigned int flags</code>
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
<code>unsigned int timeout_min</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int timeout_max</code>
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct tpm_chip * chip</code>
</li>
<li>
<b>Field added. </b>
<code>struct mutex locality_count_mutex</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int locality_count</code>
</li>
<li>
<b>Field added. </b>
<code>struct work_struct free_irq_work</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int last_unhandled_irq</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int unhandled_irqs</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int int_mask</code>
</li>
<li>
<b>Field removed. </b>
<code>bool irq_tested</code>
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
