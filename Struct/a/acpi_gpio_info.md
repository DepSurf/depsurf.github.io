# Struct: <code>acpi_gpio_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct acpi_gpio_info {
    bool gpioint;
    bool active_low;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct acpi_gpio_info {
    bool gpioint;
    int polarity;
    int triggering;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct acpi_gpio_info {
    bool gpioint;
    int polarity;
    int triggering;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct acpi_gpio_info {
    enum gpiod_flags flags;
    bool gpioint;
    int polarity;
    int triggering;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct acpi_gpio_info {
    enum gpiod_flags flags;
    bool gpioint;
    int polarity;
    int triggering;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct acpi_gpio_info {
    struct acpi_device * adev;
    enum gpiod_flags flags;
    bool gpioint;
    int polarity;
    int triggering;
    unsigned int quirks;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct acpi_gpio_info {
    struct acpi_device * adev;
    enum gpiod_flags flags;
    bool gpioint;
    int polarity;
    int triggering;
    unsigned int quirks;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct acpi_gpio_info {
    struct acpi_device * adev;
    enum gpiod_flags flags;
    bool gpioint;
    int pin_config;
    int polarity;
    int triggering;
    unsigned int quirks;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct acpi_gpio_info {
    struct acpi_device * adev;
    enum gpiod_flags flags;
    bool gpioint;
    int pin_config;
    int polarity;
    int triggering;
    unsigned int quirks;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct acpi_gpio_info {
    struct acpi_device * adev;
    enum gpiod_flags flags;
    bool gpioint;
    int pin_config;
    int polarity;
    int triggering;
    unsigned int quirks;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct acpi_gpio_info {
    struct acpi_device * adev;
    enum gpiod_flags flags;
    bool gpioint;
    int pin_config;
    int polarity;
    int triggering;
    unsigned int debounce;
    unsigned int quirks;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct acpi_gpio_info {
    struct acpi_device * adev;
    enum gpiod_flags flags;
    bool gpioint;
    int pin_config;
    int polarity;
    int triggering;
    unsigned int debounce;
    unsigned int quirks;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct acpi_gpio_info {
    struct acpi_device * adev;
    enum gpiod_flags flags;
    bool gpioint;
    int pin_config;
    int polarity;
    int triggering;
    unsigned int debounce;
    unsigned int quirks;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct acpi_gpio_info {
    struct acpi_device * adev;
    enum gpiod_flags flags;
    bool gpioint;
    int pin_config;
    int polarity;
    int triggering;
    unsigned int debounce;
    unsigned int quirks;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct acpi_gpio_info {
    struct acpi_device * adev;
    enum gpiod_flags flags;
    bool gpioint;
    int pin_config;
    int polarity;
    int triggering;
    bool wake_capable;
    unsigned int debounce;
    unsigned int quirks;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct acpi_gpio_info {
    struct acpi_device * adev;
    enum gpiod_flags flags;
    bool gpioint;
    int pin_config;
    int polarity;
    int triggering;
    bool wake_capable;
    unsigned int debounce;
    unsigned int quirks;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct acpi_gpio_info {
    struct acpi_device * adev;
    enum gpiod_flags flags;
    bool gpioint;
    int pin_config;
    int polarity;
    int triggering;
    bool wake_capable;
    unsigned int debounce;
    unsigned int quirks;
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
struct acpi_gpio_info {
    struct acpi_device * adev;
    enum gpiod_flags flags;
    bool gpioint;
    int pin_config;
    int polarity;
    int triggering;
    unsigned int quirks;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct acpi_gpio_info {
    struct acpi_device * adev;
    enum gpiod_flags flags;
    bool gpioint;
    int pin_config;
    int polarity;
    int triggering;
    unsigned int quirks;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct acpi_gpio_info {
    struct acpi_device * adev;
    enum gpiod_flags flags;
    bool gpioint;
    int pin_config;
    int polarity;
    int triggering;
    unsigned int quirks;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct acpi_gpio_info {
    struct acpi_device * adev;
    enum gpiod_flags flags;
    bool gpioint;
    int pin_config;
    int polarity;
    int triggering;
    unsigned int quirks;
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
struct acpi_gpio_info {
    struct acpi_device * adev;
    enum gpiod_flags flags;
    bool gpioint;
    int pin_config;
    int polarity;
    int triggering;
    unsigned int quirks;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct acpi_gpio_info {
    struct acpi_device * adev;
    enum gpiod_flags flags;
    bool gpioint;
    int pin_config;
    int polarity;
    int triggering;
    unsigned int quirks;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct acpi_gpio_info {
    struct acpi_device * adev;
    enum gpiod_flags flags;
    bool gpioint;
    int pin_config;
    int polarity;
    int triggering;
    unsigned int quirks;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct acpi_gpio_info {
    struct acpi_device * adev;
    enum gpiod_flags flags;
    bool gpioint;
    int pin_config;
    int polarity;
    int triggering;
    unsigned int quirks;
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
<code>int polarity</code>
</li>
<li>
<b>Field added. </b>
<code>int triggering</code>
</li>
<li>
<b>Field removed. </b>
<code>bool active_low</code>
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
<code>enum gpiod_flags flags</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct acpi_device * adev</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int quirks</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int pin_config</code>
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
<code>unsigned int debounce</code>
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
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool wake_capable</code>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>struct acpi_device * adev</code> ➡️ <code>struct acpi_device * adev</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>struct acpi_device * adev</code> ➡️ <code>struct acpi_device * adev</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>struct acpi_device * adev</code> ➡️ <code>struct acpi_device * adev</code>
</li>
</ul>
</details>
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
