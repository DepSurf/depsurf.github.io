# Struct: <code>pwm_ops</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct pwm_ops {
    int (*)(struct pwm_chip *, struct pwm_device *) request;
    void (*)(struct pwm_chip *, struct pwm_device *) free;
    int (*)(struct pwm_chip *, struct pwm_device *, int, int) config;
    int (*)(struct pwm_chip *, struct pwm_device *, enum pwm_polarity) set_polarity;
    int (*)(struct pwm_chip *, struct pwm_device *) enable;
    void (*)(struct pwm_chip *, struct pwm_device *) disable;
    void (*)(struct pwm_chip *, struct seq_file *) dbg_show;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct pwm_ops {
    int (*)(struct pwm_chip *, struct pwm_device *) request;
    void (*)(struct pwm_chip *, struct pwm_device *) free;
    int (*)(struct pwm_chip *, struct pwm_device *, int, int) config;
    int (*)(struct pwm_chip *, struct pwm_device *, enum pwm_polarity) set_polarity;
    int (*)(struct pwm_chip *, struct pwm_device *, struct pwm_capture *, long unsigned int) capture;
    int (*)(struct pwm_chip *, struct pwm_device *) enable;
    void (*)(struct pwm_chip *, struct pwm_device *) disable;
    int (*)(struct pwm_chip *, struct pwm_device *, struct pwm_state *) apply;
    void (*)(struct pwm_chip *, struct pwm_device *, struct pwm_state *) get_state;
    void (*)(struct pwm_chip *, struct seq_file *) dbg_show;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct pwm_ops {
    int (*)(struct pwm_chip *, struct pwm_device *) request;
    void (*)(struct pwm_chip *, struct pwm_device *) free;
    int (*)(struct pwm_chip *, struct pwm_device *, int, int) config;
    int (*)(struct pwm_chip *, struct pwm_device *, enum pwm_polarity) set_polarity;
    int (*)(struct pwm_chip *, struct pwm_device *, struct pwm_capture *, long unsigned int) capture;
    int (*)(struct pwm_chip *, struct pwm_device *) enable;
    void (*)(struct pwm_chip *, struct pwm_device *) disable;
    int (*)(struct pwm_chip *, struct pwm_device *, struct pwm_state *) apply;
    void (*)(struct pwm_chip *, struct pwm_device *, struct pwm_state *) get_state;
    void (*)(struct pwm_chip *, struct seq_file *) dbg_show;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct pwm_ops {
    int (*)(struct pwm_chip *, struct pwm_device *) request;
    void (*)(struct pwm_chip *, struct pwm_device *) free;
    int (*)(struct pwm_chip *, struct pwm_device *, int, int) config;
    int (*)(struct pwm_chip *, struct pwm_device *, enum pwm_polarity) set_polarity;
    int (*)(struct pwm_chip *, struct pwm_device *, struct pwm_capture *, long unsigned int) capture;
    int (*)(struct pwm_chip *, struct pwm_device *) enable;
    void (*)(struct pwm_chip *, struct pwm_device *) disable;
    int (*)(struct pwm_chip *, struct pwm_device *, struct pwm_state *) apply;
    void (*)(struct pwm_chip *, struct pwm_device *, struct pwm_state *) get_state;
    void (*)(struct pwm_chip *, struct seq_file *) dbg_show;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct pwm_ops {
    int (*)(struct pwm_chip *, struct pwm_device *) request;
    void (*)(struct pwm_chip *, struct pwm_device *) free;
    int (*)(struct pwm_chip *, struct pwm_device *, int, int) config;
    int (*)(struct pwm_chip *, struct pwm_device *, enum pwm_polarity) set_polarity;
    int (*)(struct pwm_chip *, struct pwm_device *, struct pwm_capture *, long unsigned int) capture;
    int (*)(struct pwm_chip *, struct pwm_device *) enable;
    void (*)(struct pwm_chip *, struct pwm_device *) disable;
    int (*)(struct pwm_chip *, struct pwm_device *, struct pwm_state *) apply;
    void (*)(struct pwm_chip *, struct pwm_device *, struct pwm_state *) get_state;
    void (*)(struct pwm_chip *, struct seq_file *) dbg_show;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct pwm_ops {
    int (*)(struct pwm_chip *, struct pwm_device *) request;
    void (*)(struct pwm_chip *, struct pwm_device *) free;
    int (*)(struct pwm_chip *, struct pwm_device *, int, int) config;
    int (*)(struct pwm_chip *, struct pwm_device *, enum pwm_polarity) set_polarity;
    int (*)(struct pwm_chip *, struct pwm_device *, struct pwm_capture *, long unsigned int) capture;
    int (*)(struct pwm_chip *, struct pwm_device *) enable;
    void (*)(struct pwm_chip *, struct pwm_device *) disable;
    int (*)(struct pwm_chip *, struct pwm_device *, struct pwm_state *) apply;
    void (*)(struct pwm_chip *, struct pwm_device *, struct pwm_state *) get_state;
    void (*)(struct pwm_chip *, struct seq_file *) dbg_show;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct pwm_ops {
    int (*)(struct pwm_chip *, struct pwm_device *) request;
    void (*)(struct pwm_chip *, struct pwm_device *) free;
    int (*)(struct pwm_chip *, struct pwm_device *, int, int) config;
    int (*)(struct pwm_chip *, struct pwm_device *, enum pwm_polarity) set_polarity;
    int (*)(struct pwm_chip *, struct pwm_device *, struct pwm_capture *, long unsigned int) capture;
    int (*)(struct pwm_chip *, struct pwm_device *) enable;
    void (*)(struct pwm_chip *, struct pwm_device *) disable;
    int (*)(struct pwm_chip *, struct pwm_device *, struct pwm_state *) apply;
    void (*)(struct pwm_chip *, struct pwm_device *, struct pwm_state *) get_state;
    void (*)(struct pwm_chip *, struct seq_file *) dbg_show;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct pwm_ops {
    int (*)(struct pwm_chip *, struct pwm_device *) request;
    void (*)(struct pwm_chip *, struct pwm_device *) free;
    int (*)(struct pwm_chip *, struct pwm_device *, struct pwm_capture *, long unsigned int) capture;
    int (*)(struct pwm_chip *, struct pwm_device *, struct pwm_state *) apply;
    void (*)(struct pwm_chip *, struct pwm_device *, struct pwm_state *) get_state;
    struct module * owner;
    int (*)(struct pwm_chip *, struct pwm_device *, int, int) config;
    int (*)(struct pwm_chip *, struct pwm_device *, enum pwm_polarity) set_polarity;
    int (*)(struct pwm_chip *, struct pwm_device *) enable;
    void (*)(struct pwm_chip *, struct pwm_device *) disable;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct pwm_ops {
    int (*)(struct pwm_chip *, struct pwm_device *) request;
    void (*)(struct pwm_chip *, struct pwm_device *) free;
    int (*)(struct pwm_chip *, struct pwm_device *, struct pwm_capture *, long unsigned int) capture;
    int (*)(struct pwm_chip *, struct pwm_device *, const struct pwm_state *) apply;
    void (*)(struct pwm_chip *, struct pwm_device *, struct pwm_state *) get_state;
    struct module * owner;
    int (*)(struct pwm_chip *, struct pwm_device *, int, int) config;
    int (*)(struct pwm_chip *, struct pwm_device *, enum pwm_polarity) set_polarity;
    int (*)(struct pwm_chip *, struct pwm_device *) enable;
    void (*)(struct pwm_chip *, struct pwm_device *) disable;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct pwm_ops {
    int (*)(struct pwm_chip *, struct pwm_device *) request;
    void (*)(struct pwm_chip *, struct pwm_device *) free;
    int (*)(struct pwm_chip *, struct pwm_device *, struct pwm_capture *, long unsigned int) capture;
    int (*)(struct pwm_chip *, struct pwm_device *, const struct pwm_state *) apply;
    void (*)(struct pwm_chip *, struct pwm_device *, struct pwm_state *) get_state;
    struct module * owner;
    int (*)(struct pwm_chip *, struct pwm_device *, int, int) config;
    int (*)(struct pwm_chip *, struct pwm_device *, enum pwm_polarity) set_polarity;
    int (*)(struct pwm_chip *, struct pwm_device *) enable;
    void (*)(struct pwm_chip *, struct pwm_device *) disable;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct pwm_ops {
    int (*)(struct pwm_chip *, struct pwm_device *) request;
    void (*)(struct pwm_chip *, struct pwm_device *) free;
    int (*)(struct pwm_chip *, struct pwm_device *, struct pwm_capture *, long unsigned int) capture;
    int (*)(struct pwm_chip *, struct pwm_device *, const struct pwm_state *) apply;
    void (*)(struct pwm_chip *, struct pwm_device *, struct pwm_state *) get_state;
    struct module * owner;
    int (*)(struct pwm_chip *, struct pwm_device *, int, int) config;
    int (*)(struct pwm_chip *, struct pwm_device *, enum pwm_polarity) set_polarity;
    int (*)(struct pwm_chip *, struct pwm_device *) enable;
    void (*)(struct pwm_chip *, struct pwm_device *) disable;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct pwm_ops {
    int (*)(struct pwm_chip *, struct pwm_device *) request;
    void (*)(struct pwm_chip *, struct pwm_device *) free;
    int (*)(struct pwm_chip *, struct pwm_device *, struct pwm_capture *, long unsigned int) capture;
    int (*)(struct pwm_chip *, struct pwm_device *, const struct pwm_state *) apply;
    void (*)(struct pwm_chip *, struct pwm_device *, struct pwm_state *) get_state;
    struct module * owner;
    int (*)(struct pwm_chip *, struct pwm_device *, int, int) config;
    int (*)(struct pwm_chip *, struct pwm_device *, enum pwm_polarity) set_polarity;
    int (*)(struct pwm_chip *, struct pwm_device *) enable;
    void (*)(struct pwm_chip *, struct pwm_device *) disable;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct pwm_ops {
    int (*)(struct pwm_chip *, struct pwm_device *) request;
    void (*)(struct pwm_chip *, struct pwm_device *) free;
    int (*)(struct pwm_chip *, struct pwm_device *, struct pwm_capture *, long unsigned int) capture;
    int (*)(struct pwm_chip *, struct pwm_device *, const struct pwm_state *) apply;
    void (*)(struct pwm_chip *, struct pwm_device *, struct pwm_state *) get_state;
    struct module * owner;
    int (*)(struct pwm_chip *, struct pwm_device *, int, int) config;
    int (*)(struct pwm_chip *, struct pwm_device *, enum pwm_polarity) set_polarity;
    int (*)(struct pwm_chip *, struct pwm_device *) enable;
    void (*)(struct pwm_chip *, struct pwm_device *) disable;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct pwm_ops {
    int (*)(struct pwm_chip *, struct pwm_device *) request;
    void (*)(struct pwm_chip *, struct pwm_device *) free;
    int (*)(struct pwm_chip *, struct pwm_device *, struct pwm_capture *, long unsigned int) capture;
    int (*)(struct pwm_chip *, struct pwm_device *, const struct pwm_state *) apply;
    void (*)(struct pwm_chip *, struct pwm_device *, struct pwm_state *) get_state;
    struct module * owner;
    int (*)(struct pwm_chip *, struct pwm_device *, int, int) config;
    int (*)(struct pwm_chip *, struct pwm_device *, enum pwm_polarity) set_polarity;
    int (*)(struct pwm_chip *, struct pwm_device *) enable;
    void (*)(struct pwm_chip *, struct pwm_device *) disable;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct pwm_ops {
    int (*)(struct pwm_chip *, struct pwm_device *) request;
    void (*)(struct pwm_chip *, struct pwm_device *) free;
    int (*)(struct pwm_chip *, struct pwm_device *, struct pwm_capture *, long unsigned int) capture;
    int (*)(struct pwm_chip *, struct pwm_device *, const struct pwm_state *) apply;
    int (*)(struct pwm_chip *, struct pwm_device *, struct pwm_state *) get_state;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct pwm_ops {
    int (*)(struct pwm_chip *, struct pwm_device *) request;
    void (*)(struct pwm_chip *, struct pwm_device *) free;
    int (*)(struct pwm_chip *, struct pwm_device *, struct pwm_capture *, long unsigned int) capture;
    int (*)(struct pwm_chip *, struct pwm_device *, const struct pwm_state *) apply;
    int (*)(struct pwm_chip *, struct pwm_device *, struct pwm_state *) get_state;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct pwm_ops {
    int (*)(struct pwm_chip *, struct pwm_device *) request;
    void (*)(struct pwm_chip *, struct pwm_device *) free;
    int (*)(struct pwm_chip *, struct pwm_device *, struct pwm_capture *, long unsigned int) capture;
    int (*)(struct pwm_chip *, struct pwm_device *, const struct pwm_state *) apply;
    int (*)(struct pwm_chip *, struct pwm_device *, struct pwm_state *) get_state;
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
struct pwm_ops {
    int (*)(struct pwm_chip *, struct pwm_device *) request;
    void (*)(struct pwm_chip *, struct pwm_device *) free;
    int (*)(struct pwm_chip *, struct pwm_device *, struct pwm_capture *, long unsigned int) capture;
    int (*)(struct pwm_chip *, struct pwm_device *, const struct pwm_state *) apply;
    void (*)(struct pwm_chip *, struct pwm_device *, struct pwm_state *) get_state;
    struct module * owner;
    int (*)(struct pwm_chip *, struct pwm_device *, int, int) config;
    int (*)(struct pwm_chip *, struct pwm_device *, enum pwm_polarity) set_polarity;
    int (*)(struct pwm_chip *, struct pwm_device *) enable;
    void (*)(struct pwm_chip *, struct pwm_device *) disable;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct pwm_ops {
    int (*)(struct pwm_chip *, struct pwm_device *) request;
    void (*)(struct pwm_chip *, struct pwm_device *) free;
    int (*)(struct pwm_chip *, struct pwm_device *, struct pwm_capture *, long unsigned int) capture;
    int (*)(struct pwm_chip *, struct pwm_device *, const struct pwm_state *) apply;
    void (*)(struct pwm_chip *, struct pwm_device *, struct pwm_state *) get_state;
    struct module * owner;
    int (*)(struct pwm_chip *, struct pwm_device *, int, int) config;
    int (*)(struct pwm_chip *, struct pwm_device *, enum pwm_polarity) set_polarity;
    int (*)(struct pwm_chip *, struct pwm_device *) enable;
    void (*)(struct pwm_chip *, struct pwm_device *) disable;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct pwm_ops {
    int (*)(struct pwm_chip *, struct pwm_device *) request;
    void (*)(struct pwm_chip *, struct pwm_device *) free;
    int (*)(struct pwm_chip *, struct pwm_device *, struct pwm_capture *, long unsigned int) capture;
    int (*)(struct pwm_chip *, struct pwm_device *, const struct pwm_state *) apply;
    void (*)(struct pwm_chip *, struct pwm_device *, struct pwm_state *) get_state;
    struct module * owner;
    int (*)(struct pwm_chip *, struct pwm_device *, int, int) config;
    int (*)(struct pwm_chip *, struct pwm_device *, enum pwm_polarity) set_polarity;
    int (*)(struct pwm_chip *, struct pwm_device *) enable;
    void (*)(struct pwm_chip *, struct pwm_device *) disable;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct pwm_ops {
    int (*)(struct pwm_chip *, struct pwm_device *) request;
    void (*)(struct pwm_chip *, struct pwm_device *) free;
    int (*)(struct pwm_chip *, struct pwm_device *, struct pwm_capture *, long unsigned int) capture;
    int (*)(struct pwm_chip *, struct pwm_device *, const struct pwm_state *) apply;
    void (*)(struct pwm_chip *, struct pwm_device *, struct pwm_state *) get_state;
    struct module * owner;
    int (*)(struct pwm_chip *, struct pwm_device *, int, int) config;
    int (*)(struct pwm_chip *, struct pwm_device *, enum pwm_polarity) set_polarity;
    int (*)(struct pwm_chip *, struct pwm_device *) enable;
    void (*)(struct pwm_chip *, struct pwm_device *) disable;
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
struct pwm_ops {
    int (*)(struct pwm_chip *, struct pwm_device *) request;
    void (*)(struct pwm_chip *, struct pwm_device *) free;
    int (*)(struct pwm_chip *, struct pwm_device *, struct pwm_capture *, long unsigned int) capture;
    int (*)(struct pwm_chip *, struct pwm_device *, const struct pwm_state *) apply;
    void (*)(struct pwm_chip *, struct pwm_device *, struct pwm_state *) get_state;
    struct module * owner;
    int (*)(struct pwm_chip *, struct pwm_device *, int, int) config;
    int (*)(struct pwm_chip *, struct pwm_device *, enum pwm_polarity) set_polarity;
    int (*)(struct pwm_chip *, struct pwm_device *) enable;
    void (*)(struct pwm_chip *, struct pwm_device *) disable;
}
```
</details>
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct pwm_ops {
    int (*)(struct pwm_chip *, struct pwm_device *) request;
    void (*)(struct pwm_chip *, struct pwm_device *) free;
    int (*)(struct pwm_chip *, struct pwm_device *, struct pwm_capture *, long unsigned int) capture;
    int (*)(struct pwm_chip *, struct pwm_device *, const struct pwm_state *) apply;
    void (*)(struct pwm_chip *, struct pwm_device *, struct pwm_state *) get_state;
    struct module * owner;
    int (*)(struct pwm_chip *, struct pwm_device *, int, int) config;
    int (*)(struct pwm_chip *, struct pwm_device *, enum pwm_polarity) set_polarity;
    int (*)(struct pwm_chip *, struct pwm_device *) enable;
    void (*)(struct pwm_chip *, struct pwm_device *) disable;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct pwm_ops {
    int (*)(struct pwm_chip *, struct pwm_device *) request;
    void (*)(struct pwm_chip *, struct pwm_device *) free;
    int (*)(struct pwm_chip *, struct pwm_device *, struct pwm_capture *, long unsigned int) capture;
    int (*)(struct pwm_chip *, struct pwm_device *, const struct pwm_state *) apply;
    void (*)(struct pwm_chip *, struct pwm_device *, struct pwm_state *) get_state;
    struct module * owner;
    int (*)(struct pwm_chip *, struct pwm_device *, int, int) config;
    int (*)(struct pwm_chip *, struct pwm_device *, enum pwm_polarity) set_polarity;
    int (*)(struct pwm_chip *, struct pwm_device *) enable;
    void (*)(struct pwm_chip *, struct pwm_device *) disable;
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
<code>int (*)(struct pwm_chip *, struct pwm_device *, struct pwm_capture *, long unsigned int) capture</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct pwm_chip *, struct pwm_device *, struct pwm_state *) apply</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct pwm_chip *, struct pwm_device *, struct pwm_state *) get_state</code>
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
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>void (*)(struct pwm_chip *, struct seq_file *) dbg_show</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>int (*)(struct pwm_chip *, struct pwm_device *, struct pwm_state *) apply</code> ➡️ <code>int (*)(struct pwm_chip *, struct pwm_device *, const struct pwm_state *) apply</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>int (*)(struct pwm_chip *, struct pwm_device *, int, int) config</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct pwm_chip *, struct pwm_device *, enum pwm_polarity) set_polarity</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct pwm_chip *, struct pwm_device *) enable</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct pwm_chip *, struct pwm_device *) disable</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct pwm_chip *, struct pwm_device *, struct pwm_state *) get_state</code> ➡️ <code>int (*)(struct pwm_chip *, struct pwm_device *, struct pwm_state *) get_state</code>
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
<b>Field removed. </b>
<code>struct module * owner</code>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
struct pwm_ops {
    int (*)(struct pwm_chip *, struct pwm_device *) request;
    void (*)(struct pwm_chip *, struct pwm_device *) free;
    int (*)(struct pwm_chip *, struct pwm_device *, struct pwm_capture *, long unsigned int) capture;
    int (*)(struct pwm_chip *, struct pwm_device *, const struct pwm_state *) apply;
    void (*)(struct pwm_chip *, struct pwm_device *, struct pwm_state *) get_state;
    struct module * owner;
    int (*)(struct pwm_chip *, struct pwm_device *, int, int) config;
    int (*)(struct pwm_chip *, struct pwm_device *, enum pwm_polarity) set_polarity;
    int (*)(struct pwm_chip *, struct pwm_device *) enable;
    void (*)(struct pwm_chip *, struct pwm_device *) disable;
}
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
