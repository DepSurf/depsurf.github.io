# Struct: <code>ehci_platform_priv</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct ehci_platform_priv {
    struct clk *[3] clks;
    struct reset_control * rst;
    struct phy * * phys;
    int num_phys;
    bool reset_on_resume;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct ehci_platform_priv {
    struct clk *[3] clks;
    struct reset_control *[3] rsts;
    struct phy * * phys;
    int num_phys;
    bool reset_on_resume;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct ehci_platform_priv {
    struct clk *[4] clks;
    struct reset_control *[4] rsts;
    struct phy * * phys;
    int num_phys;
    bool reset_on_resume;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct ehci_platform_priv {
    struct clk *[4] clks;
    struct reset_control *[4] rsts;
    struct phy * * phys;
    int num_phys;
    bool reset_on_resume;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct ehci_platform_priv {
    struct clk *[4] clks;
    struct reset_control * rsts;
    struct phy * * phys;
    int num_phys;
    bool reset_on_resume;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct ehci_platform_priv {
    struct clk *[4] clks;
    struct reset_control * rsts;
    bool reset_on_resume;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct ehci_platform_priv {
    struct clk *[4] clks;
    struct reset_control * rsts;
    bool reset_on_resume;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct ehci_platform_priv {
    struct clk *[4] clks;
    struct reset_control * rsts;
    bool reset_on_resume;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct ehci_platform_priv {
    struct clk *[4] clks;
    struct reset_control * rsts;
    bool reset_on_resume;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct ehci_platform_priv {
    struct clk *[4] clks;
    struct reset_control * rsts;
    bool reset_on_resume;
    bool quirk_poll;
    struct timer_list poll_timer;
    struct delayed_work poll_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct ehci_platform_priv {
    struct clk *[4] clks;
    struct reset_control * rsts;
    bool reset_on_resume;
    bool quirk_poll;
    struct timer_list poll_timer;
    struct delayed_work poll_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct ehci_platform_priv {
    struct clk *[4] clks;
    struct reset_control * rsts;
    bool reset_on_resume;
    bool quirk_poll;
    struct timer_list poll_timer;
    struct delayed_work poll_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct ehci_platform_priv {
    struct clk *[4] clks;
    struct reset_control * rsts;
    bool reset_on_resume;
    bool quirk_poll;
    struct timer_list poll_timer;
    struct delayed_work poll_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct ehci_platform_priv {
    struct clk *[4] clks;
    struct reset_control * rsts;
    bool reset_on_resume;
    bool quirk_poll;
    struct timer_list poll_timer;
    struct delayed_work poll_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct ehci_platform_priv {
    struct clk *[4] clks;
    struct reset_control * rsts;
    bool reset_on_resume;
    bool quirk_poll;
    struct timer_list poll_timer;
    struct delayed_work poll_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct ehci_platform_priv {
    struct clk *[4] clks;
    struct reset_control * rsts;
    bool reset_on_resume;
    bool quirk_poll;
    struct timer_list poll_timer;
    struct delayed_work poll_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct ehci_platform_priv {
    struct clk *[4] clks;
    struct reset_control * rsts;
    bool reset_on_resume;
    bool quirk_poll;
    struct timer_list poll_timer;
    struct delayed_work poll_work;
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct ehci_platform_priv {
    struct clk *[4] clks;
    struct reset_control * rsts;
    bool reset_on_resume;
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
struct ehci_platform_priv {
    struct clk *[4] clks;
    struct reset_control * rsts;
    bool reset_on_resume;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct ehci_platform_priv {
    struct clk *[4] clks;
    struct reset_control * rsts;
    bool reset_on_resume;
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
<code>struct reset_control *[3] rsts</code>
</li>
<li>
<b>Field removed. </b>
<code>struct reset_control * rst</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>struct clk *[3] clks</code> ➡️ <code>struct clk *[4] clks</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct reset_control *[3] rsts</code> ➡️ <code>struct reset_control *[4] rsts</code>
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
<b>Field type changed. </b>
<code>struct reset_control *[4] rsts</code> ➡️ <code>struct reset_control * rsts</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>struct phy * * phys</code>
</li>
<li>
<b>Field removed. </b>
<code>int num_phys</code>
</li>
</ul>
</details>
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
<code>bool quirk_poll</code>
</li>
<li>
<b>Field added. </b>
<code>struct timer_list poll_timer</code>
</li>
<li>
<b>Field added. </b>
<code>struct delayed_work poll_work</code>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
struct ehci_platform_priv {
    struct clk *[4] clks;
    struct reset_control * rsts;
    bool reset_on_resume;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct ehci_platform_priv {
    struct clk *[4] clks;
    struct reset_control * rsts;
    bool reset_on_resume;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct ehci_platform_priv {
    struct clk *[4] clks;
    struct reset_control * rsts;
    bool reset_on_resume;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct ehci_platform_priv {
    struct clk *[4] clks;
    struct reset_control * rsts;
    bool reset_on_resume;
}
```
</details>
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
struct ehci_platform_priv {
    struct clk *[4] clks;
    struct reset_control * rsts;
    bool reset_on_resume;
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
