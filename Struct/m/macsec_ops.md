# Struct: <code>macsec_ops</code>

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
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct macsec_ops {
    int (*)(struct macsec_context *) mdo_dev_open;
    int (*)(struct macsec_context *) mdo_dev_stop;
    int (*)(struct macsec_context *) mdo_add_secy;
    int (*)(struct macsec_context *) mdo_upd_secy;
    int (*)(struct macsec_context *) mdo_del_secy;
    int (*)(struct macsec_context *) mdo_add_rxsc;
    int (*)(struct macsec_context *) mdo_upd_rxsc;
    int (*)(struct macsec_context *) mdo_del_rxsc;
    int (*)(struct macsec_context *) mdo_add_rxsa;
    int (*)(struct macsec_context *) mdo_upd_rxsa;
    int (*)(struct macsec_context *) mdo_del_rxsa;
    int (*)(struct macsec_context *) mdo_add_txsa;
    int (*)(struct macsec_context *) mdo_upd_txsa;
    int (*)(struct macsec_context *) mdo_del_txsa;
    int (*)(struct macsec_context *) mdo_get_dev_stats;
    int (*)(struct macsec_context *) mdo_get_tx_sc_stats;
    int (*)(struct macsec_context *) mdo_get_tx_sa_stats;
    int (*)(struct macsec_context *) mdo_get_rx_sc_stats;
    int (*)(struct macsec_context *) mdo_get_rx_sa_stats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct macsec_ops {
    int (*)(struct macsec_context *) mdo_dev_open;
    int (*)(struct macsec_context *) mdo_dev_stop;
    int (*)(struct macsec_context *) mdo_add_secy;
    int (*)(struct macsec_context *) mdo_upd_secy;
    int (*)(struct macsec_context *) mdo_del_secy;
    int (*)(struct macsec_context *) mdo_add_rxsc;
    int (*)(struct macsec_context *) mdo_upd_rxsc;
    int (*)(struct macsec_context *) mdo_del_rxsc;
    int (*)(struct macsec_context *) mdo_add_rxsa;
    int (*)(struct macsec_context *) mdo_upd_rxsa;
    int (*)(struct macsec_context *) mdo_del_rxsa;
    int (*)(struct macsec_context *) mdo_add_txsa;
    int (*)(struct macsec_context *) mdo_upd_txsa;
    int (*)(struct macsec_context *) mdo_del_txsa;
    int (*)(struct macsec_context *) mdo_get_dev_stats;
    int (*)(struct macsec_context *) mdo_get_tx_sc_stats;
    int (*)(struct macsec_context *) mdo_get_tx_sa_stats;
    int (*)(struct macsec_context *) mdo_get_rx_sc_stats;
    int (*)(struct macsec_context *) mdo_get_rx_sa_stats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct macsec_ops {
    int (*)(struct macsec_context *) mdo_dev_open;
    int (*)(struct macsec_context *) mdo_dev_stop;
    int (*)(struct macsec_context *) mdo_add_secy;
    int (*)(struct macsec_context *) mdo_upd_secy;
    int (*)(struct macsec_context *) mdo_del_secy;
    int (*)(struct macsec_context *) mdo_add_rxsc;
    int (*)(struct macsec_context *) mdo_upd_rxsc;
    int (*)(struct macsec_context *) mdo_del_rxsc;
    int (*)(struct macsec_context *) mdo_add_rxsa;
    int (*)(struct macsec_context *) mdo_upd_rxsa;
    int (*)(struct macsec_context *) mdo_del_rxsa;
    int (*)(struct macsec_context *) mdo_add_txsa;
    int (*)(struct macsec_context *) mdo_upd_txsa;
    int (*)(struct macsec_context *) mdo_del_txsa;
    int (*)(struct macsec_context *) mdo_get_dev_stats;
    int (*)(struct macsec_context *) mdo_get_tx_sc_stats;
    int (*)(struct macsec_context *) mdo_get_tx_sa_stats;
    int (*)(struct macsec_context *) mdo_get_rx_sc_stats;
    int (*)(struct macsec_context *) mdo_get_rx_sa_stats;
    int (*)(struct phy_device *, struct sk_buff *) mdo_insert_tx_tag;
    unsigned int needed_headroom;
    unsigned int needed_tailroom;
}
```
</details>
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
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
struct macsec_ops {
    int (*)(struct macsec_context *) mdo_dev_open;
    int (*)(struct macsec_context *) mdo_dev_stop;
    int (*)(struct macsec_context *) mdo_add_secy;
    int (*)(struct macsec_context *) mdo_upd_secy;
    int (*)(struct macsec_context *) mdo_del_secy;
    int (*)(struct macsec_context *) mdo_add_rxsc;
    int (*)(struct macsec_context *) mdo_upd_rxsc;
    int (*)(struct macsec_context *) mdo_del_rxsc;
    int (*)(struct macsec_context *) mdo_add_rxsa;
    int (*)(struct macsec_context *) mdo_upd_rxsa;
    int (*)(struct macsec_context *) mdo_del_rxsa;
    int (*)(struct macsec_context *) mdo_add_txsa;
    int (*)(struct macsec_context *) mdo_upd_txsa;
    int (*)(struct macsec_context *) mdo_del_txsa;
    int (*)(struct macsec_context *) mdo_get_dev_stats;
    int (*)(struct macsec_context *) mdo_get_tx_sc_stats;
    int (*)(struct macsec_context *) mdo_get_tx_sa_stats;
    int (*)(struct macsec_context *) mdo_get_rx_sc_stats;
    int (*)(struct macsec_context *) mdo_get_rx_sa_stats;
}
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct phy_device *, struct sk_buff *) mdo_insert_tx_tag</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int needed_headroom</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int needed_tailroom</code>
</li>
</ul>
</details>
</li>
</ul>
