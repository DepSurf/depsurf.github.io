# Struct: <code>fec_enet_private</code>

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
struct fec_enet_private {
    void * hwp;
    struct net_device * netdev;
    struct clk * clk_ipg;
    struct clk * clk_ahb;
    struct clk * clk_ref;
    struct clk * clk_enet_out;
    struct clk * clk_ptp;
    bool ptp_clk_on;
    struct mutex ptp_clk_mutex;
    unsigned int num_tx_queues;
    unsigned int num_rx_queues;
    struct fec_enet_priv_tx_q *[3] tx_queue;
    struct fec_enet_priv_rx_q *[3] rx_queue;
    unsigned int total_tx_ring_size;
    unsigned int total_rx_ring_size;
    long unsigned int work_tx;
    long unsigned int work_rx;
    long unsigned int work_ts;
    long unsigned int work_mdio;
    struct platform_device * pdev;
    int dev_id;
    struct mii_bus * mii_bus;
    uint phy_speed;
    phy_interface_t phy_interface;
    struct device_node * phy_node;
    int link;
    int full_duplex;
    int speed;
    struct completion mdio_done;
    int[3] irq;
    bool bufdesc_ex;
    int pause_flag;
    int wol_flag;
    u32 quirks;
    struct napi_struct napi;
    int csum_flags;
    struct work_struct tx_timeout_work;
    struct ptp_clock * ptp_clock;
    struct ptp_clock_info ptp_caps;
    long unsigned int last_overflow_check;
    spinlock_t tmreg_lock;
    struct cyclecounter cc;
    struct timecounter tc;
    int rx_hwtstamp_filter;
    u32 base_incval;
    u32 cycle_speed;
    int hwts_rx_en;
    int hwts_tx_en;
    struct delayed_work time_keep;
    struct regulator * reg_phy;
    unsigned int tx_align;
    unsigned int rx_align;
    unsigned int rx_pkts_itr;
    unsigned int rx_time_itr;
    unsigned int tx_pkts_itr;
    unsigned int tx_time_itr;
    unsigned int itr_clk_rate;
    u32 rx_copybreak;
    unsigned int ptp_inc;
    int pps_channel;
    unsigned int reload_period;
    int pps_enable;
    unsigned int next_counter;
    u64[0] ethtool_stats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct fec_enet_private {
    void * hwp;
    struct net_device * netdev;
    struct clk * clk_ipg;
    struct clk * clk_ahb;
    struct clk * clk_ref;
    struct clk * clk_enet_out;
    struct clk * clk_ptp;
    bool ptp_clk_on;
    struct mutex ptp_clk_mutex;
    unsigned int num_tx_queues;
    unsigned int num_rx_queues;
    struct fec_enet_priv_tx_q *[3] tx_queue;
    struct fec_enet_priv_rx_q *[3] rx_queue;
    unsigned int total_tx_ring_size;
    unsigned int total_rx_ring_size;
    long unsigned int work_tx;
    long unsigned int work_rx;
    long unsigned int work_ts;
    long unsigned int work_mdio;
    struct platform_device * pdev;
    int dev_id;
    struct mii_bus * mii_bus;
    uint phy_speed;
    phy_interface_t phy_interface;
    struct device_node * phy_node;
    int link;
    int full_duplex;
    int speed;
    struct completion mdio_done;
    int[3] irq;
    bool bufdesc_ex;
    int pause_flag;
    int wol_flag;
    u32 quirks;
    struct napi_struct napi;
    int csum_flags;
    struct work_struct tx_timeout_work;
    struct ptp_clock * ptp_clock;
    struct ptp_clock_info ptp_caps;
    long unsigned int last_overflow_check;
    spinlock_t tmreg_lock;
    struct cyclecounter cc;
    struct timecounter tc;
    int rx_hwtstamp_filter;
    u32 base_incval;
    u32 cycle_speed;
    int hwts_rx_en;
    int hwts_tx_en;
    struct delayed_work time_keep;
    struct regulator * reg_phy;
    unsigned int tx_align;
    unsigned int rx_align;
    unsigned int rx_pkts_itr;
    unsigned int rx_time_itr;
    unsigned int tx_pkts_itr;
    unsigned int tx_time_itr;
    unsigned int itr_clk_rate;
    u32 rx_copybreak;
    unsigned int ptp_inc;
    int pps_channel;
    unsigned int reload_period;
    int pps_enable;
    unsigned int next_counter;
    u64[0] ethtool_stats;
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
struct fec_enet_private {
    void * hwp;
    struct net_device * netdev;
    struct clk * clk_ipg;
    struct clk * clk_ahb;
    struct clk * clk_ref;
    struct clk * clk_enet_out;
    struct clk * clk_ptp;
    bool ptp_clk_on;
    struct mutex ptp_clk_mutex;
    unsigned int num_tx_queues;
    unsigned int num_rx_queues;
    struct fec_enet_priv_tx_q *[3] tx_queue;
    struct fec_enet_priv_rx_q *[3] rx_queue;
    unsigned int total_tx_ring_size;
    unsigned int total_rx_ring_size;
    long unsigned int work_tx;
    long unsigned int work_rx;
    long unsigned int work_ts;
    long unsigned int work_mdio;
    struct platform_device * pdev;
    int dev_id;
    struct mii_bus * mii_bus;
    uint phy_speed;
    phy_interface_t phy_interface;
    struct device_node * phy_node;
    int link;
    int full_duplex;
    int speed;
    struct completion mdio_done;
    int[3] irq;
    bool bufdesc_ex;
    int pause_flag;
    int wol_flag;
    u32 quirks;
    struct napi_struct napi;
    int csum_flags;
    struct work_struct tx_timeout_work;
    struct ptp_clock * ptp_clock;
    struct ptp_clock_info ptp_caps;
    long unsigned int last_overflow_check;
    spinlock_t tmreg_lock;
    struct cyclecounter cc;
    struct timecounter tc;
    int rx_hwtstamp_filter;
    u32 base_incval;
    u32 cycle_speed;
    int hwts_rx_en;
    int hwts_tx_en;
    struct delayed_work time_keep;
    struct regulator * reg_phy;
    unsigned int tx_align;
    unsigned int rx_align;
    unsigned int rx_pkts_itr;
    unsigned int rx_time_itr;
    unsigned int tx_pkts_itr;
    unsigned int tx_time_itr;
    unsigned int itr_clk_rate;
    u32 rx_copybreak;
    unsigned int ptp_inc;
    int pps_channel;
    unsigned int reload_period;
    int pps_enable;
    unsigned int next_counter;
    u64[0] ethtool_stats;
}
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
struct fec_enet_private {
    void * hwp;
    struct net_device * netdev;
    struct clk * clk_ipg;
    struct clk * clk_ahb;
    struct clk * clk_ref;
    struct clk * clk_enet_out;
    struct clk * clk_ptp;
    bool ptp_clk_on;
    struct mutex ptp_clk_mutex;
    unsigned int num_tx_queues;
    unsigned int num_rx_queues;
    struct fec_enet_priv_tx_q *[3] tx_queue;
    struct fec_enet_priv_rx_q *[3] rx_queue;
    unsigned int total_tx_ring_size;
    unsigned int total_rx_ring_size;
    long unsigned int work_tx;
    long unsigned int work_rx;
    long unsigned int work_ts;
    long unsigned int work_mdio;
    struct platform_device * pdev;
    int dev_id;
    struct mii_bus * mii_bus;
    uint phy_speed;
    phy_interface_t phy_interface;
    struct device_node * phy_node;
    int link;
    int full_duplex;
    int speed;
    struct completion mdio_done;
    int[3] irq;
    bool bufdesc_ex;
    int pause_flag;
    int wol_flag;
    u32 quirks;
    struct napi_struct napi;
    int csum_flags;
    struct work_struct tx_timeout_work;
    struct ptp_clock * ptp_clock;
    struct ptp_clock_info ptp_caps;
    long unsigned int last_overflow_check;
    spinlock_t tmreg_lock;
    struct cyclecounter cc;
    struct timecounter tc;
    int rx_hwtstamp_filter;
    u32 base_incval;
    u32 cycle_speed;
    int hwts_rx_en;
    int hwts_tx_en;
    struct delayed_work time_keep;
    struct regulator * reg_phy;
    unsigned int tx_align;
    unsigned int rx_align;
    unsigned int rx_pkts_itr;
    unsigned int rx_time_itr;
    unsigned int tx_pkts_itr;
    unsigned int tx_time_itr;
    unsigned int itr_clk_rate;
    u32 rx_copybreak;
    unsigned int ptp_inc;
    int pps_channel;
    unsigned int reload_period;
    int pps_enable;
    unsigned int next_counter;
    u64[0] ethtool_stats;
}
```
</details>
</li>
</ul>
