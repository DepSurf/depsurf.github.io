# Struct: <code>regmap_irq_chip</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct regmap_irq_chip {
    const char * name;
    unsigned int status_base;
    unsigned int mask_base;
    unsigned int unmask_base;
    unsigned int ack_base;
    unsigned int wake_base;
    unsigned int irq_reg_stride;
    bool init_ack_masked;
    bool mask_invert;
    bool use_ack;
    bool ack_invert;
    bool wake_invert;
    bool runtime_pm;
    int num_regs;
    const struct regmap_irq * irqs;
    int num_irqs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct regmap_irq_chip {
    const char * name;
    unsigned int status_base;
    unsigned int mask_base;
    unsigned int unmask_base;
    unsigned int ack_base;
    unsigned int wake_base;
    unsigned int type_base;
    unsigned int irq_reg_stride;
    bool init_ack_masked;
    bool mask_invert;
    bool use_ack;
    bool ack_invert;
    bool wake_invert;
    bool runtime_pm;
    bool type_invert;
    int num_regs;
    const struct regmap_irq * irqs;
    int num_irqs;
    int num_type_reg;
    unsigned int type_reg_stride;
    int (*)(void *) handle_pre_irq;
    int (*)(void *) handle_post_irq;
    void * irq_drv_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct regmap_irq_chip {
    const char * name;
    unsigned int status_base;
    unsigned int mask_base;
    unsigned int unmask_base;
    unsigned int ack_base;
    unsigned int wake_base;
    unsigned int type_base;
    unsigned int irq_reg_stride;
    bool init_ack_masked;
    bool mask_invert;
    bool use_ack;
    bool ack_invert;
    bool wake_invert;
    bool runtime_pm;
    bool type_invert;
    int num_regs;
    const struct regmap_irq * irqs;
    int num_irqs;
    int num_type_reg;
    unsigned int type_reg_stride;
    int (*)(void *) handle_pre_irq;
    int (*)(void *) handle_post_irq;
    void * irq_drv_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct regmap_irq_chip {
    const char * name;
    unsigned int status_base;
    unsigned int mask_base;
    unsigned int unmask_base;
    unsigned int ack_base;
    unsigned int wake_base;
    unsigned int type_base;
    unsigned int irq_reg_stride;
    bool mask_writeonly;
    bool init_ack_masked;
    bool mask_invert;
    bool use_ack;
    bool ack_invert;
    bool wake_invert;
    bool runtime_pm;
    bool type_invert;
    int num_regs;
    const struct regmap_irq * irqs;
    int num_irqs;
    int num_type_reg;
    unsigned int type_reg_stride;
    int (*)(void *) handle_pre_irq;
    int (*)(void *) handle_post_irq;
    void * irq_drv_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct regmap_irq_chip {
    const char * name;
    unsigned int status_base;
    unsigned int mask_base;
    unsigned int unmask_base;
    unsigned int ack_base;
    unsigned int wake_base;
    unsigned int type_base;
    unsigned int irq_reg_stride;
    bool mask_writeonly;
    bool init_ack_masked;
    bool mask_invert;
    bool use_ack;
    bool ack_invert;
    bool wake_invert;
    bool runtime_pm;
    bool type_invert;
    int num_regs;
    const struct regmap_irq * irqs;
    int num_irqs;
    int num_type_reg;
    unsigned int type_reg_stride;
    int (*)(void *) handle_pre_irq;
    int (*)(void *) handle_post_irq;
    void * irq_drv_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct regmap_irq_chip {
    const char * name;
    unsigned int status_base;
    unsigned int mask_base;
    unsigned int unmask_base;
    unsigned int ack_base;
    unsigned int wake_base;
    unsigned int type_base;
    unsigned int irq_reg_stride;
    bool mask_writeonly;
    bool init_ack_masked;
    bool mask_invert;
    bool use_ack;
    bool ack_invert;
    bool wake_invert;
    bool runtime_pm;
    bool type_invert;
    int num_regs;
    const struct regmap_irq * irqs;
    int num_irqs;
    int num_type_reg;
    unsigned int type_reg_stride;
    int (*)(void *) handle_pre_irq;
    int (*)(void *) handle_post_irq;
    void * irq_drv_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct regmap_irq_chip {
    const char * name;
    unsigned int status_base;
    unsigned int mask_base;
    unsigned int unmask_base;
    unsigned int ack_base;
    unsigned int wake_base;
    unsigned int type_base;
    unsigned int irq_reg_stride;
    bool mask_writeonly;
    bool init_ack_masked;
    bool mask_invert;
    bool use_ack;
    bool ack_invert;
    bool wake_invert;
    bool runtime_pm;
    bool type_invert;
    bool type_in_mask;
    bool clear_on_unmask;
    int num_regs;
    const struct regmap_irq * irqs;
    int num_irqs;
    int num_type_reg;
    unsigned int type_reg_stride;
    int (*)(void *) handle_pre_irq;
    int (*)(void *) handle_post_irq;
    void * irq_drv_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct regmap_irq_chip {
    const char * name;
    unsigned int main_status;
    unsigned int num_main_status_bits;
    struct regmap_irq_sub_irq_map * sub_reg_offsets;
    int num_main_regs;
    unsigned int status_base;
    unsigned int mask_base;
    unsigned int unmask_base;
    unsigned int ack_base;
    unsigned int wake_base;
    unsigned int type_base;
    unsigned int irq_reg_stride;
    bool mask_writeonly;
    bool init_ack_masked;
    bool mask_invert;
    bool use_ack;
    bool ack_invert;
    bool wake_invert;
    bool runtime_pm;
    bool type_invert;
    bool type_in_mask;
    bool clear_on_unmask;
    int num_regs;
    const struct regmap_irq * irqs;
    int num_irqs;
    int num_type_reg;
    unsigned int type_reg_stride;
    int (*)(void *) handle_pre_irq;
    int (*)(void *) handle_post_irq;
    void * irq_drv_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct regmap_irq_chip {
    const char * name;
    unsigned int main_status;
    unsigned int num_main_status_bits;
    struct regmap_irq_sub_irq_map * sub_reg_offsets;
    int num_main_regs;
    unsigned int status_base;
    unsigned int mask_base;
    unsigned int unmask_base;
    unsigned int ack_base;
    unsigned int wake_base;
    unsigned int type_base;
    unsigned int irq_reg_stride;
    bool mask_writeonly;
    bool init_ack_masked;
    bool mask_invert;
    bool use_ack;
    bool ack_invert;
    bool wake_invert;
    bool runtime_pm;
    bool type_invert;
    bool type_in_mask;
    bool clear_on_unmask;
    int num_regs;
    const struct regmap_irq * irqs;
    int num_irqs;
    int num_type_reg;
    unsigned int type_reg_stride;
    int (*)(void *) handle_pre_irq;
    int (*)(void *) handle_post_irq;
    void * irq_drv_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct regmap_irq_chip {
    const char * name;
    unsigned int main_status;
    unsigned int num_main_status_bits;
    struct regmap_irq_sub_irq_map * sub_reg_offsets;
    int num_main_regs;
    unsigned int status_base;
    unsigned int mask_base;
    unsigned int unmask_base;
    unsigned int ack_base;
    unsigned int wake_base;
    unsigned int type_base;
    unsigned int irq_reg_stride;
    bool mask_writeonly;
    bool init_ack_masked;
    bool mask_invert;
    bool use_ack;
    bool ack_invert;
    bool wake_invert;
    bool runtime_pm;
    bool type_invert;
    bool type_in_mask;
    bool clear_on_unmask;
    int num_regs;
    const struct regmap_irq * irqs;
    int num_irqs;
    int num_type_reg;
    unsigned int type_reg_stride;
    int (*)(void *) handle_pre_irq;
    int (*)(void *) handle_post_irq;
    void * irq_drv_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct regmap_irq_chip {
    const char * name;
    unsigned int main_status;
    unsigned int num_main_status_bits;
    struct regmap_irq_sub_irq_map * sub_reg_offsets;
    int num_main_regs;
    unsigned int status_base;
    unsigned int mask_base;
    unsigned int unmask_base;
    unsigned int ack_base;
    unsigned int wake_base;
    unsigned int type_base;
    unsigned int irq_reg_stride;
    bool mask_writeonly;
    bool init_ack_masked;
    bool mask_invert;
    bool use_ack;
    bool ack_invert;
    bool clear_ack;
    bool wake_invert;
    bool runtime_pm;
    bool type_invert;
    bool type_in_mask;
    bool clear_on_unmask;
    int num_regs;
    const struct regmap_irq * irqs;
    int num_irqs;
    int num_type_reg;
    unsigned int type_reg_stride;
    int (*)(void *) handle_pre_irq;
    int (*)(void *) handle_post_irq;
    void * irq_drv_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct regmap_irq_chip {
    const char * name;
    unsigned int main_status;
    unsigned int num_main_status_bits;
    struct regmap_irq_sub_irq_map * sub_reg_offsets;
    int num_main_regs;
    unsigned int status_base;
    unsigned int mask_base;
    unsigned int unmask_base;
    unsigned int ack_base;
    unsigned int wake_base;
    unsigned int type_base;
    unsigned int * virt_reg_base;
    unsigned int irq_reg_stride;
    bool mask_writeonly;
    bool init_ack_masked;
    bool mask_invert;
    bool use_ack;
    bool ack_invert;
    bool clear_ack;
    bool wake_invert;
    bool runtime_pm;
    bool type_invert;
    bool type_in_mask;
    bool clear_on_unmask;
    bool not_fixed_stride;
    int num_regs;
    const struct regmap_irq * irqs;
    int num_irqs;
    int num_type_reg;
    int num_virt_regs;
    unsigned int type_reg_stride;
    int (*)(void *) handle_pre_irq;
    int (*)(void *) handle_post_irq;
    int (*)(unsigned int * *, unsigned int, long unsigned int, int) set_type_virt;
    void * irq_drv_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct regmap_irq_chip {
    const char * name;
    unsigned int main_status;
    unsigned int num_main_status_bits;
    struct regmap_irq_sub_irq_map * sub_reg_offsets;
    int num_main_regs;
    unsigned int status_base;
    unsigned int mask_base;
    unsigned int unmask_base;
    unsigned int ack_base;
    unsigned int wake_base;
    unsigned int type_base;
    unsigned int * virt_reg_base;
    unsigned int irq_reg_stride;
    bool mask_writeonly;
    bool init_ack_masked;
    bool mask_invert;
    bool use_ack;
    bool ack_invert;
    bool clear_ack;
    bool wake_invert;
    bool runtime_pm;
    bool type_invert;
    bool type_in_mask;
    bool clear_on_unmask;
    bool not_fixed_stride;
    bool status_invert;
    int num_regs;
    const struct regmap_irq * irqs;
    int num_irqs;
    int num_type_reg;
    int num_virt_regs;
    unsigned int type_reg_stride;
    int (*)(void *) handle_pre_irq;
    int (*)(void *) handle_post_irq;
    int (*)(unsigned int * *, unsigned int, long unsigned int, int) set_type_virt;
    void * irq_drv_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct regmap_irq_chip {
    const char * name;
    unsigned int main_status;
    unsigned int num_main_status_bits;
    struct regmap_irq_sub_irq_map * sub_reg_offsets;
    int num_main_regs;
    unsigned int status_base;
    unsigned int mask_base;
    unsigned int unmask_base;
    unsigned int ack_base;
    unsigned int wake_base;
    unsigned int type_base;
    unsigned int * virt_reg_base;
    unsigned int irq_reg_stride;
    bool mask_writeonly;
    bool init_ack_masked;
    bool mask_invert;
    bool use_ack;
    bool ack_invert;
    bool clear_ack;
    bool wake_invert;
    bool runtime_pm;
    bool type_invert;
    bool type_in_mask;
    bool clear_on_unmask;
    bool not_fixed_stride;
    bool status_invert;
    int num_regs;
    const struct regmap_irq * irqs;
    int num_irqs;
    int num_type_reg;
    int num_virt_regs;
    unsigned int type_reg_stride;
    int (*)(void *) handle_pre_irq;
    int (*)(void *) handle_post_irq;
    int (*)(unsigned int * *, unsigned int, long unsigned int, int) set_type_virt;
    void * irq_drv_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct regmap_irq_chip {
    const char * name;
    unsigned int main_status;
    unsigned int num_main_status_bits;
    struct regmap_irq_sub_irq_map * sub_reg_offsets;
    int num_main_regs;
    unsigned int status_base;
    unsigned int mask_base;
    unsigned int unmask_base;
    unsigned int ack_base;
    unsigned int wake_base;
    unsigned int type_base;
    unsigned int * virt_reg_base;
    const unsigned int * config_base;
    unsigned int irq_reg_stride;
    unsigned int init_ack_masked;
    unsigned int mask_invert;
    unsigned int mask_unmask_non_inverted;
    unsigned int use_ack;
    unsigned int ack_invert;
    unsigned int clear_ack;
    unsigned int wake_invert;
    unsigned int runtime_pm;
    unsigned int type_invert;
    unsigned int type_in_mask;
    unsigned int clear_on_unmask;
    unsigned int not_fixed_stride;
    unsigned int status_invert;
    int num_regs;
    const struct regmap_irq * irqs;
    int num_irqs;
    int num_type_reg;
    int num_virt_regs;
    int num_config_bases;
    int num_config_regs;
    int (*)(void *) handle_pre_irq;
    int (*)(void *) handle_post_irq;
    int (*)(struct regmap *, int, unsigned int, unsigned int, void *) handle_mask_sync;
    int (*)(unsigned int * *, unsigned int, long unsigned int, int) set_type_virt;
    int (*)(unsigned int * *, unsigned int, const struct regmap_irq *, int) set_type_config;
    unsigned int (*)(struct regmap_irq_chip_data *, unsigned int, int) get_irq_reg;
    void * irq_drv_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct regmap_irq_chip {
    const char * name;
    unsigned int main_status;
    unsigned int num_main_status_bits;
    struct regmap_irq_sub_irq_map * sub_reg_offsets;
    int num_main_regs;
    unsigned int status_base;
    unsigned int mask_base;
    unsigned int unmask_base;
    unsigned int ack_base;
    unsigned int wake_base;
    const unsigned int * config_base;
    unsigned int irq_reg_stride;
    unsigned int init_ack_masked;
    unsigned int mask_unmask_non_inverted;
    unsigned int use_ack;
    unsigned int ack_invert;
    unsigned int clear_ack;
    unsigned int status_invert;
    unsigned int wake_invert;
    unsigned int type_in_mask;
    unsigned int clear_on_unmask;
    unsigned int runtime_pm;
    unsigned int no_status;
    int num_regs;
    const struct regmap_irq * irqs;
    int num_irqs;
    int num_config_bases;
    int num_config_regs;
    int (*)(void *) handle_pre_irq;
    int (*)(void *) handle_post_irq;
    int (*)(int, unsigned int, unsigned int, void *) handle_mask_sync;
    int (*)(unsigned int * *, unsigned int, const struct regmap_irq *, int, void *) set_type_config;
    unsigned int (*)(struct regmap_irq_chip_data *, unsigned int, int) get_irq_reg;
    void * irq_drv_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct regmap_irq_chip {
    const char * name;
    unsigned int main_status;
    unsigned int num_main_status_bits;
    struct regmap_irq_sub_irq_map * sub_reg_offsets;
    int num_main_regs;
    unsigned int status_base;
    unsigned int mask_base;
    unsigned int unmask_base;
    unsigned int ack_base;
    unsigned int wake_base;
    const unsigned int * config_base;
    unsigned int irq_reg_stride;
    unsigned int init_ack_masked;
    unsigned int mask_unmask_non_inverted;
    unsigned int use_ack;
    unsigned int ack_invert;
    unsigned int clear_ack;
    unsigned int status_invert;
    unsigned int wake_invert;
    unsigned int type_in_mask;
    unsigned int clear_on_unmask;
    unsigned int runtime_pm;
    unsigned int no_status;
    int num_regs;
    const struct regmap_irq * irqs;
    int num_irqs;
    int num_config_bases;
    int num_config_regs;
    int (*)(void *) handle_pre_irq;
    int (*)(void *) handle_post_irq;
    int (*)(int, unsigned int, unsigned int, void *) handle_mask_sync;
    int (*)(unsigned int * *, unsigned int, const struct regmap_irq *, int, void *) set_type_config;
    unsigned int (*)(struct regmap_irq_chip_data *, unsigned int, int) get_irq_reg;
    void * irq_drv_data;
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
struct regmap_irq_chip {
    const char * name;
    unsigned int main_status;
    unsigned int num_main_status_bits;
    struct regmap_irq_sub_irq_map * sub_reg_offsets;
    int num_main_regs;
    unsigned int status_base;
    unsigned int mask_base;
    unsigned int unmask_base;
    unsigned int ack_base;
    unsigned int wake_base;
    unsigned int type_base;
    unsigned int irq_reg_stride;
    bool mask_writeonly;
    bool init_ack_masked;
    bool mask_invert;
    bool use_ack;
    bool ack_invert;
    bool wake_invert;
    bool runtime_pm;
    bool type_invert;
    bool type_in_mask;
    bool clear_on_unmask;
    int num_regs;
    const struct regmap_irq * irqs;
    int num_irqs;
    int num_type_reg;
    unsigned int type_reg_stride;
    int (*)(void *) handle_pre_irq;
    int (*)(void *) handle_post_irq;
    void * irq_drv_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct regmap_irq_chip {
    const char * name;
    unsigned int main_status;
    unsigned int num_main_status_bits;
    struct regmap_irq_sub_irq_map * sub_reg_offsets;
    int num_main_regs;
    unsigned int status_base;
    unsigned int mask_base;
    unsigned int unmask_base;
    unsigned int ack_base;
    unsigned int wake_base;
    unsigned int type_base;
    unsigned int irq_reg_stride;
    bool mask_writeonly;
    bool init_ack_masked;
    bool mask_invert;
    bool use_ack;
    bool ack_invert;
    bool wake_invert;
    bool runtime_pm;
    bool type_invert;
    bool type_in_mask;
    bool clear_on_unmask;
    int num_regs;
    const struct regmap_irq * irqs;
    int num_irqs;
    int num_type_reg;
    unsigned int type_reg_stride;
    int (*)(void *) handle_pre_irq;
    int (*)(void *) handle_post_irq;
    void * irq_drv_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct regmap_irq_chip {
    const char * name;
    unsigned int main_status;
    unsigned int num_main_status_bits;
    struct regmap_irq_sub_irq_map * sub_reg_offsets;
    int num_main_regs;
    unsigned int status_base;
    unsigned int mask_base;
    unsigned int unmask_base;
    unsigned int ack_base;
    unsigned int wake_base;
    unsigned int type_base;
    unsigned int irq_reg_stride;
    bool mask_writeonly;
    bool init_ack_masked;
    bool mask_invert;
    bool use_ack;
    bool ack_invert;
    bool wake_invert;
    bool runtime_pm;
    bool type_invert;
    bool type_in_mask;
    bool clear_on_unmask;
    int num_regs;
    const struct regmap_irq * irqs;
    int num_irqs;
    int num_type_reg;
    unsigned int type_reg_stride;
    int (*)(void *) handle_pre_irq;
    int (*)(void *) handle_post_irq;
    void * irq_drv_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct regmap_irq_chip {
    const char * name;
    unsigned int main_status;
    unsigned int num_main_status_bits;
    struct regmap_irq_sub_irq_map * sub_reg_offsets;
    int num_main_regs;
    unsigned int status_base;
    unsigned int mask_base;
    unsigned int unmask_base;
    unsigned int ack_base;
    unsigned int wake_base;
    unsigned int type_base;
    unsigned int irq_reg_stride;
    bool mask_writeonly;
    bool init_ack_masked;
    bool mask_invert;
    bool use_ack;
    bool ack_invert;
    bool wake_invert;
    bool runtime_pm;
    bool type_invert;
    bool type_in_mask;
    bool clear_on_unmask;
    int num_regs;
    const struct regmap_irq * irqs;
    int num_irqs;
    int num_type_reg;
    unsigned int type_reg_stride;
    int (*)(void *) handle_pre_irq;
    int (*)(void *) handle_post_irq;
    void * irq_drv_data;
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
struct regmap_irq_chip {
    const char * name;
    unsigned int main_status;
    unsigned int num_main_status_bits;
    struct regmap_irq_sub_irq_map * sub_reg_offsets;
    int num_main_regs;
    unsigned int status_base;
    unsigned int mask_base;
    unsigned int unmask_base;
    unsigned int ack_base;
    unsigned int wake_base;
    unsigned int type_base;
    unsigned int irq_reg_stride;
    bool mask_writeonly;
    bool init_ack_masked;
    bool mask_invert;
    bool use_ack;
    bool ack_invert;
    bool wake_invert;
    bool runtime_pm;
    bool type_invert;
    bool type_in_mask;
    bool clear_on_unmask;
    int num_regs;
    const struct regmap_irq * irqs;
    int num_irqs;
    int num_type_reg;
    unsigned int type_reg_stride;
    int (*)(void *) handle_pre_irq;
    int (*)(void *) handle_post_irq;
    void * irq_drv_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct regmap_irq_chip {
    const char * name;
    unsigned int main_status;
    unsigned int num_main_status_bits;
    struct regmap_irq_sub_irq_map * sub_reg_offsets;
    int num_main_regs;
    unsigned int status_base;
    unsigned int mask_base;
    unsigned int unmask_base;
    unsigned int ack_base;
    unsigned int wake_base;
    unsigned int type_base;
    unsigned int irq_reg_stride;
    bool mask_writeonly;
    bool init_ack_masked;
    bool mask_invert;
    bool use_ack;
    bool ack_invert;
    bool wake_invert;
    bool runtime_pm;
    bool type_invert;
    bool type_in_mask;
    bool clear_on_unmask;
    int num_regs;
    const struct regmap_irq * irqs;
    int num_irqs;
    int num_type_reg;
    unsigned int type_reg_stride;
    int (*)(void *) handle_pre_irq;
    int (*)(void *) handle_post_irq;
    void * irq_drv_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct regmap_irq_chip {
    const char * name;
    unsigned int main_status;
    unsigned int num_main_status_bits;
    struct regmap_irq_sub_irq_map * sub_reg_offsets;
    int num_main_regs;
    unsigned int status_base;
    unsigned int mask_base;
    unsigned int unmask_base;
    unsigned int ack_base;
    unsigned int wake_base;
    unsigned int type_base;
    unsigned int irq_reg_stride;
    bool mask_writeonly;
    bool init_ack_masked;
    bool mask_invert;
    bool use_ack;
    bool ack_invert;
    bool wake_invert;
    bool runtime_pm;
    bool type_invert;
    bool type_in_mask;
    bool clear_on_unmask;
    int num_regs;
    const struct regmap_irq * irqs;
    int num_irqs;
    int num_type_reg;
    unsigned int type_reg_stride;
    int (*)(void *) handle_pre_irq;
    int (*)(void *) handle_post_irq;
    void * irq_drv_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct regmap_irq_chip {
    const char * name;
    unsigned int main_status;
    unsigned int num_main_status_bits;
    struct regmap_irq_sub_irq_map * sub_reg_offsets;
    int num_main_regs;
    unsigned int status_base;
    unsigned int mask_base;
    unsigned int unmask_base;
    unsigned int ack_base;
    unsigned int wake_base;
    unsigned int type_base;
    unsigned int irq_reg_stride;
    bool mask_writeonly;
    bool init_ack_masked;
    bool mask_invert;
    bool use_ack;
    bool ack_invert;
    bool wake_invert;
    bool runtime_pm;
    bool type_invert;
    bool type_in_mask;
    bool clear_on_unmask;
    int num_regs;
    const struct regmap_irq * irqs;
    int num_irqs;
    int num_type_reg;
    unsigned int type_reg_stride;
    int (*)(void *) handle_pre_irq;
    int (*)(void *) handle_post_irq;
    void * irq_drv_data;
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
<code>unsigned int type_base</code>
</li>
<li>
<b>Field added. </b>
<code>bool type_invert</code>
</li>
<li>
<b>Field added. </b>
<code>int num_type_reg</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int type_reg_stride</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(void *) handle_pre_irq</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(void *) handle_post_irq</code>
</li>
<li>
<b>Field added. </b>
<code>void * irq_drv_data</code>
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
<code>bool mask_writeonly</code>
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool type_in_mask</code>
</li>
<li>
<b>Field added. </b>
<code>bool clear_on_unmask</code>
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
<code>unsigned int main_status</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int num_main_status_bits</code>
</li>
<li>
<b>Field added. </b>
<code>struct regmap_irq_sub_irq_map * sub_reg_offsets</code>
</li>
<li>
<b>Field added. </b>
<code>int num_main_regs</code>
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool clear_ack</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int * virt_reg_base</code>
</li>
<li>
<b>Field added. </b>
<code>bool not_fixed_stride</code>
</li>
<li>
<b>Field added. </b>
<code>int num_virt_regs</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(unsigned int * *, unsigned int, long unsigned int, int) set_type_virt</code>
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
<code>bool status_invert</code>
</li>
</ul>
</details>
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
<code>const unsigned int * config_base</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int mask_unmask_non_inverted</code>
</li>
<li>
<b>Field added. </b>
<code>int num_config_bases</code>
</li>
<li>
<b>Field added. </b>
<code>int num_config_regs</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct regmap *, int, unsigned int, unsigned int, void *) handle_mask_sync</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(unsigned int * *, unsigned int, const struct regmap_irq *, int) set_type_config</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int (*)(struct regmap_irq_chip_data *, unsigned int, int) get_irq_reg</code>
</li>
<li>
<b>Field removed. </b>
<code>bool mask_writeonly</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int type_reg_stride</code>
</li>
<li>
<b>Field type changed. </b>
<code>bool init_ack_masked</code> ➡️ <code>unsigned int init_ack_masked</code>
</li>
<li>
<b>Field type changed. </b>
<code>bool mask_invert</code> ➡️ <code>unsigned int mask_invert</code>
</li>
<li>
<b>Field type changed. </b>
<code>bool use_ack</code> ➡️ <code>unsigned int use_ack</code>
</li>
<li>
<b>Field type changed. </b>
<code>bool ack_invert</code> ➡️ <code>unsigned int ack_invert</code>
</li>
<li>
<b>Field type changed. </b>
<code>bool clear_ack</code> ➡️ <code>unsigned int clear_ack</code>
</li>
<li>
<b>Field type changed. </b>
<code>bool wake_invert</code> ➡️ <code>unsigned int wake_invert</code>
</li>
<li>
<b>Field type changed. </b>
<code>bool runtime_pm</code> ➡️ <code>unsigned int runtime_pm</code>
</li>
<li>
<b>Field type changed. </b>
<code>bool type_invert</code> ➡️ <code>unsigned int type_invert</code>
</li>
<li>
<b>Field type changed. </b>
<code>bool type_in_mask</code> ➡️ <code>unsigned int type_in_mask</code>
</li>
<li>
<b>Field type changed. </b>
<code>bool clear_on_unmask</code> ➡️ <code>unsigned int clear_on_unmask</code>
</li>
<li>
<b>Field type changed. </b>
<code>bool not_fixed_stride</code> ➡️ <code>unsigned int not_fixed_stride</code>
</li>
<li>
<b>Field type changed. </b>
<code>bool status_invert</code> ➡️ <code>unsigned int status_invert</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int no_status</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int type_base</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int * virt_reg_base</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int mask_invert</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int type_invert</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int not_fixed_stride</code>
</li>
<li>
<b>Field removed. </b>
<code>int num_type_reg</code>
</li>
<li>
<b>Field removed. </b>
<code>int num_virt_regs</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(unsigned int * *, unsigned int, long unsigned int, int) set_type_virt</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct regmap *, int, unsigned int, unsigned int, void *) handle_mask_sync</code> ➡️ <code>int (*)(int, unsigned int, unsigned int, void *) handle_mask_sync</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(unsigned int * *, unsigned int, const struct regmap_irq *, int) set_type_config</code> ➡️ <code>int (*)(unsigned int * *, unsigned int, const struct regmap_irq *, int, void *) set_type_config</code>
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
