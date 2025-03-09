# Struct: <code>eeh_ops</code>

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
struct eeh_ops {
    char * name;
    int (*)() init;
    void * (*)(struct pci_dn *, void *) probe;
    int (*)(struct eeh_pe *, int) set_option;
    int (*)(struct eeh_pe *) get_pe_addr;
    int (*)(struct eeh_pe *, int *) get_state;
    int (*)(struct eeh_pe *, int) reset;
    int (*)(struct eeh_pe *, int, char *, long unsigned int) get_log;
    int (*)(struct eeh_pe *) configure_bridge;
    int (*)(struct eeh_pe *, int, int, long unsigned int, long unsigned int) err_inject;
    int (*)(struct pci_dn *, int, int, u32 *) read_config;
    int (*)(struct pci_dn *, int, int, u32) write_config;
    int (*)(struct eeh_pe * *) next_error;
    int (*)(struct pci_dn *) restore_config;
    int (*)(struct pci_dn *) notify_resume;
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
struct eeh_ops {
    char * name;
    int (*)() init;
    void * (*)(struct pci_dn *, void *) probe;
    int (*)(struct eeh_pe *, int) set_option;
    int (*)(struct eeh_pe *) get_pe_addr;
    int (*)(struct eeh_pe *, int *) get_state;
    int (*)(struct eeh_pe *, int) reset;
    int (*)(struct eeh_pe *, int, char *, long unsigned int) get_log;
    int (*)(struct eeh_pe *) configure_bridge;
    int (*)(struct eeh_pe *, int, int, long unsigned int, long unsigned int) err_inject;
    int (*)(struct pci_dn *, int, int, u32 *) read_config;
    int (*)(struct pci_dn *, int, int, u32) write_config;
    int (*)(struct eeh_pe * *) next_error;
    int (*)(struct pci_dn *) restore_config;
    int (*)(struct pci_dn *) notify_resume;
}
```
</details>
</li>
</ul>
