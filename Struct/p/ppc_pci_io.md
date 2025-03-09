# Struct: <code>ppc_pci_io</code>

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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct ppc_pci_io {
    u8 (*)(volatile const void *) readb;
    u16 (*)(volatile const void *) readw;
    u32 (*)(volatile const void *) readl;
    u16 (*)(volatile const void *) readw_be;
    u32 (*)(volatile const void *) readl_be;
    void (*)(u8, volatile void *) writeb;
    void (*)(u16, volatile void *) writew;
    void (*)(u32, volatile void *) writel;
    void (*)(u16, volatile void *) writew_be;
    void (*)(u32, volatile void *) writel_be;
    u64 (*)(volatile const void *) readq;
    u64 (*)(volatile const void *) readq_be;
    void (*)(u64, volatile void *) writeq;
    void (*)(u64, volatile void *) writeq_be;
    u8 (*)(long unsigned int) inb;
    u16 (*)(long unsigned int) inw;
    u32 (*)(long unsigned int) inl;
    void (*)(u8, long unsigned int) outb;
    void (*)(u16, long unsigned int) outw;
    void (*)(u32, long unsigned int) outl;
    void (*)(volatile const void *, void *, long unsigned int) readsb;
    void (*)(volatile const void *, void *, long unsigned int) readsw;
    void (*)(volatile const void *, void *, long unsigned int) readsl;
    void (*)(volatile void *, const void *, long unsigned int) writesb;
    void (*)(volatile void *, const void *, long unsigned int) writesw;
    void (*)(volatile void *, const void *, long unsigned int) writesl;
    void (*)(long unsigned int, void *, long unsigned int) insb;
    void (*)(long unsigned int, void *, long unsigned int) insw;
    void (*)(long unsigned int, void *, long unsigned int) insl;
    void (*)(long unsigned int, const void *, long unsigned int) outsb;
    void (*)(long unsigned int, const void *, long unsigned int) outsw;
    void (*)(long unsigned int, const void *, long unsigned int) outsl;
    void (*)(volatile void *, int, long unsigned int) memset_io;
    void (*)(void *, volatile const void *, long unsigned int) memcpy_fromio;
    void (*)(volatile void *, const void *, long unsigned int) memcpy_toio;
}
```
</details>
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
struct ppc_pci_io {
    u8 (*)(volatile const void *) readb;
    u16 (*)(volatile const void *) readw;
    u32 (*)(volatile const void *) readl;
    u16 (*)(volatile const void *) readw_be;
    u32 (*)(volatile const void *) readl_be;
    void (*)(u8, volatile void *) writeb;
    void (*)(u16, volatile void *) writew;
    void (*)(u32, volatile void *) writel;
    void (*)(u16, volatile void *) writew_be;
    void (*)(u32, volatile void *) writel_be;
    u64 (*)(volatile const void *) readq;
    u64 (*)(volatile const void *) readq_be;
    void (*)(u64, volatile void *) writeq;
    void (*)(u64, volatile void *) writeq_be;
    u8 (*)(long unsigned int) inb;
    u16 (*)(long unsigned int) inw;
    u32 (*)(long unsigned int) inl;
    void (*)(u8, long unsigned int) outb;
    void (*)(u16, long unsigned int) outw;
    void (*)(u32, long unsigned int) outl;
    void (*)(volatile const void *, void *, long unsigned int) readsb;
    void (*)(volatile const void *, void *, long unsigned int) readsw;
    void (*)(volatile const void *, void *, long unsigned int) readsl;
    void (*)(volatile void *, const void *, long unsigned int) writesb;
    void (*)(volatile void *, const void *, long unsigned int) writesw;
    void (*)(volatile void *, const void *, long unsigned int) writesl;
    void (*)(long unsigned int, void *, long unsigned int) insb;
    void (*)(long unsigned int, void *, long unsigned int) insw;
    void (*)(long unsigned int, void *, long unsigned int) insl;
    void (*)(long unsigned int, const void *, long unsigned int) outsb;
    void (*)(long unsigned int, const void *, long unsigned int) outsw;
    void (*)(long unsigned int, const void *, long unsigned int) outsl;
    void (*)(volatile void *, int, long unsigned int) memset_io;
    void (*)(void *, volatile const void *, long unsigned int) memcpy_fromio;
    void (*)(volatile void *, const void *, long unsigned int) memcpy_toio;
}
```
</details>
</li>
</ul>
