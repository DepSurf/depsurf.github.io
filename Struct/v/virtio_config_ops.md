# Struct: <code>virtio_config_ops</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct virtio_config_ops {
    void (*)(struct virtio_device *, unsigned int, void *, unsigned int) get;
    void (*)(struct virtio_device *, unsigned int, const void *, unsigned int) set;
    u32 (*)(struct virtio_device *) generation;
    u8 (*)(struct virtio_device *) get_status;
    void (*)(struct virtio_device *, u8) set_status;
    void (*)(struct virtio_device *) reset;
    int (*)(struct virtio_device *, unsigned int, struct virtqueue * *, vq_callback_t * *, const char * *) find_vqs;
    void (*)(struct virtio_device *) del_vqs;
    u64 (*)(struct virtio_device *) get_features;
    int (*)(struct virtio_device *) finalize_features;
    const char * (*)(struct virtio_device *) bus_name;
    int (*)(struct virtqueue *, int) set_vq_affinity;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct virtio_config_ops {
    void (*)(struct virtio_device *, unsigned int, void *, unsigned int) get;
    void (*)(struct virtio_device *, unsigned int, const void *, unsigned int) set;
    u32 (*)(struct virtio_device *) generation;
    u8 (*)(struct virtio_device *) get_status;
    void (*)(struct virtio_device *, u8) set_status;
    void (*)(struct virtio_device *) reset;
    int (*)(struct virtio_device *, unsigned int, struct virtqueue * *, vq_callback_t * *, const const char * *) find_vqs;
    void (*)(struct virtio_device *) del_vqs;
    u64 (*)(struct virtio_device *) get_features;
    int (*)(struct virtio_device *) finalize_features;
    const char * (*)(struct virtio_device *) bus_name;
    int (*)(struct virtqueue *, int) set_vq_affinity;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct virtio_config_ops {
    void (*)(struct virtio_device *, unsigned int, void *, unsigned int) get;
    void (*)(struct virtio_device *, unsigned int, const void *, unsigned int) set;
    u32 (*)(struct virtio_device *) generation;
    u8 (*)(struct virtio_device *) get_status;
    void (*)(struct virtio_device *, u8) set_status;
    void (*)(struct virtio_device *) reset;
    int (*)(struct virtio_device *, unsigned int, struct virtqueue * *, vq_callback_t * *, const const char * *) find_vqs;
    void (*)(struct virtio_device *) del_vqs;
    u64 (*)(struct virtio_device *) get_features;
    int (*)(struct virtio_device *) finalize_features;
    const char * (*)(struct virtio_device *) bus_name;
    int (*)(struct virtqueue *, int) set_vq_affinity;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct virtio_config_ops {
    void (*)(struct virtio_device *, unsigned int, void *, unsigned int) get;
    void (*)(struct virtio_device *, unsigned int, const void *, unsigned int) set;
    u32 (*)(struct virtio_device *) generation;
    u8 (*)(struct virtio_device *) get_status;
    void (*)(struct virtio_device *, u8) set_status;
    void (*)(struct virtio_device *) reset;
    int (*)(struct virtio_device *, unsigned int, struct virtqueue * *, vq_callback_t * *, const const char * *, const bool *, struct irq_affinity *) find_vqs;
    void (*)(struct virtio_device *) del_vqs;
    u64 (*)(struct virtio_device *) get_features;
    int (*)(struct virtio_device *) finalize_features;
    const char * (*)(struct virtio_device *) bus_name;
    int (*)(struct virtqueue *, int) set_vq_affinity;
    const struct cpumask * (*)(struct virtio_device *, int) get_vq_affinity;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct virtio_config_ops {
    void (*)(struct virtio_device *, unsigned int, void *, unsigned int) get;
    void (*)(struct virtio_device *, unsigned int, const void *, unsigned int) set;
    u32 (*)(struct virtio_device *) generation;
    u8 (*)(struct virtio_device *) get_status;
    void (*)(struct virtio_device *, u8) set_status;
    void (*)(struct virtio_device *) reset;
    int (*)(struct virtio_device *, unsigned int, struct virtqueue * *, vq_callback_t * *, const const char * *, const bool *, struct irq_affinity *) find_vqs;
    void (*)(struct virtio_device *) del_vqs;
    u64 (*)(struct virtio_device *) get_features;
    int (*)(struct virtio_device *) finalize_features;
    const char * (*)(struct virtio_device *) bus_name;
    int (*)(struct virtqueue *, int) set_vq_affinity;
    const struct cpumask * (*)(struct virtio_device *, int) get_vq_affinity;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct virtio_config_ops {
    void (*)(struct virtio_device *, unsigned int, void *, unsigned int) get;
    void (*)(struct virtio_device *, unsigned int, const void *, unsigned int) set;
    u32 (*)(struct virtio_device *) generation;
    u8 (*)(struct virtio_device *) get_status;
    void (*)(struct virtio_device *, u8) set_status;
    void (*)(struct virtio_device *) reset;
    int (*)(struct virtio_device *, unsigned int, struct virtqueue * *, vq_callback_t * *, const const char * *, const bool *, struct irq_affinity *) find_vqs;
    void (*)(struct virtio_device *) del_vqs;
    u64 (*)(struct virtio_device *) get_features;
    int (*)(struct virtio_device *) finalize_features;
    const char * (*)(struct virtio_device *) bus_name;
    int (*)(struct virtqueue *, int) set_vq_affinity;
    const struct cpumask * (*)(struct virtio_device *, int) get_vq_affinity;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct virtio_config_ops {
    void (*)(struct virtio_device *, unsigned int, void *, unsigned int) get;
    void (*)(struct virtio_device *, unsigned int, const void *, unsigned int) set;
    u32 (*)(struct virtio_device *) generation;
    u8 (*)(struct virtio_device *) get_status;
    void (*)(struct virtio_device *, u8) set_status;
    void (*)(struct virtio_device *) reset;
    int (*)(struct virtio_device *, unsigned int, struct virtqueue * *, vq_callback_t * *, const const char * *, const bool *, struct irq_affinity *) find_vqs;
    void (*)(struct virtio_device *) del_vqs;
    u64 (*)(struct virtio_device *) get_features;
    int (*)(struct virtio_device *) finalize_features;
    const char * (*)(struct virtio_device *) bus_name;
    int (*)(struct virtqueue *, const struct cpumask *) set_vq_affinity;
    const struct cpumask * (*)(struct virtio_device *, int) get_vq_affinity;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct virtio_config_ops {
    void (*)(struct virtio_device *, unsigned int, void *, unsigned int) get;
    void (*)(struct virtio_device *, unsigned int, const void *, unsigned int) set;
    u32 (*)(struct virtio_device *) generation;
    u8 (*)(struct virtio_device *) get_status;
    void (*)(struct virtio_device *, u8) set_status;
    void (*)(struct virtio_device *) reset;
    int (*)(struct virtio_device *, unsigned int, struct virtqueue * *, vq_callback_t * *, const const char * *, const bool *, struct irq_affinity *) find_vqs;
    void (*)(struct virtio_device *) del_vqs;
    u64 (*)(struct virtio_device *) get_features;
    int (*)(struct virtio_device *) finalize_features;
    const char * (*)(struct virtio_device *) bus_name;
    int (*)(struct virtqueue *, const struct cpumask *) set_vq_affinity;
    const struct cpumask * (*)(struct virtio_device *, int) get_vq_affinity;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct virtio_config_ops {
    void (*)(struct virtio_device *, unsigned int, void *, unsigned int) get;
    void (*)(struct virtio_device *, unsigned int, const void *, unsigned int) set;
    u32 (*)(struct virtio_device *) generation;
    u8 (*)(struct virtio_device *) get_status;
    void (*)(struct virtio_device *, u8) set_status;
    void (*)(struct virtio_device *) reset;
    int (*)(struct virtio_device *, unsigned int, struct virtqueue * *, vq_callback_t * *, const const char * *, const bool *, struct irq_affinity *) find_vqs;
    void (*)(struct virtio_device *) del_vqs;
    u64 (*)(struct virtio_device *) get_features;
    int (*)(struct virtio_device *) finalize_features;
    const char * (*)(struct virtio_device *) bus_name;
    int (*)(struct virtqueue *, const struct cpumask *) set_vq_affinity;
    const struct cpumask * (*)(struct virtio_device *, int) get_vq_affinity;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct virtio_config_ops {
    void (*)(struct virtio_device *, unsigned int, void *, unsigned int) get;
    void (*)(struct virtio_device *, unsigned int, const void *, unsigned int) set;
    u32 (*)(struct virtio_device *) generation;
    u8 (*)(struct virtio_device *) get_status;
    void (*)(struct virtio_device *, u8) set_status;
    void (*)(struct virtio_device *) reset;
    int (*)(struct virtio_device *, unsigned int, struct virtqueue * *, vq_callback_t * *, const const char * *, const bool *, struct irq_affinity *) find_vqs;
    void (*)(struct virtio_device *) del_vqs;
    u64 (*)(struct virtio_device *) get_features;
    int (*)(struct virtio_device *) finalize_features;
    const char * (*)(struct virtio_device *) bus_name;
    int (*)(struct virtqueue *, const struct cpumask *) set_vq_affinity;
    const struct cpumask * (*)(struct virtio_device *, int) get_vq_affinity;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct virtio_config_ops {
    void (*)(struct virtio_device *, unsigned int, void *, unsigned int) get;
    void (*)(struct virtio_device *, unsigned int, const void *, unsigned int) set;
    u32 (*)(struct virtio_device *) generation;
    u8 (*)(struct virtio_device *) get_status;
    void (*)(struct virtio_device *, u8) set_status;
    void (*)(struct virtio_device *) reset;
    int (*)(struct virtio_device *, unsigned int, struct virtqueue * *, vq_callback_t * *, const const char * *, const bool *, struct irq_affinity *) find_vqs;
    void (*)(struct virtio_device *) del_vqs;
    u64 (*)(struct virtio_device *) get_features;
    int (*)(struct virtio_device *) finalize_features;
    const char * (*)(struct virtio_device *) bus_name;
    int (*)(struct virtqueue *, const struct cpumask *) set_vq_affinity;
    const struct cpumask * (*)(struct virtio_device *, int) get_vq_affinity;
    bool (*)(struct virtio_device *, struct virtio_shm_region *, u8) get_shm_region;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct virtio_config_ops {
    void (*)(struct virtio_device *, unsigned int, void *, unsigned int) get;
    void (*)(struct virtio_device *, unsigned int, const void *, unsigned int) set;
    u32 (*)(struct virtio_device *) generation;
    u8 (*)(struct virtio_device *) get_status;
    void (*)(struct virtio_device *, u8) set_status;
    void (*)(struct virtio_device *) reset;
    int (*)(struct virtio_device *, unsigned int, struct virtqueue * *, vq_callback_t * *, const const char * *, const bool *, struct irq_affinity *) find_vqs;
    void (*)(struct virtio_device *) del_vqs;
    u64 (*)(struct virtio_device *) get_features;
    int (*)(struct virtio_device *) finalize_features;
    const char * (*)(struct virtio_device *) bus_name;
    int (*)(struct virtqueue *, const struct cpumask *) set_vq_affinity;
    const struct cpumask * (*)(struct virtio_device *, int) get_vq_affinity;
    bool (*)(struct virtio_device *, struct virtio_shm_region *, u8) get_shm_region;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct virtio_config_ops {
    void (*)(struct virtio_device *, unsigned int, void *, unsigned int) get;
    void (*)(struct virtio_device *, unsigned int, const void *, unsigned int) set;
    u32 (*)(struct virtio_device *) generation;
    u8 (*)(struct virtio_device *) get_status;
    void (*)(struct virtio_device *, u8) set_status;
    void (*)(struct virtio_device *) reset;
    int (*)(struct virtio_device *, unsigned int, struct virtqueue * *, vq_callback_t * *, const const char * *, const bool *, struct irq_affinity *) find_vqs;
    void (*)(struct virtio_device *) del_vqs;
    u64 (*)(struct virtio_device *) get_features;
    int (*)(struct virtio_device *) finalize_features;
    const char * (*)(struct virtio_device *) bus_name;
    int (*)(struct virtqueue *, const struct cpumask *) set_vq_affinity;
    const struct cpumask * (*)(struct virtio_device *, int) get_vq_affinity;
    bool (*)(struct virtio_device *, struct virtio_shm_region *, u8) get_shm_region;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct virtio_config_ops {
    void (*)(struct virtio_device *, unsigned int, void *, unsigned int) get;
    void (*)(struct virtio_device *, unsigned int, const void *, unsigned int) set;
    u32 (*)(struct virtio_device *) generation;
    u8 (*)(struct virtio_device *) get_status;
    void (*)(struct virtio_device *, u8) set_status;
    void (*)(struct virtio_device *) reset;
    int (*)(struct virtio_device *, unsigned int, struct virtqueue * *, vq_callback_t * *, const const char * *, const bool *, struct irq_affinity *) find_vqs;
    void (*)(struct virtio_device *) del_vqs;
    void (*)(struct virtio_device *) synchronize_cbs;
    u64 (*)(struct virtio_device *) get_features;
    int (*)(struct virtio_device *) finalize_features;
    const char * (*)(struct virtio_device *) bus_name;
    int (*)(struct virtqueue *, const struct cpumask *) set_vq_affinity;
    const struct cpumask * (*)(struct virtio_device *, int) get_vq_affinity;
    bool (*)(struct virtio_device *, struct virtio_shm_region *, u8) get_shm_region;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct virtio_config_ops {
    void (*)(struct virtio_device *, unsigned int, void *, unsigned int) get;
    void (*)(struct virtio_device *, unsigned int, const void *, unsigned int) set;
    u32 (*)(struct virtio_device *) generation;
    u8 (*)(struct virtio_device *) get_status;
    void (*)(struct virtio_device *, u8) set_status;
    void (*)(struct virtio_device *) reset;
    int (*)(struct virtio_device *, unsigned int, struct virtqueue * *, vq_callback_t * *, const const char * *, const bool *, struct irq_affinity *) find_vqs;
    void (*)(struct virtio_device *) del_vqs;
    void (*)(struct virtio_device *) synchronize_cbs;
    u64 (*)(struct virtio_device *) get_features;
    int (*)(struct virtio_device *) finalize_features;
    const char * (*)(struct virtio_device *) bus_name;
    int (*)(struct virtqueue *, const struct cpumask *) set_vq_affinity;
    const struct cpumask * (*)(struct virtio_device *, int) get_vq_affinity;
    bool (*)(struct virtio_device *, struct virtio_shm_region *, u8) get_shm_region;
    int (*)(struct virtqueue *) disable_vq_and_reset;
    int (*)(struct virtqueue *) enable_vq_after_reset;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct virtio_config_ops {
    void (*)(struct virtio_device *, unsigned int, void *, unsigned int) get;
    void (*)(struct virtio_device *, unsigned int, const void *, unsigned int) set;
    u32 (*)(struct virtio_device *) generation;
    u8 (*)(struct virtio_device *) get_status;
    void (*)(struct virtio_device *, u8) set_status;
    void (*)(struct virtio_device *) reset;
    int (*)(struct virtio_device *, unsigned int, struct virtqueue * *, vq_callback_t * *, const const char * *, const bool *, struct irq_affinity *) find_vqs;
    void (*)(struct virtio_device *) del_vqs;
    void (*)(struct virtio_device *) synchronize_cbs;
    u64 (*)(struct virtio_device *) get_features;
    int (*)(struct virtio_device *) finalize_features;
    const char * (*)(struct virtio_device *) bus_name;
    int (*)(struct virtqueue *, const struct cpumask *) set_vq_affinity;
    const struct cpumask * (*)(struct virtio_device *, int) get_vq_affinity;
    bool (*)(struct virtio_device *, struct virtio_shm_region *, u8) get_shm_region;
    int (*)(struct virtqueue *) disable_vq_and_reset;
    int (*)(struct virtqueue *) enable_vq_after_reset;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct virtio_config_ops {
    void (*)(struct virtio_device *, unsigned int, void *, unsigned int) get;
    void (*)(struct virtio_device *, unsigned int, const void *, unsigned int) set;
    u32 (*)(struct virtio_device *) generation;
    u8 (*)(struct virtio_device *) get_status;
    void (*)(struct virtio_device *, u8) set_status;
    void (*)(struct virtio_device *) reset;
    int (*)(struct virtio_device *, unsigned int, struct virtqueue * *, vq_callback_t * *, const const char * *, const bool *, struct irq_affinity *) find_vqs;
    void (*)(struct virtio_device *) del_vqs;
    void (*)(struct virtio_device *) synchronize_cbs;
    u64 (*)(struct virtio_device *) get_features;
    int (*)(struct virtio_device *) finalize_features;
    const char * (*)(struct virtio_device *) bus_name;
    int (*)(struct virtqueue *, const struct cpumask *) set_vq_affinity;
    const struct cpumask * (*)(struct virtio_device *, int) get_vq_affinity;
    bool (*)(struct virtio_device *, struct virtio_shm_region *, u8) get_shm_region;
    int (*)(struct virtqueue *) disable_vq_and_reset;
    int (*)(struct virtqueue *) enable_vq_after_reset;
    int (*)(struct virtio_device *) create_avq;
    void (*)(struct virtio_device *) destroy_avq;
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
struct virtio_config_ops {
    void (*)(struct virtio_device *, unsigned int, void *, unsigned int) get;
    void (*)(struct virtio_device *, unsigned int, const void *, unsigned int) set;
    u32 (*)(struct virtio_device *) generation;
    u8 (*)(struct virtio_device *) get_status;
    void (*)(struct virtio_device *, u8) set_status;
    void (*)(struct virtio_device *) reset;
    int (*)(struct virtio_device *, unsigned int, struct virtqueue * *, vq_callback_t * *, const const char * *, const bool *, struct irq_affinity *) find_vqs;
    void (*)(struct virtio_device *) del_vqs;
    u64 (*)(struct virtio_device *) get_features;
    int (*)(struct virtio_device *) finalize_features;
    const char * (*)(struct virtio_device *) bus_name;
    int (*)(struct virtqueue *, const struct cpumask *) set_vq_affinity;
    const struct cpumask * (*)(struct virtio_device *, int) get_vq_affinity;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct virtio_config_ops {
    void (*)(struct virtio_device *, unsigned int, void *, unsigned int) get;
    void (*)(struct virtio_device *, unsigned int, const void *, unsigned int) set;
    u32 (*)(struct virtio_device *) generation;
    u8 (*)(struct virtio_device *) get_status;
    void (*)(struct virtio_device *, u8) set_status;
    void (*)(struct virtio_device *) reset;
    int (*)(struct virtio_device *, unsigned int, struct virtqueue * *, vq_callback_t * *, const const char * *, const bool *, struct irq_affinity *) find_vqs;
    void (*)(struct virtio_device *) del_vqs;
    u64 (*)(struct virtio_device *) get_features;
    int (*)(struct virtio_device *) finalize_features;
    const char * (*)(struct virtio_device *) bus_name;
    int (*)(struct virtqueue *, const struct cpumask *) set_vq_affinity;
    const struct cpumask * (*)(struct virtio_device *, int) get_vq_affinity;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct virtio_config_ops {
    void (*)(struct virtio_device *, unsigned int, void *, unsigned int) get;
    void (*)(struct virtio_device *, unsigned int, const void *, unsigned int) set;
    u32 (*)(struct virtio_device *) generation;
    u8 (*)(struct virtio_device *) get_status;
    void (*)(struct virtio_device *, u8) set_status;
    void (*)(struct virtio_device *) reset;
    int (*)(struct virtio_device *, unsigned int, struct virtqueue * *, vq_callback_t * *, const const char * *, const bool *, struct irq_affinity *) find_vqs;
    void (*)(struct virtio_device *) del_vqs;
    u64 (*)(struct virtio_device *) get_features;
    int (*)(struct virtio_device *) finalize_features;
    const char * (*)(struct virtio_device *) bus_name;
    int (*)(struct virtqueue *, const struct cpumask *) set_vq_affinity;
    const struct cpumask * (*)(struct virtio_device *, int) get_vq_affinity;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct virtio_config_ops {
    void (*)(struct virtio_device *, unsigned int, void *, unsigned int) get;
    void (*)(struct virtio_device *, unsigned int, const void *, unsigned int) set;
    u32 (*)(struct virtio_device *) generation;
    u8 (*)(struct virtio_device *) get_status;
    void (*)(struct virtio_device *, u8) set_status;
    void (*)(struct virtio_device *) reset;
    int (*)(struct virtio_device *, unsigned int, struct virtqueue * *, vq_callback_t * *, const const char * *, const bool *, struct irq_affinity *) find_vqs;
    void (*)(struct virtio_device *) del_vqs;
    u64 (*)(struct virtio_device *) get_features;
    int (*)(struct virtio_device *) finalize_features;
    const char * (*)(struct virtio_device *) bus_name;
    int (*)(struct virtqueue *, const struct cpumask *) set_vq_affinity;
    const struct cpumask * (*)(struct virtio_device *, int) get_vq_affinity;
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
struct virtio_config_ops {
    void (*)(struct virtio_device *, unsigned int, void *, unsigned int) get;
    void (*)(struct virtio_device *, unsigned int, const void *, unsigned int) set;
    u32 (*)(struct virtio_device *) generation;
    u8 (*)(struct virtio_device *) get_status;
    void (*)(struct virtio_device *, u8) set_status;
    void (*)(struct virtio_device *) reset;
    int (*)(struct virtio_device *, unsigned int, struct virtqueue * *, vq_callback_t * *, const const char * *, const bool *, struct irq_affinity *) find_vqs;
    void (*)(struct virtio_device *) del_vqs;
    u64 (*)(struct virtio_device *) get_features;
    int (*)(struct virtio_device *) finalize_features;
    const char * (*)(struct virtio_device *) bus_name;
    int (*)(struct virtqueue *, const struct cpumask *) set_vq_affinity;
    const struct cpumask * (*)(struct virtio_device *, int) get_vq_affinity;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct virtio_config_ops {
    void (*)(struct virtio_device *, unsigned int, void *, unsigned int) get;
    void (*)(struct virtio_device *, unsigned int, const void *, unsigned int) set;
    u32 (*)(struct virtio_device *) generation;
    u8 (*)(struct virtio_device *) get_status;
    void (*)(struct virtio_device *, u8) set_status;
    void (*)(struct virtio_device *) reset;
    int (*)(struct virtio_device *, unsigned int, struct virtqueue * *, vq_callback_t * *, const const char * *, const bool *, struct irq_affinity *) find_vqs;
    void (*)(struct virtio_device *) del_vqs;
    u64 (*)(struct virtio_device *) get_features;
    int (*)(struct virtio_device *) finalize_features;
    const char * (*)(struct virtio_device *) bus_name;
    int (*)(struct virtqueue *, const struct cpumask *) set_vq_affinity;
    const struct cpumask * (*)(struct virtio_device *, int) get_vq_affinity;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct virtio_config_ops {
    void (*)(struct virtio_device *, unsigned int, void *, unsigned int) get;
    void (*)(struct virtio_device *, unsigned int, const void *, unsigned int) set;
    u32 (*)(struct virtio_device *) generation;
    u8 (*)(struct virtio_device *) get_status;
    void (*)(struct virtio_device *, u8) set_status;
    void (*)(struct virtio_device *) reset;
    int (*)(struct virtio_device *, unsigned int, struct virtqueue * *, vq_callback_t * *, const const char * *, const bool *, struct irq_affinity *) find_vqs;
    void (*)(struct virtio_device *) del_vqs;
    u64 (*)(struct virtio_device *) get_features;
    int (*)(struct virtio_device *) finalize_features;
    const char * (*)(struct virtio_device *) bus_name;
    int (*)(struct virtqueue *, const struct cpumask *) set_vq_affinity;
    const struct cpumask * (*)(struct virtio_device *, int) get_vq_affinity;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct virtio_config_ops {
    void (*)(struct virtio_device *, unsigned int, void *, unsigned int) get;
    void (*)(struct virtio_device *, unsigned int, const void *, unsigned int) set;
    u32 (*)(struct virtio_device *) generation;
    u8 (*)(struct virtio_device *) get_status;
    void (*)(struct virtio_device *, u8) set_status;
    void (*)(struct virtio_device *) reset;
    int (*)(struct virtio_device *, unsigned int, struct virtqueue * *, vq_callback_t * *, const const char * *, const bool *, struct irq_affinity *) find_vqs;
    void (*)(struct virtio_device *) del_vqs;
    u64 (*)(struct virtio_device *) get_features;
    int (*)(struct virtio_device *) finalize_features;
    const char * (*)(struct virtio_device *) bus_name;
    int (*)(struct virtqueue *, const struct cpumask *) set_vq_affinity;
    const struct cpumask * (*)(struct virtio_device *, int) get_vq_affinity;
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
<b>Field type changed. </b>
<code>int (*)(struct virtio_device *, unsigned int, struct virtqueue * *, vq_callback_t * *, const char * *) find_vqs</code> ➡️ <code>int (*)(struct virtio_device *, unsigned int, struct virtqueue * *, vq_callback_t * *, const const char * *) find_vqs</code>
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
<code>const struct cpumask * (*)(struct virtio_device *, int) get_vq_affinity</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct virtio_device *, unsigned int, struct virtqueue * *, vq_callback_t * *, const const char * *) find_vqs</code> ➡️ <code>int (*)(struct virtio_device *, unsigned int, struct virtqueue * *, vq_callback_t * *, const const char * *, const bool *, struct irq_affinity *) find_vqs</code>
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
<b>Field type changed. </b>
<code>int (*)(struct virtqueue *, int) set_vq_affinity</code> ➡️ <code>int (*)(struct virtqueue *, const struct cpumask *) set_vq_affinity</code>
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool (*)(struct virtio_device *, struct virtio_shm_region *, u8) get_shm_region</code>
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
<b>Field added. </b>
<code>void (*)(struct virtio_device *) synchronize_cbs</code>
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
<code>int (*)(struct virtqueue *) disable_vq_and_reset</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct virtqueue *) enable_vq_after_reset</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct virtio_device *) create_avq</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct virtio_device *) destroy_avq</code>
</li>
</ul>
</details>
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
