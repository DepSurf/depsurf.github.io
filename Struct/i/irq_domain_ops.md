# Struct: <code>irq_domain_ops</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct irq_domain_ops {
    int (*)(struct irq_domain *, struct device_node *, enum irq_domain_bus_token) match;
    int (*)(struct irq_domain *, unsigned int, irq_hw_number_t) map;
    void (*)(struct irq_domain *, unsigned int) unmap;
    int (*)(struct irq_domain *, struct device_node *, const u32 *, unsigned int, long unsigned int *, unsigned int *) xlate;
    int (*)(struct irq_domain *, unsigned int, unsigned int, void *) alloc;
    void (*)(struct irq_domain *, unsigned int, unsigned int) free;
    void (*)(struct irq_domain *, struct irq_data *) activate;
    void (*)(struct irq_domain *, struct irq_data *) deactivate;
    int (*)(struct irq_domain *, struct irq_fwspec *, long unsigned int *, unsigned int *) translate;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct irq_domain_ops {
    int (*)(struct irq_domain *, struct device_node *, enum irq_domain_bus_token) match;
    int (*)(struct irq_domain *, struct irq_fwspec *, enum irq_domain_bus_token) select;
    int (*)(struct irq_domain *, unsigned int, irq_hw_number_t) map;
    void (*)(struct irq_domain *, unsigned int) unmap;
    int (*)(struct irq_domain *, struct device_node *, const u32 *, unsigned int, long unsigned int *, unsigned int *) xlate;
    int (*)(struct irq_domain *, unsigned int, unsigned int, void *) alloc;
    void (*)(struct irq_domain *, unsigned int, unsigned int) free;
    void (*)(struct irq_domain *, struct irq_data *) activate;
    void (*)(struct irq_domain *, struct irq_data *) deactivate;
    int (*)(struct irq_domain *, struct irq_fwspec *, long unsigned int *, unsigned int *) translate;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct irq_domain_ops {
    int (*)(struct irq_domain *, struct device_node *, enum irq_domain_bus_token) match;
    int (*)(struct irq_domain *, struct irq_fwspec *, enum irq_domain_bus_token) select;
    int (*)(struct irq_domain *, unsigned int, irq_hw_number_t) map;
    void (*)(struct irq_domain *, unsigned int) unmap;
    int (*)(struct irq_domain *, struct device_node *, const u32 *, unsigned int, long unsigned int *, unsigned int *) xlate;
    int (*)(struct irq_domain *, unsigned int, unsigned int, void *) alloc;
    void (*)(struct irq_domain *, unsigned int, unsigned int) free;
    void (*)(struct irq_domain *, struct irq_data *) activate;
    void (*)(struct irq_domain *, struct irq_data *) deactivate;
    int (*)(struct irq_domain *, struct irq_fwspec *, long unsigned int *, unsigned int *) translate;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct irq_domain_ops {
    int (*)(struct irq_domain *, struct device_node *, enum irq_domain_bus_token) match;
    int (*)(struct irq_domain *, struct irq_fwspec *, enum irq_domain_bus_token) select;
    int (*)(struct irq_domain *, unsigned int, irq_hw_number_t) map;
    void (*)(struct irq_domain *, unsigned int) unmap;
    int (*)(struct irq_domain *, struct device_node *, const u32 *, unsigned int, long unsigned int *, unsigned int *) xlate;
    int (*)(struct irq_domain *, unsigned int, unsigned int, void *) alloc;
    void (*)(struct irq_domain *, unsigned int, unsigned int) free;
    void (*)(struct irq_domain *, struct irq_data *) activate;
    void (*)(struct irq_domain *, struct irq_data *) deactivate;
    int (*)(struct irq_domain *, struct irq_fwspec *, long unsigned int *, unsigned int *) translate;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct irq_domain_ops {
    int (*)(struct irq_domain *, struct device_node *, enum irq_domain_bus_token) match;
    int (*)(struct irq_domain *, struct irq_fwspec *, enum irq_domain_bus_token) select;
    int (*)(struct irq_domain *, unsigned int, irq_hw_number_t) map;
    void (*)(struct irq_domain *, unsigned int) unmap;
    int (*)(struct irq_domain *, struct device_node *, const u32 *, unsigned int, long unsigned int *, unsigned int *) xlate;
    int (*)(struct irq_domain *, unsigned int, unsigned int, void *) alloc;
    void (*)(struct irq_domain *, unsigned int, unsigned int) free;
    int (*)(struct irq_domain *, struct irq_data *, bool) activate;
    void (*)(struct irq_domain *, struct irq_data *) deactivate;
    int (*)(struct irq_domain *, struct irq_fwspec *, long unsigned int *, unsigned int *) translate;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct irq_domain_ops {
    int (*)(struct irq_domain *, struct device_node *, enum irq_domain_bus_token) match;
    int (*)(struct irq_domain *, struct irq_fwspec *, enum irq_domain_bus_token) select;
    int (*)(struct irq_domain *, unsigned int, irq_hw_number_t) map;
    void (*)(struct irq_domain *, unsigned int) unmap;
    int (*)(struct irq_domain *, struct device_node *, const u32 *, unsigned int, long unsigned int *, unsigned int *) xlate;
    int (*)(struct irq_domain *, unsigned int, unsigned int, void *) alloc;
    void (*)(struct irq_domain *, unsigned int, unsigned int) free;
    int (*)(struct irq_domain *, struct irq_data *, bool) activate;
    void (*)(struct irq_domain *, struct irq_data *) deactivate;
    int (*)(struct irq_domain *, struct irq_fwspec *, long unsigned int *, unsigned int *) translate;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct irq_domain_ops {
    int (*)(struct irq_domain *, struct device_node *, enum irq_domain_bus_token) match;
    int (*)(struct irq_domain *, struct irq_fwspec *, enum irq_domain_bus_token) select;
    int (*)(struct irq_domain *, unsigned int, irq_hw_number_t) map;
    void (*)(struct irq_domain *, unsigned int) unmap;
    int (*)(struct irq_domain *, struct device_node *, const u32 *, unsigned int, long unsigned int *, unsigned int *) xlate;
    int (*)(struct irq_domain *, unsigned int, unsigned int, void *) alloc;
    void (*)(struct irq_domain *, unsigned int, unsigned int) free;
    int (*)(struct irq_domain *, struct irq_data *, bool) activate;
    void (*)(struct irq_domain *, struct irq_data *) deactivate;
    int (*)(struct irq_domain *, struct irq_fwspec *, long unsigned int *, unsigned int *) translate;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct irq_domain_ops {
    int (*)(struct irq_domain *, struct device_node *, enum irq_domain_bus_token) match;
    int (*)(struct irq_domain *, struct irq_fwspec *, enum irq_domain_bus_token) select;
    int (*)(struct irq_domain *, unsigned int, irq_hw_number_t) map;
    void (*)(struct irq_domain *, unsigned int) unmap;
    int (*)(struct irq_domain *, struct device_node *, const u32 *, unsigned int, long unsigned int *, unsigned int *) xlate;
    int (*)(struct irq_domain *, unsigned int, unsigned int, void *) alloc;
    void (*)(struct irq_domain *, unsigned int, unsigned int) free;
    int (*)(struct irq_domain *, struct irq_data *, bool) activate;
    void (*)(struct irq_domain *, struct irq_data *) deactivate;
    int (*)(struct irq_domain *, struct irq_fwspec *, long unsigned int *, unsigned int *) translate;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct irq_domain_ops {
    int (*)(struct irq_domain *, struct device_node *, enum irq_domain_bus_token) match;
    int (*)(struct irq_domain *, struct irq_fwspec *, enum irq_domain_bus_token) select;
    int (*)(struct irq_domain *, unsigned int, irq_hw_number_t) map;
    void (*)(struct irq_domain *, unsigned int) unmap;
    int (*)(struct irq_domain *, struct device_node *, const u32 *, unsigned int, long unsigned int *, unsigned int *) xlate;
    int (*)(struct irq_domain *, unsigned int, unsigned int, void *) alloc;
    void (*)(struct irq_domain *, unsigned int, unsigned int) free;
    int (*)(struct irq_domain *, struct irq_data *, bool) activate;
    void (*)(struct irq_domain *, struct irq_data *) deactivate;
    int (*)(struct irq_domain *, struct irq_fwspec *, long unsigned int *, unsigned int *) translate;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct irq_domain_ops {
    int (*)(struct irq_domain *, struct device_node *, enum irq_domain_bus_token) match;
    int (*)(struct irq_domain *, struct irq_fwspec *, enum irq_domain_bus_token) select;
    int (*)(struct irq_domain *, unsigned int, irq_hw_number_t) map;
    void (*)(struct irq_domain *, unsigned int) unmap;
    int (*)(struct irq_domain *, struct device_node *, const u32 *, unsigned int, long unsigned int *, unsigned int *) xlate;
    int (*)(struct irq_domain *, unsigned int, unsigned int, void *) alloc;
    void (*)(struct irq_domain *, unsigned int, unsigned int) free;
    int (*)(struct irq_domain *, struct irq_data *, bool) activate;
    void (*)(struct irq_domain *, struct irq_data *) deactivate;
    int (*)(struct irq_domain *, struct irq_fwspec *, long unsigned int *, unsigned int *) translate;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct irq_domain_ops {
    int (*)(struct irq_domain *, struct device_node *, enum irq_domain_bus_token) match;
    int (*)(struct irq_domain *, struct irq_fwspec *, enum irq_domain_bus_token) select;
    int (*)(struct irq_domain *, unsigned int, irq_hw_number_t) map;
    void (*)(struct irq_domain *, unsigned int) unmap;
    int (*)(struct irq_domain *, struct device_node *, const u32 *, unsigned int, long unsigned int *, unsigned int *) xlate;
    int (*)(struct irq_domain *, unsigned int, unsigned int, void *) alloc;
    void (*)(struct irq_domain *, unsigned int, unsigned int) free;
    int (*)(struct irq_domain *, struct irq_data *, bool) activate;
    void (*)(struct irq_domain *, struct irq_data *) deactivate;
    int (*)(struct irq_domain *, struct irq_fwspec *, long unsigned int *, unsigned int *) translate;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct irq_domain_ops {
    int (*)(struct irq_domain *, struct device_node *, enum irq_domain_bus_token) match;
    int (*)(struct irq_domain *, struct irq_fwspec *, enum irq_domain_bus_token) select;
    int (*)(struct irq_domain *, unsigned int, irq_hw_number_t) map;
    void (*)(struct irq_domain *, unsigned int) unmap;
    int (*)(struct irq_domain *, struct device_node *, const u32 *, unsigned int, long unsigned int *, unsigned int *) xlate;
    int (*)(struct irq_domain *, unsigned int, unsigned int, void *) alloc;
    void (*)(struct irq_domain *, unsigned int, unsigned int) free;
    int (*)(struct irq_domain *, struct irq_data *, bool) activate;
    void (*)(struct irq_domain *, struct irq_data *) deactivate;
    int (*)(struct irq_domain *, struct irq_fwspec *, long unsigned int *, unsigned int *) translate;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct irq_domain_ops {
    int (*)(struct irq_domain *, struct device_node *, enum irq_domain_bus_token) match;
    int (*)(struct irq_domain *, struct irq_fwspec *, enum irq_domain_bus_token) select;
    int (*)(struct irq_domain *, unsigned int, irq_hw_number_t) map;
    void (*)(struct irq_domain *, unsigned int) unmap;
    int (*)(struct irq_domain *, struct device_node *, const u32 *, unsigned int, long unsigned int *, unsigned int *) xlate;
    int (*)(struct irq_domain *, unsigned int, unsigned int, void *) alloc;
    void (*)(struct irq_domain *, unsigned int, unsigned int) free;
    int (*)(struct irq_domain *, struct irq_data *, bool) activate;
    void (*)(struct irq_domain *, struct irq_data *) deactivate;
    int (*)(struct irq_domain *, struct irq_fwspec *, long unsigned int *, unsigned int *) translate;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct irq_domain_ops {
    int (*)(struct irq_domain *, struct device_node *, enum irq_domain_bus_token) match;
    int (*)(struct irq_domain *, struct irq_fwspec *, enum irq_domain_bus_token) select;
    int (*)(struct irq_domain *, unsigned int, irq_hw_number_t) map;
    void (*)(struct irq_domain *, unsigned int) unmap;
    int (*)(struct irq_domain *, struct device_node *, const u32 *, unsigned int, long unsigned int *, unsigned int *) xlate;
    int (*)(struct irq_domain *, unsigned int, unsigned int, void *) alloc;
    void (*)(struct irq_domain *, unsigned int, unsigned int) free;
    int (*)(struct irq_domain *, struct irq_data *, bool) activate;
    void (*)(struct irq_domain *, struct irq_data *) deactivate;
    int (*)(struct irq_domain *, struct irq_fwspec *, long unsigned int *, unsigned int *) translate;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct irq_domain_ops {
    int (*)(struct irq_domain *, struct device_node *, enum irq_domain_bus_token) match;
    int (*)(struct irq_domain *, struct irq_fwspec *, enum irq_domain_bus_token) select;
    int (*)(struct irq_domain *, unsigned int, irq_hw_number_t) map;
    void (*)(struct irq_domain *, unsigned int) unmap;
    int (*)(struct irq_domain *, struct device_node *, const u32 *, unsigned int, long unsigned int *, unsigned int *) xlate;
    int (*)(struct irq_domain *, unsigned int, unsigned int, void *) alloc;
    void (*)(struct irq_domain *, unsigned int, unsigned int) free;
    int (*)(struct irq_domain *, struct irq_data *, bool) activate;
    void (*)(struct irq_domain *, struct irq_data *) deactivate;
    int (*)(struct irq_domain *, struct irq_fwspec *, long unsigned int *, unsigned int *) translate;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct irq_domain_ops {
    int (*)(struct irq_domain *, struct device_node *, enum irq_domain_bus_token) match;
    int (*)(struct irq_domain *, struct irq_fwspec *, enum irq_domain_bus_token) select;
    int (*)(struct irq_domain *, unsigned int, irq_hw_number_t) map;
    void (*)(struct irq_domain *, unsigned int) unmap;
    int (*)(struct irq_domain *, struct device_node *, const u32 *, unsigned int, long unsigned int *, unsigned int *) xlate;
    int (*)(struct irq_domain *, unsigned int, unsigned int, void *) alloc;
    void (*)(struct irq_domain *, unsigned int, unsigned int) free;
    int (*)(struct irq_domain *, struct irq_data *, bool) activate;
    void (*)(struct irq_domain *, struct irq_data *) deactivate;
    int (*)(struct irq_domain *, struct irq_fwspec *, long unsigned int *, unsigned int *) translate;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct irq_domain_ops {
    int (*)(struct irq_domain *, struct device_node *, enum irq_domain_bus_token) match;
    int (*)(struct irq_domain *, struct irq_fwspec *, enum irq_domain_bus_token) select;
    int (*)(struct irq_domain *, unsigned int, irq_hw_number_t) map;
    void (*)(struct irq_domain *, unsigned int) unmap;
    int (*)(struct irq_domain *, struct device_node *, const u32 *, unsigned int, long unsigned int *, unsigned int *) xlate;
    int (*)(struct irq_domain *, unsigned int, unsigned int, void *) alloc;
    void (*)(struct irq_domain *, unsigned int, unsigned int) free;
    int (*)(struct irq_domain *, struct irq_data *, bool) activate;
    void (*)(struct irq_domain *, struct irq_data *) deactivate;
    int (*)(struct irq_domain *, struct irq_fwspec *, long unsigned int *, unsigned int *) translate;
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
struct irq_domain_ops {
    int (*)(struct irq_domain *, struct device_node *, enum irq_domain_bus_token) match;
    int (*)(struct irq_domain *, struct irq_fwspec *, enum irq_domain_bus_token) select;
    int (*)(struct irq_domain *, unsigned int, irq_hw_number_t) map;
    void (*)(struct irq_domain *, unsigned int) unmap;
    int (*)(struct irq_domain *, struct device_node *, const u32 *, unsigned int, long unsigned int *, unsigned int *) xlate;
    int (*)(struct irq_domain *, unsigned int, unsigned int, void *) alloc;
    void (*)(struct irq_domain *, unsigned int, unsigned int) free;
    int (*)(struct irq_domain *, struct irq_data *, bool) activate;
    void (*)(struct irq_domain *, struct irq_data *) deactivate;
    int (*)(struct irq_domain *, struct irq_fwspec *, long unsigned int *, unsigned int *) translate;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct irq_domain_ops {
    int (*)(struct irq_domain *, struct device_node *, enum irq_domain_bus_token) match;
    int (*)(struct irq_domain *, struct irq_fwspec *, enum irq_domain_bus_token) select;
    int (*)(struct irq_domain *, unsigned int, irq_hw_number_t) map;
    void (*)(struct irq_domain *, unsigned int) unmap;
    int (*)(struct irq_domain *, struct device_node *, const u32 *, unsigned int, long unsigned int *, unsigned int *) xlate;
    int (*)(struct irq_domain *, unsigned int, unsigned int, void *) alloc;
    void (*)(struct irq_domain *, unsigned int, unsigned int) free;
    int (*)(struct irq_domain *, struct irq_data *, bool) activate;
    void (*)(struct irq_domain *, struct irq_data *) deactivate;
    int (*)(struct irq_domain *, struct irq_fwspec *, long unsigned int *, unsigned int *) translate;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct irq_domain_ops {
    int (*)(struct irq_domain *, struct device_node *, enum irq_domain_bus_token) match;
    int (*)(struct irq_domain *, struct irq_fwspec *, enum irq_domain_bus_token) select;
    int (*)(struct irq_domain *, unsigned int, irq_hw_number_t) map;
    void (*)(struct irq_domain *, unsigned int) unmap;
    int (*)(struct irq_domain *, struct device_node *, const u32 *, unsigned int, long unsigned int *, unsigned int *) xlate;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct irq_domain_ops {
    int (*)(struct irq_domain *, struct device_node *, enum irq_domain_bus_token) match;
    int (*)(struct irq_domain *, struct irq_fwspec *, enum irq_domain_bus_token) select;
    int (*)(struct irq_domain *, unsigned int, irq_hw_number_t) map;
    void (*)(struct irq_domain *, unsigned int) unmap;
    int (*)(struct irq_domain *, struct device_node *, const u32 *, unsigned int, long unsigned int *, unsigned int *) xlate;
    int (*)(struct irq_domain *, unsigned int, unsigned int, void *) alloc;
    void (*)(struct irq_domain *, unsigned int, unsigned int) free;
    int (*)(struct irq_domain *, struct irq_data *, bool) activate;
    void (*)(struct irq_domain *, struct irq_data *) deactivate;
    int (*)(struct irq_domain *, struct irq_fwspec *, long unsigned int *, unsigned int *) translate;
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
struct irq_domain_ops {
    int (*)(struct irq_domain *, struct device_node *, enum irq_domain_bus_token) match;
    int (*)(struct irq_domain *, struct irq_fwspec *, enum irq_domain_bus_token) select;
    int (*)(struct irq_domain *, unsigned int, irq_hw_number_t) map;
    void (*)(struct irq_domain *, unsigned int) unmap;
    int (*)(struct irq_domain *, struct device_node *, const u32 *, unsigned int, long unsigned int *, unsigned int *) xlate;
    int (*)(struct irq_domain *, unsigned int, unsigned int, void *) alloc;
    void (*)(struct irq_domain *, unsigned int, unsigned int) free;
    int (*)(struct irq_domain *, struct irq_data *, bool) activate;
    void (*)(struct irq_domain *, struct irq_data *) deactivate;
    int (*)(struct irq_domain *, struct irq_fwspec *, long unsigned int *, unsigned int *) translate;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct irq_domain_ops {
    int (*)(struct irq_domain *, struct device_node *, enum irq_domain_bus_token) match;
    int (*)(struct irq_domain *, struct irq_fwspec *, enum irq_domain_bus_token) select;
    int (*)(struct irq_domain *, unsigned int, irq_hw_number_t) map;
    void (*)(struct irq_domain *, unsigned int) unmap;
    int (*)(struct irq_domain *, struct device_node *, const u32 *, unsigned int, long unsigned int *, unsigned int *) xlate;
    int (*)(struct irq_domain *, unsigned int, unsigned int, void *) alloc;
    void (*)(struct irq_domain *, unsigned int, unsigned int) free;
    int (*)(struct irq_domain *, struct irq_data *, bool) activate;
    void (*)(struct irq_domain *, struct irq_data *) deactivate;
    int (*)(struct irq_domain *, struct irq_fwspec *, long unsigned int *, unsigned int *) translate;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct irq_domain_ops {
    int (*)(struct irq_domain *, struct device_node *, enum irq_domain_bus_token) match;
    int (*)(struct irq_domain *, struct irq_fwspec *, enum irq_domain_bus_token) select;
    int (*)(struct irq_domain *, unsigned int, irq_hw_number_t) map;
    void (*)(struct irq_domain *, unsigned int) unmap;
    int (*)(struct irq_domain *, struct device_node *, const u32 *, unsigned int, long unsigned int *, unsigned int *) xlate;
    int (*)(struct irq_domain *, unsigned int, unsigned int, void *) alloc;
    void (*)(struct irq_domain *, unsigned int, unsigned int) free;
    int (*)(struct irq_domain *, struct irq_data *, bool) activate;
    void (*)(struct irq_domain *, struct irq_data *) deactivate;
    int (*)(struct irq_domain *, struct irq_fwspec *, long unsigned int *, unsigned int *) translate;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct irq_domain_ops {
    int (*)(struct irq_domain *, struct device_node *, enum irq_domain_bus_token) match;
    int (*)(struct irq_domain *, struct irq_fwspec *, enum irq_domain_bus_token) select;
    int (*)(struct irq_domain *, unsigned int, irq_hw_number_t) map;
    void (*)(struct irq_domain *, unsigned int) unmap;
    int (*)(struct irq_domain *, struct device_node *, const u32 *, unsigned int, long unsigned int *, unsigned int *) xlate;
    int (*)(struct irq_domain *, unsigned int, unsigned int, void *) alloc;
    void (*)(struct irq_domain *, unsigned int, unsigned int) free;
    int (*)(struct irq_domain *, struct irq_data *, bool) activate;
    void (*)(struct irq_domain *, struct irq_data *) deactivate;
    int (*)(struct irq_domain *, struct irq_fwspec *, long unsigned int *, unsigned int *) translate;
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
<code>int (*)(struct irq_domain *, struct irq_fwspec *, enum irq_domain_bus_token) select</code>
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
<b>Field type changed. </b>
<code>void (*)(struct irq_domain *, struct irq_data *) activate</code> ➡️ <code>int (*)(struct irq_domain *, struct irq_data *, bool) activate</code>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>int (*)(struct irq_domain *, unsigned int, unsigned int, void *) alloc</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct irq_domain *, unsigned int, unsigned int) free</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct irq_domain *, struct irq_data *, bool) activate</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct irq_domain *, struct irq_data *) deactivate</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct irq_domain *, struct irq_fwspec *, long unsigned int *, unsigned int *) translate</code>
</li>
</ul>
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
