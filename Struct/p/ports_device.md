# Struct: <code>ports_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct ports_device {
    struct list_head list;
    struct work_struct control_work;
    struct work_struct config_work;
    struct list_head ports;
    spinlock_t ports_lock;
    spinlock_t c_ivq_lock;
    spinlock_t c_ovq_lock;
    struct virtio_console_config config;
    struct virtio_device * vdev;
    struct virtqueue * c_ivq;
    struct virtqueue * c_ovq;
    struct virtqueue * * in_vqs;
    struct virtqueue * * out_vqs;
    int chr_major;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct ports_device {
    struct list_head list;
    struct work_struct control_work;
    struct work_struct config_work;
    struct list_head ports;
    spinlock_t ports_lock;
    spinlock_t c_ivq_lock;
    spinlock_t c_ovq_lock;
    struct virtio_console_config config;
    struct virtio_device * vdev;
    struct virtqueue * c_ivq;
    struct virtqueue * c_ovq;
    struct virtio_console_control cpkt;
    struct virtqueue * * in_vqs;
    struct virtqueue * * out_vqs;
    int chr_major;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct ports_device {
    struct list_head list;
    struct work_struct control_work;
    struct work_struct config_work;
    struct list_head ports;
    spinlock_t ports_lock;
    spinlock_t c_ivq_lock;
    spinlock_t c_ovq_lock;
    u32 max_nr_ports;
    struct virtio_device * vdev;
    struct virtqueue * c_ivq;
    struct virtqueue * c_ovq;
    struct virtio_console_control cpkt;
    struct virtqueue * * in_vqs;
    struct virtqueue * * out_vqs;
    int chr_major;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct ports_device {
    struct list_head list;
    struct work_struct control_work;
    struct work_struct config_work;
    struct list_head ports;
    spinlock_t ports_lock;
    spinlock_t c_ivq_lock;
    spinlock_t c_ovq_lock;
    u32 max_nr_ports;
    struct virtio_device * vdev;
    struct virtqueue * c_ivq;
    struct virtqueue * c_ovq;
    struct virtio_console_control cpkt;
    struct virtqueue * * in_vqs;
    struct virtqueue * * out_vqs;
    int chr_major;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct ports_device {
    struct list_head list;
    struct work_struct control_work;
    struct work_struct config_work;
    struct list_head ports;
    spinlock_t ports_lock;
    spinlock_t c_ivq_lock;
    spinlock_t c_ovq_lock;
    u32 max_nr_ports;
    struct virtio_device * vdev;
    struct virtqueue * c_ivq;
    struct virtqueue * c_ovq;
    struct virtio_console_control cpkt;
    struct virtqueue * * in_vqs;
    struct virtqueue * * out_vqs;
    int chr_major;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct ports_device {
    struct list_head list;
    struct work_struct control_work;
    struct work_struct config_work;
    struct list_head ports;
    spinlock_t ports_lock;
    spinlock_t c_ivq_lock;
    spinlock_t c_ovq_lock;
    u32 max_nr_ports;
    struct virtio_device * vdev;
    struct virtqueue * c_ivq;
    struct virtqueue * c_ovq;
    struct virtio_console_control cpkt;
    struct virtqueue * * in_vqs;
    struct virtqueue * * out_vqs;
    int chr_major;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct ports_device {
    struct list_head list;
    struct work_struct control_work;
    struct work_struct config_work;
    struct list_head ports;
    spinlock_t ports_lock;
    spinlock_t c_ivq_lock;
    spinlock_t c_ovq_lock;
    u32 max_nr_ports;
    struct virtio_device * vdev;
    struct virtqueue * c_ivq;
    struct virtqueue * c_ovq;
    struct virtio_console_control cpkt;
    struct virtqueue * * in_vqs;
    struct virtqueue * * out_vqs;
    int chr_major;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct ports_device {
    struct list_head list;
    struct work_struct control_work;
    struct work_struct config_work;
    struct list_head ports;
    spinlock_t ports_lock;
    spinlock_t c_ivq_lock;
    spinlock_t c_ovq_lock;
    u32 max_nr_ports;
    struct virtio_device * vdev;
    struct virtqueue * c_ivq;
    struct virtqueue * c_ovq;
    struct virtio_console_control cpkt;
    struct virtqueue * * in_vqs;
    struct virtqueue * * out_vqs;
    int chr_major;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct ports_device {
    struct list_head list;
    struct work_struct control_work;
    struct work_struct config_work;
    struct list_head ports;
    spinlock_t ports_lock;
    spinlock_t c_ivq_lock;
    spinlock_t c_ovq_lock;
    u32 max_nr_ports;
    struct virtio_device * vdev;
    struct virtqueue * c_ivq;
    struct virtqueue * c_ovq;
    struct virtio_console_control cpkt;
    struct virtqueue * * in_vqs;
    struct virtqueue * * out_vqs;
    int chr_major;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct ports_device {
    struct list_head list;
    struct work_struct control_work;
    struct work_struct config_work;
    struct list_head ports;
    spinlock_t ports_lock;
    spinlock_t c_ivq_lock;
    spinlock_t c_ovq_lock;
    u32 max_nr_ports;
    struct virtio_device * vdev;
    struct virtqueue * c_ivq;
    struct virtqueue * c_ovq;
    struct virtio_console_control cpkt;
    struct virtqueue * * in_vqs;
    struct virtqueue * * out_vqs;
    int chr_major;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct ports_device {
    struct list_head list;
    struct work_struct control_work;
    struct work_struct config_work;
    struct list_head ports;
    spinlock_t ports_lock;
    spinlock_t c_ivq_lock;
    spinlock_t c_ovq_lock;
    u32 max_nr_ports;
    struct virtio_device * vdev;
    struct virtqueue * c_ivq;
    struct virtqueue * c_ovq;
    struct virtio_console_control cpkt;
    struct virtqueue * * in_vqs;
    struct virtqueue * * out_vqs;
    int chr_major;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct ports_device {
    struct list_head list;
    struct work_struct control_work;
    struct work_struct config_work;
    struct list_head ports;
    spinlock_t ports_lock;
    spinlock_t c_ivq_lock;
    spinlock_t c_ovq_lock;
    u32 max_nr_ports;
    struct virtio_device * vdev;
    struct virtqueue * c_ivq;
    struct virtqueue * c_ovq;
    struct virtio_console_control cpkt;
    struct virtqueue * * in_vqs;
    struct virtqueue * * out_vqs;
    int chr_major;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct ports_device {
    struct list_head list;
    struct work_struct control_work;
    struct work_struct config_work;
    struct list_head ports;
    spinlock_t ports_lock;
    spinlock_t c_ivq_lock;
    spinlock_t c_ovq_lock;
    u32 max_nr_ports;
    struct virtio_device * vdev;
    struct virtqueue * c_ivq;
    struct virtqueue * c_ovq;
    struct virtio_console_control cpkt;
    struct virtqueue * * in_vqs;
    struct virtqueue * * out_vqs;
    int chr_major;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct ports_device {
    struct list_head list;
    struct work_struct control_work;
    struct work_struct config_work;
    struct list_head ports;
    spinlock_t ports_lock;
    spinlock_t c_ivq_lock;
    spinlock_t c_ovq_lock;
    u32 max_nr_ports;
    struct virtio_device * vdev;
    struct virtqueue * c_ivq;
    struct virtqueue * c_ovq;
    struct virtio_console_control cpkt;
    struct virtqueue * * in_vqs;
    struct virtqueue * * out_vqs;
    int chr_major;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct ports_device {
    struct list_head list;
    struct work_struct control_work;
    struct work_struct config_work;
    struct list_head ports;
    spinlock_t ports_lock;
    spinlock_t c_ivq_lock;
    spinlock_t c_ovq_lock;
    u32 max_nr_ports;
    struct virtio_device * vdev;
    struct virtqueue * c_ivq;
    struct virtqueue * c_ovq;
    struct virtio_console_control cpkt;
    struct virtqueue * * in_vqs;
    struct virtqueue * * out_vqs;
    int chr_major;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct ports_device {
    struct list_head list;
    struct work_struct control_work;
    struct work_struct config_work;
    struct list_head ports;
    spinlock_t ports_lock;
    spinlock_t c_ivq_lock;
    spinlock_t c_ovq_lock;
    u32 max_nr_ports;
    struct virtio_device * vdev;
    struct virtqueue * c_ivq;
    struct virtqueue * c_ovq;
    struct virtio_console_control cpkt;
    struct virtqueue * * in_vqs;
    struct virtqueue * * out_vqs;
    int chr_major;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct ports_device {
    struct list_head list;
    struct work_struct control_work;
    struct work_struct config_work;
    struct list_head ports;
    spinlock_t ports_lock;
    spinlock_t c_ivq_lock;
    spinlock_t c_ovq_lock;
    u32 max_nr_ports;
    struct virtio_device * vdev;
    struct virtqueue * c_ivq;
    struct virtqueue * c_ovq;
    struct virtio_console_control cpkt;
    struct virtqueue * * in_vqs;
    struct virtqueue * * out_vqs;
    int chr_major;
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
struct ports_device {
    struct list_head list;
    struct work_struct control_work;
    struct work_struct config_work;
    struct list_head ports;
    spinlock_t ports_lock;
    spinlock_t c_ivq_lock;
    spinlock_t c_ovq_lock;
    u32 max_nr_ports;
    struct virtio_device * vdev;
    struct virtqueue * c_ivq;
    struct virtqueue * c_ovq;
    struct virtio_console_control cpkt;
    struct virtqueue * * in_vqs;
    struct virtqueue * * out_vqs;
    int chr_major;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct ports_device {
    struct list_head list;
    struct work_struct control_work;
    struct work_struct config_work;
    struct list_head ports;
    spinlock_t ports_lock;
    spinlock_t c_ivq_lock;
    spinlock_t c_ovq_lock;
    u32 max_nr_ports;
    struct virtio_device * vdev;
    struct virtqueue * c_ivq;
    struct virtqueue * c_ovq;
    struct virtio_console_control cpkt;
    struct virtqueue * * in_vqs;
    struct virtqueue * * out_vqs;
    int chr_major;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct ports_device {
    struct list_head list;
    struct work_struct control_work;
    struct work_struct config_work;
    struct list_head ports;
    spinlock_t ports_lock;
    spinlock_t c_ivq_lock;
    spinlock_t c_ovq_lock;
    u32 max_nr_ports;
    struct virtio_device * vdev;
    struct virtqueue * c_ivq;
    struct virtqueue * c_ovq;
    struct virtio_console_control cpkt;
    struct virtqueue * * in_vqs;
    struct virtqueue * * out_vqs;
    int chr_major;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct ports_device {
    struct list_head list;
    struct work_struct control_work;
    struct work_struct config_work;
    struct list_head ports;
    spinlock_t ports_lock;
    spinlock_t c_ivq_lock;
    spinlock_t c_ovq_lock;
    u32 max_nr_ports;
    struct virtio_device * vdev;
    struct virtqueue * c_ivq;
    struct virtqueue * c_ovq;
    struct virtio_console_control cpkt;
    struct virtqueue * * in_vqs;
    struct virtqueue * * out_vqs;
    int chr_major;
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
struct ports_device {
    struct list_head list;
    struct work_struct control_work;
    struct work_struct config_work;
    struct list_head ports;
    spinlock_t ports_lock;
    spinlock_t c_ivq_lock;
    spinlock_t c_ovq_lock;
    u32 max_nr_ports;
    struct virtio_device * vdev;
    struct virtqueue * c_ivq;
    struct virtqueue * c_ovq;
    struct virtio_console_control cpkt;
    struct virtqueue * * in_vqs;
    struct virtqueue * * out_vqs;
    int chr_major;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct ports_device {
    struct list_head list;
    struct work_struct control_work;
    struct work_struct config_work;
    struct list_head ports;
    spinlock_t ports_lock;
    spinlock_t c_ivq_lock;
    spinlock_t c_ovq_lock;
    u32 max_nr_ports;
    struct virtio_device * vdev;
    struct virtqueue * c_ivq;
    struct virtqueue * c_ovq;
    struct virtio_console_control cpkt;
    struct virtqueue * * in_vqs;
    struct virtqueue * * out_vqs;
    int chr_major;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct ports_device {
    struct list_head list;
    struct work_struct control_work;
    struct work_struct config_work;
    struct list_head ports;
    spinlock_t ports_lock;
    spinlock_t c_ivq_lock;
    spinlock_t c_ovq_lock;
    u32 max_nr_ports;
    struct virtio_device * vdev;
    struct virtqueue * c_ivq;
    struct virtqueue * c_ovq;
    struct virtio_console_control cpkt;
    struct virtqueue * * in_vqs;
    struct virtqueue * * out_vqs;
    int chr_major;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct ports_device {
    struct list_head list;
    struct work_struct control_work;
    struct work_struct config_work;
    struct list_head ports;
    spinlock_t ports_lock;
    spinlock_t c_ivq_lock;
    spinlock_t c_ovq_lock;
    u32 max_nr_ports;
    struct virtio_device * vdev;
    struct virtqueue * c_ivq;
    struct virtqueue * c_ovq;
    struct virtio_console_control cpkt;
    struct virtqueue * * in_vqs;
    struct virtqueue * * out_vqs;
    int chr_major;
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
<code>struct virtio_console_control cpkt</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u32 max_nr_ports</code>
</li>
<li>
<b>Field removed. </b>
<code>struct virtio_console_config config</code>
</li>
</ul>
</details>
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
