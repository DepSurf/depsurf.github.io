# Struct: <code>dsa_switch_driver</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct dsa_switch_driver {
    struct list_head list;
    enum dsa_tag_protocol tag_protocol;
    const char * (*)(struct device *, struct device *, int, void * *) probe;
    int (*)(struct dsa_switch *) setup;
    int (*)(struct dsa_switch *, u8 *) set_addr;
    u32 (*)(struct dsa_switch *, int) get_phy_flags;
    int (*)(struct dsa_switch *, int, int) phy_read;
    int (*)(struct dsa_switch *, int, int, u16) phy_write;
    void (*)(struct dsa_switch *, int, struct phy_device *) adjust_link;
    void (*)(struct dsa_switch *, int, struct fixed_phy_status *) fixed_link_update;
    void (*)(struct dsa_switch *, int, uint8_t *) get_strings;
    void (*)(struct dsa_switch *, int, uint64_t *) get_ethtool_stats;
    int (*)(struct dsa_switch *) get_sset_count;
    void (*)(struct dsa_switch *, int, struct ethtool_wolinfo *) get_wol;
    int (*)(struct dsa_switch *, int, struct ethtool_wolinfo *) set_wol;
    int (*)(struct dsa_switch *) suspend;
    int (*)(struct dsa_switch *) resume;
    int (*)(struct dsa_switch *, int, struct phy_device *) port_enable;
    void (*)(struct dsa_switch *, int, struct phy_device *) port_disable;
    int (*)(struct dsa_switch *, int, struct phy_device *, struct ethtool_eee *) set_eee;
    int (*)(struct dsa_switch *, int, struct ethtool_eee *) get_eee;
    int (*)(struct dsa_switch *, int *) get_temp;
    int (*)(struct dsa_switch *, int *) get_temp_limit;
    int (*)(struct dsa_switch *, int) set_temp_limit;
    int (*)(struct dsa_switch *, bool *) get_temp_alarm;
    int (*)(struct dsa_switch *) get_eeprom_len;
    int (*)(struct dsa_switch *, struct ethtool_eeprom *, u8 *) get_eeprom;
    int (*)(struct dsa_switch *, struct ethtool_eeprom *, u8 *) set_eeprom;
    int (*)(struct dsa_switch *, int) get_regs_len;
    void (*)(struct dsa_switch *, int, struct ethtool_regs *, void *) get_regs;
    int (*)(struct dsa_switch *, unsigned int) set_ageing_time;
    int (*)(struct dsa_switch *, int, struct net_device *) port_bridge_join;
    void (*)(struct dsa_switch *, int) port_bridge_leave;
    void (*)(struct dsa_switch *, int, u8) port_stp_state_set;
    int (*)(struct dsa_switch *, int, bool) port_vlan_filtering;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_vlan *, struct switchdev_trans *) port_vlan_prepare;
    void (*)(struct dsa_switch *, int, const struct switchdev_obj_port_vlan *, struct switchdev_trans *) port_vlan_add;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_vlan *) port_vlan_del;
    int (*)(struct dsa_switch *, int, struct switchdev_obj_port_vlan *, int (*)(struct switchdev_obj *)) port_vlan_dump;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_fdb *, struct switchdev_trans *) port_fdb_prepare;
    void (*)(struct dsa_switch *, int, const struct switchdev_obj_port_fdb *, struct switchdev_trans *) port_fdb_add;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_fdb *) port_fdb_del;
    int (*)(struct dsa_switch *, int, struct switchdev_obj_port_fdb *, int (*)(struct switchdev_obj *)) port_fdb_dump;
}
```
</details>
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
struct dsa_switch_driver {
    struct list_head list;
    enum dsa_tag_protocol tag_protocol;
    const char * (*)(struct device *, struct device *, int, void * *) probe;
    int (*)(struct dsa_switch *) setup;
    int (*)(struct dsa_switch *, u8 *) set_addr;
    u32 (*)(struct dsa_switch *, int) get_phy_flags;
    int (*)(struct dsa_switch *, int, int) phy_read;
    int (*)(struct dsa_switch *, int, int, u16) phy_write;
    void (*)(struct dsa_switch *, int, struct phy_device *) adjust_link;
    void (*)(struct dsa_switch *, int, struct fixed_phy_status *) fixed_link_update;
    void (*)(struct dsa_switch *, int, uint8_t *) get_strings;
    void (*)(struct dsa_switch *, int, uint64_t *) get_ethtool_stats;
    int (*)(struct dsa_switch *) get_sset_count;
    void (*)(struct dsa_switch *, int, struct ethtool_wolinfo *) get_wol;
    int (*)(struct dsa_switch *, int, struct ethtool_wolinfo *) set_wol;
    int (*)(struct dsa_switch *) suspend;
    int (*)(struct dsa_switch *) resume;
    int (*)(struct dsa_switch *, int, struct phy_device *) port_enable;
    void (*)(struct dsa_switch *, int, struct phy_device *) port_disable;
    int (*)(struct dsa_switch *, int, struct phy_device *, struct ethtool_eee *) set_eee;
    int (*)(struct dsa_switch *, int, struct ethtool_eee *) get_eee;
    int (*)(struct dsa_switch *, int *) get_temp;
    int (*)(struct dsa_switch *, int *) get_temp_limit;
    int (*)(struct dsa_switch *, int) set_temp_limit;
    int (*)(struct dsa_switch *, bool *) get_temp_alarm;
    int (*)(struct dsa_switch *) get_eeprom_len;
    int (*)(struct dsa_switch *, struct ethtool_eeprom *, u8 *) get_eeprom;
    int (*)(struct dsa_switch *, struct ethtool_eeprom *, u8 *) set_eeprom;
    int (*)(struct dsa_switch *, int) get_regs_len;
    void (*)(struct dsa_switch *, int, struct ethtool_regs *, void *) get_regs;
    int (*)(struct dsa_switch *, unsigned int) set_ageing_time;
    int (*)(struct dsa_switch *, int, struct net_device *) port_bridge_join;
    void (*)(struct dsa_switch *, int) port_bridge_leave;
    void (*)(struct dsa_switch *, int, u8) port_stp_state_set;
    int (*)(struct dsa_switch *, int, bool) port_vlan_filtering;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_vlan *, struct switchdev_trans *) port_vlan_prepare;
    void (*)(struct dsa_switch *, int, const struct switchdev_obj_port_vlan *, struct switchdev_trans *) port_vlan_add;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_vlan *) port_vlan_del;
    int (*)(struct dsa_switch *, int, struct switchdev_obj_port_vlan *, int (*)(struct switchdev_obj *)) port_vlan_dump;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_fdb *, struct switchdev_trans *) port_fdb_prepare;
    void (*)(struct dsa_switch *, int, const struct switchdev_obj_port_fdb *, struct switchdev_trans *) port_fdb_add;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_fdb *) port_fdb_del;
    int (*)(struct dsa_switch *, int, struct switchdev_obj_port_fdb *, int (*)(struct switchdev_obj *)) port_fdb_dump;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➖</summary>

```c
struct dsa_switch_driver {
    struct list_head list;
    enum dsa_tag_protocol tag_protocol;
    const char * (*)(struct device *, struct device *, int, void * *) probe;
    int (*)(struct dsa_switch *) setup;
    int (*)(struct dsa_switch *, u8 *) set_addr;
    u32 (*)(struct dsa_switch *, int) get_phy_flags;
    int (*)(struct dsa_switch *, int, int) phy_read;
    int (*)(struct dsa_switch *, int, int, u16) phy_write;
    void (*)(struct dsa_switch *, int, struct phy_device *) adjust_link;
    void (*)(struct dsa_switch *, int, struct fixed_phy_status *) fixed_link_update;
    void (*)(struct dsa_switch *, int, uint8_t *) get_strings;
    void (*)(struct dsa_switch *, int, uint64_t *) get_ethtool_stats;
    int (*)(struct dsa_switch *) get_sset_count;
    void (*)(struct dsa_switch *, int, struct ethtool_wolinfo *) get_wol;
    int (*)(struct dsa_switch *, int, struct ethtool_wolinfo *) set_wol;
    int (*)(struct dsa_switch *) suspend;
    int (*)(struct dsa_switch *) resume;
    int (*)(struct dsa_switch *, int, struct phy_device *) port_enable;
    void (*)(struct dsa_switch *, int, struct phy_device *) port_disable;
    int (*)(struct dsa_switch *, int, struct phy_device *, struct ethtool_eee *) set_eee;
    int (*)(struct dsa_switch *, int, struct ethtool_eee *) get_eee;
    int (*)(struct dsa_switch *, int *) get_temp;
    int (*)(struct dsa_switch *, int *) get_temp_limit;
    int (*)(struct dsa_switch *, int) set_temp_limit;
    int (*)(struct dsa_switch *, bool *) get_temp_alarm;
    int (*)(struct dsa_switch *) get_eeprom_len;
    int (*)(struct dsa_switch *, struct ethtool_eeprom *, u8 *) get_eeprom;
    int (*)(struct dsa_switch *, struct ethtool_eeprom *, u8 *) set_eeprom;
    int (*)(struct dsa_switch *, int) get_regs_len;
    void (*)(struct dsa_switch *, int, struct ethtool_regs *, void *) get_regs;
    int (*)(struct dsa_switch *, unsigned int) set_ageing_time;
    int (*)(struct dsa_switch *, int, struct net_device *) port_bridge_join;
    void (*)(struct dsa_switch *, int) port_bridge_leave;
    void (*)(struct dsa_switch *, int, u8) port_stp_state_set;
    int (*)(struct dsa_switch *, int, bool) port_vlan_filtering;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_vlan *, struct switchdev_trans *) port_vlan_prepare;
    void (*)(struct dsa_switch *, int, const struct switchdev_obj_port_vlan *, struct switchdev_trans *) port_vlan_add;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_vlan *) port_vlan_del;
    int (*)(struct dsa_switch *, int, struct switchdev_obj_port_vlan *, int (*)(struct switchdev_obj *)) port_vlan_dump;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_fdb *, struct switchdev_trans *) port_fdb_prepare;
    void (*)(struct dsa_switch *, int, const struct switchdev_obj_port_fdb *, struct switchdev_trans *) port_fdb_add;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_fdb *) port_fdb_del;
    int (*)(struct dsa_switch *, int, struct switchdev_obj_port_fdb *, int (*)(struct switchdev_obj *)) port_fdb_dump;
}
```
</details>
</li>
</ul>
