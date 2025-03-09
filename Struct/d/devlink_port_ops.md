# Struct: <code>devlink_port_ops</code>

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
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct devlink_port_ops {
    int (*)(struct devlink *, struct devlink_port *, unsigned int, struct netlink_ext_ack *) port_split;
    int (*)(struct devlink *, struct devlink_port *, struct netlink_ext_ack *) port_unsplit;
    int (*)(struct devlink_port *, enum devlink_port_type) port_type_set;
    int (*)(struct devlink *, struct devlink_port *, struct netlink_ext_ack *) port_del;
    int (*)(struct devlink_port *, u8 *, int *, struct netlink_ext_ack *) port_fn_hw_addr_get;
    int (*)(struct devlink_port *, const u8 *, int, struct netlink_ext_ack *) port_fn_hw_addr_set;
    int (*)(struct devlink_port *, bool *, struct netlink_ext_ack *) port_fn_roce_get;
    int (*)(struct devlink_port *, bool, struct netlink_ext_ack *) port_fn_roce_set;
    int (*)(struct devlink_port *, bool *, struct netlink_ext_ack *) port_fn_migratable_get;
    int (*)(struct devlink_port *, bool, struct netlink_ext_ack *) port_fn_migratable_set;
    int (*)(struct devlink_port *, enum devlink_port_fn_state *, enum devlink_port_fn_opstate *, struct netlink_ext_ack *) port_fn_state_get;
    int (*)(struct devlink_port *, enum devlink_port_fn_state, struct netlink_ext_ack *) port_fn_state_set;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct devlink_port_ops {
    int (*)(struct devlink *, struct devlink_port *, unsigned int, struct netlink_ext_ack *) port_split;
    int (*)(struct devlink *, struct devlink_port *, struct netlink_ext_ack *) port_unsplit;
    int (*)(struct devlink_port *, enum devlink_port_type) port_type_set;
    int (*)(struct devlink *, struct devlink_port *, struct netlink_ext_ack *) port_del;
    int (*)(struct devlink_port *, u8 *, int *, struct netlink_ext_ack *) port_fn_hw_addr_get;
    int (*)(struct devlink_port *, const u8 *, int, struct netlink_ext_ack *) port_fn_hw_addr_set;
    int (*)(struct devlink_port *, bool *, struct netlink_ext_ack *) port_fn_roce_get;
    int (*)(struct devlink_port *, bool, struct netlink_ext_ack *) port_fn_roce_set;
    int (*)(struct devlink_port *, bool *, struct netlink_ext_ack *) port_fn_migratable_get;
    int (*)(struct devlink_port *, bool, struct netlink_ext_ack *) port_fn_migratable_set;
    int (*)(struct devlink_port *, enum devlink_port_fn_state *, enum devlink_port_fn_opstate *, struct netlink_ext_ack *) port_fn_state_get;
    int (*)(struct devlink_port *, enum devlink_port_fn_state, struct netlink_ext_ack *) port_fn_state_set;
    int (*)(struct devlink_port *, bool *, struct netlink_ext_ack *) port_fn_ipsec_crypto_get;
    int (*)(struct devlink_port *, bool, struct netlink_ext_ack *) port_fn_ipsec_crypto_set;
    int (*)(struct devlink_port *, bool *, struct netlink_ext_ack *) port_fn_ipsec_packet_get;
    int (*)(struct devlink_port *, bool, struct netlink_ext_ack *) port_fn_ipsec_packet_set;
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
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
struct devlink_port_ops {
    int (*)(struct devlink *, struct devlink_port *, unsigned int, struct netlink_ext_ack *) port_split;
    int (*)(struct devlink *, struct devlink_port *, struct netlink_ext_ack *) port_unsplit;
    int (*)(struct devlink_port *, enum devlink_port_type) port_type_set;
    int (*)(struct devlink *, struct devlink_port *, struct netlink_ext_ack *) port_del;
    int (*)(struct devlink_port *, u8 *, int *, struct netlink_ext_ack *) port_fn_hw_addr_get;
    int (*)(struct devlink_port *, const u8 *, int, struct netlink_ext_ack *) port_fn_hw_addr_set;
    int (*)(struct devlink_port *, bool *, struct netlink_ext_ack *) port_fn_roce_get;
    int (*)(struct devlink_port *, bool, struct netlink_ext_ack *) port_fn_roce_set;
    int (*)(struct devlink_port *, bool *, struct netlink_ext_ack *) port_fn_migratable_get;
    int (*)(struct devlink_port *, bool, struct netlink_ext_ack *) port_fn_migratable_set;
    int (*)(struct devlink_port *, enum devlink_port_fn_state *, enum devlink_port_fn_opstate *, struct netlink_ext_ack *) port_fn_state_get;
    int (*)(struct devlink_port *, enum devlink_port_fn_state, struct netlink_ext_ack *) port_fn_state_set;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct devlink_port *, bool *, struct netlink_ext_ack *) port_fn_ipsec_crypto_get</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct devlink_port *, bool, struct netlink_ext_ack *) port_fn_ipsec_crypto_set</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct devlink_port *, bool *, struct netlink_ext_ack *) port_fn_ipsec_packet_get</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct devlink_port *, bool, struct netlink_ext_ack *) port_fn_ipsec_packet_set</code>
</li>
</ul>
</details>
</li>
</ul>
