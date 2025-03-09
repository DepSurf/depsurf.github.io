# Struct: <code>fixed_phy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct fixed_phy {
    int addr;
    u16[29] regs;
    struct phy_device * phydev;
    struct fixed_phy_status status;
    int (*)(struct net_device *, struct fixed_phy_status *) link_update;
    struct list_head node;
    int link_gpio;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct fixed_phy {
    int addr;
    struct phy_device * phydev;
    seqcount_t seqcount;
    struct fixed_phy_status status;
    int (*)(struct net_device *, struct fixed_phy_status *) link_update;
    struct list_head node;
    int link_gpio;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct fixed_phy {
    int addr;
    struct phy_device * phydev;
    seqcount_t seqcount;
    struct fixed_phy_status status;
    int (*)(struct net_device *, struct fixed_phy_status *) link_update;
    struct list_head node;
    int link_gpio;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct fixed_phy {
    int addr;
    struct phy_device * phydev;
    seqcount_t seqcount;
    struct fixed_phy_status status;
    int (*)(struct net_device *, struct fixed_phy_status *) link_update;
    struct list_head node;
    int link_gpio;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct fixed_phy {
    int addr;
    struct phy_device * phydev;
    seqcount_t seqcount;
    struct fixed_phy_status status;
    int (*)(struct net_device *, struct fixed_phy_status *) link_update;
    struct list_head node;
    int link_gpio;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct fixed_phy {
    int addr;
    struct phy_device * phydev;
    seqcount_t seqcount;
    struct fixed_phy_status status;
    int (*)(struct net_device *, struct fixed_phy_status *) link_update;
    struct list_head node;
    int link_gpio;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct fixed_phy {
    int addr;
    struct phy_device * phydev;
    seqcount_t seqcount;
    struct fixed_phy_status status;
    bool no_carrier;
    int (*)(struct net_device *, struct fixed_phy_status *) link_update;
    struct list_head node;
    int link_gpio;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct fixed_phy {
    int addr;
    struct phy_device * phydev;
    seqcount_t seqcount;
    struct fixed_phy_status status;
    bool no_carrier;
    int (*)(struct net_device *, struct fixed_phy_status *) link_update;
    struct list_head node;
    struct gpio_desc * link_gpiod;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct fixed_phy {
    int addr;
    struct phy_device * phydev;
    seqcount_t seqcount;
    struct fixed_phy_status status;
    bool no_carrier;
    int (*)(struct net_device *, struct fixed_phy_status *) link_update;
    struct list_head node;
    struct gpio_desc * link_gpiod;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct fixed_phy {
    int addr;
    struct phy_device * phydev;
    struct fixed_phy_status status;
    bool no_carrier;
    int (*)(struct net_device *, struct fixed_phy_status *) link_update;
    struct list_head node;
    struct gpio_desc * link_gpiod;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct fixed_phy {
    int addr;
    struct phy_device * phydev;
    struct fixed_phy_status status;
    bool no_carrier;
    int (*)(struct net_device *, struct fixed_phy_status *) link_update;
    struct list_head node;
    struct gpio_desc * link_gpiod;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct fixed_phy {
    int addr;
    struct phy_device * phydev;
    struct fixed_phy_status status;
    bool no_carrier;
    int (*)(struct net_device *, struct fixed_phy_status *) link_update;
    struct list_head node;
    struct gpio_desc * link_gpiod;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct fixed_phy {
    int addr;
    struct phy_device * phydev;
    struct fixed_phy_status status;
    bool no_carrier;
    int (*)(struct net_device *, struct fixed_phy_status *) link_update;
    struct list_head node;
    struct gpio_desc * link_gpiod;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct fixed_phy {
    int addr;
    struct phy_device * phydev;
    struct fixed_phy_status status;
    bool no_carrier;
    int (*)(struct net_device *, struct fixed_phy_status *) link_update;
    struct list_head node;
    struct gpio_desc * link_gpiod;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct fixed_phy {
    int addr;
    struct phy_device * phydev;
    struct fixed_phy_status status;
    bool no_carrier;
    int (*)(struct net_device *, struct fixed_phy_status *) link_update;
    struct list_head node;
    struct gpio_desc * link_gpiod;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct fixed_phy {
    int addr;
    struct phy_device * phydev;
    struct fixed_phy_status status;
    bool no_carrier;
    int (*)(struct net_device *, struct fixed_phy_status *) link_update;
    struct list_head node;
    struct gpio_desc * link_gpiod;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct fixed_phy {
    int addr;
    struct phy_device * phydev;
    struct fixed_phy_status status;
    bool no_carrier;
    int (*)(struct net_device *, struct fixed_phy_status *) link_update;
    struct list_head node;
    struct gpio_desc * link_gpiod;
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
struct fixed_phy {
    int addr;
    struct phy_device * phydev;
    seqcount_t seqcount;
    struct fixed_phy_status status;
    bool no_carrier;
    int (*)(struct net_device *, struct fixed_phy_status *) link_update;
    struct list_head node;
    struct gpio_desc * link_gpiod;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct fixed_phy {
    int addr;
    struct phy_device * phydev;
    seqcount_t seqcount;
    struct fixed_phy_status status;
    bool no_carrier;
    int (*)(struct net_device *, struct fixed_phy_status *) link_update;
    struct list_head node;
    struct gpio_desc * link_gpiod;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct fixed_phy {
    int addr;
    struct phy_device * phydev;
    seqcount_t seqcount;
    struct fixed_phy_status status;
    bool no_carrier;
    int (*)(struct net_device *, struct fixed_phy_status *) link_update;
    struct list_head node;
    struct gpio_desc * link_gpiod;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct fixed_phy {
    int addr;
    struct phy_device * phydev;
    seqcount_t seqcount;
    struct fixed_phy_status status;
    bool no_carrier;
    int (*)(struct net_device *, struct fixed_phy_status *) link_update;
    struct list_head node;
    struct gpio_desc * link_gpiod;
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
struct fixed_phy {
    int addr;
    struct phy_device * phydev;
    seqcount_t seqcount;
    struct fixed_phy_status status;
    bool no_carrier;
    int (*)(struct net_device *, struct fixed_phy_status *) link_update;
    struct list_head node;
    struct gpio_desc * link_gpiod;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct fixed_phy {
    int addr;
    struct phy_device * phydev;
    seqcount_t seqcount;
    struct fixed_phy_status status;
    bool no_carrier;
    int (*)(struct net_device *, struct fixed_phy_status *) link_update;
    struct list_head node;
    struct gpio_desc * link_gpiod;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct fixed_phy {
    int addr;
    struct phy_device * phydev;
    seqcount_t seqcount;
    struct fixed_phy_status status;
    bool no_carrier;
    int (*)(struct net_device *, struct fixed_phy_status *) link_update;
    struct list_head node;
    struct gpio_desc * link_gpiod;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct fixed_phy {
    int addr;
    struct phy_device * phydev;
    seqcount_t seqcount;
    struct fixed_phy_status status;
    bool no_carrier;
    int (*)(struct net_device *, struct fixed_phy_status *) link_update;
    struct list_head node;
    struct gpio_desc * link_gpiod;
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
<code>seqcount_t seqcount</code>
</li>
<li>
<b>Field removed. </b>
<code>u16[29] regs</code>
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool no_carrier</code>
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
<code>struct gpio_desc * link_gpiod</code>
</li>
<li>
<b>Field removed. </b>
<code>int link_gpio</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>seqcount_t seqcount</code>
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
