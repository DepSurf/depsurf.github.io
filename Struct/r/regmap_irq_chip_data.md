# Struct: <code>regmap_irq_chip_data</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct regmap_irq_chip_data {
    struct mutex lock;
    struct irq_chip irq_chip;
    struct regmap * map;
    const struct regmap_irq_chip * chip;
    int irq_base;
    struct irq_domain * domain;
    int irq;
    int wake_count;
    void * status_reg_buf;
    unsigned int * status_buf;
    unsigned int * mask_buf;
    unsigned int * mask_buf_def;
    unsigned int * wake_buf;
    unsigned int irq_reg_stride;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct regmap_irq_chip_data {
    struct mutex lock;
    struct irq_chip irq_chip;
    struct regmap * map;
    const struct regmap_irq_chip * chip;
    int irq_base;
    struct irq_domain * domain;
    int irq;
    int wake_count;
    void * status_reg_buf;
    unsigned int * status_buf;
    unsigned int * mask_buf;
    unsigned int * mask_buf_def;
    unsigned int * wake_buf;
    unsigned int * type_buf;
    unsigned int * type_buf_def;
    unsigned int irq_reg_stride;
    unsigned int type_reg_stride;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct regmap_irq_chip_data {
    struct mutex lock;
    struct irq_chip irq_chip;
    struct regmap * map;
    const struct regmap_irq_chip * chip;
    int irq_base;
    struct irq_domain * domain;
    int irq;
    int wake_count;
    void * status_reg_buf;
    unsigned int * status_buf;
    unsigned int * mask_buf;
    unsigned int * mask_buf_def;
    unsigned int * wake_buf;
    unsigned int * type_buf;
    unsigned int * type_buf_def;
    unsigned int irq_reg_stride;
    unsigned int type_reg_stride;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct regmap_irq_chip_data {
    struct mutex lock;
    struct irq_chip irq_chip;
    struct regmap * map;
    const struct regmap_irq_chip * chip;
    int irq_base;
    struct irq_domain * domain;
    int irq;
    int wake_count;
    void * status_reg_buf;
    unsigned int * status_buf;
    unsigned int * mask_buf;
    unsigned int * mask_buf_def;
    unsigned int * wake_buf;
    unsigned int * type_buf;
    unsigned int * type_buf_def;
    unsigned int irq_reg_stride;
    unsigned int type_reg_stride;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct regmap_irq_chip_data {
    struct mutex lock;
    struct irq_chip irq_chip;
    struct regmap * map;
    const struct regmap_irq_chip * chip;
    int irq_base;
    struct irq_domain * domain;
    int irq;
    int wake_count;
    void * status_reg_buf;
    unsigned int * status_buf;
    unsigned int * mask_buf;
    unsigned int * mask_buf_def;
    unsigned int * wake_buf;
    unsigned int * type_buf;
    unsigned int * type_buf_def;
    unsigned int irq_reg_stride;
    unsigned int type_reg_stride;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct regmap_irq_chip_data {
    struct mutex lock;
    struct irq_chip irq_chip;
    struct regmap * map;
    const struct regmap_irq_chip * chip;
    int irq_base;
    struct irq_domain * domain;
    int irq;
    int wake_count;
    void * status_reg_buf;
    unsigned int * status_buf;
    unsigned int * mask_buf;
    unsigned int * mask_buf_def;
    unsigned int * wake_buf;
    unsigned int * type_buf;
    unsigned int * type_buf_def;
    unsigned int irq_reg_stride;
    unsigned int type_reg_stride;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct regmap_irq_chip_data {
    struct mutex lock;
    struct irq_chip irq_chip;
    struct regmap * map;
    const struct regmap_irq_chip * chip;
    int irq_base;
    struct irq_domain * domain;
    int irq;
    int wake_count;
    void * status_reg_buf;
    unsigned int * status_buf;
    unsigned int * mask_buf;
    unsigned int * mask_buf_def;
    unsigned int * wake_buf;
    unsigned int * type_buf;
    unsigned int * type_buf_def;
    unsigned int irq_reg_stride;
    unsigned int type_reg_stride;
    bool clear_status;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct regmap_irq_chip_data {
    struct mutex lock;
    struct irq_chip irq_chip;
    struct regmap * map;
    const struct regmap_irq_chip * chip;
    int irq_base;
    struct irq_domain * domain;
    int irq;
    int wake_count;
    void * status_reg_buf;
    unsigned int * main_status_buf;
    unsigned int * status_buf;
    unsigned int * mask_buf;
    unsigned int * mask_buf_def;
    unsigned int * wake_buf;
    unsigned int * type_buf;
    unsigned int * type_buf_def;
    unsigned int irq_reg_stride;
    unsigned int type_reg_stride;
    bool clear_status;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct regmap_irq_chip_data {
    struct mutex lock;
    struct irq_chip irq_chip;
    struct regmap * map;
    const struct regmap_irq_chip * chip;
    int irq_base;
    struct irq_domain * domain;
    int irq;
    int wake_count;
    void * status_reg_buf;
    unsigned int * main_status_buf;
    unsigned int * status_buf;
    unsigned int * mask_buf;
    unsigned int * mask_buf_def;
    unsigned int * wake_buf;
    unsigned int * type_buf;
    unsigned int * type_buf_def;
    unsigned int irq_reg_stride;
    unsigned int type_reg_stride;
    bool clear_status;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct regmap_irq_chip_data {
    struct mutex lock;
    struct irq_chip irq_chip;
    struct regmap * map;
    const struct regmap_irq_chip * chip;
    int irq_base;
    struct irq_domain * domain;
    int irq;
    int wake_count;
    void * status_reg_buf;
    unsigned int * main_status_buf;
    unsigned int * status_buf;
    unsigned int * mask_buf;
    unsigned int * mask_buf_def;
    unsigned int * wake_buf;
    unsigned int * type_buf;
    unsigned int * type_buf_def;
    unsigned int irq_reg_stride;
    unsigned int type_reg_stride;
    bool clear_status;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct regmap_irq_chip_data {
    struct mutex lock;
    struct irq_chip irq_chip;
    struct regmap * map;
    const struct regmap_irq_chip * chip;
    int irq_base;
    struct irq_domain * domain;
    int irq;
    int wake_count;
    void * status_reg_buf;
    unsigned int * main_status_buf;
    unsigned int * status_buf;
    unsigned int * mask_buf;
    unsigned int * mask_buf_def;
    unsigned int * wake_buf;
    unsigned int * type_buf;
    unsigned int * type_buf_def;
    unsigned int irq_reg_stride;
    unsigned int type_reg_stride;
    bool clear_status;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct regmap_irq_chip_data {
    struct mutex lock;
    struct irq_chip irq_chip;
    struct regmap * map;
    const struct regmap_irq_chip * chip;
    int irq_base;
    struct irq_domain * domain;
    int irq;
    int wake_count;
    void * status_reg_buf;
    unsigned int * main_status_buf;
    unsigned int * status_buf;
    unsigned int * mask_buf;
    unsigned int * mask_buf_def;
    unsigned int * wake_buf;
    unsigned int * type_buf;
    unsigned int * type_buf_def;
    unsigned int * * virt_buf;
    unsigned int irq_reg_stride;
    unsigned int type_reg_stride;
    bool clear_status;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct regmap_irq_chip_data {
    struct mutex lock;
    struct irq_chip irq_chip;
    struct regmap * map;
    const struct regmap_irq_chip * chip;
    int irq_base;
    struct irq_domain * domain;
    int irq;
    int wake_count;
    void * status_reg_buf;
    unsigned int * main_status_buf;
    unsigned int * status_buf;
    unsigned int * mask_buf;
    unsigned int * mask_buf_def;
    unsigned int * wake_buf;
    unsigned int * type_buf;
    unsigned int * type_buf_def;
    unsigned int * * virt_buf;
    unsigned int irq_reg_stride;
    unsigned int type_reg_stride;
    bool clear_status;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct regmap_irq_chip_data {
    struct mutex lock;
    struct irq_chip irq_chip;
    struct regmap * map;
    const struct regmap_irq_chip * chip;
    int irq_base;
    struct irq_domain * domain;
    int irq;
    int wake_count;
    void * status_reg_buf;
    unsigned int * main_status_buf;
    unsigned int * status_buf;
    unsigned int * mask_buf;
    unsigned int * mask_buf_def;
    unsigned int * wake_buf;
    unsigned int * type_buf;
    unsigned int * type_buf_def;
    unsigned int * * virt_buf;
    unsigned int irq_reg_stride;
    unsigned int type_reg_stride;
    bool clear_status;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct regmap_irq_chip_data {
    struct mutex lock;
    struct irq_chip irq_chip;
    struct regmap * map;
    const struct regmap_irq_chip * chip;
    int irq_base;
    struct irq_domain * domain;
    int irq;
    int wake_count;
    unsigned int mask_base;
    unsigned int unmask_base;
    void * status_reg_buf;
    unsigned int * main_status_buf;
    unsigned int * status_buf;
    unsigned int * mask_buf;
    unsigned int * mask_buf_def;
    unsigned int * wake_buf;
    unsigned int * type_buf;
    unsigned int * type_buf_def;
    unsigned int * * virt_buf;
    unsigned int * * config_buf;
    unsigned int irq_reg_stride;
    unsigned int (*)(struct regmap_irq_chip_data *, unsigned int, int) get_irq_reg;
    unsigned int clear_status;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct regmap_irq_chip_data {
    struct mutex lock;
    struct irq_chip irq_chip;
    struct regmap * map;
    const struct regmap_irq_chip * chip;
    int irq_base;
    struct irq_domain * domain;
    int irq;
    int wake_count;
    void * status_reg_buf;
    unsigned int * main_status_buf;
    unsigned int * status_buf;
    unsigned int * mask_buf;
    unsigned int * mask_buf_def;
    unsigned int * wake_buf;
    unsigned int * type_buf;
    unsigned int * type_buf_def;
    unsigned int * * config_buf;
    unsigned int irq_reg_stride;
    unsigned int (*)(struct regmap_irq_chip_data *, unsigned int, int) get_irq_reg;
    unsigned int clear_status;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct regmap_irq_chip_data {
    struct mutex lock;
    struct irq_chip irq_chip;
    struct regmap * map;
    const struct regmap_irq_chip * chip;
    int irq_base;
    struct irq_domain * domain;
    int irq;
    int wake_count;
    void * status_reg_buf;
    unsigned int * main_status_buf;
    unsigned int * status_buf;
    unsigned int * mask_buf;
    unsigned int * mask_buf_def;
    unsigned int * wake_buf;
    unsigned int * type_buf;
    unsigned int * type_buf_def;
    unsigned int * * config_buf;
    unsigned int irq_reg_stride;
    unsigned int (*)(struct regmap_irq_chip_data *, unsigned int, int) get_irq_reg;
    unsigned int clear_status;
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
struct regmap_irq_chip_data {
    struct mutex lock;
    struct irq_chip irq_chip;
    struct regmap * map;
    const struct regmap_irq_chip * chip;
    int irq_base;
    struct irq_domain * domain;
    int irq;
    int wake_count;
    void * status_reg_buf;
    unsigned int * main_status_buf;
    unsigned int * status_buf;
    unsigned int * mask_buf;
    unsigned int * mask_buf_def;
    unsigned int * wake_buf;
    unsigned int * type_buf;
    unsigned int * type_buf_def;
    unsigned int irq_reg_stride;
    unsigned int type_reg_stride;
    bool clear_status;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct regmap_irq_chip_data {
    struct mutex lock;
    struct irq_chip irq_chip;
    struct regmap * map;
    const struct regmap_irq_chip * chip;
    int irq_base;
    struct irq_domain * domain;
    int irq;
    int wake_count;
    void * status_reg_buf;
    unsigned int * main_status_buf;
    unsigned int * status_buf;
    unsigned int * mask_buf;
    unsigned int * mask_buf_def;
    unsigned int * wake_buf;
    unsigned int * type_buf;
    unsigned int * type_buf_def;
    unsigned int irq_reg_stride;
    unsigned int type_reg_stride;
    bool clear_status;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct regmap_irq_chip_data {
    struct mutex lock;
    struct irq_chip irq_chip;
    struct regmap * map;
    const struct regmap_irq_chip * chip;
    int irq_base;
    struct irq_domain * domain;
    int irq;
    int wake_count;
    void * status_reg_buf;
    unsigned int * main_status_buf;
    unsigned int * status_buf;
    unsigned int * mask_buf;
    unsigned int * mask_buf_def;
    unsigned int * wake_buf;
    unsigned int * type_buf;
    unsigned int * type_buf_def;
    unsigned int irq_reg_stride;
    unsigned int type_reg_stride;
    bool clear_status;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct regmap_irq_chip_data {
    struct mutex lock;
    struct irq_chip irq_chip;
    struct regmap * map;
    const struct regmap_irq_chip * chip;
    int irq_base;
    struct irq_domain * domain;
    int irq;
    int wake_count;
    void * status_reg_buf;
    unsigned int * main_status_buf;
    unsigned int * status_buf;
    unsigned int * mask_buf;
    unsigned int * mask_buf_def;
    unsigned int * wake_buf;
    unsigned int * type_buf;
    unsigned int * type_buf_def;
    unsigned int irq_reg_stride;
    unsigned int type_reg_stride;
    bool clear_status;
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
struct regmap_irq_chip_data {
    struct mutex lock;
    struct irq_chip irq_chip;
    struct regmap * map;
    const struct regmap_irq_chip * chip;
    int irq_base;
    struct irq_domain * domain;
    int irq;
    int wake_count;
    void * status_reg_buf;
    unsigned int * main_status_buf;
    unsigned int * status_buf;
    unsigned int * mask_buf;
    unsigned int * mask_buf_def;
    unsigned int * wake_buf;
    unsigned int * type_buf;
    unsigned int * type_buf_def;
    unsigned int irq_reg_stride;
    unsigned int type_reg_stride;
    bool clear_status;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct regmap_irq_chip_data {
    struct mutex lock;
    struct irq_chip irq_chip;
    struct regmap * map;
    const struct regmap_irq_chip * chip;
    int irq_base;
    struct irq_domain * domain;
    int irq;
    int wake_count;
    void * status_reg_buf;
    unsigned int * main_status_buf;
    unsigned int * status_buf;
    unsigned int * mask_buf;
    unsigned int * mask_buf_def;
    unsigned int * wake_buf;
    unsigned int * type_buf;
    unsigned int * type_buf_def;
    unsigned int irq_reg_stride;
    unsigned int type_reg_stride;
    bool clear_status;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct regmap_irq_chip_data {
    struct mutex lock;
    struct irq_chip irq_chip;
    struct regmap * map;
    const struct regmap_irq_chip * chip;
    int irq_base;
    struct irq_domain * domain;
    int irq;
    int wake_count;
    void * status_reg_buf;
    unsigned int * main_status_buf;
    unsigned int * status_buf;
    unsigned int * mask_buf;
    unsigned int * mask_buf_def;
    unsigned int * wake_buf;
    unsigned int * type_buf;
    unsigned int * type_buf_def;
    unsigned int irq_reg_stride;
    unsigned int type_reg_stride;
    bool clear_status;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct regmap_irq_chip_data {
    struct mutex lock;
    struct irq_chip irq_chip;
    struct regmap * map;
    const struct regmap_irq_chip * chip;
    int irq_base;
    struct irq_domain * domain;
    int irq;
    int wake_count;
    void * status_reg_buf;
    unsigned int * main_status_buf;
    unsigned int * status_buf;
    unsigned int * mask_buf;
    unsigned int * mask_buf_def;
    unsigned int * wake_buf;
    unsigned int * type_buf;
    unsigned int * type_buf_def;
    unsigned int irq_reg_stride;
    unsigned int type_reg_stride;
    bool clear_status;
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
<code>unsigned int * type_buf</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int * type_buf_def</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int type_reg_stride</code>
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
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool clear_status</code>
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
<code>unsigned int * main_status_buf</code>
</li>
</ul>
</details>
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
<b>Field added. </b>
<code>unsigned int * * virt_buf</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int mask_base</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int unmask_base</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int * * config_buf</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int (*)(struct regmap_irq_chip_data *, unsigned int, int) get_irq_reg</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int type_reg_stride</code>
</li>
<li>
<b>Field type changed. </b>
<code>bool clear_status</code> ➡️ <code>unsigned int clear_status</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>unsigned int mask_base</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int unmask_base</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int * * virt_buf</code>
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
