# Struct: <code>uart_8250_dma</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct uart_8250_dma {
    int (*)(struct uart_8250_port *) tx_dma;
    int (*)(struct uart_8250_port *, unsigned int) rx_dma;
    dma_filter_fn fn;
    void * rx_param;
    void * tx_param;
    struct dma_slave_config rxconf;
    struct dma_slave_config txconf;
    struct dma_chan * rxchan;
    struct dma_chan * txchan;
    dma_addr_t rx_addr;
    dma_addr_t tx_addr;
    dma_cookie_t rx_cookie;
    dma_cookie_t tx_cookie;
    void * rx_buf;
    size_t rx_size;
    size_t tx_size;
    unsigned char tx_running;
    unsigned char tx_err;
    unsigned char rx_running;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct uart_8250_dma {
    int (*)(struct uart_8250_port *) tx_dma;
    int (*)(struct uart_8250_port *) rx_dma;
    dma_filter_fn fn;
    void * rx_param;
    void * tx_param;
    struct dma_slave_config rxconf;
    struct dma_slave_config txconf;
    struct dma_chan * rxchan;
    struct dma_chan * txchan;
    dma_addr_t rx_addr;
    dma_addr_t tx_addr;
    dma_cookie_t rx_cookie;
    dma_cookie_t tx_cookie;
    void * rx_buf;
    size_t rx_size;
    size_t tx_size;
    unsigned char tx_running;
    unsigned char tx_err;
    unsigned char rx_running;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct uart_8250_dma {
    int (*)(struct uart_8250_port *) tx_dma;
    int (*)(struct uart_8250_port *) rx_dma;
    dma_filter_fn fn;
    void * rx_param;
    void * tx_param;
    struct dma_slave_config rxconf;
    struct dma_slave_config txconf;
    struct dma_chan * rxchan;
    struct dma_chan * txchan;
    phys_addr_t rx_dma_addr;
    phys_addr_t tx_dma_addr;
    dma_addr_t rx_addr;
    dma_addr_t tx_addr;
    dma_cookie_t rx_cookie;
    dma_cookie_t tx_cookie;
    void * rx_buf;
    size_t rx_size;
    size_t tx_size;
    unsigned char tx_running;
    unsigned char tx_err;
    unsigned char rx_running;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct uart_8250_dma {
    int (*)(struct uart_8250_port *) tx_dma;
    int (*)(struct uart_8250_port *) rx_dma;
    dma_filter_fn fn;
    void * rx_param;
    void * tx_param;
    struct dma_slave_config rxconf;
    struct dma_slave_config txconf;
    struct dma_chan * rxchan;
    struct dma_chan * txchan;
    phys_addr_t rx_dma_addr;
    phys_addr_t tx_dma_addr;
    dma_addr_t rx_addr;
    dma_addr_t tx_addr;
    dma_cookie_t rx_cookie;
    dma_cookie_t tx_cookie;
    void * rx_buf;
    size_t rx_size;
    size_t tx_size;
    unsigned char tx_running;
    unsigned char tx_err;
    unsigned char rx_running;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct uart_8250_dma {
    int (*)(struct uart_8250_port *) tx_dma;
    int (*)(struct uart_8250_port *) rx_dma;
    dma_filter_fn fn;
    void * rx_param;
    void * tx_param;
    struct dma_slave_config rxconf;
    struct dma_slave_config txconf;
    struct dma_chan * rxchan;
    struct dma_chan * txchan;
    phys_addr_t rx_dma_addr;
    phys_addr_t tx_dma_addr;
    dma_addr_t rx_addr;
    dma_addr_t tx_addr;
    dma_cookie_t rx_cookie;
    dma_cookie_t tx_cookie;
    void * rx_buf;
    size_t rx_size;
    size_t tx_size;
    unsigned char tx_running;
    unsigned char tx_err;
    unsigned char rx_running;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct uart_8250_dma {
    int (*)(struct uart_8250_port *) tx_dma;
    int (*)(struct uart_8250_port *) rx_dma;
    dma_filter_fn fn;
    void * rx_param;
    void * tx_param;
    struct dma_slave_config rxconf;
    struct dma_slave_config txconf;
    struct dma_chan * rxchan;
    struct dma_chan * txchan;
    phys_addr_t rx_dma_addr;
    phys_addr_t tx_dma_addr;
    dma_addr_t rx_addr;
    dma_addr_t tx_addr;
    dma_cookie_t rx_cookie;
    dma_cookie_t tx_cookie;
    void * rx_buf;
    size_t rx_size;
    size_t tx_size;
    unsigned char tx_running;
    unsigned char tx_err;
    unsigned char rx_running;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct uart_8250_dma {
    int (*)(struct uart_8250_port *) tx_dma;
    int (*)(struct uart_8250_port *) rx_dma;
    dma_filter_fn fn;
    void * rx_param;
    void * tx_param;
    struct dma_slave_config rxconf;
    struct dma_slave_config txconf;
    struct dma_chan * rxchan;
    struct dma_chan * txchan;
    phys_addr_t rx_dma_addr;
    phys_addr_t tx_dma_addr;
    dma_addr_t rx_addr;
    dma_addr_t tx_addr;
    dma_cookie_t rx_cookie;
    dma_cookie_t tx_cookie;
    void * rx_buf;
    size_t rx_size;
    size_t tx_size;
    unsigned char tx_running;
    unsigned char tx_err;
    unsigned char rx_running;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct uart_8250_dma {
    int (*)(struct uart_8250_port *) tx_dma;
    int (*)(struct uart_8250_port *) rx_dma;
    dma_filter_fn fn;
    void * rx_param;
    void * tx_param;
    struct dma_slave_config rxconf;
    struct dma_slave_config txconf;
    struct dma_chan * rxchan;
    struct dma_chan * txchan;
    phys_addr_t rx_dma_addr;
    phys_addr_t tx_dma_addr;
    dma_addr_t rx_addr;
    dma_addr_t tx_addr;
    dma_cookie_t rx_cookie;
    dma_cookie_t tx_cookie;
    void * rx_buf;
    size_t rx_size;
    size_t tx_size;
    unsigned char tx_running;
    unsigned char tx_err;
    unsigned char rx_running;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct uart_8250_dma {
    int (*)(struct uart_8250_port *) tx_dma;
    int (*)(struct uart_8250_port *) rx_dma;
    dma_filter_fn fn;
    void * rx_param;
    void * tx_param;
    struct dma_slave_config rxconf;
    struct dma_slave_config txconf;
    struct dma_chan * rxchan;
    struct dma_chan * txchan;
    phys_addr_t rx_dma_addr;
    phys_addr_t tx_dma_addr;
    dma_addr_t rx_addr;
    dma_addr_t tx_addr;
    dma_cookie_t rx_cookie;
    dma_cookie_t tx_cookie;
    void * rx_buf;
    size_t rx_size;
    size_t tx_size;
    unsigned char tx_running;
    unsigned char tx_err;
    unsigned char rx_running;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct uart_8250_dma {
    int (*)(struct uart_8250_port *) tx_dma;
    int (*)(struct uart_8250_port *) rx_dma;
    dma_filter_fn fn;
    void * rx_param;
    void * tx_param;
    struct dma_slave_config rxconf;
    struct dma_slave_config txconf;
    struct dma_chan * rxchan;
    struct dma_chan * txchan;
    phys_addr_t rx_dma_addr;
    phys_addr_t tx_dma_addr;
    dma_addr_t rx_addr;
    dma_addr_t tx_addr;
    dma_cookie_t rx_cookie;
    dma_cookie_t tx_cookie;
    void * rx_buf;
    size_t rx_size;
    size_t tx_size;
    unsigned char tx_running;
    unsigned char tx_err;
    unsigned char rx_running;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct uart_8250_dma {
    int (*)(struct uart_8250_port *) tx_dma;
    int (*)(struct uart_8250_port *) rx_dma;
    dma_filter_fn fn;
    void * rx_param;
    void * tx_param;
    struct dma_slave_config rxconf;
    struct dma_slave_config txconf;
    struct dma_chan * rxchan;
    struct dma_chan * txchan;
    phys_addr_t rx_dma_addr;
    phys_addr_t tx_dma_addr;
    dma_addr_t rx_addr;
    dma_addr_t tx_addr;
    dma_cookie_t rx_cookie;
    dma_cookie_t tx_cookie;
    void * rx_buf;
    size_t rx_size;
    size_t tx_size;
    unsigned char tx_running;
    unsigned char tx_err;
    unsigned char rx_running;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct uart_8250_dma {
    int (*)(struct uart_8250_port *) tx_dma;
    int (*)(struct uart_8250_port *) rx_dma;
    dma_filter_fn fn;
    void * rx_param;
    void * tx_param;
    struct dma_slave_config rxconf;
    struct dma_slave_config txconf;
    struct dma_chan * rxchan;
    struct dma_chan * txchan;
    phys_addr_t rx_dma_addr;
    phys_addr_t tx_dma_addr;
    dma_addr_t rx_addr;
    dma_addr_t tx_addr;
    dma_cookie_t rx_cookie;
    dma_cookie_t tx_cookie;
    void * rx_buf;
    size_t rx_size;
    size_t tx_size;
    unsigned char tx_running;
    unsigned char tx_err;
    unsigned char rx_running;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct uart_8250_dma {
    int (*)(struct uart_8250_port *) tx_dma;
    int (*)(struct uart_8250_port *) rx_dma;
    dma_filter_fn fn;
    void * rx_param;
    void * tx_param;
    struct dma_slave_config rxconf;
    struct dma_slave_config txconf;
    struct dma_chan * rxchan;
    struct dma_chan * txchan;
    phys_addr_t rx_dma_addr;
    phys_addr_t tx_dma_addr;
    dma_addr_t rx_addr;
    dma_addr_t tx_addr;
    dma_cookie_t rx_cookie;
    dma_cookie_t tx_cookie;
    void * rx_buf;
    size_t rx_size;
    size_t tx_size;
    unsigned char tx_running;
    unsigned char tx_err;
    unsigned char rx_running;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct uart_8250_dma {
    int (*)(struct uart_8250_port *) tx_dma;
    int (*)(struct uart_8250_port *) rx_dma;
    void (*)(struct uart_8250_port *) prepare_tx_dma;
    void (*)(struct uart_8250_port *) prepare_rx_dma;
    dma_filter_fn fn;
    void * rx_param;
    void * tx_param;
    struct dma_slave_config rxconf;
    struct dma_slave_config txconf;
    struct dma_chan * rxchan;
    struct dma_chan * txchan;
    phys_addr_t rx_dma_addr;
    phys_addr_t tx_dma_addr;
    dma_addr_t rx_addr;
    dma_addr_t tx_addr;
    dma_cookie_t rx_cookie;
    dma_cookie_t tx_cookie;
    void * rx_buf;
    size_t rx_size;
    size_t tx_size;
    unsigned char tx_running;
    unsigned char tx_err;
    unsigned char rx_running;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct uart_8250_dma {
    int (*)(struct uart_8250_port *) tx_dma;
    int (*)(struct uart_8250_port *) rx_dma;
    void (*)(struct uart_8250_port *) prepare_tx_dma;
    void (*)(struct uart_8250_port *) prepare_rx_dma;
    dma_filter_fn fn;
    void * rx_param;
    void * tx_param;
    struct dma_slave_config rxconf;
    struct dma_slave_config txconf;
    struct dma_chan * rxchan;
    struct dma_chan * txchan;
    phys_addr_t rx_dma_addr;
    phys_addr_t tx_dma_addr;
    dma_addr_t rx_addr;
    dma_addr_t tx_addr;
    dma_cookie_t rx_cookie;
    dma_cookie_t tx_cookie;
    void * rx_buf;
    size_t rx_size;
    size_t tx_size;
    unsigned char tx_running;
    unsigned char tx_err;
    unsigned char rx_running;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct uart_8250_dma {
    int (*)(struct uart_8250_port *) tx_dma;
    int (*)(struct uart_8250_port *) rx_dma;
    void (*)(struct uart_8250_port *) prepare_tx_dma;
    void (*)(struct uart_8250_port *) prepare_rx_dma;
    dma_filter_fn fn;
    void * rx_param;
    void * tx_param;
    struct dma_slave_config rxconf;
    struct dma_slave_config txconf;
    struct dma_chan * rxchan;
    struct dma_chan * txchan;
    phys_addr_t rx_dma_addr;
    phys_addr_t tx_dma_addr;
    dma_addr_t rx_addr;
    dma_addr_t tx_addr;
    dma_cookie_t rx_cookie;
    dma_cookie_t tx_cookie;
    void * rx_buf;
    size_t rx_size;
    size_t tx_size;
    unsigned char tx_running;
    unsigned char tx_err;
    unsigned char rx_running;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct uart_8250_dma {
    int (*)(struct uart_8250_port *) tx_dma;
    int (*)(struct uart_8250_port *) rx_dma;
    void (*)(struct uart_8250_port *) prepare_tx_dma;
    void (*)(struct uart_8250_port *) prepare_rx_dma;
    dma_filter_fn fn;
    void * rx_param;
    void * tx_param;
    struct dma_slave_config rxconf;
    struct dma_slave_config txconf;
    struct dma_chan * rxchan;
    struct dma_chan * txchan;
    phys_addr_t rx_dma_addr;
    phys_addr_t tx_dma_addr;
    dma_addr_t rx_addr;
    dma_addr_t tx_addr;
    dma_cookie_t rx_cookie;
    dma_cookie_t tx_cookie;
    void * rx_buf;
    size_t rx_size;
    size_t tx_size;
    unsigned char tx_running;
    unsigned char tx_err;
    unsigned char rx_running;
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
struct uart_8250_dma {
    int (*)(struct uart_8250_port *) tx_dma;
    int (*)(struct uart_8250_port *) rx_dma;
    dma_filter_fn fn;
    void * rx_param;
    void * tx_param;
    struct dma_slave_config rxconf;
    struct dma_slave_config txconf;
    struct dma_chan * rxchan;
    struct dma_chan * txchan;
    phys_addr_t rx_dma_addr;
    phys_addr_t tx_dma_addr;
    dma_addr_t rx_addr;
    dma_addr_t tx_addr;
    dma_cookie_t rx_cookie;
    dma_cookie_t tx_cookie;
    void * rx_buf;
    size_t rx_size;
    size_t tx_size;
    unsigned char tx_running;
    unsigned char tx_err;
    unsigned char rx_running;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct uart_8250_dma {
    int (*)(struct uart_8250_port *) tx_dma;
    int (*)(struct uart_8250_port *) rx_dma;
    dma_filter_fn fn;
    void * rx_param;
    void * tx_param;
    struct dma_slave_config rxconf;
    struct dma_slave_config txconf;
    struct dma_chan * rxchan;
    struct dma_chan * txchan;
    phys_addr_t rx_dma_addr;
    phys_addr_t tx_dma_addr;
    dma_addr_t rx_addr;
    dma_addr_t tx_addr;
    dma_cookie_t rx_cookie;
    dma_cookie_t tx_cookie;
    void * rx_buf;
    size_t rx_size;
    size_t tx_size;
    unsigned char tx_running;
    unsigned char tx_err;
    unsigned char rx_running;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct uart_8250_dma {
    int (*)(struct uart_8250_port *) tx_dma;
    int (*)(struct uart_8250_port *) rx_dma;
    dma_filter_fn fn;
    void * rx_param;
    void * tx_param;
    struct dma_slave_config rxconf;
    struct dma_slave_config txconf;
    struct dma_chan * rxchan;
    struct dma_chan * txchan;
    phys_addr_t rx_dma_addr;
    phys_addr_t tx_dma_addr;
    dma_addr_t rx_addr;
    dma_addr_t tx_addr;
    dma_cookie_t rx_cookie;
    dma_cookie_t tx_cookie;
    void * rx_buf;
    size_t rx_size;
    size_t tx_size;
    unsigned char tx_running;
    unsigned char tx_err;
    unsigned char rx_running;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct uart_8250_dma {
    int (*)(struct uart_8250_port *) tx_dma;
    int (*)(struct uart_8250_port *) rx_dma;
    dma_filter_fn fn;
    void * rx_param;
    void * tx_param;
    struct dma_slave_config rxconf;
    struct dma_slave_config txconf;
    struct dma_chan * rxchan;
    struct dma_chan * txchan;
    phys_addr_t rx_dma_addr;
    phys_addr_t tx_dma_addr;
    dma_addr_t rx_addr;
    dma_addr_t tx_addr;
    dma_cookie_t rx_cookie;
    dma_cookie_t tx_cookie;
    void * rx_buf;
    size_t rx_size;
    size_t tx_size;
    unsigned char tx_running;
    unsigned char tx_err;
    unsigned char rx_running;
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
struct uart_8250_dma {
    int (*)(struct uart_8250_port *) tx_dma;
    int (*)(struct uart_8250_port *) rx_dma;
    dma_filter_fn fn;
    void * rx_param;
    void * tx_param;
    struct dma_slave_config rxconf;
    struct dma_slave_config txconf;
    struct dma_chan * rxchan;
    struct dma_chan * txchan;
    phys_addr_t rx_dma_addr;
    phys_addr_t tx_dma_addr;
    dma_addr_t rx_addr;
    dma_addr_t tx_addr;
    dma_cookie_t rx_cookie;
    dma_cookie_t tx_cookie;
    void * rx_buf;
    size_t rx_size;
    size_t tx_size;
    unsigned char tx_running;
    unsigned char tx_err;
    unsigned char rx_running;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct uart_8250_dma {
    int (*)(struct uart_8250_port *) tx_dma;
    int (*)(struct uart_8250_port *) rx_dma;
    dma_filter_fn fn;
    void * rx_param;
    void * tx_param;
    struct dma_slave_config rxconf;
    struct dma_slave_config txconf;
    struct dma_chan * rxchan;
    struct dma_chan * txchan;
    phys_addr_t rx_dma_addr;
    phys_addr_t tx_dma_addr;
    dma_addr_t rx_addr;
    dma_addr_t tx_addr;
    dma_cookie_t rx_cookie;
    dma_cookie_t tx_cookie;
    void * rx_buf;
    size_t rx_size;
    size_t tx_size;
    unsigned char tx_running;
    unsigned char tx_err;
    unsigned char rx_running;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct uart_8250_dma {
    int (*)(struct uart_8250_port *) tx_dma;
    int (*)(struct uart_8250_port *) rx_dma;
    dma_filter_fn fn;
    void * rx_param;
    void * tx_param;
    struct dma_slave_config rxconf;
    struct dma_slave_config txconf;
    struct dma_chan * rxchan;
    struct dma_chan * txchan;
    phys_addr_t rx_dma_addr;
    phys_addr_t tx_dma_addr;
    dma_addr_t rx_addr;
    dma_addr_t tx_addr;
    dma_cookie_t rx_cookie;
    dma_cookie_t tx_cookie;
    void * rx_buf;
    size_t rx_size;
    size_t tx_size;
    unsigned char tx_running;
    unsigned char tx_err;
    unsigned char rx_running;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct uart_8250_dma {
    int (*)(struct uart_8250_port *) tx_dma;
    int (*)(struct uart_8250_port *) rx_dma;
    dma_filter_fn fn;
    void * rx_param;
    void * tx_param;
    struct dma_slave_config rxconf;
    struct dma_slave_config txconf;
    struct dma_chan * rxchan;
    struct dma_chan * txchan;
    phys_addr_t rx_dma_addr;
    phys_addr_t tx_dma_addr;
    dma_addr_t rx_addr;
    dma_addr_t tx_addr;
    dma_cookie_t rx_cookie;
    dma_cookie_t tx_cookie;
    void * rx_buf;
    size_t rx_size;
    size_t tx_size;
    unsigned char tx_running;
    unsigned char tx_err;
    unsigned char rx_running;
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
<b>Field type changed. </b>
<code>int (*)(struct uart_8250_port *, unsigned int) rx_dma</code> ➡️ <code>int (*)(struct uart_8250_port *) rx_dma</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>phys_addr_t rx_dma_addr</code>
</li>
<li>
<b>Field added. </b>
<code>phys_addr_t tx_dma_addr</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
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
<b>Field added. </b>
<code>void (*)(struct uart_8250_port *) prepare_tx_dma</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct uart_8250_port *) prepare_rx_dma</code>
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
