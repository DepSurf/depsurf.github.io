# Struct: <code>mii_bus</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct mii_bus {
    struct module * owner;
    const char * name;
    char[17] id;
    void * priv;
    int (*)(struct mii_bus *, int, int) read;
    int (*)(struct mii_bus *, int, int, u16) write;
    int (*)(struct mii_bus *) reset;
    struct mutex mdio_lock;
    struct device * parent;
    enum (anon) state;
    struct device dev;
    struct phy_device *[32] phy_map;
    u32 phy_mask;
    u32 phy_ignore_ta_mask;
    int * irq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct mii_bus {
    struct module * owner;
    const char * name;
    char[17] id;
    void * priv;
    int (*)(struct mii_bus *, int, int) read;
    int (*)(struct mii_bus *, int, int, u16) write;
    int (*)(struct mii_bus *) reset;
    struct mutex mdio_lock;
    struct device * parent;
    enum (anon) state;
    struct device dev;
    struct mdio_device *[32] mdio_map;
    u32 phy_mask;
    u32 phy_ignore_ta_mask;
    int[32] irq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct mii_bus {
    struct module * owner;
    const char * name;
    char[17] id;
    void * priv;
    int (*)(struct mii_bus *, int, int) read;
    int (*)(struct mii_bus *, int, int, u16) write;
    int (*)(struct mii_bus *) reset;
    struct mutex mdio_lock;
    struct device * parent;
    enum (anon) state;
    struct device dev;
    struct mdio_device *[32] mdio_map;
    u32 phy_mask;
    u32 phy_ignore_ta_mask;
    int[32] irq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct mii_bus {
    struct module * owner;
    const char * name;
    char[61] id;
    void * priv;
    int (*)(struct mii_bus *, int, int) read;
    int (*)(struct mii_bus *, int, int, u16) write;
    int (*)(struct mii_bus *) reset;
    struct mutex mdio_lock;
    struct device * parent;
    enum (anon) state;
    struct device dev;
    struct mdio_device *[32] mdio_map;
    u32 phy_mask;
    u32 phy_ignore_ta_mask;
    int[32] irq;
    int reset_delay_us;
    struct gpio_desc * reset_gpiod;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct mii_bus {
    struct module * owner;
    const char * name;
    char[61] id;
    void * priv;
    int (*)(struct mii_bus *, int, int) read;
    int (*)(struct mii_bus *, int, int, u16) write;
    int (*)(struct mii_bus *) reset;
    struct mutex mdio_lock;
    struct device * parent;
    enum (anon) state;
    struct device dev;
    struct mdio_device *[32] mdio_map;
    u32 phy_mask;
    u32 phy_ignore_ta_mask;
    int[32] irq;
    int reset_delay_us;
    struct gpio_desc * reset_gpiod;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct mii_bus {
    struct module * owner;
    const char * name;
    char[61] id;
    void * priv;
    int (*)(struct mii_bus *, int, int) read;
    int (*)(struct mii_bus *, int, int, u16) write;
    int (*)(struct mii_bus *) reset;
    struct mutex mdio_lock;
    struct device * parent;
    enum (anon) state;
    struct device dev;
    struct mdio_device *[32] mdio_map;
    u32 phy_mask;
    u32 phy_ignore_ta_mask;
    int[32] irq;
    int reset_delay_us;
    struct gpio_desc * reset_gpiod;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct mii_bus {
    struct module * owner;
    const char * name;
    char[61] id;
    void * priv;
    int (*)(struct mii_bus *, int, int) read;
    int (*)(struct mii_bus *, int, int, u16) write;
    int (*)(struct mii_bus *) reset;
    struct mutex mdio_lock;
    struct device * parent;
    enum (anon) state;
    struct device dev;
    struct mdio_device *[32] mdio_map;
    u32 phy_mask;
    u32 phy_ignore_ta_mask;
    int[32] irq;
    int reset_delay_us;
    struct gpio_desc * reset_gpiod;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct mii_bus {
    struct module * owner;
    const char * name;
    char[61] id;
    void * priv;
    int (*)(struct mii_bus *, int, int) read;
    int (*)(struct mii_bus *, int, int, u16) write;
    int (*)(struct mii_bus *) reset;
    struct mutex mdio_lock;
    struct device * parent;
    enum (anon) state;
    struct device dev;
    struct mdio_device *[32] mdio_map;
    u32 phy_mask;
    u32 phy_ignore_ta_mask;
    int[32] irq;
    int reset_delay_us;
    struct gpio_desc * reset_gpiod;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct mii_bus {
    struct module * owner;
    const char * name;
    char[61] id;
    void * priv;
    int (*)(struct mii_bus *, int, int) read;
    int (*)(struct mii_bus *, int, int, u16) write;
    int (*)(struct mii_bus *) reset;
    struct mutex mdio_lock;
    struct device * parent;
    enum (anon) state;
    struct device dev;
    struct mdio_device *[32] mdio_map;
    u32 phy_mask;
    u32 phy_ignore_ta_mask;
    int[32] irq;
    int reset_delay_us;
    struct gpio_desc * reset_gpiod;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct mii_bus {
    struct module * owner;
    const char * name;
    char[61] id;
    void * priv;
    int (*)(struct mii_bus *, int, int) read;
    int (*)(struct mii_bus *, int, int, u16) write;
    int (*)(struct mii_bus *) reset;
    struct mdio_bus_stats[32] stats;
    unsigned int is_managed;
    unsigned int is_managed_registered;
    struct mutex mdio_lock;
    struct device * parent;
    enum (anon) state;
    struct device dev;
    struct mdio_device *[32] mdio_map;
    u32 phy_mask;
    u32 phy_ignore_ta_mask;
    int[32] irq;
    int reset_delay_us;
    struct gpio_desc * reset_gpiod;
    struct mutex shared_lock;
    struct phy_package_shared *[32] shared;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct mii_bus {
    struct module * owner;
    const char * name;
    char[61] id;
    void * priv;
    int (*)(struct mii_bus *, int, int) read;
    int (*)(struct mii_bus *, int, int, u16) write;
    int (*)(struct mii_bus *) reset;
    struct mdio_bus_stats[32] stats;
    struct mutex mdio_lock;
    struct device * parent;
    enum (anon) state;
    struct device dev;
    struct mdio_device *[32] mdio_map;
    u32 phy_mask;
    u32 phy_ignore_ta_mask;
    int[32] irq;
    int reset_delay_us;
    int reset_post_delay_us;
    struct gpio_desc * reset_gpiod;
    enum (anon) probe_capabilities;
    struct mutex shared_lock;
    struct phy_package_shared *[32] shared;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct mii_bus {
    struct module * owner;
    const char * name;
    char[61] id;
    void * priv;
    int (*)(struct mii_bus *, int, int) read;
    int (*)(struct mii_bus *, int, int, u16) write;
    int (*)(struct mii_bus *) reset;
    struct mdio_bus_stats[32] stats;
    struct mutex mdio_lock;
    struct device * parent;
    enum (anon) state;
    struct device dev;
    struct mdio_device *[32] mdio_map;
    u32 phy_mask;
    u32 phy_ignore_ta_mask;
    int[32] irq;
    int reset_delay_us;
    int reset_post_delay_us;
    struct gpio_desc * reset_gpiod;
    enum (anon) probe_capabilities;
    struct mutex shared_lock;
    struct phy_package_shared *[32] shared;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct mii_bus {
    struct module * owner;
    const char * name;
    char[61] id;
    void * priv;
    int (*)(struct mii_bus *, int, int) read;
    int (*)(struct mii_bus *, int, int, u16) write;
    int (*)(struct mii_bus *) reset;
    struct mdio_bus_stats[32] stats;
    struct mutex mdio_lock;
    struct device * parent;
    enum (anon) state;
    struct device dev;
    struct mdio_device *[32] mdio_map;
    u32 phy_mask;
    u32 phy_ignore_ta_mask;
    int[32] irq;
    int reset_delay_us;
    int reset_post_delay_us;
    struct gpio_desc * reset_gpiod;
    enum (anon) probe_capabilities;
    struct mutex shared_lock;
    struct phy_package_shared *[32] shared;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct mii_bus {
    struct module * owner;
    const char * name;
    char[61] id;
    void * priv;
    int (*)(struct mii_bus *, int, int) read;
    int (*)(struct mii_bus *, int, int, u16) write;
    int (*)(struct mii_bus *) reset;
    struct mdio_bus_stats[32] stats;
    struct mutex mdio_lock;
    struct device * parent;
    enum (anon) state;
    struct device dev;
    struct mdio_device *[32] mdio_map;
    u32 phy_mask;
    u32 phy_ignore_ta_mask;
    int[32] irq;
    int reset_delay_us;
    int reset_post_delay_us;
    struct gpio_desc * reset_gpiod;
    enum (anon) probe_capabilities;
    struct mutex shared_lock;
    struct phy_package_shared *[32] shared;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct mii_bus {
    struct module * owner;
    const char * name;
    char[61] id;
    void * priv;
    int (*)(struct mii_bus *, int, int) read;
    int (*)(struct mii_bus *, int, int, u16) write;
    int (*)(struct mii_bus *) reset;
    struct mdio_bus_stats[32] stats;
    struct mutex mdio_lock;
    struct device * parent;
    enum (anon) state;
    struct device dev;
    struct mdio_device *[32] mdio_map;
    u32 phy_mask;
    u32 phy_ignore_ta_mask;
    int[32] irq;
    int reset_delay_us;
    int reset_post_delay_us;
    struct gpio_desc * reset_gpiod;
    enum (anon) probe_capabilities;
    struct mutex shared_lock;
    struct phy_package_shared *[32] shared;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct mii_bus {
    struct module * owner;
    const char * name;
    char[61] id;
    void * priv;
    int (*)(struct mii_bus *, int, int) read;
    int (*)(struct mii_bus *, int, int, u16) write;
    int (*)(struct mii_bus *, int, int, int) read_c45;
    int (*)(struct mii_bus *, int, int, int, u16) write_c45;
    int (*)(struct mii_bus *) reset;
    struct mdio_bus_stats[32] stats;
    struct mutex mdio_lock;
    struct device * parent;
    enum (anon) state;
    struct device dev;
    struct mdio_device *[32] mdio_map;
    u32 phy_mask;
    u32 phy_ignore_ta_mask;
    int[32] irq;
    int reset_delay_us;
    int reset_post_delay_us;
    struct gpio_desc * reset_gpiod;
    struct mutex shared_lock;
    struct phy_package_shared *[32] shared;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct mii_bus {
    struct module * owner;
    const char * name;
    char[61] id;
    void * priv;
    int (*)(struct mii_bus *, int, int) read;
    int (*)(struct mii_bus *, int, int, u16) write;
    int (*)(struct mii_bus *, int, int, int) read_c45;
    int (*)(struct mii_bus *, int, int, int, u16) write_c45;
    int (*)(struct mii_bus *) reset;
    struct mdio_bus_stats[32] stats;
    struct mutex mdio_lock;
    struct device * parent;
    enum (anon) state;
    struct device dev;
    struct mdio_device *[32] mdio_map;
    u32 phy_mask;
    u32 phy_ignore_ta_mask;
    int[32] irq;
    int reset_delay_us;
    int reset_post_delay_us;
    struct gpio_desc * reset_gpiod;
    struct mutex shared_lock;
    struct phy_package_shared *[32] shared;
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
struct mii_bus {
    struct module * owner;
    const char * name;
    char[61] id;
    void * priv;
    int (*)(struct mii_bus *, int, int) read;
    int (*)(struct mii_bus *, int, int, u16) write;
    int (*)(struct mii_bus *) reset;
    struct mutex mdio_lock;
    struct device * parent;
    enum (anon) state;
    struct device dev;
    struct mdio_device *[32] mdio_map;
    u32 phy_mask;
    u32 phy_ignore_ta_mask;
    int[32] irq;
    int reset_delay_us;
    struct gpio_desc * reset_gpiod;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct mii_bus {
    struct module * owner;
    const char * name;
    char[61] id;
    void * priv;
    int (*)(struct mii_bus *, int, int) read;
    int (*)(struct mii_bus *, int, int, u16) write;
    int (*)(struct mii_bus *) reset;
    struct mutex mdio_lock;
    struct device * parent;
    enum (anon) state;
    struct device dev;
    struct mdio_device *[32] mdio_map;
    u32 phy_mask;
    u32 phy_ignore_ta_mask;
    int[32] irq;
    int reset_delay_us;
    struct gpio_desc * reset_gpiod;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct mii_bus {
    struct module * owner;
    const char * name;
    char[61] id;
    void * priv;
    int (*)(struct mii_bus *, int, int) read;
    int (*)(struct mii_bus *, int, int, u16) write;
    int (*)(struct mii_bus *) reset;
    struct mutex mdio_lock;
    struct device * parent;
    enum (anon) state;
    struct device dev;
    struct mdio_device *[32] mdio_map;
    u32 phy_mask;
    u32 phy_ignore_ta_mask;
    int[32] irq;
    int reset_delay_us;
    struct gpio_desc * reset_gpiod;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct mii_bus {
    struct module * owner;
    const char * name;
    char[61] id;
    void * priv;
    int (*)(struct mii_bus *, int, int) read;
    int (*)(struct mii_bus *, int, int, u16) write;
    int (*)(struct mii_bus *) reset;
    struct mutex mdio_lock;
    struct device * parent;
    enum (anon) state;
    struct device dev;
    struct mdio_device *[32] mdio_map;
    u32 phy_mask;
    u32 phy_ignore_ta_mask;
    int[32] irq;
    int reset_delay_us;
    struct gpio_desc * reset_gpiod;
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
struct mii_bus {
    struct module * owner;
    const char * name;
    char[61] id;
    void * priv;
    int (*)(struct mii_bus *, int, int) read;
    int (*)(struct mii_bus *, int, int, u16) write;
    int (*)(struct mii_bus *) reset;
    struct mutex mdio_lock;
    struct device * parent;
    enum (anon) state;
    struct device dev;
    struct mdio_device *[32] mdio_map;
    u32 phy_mask;
    u32 phy_ignore_ta_mask;
    int[32] irq;
    int reset_delay_us;
    struct gpio_desc * reset_gpiod;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct mii_bus {
    struct module * owner;
    const char * name;
    char[61] id;
    void * priv;
    int (*)(struct mii_bus *, int, int) read;
    int (*)(struct mii_bus *, int, int, u16) write;
    int (*)(struct mii_bus *) reset;
    struct mutex mdio_lock;
    struct device * parent;
    enum (anon) state;
    struct device dev;
    struct mdio_device *[32] mdio_map;
    u32 phy_mask;
    u32 phy_ignore_ta_mask;
    int[32] irq;
    int reset_delay_us;
    struct gpio_desc * reset_gpiod;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct mii_bus {
    struct module * owner;
    const char * name;
    char[61] id;
    void * priv;
    int (*)(struct mii_bus *, int, int) read;
    int (*)(struct mii_bus *, int, int, u16) write;
    int (*)(struct mii_bus *) reset;
    struct mutex mdio_lock;
    struct device * parent;
    enum (anon) state;
    struct device dev;
    struct mdio_device *[32] mdio_map;
    u32 phy_mask;
    u32 phy_ignore_ta_mask;
    int[32] irq;
    int reset_delay_us;
    struct gpio_desc * reset_gpiod;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct mii_bus {
    struct module * owner;
    const char * name;
    char[61] id;
    void * priv;
    int (*)(struct mii_bus *, int, int) read;
    int (*)(struct mii_bus *, int, int, u16) write;
    int (*)(struct mii_bus *) reset;
    struct mutex mdio_lock;
    struct device * parent;
    enum (anon) state;
    struct device dev;
    struct mdio_device *[32] mdio_map;
    u32 phy_mask;
    u32 phy_ignore_ta_mask;
    int[32] irq;
    int reset_delay_us;
    struct gpio_desc * reset_gpiod;
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
<code>struct mdio_device *[32] mdio_map</code>
</li>
<li>
<b>Field removed. </b>
<code>struct phy_device *[32] phy_map</code>
</li>
<li>
<b>Field type changed. </b>
<code>int * irq</code> ➡️ <code>int[32] irq</code>
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
<code>int reset_delay_us</code>
</li>
<li>
<b>Field added. </b>
<code>struct gpio_desc * reset_gpiod</code>
</li>
<li>
<b>Field type changed. </b>
<code>char[17] id</code> ➡️ <code>char[61] id</code>
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
<code>struct mdio_bus_stats[32] stats</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int is_managed</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int is_managed_registered</code>
</li>
<li>
<b>Field added. </b>
<code>struct mutex shared_lock</code>
</li>
<li>
<b>Field added. </b>
<code>struct phy_package_shared *[32] shared</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int reset_post_delay_us</code>
</li>
<li>
<b>Field added. </b>
<code>enum (anon) probe_capabilities</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int is_managed</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int is_managed_registered</code>
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
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct mii_bus *, int, int, int) read_c45</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct mii_bus *, int, int, int, u16) write_c45</code>
</li>
<li>
<b>Field removed. </b>
<code>enum (anon) probe_capabilities</code>
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
