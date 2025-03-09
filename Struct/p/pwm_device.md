# Struct: <code>pwm_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct pwm_device {
    const char * label;
    long unsigned int flags;
    unsigned int hwpwm;
    unsigned int pwm;
    struct pwm_chip * chip;
    void * chip_data;
    struct mutex lock;
    unsigned int period;
    unsigned int duty_cycle;
    enum pwm_polarity polarity;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct pwm_device {
    const char * label;
    long unsigned int flags;
    unsigned int hwpwm;
    unsigned int pwm;
    struct pwm_chip * chip;
    void * chip_data;
    struct pwm_args args;
    struct pwm_state state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct pwm_device {
    const char * label;
    long unsigned int flags;
    unsigned int hwpwm;
    unsigned int pwm;
    struct pwm_chip * chip;
    void * chip_data;
    struct pwm_args args;
    struct pwm_state state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct pwm_device {
    const char * label;
    long unsigned int flags;
    unsigned int hwpwm;
    unsigned int pwm;
    struct pwm_chip * chip;
    void * chip_data;
    struct pwm_args args;
    struct pwm_state state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct pwm_device {
    const char * label;
    long unsigned int flags;
    unsigned int hwpwm;
    unsigned int pwm;
    struct pwm_chip * chip;
    void * chip_data;
    struct pwm_args args;
    struct pwm_state state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct pwm_device {
    const char * label;
    long unsigned int flags;
    unsigned int hwpwm;
    unsigned int pwm;
    struct pwm_chip * chip;
    void * chip_data;
    struct pwm_args args;
    struct pwm_state state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct pwm_device {
    const char * label;
    long unsigned int flags;
    unsigned int hwpwm;
    unsigned int pwm;
    struct pwm_chip * chip;
    void * chip_data;
    struct pwm_args args;
    struct pwm_state state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct pwm_device {
    const char * label;
    long unsigned int flags;
    unsigned int hwpwm;
    unsigned int pwm;
    struct pwm_chip * chip;
    void * chip_data;
    struct pwm_args args;
    struct pwm_state state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct pwm_device {
    const char * label;
    long unsigned int flags;
    unsigned int hwpwm;
    unsigned int pwm;
    struct pwm_chip * chip;
    void * chip_data;
    struct pwm_args args;
    struct pwm_state state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct pwm_device {
    const char * label;
    long unsigned int flags;
    unsigned int hwpwm;
    unsigned int pwm;
    struct pwm_chip * chip;
    void * chip_data;
    struct pwm_args args;
    struct pwm_state state;
    struct pwm_state last;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct pwm_device {
    const char * label;
    long unsigned int flags;
    unsigned int hwpwm;
    unsigned int pwm;
    struct pwm_chip * chip;
    void * chip_data;
    struct pwm_args args;
    struct pwm_state state;
    struct pwm_state last;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct pwm_device {
    const char * label;
    long unsigned int flags;
    unsigned int hwpwm;
    unsigned int pwm;
    struct pwm_chip * chip;
    void * chip_data;
    struct pwm_args args;
    struct pwm_state state;
    struct pwm_state last;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct pwm_device {
    const char * label;
    long unsigned int flags;
    unsigned int hwpwm;
    unsigned int pwm;
    struct pwm_chip * chip;
    void * chip_data;
    struct pwm_args args;
    struct pwm_state state;
    struct pwm_state last;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct pwm_device {
    const char * label;
    long unsigned int flags;
    unsigned int hwpwm;
    unsigned int pwm;
    struct pwm_chip * chip;
    void * chip_data;
    struct pwm_args args;
    struct pwm_state state;
    struct pwm_state last;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct pwm_device {
    const char * label;
    long unsigned int flags;
    unsigned int hwpwm;
    unsigned int pwm;
    struct pwm_chip * chip;
    void * chip_data;
    struct pwm_args args;
    struct pwm_state state;
    struct pwm_state last;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct pwm_device {
    const char * label;
    long unsigned int flags;
    unsigned int hwpwm;
    unsigned int pwm;
    struct pwm_chip * chip;
    void * chip_data;
    struct pwm_args args;
    struct pwm_state state;
    struct pwm_state last;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct pwm_device {
    const char * label;
    long unsigned int flags;
    unsigned int hwpwm;
    struct pwm_chip * chip;
    struct pwm_args args;
    struct pwm_state state;
    struct pwm_state last;
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
struct pwm_device {
    const char * label;
    long unsigned int flags;
    unsigned int hwpwm;
    unsigned int pwm;
    struct pwm_chip * chip;
    void * chip_data;
    struct pwm_args args;
    struct pwm_state state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct pwm_device {
    const char * label;
    long unsigned int flags;
    unsigned int hwpwm;
    unsigned int pwm;
    struct pwm_chip * chip;
    void * chip_data;
    struct pwm_args args;
    struct pwm_state state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct pwm_device {
    const char * label;
    long unsigned int flags;
    unsigned int hwpwm;
    unsigned int pwm;
    struct pwm_chip * chip;
    void * chip_data;
    struct pwm_args args;
    struct pwm_state state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct pwm_device {
    const char * label;
    long unsigned int flags;
    unsigned int hwpwm;
    unsigned int pwm;
    struct pwm_chip * chip;
    void * chip_data;
    struct pwm_args args;
    struct pwm_state state;
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
struct pwm_device {
    const char * label;
    long unsigned int flags;
    unsigned int hwpwm;
    unsigned int pwm;
    struct pwm_chip * chip;
    void * chip_data;
    struct pwm_args args;
    struct pwm_state state;
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
struct pwm_device {
    const char * label;
    long unsigned int flags;
    unsigned int hwpwm;
    unsigned int pwm;
    struct pwm_chip * chip;
    void * chip_data;
    struct pwm_args args;
    struct pwm_state state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct pwm_device {
    const char * label;
    long unsigned int flags;
    unsigned int hwpwm;
    unsigned int pwm;
    struct pwm_chip * chip;
    void * chip_data;
    struct pwm_args args;
    struct pwm_state state;
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
<code>struct pwm_args args</code>
</li>
<li>
<b>Field added. </b>
<code>struct pwm_state state</code>
</li>
<li>
<b>Field removed. </b>
<code>struct mutex lock</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int period</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int duty_cycle</code>
</li>
<li>
<b>Field removed. </b>
<code>enum pwm_polarity polarity</code>
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
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
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
<code>struct pwm_state last</code>
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
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
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
<code>unsigned int pwm</code>
</li>
<li>
<b>Field removed. </b>
<code>void * chip_data</code>
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
struct pwm_device {
    const char * label;
    long unsigned int flags;
    unsigned int hwpwm;
    unsigned int pwm;
    struct pwm_chip * chip;
    void * chip_data;
    struct pwm_args args;
    struct pwm_state state;
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
