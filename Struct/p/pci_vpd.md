# Struct: <code>pci_vpd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct pci_vpd {
    unsigned int len;
    const struct pci_vpd_ops * ops;
    struct bin_attribute * attr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct pci_vpd {
    const struct pci_vpd_ops * ops;
    struct bin_attribute * attr;
    struct mutex lock;
    unsigned int len;
    u16 flag;
    u8 cap;
    u8 busy;
    u8 valid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct pci_vpd {
    const struct pci_vpd_ops * ops;
    struct bin_attribute * attr;
    struct mutex lock;
    unsigned int len;
    u16 flag;
    u8 cap;
    u8 busy;
    u8 valid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct pci_vpd {
    const struct pci_vpd_ops * ops;
    struct bin_attribute * attr;
    struct mutex lock;
    unsigned int len;
    u16 flag;
    u8 cap;
    u8 busy;
    u8 valid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct pci_vpd {
    const struct pci_vpd_ops * ops;
    struct bin_attribute * attr;
    struct mutex lock;
    unsigned int len;
    u16 flag;
    u8 cap;
    u8 busy;
    u8 valid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct pci_vpd {
    const struct pci_vpd_ops * ops;
    struct bin_attribute * attr;
    struct mutex lock;
    unsigned int len;
    u16 flag;
    u8 cap;
    unsigned int busy;
    unsigned int valid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct pci_vpd {
    const struct pci_vpd_ops * ops;
    struct bin_attribute * attr;
    struct mutex lock;
    unsigned int len;
    u16 flag;
    u8 cap;
    unsigned int busy;
    unsigned int valid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct pci_vpd {
    const struct pci_vpd_ops * ops;
    struct bin_attribute * attr;
    struct mutex lock;
    unsigned int len;
    u16 flag;
    u8 cap;
    unsigned int busy;
    unsigned int valid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct pci_vpd {
    const struct pci_vpd_ops * ops;
    struct bin_attribute * attr;
    struct mutex lock;
    unsigned int len;
    u16 flag;
    u8 cap;
    unsigned int busy;
    unsigned int valid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct pci_vpd {
    const struct pci_vpd_ops * ops;
    struct bin_attribute * attr;
    struct mutex lock;
    unsigned int len;
    u16 flag;
    u8 cap;
    unsigned int busy;
    unsigned int valid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct pci_vpd {
    const struct pci_vpd_ops * ops;
    struct bin_attribute * attr;
    struct mutex lock;
    unsigned int len;
    u16 flag;
    u8 cap;
    unsigned int busy;
    unsigned int valid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct pci_vpd {
    const struct pci_vpd_ops * ops;
    struct mutex lock;
    unsigned int len;
    u16 flag;
    u8 cap;
    unsigned int busy;
    unsigned int valid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct pci_vpd {
    struct mutex lock;
    unsigned int len;
    u8 cap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct pci_vpd {
    struct mutex lock;
    unsigned int len;
    u8 cap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct pci_vpd {
    struct mutex lock;
    unsigned int len;
    u8 cap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct pci_vpd {
    struct mutex lock;
    unsigned int len;
    u8 cap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct pci_vpd {
    struct mutex lock;
    unsigned int len;
    u8 cap;
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
struct pci_vpd {
    const struct pci_vpd_ops * ops;
    struct bin_attribute * attr;
    struct mutex lock;
    unsigned int len;
    u16 flag;
    u8 cap;
    unsigned int busy;
    unsigned int valid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct pci_vpd {
    const struct pci_vpd_ops * ops;
    struct bin_attribute * attr;
    struct mutex lock;
    unsigned int len;
    u16 flag;
    u8 cap;
    unsigned int busy;
    unsigned int valid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct pci_vpd {
    const struct pci_vpd_ops * ops;
    struct bin_attribute * attr;
    struct mutex lock;
    unsigned int len;
    u16 flag;
    u8 cap;
    unsigned int busy;
    unsigned int valid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct pci_vpd {
    const struct pci_vpd_ops * ops;
    struct bin_attribute * attr;
    struct mutex lock;
    unsigned int len;
    u16 flag;
    u8 cap;
    unsigned int busy;
    unsigned int valid;
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
struct pci_vpd {
    const struct pci_vpd_ops * ops;
    struct bin_attribute * attr;
    struct mutex lock;
    unsigned int len;
    u16 flag;
    u8 cap;
    unsigned int busy;
    unsigned int valid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct pci_vpd {
    const struct pci_vpd_ops * ops;
    struct bin_attribute * attr;
    struct mutex lock;
    unsigned int len;
    u16 flag;
    u8 cap;
    unsigned int busy;
    unsigned int valid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct pci_vpd {
    const struct pci_vpd_ops * ops;
    struct bin_attribute * attr;
    struct mutex lock;
    unsigned int len;
    u16 flag;
    u8 cap;
    unsigned int busy;
    unsigned int valid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct pci_vpd {
    const struct pci_vpd_ops * ops;
    struct bin_attribute * attr;
    struct mutex lock;
    unsigned int len;
    u16 flag;
    u8 cap;
    unsigned int busy;
    unsigned int valid;
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
<code>struct mutex lock</code>
</li>
<li>
<b>Field added. </b>
<code>u16 flag</code>
</li>
<li>
<b>Field added. </b>
<code>u8 cap</code>
</li>
<li>
<b>Field added. </b>
<code>u8 busy</code>
</li>
<li>
<b>Field added. </b>
<code>u8 valid</code>
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
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>u8 busy</code> ➡️ <code>unsigned int busy</code>
</li>
<li>
<b>Field type changed. </b>
<code>u8 valid</code> ➡️ <code>unsigned int valid</code>
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
<b>Field removed. </b>
<code>struct bin_attribute * attr</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>const struct pci_vpd_ops * ops</code>
</li>
<li>
<b>Field removed. </b>
<code>u16 flag</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int busy</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int valid</code>
</li>
</ul>
</details>
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
