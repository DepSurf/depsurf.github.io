# Struct: <code>rtc_class_ops</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct rtc_class_ops {
    int (*)(struct device *) open;
    void (*)(struct device *) release;
    int (*)(struct device *, unsigned int, long unsigned int) ioctl;
    int (*)(struct device *, struct rtc_time *) read_time;
    int (*)(struct device *, struct rtc_time *) set_time;
    int (*)(struct device *, struct rtc_wkalrm *) read_alarm;
    int (*)(struct device *, struct rtc_wkalrm *) set_alarm;
    int (*)(struct device *, struct seq_file *) proc;
    int (*)(struct device *, time64_t) set_mmss64;
    int (*)(struct device *, long unsigned int) set_mmss;
    int (*)(struct device *, int) read_callback;
    int (*)(struct device *, unsigned int) alarm_irq_enable;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct rtc_class_ops {
    int (*)(struct device *) open;
    void (*)(struct device *) release;
    int (*)(struct device *, unsigned int, long unsigned int) ioctl;
    int (*)(struct device *, struct rtc_time *) read_time;
    int (*)(struct device *, struct rtc_time *) set_time;
    int (*)(struct device *, struct rtc_wkalrm *) read_alarm;
    int (*)(struct device *, struct rtc_wkalrm *) set_alarm;
    int (*)(struct device *, struct seq_file *) proc;
    int (*)(struct device *, time64_t) set_mmss64;
    int (*)(struct device *, long unsigned int) set_mmss;
    int (*)(struct device *, int) read_callback;
    int (*)(struct device *, unsigned int) alarm_irq_enable;
    int (*)(struct device *, long int *) read_offset;
    int (*)(struct device *, long int) set_offset;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct rtc_class_ops {
    int (*)(struct device *) open;
    void (*)(struct device *) release;
    int (*)(struct device *, unsigned int, long unsigned int) ioctl;
    int (*)(struct device *, struct rtc_time *) read_time;
    int (*)(struct device *, struct rtc_time *) set_time;
    int (*)(struct device *, struct rtc_wkalrm *) read_alarm;
    int (*)(struct device *, struct rtc_wkalrm *) set_alarm;
    int (*)(struct device *, struct seq_file *) proc;
    int (*)(struct device *, time64_t) set_mmss64;
    int (*)(struct device *, long unsigned int) set_mmss;
    int (*)(struct device *, int) read_callback;
    int (*)(struct device *, unsigned int) alarm_irq_enable;
    int (*)(struct device *, long int *) read_offset;
    int (*)(struct device *, long int) set_offset;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct rtc_class_ops {
    int (*)(struct device *) open;
    void (*)(struct device *) release;
    int (*)(struct device *, unsigned int, long unsigned int) ioctl;
    int (*)(struct device *, struct rtc_time *) read_time;
    int (*)(struct device *, struct rtc_time *) set_time;
    int (*)(struct device *, struct rtc_wkalrm *) read_alarm;
    int (*)(struct device *, struct rtc_wkalrm *) set_alarm;
    int (*)(struct device *, struct seq_file *) proc;
    int (*)(struct device *, time64_t) set_mmss64;
    int (*)(struct device *, long unsigned int) set_mmss;
    int (*)(struct device *, int) read_callback;
    int (*)(struct device *, unsigned int) alarm_irq_enable;
    int (*)(struct device *, long int *) read_offset;
    int (*)(struct device *, long int) set_offset;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct rtc_class_ops {
    int (*)(struct device *, unsigned int, long unsigned int) ioctl;
    int (*)(struct device *, struct rtc_time *) read_time;
    int (*)(struct device *, struct rtc_time *) set_time;
    int (*)(struct device *, struct rtc_wkalrm *) read_alarm;
    int (*)(struct device *, struct rtc_wkalrm *) set_alarm;
    int (*)(struct device *, struct seq_file *) proc;
    int (*)(struct device *, time64_t) set_mmss64;
    int (*)(struct device *, long unsigned int) set_mmss;
    int (*)(struct device *, int) read_callback;
    int (*)(struct device *, unsigned int) alarm_irq_enable;
    int (*)(struct device *, long int *) read_offset;
    int (*)(struct device *, long int) set_offset;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct rtc_class_ops {
    int (*)(struct device *, unsigned int, long unsigned int) ioctl;
    int (*)(struct device *, struct rtc_time *) read_time;
    int (*)(struct device *, struct rtc_time *) set_time;
    int (*)(struct device *, struct rtc_wkalrm *) read_alarm;
    int (*)(struct device *, struct rtc_wkalrm *) set_alarm;
    int (*)(struct device *, struct seq_file *) proc;
    int (*)(struct device *, time64_t) set_mmss64;
    int (*)(struct device *, long unsigned int) set_mmss;
    int (*)(struct device *, int) read_callback;
    int (*)(struct device *, unsigned int) alarm_irq_enable;
    int (*)(struct device *, long int *) read_offset;
    int (*)(struct device *, long int) set_offset;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct rtc_class_ops {
    int (*)(struct device *, unsigned int, long unsigned int) ioctl;
    int (*)(struct device *, struct rtc_time *) read_time;
    int (*)(struct device *, struct rtc_time *) set_time;
    int (*)(struct device *, struct rtc_wkalrm *) read_alarm;
    int (*)(struct device *, struct rtc_wkalrm *) set_alarm;
    int (*)(struct device *, struct seq_file *) proc;
    int (*)(struct device *, time64_t) set_mmss64;
    int (*)(struct device *, long unsigned int) set_mmss;
    int (*)(struct device *, int) read_callback;
    int (*)(struct device *, unsigned int) alarm_irq_enable;
    int (*)(struct device *, long int *) read_offset;
    int (*)(struct device *, long int) set_offset;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct rtc_class_ops {
    int (*)(struct device *, unsigned int, long unsigned int) ioctl;
    int (*)(struct device *, struct rtc_time *) read_time;
    int (*)(struct device *, struct rtc_time *) set_time;
    int (*)(struct device *, struct rtc_wkalrm *) read_alarm;
    int (*)(struct device *, struct rtc_wkalrm *) set_alarm;
    int (*)(struct device *, struct seq_file *) proc;
    int (*)(struct device *, unsigned int) alarm_irq_enable;
    int (*)(struct device *, long int *) read_offset;
    int (*)(struct device *, long int) set_offset;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct rtc_class_ops {
    int (*)(struct device *, unsigned int, long unsigned int) ioctl;
    int (*)(struct device *, struct rtc_time *) read_time;
    int (*)(struct device *, struct rtc_time *) set_time;
    int (*)(struct device *, struct rtc_wkalrm *) read_alarm;
    int (*)(struct device *, struct rtc_wkalrm *) set_alarm;
    int (*)(struct device *, struct seq_file *) proc;
    int (*)(struct device *, unsigned int) alarm_irq_enable;
    int (*)(struct device *, long int *) read_offset;
    int (*)(struct device *, long int) set_offset;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct rtc_class_ops {
    int (*)(struct device *, unsigned int, long unsigned int) ioctl;
    int (*)(struct device *, struct rtc_time *) read_time;
    int (*)(struct device *, struct rtc_time *) set_time;
    int (*)(struct device *, struct rtc_wkalrm *) read_alarm;
    int (*)(struct device *, struct rtc_wkalrm *) set_alarm;
    int (*)(struct device *, struct seq_file *) proc;
    int (*)(struct device *, unsigned int) alarm_irq_enable;
    int (*)(struct device *, long int *) read_offset;
    int (*)(struct device *, long int) set_offset;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct rtc_class_ops {
    int (*)(struct device *, unsigned int, long unsigned int) ioctl;
    int (*)(struct device *, struct rtc_time *) read_time;
    int (*)(struct device *, struct rtc_time *) set_time;
    int (*)(struct device *, struct rtc_wkalrm *) read_alarm;
    int (*)(struct device *, struct rtc_wkalrm *) set_alarm;
    int (*)(struct device *, struct seq_file *) proc;
    int (*)(struct device *, unsigned int) alarm_irq_enable;
    int (*)(struct device *, long int *) read_offset;
    int (*)(struct device *, long int) set_offset;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct rtc_class_ops {
    int (*)(struct device *, unsigned int, long unsigned int) ioctl;
    int (*)(struct device *, struct rtc_time *) read_time;
    int (*)(struct device *, struct rtc_time *) set_time;
    int (*)(struct device *, struct rtc_wkalrm *) read_alarm;
    int (*)(struct device *, struct rtc_wkalrm *) set_alarm;
    int (*)(struct device *, struct seq_file *) proc;
    int (*)(struct device *, unsigned int) alarm_irq_enable;
    int (*)(struct device *, long int *) read_offset;
    int (*)(struct device *, long int) set_offset;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct rtc_class_ops {
    int (*)(struct device *, unsigned int, long unsigned int) ioctl;
    int (*)(struct device *, struct rtc_time *) read_time;
    int (*)(struct device *, struct rtc_time *) set_time;
    int (*)(struct device *, struct rtc_wkalrm *) read_alarm;
    int (*)(struct device *, struct rtc_wkalrm *) set_alarm;
    int (*)(struct device *, struct seq_file *) proc;
    int (*)(struct device *, unsigned int) alarm_irq_enable;
    int (*)(struct device *, long int *) read_offset;
    int (*)(struct device *, long int) set_offset;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct rtc_class_ops {
    int (*)(struct device *, unsigned int, long unsigned int) ioctl;
    int (*)(struct device *, struct rtc_time *) read_time;
    int (*)(struct device *, struct rtc_time *) set_time;
    int (*)(struct device *, struct rtc_wkalrm *) read_alarm;
    int (*)(struct device *, struct rtc_wkalrm *) set_alarm;
    int (*)(struct device *, struct seq_file *) proc;
    int (*)(struct device *, unsigned int) alarm_irq_enable;
    int (*)(struct device *, long int *) read_offset;
    int (*)(struct device *, long int) set_offset;
    int (*)(struct device *, struct rtc_param *) param_get;
    int (*)(struct device *, struct rtc_param *) param_set;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct rtc_class_ops {
    int (*)(struct device *, unsigned int, long unsigned int) ioctl;
    int (*)(struct device *, struct rtc_time *) read_time;
    int (*)(struct device *, struct rtc_time *) set_time;
    int (*)(struct device *, struct rtc_wkalrm *) read_alarm;
    int (*)(struct device *, struct rtc_wkalrm *) set_alarm;
    int (*)(struct device *, struct seq_file *) proc;
    int (*)(struct device *, unsigned int) alarm_irq_enable;
    int (*)(struct device *, long int *) read_offset;
    int (*)(struct device *, long int) set_offset;
    int (*)(struct device *, struct rtc_param *) param_get;
    int (*)(struct device *, struct rtc_param *) param_set;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct rtc_class_ops {
    int (*)(struct device *, unsigned int, long unsigned int) ioctl;
    int (*)(struct device *, struct rtc_time *) read_time;
    int (*)(struct device *, struct rtc_time *) set_time;
    int (*)(struct device *, struct rtc_wkalrm *) read_alarm;
    int (*)(struct device *, struct rtc_wkalrm *) set_alarm;
    int (*)(struct device *, struct seq_file *) proc;
    int (*)(struct device *, unsigned int) alarm_irq_enable;
    int (*)(struct device *, long int *) read_offset;
    int (*)(struct device *, long int) set_offset;
    int (*)(struct device *, struct rtc_param *) param_get;
    int (*)(struct device *, struct rtc_param *) param_set;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct rtc_class_ops {
    int (*)(struct device *, unsigned int, long unsigned int) ioctl;
    int (*)(struct device *, struct rtc_time *) read_time;
    int (*)(struct device *, struct rtc_time *) set_time;
    int (*)(struct device *, struct rtc_wkalrm *) read_alarm;
    int (*)(struct device *, struct rtc_wkalrm *) set_alarm;
    int (*)(struct device *, struct seq_file *) proc;
    int (*)(struct device *, unsigned int) alarm_irq_enable;
    int (*)(struct device *, long int *) read_offset;
    int (*)(struct device *, long int) set_offset;
    int (*)(struct device *, struct rtc_param *) param_get;
    int (*)(struct device *, struct rtc_param *) param_set;
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
struct rtc_class_ops {
    int (*)(struct device *, unsigned int, long unsigned int) ioctl;
    int (*)(struct device *, struct rtc_time *) read_time;
    int (*)(struct device *, struct rtc_time *) set_time;
    int (*)(struct device *, struct rtc_wkalrm *) read_alarm;
    int (*)(struct device *, struct rtc_wkalrm *) set_alarm;
    int (*)(struct device *, struct seq_file *) proc;
    int (*)(struct device *, unsigned int) alarm_irq_enable;
    int (*)(struct device *, long int *) read_offset;
    int (*)(struct device *, long int) set_offset;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct rtc_class_ops {
    int (*)(struct device *, unsigned int, long unsigned int) ioctl;
    int (*)(struct device *, struct rtc_time *) read_time;
    int (*)(struct device *, struct rtc_time *) set_time;
    int (*)(struct device *, struct rtc_wkalrm *) read_alarm;
    int (*)(struct device *, struct rtc_wkalrm *) set_alarm;
    int (*)(struct device *, struct seq_file *) proc;
    int (*)(struct device *, unsigned int) alarm_irq_enable;
    int (*)(struct device *, long int *) read_offset;
    int (*)(struct device *, long int) set_offset;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct rtc_class_ops {
    int (*)(struct device *, unsigned int, long unsigned int) ioctl;
    int (*)(struct device *, struct rtc_time *) read_time;
    int (*)(struct device *, struct rtc_time *) set_time;
    int (*)(struct device *, struct rtc_wkalrm *) read_alarm;
    int (*)(struct device *, struct rtc_wkalrm *) set_alarm;
    int (*)(struct device *, struct seq_file *) proc;
    int (*)(struct device *, unsigned int) alarm_irq_enable;
    int (*)(struct device *, long int *) read_offset;
    int (*)(struct device *, long int) set_offset;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct rtc_class_ops {
    int (*)(struct device *, unsigned int, long unsigned int) ioctl;
    int (*)(struct device *, struct rtc_time *) read_time;
    int (*)(struct device *, struct rtc_time *) set_time;
    int (*)(struct device *, struct rtc_wkalrm *) read_alarm;
    int (*)(struct device *, struct rtc_wkalrm *) set_alarm;
    int (*)(struct device *, struct seq_file *) proc;
    int (*)(struct device *, unsigned int) alarm_irq_enable;
    int (*)(struct device *, long int *) read_offset;
    int (*)(struct device *, long int) set_offset;
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
struct rtc_class_ops {
    int (*)(struct device *, unsigned int, long unsigned int) ioctl;
    int (*)(struct device *, struct rtc_time *) read_time;
    int (*)(struct device *, struct rtc_time *) set_time;
    int (*)(struct device *, struct rtc_wkalrm *) read_alarm;
    int (*)(struct device *, struct rtc_wkalrm *) set_alarm;
    int (*)(struct device *, struct seq_file *) proc;
    int (*)(struct device *, unsigned int) alarm_irq_enable;
    int (*)(struct device *, long int *) read_offset;
    int (*)(struct device *, long int) set_offset;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct rtc_class_ops {
    int (*)(struct device *, unsigned int, long unsigned int) ioctl;
    int (*)(struct device *, struct rtc_time *) read_time;
    int (*)(struct device *, struct rtc_time *) set_time;
    int (*)(struct device *, struct rtc_wkalrm *) read_alarm;
    int (*)(struct device *, struct rtc_wkalrm *) set_alarm;
    int (*)(struct device *, struct seq_file *) proc;
    int (*)(struct device *, unsigned int) alarm_irq_enable;
    int (*)(struct device *, long int *) read_offset;
    int (*)(struct device *, long int) set_offset;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct rtc_class_ops {
    int (*)(struct device *, unsigned int, long unsigned int) ioctl;
    int (*)(struct device *, struct rtc_time *) read_time;
    int (*)(struct device *, struct rtc_time *) set_time;
    int (*)(struct device *, struct rtc_wkalrm *) read_alarm;
    int (*)(struct device *, struct rtc_wkalrm *) set_alarm;
    int (*)(struct device *, struct seq_file *) proc;
    int (*)(struct device *, unsigned int) alarm_irq_enable;
    int (*)(struct device *, long int *) read_offset;
    int (*)(struct device *, long int) set_offset;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct rtc_class_ops {
    int (*)(struct device *, unsigned int, long unsigned int) ioctl;
    int (*)(struct device *, struct rtc_time *) read_time;
    int (*)(struct device *, struct rtc_time *) set_time;
    int (*)(struct device *, struct rtc_wkalrm *) read_alarm;
    int (*)(struct device *, struct rtc_wkalrm *) set_alarm;
    int (*)(struct device *, struct seq_file *) proc;
    int (*)(struct device *, unsigned int) alarm_irq_enable;
    int (*)(struct device *, long int *) read_offset;
    int (*)(struct device *, long int) set_offset;
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
<code>int (*)(struct device *, long int *) read_offset</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct device *, long int) set_offset</code>
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
<b>Field removed. </b>
<code>int (*)(struct device *) open</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct device *) release</code>
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
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>int (*)(struct device *, time64_t) set_mmss64</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct device *, long unsigned int) set_mmss</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct device *, int) read_callback</code>
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
<code>int (*)(struct device *, struct rtc_param *) param_get</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct device *, struct rtc_param *) param_set</code>
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
