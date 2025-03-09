# Struct: <code>pci_bridge_emul_pcie_conf</code>

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
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct pci_bridge_emul_pcie_conf {
    u8 cap_id;
    u8 next;
    u16 cap;
    u32 devcap;
    u16 devctl;
    u16 devsta;
    u32 lnkcap;
    u16 lnkctl;
    u16 lnksta;
    u32 slotcap;
    u16 slotctl;
    u16 slotsta;
    u16 rootctl;
    u16 rsvd;
    u32 rootsta;
    u32 devcap2;
    u16 devctl2;
    u16 devsta2;
    u32 lnkcap2;
    u16 lnkctl2;
    u16 lnksta2;
    u32 slotcap2;
    u16 slotctl2;
    u16 slotsta2;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct pci_bridge_emul_pcie_conf {
    u8 cap_id;
    u8 next;
    u16 cap;
    u32 devcap;
    u16 devctl;
    u16 devsta;
    u32 lnkcap;
    u16 lnkctl;
    u16 lnksta;
    u32 slotcap;
    u16 slotctl;
    u16 slotsta;
    u16 rootctl;
    u16 rsvd;
    u32 rootsta;
    u32 devcap2;
    u16 devctl2;
    u16 devsta2;
    u32 lnkcap2;
    u16 lnkctl2;
    u16 lnksta2;
    u32 slotcap2;
    u16 slotctl2;
    u16 slotsta2;
}
```
</details>
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
struct pci_bridge_emul_pcie_conf {
    u8 cap_id;
    u8 next;
    u16 cap;
    u32 devcap;
    u16 devctl;
    u16 devsta;
    u32 lnkcap;
    u16 lnkctl;
    u16 lnksta;
    u32 slotcap;
    u16 slotctl;
    u16 slotsta;
    u16 rootctl;
    u16 rsvd;
    u32 rootsta;
    u32 devcap2;
    u16 devctl2;
    u16 devsta2;
    u32 lnkcap2;
    u16 lnkctl2;
    u16 lnksta2;
    u32 slotcap2;
    u16 slotctl2;
    u16 slotsta2;
}
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
struct pci_bridge_emul_pcie_conf {
    u8 cap_id;
    u8 next;
    u16 cap;
    u32 devcap;
    u16 devctl;
    u16 devsta;
    u32 lnkcap;
    u16 lnkctl;
    u16 lnksta;
    u32 slotcap;
    u16 slotctl;
    u16 slotsta;
    u16 rootctl;
    u16 rsvd;
    u32 rootsta;
    u32 devcap2;
    u16 devctl2;
    u16 devsta2;
    u32 lnkcap2;
    u16 lnkctl2;
    u16 lnksta2;
    u32 slotcap2;
    u16 slotctl2;
    u16 slotsta2;
}
```
</details>
</li>
</ul>
