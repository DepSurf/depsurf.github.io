# Struct: <code>mpc8xxx_spi</code>

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
struct mpc8xxx_spi {
    struct device * dev;
    void * reg_base;
    const void * tx;
    void * rx;
    int subblock;
    struct spi_pram * pram;
    struct spi_transfer * xfer_in_progress;
    dma_addr_t tx_dma;
    dma_addr_t rx_dma;
    bool map_tx_dma;
    bool map_rx_dma;
    dma_addr_t dma_dummy_tx;
    dma_addr_t dma_dummy_rx;
    void (*)(u32, struct mpc8xxx_spi *) get_rx;
    u32 (*)(struct mpc8xxx_spi *) get_tx;
    unsigned int count;
    unsigned int irq;
    unsigned int nsecs;
    u32 spibrg;
    u32 rx_shift;
    u32 tx_shift;
    unsigned int flags;
    int type;
    int native_chipselects;
    u8 max_bits_per_word;
    void (*)(u32 *, u32 *, int, int) set_shifts;
    struct completion done;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct mpc8xxx_spi {
    struct device * dev;
    void * reg_base;
    const void * tx;
    void * rx;
    int subblock;
    struct spi_pram * pram;
    struct spi_transfer * xfer_in_progress;
    dma_addr_t tx_dma;
    dma_addr_t rx_dma;
    bool map_tx_dma;
    bool map_rx_dma;
    dma_addr_t dma_dummy_tx;
    dma_addr_t dma_dummy_rx;
    void (*)(u32, struct mpc8xxx_spi *) get_rx;
    u32 (*)(struct mpc8xxx_spi *) get_tx;
    unsigned int count;
    unsigned int irq;
    unsigned int nsecs;
    u32 spibrg;
    u32 rx_shift;
    u32 tx_shift;
    unsigned int flags;
    int type;
    int native_chipselects;
    u8 max_bits_per_word;
    void (*)(u32 *, u32 *, int, int) set_shifts;
    struct completion done;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct mpc8xxx_spi {
    struct device * dev;
    void * reg_base;
    const void * tx;
    void * rx;
    int subblock;
    struct spi_pram * pram;
    struct spi_transfer * xfer_in_progress;
    dma_addr_t tx_dma;
    dma_addr_t rx_dma;
    bool map_tx_dma;
    bool map_rx_dma;
    dma_addr_t dma_dummy_tx;
    dma_addr_t dma_dummy_rx;
    void (*)(u32, struct mpc8xxx_spi *) get_rx;
    u32 (*)(struct mpc8xxx_spi *) get_tx;
    unsigned int count;
    unsigned int irq;
    unsigned int nsecs;
    u32 spibrg;
    u32 rx_shift;
    u32 tx_shift;
    unsigned int flags;
    int type;
    int native_chipselects;
    u8 max_bits_per_word;
    void (*)(u32 *, u32 *, int, int) set_shifts;
    struct completion done;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct mpc8xxx_spi {
    struct device * dev;
    void * reg_base;
    const void * tx;
    void * rx;
    int subblock;
    struct spi_pram * pram;
    struct spi_transfer * xfer_in_progress;
    dma_addr_t tx_dma;
    dma_addr_t rx_dma;
    bool map_tx_dma;
    bool map_rx_dma;
    dma_addr_t dma_dummy_tx;
    dma_addr_t dma_dummy_rx;
    void (*)(u32, struct mpc8xxx_spi *) get_rx;
    u32 (*)(struct mpc8xxx_spi *) get_tx;
    unsigned int count;
    unsigned int irq;
    unsigned int nsecs;
    u32 spibrg;
    u32 rx_shift;
    u32 tx_shift;
    unsigned int flags;
    int type;
    int native_chipselects;
    u8 max_bits_per_word;
    void (*)(u32 *, u32 *, int, int) set_shifts;
    struct completion done;
}
```
</details>
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
struct mpc8xxx_spi {
    struct device * dev;
    void * reg_base;
    const void * tx;
    void * rx;
    int subblock;
    struct spi_pram * pram;
    struct spi_transfer * xfer_in_progress;
    dma_addr_t tx_dma;
    dma_addr_t rx_dma;
    bool map_tx_dma;
    bool map_rx_dma;
    dma_addr_t dma_dummy_tx;
    dma_addr_t dma_dummy_rx;
    void (*)(u32, struct mpc8xxx_spi *) get_rx;
    u32 (*)(struct mpc8xxx_spi *) get_tx;
    unsigned int count;
    unsigned int irq;
    unsigned int nsecs;
    u32 spibrg;
    u32 rx_shift;
    u32 tx_shift;
    unsigned int flags;
    int type;
    int native_chipselects;
    u8 max_bits_per_word;
    void (*)(u32 *, u32 *, int, int) set_shifts;
    struct completion done;
}
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
struct mpc8xxx_spi {
    struct device * dev;
    void * reg_base;
    const void * tx;
    void * rx;
    int subblock;
    struct spi_pram * pram;
    struct spi_transfer * xfer_in_progress;
    dma_addr_t tx_dma;
    dma_addr_t rx_dma;
    bool map_tx_dma;
    bool map_rx_dma;
    dma_addr_t dma_dummy_tx;
    dma_addr_t dma_dummy_rx;
    void (*)(u32, struct mpc8xxx_spi *) get_rx;
    u32 (*)(struct mpc8xxx_spi *) get_tx;
    unsigned int count;
    unsigned int irq;
    unsigned int nsecs;
    u32 spibrg;
    u32 rx_shift;
    u32 tx_shift;
    unsigned int flags;
    int type;
    int native_chipselects;
    u8 max_bits_per_word;
    void (*)(u32 *, u32 *, int, int) set_shifts;
    struct completion done;
}
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
struct mpc8xxx_spi {
    struct device * dev;
    void * reg_base;
    const void * tx;
    void * rx;
    int subblock;
    struct spi_pram * pram;
    struct spi_transfer * xfer_in_progress;
    dma_addr_t tx_dma;
    dma_addr_t rx_dma;
    bool map_tx_dma;
    bool map_rx_dma;
    dma_addr_t dma_dummy_tx;
    dma_addr_t dma_dummy_rx;
    void (*)(u32, struct mpc8xxx_spi *) get_rx;
    u32 (*)(struct mpc8xxx_spi *) get_tx;
    unsigned int count;
    unsigned int irq;
    unsigned int nsecs;
    u32 spibrg;
    u32 rx_shift;
    u32 tx_shift;
    unsigned int flags;
    int type;
    int native_chipselects;
    u8 max_bits_per_word;
    void (*)(u32 *, u32 *, int, int) set_shifts;
    struct completion done;
}
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
struct mpc8xxx_spi {
    struct device * dev;
    void * reg_base;
    const void * tx;
    void * rx;
    int subblock;
    struct spi_pram * pram;
    struct spi_transfer * xfer_in_progress;
    dma_addr_t tx_dma;
    dma_addr_t rx_dma;
    bool map_tx_dma;
    bool map_rx_dma;
    dma_addr_t dma_dummy_tx;
    dma_addr_t dma_dummy_rx;
    void (*)(u32, struct mpc8xxx_spi *) get_rx;
    u32 (*)(struct mpc8xxx_spi *) get_tx;
    unsigned int count;
    unsigned int irq;
    unsigned int nsecs;
    u32 spibrg;
    u32 rx_shift;
    u32 tx_shift;
    unsigned int flags;
    int type;
    int native_chipselects;
    u8 max_bits_per_word;
    void (*)(u32 *, u32 *, int, int) set_shifts;
    struct completion done;
}
```
</details>
</li>
</ul>
