# Struct: <code>phylink_link_state</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct phylink_link_state {
    long unsigned int[2] advertising;
    long unsigned int[2] lp_advertising;
    phy_interface_t interface;
    int speed;
    int duplex;
    int pause;
    unsigned int link;
    unsigned int an_enabled;
    unsigned int an_complete;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct phylink_link_state {
    long unsigned int[2] advertising;
    long unsigned int[2] lp_advertising;
    phy_interface_t interface;
    int speed;
    int duplex;
    int pause;
    unsigned int link;
    unsigned int an_enabled;
    unsigned int an_complete;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct phylink_link_state {
    long unsigned int[2] advertising;
    long unsigned int[2] lp_advertising;
    phy_interface_t interface;
    int speed;
    int duplex;
    int pause;
    unsigned int link;
    unsigned int an_enabled;
    unsigned int an_complete;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct phylink_link_state {
    long unsigned int[2] advertising;
    long unsigned int[2] lp_advertising;
    phy_interface_t interface;
    int speed;
    int duplex;
    int pause;
    unsigned int link;
    unsigned int an_enabled;
    unsigned int an_complete;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct phylink_link_state {
    long unsigned int[2] advertising;
    long unsigned int[2] lp_advertising;
    phy_interface_t interface;
    int speed;
    int duplex;
    int pause;
    unsigned int link;
    unsigned int an_enabled;
    unsigned int an_complete;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct phylink_link_state {
    long unsigned int[2] advertising;
    long unsigned int[2] lp_advertising;
    phy_interface_t interface;
    int speed;
    int duplex;
    int pause;
    unsigned int link;
    unsigned int an_enabled;
    unsigned int an_complete;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct phylink_link_state {
    long unsigned int[2] advertising;
    long unsigned int[2] lp_advertising;
    phy_interface_t interface;
    int speed;
    int duplex;
    int pause;
    unsigned int link;
    unsigned int an_enabled;
    unsigned int an_complete;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct phylink_link_state {
    long unsigned int[2] advertising;
    long unsigned int[2] lp_advertising;
    phy_interface_t interface;
    int speed;
    int duplex;
    int pause;
    int rate_matching;
    unsigned int link;
    unsigned int an_enabled;
    unsigned int an_complete;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct phylink_link_state {
    long unsigned int[2] advertising;
    long unsigned int[2] lp_advertising;
    phy_interface_t interface;
    int speed;
    int duplex;
    int pause;
    int rate_matching;
    unsigned int link;
    unsigned int an_complete;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct phylink_link_state {
    long unsigned int[2] advertising;
    long unsigned int[2] lp_advertising;
    phy_interface_t interface;
    int speed;
    int duplex;
    int pause;
    int rate_matching;
    unsigned int link;
    unsigned int an_complete;
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
struct phylink_link_state {
    long unsigned int[2] advertising;
    long unsigned int[2] lp_advertising;
    phy_interface_t interface;
    int speed;
    int duplex;
    int pause;
    unsigned int link;
    unsigned int an_enabled;
    unsigned int an_complete;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct phylink_link_state {
    long unsigned int[3] advertising;
    long unsigned int[3] lp_advertising;
    phy_interface_t interface;
    int speed;
    int duplex;
    int pause;
    unsigned int link;
    unsigned int an_enabled;
    unsigned int an_complete;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct phylink_link_state {
    long unsigned int[2] advertising;
    long unsigned int[2] lp_advertising;
    phy_interface_t interface;
    int speed;
    int duplex;
    int pause;
    unsigned int link;
    unsigned int an_enabled;
    unsigned int an_complete;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct phylink_link_state {
    long unsigned int[2] advertising;
    long unsigned int[2] lp_advertising;
    phy_interface_t interface;
    int speed;
    int duplex;
    int pause;
    unsigned int link;
    unsigned int an_enabled;
    unsigned int an_complete;
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
struct phylink_link_state {
    long unsigned int[2] advertising;
    long unsigned int[2] lp_advertising;
    phy_interface_t interface;
    int speed;
    int duplex;
    int pause;
    unsigned int link;
    unsigned int an_enabled;
    unsigned int an_complete;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct phylink_link_state {
    long unsigned int[2] advertising;
    long unsigned int[2] lp_advertising;
    phy_interface_t interface;
    int speed;
    int duplex;
    int pause;
    unsigned int link;
    unsigned int an_enabled;
    unsigned int an_complete;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct phylink_link_state {
    long unsigned int[2] advertising;
    long unsigned int[2] lp_advertising;
    phy_interface_t interface;
    int speed;
    int duplex;
    int pause;
    unsigned int link;
    unsigned int an_enabled;
    unsigned int an_complete;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct phylink_link_state {
    long unsigned int[2] advertising;
    long unsigned int[2] lp_advertising;
    phy_interface_t interface;
    int speed;
    int duplex;
    int pause;
    unsigned int link;
    unsigned int an_enabled;
    unsigned int an_complete;
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
struct phylink_link_state {
    long unsigned int[2] advertising;
    long unsigned int[2] lp_advertising;
    phy_interface_t interface;
    int speed;
    int duplex;
    int pause;
    unsigned int link;
    unsigned int an_enabled;
    unsigned int an_complete;
}
```
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
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int rate_matching</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>unsigned int an_enabled</code>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>long unsigned int[2] advertising</code> ➡️ <code>long unsigned int[3] advertising</code>
</li>
<li>
<b>Field type changed. </b>
<code>long unsigned int[2] lp_advertising</code> ➡️ <code>long unsigned int[3] lp_advertising</code>
</li>
</ul>
</details>
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
