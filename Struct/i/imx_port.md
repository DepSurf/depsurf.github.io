# Struct: <code>imx_port</code>

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
struct imx_port {
    struct uart_port port;
    struct timer_list timer;
    unsigned int old_status;
    unsigned int have_rtscts;
    unsigned int have_rtsgpio;
    unsigned int dte_mode;
    struct clk * clk_ipg;
    struct clk * clk_per;
    const struct imx_uart_data * devdata;
    struct mctrl_gpios * gpios;
    unsigned int ucr1;
    unsigned int ucr2;
    unsigned int ucr3;
    unsigned int ucr4;
    unsigned int ufcr;
    unsigned int dma_is_enabled;
    unsigned int dma_is_rxing;
    unsigned int dma_is_txing;
    struct dma_chan * dma_chan_rx;
    struct dma_chan * dma_chan_tx;
    struct scatterlist rx_sgl;
    struct scatterlist[2] tx_sgl;
    void * rx_buf;
    struct circ_buf rx_ring;
    unsigned int rx_periods;
    dma_cookie_t rx_cookie;
    unsigned int tx_bytes;
    unsigned int dma_tx_nents;
    unsigned int[10] saved_reg;
    bool context_saved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct imx_port {
    struct uart_port port;
    struct timer_list timer;
    unsigned int old_status;
    unsigned int have_rtscts;
    unsigned int have_rtsgpio;
    unsigned int dte_mode;
    struct clk * clk_ipg;
    struct clk * clk_per;
    const struct imx_uart_data * devdata;
    struct mctrl_gpios * gpios;
    unsigned int ucr1;
    unsigned int ucr2;
    unsigned int ucr3;
    unsigned int ucr4;
    unsigned int ufcr;
    unsigned int dma_is_enabled;
    unsigned int dma_is_rxing;
    unsigned int dma_is_txing;
    struct dma_chan * dma_chan_rx;
    struct dma_chan * dma_chan_tx;
    struct scatterlist rx_sgl;
    struct scatterlist[2] tx_sgl;
    void * rx_buf;
    struct circ_buf rx_ring;
    unsigned int rx_periods;
    dma_cookie_t rx_cookie;
    unsigned int tx_bytes;
    unsigned int dma_tx_nents;
    unsigned int[10] saved_reg;
    bool context_saved;
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
struct imx_port {
    struct uart_port port;
    struct timer_list timer;
    unsigned int old_status;
    unsigned int have_rtscts;
    unsigned int have_rtsgpio;
    unsigned int dte_mode;
    struct clk * clk_ipg;
    struct clk * clk_per;
    const struct imx_uart_data * devdata;
    struct mctrl_gpios * gpios;
    unsigned int ucr1;
    unsigned int ucr2;
    unsigned int ucr3;
    unsigned int ucr4;
    unsigned int ufcr;
    unsigned int dma_is_enabled;
    unsigned int dma_is_rxing;
    unsigned int dma_is_txing;
    struct dma_chan * dma_chan_rx;
    struct dma_chan * dma_chan_tx;
    struct scatterlist rx_sgl;
    struct scatterlist[2] tx_sgl;
    void * rx_buf;
    struct circ_buf rx_ring;
    unsigned int rx_periods;
    dma_cookie_t rx_cookie;
    unsigned int tx_bytes;
    unsigned int dma_tx_nents;
    unsigned int[10] saved_reg;
    bool context_saved;
}
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
struct imx_port {
    struct uart_port port;
    struct timer_list timer;
    unsigned int old_status;
    unsigned int have_rtscts;
    unsigned int have_rtsgpio;
    unsigned int dte_mode;
    struct clk * clk_ipg;
    struct clk * clk_per;
    const struct imx_uart_data * devdata;
    struct mctrl_gpios * gpios;
    unsigned int ucr1;
    unsigned int ucr2;
    unsigned int ucr3;
    unsigned int ucr4;
    unsigned int ufcr;
    unsigned int dma_is_enabled;
    unsigned int dma_is_rxing;
    unsigned int dma_is_txing;
    struct dma_chan * dma_chan_rx;
    struct dma_chan * dma_chan_tx;
    struct scatterlist rx_sgl;
    struct scatterlist[2] tx_sgl;
    void * rx_buf;
    struct circ_buf rx_ring;
    unsigned int rx_periods;
    dma_cookie_t rx_cookie;
    unsigned int tx_bytes;
    unsigned int dma_tx_nents;
    unsigned int[10] saved_reg;
    bool context_saved;
}
```
</details>
</li>
</ul>
