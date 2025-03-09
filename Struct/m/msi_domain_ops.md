# Struct: <code>msi_domain_ops</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct msi_domain_ops {
    irq_hw_number_t (*)(struct msi_domain_info *, msi_alloc_info_t *) get_hwirq;
    int (*)(struct irq_domain *, struct msi_domain_info *, unsigned int, irq_hw_number_t, msi_alloc_info_t *) msi_init;
    void (*)(struct irq_domain *, struct msi_domain_info *, unsigned int) msi_free;
    int (*)(struct irq_domain *, struct msi_domain_info *, struct device *) msi_check;
    int (*)(struct irq_domain *, struct device *, int, msi_alloc_info_t *) msi_prepare;
    void (*)(msi_alloc_info_t *, int) msi_finish;
    void (*)(msi_alloc_info_t *, struct msi_desc *) set_desc;
    int (*)(struct irq_domain *, struct msi_desc *, int) handle_error;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct msi_domain_ops {
    irq_hw_number_t (*)(struct msi_domain_info *, msi_alloc_info_t *) get_hwirq;
    int (*)(struct irq_domain *, struct msi_domain_info *, unsigned int, irq_hw_number_t, msi_alloc_info_t *) msi_init;
    void (*)(struct irq_domain *, struct msi_domain_info *, unsigned int) msi_free;
    int (*)(struct irq_domain *, struct msi_domain_info *, struct device *) msi_check;
    int (*)(struct irq_domain *, struct device *, int, msi_alloc_info_t *) msi_prepare;
    void (*)(msi_alloc_info_t *, int) msi_finish;
    void (*)(msi_alloc_info_t *, struct msi_desc *) set_desc;
    int (*)(struct irq_domain *, struct msi_desc *, int) handle_error;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct msi_domain_ops {
    irq_hw_number_t (*)(struct msi_domain_info *, msi_alloc_info_t *) get_hwirq;
    int (*)(struct irq_domain *, struct msi_domain_info *, unsigned int, irq_hw_number_t, msi_alloc_info_t *) msi_init;
    void (*)(struct irq_domain *, struct msi_domain_info *, unsigned int) msi_free;
    int (*)(struct irq_domain *, struct msi_domain_info *, struct device *) msi_check;
    int (*)(struct irq_domain *, struct device *, int, msi_alloc_info_t *) msi_prepare;
    void (*)(msi_alloc_info_t *, int) msi_finish;
    void (*)(msi_alloc_info_t *, struct msi_desc *) set_desc;
    int (*)(struct irq_domain *, struct msi_desc *, int) handle_error;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct msi_domain_ops {
    irq_hw_number_t (*)(struct msi_domain_info *, msi_alloc_info_t *) get_hwirq;
    int (*)(struct irq_domain *, struct msi_domain_info *, unsigned int, irq_hw_number_t, msi_alloc_info_t *) msi_init;
    void (*)(struct irq_domain *, struct msi_domain_info *, unsigned int) msi_free;
    int (*)(struct irq_domain *, struct msi_domain_info *, struct device *) msi_check;
    int (*)(struct irq_domain *, struct device *, int, msi_alloc_info_t *) msi_prepare;
    void (*)(msi_alloc_info_t *, int) msi_finish;
    void (*)(msi_alloc_info_t *, struct msi_desc *) set_desc;
    int (*)(struct irq_domain *, struct msi_desc *, int) handle_error;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct msi_domain_ops {
    irq_hw_number_t (*)(struct msi_domain_info *, msi_alloc_info_t *) get_hwirq;
    int (*)(struct irq_domain *, struct msi_domain_info *, unsigned int, irq_hw_number_t, msi_alloc_info_t *) msi_init;
    void (*)(struct irq_domain *, struct msi_domain_info *, unsigned int) msi_free;
    int (*)(struct irq_domain *, struct msi_domain_info *, struct device *) msi_check;
    int (*)(struct irq_domain *, struct device *, int, msi_alloc_info_t *) msi_prepare;
    void (*)(msi_alloc_info_t *, int) msi_finish;
    void (*)(msi_alloc_info_t *, struct msi_desc *) set_desc;
    int (*)(struct irq_domain *, struct msi_desc *, int) handle_error;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct msi_domain_ops {
    irq_hw_number_t (*)(struct msi_domain_info *, msi_alloc_info_t *) get_hwirq;
    int (*)(struct irq_domain *, struct msi_domain_info *, unsigned int, irq_hw_number_t, msi_alloc_info_t *) msi_init;
    void (*)(struct irq_domain *, struct msi_domain_info *, unsigned int) msi_free;
    int (*)(struct irq_domain *, struct msi_domain_info *, struct device *) msi_check;
    int (*)(struct irq_domain *, struct device *, int, msi_alloc_info_t *) msi_prepare;
    void (*)(msi_alloc_info_t *, int) msi_finish;
    void (*)(msi_alloc_info_t *, struct msi_desc *) set_desc;
    int (*)(struct irq_domain *, struct msi_desc *, int) handle_error;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct msi_domain_ops {
    irq_hw_number_t (*)(struct msi_domain_info *, msi_alloc_info_t *) get_hwirq;
    int (*)(struct irq_domain *, struct msi_domain_info *, unsigned int, irq_hw_number_t, msi_alloc_info_t *) msi_init;
    void (*)(struct irq_domain *, struct msi_domain_info *, unsigned int) msi_free;
    int (*)(struct irq_domain *, struct msi_domain_info *, struct device *) msi_check;
    int (*)(struct irq_domain *, struct device *, int, msi_alloc_info_t *) msi_prepare;
    void (*)(msi_alloc_info_t *, int) msi_finish;
    void (*)(msi_alloc_info_t *, struct msi_desc *) set_desc;
    int (*)(struct irq_domain *, struct msi_desc *, int) handle_error;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct msi_domain_ops {
    irq_hw_number_t (*)(struct msi_domain_info *, msi_alloc_info_t *) get_hwirq;
    int (*)(struct irq_domain *, struct msi_domain_info *, unsigned int, irq_hw_number_t, msi_alloc_info_t *) msi_init;
    void (*)(struct irq_domain *, struct msi_domain_info *, unsigned int) msi_free;
    int (*)(struct irq_domain *, struct msi_domain_info *, struct device *) msi_check;
    int (*)(struct irq_domain *, struct device *, int, msi_alloc_info_t *) msi_prepare;
    void (*)(msi_alloc_info_t *, int) msi_finish;
    void (*)(msi_alloc_info_t *, struct msi_desc *) set_desc;
    int (*)(struct irq_domain *, struct msi_desc *, int) handle_error;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct msi_domain_ops {
    irq_hw_number_t (*)(struct msi_domain_info *, msi_alloc_info_t *) get_hwirq;
    int (*)(struct irq_domain *, struct msi_domain_info *, unsigned int, irq_hw_number_t, msi_alloc_info_t *) msi_init;
    void (*)(struct irq_domain *, struct msi_domain_info *, unsigned int) msi_free;
    int (*)(struct irq_domain *, struct msi_domain_info *, struct device *) msi_check;
    int (*)(struct irq_domain *, struct device *, int, msi_alloc_info_t *) msi_prepare;
    void (*)(msi_alloc_info_t *, int) msi_finish;
    void (*)(msi_alloc_info_t *, struct msi_desc *) set_desc;
    int (*)(struct irq_domain *, struct msi_desc *, int) handle_error;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct msi_domain_ops {
    irq_hw_number_t (*)(struct msi_domain_info *, msi_alloc_info_t *) get_hwirq;
    int (*)(struct irq_domain *, struct msi_domain_info *, unsigned int, irq_hw_number_t, msi_alloc_info_t *) msi_init;
    void (*)(struct irq_domain *, struct msi_domain_info *, unsigned int) msi_free;
    int (*)(struct irq_domain *, struct msi_domain_info *, struct device *) msi_check;
    int (*)(struct irq_domain *, struct device *, int, msi_alloc_info_t *) msi_prepare;
    void (*)(msi_alloc_info_t *, int) msi_finish;
    void (*)(msi_alloc_info_t *, struct msi_desc *) set_desc;
    int (*)(struct irq_domain *, struct msi_desc *, int) handle_error;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct msi_domain_ops {
    irq_hw_number_t (*)(struct msi_domain_info *, msi_alloc_info_t *) get_hwirq;
    int (*)(struct irq_domain *, struct msi_domain_info *, unsigned int, irq_hw_number_t, msi_alloc_info_t *) msi_init;
    void (*)(struct irq_domain *, struct msi_domain_info *, unsigned int) msi_free;
    int (*)(struct irq_domain *, struct msi_domain_info *, struct device *) msi_check;
    int (*)(struct irq_domain *, struct device *, int, msi_alloc_info_t *) msi_prepare;
    void (*)(msi_alloc_info_t *, int) msi_finish;
    void (*)(msi_alloc_info_t *, struct msi_desc *) set_desc;
    int (*)(struct irq_domain *, struct msi_desc *, int) handle_error;
    int (*)(struct irq_domain *, struct device *, int) domain_alloc_irqs;
    void (*)(struct irq_domain *, struct device *) domain_free_irqs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct msi_domain_ops {
    irq_hw_number_t (*)(struct msi_domain_info *, msi_alloc_info_t *) get_hwirq;
    int (*)(struct irq_domain *, struct msi_domain_info *, unsigned int, irq_hw_number_t, msi_alloc_info_t *) msi_init;
    void (*)(struct irq_domain *, struct msi_domain_info *, unsigned int) msi_free;
    int (*)(struct irq_domain *, struct msi_domain_info *, struct device *) msi_check;
    int (*)(struct irq_domain *, struct device *, int, msi_alloc_info_t *) msi_prepare;
    void (*)(msi_alloc_info_t *, int) msi_finish;
    void (*)(msi_alloc_info_t *, struct msi_desc *) set_desc;
    int (*)(struct irq_domain *, struct msi_desc *, int) handle_error;
    int (*)(struct irq_domain *, struct device *, int) domain_alloc_irqs;
    void (*)(struct irq_domain *, struct device *) domain_free_irqs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct msi_domain_ops {
    irq_hw_number_t (*)(struct msi_domain_info *, msi_alloc_info_t *) get_hwirq;
    int (*)(struct irq_domain *, struct msi_domain_info *, unsigned int, irq_hw_number_t, msi_alloc_info_t *) msi_init;
    void (*)(struct irq_domain *, struct msi_domain_info *, unsigned int) msi_free;
    int (*)(struct irq_domain *, struct msi_domain_info *, struct device *) msi_check;
    int (*)(struct irq_domain *, struct device *, int, msi_alloc_info_t *) msi_prepare;
    void (*)(msi_alloc_info_t *, int) msi_finish;
    void (*)(msi_alloc_info_t *, struct msi_desc *) set_desc;
    int (*)(struct irq_domain *, struct msi_desc *, int) handle_error;
    int (*)(struct irq_domain *, struct device *, int) domain_alloc_irqs;
    void (*)(struct irq_domain *, struct device *) domain_free_irqs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct msi_domain_ops {
    irq_hw_number_t (*)(struct msi_domain_info *, msi_alloc_info_t *) get_hwirq;
    int (*)(struct irq_domain *, struct msi_domain_info *, unsigned int, irq_hw_number_t, msi_alloc_info_t *) msi_init;
    void (*)(struct irq_domain *, struct msi_domain_info *, unsigned int) msi_free;
    int (*)(struct irq_domain *, struct msi_domain_info *, struct device *) msi_check;
    int (*)(struct irq_domain *, struct device *, int, msi_alloc_info_t *) msi_prepare;
    void (*)(msi_alloc_info_t *, struct msi_desc *) set_desc;
    int (*)(struct irq_domain *, struct device *, int) domain_alloc_irqs;
    void (*)(struct irq_domain *, struct device *) domain_free_irqs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct msi_domain_ops {
    irq_hw_number_t (*)(struct msi_domain_info *, msi_alloc_info_t *) get_hwirq;
    int (*)(struct irq_domain *, struct msi_domain_info *, unsigned int, irq_hw_number_t, msi_alloc_info_t *) msi_init;
    void (*)(struct irq_domain *, struct msi_domain_info *, unsigned int) msi_free;
    int (*)(struct irq_domain *, struct device *, int, msi_alloc_info_t *) msi_prepare;
    void (*)(struct irq_domain *, msi_alloc_info_t *, struct msi_desc *) prepare_desc;
    void (*)(msi_alloc_info_t *, struct msi_desc *) set_desc;
    int (*)(struct irq_domain *, struct device *, int) domain_alloc_irqs;
    void (*)(struct irq_domain *, struct device *) domain_free_irqs;
    void (*)(struct irq_domain *, struct device *) msi_post_free;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct msi_domain_ops {
    irq_hw_number_t (*)(struct msi_domain_info *, msi_alloc_info_t *) get_hwirq;
    int (*)(struct irq_domain *, struct msi_domain_info *, unsigned int, irq_hw_number_t, msi_alloc_info_t *) msi_init;
    void (*)(struct irq_domain *, struct msi_domain_info *, unsigned int) msi_free;
    int (*)(struct irq_domain *, struct device *, int, msi_alloc_info_t *) msi_prepare;
    void (*)(struct irq_domain *, msi_alloc_info_t *, struct msi_desc *) prepare_desc;
    void (*)(msi_alloc_info_t *, struct msi_desc *) set_desc;
    int (*)(struct irq_domain *, struct device *, int) domain_alloc_irqs;
    void (*)(struct irq_domain *, struct device *) domain_free_irqs;
    void (*)(struct irq_domain *, struct device *) msi_post_free;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct msi_domain_ops {
    irq_hw_number_t (*)(struct msi_domain_info *, msi_alloc_info_t *) get_hwirq;
    int (*)(struct irq_domain *, struct msi_domain_info *, unsigned int, irq_hw_number_t, msi_alloc_info_t *) msi_init;
    void (*)(struct irq_domain *, struct msi_domain_info *, unsigned int) msi_free;
    int (*)(struct irq_domain *, struct device *, int, msi_alloc_info_t *) msi_prepare;
    void (*)(struct irq_domain *, msi_alloc_info_t *, struct msi_desc *) prepare_desc;
    void (*)(msi_alloc_info_t *, struct msi_desc *) set_desc;
    int (*)(struct irq_domain *, struct device *, int) domain_alloc_irqs;
    void (*)(struct irq_domain *, struct device *) domain_free_irqs;
    void (*)(struct irq_domain *, struct device *) msi_post_free;
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
struct msi_domain_ops {
    irq_hw_number_t (*)(struct msi_domain_info *, msi_alloc_info_t *) get_hwirq;
    int (*)(struct irq_domain *, struct msi_domain_info *, unsigned int, irq_hw_number_t, msi_alloc_info_t *) msi_init;
    void (*)(struct irq_domain *, struct msi_domain_info *, unsigned int) msi_free;
    int (*)(struct irq_domain *, struct msi_domain_info *, struct device *) msi_check;
    int (*)(struct irq_domain *, struct device *, int, msi_alloc_info_t *) msi_prepare;
    void (*)(msi_alloc_info_t *, int) msi_finish;
    void (*)(msi_alloc_info_t *, struct msi_desc *) set_desc;
    int (*)(struct irq_domain *, struct msi_desc *, int) handle_error;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct msi_domain_ops {
    irq_hw_number_t (*)(struct msi_domain_info *, msi_alloc_info_t *) get_hwirq;
    int (*)(struct irq_domain *, struct msi_domain_info *, unsigned int, irq_hw_number_t, msi_alloc_info_t *) msi_init;
    void (*)(struct irq_domain *, struct msi_domain_info *, unsigned int) msi_free;
    int (*)(struct irq_domain *, struct msi_domain_info *, struct device *) msi_check;
    int (*)(struct irq_domain *, struct device *, int, msi_alloc_info_t *) msi_prepare;
    void (*)(msi_alloc_info_t *, int) msi_finish;
    void (*)(msi_alloc_info_t *, struct msi_desc *) set_desc;
    int (*)(struct irq_domain *, struct msi_desc *, int) handle_error;
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct msi_domain_ops {
    irq_hw_number_t (*)(struct msi_domain_info *, msi_alloc_info_t *) get_hwirq;
    int (*)(struct irq_domain *, struct msi_domain_info *, unsigned int, irq_hw_number_t, msi_alloc_info_t *) msi_init;
    void (*)(struct irq_domain *, struct msi_domain_info *, unsigned int) msi_free;
    int (*)(struct irq_domain *, struct msi_domain_info *, struct device *) msi_check;
    int (*)(struct irq_domain *, struct device *, int, msi_alloc_info_t *) msi_prepare;
    void (*)(msi_alloc_info_t *, int) msi_finish;
    void (*)(msi_alloc_info_t *, struct msi_desc *) set_desc;
    int (*)(struct irq_domain *, struct msi_desc *, int) handle_error;
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
struct msi_domain_ops {
    irq_hw_number_t (*)(struct msi_domain_info *, msi_alloc_info_t *) get_hwirq;
    int (*)(struct irq_domain *, struct msi_domain_info *, unsigned int, irq_hw_number_t, msi_alloc_info_t *) msi_init;
    void (*)(struct irq_domain *, struct msi_domain_info *, unsigned int) msi_free;
    int (*)(struct irq_domain *, struct msi_domain_info *, struct device *) msi_check;
    int (*)(struct irq_domain *, struct device *, int, msi_alloc_info_t *) msi_prepare;
    void (*)(msi_alloc_info_t *, int) msi_finish;
    void (*)(msi_alloc_info_t *, struct msi_desc *) set_desc;
    int (*)(struct irq_domain *, struct msi_desc *, int) handle_error;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct msi_domain_ops {
    irq_hw_number_t (*)(struct msi_domain_info *, msi_alloc_info_t *) get_hwirq;
    int (*)(struct irq_domain *, struct msi_domain_info *, unsigned int, irq_hw_number_t, msi_alloc_info_t *) msi_init;
    void (*)(struct irq_domain *, struct msi_domain_info *, unsigned int) msi_free;
    int (*)(struct irq_domain *, struct msi_domain_info *, struct device *) msi_check;
    int (*)(struct irq_domain *, struct device *, int, msi_alloc_info_t *) msi_prepare;
    void (*)(msi_alloc_info_t *, int) msi_finish;
    void (*)(msi_alloc_info_t *, struct msi_desc *) set_desc;
    int (*)(struct irq_domain *, struct msi_desc *, int) handle_error;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct msi_domain_ops {
    irq_hw_number_t (*)(struct msi_domain_info *, msi_alloc_info_t *) get_hwirq;
    int (*)(struct irq_domain *, struct msi_domain_info *, unsigned int, irq_hw_number_t, msi_alloc_info_t *) msi_init;
    void (*)(struct irq_domain *, struct msi_domain_info *, unsigned int) msi_free;
    int (*)(struct irq_domain *, struct msi_domain_info *, struct device *) msi_check;
    int (*)(struct irq_domain *, struct device *, int, msi_alloc_info_t *) msi_prepare;
    void (*)(msi_alloc_info_t *, int) msi_finish;
    void (*)(msi_alloc_info_t *, struct msi_desc *) set_desc;
    int (*)(struct irq_domain *, struct msi_desc *, int) handle_error;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct msi_domain_ops {
    irq_hw_number_t (*)(struct msi_domain_info *, msi_alloc_info_t *) get_hwirq;
    int (*)(struct irq_domain *, struct msi_domain_info *, unsigned int, irq_hw_number_t, msi_alloc_info_t *) msi_init;
    void (*)(struct irq_domain *, struct msi_domain_info *, unsigned int) msi_free;
    int (*)(struct irq_domain *, struct msi_domain_info *, struct device *) msi_check;
    int (*)(struct irq_domain *, struct device *, int, msi_alloc_info_t *) msi_prepare;
    void (*)(msi_alloc_info_t *, int) msi_finish;
    void (*)(msi_alloc_info_t *, struct msi_desc *) set_desc;
    int (*)(struct irq_domain *, struct msi_desc *, int) handle_error;
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
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct irq_domain *, struct device *, int) domain_alloc_irqs</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct irq_domain *, struct device *) domain_free_irqs</code>
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>void (*)(msi_alloc_info_t *, int) msi_finish</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct irq_domain *, struct msi_desc *, int) handle_error</code>
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
<code>void (*)(struct irq_domain *, msi_alloc_info_t *, struct msi_desc *) prepare_desc</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct irq_domain *, struct device *) msi_post_free</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct irq_domain *, struct msi_domain_info *, struct device *) msi_check</code>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct msi_domain_ops {
    irq_hw_number_t (*)(struct msi_domain_info *, msi_alloc_info_t *) get_hwirq;
    int (*)(struct irq_domain *, struct msi_domain_info *, unsigned int, irq_hw_number_t, msi_alloc_info_t *) msi_init;
    void (*)(struct irq_domain *, struct msi_domain_info *, unsigned int) msi_free;
    int (*)(struct irq_domain *, struct msi_domain_info *, struct device *) msi_check;
    int (*)(struct irq_domain *, struct device *, int, msi_alloc_info_t *) msi_prepare;
    void (*)(msi_alloc_info_t *, int) msi_finish;
    void (*)(msi_alloc_info_t *, struct msi_desc *) set_desc;
    int (*)(struct irq_domain *, struct msi_desc *, int) handle_error;
}
```
</details>
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
