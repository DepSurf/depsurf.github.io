# Struct: <code>pcie_link_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct pcie_link_state {
    struct pci_dev * pdev;
    struct pcie_link_state * root;
    struct pcie_link_state * parent;
    struct list_head sibling;
    struct list_head children;
    struct list_head link;
    u32 aspm_support;
    u32 aspm_enabled;
    u32 aspm_capable;
    u32 aspm_default;
    u32 aspm_disable;
    u32 clkpm_capable;
    u32 clkpm_enabled;
    u32 clkpm_default;
    struct aspm_latency latency_up;
    struct aspm_latency latency_dw;
    struct aspm_latency[8] acceptable;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct pcie_link_state {
    struct pci_dev * pdev;
    struct pcie_link_state * root;
    struct pcie_link_state * parent;
    struct list_head sibling;
    struct list_head children;
    struct list_head link;
    u32 aspm_support;
    u32 aspm_enabled;
    u32 aspm_capable;
    u32 aspm_default;
    u32 aspm_disable;
    u32 clkpm_capable;
    u32 clkpm_enabled;
    u32 clkpm_default;
    struct aspm_latency latency_up;
    struct aspm_latency latency_dw;
    struct aspm_latency[8] acceptable;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct pcie_link_state {
    struct pci_dev * pdev;
    struct pcie_link_state * root;
    struct pcie_link_state * parent;
    struct list_head sibling;
    struct list_head children;
    struct list_head link;
    u32 aspm_support;
    u32 aspm_enabled;
    u32 aspm_capable;
    u32 aspm_default;
    u32 aspm_disable;
    u32 clkpm_capable;
    u32 clkpm_enabled;
    u32 clkpm_default;
    struct aspm_latency latency_up;
    struct aspm_latency latency_dw;
    struct aspm_latency[8] acceptable;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct pcie_link_state {
    struct pci_dev * pdev;
    struct pci_dev * downstream;
    struct pcie_link_state * root;
    struct pcie_link_state * parent;
    struct list_head sibling;
    struct list_head children;
    struct list_head link;
    u32 aspm_support;
    u32 aspm_enabled;
    u32 aspm_capable;
    u32 aspm_default;
    u32 aspm_disable;
    u32 clkpm_capable;
    u32 clkpm_enabled;
    u32 clkpm_default;
    struct aspm_latency latency_up;
    struct aspm_latency latency_dw;
    struct aspm_latency[8] acceptable;
    struct (anon) l1ss;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct pcie_link_state {
    struct pci_dev * pdev;
    struct pci_dev * downstream;
    struct pcie_link_state * root;
    struct pcie_link_state * parent;
    struct list_head sibling;
    struct list_head children;
    struct list_head link;
    u32 aspm_support;
    u32 aspm_enabled;
    u32 aspm_capable;
    u32 aspm_default;
    u32 aspm_disable;
    u32 clkpm_capable;
    u32 clkpm_enabled;
    u32 clkpm_default;
    struct aspm_latency latency_up;
    struct aspm_latency latency_dw;
    struct aspm_latency[8] acceptable;
    struct (anon) l1ss;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct pcie_link_state {
    struct pci_dev * pdev;
    struct pci_dev * downstream;
    struct pcie_link_state * root;
    struct pcie_link_state * parent;
    struct list_head sibling;
    struct list_head children;
    struct list_head link;
    u32 aspm_support;
    u32 aspm_enabled;
    u32 aspm_capable;
    u32 aspm_default;
    u32 aspm_disable;
    u32 clkpm_capable;
    u32 clkpm_enabled;
    u32 clkpm_default;
    struct aspm_latency latency_up;
    struct aspm_latency latency_dw;
    struct aspm_latency[8] acceptable;
    struct (anon) l1ss;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct pcie_link_state {
    struct pci_dev * pdev;
    struct pci_dev * downstream;
    struct pcie_link_state * root;
    struct pcie_link_state * parent;
    struct list_head sibling;
    u32 aspm_support;
    u32 aspm_enabled;
    u32 aspm_capable;
    u32 aspm_default;
    u32 aspm_disable;
    u32 clkpm_capable;
    u32 clkpm_enabled;
    u32 clkpm_default;
    struct aspm_latency latency_up;
    struct aspm_latency latency_dw;
    struct aspm_latency[8] acceptable;
    struct (anon) l1ss;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct pcie_link_state {
    struct pci_dev * pdev;
    struct pci_dev * downstream;
    struct pcie_link_state * root;
    struct pcie_link_state * parent;
    struct list_head sibling;
    u32 aspm_support;
    u32 aspm_enabled;
    u32 aspm_capable;
    u32 aspm_default;
    u32 aspm_disable;
    u32 clkpm_capable;
    u32 clkpm_enabled;
    u32 clkpm_default;
    struct aspm_latency latency_up;
    struct aspm_latency latency_dw;
    struct aspm_latency[8] acceptable;
    struct (anon) l1ss;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct pcie_link_state {
    struct pci_dev * pdev;
    struct pci_dev * downstream;
    struct pcie_link_state * root;
    struct pcie_link_state * parent;
    struct list_head sibling;
    u32 aspm_support;
    u32 aspm_enabled;
    u32 aspm_capable;
    u32 aspm_default;
    u32 aspm_disable;
    u32 clkpm_capable;
    u32 clkpm_enabled;
    u32 clkpm_default;
    u32 clkpm_disable;
    struct aspm_latency latency_up;
    struct aspm_latency latency_dw;
    struct aspm_latency[8] acceptable;
    struct (anon) l1ss;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct pcie_link_state {
    struct pci_dev * pdev;
    struct pci_dev * downstream;
    struct pcie_link_state * root;
    struct pcie_link_state * parent;
    struct list_head sibling;
    u32 aspm_support;
    u32 aspm_enabled;
    u32 aspm_capable;
    u32 aspm_default;
    u32 aspm_disable;
    u32 clkpm_capable;
    u32 clkpm_enabled;
    u32 clkpm_default;
    u32 clkpm_disable;
    struct aspm_latency latency_up;
    struct aspm_latency latency_dw;
    struct aspm_latency[8] acceptable;
    struct (anon) l1ss;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct pcie_link_state {
    struct pci_dev * pdev;
    struct pci_dev * downstream;
    struct pcie_link_state * root;
    struct pcie_link_state * parent;
    struct list_head sibling;
    u32 aspm_support;
    u32 aspm_enabled;
    u32 aspm_capable;
    u32 aspm_default;
    u32 aspm_disable;
    u32 clkpm_capable;
    u32 clkpm_enabled;
    u32 clkpm_default;
    u32 clkpm_disable;
    struct aspm_latency latency_up;
    struct aspm_latency latency_dw;
    struct aspm_latency[8] acceptable;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct pcie_link_state {
    struct pci_dev * pdev;
    struct pci_dev * downstream;
    struct pcie_link_state * root;
    struct pcie_link_state * parent;
    struct list_head sibling;
    u32 aspm_support;
    u32 aspm_enabled;
    u32 aspm_capable;
    u32 aspm_default;
    u32 aspm_disable;
    u32 clkpm_capable;
    u32 clkpm_enabled;
    u32 clkpm_default;
    u32 clkpm_disable;
    struct aspm_latency latency_up;
    struct aspm_latency latency_dw;
    struct aspm_latency[8] acceptable;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct pcie_link_state {
    struct pci_dev * pdev;
    struct pci_dev * downstream;
    struct pcie_link_state * root;
    struct pcie_link_state * parent;
    struct list_head sibling;
    u32 aspm_support;
    u32 aspm_enabled;
    u32 aspm_capable;
    u32 aspm_default;
    u32 aspm_disable;
    u32 clkpm_capable;
    u32 clkpm_enabled;
    u32 clkpm_default;
    u32 clkpm_disable;
    struct aspm_latency latency_up;
    struct aspm_latency latency_dw;
    struct aspm_latency[8] acceptable;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct pcie_link_state {
    struct pci_dev * pdev;
    struct pci_dev * downstream;
    struct pcie_link_state * root;
    struct pcie_link_state * parent;
    struct list_head sibling;
    u32 aspm_support;
    u32 aspm_enabled;
    u32 aspm_capable;
    u32 aspm_default;
    u32 aspm_disable;
    u32 clkpm_capable;
    u32 clkpm_enabled;
    u32 clkpm_default;
    u32 clkpm_disable;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct pcie_link_state {
    struct pci_dev * pdev;
    struct pci_dev * downstream;
    struct pcie_link_state * root;
    struct pcie_link_state * parent;
    struct list_head sibling;
    u32 aspm_support;
    u32 aspm_enabled;
    u32 aspm_capable;
    u32 aspm_default;
    u32 aspm_disable;
    u32 clkpm_capable;
    u32 clkpm_enabled;
    u32 clkpm_default;
    u32 clkpm_disable;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct pcie_link_state {
    struct pci_dev * pdev;
    struct pci_dev * downstream;
    struct pcie_link_state * root;
    struct pcie_link_state * parent;
    struct list_head sibling;
    u32 aspm_support;
    u32 aspm_enabled;
    u32 aspm_capable;
    u32 aspm_default;
    u32 aspm_disable;
    u32 clkpm_capable;
    u32 clkpm_enabled;
    u32 clkpm_default;
    u32 clkpm_disable;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct pcie_link_state {
    struct pci_dev * pdev;
    struct pci_dev * downstream;
    struct pcie_link_state * root;
    struct pcie_link_state * parent;
    struct list_head sibling;
    u32 aspm_support;
    u32 aspm_enabled;
    u32 aspm_capable;
    u32 aspm_default;
    u32 aspm_disable;
    u32 clkpm_capable;
    u32 clkpm_enabled;
    u32 clkpm_default;
    u32 clkpm_disable;
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
struct pcie_link_state {
    struct pci_dev * pdev;
    struct pci_dev * downstream;
    struct pcie_link_state * root;
    struct pcie_link_state * parent;
    struct list_head sibling;
    u32 aspm_support;
    u32 aspm_enabled;
    u32 aspm_capable;
    u32 aspm_default;
    u32 aspm_disable;
    u32 clkpm_capable;
    u32 clkpm_enabled;
    u32 clkpm_default;
    u32 clkpm_disable;
    struct aspm_latency latency_up;
    struct aspm_latency latency_dw;
    struct aspm_latency[8] acceptable;
    struct (anon) l1ss;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct pcie_link_state {
    struct pci_dev * pdev;
    struct pci_dev * downstream;
    struct pcie_link_state * root;
    struct pcie_link_state * parent;
    struct list_head sibling;
    u32 aspm_support;
    u32 aspm_enabled;
    u32 aspm_capable;
    u32 aspm_default;
    u32 aspm_disable;
    u32 clkpm_capable;
    u32 clkpm_enabled;
    u32 clkpm_default;
    u32 clkpm_disable;
    struct aspm_latency latency_up;
    struct aspm_latency latency_dw;
    struct aspm_latency[8] acceptable;
    struct (anon) l1ss;
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct pcie_link_state {
    struct pci_dev * pdev;
    struct pci_dev * downstream;
    struct pcie_link_state * root;
    struct pcie_link_state * parent;
    struct list_head sibling;
    u32 aspm_support;
    u32 aspm_enabled;
    u32 aspm_capable;
    u32 aspm_default;
    u32 aspm_disable;
    u32 clkpm_capable;
    u32 clkpm_enabled;
    u32 clkpm_default;
    u32 clkpm_disable;
    struct aspm_latency latency_up;
    struct aspm_latency latency_dw;
    struct aspm_latency[8] acceptable;
    struct (anon) l1ss;
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
struct pcie_link_state {
    struct pci_dev * pdev;
    struct pci_dev * downstream;
    struct pcie_link_state * root;
    struct pcie_link_state * parent;
    struct list_head sibling;
    u32 aspm_support;
    u32 aspm_enabled;
    u32 aspm_capable;
    u32 aspm_default;
    u32 aspm_disable;
    u32 clkpm_capable;
    u32 clkpm_enabled;
    u32 clkpm_default;
    u32 clkpm_disable;
    struct aspm_latency latency_up;
    struct aspm_latency latency_dw;
    struct aspm_latency[8] acceptable;
    struct (anon) l1ss;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct pcie_link_state {
    struct pci_dev * pdev;
    struct pci_dev * downstream;
    struct pcie_link_state * root;
    struct pcie_link_state * parent;
    struct list_head sibling;
    u32 aspm_support;
    u32 aspm_enabled;
    u32 aspm_capable;
    u32 aspm_default;
    u32 aspm_disable;
    u32 clkpm_capable;
    u32 clkpm_enabled;
    u32 clkpm_default;
    u32 clkpm_disable;
    struct aspm_latency latency_up;
    struct aspm_latency latency_dw;
    struct aspm_latency[8] acceptable;
    struct (anon) l1ss;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct pcie_link_state {
    struct pci_dev * pdev;
    struct pci_dev * downstream;
    struct pcie_link_state * root;
    struct pcie_link_state * parent;
    struct list_head sibling;
    u32 aspm_support;
    u32 aspm_enabled;
    u32 aspm_capable;
    u32 aspm_default;
    u32 aspm_disable;
    u32 clkpm_capable;
    u32 clkpm_enabled;
    u32 clkpm_default;
    u32 clkpm_disable;
    struct aspm_latency latency_up;
    struct aspm_latency latency_dw;
    struct aspm_latency[8] acceptable;
    struct (anon) l1ss;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct pcie_link_state {
    struct pci_dev * pdev;
    struct pci_dev * downstream;
    struct pcie_link_state * root;
    struct pcie_link_state * parent;
    struct list_head sibling;
    u32 aspm_support;
    u32 aspm_enabled;
    u32 aspm_capable;
    u32 aspm_default;
    u32 aspm_disable;
    u32 clkpm_capable;
    u32 clkpm_enabled;
    u32 clkpm_default;
    u32 clkpm_disable;
    struct aspm_latency latency_up;
    struct aspm_latency latency_dw;
    struct aspm_latency[8] acceptable;
    struct (anon) l1ss;
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
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
<code>struct pci_dev * downstream</code>
</li>
<li>
<b>Field added. </b>
<code>struct (anon) l1ss</code>
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>struct list_head children</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head link</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u32 clkpm_disable</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>struct (anon) l1ss</code>
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>struct aspm_latency latency_up</code>
</li>
<li>
<b>Field removed. </b>
<code>struct aspm_latency latency_dw</code>
</li>
<li>
<b>Field removed. </b>
<code>struct aspm_latency[8] acceptable</code>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct pcie_link_state {
    struct pci_dev * pdev;
    struct pci_dev * downstream;
    struct pcie_link_state * root;
    struct pcie_link_state * parent;
    struct list_head sibling;
    u32 aspm_support;
    u32 aspm_enabled;
    u32 aspm_capable;
    u32 aspm_default;
    u32 aspm_disable;
    u32 clkpm_capable;
    u32 clkpm_enabled;
    u32 clkpm_default;
    u32 clkpm_disable;
    struct aspm_latency latency_up;
    struct aspm_latency latency_dw;
    struct aspm_latency[8] acceptable;
    struct (anon) l1ss;
}
```
</details>
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
