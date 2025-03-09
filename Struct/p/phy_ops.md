# Struct: <code>phy_ops</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct phy_ops {
    int (*)(struct phy *) init;
    int (*)(struct phy *) exit;
    int (*)(struct phy *) power_on;
    int (*)(struct phy *) power_off;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct phy_ops {
    int (*)(struct phy *) init;
    int (*)(struct phy *) exit;
    int (*)(struct phy *) power_on;
    int (*)(struct phy *) power_off;
    int (*)(struct phy *, enum phy_mode) set_mode;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct phy_ops {
    int (*)(struct phy *) init;
    int (*)(struct phy *) exit;
    int (*)(struct phy *) power_on;
    int (*)(struct phy *) power_off;
    int (*)(struct phy *, enum phy_mode) set_mode;
    int (*)(struct phy *) reset;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct phy_ops {
    int (*)(struct phy *) init;
    int (*)(struct phy *) exit;
    int (*)(struct phy *) power_on;
    int (*)(struct phy *) power_off;
    int (*)(struct phy *, enum phy_mode) set_mode;
    int (*)(struct phy *) reset;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct phy_ops {
    int (*)(struct phy *) init;
    int (*)(struct phy *) exit;
    int (*)(struct phy *) power_on;
    int (*)(struct phy *) power_off;
    int (*)(struct phy *, enum phy_mode) set_mode;
    int (*)(struct phy *) reset;
    int (*)(struct phy *) calibrate;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct phy_ops {
    int (*)(struct phy *) init;
    int (*)(struct phy *) exit;
    int (*)(struct phy *) power_on;
    int (*)(struct phy *) power_off;
    int (*)(struct phy *, enum phy_mode) set_mode;
    int (*)(struct phy *) reset;
    int (*)(struct phy *) calibrate;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct phy_ops {
    int (*)(struct phy *) init;
    int (*)(struct phy *) exit;
    int (*)(struct phy *) power_on;
    int (*)(struct phy *) power_off;
    int (*)(struct phy *, enum phy_mode, int) set_mode;
    int (*)(struct phy *, union phy_configure_opts *) configure;
    int (*)(struct phy *, enum phy_mode, int, union phy_configure_opts *) validate;
    int (*)(struct phy *) reset;
    int (*)(struct phy *) calibrate;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct phy_ops {
    int (*)(struct phy *) init;
    int (*)(struct phy *) exit;
    int (*)(struct phy *) power_on;
    int (*)(struct phy *) power_off;
    int (*)(struct phy *, enum phy_mode, int) set_mode;
    int (*)(struct phy *, union phy_configure_opts *) configure;
    int (*)(struct phy *, enum phy_mode, int, union phy_configure_opts *) validate;
    int (*)(struct phy *) reset;
    int (*)(struct phy *) calibrate;
    void (*)(struct phy *) release;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct phy_ops {
    int (*)(struct phy *) init;
    int (*)(struct phy *) exit;
    int (*)(struct phy *) power_on;
    int (*)(struct phy *) power_off;
    int (*)(struct phy *, enum phy_mode, int) set_mode;
    int (*)(struct phy *, union phy_configure_opts *) configure;
    int (*)(struct phy *, enum phy_mode, int, union phy_configure_opts *) validate;
    int (*)(struct phy *) reset;
    int (*)(struct phy *) calibrate;
    void (*)(struct phy *) release;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct phy_ops {
    int (*)(struct phy *) init;
    int (*)(struct phy *) exit;
    int (*)(struct phy *) power_on;
    int (*)(struct phy *) power_off;
    int (*)(struct phy *, enum phy_mode, int) set_mode;
    int (*)(struct phy *, union phy_configure_opts *) configure;
    int (*)(struct phy *, enum phy_mode, int, union phy_configure_opts *) validate;
    int (*)(struct phy *) reset;
    int (*)(struct phy *) calibrate;
    void (*)(struct phy *) release;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct phy_ops {
    int (*)(struct phy *) init;
    int (*)(struct phy *) exit;
    int (*)(struct phy *) power_on;
    int (*)(struct phy *) power_off;
    int (*)(struct phy *, enum phy_mode, int) set_mode;
    int (*)(struct phy *, union phy_configure_opts *) configure;
    int (*)(struct phy *, enum phy_mode, int, union phy_configure_opts *) validate;
    int (*)(struct phy *) reset;
    int (*)(struct phy *) calibrate;
    void (*)(struct phy *) release;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct phy_ops {
    int (*)(struct phy *) init;
    int (*)(struct phy *) exit;
    int (*)(struct phy *) power_on;
    int (*)(struct phy *) power_off;
    int (*)(struct phy *, enum phy_mode, int) set_mode;
    int (*)(struct phy *, enum phy_media) set_media;
    int (*)(struct phy *, int) set_speed;
    int (*)(struct phy *, union phy_configure_opts *) configure;
    int (*)(struct phy *, enum phy_mode, int, union phy_configure_opts *) validate;
    int (*)(struct phy *) reset;
    int (*)(struct phy *) calibrate;
    void (*)(struct phy *) release;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct phy_ops {
    int (*)(struct phy *) init;
    int (*)(struct phy *) exit;
    int (*)(struct phy *) power_on;
    int (*)(struct phy *) power_off;
    int (*)(struct phy *, enum phy_mode, int) set_mode;
    int (*)(struct phy *, enum phy_media) set_media;
    int (*)(struct phy *, int) set_speed;
    int (*)(struct phy *, union phy_configure_opts *) configure;
    int (*)(struct phy *, enum phy_mode, int, union phy_configure_opts *) validate;
    int (*)(struct phy *) reset;
    int (*)(struct phy *) calibrate;
    void (*)(struct phy *) release;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct phy_ops {
    int (*)(struct phy *) init;
    int (*)(struct phy *) exit;
    int (*)(struct phy *) power_on;
    int (*)(struct phy *) power_off;
    int (*)(struct phy *, enum phy_mode, int) set_mode;
    int (*)(struct phy *, enum phy_media) set_media;
    int (*)(struct phy *, int) set_speed;
    int (*)(struct phy *, union phy_configure_opts *) configure;
    int (*)(struct phy *, enum phy_mode, int, union phy_configure_opts *) validate;
    int (*)(struct phy *) reset;
    int (*)(struct phy *) calibrate;
    void (*)(struct phy *) release;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct phy_ops {
    int (*)(struct phy *) init;
    int (*)(struct phy *) exit;
    int (*)(struct phy *) power_on;
    int (*)(struct phy *) power_off;
    int (*)(struct phy *, enum phy_mode, int) set_mode;
    int (*)(struct phy *, enum phy_media) set_media;
    int (*)(struct phy *, int) set_speed;
    int (*)(struct phy *, union phy_configure_opts *) configure;
    int (*)(struct phy *, enum phy_mode, int, union phy_configure_opts *) validate;
    int (*)(struct phy *) reset;
    int (*)(struct phy *) calibrate;
    void (*)(struct phy *) release;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct phy_ops {
    int (*)(struct phy *) init;
    int (*)(struct phy *) exit;
    int (*)(struct phy *) power_on;
    int (*)(struct phy *) power_off;
    int (*)(struct phy *, enum phy_mode, int) set_mode;
    int (*)(struct phy *, enum phy_media) set_media;
    int (*)(struct phy *, int) set_speed;
    int (*)(struct phy *, union phy_configure_opts *) configure;
    int (*)(struct phy *, enum phy_mode, int, union phy_configure_opts *) validate;
    int (*)(struct phy *) reset;
    int (*)(struct phy *) calibrate;
    void (*)(struct phy *) release;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct phy_ops {
    int (*)(struct phy *) init;
    int (*)(struct phy *) exit;
    int (*)(struct phy *) power_on;
    int (*)(struct phy *) power_off;
    int (*)(struct phy *, enum phy_mode, int) set_mode;
    int (*)(struct phy *, enum phy_media) set_media;
    int (*)(struct phy *, int) set_speed;
    int (*)(struct phy *, union phy_configure_opts *) configure;
    int (*)(struct phy *, enum phy_mode, int, union phy_configure_opts *) validate;
    int (*)(struct phy *) reset;
    int (*)(struct phy *) calibrate;
    void (*)(struct phy *) release;
    struct module * owner;
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
struct phy_ops {
    int (*)(struct phy *) init;
    int (*)(struct phy *) exit;
    int (*)(struct phy *) power_on;
    int (*)(struct phy *) power_off;
    int (*)(struct phy *, enum phy_mode, int) set_mode;
    int (*)(struct phy *, union phy_configure_opts *) configure;
    int (*)(struct phy *, enum phy_mode, int, union phy_configure_opts *) validate;
    int (*)(struct phy *) reset;
    int (*)(struct phy *) calibrate;
    void (*)(struct phy *) release;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct phy_ops {
    int (*)(struct phy *) init;
    int (*)(struct phy *) exit;
    int (*)(struct phy *) power_on;
    int (*)(struct phy *) power_off;
    int (*)(struct phy *, enum phy_mode, int) set_mode;
    int (*)(struct phy *, union phy_configure_opts *) configure;
    int (*)(struct phy *, enum phy_mode, int, union phy_configure_opts *) validate;
    int (*)(struct phy *) reset;
    int (*)(struct phy *) calibrate;
    void (*)(struct phy *) release;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct phy_ops {
    int (*)(struct phy *) init;
    int (*)(struct phy *) exit;
    int (*)(struct phy *) power_on;
    int (*)(struct phy *) power_off;
    int (*)(struct phy *, enum phy_mode, int) set_mode;
    int (*)(struct phy *, union phy_configure_opts *) configure;
    int (*)(struct phy *, enum phy_mode, int, union phy_configure_opts *) validate;
    int (*)(struct phy *) reset;
    int (*)(struct phy *) calibrate;
    void (*)(struct phy *) release;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct phy_ops {
    int (*)(struct phy *) init;
    int (*)(struct phy *) exit;
    int (*)(struct phy *) power_on;
    int (*)(struct phy *) power_off;
    int (*)(struct phy *, enum phy_mode, int) set_mode;
    int (*)(struct phy *, union phy_configure_opts *) configure;
    int (*)(struct phy *, enum phy_mode, int, union phy_configure_opts *) validate;
    int (*)(struct phy *) reset;
    int (*)(struct phy *) calibrate;
    void (*)(struct phy *) release;
    struct module * owner;
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
struct phy_ops {
    int (*)(struct phy *) init;
    int (*)(struct phy *) exit;
    int (*)(struct phy *) power_on;
    int (*)(struct phy *) power_off;
    int (*)(struct phy *, enum phy_mode, int) set_mode;
    int (*)(struct phy *, union phy_configure_opts *) configure;
    int (*)(struct phy *, enum phy_mode, int, union phy_configure_opts *) validate;
    int (*)(struct phy *) reset;
    int (*)(struct phy *) calibrate;
    void (*)(struct phy *) release;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct phy_ops {
    int (*)(struct phy *) init;
    int (*)(struct phy *) exit;
    int (*)(struct phy *) power_on;
    int (*)(struct phy *) power_off;
    int (*)(struct phy *, enum phy_mode, int) set_mode;
    int (*)(struct phy *, union phy_configure_opts *) configure;
    int (*)(struct phy *, enum phy_mode, int, union phy_configure_opts *) validate;
    int (*)(struct phy *) reset;
    int (*)(struct phy *) calibrate;
    void (*)(struct phy *) release;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct phy_ops {
    int (*)(struct phy *) init;
    int (*)(struct phy *) exit;
    int (*)(struct phy *) power_on;
    int (*)(struct phy *) power_off;
    int (*)(struct phy *, enum phy_mode, int) set_mode;
    int (*)(struct phy *, union phy_configure_opts *) configure;
    int (*)(struct phy *, enum phy_mode, int, union phy_configure_opts *) validate;
    int (*)(struct phy *) reset;
    int (*)(struct phy *) calibrate;
    void (*)(struct phy *) release;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct phy_ops {
    int (*)(struct phy *) init;
    int (*)(struct phy *) exit;
    int (*)(struct phy *) power_on;
    int (*)(struct phy *) power_off;
    int (*)(struct phy *, enum phy_mode, int) set_mode;
    int (*)(struct phy *, union phy_configure_opts *) configure;
    int (*)(struct phy *, enum phy_mode, int, union phy_configure_opts *) validate;
    int (*)(struct phy *) reset;
    int (*)(struct phy *) calibrate;
    void (*)(struct phy *) release;
    struct module * owner;
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
<code>int (*)(struct phy *, enum phy_mode) set_mode</code>
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
<code>int (*)(struct phy *) reset</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct phy *) calibrate</code>
</li>
</ul>
</details>
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
<code>int (*)(struct phy *, union phy_configure_opts *) configure</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct phy *, enum phy_mode, int, union phy_configure_opts *) validate</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct phy *, enum phy_mode) set_mode</code> ➡️ <code>int (*)(struct phy *, enum phy_mode, int) set_mode</code>
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
<code>void (*)(struct phy *) release</code>
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
<code>int (*)(struct phy *, enum phy_media) set_media</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct phy *, int) set_speed</code>
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
