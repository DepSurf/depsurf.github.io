# Struct: <code>mmci_host_ops</code>

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
struct mmci_host_ops {
    int (*)(struct mmci_host *, struct mmc_data *) validate_data;
    int (*)(struct mmci_host *, struct mmc_data *, bool) prep_data;
    void (*)(struct mmci_host *, struct mmc_data *, int) unprep_data;
    u32 (*)(struct mmci_host *) get_datactrl_cfg;
    void (*)(struct mmci_host *, struct mmc_data *) get_next_data;
    int (*)(struct mmci_host *) dma_setup;
    void (*)(struct mmci_host *) dma_release;
    int (*)(struct mmci_host *, unsigned int *) dma_start;
    void (*)(struct mmci_host *, struct mmc_data *) dma_finalize;
    void (*)(struct mmci_host *) dma_error;
    void (*)(struct mmci_host *, unsigned int) set_clkreg;
    void (*)(struct mmci_host *, unsigned int) set_pwrreg;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct mmci_host_ops {
    int (*)(struct mmci_host *, struct mmc_data *) validate_data;
    int (*)(struct mmci_host *, struct mmc_data *, bool) prep_data;
    void (*)(struct mmci_host *, struct mmc_data *, int) unprep_data;
    u32 (*)(struct mmci_host *) get_datactrl_cfg;
    void (*)(struct mmci_host *, struct mmc_data *) get_next_data;
    int (*)(struct mmci_host *) dma_setup;
    void (*)(struct mmci_host *) dma_release;
    int (*)(struct mmci_host *, unsigned int *) dma_start;
    void (*)(struct mmci_host *, struct mmc_data *) dma_finalize;
    void (*)(struct mmci_host *) dma_error;
    void (*)(struct mmci_host *, unsigned int) set_clkreg;
    void (*)(struct mmci_host *, unsigned int) set_pwrreg;
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
struct mmci_host_ops {
    int (*)(struct mmci_host *, struct mmc_data *) validate_data;
    int (*)(struct mmci_host *, struct mmc_data *, bool) prep_data;
    void (*)(struct mmci_host *, struct mmc_data *, int) unprep_data;
    u32 (*)(struct mmci_host *) get_datactrl_cfg;
    void (*)(struct mmci_host *, struct mmc_data *) get_next_data;
    int (*)(struct mmci_host *) dma_setup;
    void (*)(struct mmci_host *) dma_release;
    int (*)(struct mmci_host *, unsigned int *) dma_start;
    void (*)(struct mmci_host *, struct mmc_data *) dma_finalize;
    void (*)(struct mmci_host *) dma_error;
    void (*)(struct mmci_host *, unsigned int) set_clkreg;
    void (*)(struct mmci_host *, unsigned int) set_pwrreg;
}
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
struct mmci_host_ops {
    int (*)(struct mmci_host *, struct mmc_data *) validate_data;
    int (*)(struct mmci_host *, struct mmc_data *, bool) prep_data;
    void (*)(struct mmci_host *, struct mmc_data *, int) unprep_data;
    u32 (*)(struct mmci_host *) get_datactrl_cfg;
    void (*)(struct mmci_host *, struct mmc_data *) get_next_data;
    int (*)(struct mmci_host *) dma_setup;
    void (*)(struct mmci_host *) dma_release;
    int (*)(struct mmci_host *, unsigned int *) dma_start;
    void (*)(struct mmci_host *, struct mmc_data *) dma_finalize;
    void (*)(struct mmci_host *) dma_error;
    void (*)(struct mmci_host *, unsigned int) set_clkreg;
    void (*)(struct mmci_host *, unsigned int) set_pwrreg;
}
```
</details>
</li>
</ul>
