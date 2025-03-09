# Struct: <code>dsa_switch_ops</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct dsa_switch_ops {
    struct list_head list;
    const char * (*)(struct device *, struct device *, int, void * *) probe;
    enum dsa_tag_protocol (*)(struct dsa_switch *) get_tag_protocol;
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
    void (*)(struct dsa_switch *, int) port_fast_age;
    int (*)(struct dsa_switch *, int, bool) port_vlan_filtering;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_vlan *, struct switchdev_trans *) port_vlan_prepare;
    void (*)(struct dsa_switch *, int, const struct switchdev_obj_port_vlan *, struct switchdev_trans *) port_vlan_add;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_vlan *) port_vlan_del;
    int (*)(struct dsa_switch *, int, struct switchdev_obj_port_vlan *, int (*)(struct switchdev_obj *)) port_vlan_dump;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_fdb *, struct switchdev_trans *) port_fdb_prepare;
    void (*)(struct dsa_switch *, int, const struct switchdev_obj_port_fdb *, struct switchdev_trans *) port_fdb_add;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_fdb *) port_fdb_del;
    int (*)(struct dsa_switch *, int, struct switchdev_obj_port_fdb *, int (*)(struct switchdev_obj *)) port_fdb_dump;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_mdb *, struct switchdev_trans *) port_mdb_prepare;
    void (*)(struct dsa_switch *, int, const struct switchdev_obj_port_mdb *, struct switchdev_trans *) port_mdb_add;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_mdb *) port_mdb_del;
    int (*)(struct dsa_switch *, int, struct switchdev_obj_port_mdb *, int (*)(struct switchdev_obj *)) port_mdb_dump;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct dsa_switch_ops {
    const char * (*)(struct device *, struct device *, int, void * *) probe;
    enum dsa_tag_protocol (*)(struct dsa_switch *) get_tag_protocol;
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
    int (*)(struct dsa_switch *) get_eeprom_len;
    int (*)(struct dsa_switch *, struct ethtool_eeprom *, u8 *) get_eeprom;
    int (*)(struct dsa_switch *, struct ethtool_eeprom *, u8 *) set_eeprom;
    int (*)(struct dsa_switch *, int) get_regs_len;
    void (*)(struct dsa_switch *, int, struct ethtool_regs *, void *) get_regs;
    int (*)(struct dsa_switch *, unsigned int) set_ageing_time;
    int (*)(struct dsa_switch *, int, struct net_device *) port_bridge_join;
    void (*)(struct dsa_switch *, int, struct net_device *) port_bridge_leave;
    void (*)(struct dsa_switch *, int, u8) port_stp_state_set;
    void (*)(struct dsa_switch *, int) port_fast_age;
    int (*)(struct dsa_switch *, int, bool) port_vlan_filtering;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_vlan *, struct switchdev_trans *) port_vlan_prepare;
    void (*)(struct dsa_switch *, int, const struct switchdev_obj_port_vlan *, struct switchdev_trans *) port_vlan_add;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_vlan *) port_vlan_del;
    int (*)(struct dsa_switch *, int, struct switchdev_obj_port_vlan *, switchdev_obj_dump_cb_t *) port_vlan_dump;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_fdb *, struct switchdev_trans *) port_fdb_prepare;
    void (*)(struct dsa_switch *, int, const struct switchdev_obj_port_fdb *, struct switchdev_trans *) port_fdb_add;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_fdb *) port_fdb_del;
    int (*)(struct dsa_switch *, int, struct switchdev_obj_port_fdb *, switchdev_obj_dump_cb_t *) port_fdb_dump;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_mdb *, struct switchdev_trans *) port_mdb_prepare;
    void (*)(struct dsa_switch *, int, const struct switchdev_obj_port_mdb *, struct switchdev_trans *) port_mdb_add;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_mdb *) port_mdb_del;
    int (*)(struct dsa_switch *, int, struct switchdev_obj_port_mdb *, switchdev_obj_dump_cb_t *) port_mdb_dump;
    int (*)(struct dsa_switch *, int, struct ethtool_rxnfc *, u32 *) get_rxnfc;
    int (*)(struct dsa_switch *, int, struct ethtool_rxnfc *) set_rxnfc;
    int (*)(struct dsa_switch *, int, struct dsa_mall_mirror_tc_entry *, bool) port_mirror_add;
    void (*)(struct dsa_switch *, int, struct dsa_mall_mirror_tc_entry *) port_mirror_del;
    int (*)(struct dsa_switch *, int, int, struct net_device *) crosschip_bridge_join;
    void (*)(struct dsa_switch *, int, int, struct net_device *) crosschip_bridge_leave;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct dsa_switch_ops {
    const char * (*)(struct device *, struct device *, int, void * *) probe;
    enum dsa_tag_protocol (*)(struct dsa_switch *, int) get_tag_protocol;
    int (*)(struct dsa_switch *) setup;
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
    int (*)(struct dsa_switch *, int, struct ethtool_eee *) set_mac_eee;
    int (*)(struct dsa_switch *, int, struct ethtool_eee *) get_mac_eee;
    int (*)(struct dsa_switch *) get_eeprom_len;
    int (*)(struct dsa_switch *, struct ethtool_eeprom *, u8 *) get_eeprom;
    int (*)(struct dsa_switch *, struct ethtool_eeprom *, u8 *) set_eeprom;
    int (*)(struct dsa_switch *, int) get_regs_len;
    void (*)(struct dsa_switch *, int, struct ethtool_regs *, void *) get_regs;
    int (*)(struct dsa_switch *, unsigned int) set_ageing_time;
    int (*)(struct dsa_switch *, int, struct net_device *) port_bridge_join;
    void (*)(struct dsa_switch *, int, struct net_device *) port_bridge_leave;
    void (*)(struct dsa_switch *, int, u8) port_stp_state_set;
    void (*)(struct dsa_switch *, int) port_fast_age;
    int (*)(struct dsa_switch *, int, bool) port_vlan_filtering;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_vlan *, struct switchdev_trans *) port_vlan_prepare;
    void (*)(struct dsa_switch *, int, const struct switchdev_obj_port_vlan *, struct switchdev_trans *) port_vlan_add;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_vlan *) port_vlan_del;
    int (*)(struct dsa_switch *, int, const unsigned char *, u16) port_fdb_add;
    int (*)(struct dsa_switch *, int, const unsigned char *, u16) port_fdb_del;
    int (*)(struct dsa_switch *, int, dsa_fdb_dump_cb_t *, void *) port_fdb_dump;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_mdb *, struct switchdev_trans *) port_mdb_prepare;
    void (*)(struct dsa_switch *, int, const struct switchdev_obj_port_mdb *, struct switchdev_trans *) port_mdb_add;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_mdb *) port_mdb_del;
    int (*)(struct dsa_switch *, int, struct ethtool_rxnfc *, u32 *) get_rxnfc;
    int (*)(struct dsa_switch *, int, struct ethtool_rxnfc *) set_rxnfc;
    int (*)(struct dsa_switch *, int, struct dsa_mall_mirror_tc_entry *, bool) port_mirror_add;
    void (*)(struct dsa_switch *, int, struct dsa_mall_mirror_tc_entry *) port_mirror_del;
    int (*)(struct dsa_switch *, int, int, struct net_device *) crosschip_bridge_join;
    void (*)(struct dsa_switch *, int, int, struct net_device *) crosschip_bridge_leave;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct dsa_switch_ops {
    const char * (*)(struct device *, struct device *, int, void * *) probe;
    enum dsa_tag_protocol (*)(struct dsa_switch *, int) get_tag_protocol;
    int (*)(struct dsa_switch *) setup;
    u32 (*)(struct dsa_switch *, int) get_phy_flags;
    int (*)(struct dsa_switch *, int, int) phy_read;
    int (*)(struct dsa_switch *, int, int, u16) phy_write;
    void (*)(struct dsa_switch *, int, struct phy_device *) adjust_link;
    void (*)(struct dsa_switch *, int, struct fixed_phy_status *) fixed_link_update;
    void (*)(struct dsa_switch *, int, long unsigned int *, struct phylink_link_state *) phylink_validate;
    int (*)(struct dsa_switch *, int, struct phylink_link_state *) phylink_mac_link_state;
    void (*)(struct dsa_switch *, int, unsigned int, const struct phylink_link_state *) phylink_mac_config;
    void (*)(struct dsa_switch *, int) phylink_mac_an_restart;
    void (*)(struct dsa_switch *, int, unsigned int, phy_interface_t) phylink_mac_link_down;
    void (*)(struct dsa_switch *, int, unsigned int, phy_interface_t, struct phy_device *) phylink_mac_link_up;
    void (*)(struct dsa_switch *, int, struct phylink_link_state *) phylink_fixed_state;
    void (*)(struct dsa_switch *, int, u32, uint8_t *) get_strings;
    void (*)(struct dsa_switch *, int, uint64_t *) get_ethtool_stats;
    int (*)(struct dsa_switch *, int, int) get_sset_count;
    void (*)(struct dsa_switch *, int, uint64_t *) get_ethtool_phy_stats;
    void (*)(struct dsa_switch *, int, struct ethtool_wolinfo *) get_wol;
    int (*)(struct dsa_switch *, int, struct ethtool_wolinfo *) set_wol;
    int (*)(struct dsa_switch *, int, struct ethtool_ts_info *) get_ts_info;
    int (*)(struct dsa_switch *) suspend;
    int (*)(struct dsa_switch *) resume;
    int (*)(struct dsa_switch *, int, struct phy_device *) port_enable;
    void (*)(struct dsa_switch *, int, struct phy_device *) port_disable;
    int (*)(struct dsa_switch *, int, struct ethtool_eee *) set_mac_eee;
    int (*)(struct dsa_switch *, int, struct ethtool_eee *) get_mac_eee;
    int (*)(struct dsa_switch *) get_eeprom_len;
    int (*)(struct dsa_switch *, struct ethtool_eeprom *, u8 *) get_eeprom;
    int (*)(struct dsa_switch *, struct ethtool_eeprom *, u8 *) set_eeprom;
    int (*)(struct dsa_switch *, int) get_regs_len;
    void (*)(struct dsa_switch *, int, struct ethtool_regs *, void *) get_regs;
    int (*)(struct dsa_switch *, unsigned int) set_ageing_time;
    int (*)(struct dsa_switch *, int, struct net_device *) port_bridge_join;
    void (*)(struct dsa_switch *, int, struct net_device *) port_bridge_leave;
    void (*)(struct dsa_switch *, int, u8) port_stp_state_set;
    void (*)(struct dsa_switch *, int) port_fast_age;
    int (*)(struct dsa_switch *, int, bool) port_vlan_filtering;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_vlan *) port_vlan_prepare;
    void (*)(struct dsa_switch *, int, const struct switchdev_obj_port_vlan *) port_vlan_add;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_vlan *) port_vlan_del;
    int (*)(struct dsa_switch *, int, const unsigned char *, u16) port_fdb_add;
    int (*)(struct dsa_switch *, int, const unsigned char *, u16) port_fdb_del;
    int (*)(struct dsa_switch *, int, dsa_fdb_dump_cb_t *, void *) port_fdb_dump;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_mdb *) port_mdb_prepare;
    void (*)(struct dsa_switch *, int, const struct switchdev_obj_port_mdb *) port_mdb_add;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_mdb *) port_mdb_del;
    int (*)(struct dsa_switch *, int, struct ethtool_rxnfc *, u32 *) get_rxnfc;
    int (*)(struct dsa_switch *, int, struct ethtool_rxnfc *) set_rxnfc;
    int (*)(struct dsa_switch *, int, struct dsa_mall_mirror_tc_entry *, bool) port_mirror_add;
    void (*)(struct dsa_switch *, int, struct dsa_mall_mirror_tc_entry *) port_mirror_del;
    int (*)(struct dsa_switch *, int, int, struct net_device *) crosschip_bridge_join;
    void (*)(struct dsa_switch *, int, int, struct net_device *) crosschip_bridge_leave;
    int (*)(struct dsa_switch *, int, struct ifreq *) port_hwtstamp_get;
    int (*)(struct dsa_switch *, int, struct ifreq *) port_hwtstamp_set;
    bool (*)(struct dsa_switch *, int, struct sk_buff *, unsigned int) port_txtstamp;
    bool (*)(struct dsa_switch *, int, struct sk_buff *, unsigned int) port_rxtstamp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct dsa_switch_ops {
    const char * (*)(struct device *, struct device *, int, void * *) probe;
    enum dsa_tag_protocol (*)(struct dsa_switch *, int) get_tag_protocol;
    int (*)(struct dsa_switch *) setup;
    u32 (*)(struct dsa_switch *, int) get_phy_flags;
    int (*)(struct dsa_switch *, int, int) phy_read;
    int (*)(struct dsa_switch *, int, int, u16) phy_write;
    void (*)(struct dsa_switch *, int, struct phy_device *) adjust_link;
    void (*)(struct dsa_switch *, int, struct fixed_phy_status *) fixed_link_update;
    void (*)(struct dsa_switch *, int, long unsigned int *, struct phylink_link_state *) phylink_validate;
    int (*)(struct dsa_switch *, int, struct phylink_link_state *) phylink_mac_link_state;
    void (*)(struct dsa_switch *, int, unsigned int, const struct phylink_link_state *) phylink_mac_config;
    void (*)(struct dsa_switch *, int) phylink_mac_an_restart;
    void (*)(struct dsa_switch *, int, unsigned int, phy_interface_t) phylink_mac_link_down;
    void (*)(struct dsa_switch *, int, unsigned int, phy_interface_t, struct phy_device *) phylink_mac_link_up;
    void (*)(struct dsa_switch *, int, struct phylink_link_state *) phylink_fixed_state;
    void (*)(struct dsa_switch *, int, u32, uint8_t *) get_strings;
    void (*)(struct dsa_switch *, int, uint64_t *) get_ethtool_stats;
    int (*)(struct dsa_switch *, int, int) get_sset_count;
    void (*)(struct dsa_switch *, int, uint64_t *) get_ethtool_phy_stats;
    void (*)(struct dsa_switch *, int, struct ethtool_wolinfo *) get_wol;
    int (*)(struct dsa_switch *, int, struct ethtool_wolinfo *) set_wol;
    int (*)(struct dsa_switch *, int, struct ethtool_ts_info *) get_ts_info;
    int (*)(struct dsa_switch *) suspend;
    int (*)(struct dsa_switch *) resume;
    int (*)(struct dsa_switch *, int, struct phy_device *) port_enable;
    void (*)(struct dsa_switch *, int, struct phy_device *) port_disable;
    int (*)(struct dsa_switch *, int, struct ethtool_eee *) set_mac_eee;
    int (*)(struct dsa_switch *, int, struct ethtool_eee *) get_mac_eee;
    int (*)(struct dsa_switch *) get_eeprom_len;
    int (*)(struct dsa_switch *, struct ethtool_eeprom *, u8 *) get_eeprom;
    int (*)(struct dsa_switch *, struct ethtool_eeprom *, u8 *) set_eeprom;
    int (*)(struct dsa_switch *, int) get_regs_len;
    void (*)(struct dsa_switch *, int, struct ethtool_regs *, void *) get_regs;
    int (*)(struct dsa_switch *, unsigned int) set_ageing_time;
    int (*)(struct dsa_switch *, int, struct net_device *) port_bridge_join;
    void (*)(struct dsa_switch *, int, struct net_device *) port_bridge_leave;
    void (*)(struct dsa_switch *, int, u8) port_stp_state_set;
    void (*)(struct dsa_switch *, int) port_fast_age;
    int (*)(struct dsa_switch *, int, bool) port_vlan_filtering;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_vlan *) port_vlan_prepare;
    void (*)(struct dsa_switch *, int, const struct switchdev_obj_port_vlan *) port_vlan_add;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_vlan *) port_vlan_del;
    int (*)(struct dsa_switch *, int, const unsigned char *, u16) port_fdb_add;
    int (*)(struct dsa_switch *, int, const unsigned char *, u16) port_fdb_del;
    int (*)(struct dsa_switch *, int, dsa_fdb_dump_cb_t *, void *) port_fdb_dump;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_mdb *) port_mdb_prepare;
    void (*)(struct dsa_switch *, int, const struct switchdev_obj_port_mdb *) port_mdb_add;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_mdb *) port_mdb_del;
    int (*)(struct dsa_switch *, int, struct ethtool_rxnfc *, u32 *) get_rxnfc;
    int (*)(struct dsa_switch *, int, struct ethtool_rxnfc *) set_rxnfc;
    int (*)(struct dsa_switch *, int, struct dsa_mall_mirror_tc_entry *, bool) port_mirror_add;
    void (*)(struct dsa_switch *, int, struct dsa_mall_mirror_tc_entry *) port_mirror_del;
    int (*)(struct dsa_switch *, int, int, struct net_device *) crosschip_bridge_join;
    void (*)(struct dsa_switch *, int, int, struct net_device *) crosschip_bridge_leave;
    int (*)(struct dsa_switch *, int, struct ifreq *) port_hwtstamp_get;
    int (*)(struct dsa_switch *, int, struct ifreq *) port_hwtstamp_set;
    bool (*)(struct dsa_switch *, int, struct sk_buff *, unsigned int) port_txtstamp;
    bool (*)(struct dsa_switch *, int, struct sk_buff *, unsigned int) port_rxtstamp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct dsa_switch_ops {
    enum dsa_tag_protocol (*)(struct dsa_switch *, int) get_tag_protocol;
    int (*)(struct dsa_switch *) setup;
    void (*)(struct dsa_switch *) teardown;
    u32 (*)(struct dsa_switch *, int) get_phy_flags;
    int (*)(struct dsa_switch *, int, int) phy_read;
    int (*)(struct dsa_switch *, int, int, u16) phy_write;
    void (*)(struct dsa_switch *, int, struct phy_device *) adjust_link;
    void (*)(struct dsa_switch *, int, struct fixed_phy_status *) fixed_link_update;
    void (*)(struct dsa_switch *, int, long unsigned int *, struct phylink_link_state *) phylink_validate;
    int (*)(struct dsa_switch *, int, struct phylink_link_state *) phylink_mac_link_state;
    void (*)(struct dsa_switch *, int, unsigned int, const struct phylink_link_state *) phylink_mac_config;
    void (*)(struct dsa_switch *, int) phylink_mac_an_restart;
    void (*)(struct dsa_switch *, int, unsigned int, phy_interface_t) phylink_mac_link_down;
    void (*)(struct dsa_switch *, int, unsigned int, phy_interface_t, struct phy_device *) phylink_mac_link_up;
    void (*)(struct dsa_switch *, int, struct phylink_link_state *) phylink_fixed_state;
    void (*)(struct dsa_switch *, int, u32, uint8_t *) get_strings;
    void (*)(struct dsa_switch *, int, uint64_t *) get_ethtool_stats;
    int (*)(struct dsa_switch *, int, int) get_sset_count;
    void (*)(struct dsa_switch *, int, uint64_t *) get_ethtool_phy_stats;
    void (*)(struct dsa_switch *, int, struct ethtool_wolinfo *) get_wol;
    int (*)(struct dsa_switch *, int, struct ethtool_wolinfo *) set_wol;
    int (*)(struct dsa_switch *, int, struct ethtool_ts_info *) get_ts_info;
    int (*)(struct dsa_switch *) suspend;
    int (*)(struct dsa_switch *) resume;
    int (*)(struct dsa_switch *, int, struct phy_device *) port_enable;
    void (*)(struct dsa_switch *, int) port_disable;
    int (*)(struct dsa_switch *, int, struct ethtool_eee *) set_mac_eee;
    int (*)(struct dsa_switch *, int, struct ethtool_eee *) get_mac_eee;
    int (*)(struct dsa_switch *) get_eeprom_len;
    int (*)(struct dsa_switch *, struct ethtool_eeprom *, u8 *) get_eeprom;
    int (*)(struct dsa_switch *, struct ethtool_eeprom *, u8 *) set_eeprom;
    int (*)(struct dsa_switch *, int) get_regs_len;
    void (*)(struct dsa_switch *, int, struct ethtool_regs *, void *) get_regs;
    int (*)(struct dsa_switch *, unsigned int) set_ageing_time;
    int (*)(struct dsa_switch *, int, struct net_device *) port_bridge_join;
    void (*)(struct dsa_switch *, int, struct net_device *) port_bridge_leave;
    void (*)(struct dsa_switch *, int, u8) port_stp_state_set;
    void (*)(struct dsa_switch *, int) port_fast_age;
    int (*)(struct dsa_switch *, int, bool, bool) port_egress_floods;
    int (*)(struct dsa_switch *, int, bool) port_vlan_filtering;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_vlan *) port_vlan_prepare;
    void (*)(struct dsa_switch *, int, const struct switchdev_obj_port_vlan *) port_vlan_add;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_vlan *) port_vlan_del;
    int (*)(struct dsa_switch *, int, const unsigned char *, u16) port_fdb_add;
    int (*)(struct dsa_switch *, int, const unsigned char *, u16) port_fdb_del;
    int (*)(struct dsa_switch *, int, dsa_fdb_dump_cb_t *, void *) port_fdb_dump;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_mdb *) port_mdb_prepare;
    void (*)(struct dsa_switch *, int, const struct switchdev_obj_port_mdb *) port_mdb_add;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_mdb *) port_mdb_del;
    int (*)(struct dsa_switch *, int, struct ethtool_rxnfc *, u32 *) get_rxnfc;
    int (*)(struct dsa_switch *, int, struct ethtool_rxnfc *) set_rxnfc;
    int (*)(struct dsa_switch *, int, struct dsa_mall_mirror_tc_entry *, bool) port_mirror_add;
    void (*)(struct dsa_switch *, int, struct dsa_mall_mirror_tc_entry *) port_mirror_del;
    int (*)(struct dsa_switch *, int, int, struct net_device *) crosschip_bridge_join;
    void (*)(struct dsa_switch *, int, int, struct net_device *) crosschip_bridge_leave;
    int (*)(struct dsa_switch *, int, struct ifreq *) port_hwtstamp_get;
    int (*)(struct dsa_switch *, int, struct ifreq *) port_hwtstamp_set;
    bool (*)(struct dsa_switch *, int, struct sk_buff *, unsigned int) port_txtstamp;
    bool (*)(struct dsa_switch *, int, struct sk_buff *, unsigned int) port_rxtstamp;
    netdev_tx_t (*)(struct dsa_switch *, int, struct sk_buff *) port_deferred_xmit;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct dsa_switch_ops {
    enum dsa_tag_protocol (*)(struct dsa_switch *, int) get_tag_protocol;
    int (*)(struct dsa_switch *) setup;
    void (*)(struct dsa_switch *) teardown;
    u32 (*)(struct dsa_switch *, int) get_phy_flags;
    int (*)(struct dsa_switch *, int, int) phy_read;
    int (*)(struct dsa_switch *, int, int, u16) phy_write;
    void (*)(struct dsa_switch *, int, struct phy_device *) adjust_link;
    void (*)(struct dsa_switch *, int, struct fixed_phy_status *) fixed_link_update;
    void (*)(struct dsa_switch *, int, long unsigned int *, struct phylink_link_state *) phylink_validate;
    int (*)(struct dsa_switch *, int, struct phylink_link_state *) phylink_mac_link_state;
    void (*)(struct dsa_switch *, int, unsigned int, const struct phylink_link_state *) phylink_mac_config;
    void (*)(struct dsa_switch *, int) phylink_mac_an_restart;
    void (*)(struct dsa_switch *, int, unsigned int, phy_interface_t) phylink_mac_link_down;
    void (*)(struct dsa_switch *, int, unsigned int, phy_interface_t, struct phy_device *) phylink_mac_link_up;
    void (*)(struct dsa_switch *, int, struct phylink_link_state *) phylink_fixed_state;
    void (*)(struct dsa_switch *, int, u32, uint8_t *) get_strings;
    void (*)(struct dsa_switch *, int, uint64_t *) get_ethtool_stats;
    int (*)(struct dsa_switch *, int, int) get_sset_count;
    void (*)(struct dsa_switch *, int, uint64_t *) get_ethtool_phy_stats;
    void (*)(struct dsa_switch *, int, struct ethtool_wolinfo *) get_wol;
    int (*)(struct dsa_switch *, int, struct ethtool_wolinfo *) set_wol;
    int (*)(struct dsa_switch *, int, struct ethtool_ts_info *) get_ts_info;
    int (*)(struct dsa_switch *) suspend;
    int (*)(struct dsa_switch *) resume;
    int (*)(struct dsa_switch *, int, struct phy_device *) port_enable;
    void (*)(struct dsa_switch *, int) port_disable;
    int (*)(struct dsa_switch *, int, struct ethtool_eee *) set_mac_eee;
    int (*)(struct dsa_switch *, int, struct ethtool_eee *) get_mac_eee;
    int (*)(struct dsa_switch *) get_eeprom_len;
    int (*)(struct dsa_switch *, struct ethtool_eeprom *, u8 *) get_eeprom;
    int (*)(struct dsa_switch *, struct ethtool_eeprom *, u8 *) set_eeprom;
    int (*)(struct dsa_switch *, int) get_regs_len;
    void (*)(struct dsa_switch *, int, struct ethtool_regs *, void *) get_regs;
    int (*)(struct dsa_switch *, unsigned int) set_ageing_time;
    int (*)(struct dsa_switch *, int, struct net_device *) port_bridge_join;
    void (*)(struct dsa_switch *, int, struct net_device *) port_bridge_leave;
    void (*)(struct dsa_switch *, int, u8) port_stp_state_set;
    void (*)(struct dsa_switch *, int) port_fast_age;
    int (*)(struct dsa_switch *, int, bool, bool) port_egress_floods;
    int (*)(struct dsa_switch *, int, bool) port_vlan_filtering;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_vlan *) port_vlan_prepare;
    void (*)(struct dsa_switch *, int, const struct switchdev_obj_port_vlan *) port_vlan_add;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_vlan *) port_vlan_del;
    int (*)(struct dsa_switch *, int, const unsigned char *, u16) port_fdb_add;
    int (*)(struct dsa_switch *, int, const unsigned char *, u16) port_fdb_del;
    int (*)(struct dsa_switch *, int, dsa_fdb_dump_cb_t *, void *) port_fdb_dump;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_mdb *) port_mdb_prepare;
    void (*)(struct dsa_switch *, int, const struct switchdev_obj_port_mdb *) port_mdb_add;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_mdb *) port_mdb_del;
    int (*)(struct dsa_switch *, int, struct ethtool_rxnfc *, u32 *) get_rxnfc;
    int (*)(struct dsa_switch *, int, struct ethtool_rxnfc *) set_rxnfc;
    int (*)(struct dsa_switch *, int, struct dsa_mall_mirror_tc_entry *, bool) port_mirror_add;
    void (*)(struct dsa_switch *, int, struct dsa_mall_mirror_tc_entry *) port_mirror_del;
    int (*)(struct dsa_switch *, int, enum tc_setup_type, void *) port_setup_tc;
    int (*)(struct dsa_switch *, int, int, struct net_device *) crosschip_bridge_join;
    void (*)(struct dsa_switch *, int, int, struct net_device *) crosschip_bridge_leave;
    int (*)(struct dsa_switch *, int, struct ifreq *) port_hwtstamp_get;
    int (*)(struct dsa_switch *, int, struct ifreq *) port_hwtstamp_set;
    bool (*)(struct dsa_switch *, int, struct sk_buff *, unsigned int) port_txtstamp;
    bool (*)(struct dsa_switch *, int, struct sk_buff *, unsigned int) port_rxtstamp;
    netdev_tx_t (*)(struct dsa_switch *, int, struct sk_buff *) port_deferred_xmit;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct dsa_switch_ops {
    enum dsa_tag_protocol (*)(struct dsa_switch *, int, enum dsa_tag_protocol) get_tag_protocol;
    int (*)(struct dsa_switch *) setup;
    void (*)(struct dsa_switch *) teardown;
    u32 (*)(struct dsa_switch *, int) get_phy_flags;
    int (*)(struct dsa_switch *, int, int) phy_read;
    int (*)(struct dsa_switch *, int, int, u16) phy_write;
    void (*)(struct dsa_switch *, int, struct phy_device *) adjust_link;
    void (*)(struct dsa_switch *, int, struct fixed_phy_status *) fixed_link_update;
    void (*)(struct dsa_switch *, int, long unsigned int *, struct phylink_link_state *) phylink_validate;
    int (*)(struct dsa_switch *, int, struct phylink_link_state *) phylink_mac_link_state;
    void (*)(struct dsa_switch *, int, unsigned int, const struct phylink_link_state *) phylink_mac_config;
    void (*)(struct dsa_switch *, int) phylink_mac_an_restart;
    void (*)(struct dsa_switch *, int, unsigned int, phy_interface_t) phylink_mac_link_down;
    void (*)(struct dsa_switch *, int, unsigned int, phy_interface_t, struct phy_device *, int, int, bool, bool) phylink_mac_link_up;
    void (*)(struct dsa_switch *, int, struct phylink_link_state *) phylink_fixed_state;
    void (*)(struct dsa_switch *, int, u32, uint8_t *) get_strings;
    void (*)(struct dsa_switch *, int, uint64_t *) get_ethtool_stats;
    int (*)(struct dsa_switch *, int, int) get_sset_count;
    void (*)(struct dsa_switch *, int, uint64_t *) get_ethtool_phy_stats;
    void (*)(struct dsa_switch *, int, struct ethtool_wolinfo *) get_wol;
    int (*)(struct dsa_switch *, int, struct ethtool_wolinfo *) set_wol;
    int (*)(struct dsa_switch *, int, struct ethtool_ts_info *) get_ts_info;
    int (*)(struct dsa_switch *) suspend;
    int (*)(struct dsa_switch *) resume;
    int (*)(struct dsa_switch *, int, struct phy_device *) port_enable;
    void (*)(struct dsa_switch *, int) port_disable;
    int (*)(struct dsa_switch *, int, struct ethtool_eee *) set_mac_eee;
    int (*)(struct dsa_switch *, int, struct ethtool_eee *) get_mac_eee;
    int (*)(struct dsa_switch *) get_eeprom_len;
    int (*)(struct dsa_switch *, struct ethtool_eeprom *, u8 *) get_eeprom;
    int (*)(struct dsa_switch *, struct ethtool_eeprom *, u8 *) set_eeprom;
    int (*)(struct dsa_switch *, int) get_regs_len;
    void (*)(struct dsa_switch *, int, struct ethtool_regs *, void *) get_regs;
    int (*)(struct dsa_switch *, unsigned int) set_ageing_time;
    int (*)(struct dsa_switch *, int, struct net_device *) port_bridge_join;
    void (*)(struct dsa_switch *, int, struct net_device *) port_bridge_leave;
    void (*)(struct dsa_switch *, int, u8) port_stp_state_set;
    void (*)(struct dsa_switch *, int) port_fast_age;
    int (*)(struct dsa_switch *, int, bool, bool) port_egress_floods;
    int (*)(struct dsa_switch *, int, bool) port_vlan_filtering;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_vlan *) port_vlan_prepare;
    void (*)(struct dsa_switch *, int, const struct switchdev_obj_port_vlan *) port_vlan_add;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_vlan *) port_vlan_del;
    int (*)(struct dsa_switch *, int, const unsigned char *, u16) port_fdb_add;
    int (*)(struct dsa_switch *, int, const unsigned char *, u16) port_fdb_del;
    int (*)(struct dsa_switch *, int, dsa_fdb_dump_cb_t *, void *) port_fdb_dump;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_mdb *) port_mdb_prepare;
    void (*)(struct dsa_switch *, int, const struct switchdev_obj_port_mdb *) port_mdb_add;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_mdb *) port_mdb_del;
    int (*)(struct dsa_switch *, int, struct ethtool_rxnfc *, u32 *) get_rxnfc;
    int (*)(struct dsa_switch *, int, struct ethtool_rxnfc *) set_rxnfc;
    int (*)(struct dsa_switch *, int, struct flow_cls_offload *, bool) cls_flower_add;
    int (*)(struct dsa_switch *, int, struct flow_cls_offload *, bool) cls_flower_del;
    int (*)(struct dsa_switch *, int, struct flow_cls_offload *, bool) cls_flower_stats;
    int (*)(struct dsa_switch *, int, struct dsa_mall_mirror_tc_entry *, bool) port_mirror_add;
    void (*)(struct dsa_switch *, int, struct dsa_mall_mirror_tc_entry *) port_mirror_del;
    int (*)(struct dsa_switch *, int, struct dsa_mall_policer_tc_entry *) port_policer_add;
    void (*)(struct dsa_switch *, int) port_policer_del;
    int (*)(struct dsa_switch *, int, enum tc_setup_type, void *) port_setup_tc;
    int (*)(struct dsa_switch *, int, int, int, struct net_device *) crosschip_bridge_join;
    void (*)(struct dsa_switch *, int, int, int, struct net_device *) crosschip_bridge_leave;
    int (*)(struct dsa_switch *, int, struct ifreq *) port_hwtstamp_get;
    int (*)(struct dsa_switch *, int, struct ifreq *) port_hwtstamp_set;
    bool (*)(struct dsa_switch *, int, struct sk_buff *, unsigned int) port_txtstamp;
    bool (*)(struct dsa_switch *, int, struct sk_buff *, unsigned int) port_rxtstamp;
    int (*)(struct dsa_switch *, u32, struct devlink_param_gset_ctx *) devlink_param_get;
    int (*)(struct dsa_switch *, u32, struct devlink_param_gset_ctx *) devlink_param_set;
    int (*)(struct dsa_switch *, int, int) port_change_mtu;
    int (*)(struct dsa_switch *, int) port_max_mtu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct dsa_switch_ops {
    enum dsa_tag_protocol (*)(struct dsa_switch *, int, enum dsa_tag_protocol) get_tag_protocol;
    int (*)(struct dsa_switch *) setup;
    void (*)(struct dsa_switch *) teardown;
    u32 (*)(struct dsa_switch *, int) get_phy_flags;
    int (*)(struct dsa_switch *, int, int) phy_read;
    int (*)(struct dsa_switch *, int, int, u16) phy_write;
    void (*)(struct dsa_switch *, int, struct phy_device *) adjust_link;
    void (*)(struct dsa_switch *, int, struct fixed_phy_status *) fixed_link_update;
    void (*)(struct dsa_switch *, int, long unsigned int *, struct phylink_link_state *) phylink_validate;
    int (*)(struct dsa_switch *, int, struct phylink_link_state *) phylink_mac_link_state;
    void (*)(struct dsa_switch *, int, unsigned int, const struct phylink_link_state *) phylink_mac_config;
    void (*)(struct dsa_switch *, int) phylink_mac_an_restart;
    void (*)(struct dsa_switch *, int, unsigned int, phy_interface_t) phylink_mac_link_down;
    void (*)(struct dsa_switch *, int, unsigned int, phy_interface_t, struct phy_device *, int, int, bool, bool) phylink_mac_link_up;
    void (*)(struct dsa_switch *, int, struct phylink_link_state *) phylink_fixed_state;
    void (*)(struct dsa_switch *, int, u32, uint8_t *) get_strings;
    void (*)(struct dsa_switch *, int, uint64_t *) get_ethtool_stats;
    int (*)(struct dsa_switch *, int, int) get_sset_count;
    void (*)(struct dsa_switch *, int, uint64_t *) get_ethtool_phy_stats;
    void (*)(struct dsa_switch *, int, struct ethtool_wolinfo *) get_wol;
    int (*)(struct dsa_switch *, int, struct ethtool_wolinfo *) set_wol;
    int (*)(struct dsa_switch *, int, struct ethtool_ts_info *) get_ts_info;
    int (*)(struct dsa_switch *) suspend;
    int (*)(struct dsa_switch *) resume;
    int (*)(struct dsa_switch *, int, struct phy_device *) port_enable;
    void (*)(struct dsa_switch *, int) port_disable;
    int (*)(struct dsa_switch *, int, struct ethtool_eee *) set_mac_eee;
    int (*)(struct dsa_switch *, int, struct ethtool_eee *) get_mac_eee;
    int (*)(struct dsa_switch *) get_eeprom_len;
    int (*)(struct dsa_switch *, struct ethtool_eeprom *, u8 *) get_eeprom;
    int (*)(struct dsa_switch *, struct ethtool_eeprom *, u8 *) set_eeprom;
    int (*)(struct dsa_switch *, int) get_regs_len;
    void (*)(struct dsa_switch *, int, struct ethtool_regs *, void *) get_regs;
    int (*)(struct dsa_switch *, int, struct netdev_notifier_changeupper_info *) port_prechangeupper;
    int (*)(struct dsa_switch *, unsigned int) set_ageing_time;
    int (*)(struct dsa_switch *, int, struct net_device *) port_bridge_join;
    void (*)(struct dsa_switch *, int, struct net_device *) port_bridge_leave;
    void (*)(struct dsa_switch *, int, u8) port_stp_state_set;
    void (*)(struct dsa_switch *, int) port_fast_age;
    int (*)(struct dsa_switch *, int, bool, bool) port_egress_floods;
    int (*)(struct dsa_switch *, int, bool, struct switchdev_trans *) port_vlan_filtering;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_vlan *) port_vlan_prepare;
    void (*)(struct dsa_switch *, int, const struct switchdev_obj_port_vlan *) port_vlan_add;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_vlan *) port_vlan_del;
    int (*)(struct dsa_switch *, int, const unsigned char *, u16) port_fdb_add;
    int (*)(struct dsa_switch *, int, const unsigned char *, u16) port_fdb_del;
    int (*)(struct dsa_switch *, int, dsa_fdb_dump_cb_t *, void *) port_fdb_dump;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_mdb *) port_mdb_prepare;
    void (*)(struct dsa_switch *, int, const struct switchdev_obj_port_mdb *) port_mdb_add;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_mdb *) port_mdb_del;
    int (*)(struct dsa_switch *, int, struct ethtool_rxnfc *, u32 *) get_rxnfc;
    int (*)(struct dsa_switch *, int, struct ethtool_rxnfc *) set_rxnfc;
    int (*)(struct dsa_switch *, int, struct flow_cls_offload *, bool) cls_flower_add;
    int (*)(struct dsa_switch *, int, struct flow_cls_offload *, bool) cls_flower_del;
    int (*)(struct dsa_switch *, int, struct flow_cls_offload *, bool) cls_flower_stats;
    int (*)(struct dsa_switch *, int, struct dsa_mall_mirror_tc_entry *, bool) port_mirror_add;
    void (*)(struct dsa_switch *, int, struct dsa_mall_mirror_tc_entry *) port_mirror_del;
    int (*)(struct dsa_switch *, int, struct dsa_mall_policer_tc_entry *) port_policer_add;
    void (*)(struct dsa_switch *, int) port_policer_del;
    int (*)(struct dsa_switch *, int, enum tc_setup_type, void *) port_setup_tc;
    int (*)(struct dsa_switch *, int, int, int, struct net_device *) crosschip_bridge_join;
    void (*)(struct dsa_switch *, int, int, int, struct net_device *) crosschip_bridge_leave;
    int (*)(struct dsa_switch *, int, struct ifreq *) port_hwtstamp_get;
    int (*)(struct dsa_switch *, int, struct ifreq *) port_hwtstamp_set;
    bool (*)(struct dsa_switch *, int, struct sk_buff *, unsigned int) port_txtstamp;
    bool (*)(struct dsa_switch *, int, struct sk_buff *, unsigned int) port_rxtstamp;
    int (*)(struct dsa_switch *, u32, struct devlink_param_gset_ctx *) devlink_param_get;
    int (*)(struct dsa_switch *, u32, struct devlink_param_gset_ctx *) devlink_param_set;
    int (*)(struct dsa_switch *, struct devlink_info_req *, struct netlink_ext_ack *) devlink_info_get;
    int (*)(struct dsa_switch *, int, int) port_change_mtu;
    int (*)(struct dsa_switch *, int) port_max_mtu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct dsa_switch_ops {
    enum dsa_tag_protocol (*)(struct dsa_switch *, int, enum dsa_tag_protocol) get_tag_protocol;
    int (*)(struct dsa_switch *, int, enum dsa_tag_protocol) change_tag_protocol;
    int (*)(struct dsa_switch *) setup;
    void (*)(struct dsa_switch *) teardown;
    u32 (*)(struct dsa_switch *, int) get_phy_flags;
    int (*)(struct dsa_switch *, int, int) phy_read;
    int (*)(struct dsa_switch *, int, int, u16) phy_write;
    void (*)(struct dsa_switch *, int, struct phy_device *) adjust_link;
    void (*)(struct dsa_switch *, int, struct fixed_phy_status *) fixed_link_update;
    void (*)(struct dsa_switch *, int, long unsigned int *, struct phylink_link_state *) phylink_validate;
    int (*)(struct dsa_switch *, int, struct phylink_link_state *) phylink_mac_link_state;
    void (*)(struct dsa_switch *, int, unsigned int, const struct phylink_link_state *) phylink_mac_config;
    void (*)(struct dsa_switch *, int) phylink_mac_an_restart;
    void (*)(struct dsa_switch *, int, unsigned int, phy_interface_t) phylink_mac_link_down;
    void (*)(struct dsa_switch *, int, unsigned int, phy_interface_t, struct phy_device *, int, int, bool, bool) phylink_mac_link_up;
    void (*)(struct dsa_switch *, int, struct phylink_link_state *) phylink_fixed_state;
    void (*)(struct dsa_switch *, int, u32, uint8_t *) get_strings;
    void (*)(struct dsa_switch *, int, uint64_t *) get_ethtool_stats;
    int (*)(struct dsa_switch *, int, int) get_sset_count;
    void (*)(struct dsa_switch *, int, uint64_t *) get_ethtool_phy_stats;
    void (*)(struct dsa_switch *, int, struct rtnl_link_stats64 *) get_stats64;
    void (*)(struct dsa_switch *, int, struct ethtool_test *, u64 *) self_test;
    void (*)(struct dsa_switch *, int, struct ethtool_wolinfo *) get_wol;
    int (*)(struct dsa_switch *, int, struct ethtool_wolinfo *) set_wol;
    int (*)(struct dsa_switch *, int, struct ethtool_ts_info *) get_ts_info;
    int (*)(struct dsa_switch *) suspend;
    int (*)(struct dsa_switch *) resume;
    int (*)(struct dsa_switch *, int, struct phy_device *) port_enable;
    void (*)(struct dsa_switch *, int) port_disable;
    int (*)(struct dsa_switch *, int, struct ethtool_eee *) set_mac_eee;
    int (*)(struct dsa_switch *, int, struct ethtool_eee *) get_mac_eee;
    int (*)(struct dsa_switch *) get_eeprom_len;
    int (*)(struct dsa_switch *, struct ethtool_eeprom *, u8 *) get_eeprom;
    int (*)(struct dsa_switch *, struct ethtool_eeprom *, u8 *) set_eeprom;
    int (*)(struct dsa_switch *, int) get_regs_len;
    void (*)(struct dsa_switch *, int, struct ethtool_regs *, void *) get_regs;
    int (*)(struct dsa_switch *, int, struct netdev_notifier_changeupper_info *) port_prechangeupper;
    int (*)(struct dsa_switch *, unsigned int) set_ageing_time;
    int (*)(struct dsa_switch *, int, struct net_device *) port_bridge_join;
    void (*)(struct dsa_switch *, int, struct net_device *) port_bridge_leave;
    void (*)(struct dsa_switch *, int, u8) port_stp_state_set;
    void (*)(struct dsa_switch *, int) port_fast_age;
    int (*)(struct dsa_switch *, int, struct switchdev_brport_flags, struct netlink_ext_ack *) port_pre_bridge_flags;
    int (*)(struct dsa_switch *, int, struct switchdev_brport_flags, struct netlink_ext_ack *) port_bridge_flags;
    int (*)(struct dsa_switch *, int, bool, struct netlink_ext_ack *) port_set_mrouter;
    int (*)(struct dsa_switch *, int, bool, struct netlink_ext_ack *) port_vlan_filtering;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_vlan *, struct netlink_ext_ack *) port_vlan_add;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_vlan *) port_vlan_del;
    int (*)(struct dsa_switch *, int, const unsigned char *, u16) port_fdb_add;
    int (*)(struct dsa_switch *, int, const unsigned char *, u16) port_fdb_del;
    int (*)(struct dsa_switch *, int, dsa_fdb_dump_cb_t *, void *) port_fdb_dump;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_mdb *) port_mdb_add;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_mdb *) port_mdb_del;
    int (*)(struct dsa_switch *, int, struct ethtool_rxnfc *, u32 *) get_rxnfc;
    int (*)(struct dsa_switch *, int, struct ethtool_rxnfc *) set_rxnfc;
    int (*)(struct dsa_switch *, int, struct flow_cls_offload *, bool) cls_flower_add;
    int (*)(struct dsa_switch *, int, struct flow_cls_offload *, bool) cls_flower_del;
    int (*)(struct dsa_switch *, int, struct flow_cls_offload *, bool) cls_flower_stats;
    int (*)(struct dsa_switch *, int, struct dsa_mall_mirror_tc_entry *, bool) port_mirror_add;
    void (*)(struct dsa_switch *, int, struct dsa_mall_mirror_tc_entry *) port_mirror_del;
    int (*)(struct dsa_switch *, int, struct dsa_mall_policer_tc_entry *) port_policer_add;
    void (*)(struct dsa_switch *, int) port_policer_del;
    int (*)(struct dsa_switch *, int, enum tc_setup_type, void *) port_setup_tc;
    int (*)(struct dsa_switch *, int, int, int, struct net_device *) crosschip_bridge_join;
    void (*)(struct dsa_switch *, int, int, int, struct net_device *) crosschip_bridge_leave;
    int (*)(struct dsa_switch *, int, int) crosschip_lag_change;
    int (*)(struct dsa_switch *, int, int, struct net_device *, struct netdev_lag_upper_info *) crosschip_lag_join;
    int (*)(struct dsa_switch *, int, int, struct net_device *) crosschip_lag_leave;
    int (*)(struct dsa_switch *, int, struct ifreq *) port_hwtstamp_get;
    int (*)(struct dsa_switch *, int, struct ifreq *) port_hwtstamp_set;
    void (*)(struct dsa_switch *, int, struct sk_buff *) port_txtstamp;
    bool (*)(struct dsa_switch *, int, struct sk_buff *, unsigned int) port_rxtstamp;
    int (*)(struct dsa_switch *, u32, struct devlink_param_gset_ctx *) devlink_param_get;
    int (*)(struct dsa_switch *, u32, struct devlink_param_gset_ctx *) devlink_param_set;
    int (*)(struct dsa_switch *, struct devlink_info_req *, struct netlink_ext_ack *) devlink_info_get;
    int (*)(struct dsa_switch *, unsigned int, u16, struct devlink_sb_pool_info *) devlink_sb_pool_get;
    int (*)(struct dsa_switch *, unsigned int, u16, u32, enum devlink_sb_threshold_type, struct netlink_ext_ack *) devlink_sb_pool_set;
    int (*)(struct dsa_switch *, int, unsigned int, u16, u32 *) devlink_sb_port_pool_get;
    int (*)(struct dsa_switch *, int, unsigned int, u16, u32, struct netlink_ext_ack *) devlink_sb_port_pool_set;
    int (*)(struct dsa_switch *, int, unsigned int, u16, enum devlink_sb_pool_type, u16 *, u32 *) devlink_sb_tc_pool_bind_get;
    int (*)(struct dsa_switch *, int, unsigned int, u16, enum devlink_sb_pool_type, u16, u32, struct netlink_ext_ack *) devlink_sb_tc_pool_bind_set;
    int (*)(struct dsa_switch *, unsigned int) devlink_sb_occ_snapshot;
    int (*)(struct dsa_switch *, unsigned int) devlink_sb_occ_max_clear;
    int (*)(struct dsa_switch *, int, unsigned int, u16, u32 *, u32 *) devlink_sb_occ_port_pool_get;
    int (*)(struct dsa_switch *, int, unsigned int, u16, enum devlink_sb_pool_type, u32 *, u32 *) devlink_sb_occ_tc_port_bind_get;
    int (*)(struct dsa_switch *, int, int) port_change_mtu;
    int (*)(struct dsa_switch *, int) port_max_mtu;
    int (*)(struct dsa_switch *, int) port_lag_change;
    int (*)(struct dsa_switch *, int, struct net_device *, struct netdev_lag_upper_info *) port_lag_join;
    int (*)(struct dsa_switch *, int, struct net_device *) port_lag_leave;
    int (*)(struct dsa_switch *, int, struct net_device *) port_hsr_join;
    int (*)(struct dsa_switch *, int, struct net_device *) port_hsr_leave;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_mrp *) port_mrp_add;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_mrp *) port_mrp_del;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_ring_role_mrp *) port_mrp_add_ring_role;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_ring_role_mrp *) port_mrp_del_ring_role;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct dsa_switch_ops {
    enum dsa_tag_protocol (*)(struct dsa_switch *, int, enum dsa_tag_protocol) get_tag_protocol;
    int (*)(struct dsa_switch *, int, enum dsa_tag_protocol) change_tag_protocol;
    int (*)(struct dsa_switch *) setup;
    void (*)(struct dsa_switch *) teardown;
    int (*)(struct dsa_switch *, int) port_setup;
    void (*)(struct dsa_switch *, int) port_teardown;
    u32 (*)(struct dsa_switch *, int) get_phy_flags;
    int (*)(struct dsa_switch *, int, int) phy_read;
    int (*)(struct dsa_switch *, int, int, u16) phy_write;
    void (*)(struct dsa_switch *, int, struct phy_device *) adjust_link;
    void (*)(struct dsa_switch *, int, struct fixed_phy_status *) fixed_link_update;
    void (*)(struct dsa_switch *, int, long unsigned int *, struct phylink_link_state *) phylink_validate;
    int (*)(struct dsa_switch *, int, struct phylink_link_state *) phylink_mac_link_state;
    void (*)(struct dsa_switch *, int, unsigned int, const struct phylink_link_state *) phylink_mac_config;
    void (*)(struct dsa_switch *, int) phylink_mac_an_restart;
    void (*)(struct dsa_switch *, int, unsigned int, phy_interface_t) phylink_mac_link_down;
    void (*)(struct dsa_switch *, int, unsigned int, phy_interface_t, struct phy_device *, int, int, bool, bool) phylink_mac_link_up;
    void (*)(struct dsa_switch *, int, struct phylink_link_state *) phylink_fixed_state;
    void (*)(struct dsa_switch *, int, u32, uint8_t *) get_strings;
    void (*)(struct dsa_switch *, int, uint64_t *) get_ethtool_stats;
    int (*)(struct dsa_switch *, int, int) get_sset_count;
    void (*)(struct dsa_switch *, int, uint64_t *) get_ethtool_phy_stats;
    void (*)(struct dsa_switch *, int, struct rtnl_link_stats64 *) get_stats64;
    void (*)(struct dsa_switch *, int, struct ethtool_test *, u64 *) self_test;
    void (*)(struct dsa_switch *, int, struct ethtool_wolinfo *) get_wol;
    int (*)(struct dsa_switch *, int, struct ethtool_wolinfo *) set_wol;
    int (*)(struct dsa_switch *, int, struct ethtool_ts_info *) get_ts_info;
    int (*)(struct dsa_switch *) suspend;
    int (*)(struct dsa_switch *) resume;
    int (*)(struct dsa_switch *, int, struct phy_device *) port_enable;
    void (*)(struct dsa_switch *, int) port_disable;
    int (*)(struct dsa_switch *, int, struct ethtool_eee *) set_mac_eee;
    int (*)(struct dsa_switch *, int, struct ethtool_eee *) get_mac_eee;
    int (*)(struct dsa_switch *) get_eeprom_len;
    int (*)(struct dsa_switch *, struct ethtool_eeprom *, u8 *) get_eeprom;
    int (*)(struct dsa_switch *, struct ethtool_eeprom *, u8 *) set_eeprom;
    int (*)(struct dsa_switch *, int) get_regs_len;
    void (*)(struct dsa_switch *, int, struct ethtool_regs *, void *) get_regs;
    int (*)(struct dsa_switch *, int, struct netdev_notifier_changeupper_info *) port_prechangeupper;
    int (*)(struct dsa_switch *, unsigned int) set_ageing_time;
    int (*)(struct dsa_switch *, int, struct net_device *) port_bridge_join;
    void (*)(struct dsa_switch *, int, struct net_device *) port_bridge_leave;
    int (*)(struct dsa_switch *, int, struct net_device *, int) port_bridge_tx_fwd_offload;
    void (*)(struct dsa_switch *, int, struct net_device *, int) port_bridge_tx_fwd_unoffload;
    void (*)(struct dsa_switch *, int, u8) port_stp_state_set;
    void (*)(struct dsa_switch *, int) port_fast_age;
    int (*)(struct dsa_switch *, int, struct switchdev_brport_flags, struct netlink_ext_ack *) port_pre_bridge_flags;
    int (*)(struct dsa_switch *, int, struct switchdev_brport_flags, struct netlink_ext_ack *) port_bridge_flags;
    int (*)(struct dsa_switch *, int, bool, struct netlink_ext_ack *) port_vlan_filtering;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_vlan *, struct netlink_ext_ack *) port_vlan_add;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_vlan *) port_vlan_del;
    int (*)(struct dsa_switch *, int, const unsigned char *, u16) port_fdb_add;
    int (*)(struct dsa_switch *, int, const unsigned char *, u16) port_fdb_del;
    int (*)(struct dsa_switch *, int, dsa_fdb_dump_cb_t *, void *) port_fdb_dump;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_mdb *) port_mdb_add;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_mdb *) port_mdb_del;
    int (*)(struct dsa_switch *, int, struct ethtool_rxnfc *, u32 *) get_rxnfc;
    int (*)(struct dsa_switch *, int, struct ethtool_rxnfc *) set_rxnfc;
    int (*)(struct dsa_switch *, int, struct flow_cls_offload *, bool) cls_flower_add;
    int (*)(struct dsa_switch *, int, struct flow_cls_offload *, bool) cls_flower_del;
    int (*)(struct dsa_switch *, int, struct flow_cls_offload *, bool) cls_flower_stats;
    int (*)(struct dsa_switch *, int, struct dsa_mall_mirror_tc_entry *, bool) port_mirror_add;
    void (*)(struct dsa_switch *, int, struct dsa_mall_mirror_tc_entry *) port_mirror_del;
    int (*)(struct dsa_switch *, int, struct dsa_mall_policer_tc_entry *) port_policer_add;
    void (*)(struct dsa_switch *, int) port_policer_del;
    int (*)(struct dsa_switch *, int, enum tc_setup_type, void *) port_setup_tc;
    int (*)(struct dsa_switch *, int, int, int, struct net_device *) crosschip_bridge_join;
    void (*)(struct dsa_switch *, int, int, int, struct net_device *) crosschip_bridge_leave;
    int (*)(struct dsa_switch *, int, int) crosschip_lag_change;
    int (*)(struct dsa_switch *, int, int, struct net_device *, struct netdev_lag_upper_info *) crosschip_lag_join;
    int (*)(struct dsa_switch *, int, int, struct net_device *) crosschip_lag_leave;
    int (*)(struct dsa_switch *, int, struct ifreq *) port_hwtstamp_get;
    int (*)(struct dsa_switch *, int, struct ifreq *) port_hwtstamp_set;
    void (*)(struct dsa_switch *, int, struct sk_buff *) port_txtstamp;
    bool (*)(struct dsa_switch *, int, struct sk_buff *, unsigned int) port_rxtstamp;
    int (*)(struct dsa_switch *, u32, struct devlink_param_gset_ctx *) devlink_param_get;
    int (*)(struct dsa_switch *, u32, struct devlink_param_gset_ctx *) devlink_param_set;
    int (*)(struct dsa_switch *, struct devlink_info_req *, struct netlink_ext_ack *) devlink_info_get;
    int (*)(struct dsa_switch *, unsigned int, u16, struct devlink_sb_pool_info *) devlink_sb_pool_get;
    int (*)(struct dsa_switch *, unsigned int, u16, u32, enum devlink_sb_threshold_type, struct netlink_ext_ack *) devlink_sb_pool_set;
    int (*)(struct dsa_switch *, int, unsigned int, u16, u32 *) devlink_sb_port_pool_get;
    int (*)(struct dsa_switch *, int, unsigned int, u16, u32, struct netlink_ext_ack *) devlink_sb_port_pool_set;
    int (*)(struct dsa_switch *, int, unsigned int, u16, enum devlink_sb_pool_type, u16 *, u32 *) devlink_sb_tc_pool_bind_get;
    int (*)(struct dsa_switch *, int, unsigned int, u16, enum devlink_sb_pool_type, u16, u32, struct netlink_ext_ack *) devlink_sb_tc_pool_bind_set;
    int (*)(struct dsa_switch *, unsigned int) devlink_sb_occ_snapshot;
    int (*)(struct dsa_switch *, unsigned int) devlink_sb_occ_max_clear;
    int (*)(struct dsa_switch *, int, unsigned int, u16, u32 *, u32 *) devlink_sb_occ_port_pool_get;
    int (*)(struct dsa_switch *, int, unsigned int, u16, enum devlink_sb_pool_type, u32 *, u32 *) devlink_sb_occ_tc_port_bind_get;
    int (*)(struct dsa_switch *, int, int) port_change_mtu;
    int (*)(struct dsa_switch *, int) port_max_mtu;
    int (*)(struct dsa_switch *, int) port_lag_change;
    int (*)(struct dsa_switch *, int, struct net_device *, struct netdev_lag_upper_info *) port_lag_join;
    int (*)(struct dsa_switch *, int, struct net_device *) port_lag_leave;
    int (*)(struct dsa_switch *, int, struct net_device *) port_hsr_join;
    int (*)(struct dsa_switch *, int, struct net_device *) port_hsr_leave;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_mrp *) port_mrp_add;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_mrp *) port_mrp_del;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_ring_role_mrp *) port_mrp_add_ring_role;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_ring_role_mrp *) port_mrp_del_ring_role;
    int (*)(struct dsa_switch *, int, u16, u16) tag_8021q_vlan_add;
    int (*)(struct dsa_switch *, int, u16) tag_8021q_vlan_del;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct dsa_switch_ops {
    enum dsa_tag_protocol (*)(struct dsa_switch *, int, enum dsa_tag_protocol) get_tag_protocol;
    int (*)(struct dsa_switch *, enum dsa_tag_protocol) change_tag_protocol;
    int (*)(struct dsa_switch *, enum dsa_tag_protocol) connect_tag_protocol;
    int (*)(struct dsa_switch *) setup;
    void (*)(struct dsa_switch *) teardown;
    int (*)(struct dsa_switch *, int) port_setup;
    void (*)(struct dsa_switch *, int) port_teardown;
    u32 (*)(struct dsa_switch *, int) get_phy_flags;
    int (*)(struct dsa_switch *, int, int) phy_read;
    int (*)(struct dsa_switch *, int, int, u16) phy_write;
    void (*)(struct dsa_switch *, int, struct phy_device *) adjust_link;
    void (*)(struct dsa_switch *, int, struct fixed_phy_status *) fixed_link_update;
    void (*)(struct dsa_switch *, int, struct phylink_config *) phylink_get_caps;
    void (*)(struct dsa_switch *, int, long unsigned int *, struct phylink_link_state *) phylink_validate;
    struct phylink_pcs * (*)(struct dsa_switch *, int, phy_interface_t) phylink_mac_select_pcs;
    int (*)(struct dsa_switch *, int, struct phylink_link_state *) phylink_mac_link_state;
    void (*)(struct dsa_switch *, int, unsigned int, const struct phylink_link_state *) phylink_mac_config;
    void (*)(struct dsa_switch *, int) phylink_mac_an_restart;
    void (*)(struct dsa_switch *, int, unsigned int, phy_interface_t) phylink_mac_link_down;
    void (*)(struct dsa_switch *, int, unsigned int, phy_interface_t, struct phy_device *, int, int, bool, bool) phylink_mac_link_up;
    void (*)(struct dsa_switch *, int, struct phylink_link_state *) phylink_fixed_state;
    void (*)(struct dsa_switch *, int, u32, uint8_t *) get_strings;
    void (*)(struct dsa_switch *, int, uint64_t *) get_ethtool_stats;
    int (*)(struct dsa_switch *, int, int) get_sset_count;
    void (*)(struct dsa_switch *, int, uint64_t *) get_ethtool_phy_stats;
    void (*)(struct dsa_switch *, int, struct ethtool_eth_phy_stats *) get_eth_phy_stats;
    void (*)(struct dsa_switch *, int, struct ethtool_eth_mac_stats *) get_eth_mac_stats;
    void (*)(struct dsa_switch *, int, struct ethtool_eth_ctrl_stats *) get_eth_ctrl_stats;
    void (*)(struct dsa_switch *, int, struct rtnl_link_stats64 *) get_stats64;
    void (*)(struct dsa_switch *, int, struct ethtool_test *, u64 *) self_test;
    void (*)(struct dsa_switch *, int, struct ethtool_wolinfo *) get_wol;
    int (*)(struct dsa_switch *, int, struct ethtool_wolinfo *) set_wol;
    int (*)(struct dsa_switch *, int, struct ethtool_ts_info *) get_ts_info;
    int (*)(struct dsa_switch *, int) port_get_default_prio;
    int (*)(struct dsa_switch *, int, u8) port_set_default_prio;
    int (*)(struct dsa_switch *, int, u8) port_get_dscp_prio;
    int (*)(struct dsa_switch *, int, u8, u8) port_add_dscp_prio;
    int (*)(struct dsa_switch *, int, u8, u8) port_del_dscp_prio;
    int (*)(struct dsa_switch *) suspend;
    int (*)(struct dsa_switch *) resume;
    int (*)(struct dsa_switch *, int, struct phy_device *) port_enable;
    void (*)(struct dsa_switch *, int) port_disable;
    int (*)(struct dsa_switch *, int, struct ethtool_eee *) set_mac_eee;
    int (*)(struct dsa_switch *, int, struct ethtool_eee *) get_mac_eee;
    int (*)(struct dsa_switch *) get_eeprom_len;
    int (*)(struct dsa_switch *, struct ethtool_eeprom *, u8 *) get_eeprom;
    int (*)(struct dsa_switch *, struct ethtool_eeprom *, u8 *) set_eeprom;
    int (*)(struct dsa_switch *, int) get_regs_len;
    void (*)(struct dsa_switch *, int, struct ethtool_regs *, void *) get_regs;
    int (*)(struct dsa_switch *, int, struct netdev_notifier_changeupper_info *) port_prechangeupper;
    int (*)(struct dsa_switch *, unsigned int) set_ageing_time;
    int (*)(struct dsa_switch *, int, struct dsa_bridge, bool *, struct netlink_ext_ack *) port_bridge_join;
    void (*)(struct dsa_switch *, int, struct dsa_bridge) port_bridge_leave;
    void (*)(struct dsa_switch *, int, u8) port_stp_state_set;
    int (*)(struct dsa_switch *, int, const struct switchdev_mst_state *) port_mst_state_set;
    void (*)(struct dsa_switch *, int) port_fast_age;
    int (*)(struct dsa_switch *, int, u16) port_vlan_fast_age;
    int (*)(struct dsa_switch *, int, struct switchdev_brport_flags, struct netlink_ext_ack *) port_pre_bridge_flags;
    int (*)(struct dsa_switch *, int, struct switchdev_brport_flags, struct netlink_ext_ack *) port_bridge_flags;
    void (*)(struct dsa_switch *, int, bool, bool) port_set_host_flood;
    int (*)(struct dsa_switch *, int, bool, struct netlink_ext_ack *) port_vlan_filtering;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_vlan *, struct netlink_ext_ack *) port_vlan_add;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_vlan *) port_vlan_del;
    int (*)(struct dsa_switch *, struct dsa_bridge, const struct switchdev_vlan_msti *) vlan_msti_set;
    int (*)(struct dsa_switch *, int, const unsigned char *, u16, struct dsa_db) port_fdb_add;
    int (*)(struct dsa_switch *, int, const unsigned char *, u16, struct dsa_db) port_fdb_del;
    int (*)(struct dsa_switch *, int, dsa_fdb_dump_cb_t *, void *) port_fdb_dump;
    int (*)(struct dsa_switch *, struct dsa_lag, const unsigned char *, u16, struct dsa_db) lag_fdb_add;
    int (*)(struct dsa_switch *, struct dsa_lag, const unsigned char *, u16, struct dsa_db) lag_fdb_del;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_mdb *, struct dsa_db) port_mdb_add;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_mdb *, struct dsa_db) port_mdb_del;
    int (*)(struct dsa_switch *, int, struct ethtool_rxnfc *, u32 *) get_rxnfc;
    int (*)(struct dsa_switch *, int, struct ethtool_rxnfc *) set_rxnfc;
    int (*)(struct dsa_switch *, int, struct flow_cls_offload *, bool) cls_flower_add;
    int (*)(struct dsa_switch *, int, struct flow_cls_offload *, bool) cls_flower_del;
    int (*)(struct dsa_switch *, int, struct flow_cls_offload *, bool) cls_flower_stats;
    int (*)(struct dsa_switch *, int, struct dsa_mall_mirror_tc_entry *, bool, struct netlink_ext_ack *) port_mirror_add;
    void (*)(struct dsa_switch *, int, struct dsa_mall_mirror_tc_entry *) port_mirror_del;
    int (*)(struct dsa_switch *, int, struct dsa_mall_policer_tc_entry *) port_policer_add;
    void (*)(struct dsa_switch *, int) port_policer_del;
    int (*)(struct dsa_switch *, int, enum tc_setup_type, void *) port_setup_tc;
    int (*)(struct dsa_switch *, int, int, int, struct dsa_bridge, struct netlink_ext_ack *) crosschip_bridge_join;
    void (*)(struct dsa_switch *, int, int, int, struct dsa_bridge) crosschip_bridge_leave;
    int (*)(struct dsa_switch *, int, int) crosschip_lag_change;
    int (*)(struct dsa_switch *, int, int, struct dsa_lag, struct netdev_lag_upper_info *) crosschip_lag_join;
    int (*)(struct dsa_switch *, int, int, struct dsa_lag) crosschip_lag_leave;
    int (*)(struct dsa_switch *, int, struct ifreq *) port_hwtstamp_get;
    int (*)(struct dsa_switch *, int, struct ifreq *) port_hwtstamp_set;
    void (*)(struct dsa_switch *, int, struct sk_buff *) port_txtstamp;
    bool (*)(struct dsa_switch *, int, struct sk_buff *, unsigned int) port_rxtstamp;
    int (*)(struct dsa_switch *, u32, struct devlink_param_gset_ctx *) devlink_param_get;
    int (*)(struct dsa_switch *, u32, struct devlink_param_gset_ctx *) devlink_param_set;
    int (*)(struct dsa_switch *, struct devlink_info_req *, struct netlink_ext_ack *) devlink_info_get;
    int (*)(struct dsa_switch *, unsigned int, u16, struct devlink_sb_pool_info *) devlink_sb_pool_get;
    int (*)(struct dsa_switch *, unsigned int, u16, u32, enum devlink_sb_threshold_type, struct netlink_ext_ack *) devlink_sb_pool_set;
    int (*)(struct dsa_switch *, int, unsigned int, u16, u32 *) devlink_sb_port_pool_get;
    int (*)(struct dsa_switch *, int, unsigned int, u16, u32, struct netlink_ext_ack *) devlink_sb_port_pool_set;
    int (*)(struct dsa_switch *, int, unsigned int, u16, enum devlink_sb_pool_type, u16 *, u32 *) devlink_sb_tc_pool_bind_get;
    int (*)(struct dsa_switch *, int, unsigned int, u16, enum devlink_sb_pool_type, u16, u32, struct netlink_ext_ack *) devlink_sb_tc_pool_bind_set;
    int (*)(struct dsa_switch *, unsigned int) devlink_sb_occ_snapshot;
    int (*)(struct dsa_switch *, unsigned int) devlink_sb_occ_max_clear;
    int (*)(struct dsa_switch *, int, unsigned int, u16, u32 *, u32 *) devlink_sb_occ_port_pool_get;
    int (*)(struct dsa_switch *, int, unsigned int, u16, enum devlink_sb_pool_type, u32 *, u32 *) devlink_sb_occ_tc_port_bind_get;
    int (*)(struct dsa_switch *, int, int) port_change_mtu;
    int (*)(struct dsa_switch *, int) port_max_mtu;
    int (*)(struct dsa_switch *, int) port_lag_change;
    int (*)(struct dsa_switch *, int, struct dsa_lag, struct netdev_lag_upper_info *) port_lag_join;
    int (*)(struct dsa_switch *, int, struct dsa_lag) port_lag_leave;
    int (*)(struct dsa_switch *, int, struct net_device *) port_hsr_join;
    int (*)(struct dsa_switch *, int, struct net_device *) port_hsr_leave;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_mrp *) port_mrp_add;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_mrp *) port_mrp_del;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_ring_role_mrp *) port_mrp_add_ring_role;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_ring_role_mrp *) port_mrp_del_ring_role;
    int (*)(struct dsa_switch *, int, u16, u16) tag_8021q_vlan_add;
    int (*)(struct dsa_switch *, int, u16) tag_8021q_vlan_del;
    void (*)(struct dsa_switch *, const struct net_device *, bool) master_state_change;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct dsa_switch_ops {
    enum dsa_tag_protocol (*)(struct dsa_switch *, int, enum dsa_tag_protocol) get_tag_protocol;
    int (*)(struct dsa_switch *, enum dsa_tag_protocol) change_tag_protocol;
    int (*)(struct dsa_switch *, enum dsa_tag_protocol) connect_tag_protocol;
    int (*)(struct dsa_switch *, int, struct net_device *, struct netlink_ext_ack *) port_change_master;
    int (*)(struct dsa_switch *) setup;
    void (*)(struct dsa_switch *) teardown;
    int (*)(struct dsa_switch *, int) port_setup;
    void (*)(struct dsa_switch *, int) port_teardown;
    u32 (*)(struct dsa_switch *, int) get_phy_flags;
    int (*)(struct dsa_switch *, int, int) phy_read;
    int (*)(struct dsa_switch *, int, int, u16) phy_write;
    void (*)(struct dsa_switch *, int, struct phy_device *) adjust_link;
    void (*)(struct dsa_switch *, int, struct fixed_phy_status *) fixed_link_update;
    void (*)(struct dsa_switch *, int, struct phylink_config *) phylink_get_caps;
    struct phylink_pcs * (*)(struct dsa_switch *, int, phy_interface_t) phylink_mac_select_pcs;
    int (*)(struct dsa_switch *, int, struct phylink_link_state *) phylink_mac_link_state;
    void (*)(struct dsa_switch *, int, unsigned int, const struct phylink_link_state *) phylink_mac_config;
    void (*)(struct dsa_switch *, int) phylink_mac_an_restart;
    void (*)(struct dsa_switch *, int, unsigned int, phy_interface_t) phylink_mac_link_down;
    void (*)(struct dsa_switch *, int, unsigned int, phy_interface_t, struct phy_device *, int, int, bool, bool) phylink_mac_link_up;
    void (*)(struct dsa_switch *, int, struct phylink_link_state *) phylink_fixed_state;
    void (*)(struct dsa_switch *, int, u32, uint8_t *) get_strings;
    void (*)(struct dsa_switch *, int, uint64_t *) get_ethtool_stats;
    int (*)(struct dsa_switch *, int, int) get_sset_count;
    void (*)(struct dsa_switch *, int, uint64_t *) get_ethtool_phy_stats;
    void (*)(struct dsa_switch *, int, struct ethtool_eth_phy_stats *) get_eth_phy_stats;
    void (*)(struct dsa_switch *, int, struct ethtool_eth_mac_stats *) get_eth_mac_stats;
    void (*)(struct dsa_switch *, int, struct ethtool_eth_ctrl_stats *) get_eth_ctrl_stats;
    void (*)(struct dsa_switch *, int, struct ethtool_rmon_stats *, const struct ethtool_rmon_hist_range * *) get_rmon_stats;
    void (*)(struct dsa_switch *, int, struct rtnl_link_stats64 *) get_stats64;
    void (*)(struct dsa_switch *, int, struct ethtool_pause_stats *) get_pause_stats;
    void (*)(struct dsa_switch *, int, struct ethtool_test *, u64 *) self_test;
    void (*)(struct dsa_switch *, int, struct ethtool_wolinfo *) get_wol;
    int (*)(struct dsa_switch *, int, struct ethtool_wolinfo *) set_wol;
    int (*)(struct dsa_switch *, int, struct ethtool_ts_info *) get_ts_info;
    int (*)(struct dsa_switch *, int) port_get_default_prio;
    int (*)(struct dsa_switch *, int, u8) port_set_default_prio;
    int (*)(struct dsa_switch *, int, u8) port_get_dscp_prio;
    int (*)(struct dsa_switch *, int, u8, u8) port_add_dscp_prio;
    int (*)(struct dsa_switch *, int, u8, u8) port_del_dscp_prio;
    int (*)(struct dsa_switch *) suspend;
    int (*)(struct dsa_switch *) resume;
    int (*)(struct dsa_switch *, int, struct phy_device *) port_enable;
    void (*)(struct dsa_switch *, int) port_disable;
    int (*)(struct dsa_switch *, int, struct ethtool_eee *) set_mac_eee;
    int (*)(struct dsa_switch *, int, struct ethtool_eee *) get_mac_eee;
    int (*)(struct dsa_switch *) get_eeprom_len;
    int (*)(struct dsa_switch *, struct ethtool_eeprom *, u8 *) get_eeprom;
    int (*)(struct dsa_switch *, struct ethtool_eeprom *, u8 *) set_eeprom;
    int (*)(struct dsa_switch *, int) get_regs_len;
    void (*)(struct dsa_switch *, int, struct ethtool_regs *, void *) get_regs;
    int (*)(struct dsa_switch *, int, struct netdev_notifier_changeupper_info *) port_prechangeupper;
    int (*)(struct dsa_switch *, unsigned int) set_ageing_time;
    int (*)(struct dsa_switch *, int, struct dsa_bridge, bool *, struct netlink_ext_ack *) port_bridge_join;
    void (*)(struct dsa_switch *, int, struct dsa_bridge) port_bridge_leave;
    void (*)(struct dsa_switch *, int, u8) port_stp_state_set;
    int (*)(struct dsa_switch *, int, const struct switchdev_mst_state *) port_mst_state_set;
    void (*)(struct dsa_switch *, int) port_fast_age;
    int (*)(struct dsa_switch *, int, u16) port_vlan_fast_age;
    int (*)(struct dsa_switch *, int, struct switchdev_brport_flags, struct netlink_ext_ack *) port_pre_bridge_flags;
    int (*)(struct dsa_switch *, int, struct switchdev_brport_flags, struct netlink_ext_ack *) port_bridge_flags;
    void (*)(struct dsa_switch *, int, bool, bool) port_set_host_flood;
    int (*)(struct dsa_switch *, int, bool, struct netlink_ext_ack *) port_vlan_filtering;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_vlan *, struct netlink_ext_ack *) port_vlan_add;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_vlan *) port_vlan_del;
    int (*)(struct dsa_switch *, struct dsa_bridge, const struct switchdev_vlan_msti *) vlan_msti_set;
    int (*)(struct dsa_switch *, int, const unsigned char *, u16, struct dsa_db) port_fdb_add;
    int (*)(struct dsa_switch *, int, const unsigned char *, u16, struct dsa_db) port_fdb_del;
    int (*)(struct dsa_switch *, int, dsa_fdb_dump_cb_t *, void *) port_fdb_dump;
    int (*)(struct dsa_switch *, struct dsa_lag, const unsigned char *, u16, struct dsa_db) lag_fdb_add;
    int (*)(struct dsa_switch *, struct dsa_lag, const unsigned char *, u16, struct dsa_db) lag_fdb_del;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_mdb *, struct dsa_db) port_mdb_add;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_mdb *, struct dsa_db) port_mdb_del;
    int (*)(struct dsa_switch *, int, struct ethtool_rxnfc *, u32 *) get_rxnfc;
    int (*)(struct dsa_switch *, int, struct ethtool_rxnfc *) set_rxnfc;
    int (*)(struct dsa_switch *, int, struct flow_cls_offload *, bool) cls_flower_add;
    int (*)(struct dsa_switch *, int, struct flow_cls_offload *, bool) cls_flower_del;
    int (*)(struct dsa_switch *, int, struct flow_cls_offload *, bool) cls_flower_stats;
    int (*)(struct dsa_switch *, int, struct dsa_mall_mirror_tc_entry *, bool, struct netlink_ext_ack *) port_mirror_add;
    void (*)(struct dsa_switch *, int, struct dsa_mall_mirror_tc_entry *) port_mirror_del;
    int (*)(struct dsa_switch *, int, struct dsa_mall_policer_tc_entry *) port_policer_add;
    void (*)(struct dsa_switch *, int) port_policer_del;
    int (*)(struct dsa_switch *, int, enum tc_setup_type, void *) port_setup_tc;
    int (*)(struct dsa_switch *, int, int, int, struct dsa_bridge, struct netlink_ext_ack *) crosschip_bridge_join;
    void (*)(struct dsa_switch *, int, int, int, struct dsa_bridge) crosschip_bridge_leave;
    int (*)(struct dsa_switch *, int, int) crosschip_lag_change;
    int (*)(struct dsa_switch *, int, int, struct dsa_lag, struct netdev_lag_upper_info *, struct netlink_ext_ack *) crosschip_lag_join;
    int (*)(struct dsa_switch *, int, int, struct dsa_lag) crosschip_lag_leave;
    int (*)(struct dsa_switch *, int, struct ifreq *) port_hwtstamp_get;
    int (*)(struct dsa_switch *, int, struct ifreq *) port_hwtstamp_set;
    void (*)(struct dsa_switch *, int, struct sk_buff *) port_txtstamp;
    bool (*)(struct dsa_switch *, int, struct sk_buff *, unsigned int) port_rxtstamp;
    int (*)(struct dsa_switch *, u32, struct devlink_param_gset_ctx *) devlink_param_get;
    int (*)(struct dsa_switch *, u32, struct devlink_param_gset_ctx *) devlink_param_set;
    int (*)(struct dsa_switch *, struct devlink_info_req *, struct netlink_ext_ack *) devlink_info_get;
    int (*)(struct dsa_switch *, unsigned int, u16, struct devlink_sb_pool_info *) devlink_sb_pool_get;
    int (*)(struct dsa_switch *, unsigned int, u16, u32, enum devlink_sb_threshold_type, struct netlink_ext_ack *) devlink_sb_pool_set;
    int (*)(struct dsa_switch *, int, unsigned int, u16, u32 *) devlink_sb_port_pool_get;
    int (*)(struct dsa_switch *, int, unsigned int, u16, u32, struct netlink_ext_ack *) devlink_sb_port_pool_set;
    int (*)(struct dsa_switch *, int, unsigned int, u16, enum devlink_sb_pool_type, u16 *, u32 *) devlink_sb_tc_pool_bind_get;
    int (*)(struct dsa_switch *, int, unsigned int, u16, enum devlink_sb_pool_type, u16, u32, struct netlink_ext_ack *) devlink_sb_tc_pool_bind_set;
    int (*)(struct dsa_switch *, unsigned int) devlink_sb_occ_snapshot;
    int (*)(struct dsa_switch *, unsigned int) devlink_sb_occ_max_clear;
    int (*)(struct dsa_switch *, int, unsigned int, u16, u32 *, u32 *) devlink_sb_occ_port_pool_get;
    int (*)(struct dsa_switch *, int, unsigned int, u16, enum devlink_sb_pool_type, u32 *, u32 *) devlink_sb_occ_tc_port_bind_get;
    int (*)(struct dsa_switch *, int, int) port_change_mtu;
    int (*)(struct dsa_switch *, int) port_max_mtu;
    int (*)(struct dsa_switch *, int) port_lag_change;
    int (*)(struct dsa_switch *, int, struct dsa_lag, struct netdev_lag_upper_info *, struct netlink_ext_ack *) port_lag_join;
    int (*)(struct dsa_switch *, int, struct dsa_lag) port_lag_leave;
    int (*)(struct dsa_switch *, int, struct net_device *) port_hsr_join;
    int (*)(struct dsa_switch *, int, struct net_device *) port_hsr_leave;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_mrp *) port_mrp_add;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_mrp *) port_mrp_del;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_ring_role_mrp *) port_mrp_add_ring_role;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_ring_role_mrp *) port_mrp_del_ring_role;
    int (*)(struct dsa_switch *, int, u16, u16) tag_8021q_vlan_add;
    int (*)(struct dsa_switch *, int, u16) tag_8021q_vlan_del;
    void (*)(struct dsa_switch *, const struct net_device *, bool) master_state_change;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct dsa_switch_ops {
    enum dsa_tag_protocol (*)(struct dsa_switch *, int, enum dsa_tag_protocol) get_tag_protocol;
    int (*)(struct dsa_switch *, enum dsa_tag_protocol) change_tag_protocol;
    int (*)(struct dsa_switch *, enum dsa_tag_protocol) connect_tag_protocol;
    int (*)(struct dsa_switch *, int, struct net_device *, struct netlink_ext_ack *) port_change_master;
    int (*)(struct dsa_switch *) setup;
    void (*)(struct dsa_switch *) teardown;
    int (*)(struct dsa_switch *, int) port_setup;
    void (*)(struct dsa_switch *, int) port_teardown;
    u32 (*)(struct dsa_switch *, int) get_phy_flags;
    int (*)(struct dsa_switch *, int, int) phy_read;
    int (*)(struct dsa_switch *, int, int, u16) phy_write;
    void (*)(struct dsa_switch *, int, struct phy_device *) adjust_link;
    void (*)(struct dsa_switch *, int, struct fixed_phy_status *) fixed_link_update;
    void (*)(struct dsa_switch *, int, struct phylink_config *) phylink_get_caps;
    struct phylink_pcs * (*)(struct dsa_switch *, int, phy_interface_t) phylink_mac_select_pcs;
    int (*)(struct dsa_switch *, int, struct phylink_link_state *) phylink_mac_link_state;
    int (*)(struct dsa_switch *, int, unsigned int, phy_interface_t) phylink_mac_prepare;
    void (*)(struct dsa_switch *, int, unsigned int, const struct phylink_link_state *) phylink_mac_config;
    int (*)(struct dsa_switch *, int, unsigned int, phy_interface_t) phylink_mac_finish;
    void (*)(struct dsa_switch *, int) phylink_mac_an_restart;
    void (*)(struct dsa_switch *, int, unsigned int, phy_interface_t) phylink_mac_link_down;
    void (*)(struct dsa_switch *, int, unsigned int, phy_interface_t, struct phy_device *, int, int, bool, bool) phylink_mac_link_up;
    void (*)(struct dsa_switch *, int, struct phylink_link_state *) phylink_fixed_state;
    void (*)(struct dsa_switch *, int, u32, uint8_t *) get_strings;
    void (*)(struct dsa_switch *, int, uint64_t *) get_ethtool_stats;
    int (*)(struct dsa_switch *, int, int) get_sset_count;
    void (*)(struct dsa_switch *, int, uint64_t *) get_ethtool_phy_stats;
    void (*)(struct dsa_switch *, int, struct ethtool_eth_phy_stats *) get_eth_phy_stats;
    void (*)(struct dsa_switch *, int, struct ethtool_eth_mac_stats *) get_eth_mac_stats;
    void (*)(struct dsa_switch *, int, struct ethtool_eth_ctrl_stats *) get_eth_ctrl_stats;
    void (*)(struct dsa_switch *, int, struct ethtool_rmon_stats *, const struct ethtool_rmon_hist_range * *) get_rmon_stats;
    void (*)(struct dsa_switch *, int, struct rtnl_link_stats64 *) get_stats64;
    void (*)(struct dsa_switch *, int, struct ethtool_pause_stats *) get_pause_stats;
    void (*)(struct dsa_switch *, int, struct ethtool_test *, u64 *) self_test;
    void (*)(struct dsa_switch *, int, struct ethtool_wolinfo *) get_wol;
    int (*)(struct dsa_switch *, int, struct ethtool_wolinfo *) set_wol;
    int (*)(struct dsa_switch *, int, struct ethtool_ts_info *) get_ts_info;
    int (*)(struct dsa_switch *, int, struct ethtool_mm_state *) get_mm;
    int (*)(struct dsa_switch *, int, struct ethtool_mm_cfg *, struct netlink_ext_ack *) set_mm;
    void (*)(struct dsa_switch *, int, struct ethtool_mm_stats *) get_mm_stats;
    int (*)(struct dsa_switch *, int) port_get_default_prio;
    int (*)(struct dsa_switch *, int, u8) port_set_default_prio;
    int (*)(struct dsa_switch *, int, u8) port_get_dscp_prio;
    int (*)(struct dsa_switch *, int, u8, u8) port_add_dscp_prio;
    int (*)(struct dsa_switch *, int, u8, u8) port_del_dscp_prio;
    int (*)(struct dsa_switch *) suspend;
    int (*)(struct dsa_switch *) resume;
    int (*)(struct dsa_switch *, int, struct phy_device *) port_enable;
    void (*)(struct dsa_switch *, int) port_disable;
    struct dsa_port * (*)(struct dsa_switch *) preferred_default_local_cpu_port;
    int (*)(struct dsa_switch *, int, struct ethtool_eee *) set_mac_eee;
    int (*)(struct dsa_switch *, int, struct ethtool_eee *) get_mac_eee;
    int (*)(struct dsa_switch *) get_eeprom_len;
    int (*)(struct dsa_switch *, struct ethtool_eeprom *, u8 *) get_eeprom;
    int (*)(struct dsa_switch *, struct ethtool_eeprom *, u8 *) set_eeprom;
    int (*)(struct dsa_switch *, int) get_regs_len;
    void (*)(struct dsa_switch *, int, struct ethtool_regs *, void *) get_regs;
    int (*)(struct dsa_switch *, int, struct netdev_notifier_changeupper_info *) port_prechangeupper;
    int (*)(struct dsa_switch *, unsigned int) set_ageing_time;
    int (*)(struct dsa_switch *, int, struct dsa_bridge, bool *, struct netlink_ext_ack *) port_bridge_join;
    void (*)(struct dsa_switch *, int, struct dsa_bridge) port_bridge_leave;
    void (*)(struct dsa_switch *, int, u8) port_stp_state_set;
    int (*)(struct dsa_switch *, int, const struct switchdev_mst_state *) port_mst_state_set;
    void (*)(struct dsa_switch *, int) port_fast_age;
    int (*)(struct dsa_switch *, int, u16) port_vlan_fast_age;
    int (*)(struct dsa_switch *, int, struct switchdev_brport_flags, struct netlink_ext_ack *) port_pre_bridge_flags;
    int (*)(struct dsa_switch *, int, struct switchdev_brport_flags, struct netlink_ext_ack *) port_bridge_flags;
    void (*)(struct dsa_switch *, int, bool, bool) port_set_host_flood;
    int (*)(struct dsa_switch *, int, bool, struct netlink_ext_ack *) port_vlan_filtering;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_vlan *, struct netlink_ext_ack *) port_vlan_add;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_vlan *) port_vlan_del;
    int (*)(struct dsa_switch *, struct dsa_bridge, const struct switchdev_vlan_msti *) vlan_msti_set;
    int (*)(struct dsa_switch *, int, const unsigned char *, u16, struct dsa_db) port_fdb_add;
    int (*)(struct dsa_switch *, int, const unsigned char *, u16, struct dsa_db) port_fdb_del;
    int (*)(struct dsa_switch *, int, dsa_fdb_dump_cb_t *, void *) port_fdb_dump;
    int (*)(struct dsa_switch *, struct dsa_lag, const unsigned char *, u16, struct dsa_db) lag_fdb_add;
    int (*)(struct dsa_switch *, struct dsa_lag, const unsigned char *, u16, struct dsa_db) lag_fdb_del;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_mdb *, struct dsa_db) port_mdb_add;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_mdb *, struct dsa_db) port_mdb_del;
    int (*)(struct dsa_switch *, int, struct ethtool_rxnfc *, u32 *) get_rxnfc;
    int (*)(struct dsa_switch *, int, struct ethtool_rxnfc *) set_rxnfc;
    int (*)(struct dsa_switch *, int, struct flow_cls_offload *, bool) cls_flower_add;
    int (*)(struct dsa_switch *, int, struct flow_cls_offload *, bool) cls_flower_del;
    int (*)(struct dsa_switch *, int, struct flow_cls_offload *, bool) cls_flower_stats;
    int (*)(struct dsa_switch *, int, struct dsa_mall_mirror_tc_entry *, bool, struct netlink_ext_ack *) port_mirror_add;
    void (*)(struct dsa_switch *, int, struct dsa_mall_mirror_tc_entry *) port_mirror_del;
    int (*)(struct dsa_switch *, int, struct dsa_mall_policer_tc_entry *) port_policer_add;
    void (*)(struct dsa_switch *, int) port_policer_del;
    int (*)(struct dsa_switch *, int, enum tc_setup_type, void *) port_setup_tc;
    int (*)(struct dsa_switch *, int, int, int, struct dsa_bridge, struct netlink_ext_ack *) crosschip_bridge_join;
    void (*)(struct dsa_switch *, int, int, int, struct dsa_bridge) crosschip_bridge_leave;
    int (*)(struct dsa_switch *, int, int) crosschip_lag_change;
    int (*)(struct dsa_switch *, int, int, struct dsa_lag, struct netdev_lag_upper_info *, struct netlink_ext_ack *) crosschip_lag_join;
    int (*)(struct dsa_switch *, int, int, struct dsa_lag) crosschip_lag_leave;
    int (*)(struct dsa_switch *, int, struct ifreq *) port_hwtstamp_get;
    int (*)(struct dsa_switch *, int, struct ifreq *) port_hwtstamp_set;
    void (*)(struct dsa_switch *, int, struct sk_buff *) port_txtstamp;
    bool (*)(struct dsa_switch *, int, struct sk_buff *, unsigned int) port_rxtstamp;
    int (*)(struct dsa_switch *, u32, struct devlink_param_gset_ctx *) devlink_param_get;
    int (*)(struct dsa_switch *, u32, struct devlink_param_gset_ctx *) devlink_param_set;
    int (*)(struct dsa_switch *, struct devlink_info_req *, struct netlink_ext_ack *) devlink_info_get;
    int (*)(struct dsa_switch *, unsigned int, u16, struct devlink_sb_pool_info *) devlink_sb_pool_get;
    int (*)(struct dsa_switch *, unsigned int, u16, u32, enum devlink_sb_threshold_type, struct netlink_ext_ack *) devlink_sb_pool_set;
    int (*)(struct dsa_switch *, int, unsigned int, u16, u32 *) devlink_sb_port_pool_get;
    int (*)(struct dsa_switch *, int, unsigned int, u16, u32, struct netlink_ext_ack *) devlink_sb_port_pool_set;
    int (*)(struct dsa_switch *, int, unsigned int, u16, enum devlink_sb_pool_type, u16 *, u32 *) devlink_sb_tc_pool_bind_get;
    int (*)(struct dsa_switch *, int, unsigned int, u16, enum devlink_sb_pool_type, u16, u32, struct netlink_ext_ack *) devlink_sb_tc_pool_bind_set;
    int (*)(struct dsa_switch *, unsigned int) devlink_sb_occ_snapshot;
    int (*)(struct dsa_switch *, unsigned int) devlink_sb_occ_max_clear;
    int (*)(struct dsa_switch *, int, unsigned int, u16, u32 *, u32 *) devlink_sb_occ_port_pool_get;
    int (*)(struct dsa_switch *, int, unsigned int, u16, enum devlink_sb_pool_type, u32 *, u32 *) devlink_sb_occ_tc_port_bind_get;
    int (*)(struct dsa_switch *, int, int) port_change_mtu;
    int (*)(struct dsa_switch *, int) port_max_mtu;
    int (*)(struct dsa_switch *, int) port_lag_change;
    int (*)(struct dsa_switch *, int, struct dsa_lag, struct netdev_lag_upper_info *, struct netlink_ext_ack *) port_lag_join;
    int (*)(struct dsa_switch *, int, struct dsa_lag) port_lag_leave;
    int (*)(struct dsa_switch *, int, struct net_device *) port_hsr_join;
    int (*)(struct dsa_switch *, int, struct net_device *) port_hsr_leave;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_mrp *) port_mrp_add;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_mrp *) port_mrp_del;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_ring_role_mrp *) port_mrp_add_ring_role;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_ring_role_mrp *) port_mrp_del_ring_role;
    int (*)(struct dsa_switch *, int, u16, u16) tag_8021q_vlan_add;
    int (*)(struct dsa_switch *, int, u16) tag_8021q_vlan_del;
    void (*)(struct dsa_switch *, const struct net_device *, bool) master_state_change;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct dsa_switch_ops {
    enum dsa_tag_protocol (*)(struct dsa_switch *, int, enum dsa_tag_protocol) get_tag_protocol;
    int (*)(struct dsa_switch *, enum dsa_tag_protocol) change_tag_protocol;
    int (*)(struct dsa_switch *, enum dsa_tag_protocol) connect_tag_protocol;
    int (*)(struct dsa_switch *, int, struct net_device *, struct netlink_ext_ack *) port_change_conduit;
    int (*)(struct dsa_switch *) setup;
    void (*)(struct dsa_switch *) teardown;
    int (*)(struct dsa_switch *, int) port_setup;
    void (*)(struct dsa_switch *, int) port_teardown;
    u32 (*)(struct dsa_switch *, int) get_phy_flags;
    int (*)(struct dsa_switch *, int, int) phy_read;
    int (*)(struct dsa_switch *, int, int, u16) phy_write;
    void (*)(struct dsa_switch *, int, struct phy_device *) adjust_link;
    void (*)(struct dsa_switch *, int, struct fixed_phy_status *) fixed_link_update;
    void (*)(struct dsa_switch *, int, struct phylink_config *) phylink_get_caps;
    struct phylink_pcs * (*)(struct dsa_switch *, int, phy_interface_t) phylink_mac_select_pcs;
    int (*)(struct dsa_switch *, int, unsigned int, phy_interface_t) phylink_mac_prepare;
    void (*)(struct dsa_switch *, int, unsigned int, const struct phylink_link_state *) phylink_mac_config;
    int (*)(struct dsa_switch *, int, unsigned int, phy_interface_t) phylink_mac_finish;
    void (*)(struct dsa_switch *, int, unsigned int, phy_interface_t) phylink_mac_link_down;
    void (*)(struct dsa_switch *, int, unsigned int, phy_interface_t, struct phy_device *, int, int, bool, bool) phylink_mac_link_up;
    void (*)(struct dsa_switch *, int, struct phylink_link_state *) phylink_fixed_state;
    void (*)(struct dsa_switch *, int, u32, uint8_t *) get_strings;
    void (*)(struct dsa_switch *, int, uint64_t *) get_ethtool_stats;
    int (*)(struct dsa_switch *, int, int) get_sset_count;
    void (*)(struct dsa_switch *, int, uint64_t *) get_ethtool_phy_stats;
    void (*)(struct dsa_switch *, int, struct ethtool_eth_phy_stats *) get_eth_phy_stats;
    void (*)(struct dsa_switch *, int, struct ethtool_eth_mac_stats *) get_eth_mac_stats;
    void (*)(struct dsa_switch *, int, struct ethtool_eth_ctrl_stats *) get_eth_ctrl_stats;
    void (*)(struct dsa_switch *, int, struct ethtool_rmon_stats *, const struct ethtool_rmon_hist_range * *) get_rmon_stats;
    void (*)(struct dsa_switch *, int, struct rtnl_link_stats64 *) get_stats64;
    void (*)(struct dsa_switch *, int, struct ethtool_pause_stats *) get_pause_stats;
    void (*)(struct dsa_switch *, int, struct ethtool_test *, u64 *) self_test;
    void (*)(struct dsa_switch *, int, struct ethtool_wolinfo *) get_wol;
    int (*)(struct dsa_switch *, int, struct ethtool_wolinfo *) set_wol;
    int (*)(struct dsa_switch *, int, struct ethtool_ts_info *) get_ts_info;
    int (*)(struct dsa_switch *, int, struct ethtool_mm_state *) get_mm;
    int (*)(struct dsa_switch *, int, struct ethtool_mm_cfg *, struct netlink_ext_ack *) set_mm;
    void (*)(struct dsa_switch *, int, struct ethtool_mm_stats *) get_mm_stats;
    int (*)(struct dsa_switch *, int) port_get_default_prio;
    int (*)(struct dsa_switch *, int, u8) port_set_default_prio;
    int (*)(struct dsa_switch *, int, u8) port_get_dscp_prio;
    int (*)(struct dsa_switch *, int, u8, u8) port_add_dscp_prio;
    int (*)(struct dsa_switch *, int, u8, u8) port_del_dscp_prio;
    int (*)(struct dsa_switch *) suspend;
    int (*)(struct dsa_switch *) resume;
    int (*)(struct dsa_switch *, int, struct phy_device *) port_enable;
    void (*)(struct dsa_switch *, int) port_disable;
    int (*)(struct dsa_switch *, int, const unsigned char *) port_set_mac_address;
    struct dsa_port * (*)(struct dsa_switch *) preferred_default_local_cpu_port;
    int (*)(struct dsa_switch *, int, struct ethtool_eee *) set_mac_eee;
    int (*)(struct dsa_switch *, int, struct ethtool_eee *) get_mac_eee;
    int (*)(struct dsa_switch *) get_eeprom_len;
    int (*)(struct dsa_switch *, struct ethtool_eeprom *, u8 *) get_eeprom;
    int (*)(struct dsa_switch *, struct ethtool_eeprom *, u8 *) set_eeprom;
    int (*)(struct dsa_switch *, int) get_regs_len;
    void (*)(struct dsa_switch *, int, struct ethtool_regs *, void *) get_regs;
    int (*)(struct dsa_switch *, int, struct netdev_notifier_changeupper_info *) port_prechangeupper;
    int (*)(struct dsa_switch *, unsigned int) set_ageing_time;
    int (*)(struct dsa_switch *, int, struct dsa_bridge, bool *, struct netlink_ext_ack *) port_bridge_join;
    void (*)(struct dsa_switch *, int, struct dsa_bridge) port_bridge_leave;
    void (*)(struct dsa_switch *, int, u8) port_stp_state_set;
    int (*)(struct dsa_switch *, int, const struct switchdev_mst_state *) port_mst_state_set;
    void (*)(struct dsa_switch *, int) port_fast_age;
    int (*)(struct dsa_switch *, int, u16) port_vlan_fast_age;
    int (*)(struct dsa_switch *, int, struct switchdev_brport_flags, struct netlink_ext_ack *) port_pre_bridge_flags;
    int (*)(struct dsa_switch *, int, struct switchdev_brport_flags, struct netlink_ext_ack *) port_bridge_flags;
    void (*)(struct dsa_switch *, int, bool, bool) port_set_host_flood;
    int (*)(struct dsa_switch *, int, bool, struct netlink_ext_ack *) port_vlan_filtering;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_vlan *, struct netlink_ext_ack *) port_vlan_add;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_vlan *) port_vlan_del;
    int (*)(struct dsa_switch *, struct dsa_bridge, const struct switchdev_vlan_msti *) vlan_msti_set;
    int (*)(struct dsa_switch *, int, const unsigned char *, u16, struct dsa_db) port_fdb_add;
    int (*)(struct dsa_switch *, int, const unsigned char *, u16, struct dsa_db) port_fdb_del;
    int (*)(struct dsa_switch *, int, dsa_fdb_dump_cb_t *, void *) port_fdb_dump;
    int (*)(struct dsa_switch *, struct dsa_lag, const unsigned char *, u16, struct dsa_db) lag_fdb_add;
    int (*)(struct dsa_switch *, struct dsa_lag, const unsigned char *, u16, struct dsa_db) lag_fdb_del;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_mdb *, struct dsa_db) port_mdb_add;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_mdb *, struct dsa_db) port_mdb_del;
    int (*)(struct dsa_switch *, int, struct ethtool_rxnfc *, u32 *) get_rxnfc;
    int (*)(struct dsa_switch *, int, struct ethtool_rxnfc *) set_rxnfc;
    int (*)(struct dsa_switch *, int, struct flow_cls_offload *, bool) cls_flower_add;
    int (*)(struct dsa_switch *, int, struct flow_cls_offload *, bool) cls_flower_del;
    int (*)(struct dsa_switch *, int, struct flow_cls_offload *, bool) cls_flower_stats;
    int (*)(struct dsa_switch *, int, struct dsa_mall_mirror_tc_entry *, bool, struct netlink_ext_ack *) port_mirror_add;
    void (*)(struct dsa_switch *, int, struct dsa_mall_mirror_tc_entry *) port_mirror_del;
    int (*)(struct dsa_switch *, int, struct dsa_mall_policer_tc_entry *) port_policer_add;
    void (*)(struct dsa_switch *, int) port_policer_del;
    int (*)(struct dsa_switch *, int, enum tc_setup_type, void *) port_setup_tc;
    int (*)(struct dsa_switch *, int, int, int, struct dsa_bridge, struct netlink_ext_ack *) crosschip_bridge_join;
    void (*)(struct dsa_switch *, int, int, int, struct dsa_bridge) crosschip_bridge_leave;
    int (*)(struct dsa_switch *, int, int) crosschip_lag_change;
    int (*)(struct dsa_switch *, int, int, struct dsa_lag, struct netdev_lag_upper_info *, struct netlink_ext_ack *) crosschip_lag_join;
    int (*)(struct dsa_switch *, int, int, struct dsa_lag) crosschip_lag_leave;
    int (*)(struct dsa_switch *, int, struct ifreq *) port_hwtstamp_get;
    int (*)(struct dsa_switch *, int, struct ifreq *) port_hwtstamp_set;
    void (*)(struct dsa_switch *, int, struct sk_buff *) port_txtstamp;
    bool (*)(struct dsa_switch *, int, struct sk_buff *, unsigned int) port_rxtstamp;
    int (*)(struct dsa_switch *, u32, struct devlink_param_gset_ctx *) devlink_param_get;
    int (*)(struct dsa_switch *, u32, struct devlink_param_gset_ctx *) devlink_param_set;
    int (*)(struct dsa_switch *, struct devlink_info_req *, struct netlink_ext_ack *) devlink_info_get;
    int (*)(struct dsa_switch *, unsigned int, u16, struct devlink_sb_pool_info *) devlink_sb_pool_get;
    int (*)(struct dsa_switch *, unsigned int, u16, u32, enum devlink_sb_threshold_type, struct netlink_ext_ack *) devlink_sb_pool_set;
    int (*)(struct dsa_switch *, int, unsigned int, u16, u32 *) devlink_sb_port_pool_get;
    int (*)(struct dsa_switch *, int, unsigned int, u16, u32, struct netlink_ext_ack *) devlink_sb_port_pool_set;
    int (*)(struct dsa_switch *, int, unsigned int, u16, enum devlink_sb_pool_type, u16 *, u32 *) devlink_sb_tc_pool_bind_get;
    int (*)(struct dsa_switch *, int, unsigned int, u16, enum devlink_sb_pool_type, u16, u32, struct netlink_ext_ack *) devlink_sb_tc_pool_bind_set;
    int (*)(struct dsa_switch *, unsigned int) devlink_sb_occ_snapshot;
    int (*)(struct dsa_switch *, unsigned int) devlink_sb_occ_max_clear;
    int (*)(struct dsa_switch *, int, unsigned int, u16, u32 *, u32 *) devlink_sb_occ_port_pool_get;
    int (*)(struct dsa_switch *, int, unsigned int, u16, enum devlink_sb_pool_type, u32 *, u32 *) devlink_sb_occ_tc_port_bind_get;
    int (*)(struct dsa_switch *, int, int) port_change_mtu;
    int (*)(struct dsa_switch *, int) port_max_mtu;
    int (*)(struct dsa_switch *, int) port_lag_change;
    int (*)(struct dsa_switch *, int, struct dsa_lag, struct netdev_lag_upper_info *, struct netlink_ext_ack *) port_lag_join;
    int (*)(struct dsa_switch *, int, struct dsa_lag) port_lag_leave;
    int (*)(struct dsa_switch *, int, struct net_device *, struct netlink_ext_ack *) port_hsr_join;
    int (*)(struct dsa_switch *, int, struct net_device *) port_hsr_leave;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_mrp *) port_mrp_add;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_mrp *) port_mrp_del;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_ring_role_mrp *) port_mrp_add_ring_role;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_ring_role_mrp *) port_mrp_del_ring_role;
    int (*)(struct dsa_switch *, int, u16, u16) tag_8021q_vlan_add;
    int (*)(struct dsa_switch *, int, u16) tag_8021q_vlan_del;
    void (*)(struct dsa_switch *, const struct net_device *, bool) conduit_state_change;
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
struct dsa_switch_ops {
    enum dsa_tag_protocol (*)(struct dsa_switch *, int) get_tag_protocol;
    int (*)(struct dsa_switch *) setup;
    void (*)(struct dsa_switch *) teardown;
    u32 (*)(struct dsa_switch *, int) get_phy_flags;
    int (*)(struct dsa_switch *, int, int) phy_read;
    int (*)(struct dsa_switch *, int, int, u16) phy_write;
    void (*)(struct dsa_switch *, int, struct phy_device *) adjust_link;
    void (*)(struct dsa_switch *, int, struct fixed_phy_status *) fixed_link_update;
    void (*)(struct dsa_switch *, int, long unsigned int *, struct phylink_link_state *) phylink_validate;
    int (*)(struct dsa_switch *, int, struct phylink_link_state *) phylink_mac_link_state;
    void (*)(struct dsa_switch *, int, unsigned int, const struct phylink_link_state *) phylink_mac_config;
    void (*)(struct dsa_switch *, int) phylink_mac_an_restart;
    void (*)(struct dsa_switch *, int, unsigned int, phy_interface_t) phylink_mac_link_down;
    void (*)(struct dsa_switch *, int, unsigned int, phy_interface_t, struct phy_device *) phylink_mac_link_up;
    void (*)(struct dsa_switch *, int, struct phylink_link_state *) phylink_fixed_state;
    void (*)(struct dsa_switch *, int, u32, uint8_t *) get_strings;
    void (*)(struct dsa_switch *, int, uint64_t *) get_ethtool_stats;
    int (*)(struct dsa_switch *, int, int) get_sset_count;
    void (*)(struct dsa_switch *, int, uint64_t *) get_ethtool_phy_stats;
    void (*)(struct dsa_switch *, int, struct ethtool_wolinfo *) get_wol;
    int (*)(struct dsa_switch *, int, struct ethtool_wolinfo *) set_wol;
    int (*)(struct dsa_switch *, int, struct ethtool_ts_info *) get_ts_info;
    int (*)(struct dsa_switch *) suspend;
    int (*)(struct dsa_switch *) resume;
    int (*)(struct dsa_switch *, int, struct phy_device *) port_enable;
    void (*)(struct dsa_switch *, int) port_disable;
    int (*)(struct dsa_switch *, int, struct ethtool_eee *) set_mac_eee;
    int (*)(struct dsa_switch *, int, struct ethtool_eee *) get_mac_eee;
    int (*)(struct dsa_switch *) get_eeprom_len;
    int (*)(struct dsa_switch *, struct ethtool_eeprom *, u8 *) get_eeprom;
    int (*)(struct dsa_switch *, struct ethtool_eeprom *, u8 *) set_eeprom;
    int (*)(struct dsa_switch *, int) get_regs_len;
    void (*)(struct dsa_switch *, int, struct ethtool_regs *, void *) get_regs;
    int (*)(struct dsa_switch *, unsigned int) set_ageing_time;
    int (*)(struct dsa_switch *, int, struct net_device *) port_bridge_join;
    void (*)(struct dsa_switch *, int, struct net_device *) port_bridge_leave;
    void (*)(struct dsa_switch *, int, u8) port_stp_state_set;
    void (*)(struct dsa_switch *, int) port_fast_age;
    int (*)(struct dsa_switch *, int, bool, bool) port_egress_floods;
    int (*)(struct dsa_switch *, int, bool) port_vlan_filtering;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_vlan *) port_vlan_prepare;
    void (*)(struct dsa_switch *, int, const struct switchdev_obj_port_vlan *) port_vlan_add;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_vlan *) port_vlan_del;
    int (*)(struct dsa_switch *, int, const unsigned char *, u16) port_fdb_add;
    int (*)(struct dsa_switch *, int, const unsigned char *, u16) port_fdb_del;
    int (*)(struct dsa_switch *, int, dsa_fdb_dump_cb_t *, void *) port_fdb_dump;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_mdb *) port_mdb_prepare;
    void (*)(struct dsa_switch *, int, const struct switchdev_obj_port_mdb *) port_mdb_add;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_mdb *) port_mdb_del;
    int (*)(struct dsa_switch *, int, struct ethtool_rxnfc *, u32 *) get_rxnfc;
    int (*)(struct dsa_switch *, int, struct ethtool_rxnfc *) set_rxnfc;
    int (*)(struct dsa_switch *, int, struct dsa_mall_mirror_tc_entry *, bool) port_mirror_add;
    void (*)(struct dsa_switch *, int, struct dsa_mall_mirror_tc_entry *) port_mirror_del;
    int (*)(struct dsa_switch *, int, enum tc_setup_type, void *) port_setup_tc;
    int (*)(struct dsa_switch *, int, int, struct net_device *) crosschip_bridge_join;
    void (*)(struct dsa_switch *, int, int, struct net_device *) crosschip_bridge_leave;
    int (*)(struct dsa_switch *, int, struct ifreq *) port_hwtstamp_get;
    int (*)(struct dsa_switch *, int, struct ifreq *) port_hwtstamp_set;
    bool (*)(struct dsa_switch *, int, struct sk_buff *, unsigned int) port_txtstamp;
    bool (*)(struct dsa_switch *, int, struct sk_buff *, unsigned int) port_rxtstamp;
    netdev_tx_t (*)(struct dsa_switch *, int, struct sk_buff *) port_deferred_xmit;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct dsa_switch_ops {
    enum dsa_tag_protocol (*)(struct dsa_switch *, int) get_tag_protocol;
    int (*)(struct dsa_switch *) setup;
    void (*)(struct dsa_switch *) teardown;
    u32 (*)(struct dsa_switch *, int) get_phy_flags;
    int (*)(struct dsa_switch *, int, int) phy_read;
    int (*)(struct dsa_switch *, int, int, u16) phy_write;
    void (*)(struct dsa_switch *, int, struct phy_device *) adjust_link;
    void (*)(struct dsa_switch *, int, struct fixed_phy_status *) fixed_link_update;
    void (*)(struct dsa_switch *, int, long unsigned int *, struct phylink_link_state *) phylink_validate;
    int (*)(struct dsa_switch *, int, struct phylink_link_state *) phylink_mac_link_state;
    void (*)(struct dsa_switch *, int, unsigned int, const struct phylink_link_state *) phylink_mac_config;
    void (*)(struct dsa_switch *, int) phylink_mac_an_restart;
    void (*)(struct dsa_switch *, int, unsigned int, phy_interface_t) phylink_mac_link_down;
    void (*)(struct dsa_switch *, int, unsigned int, phy_interface_t, struct phy_device *) phylink_mac_link_up;
    void (*)(struct dsa_switch *, int, struct phylink_link_state *) phylink_fixed_state;
    void (*)(struct dsa_switch *, int, u32, uint8_t *) get_strings;
    void (*)(struct dsa_switch *, int, uint64_t *) get_ethtool_stats;
    int (*)(struct dsa_switch *, int, int) get_sset_count;
    void (*)(struct dsa_switch *, int, uint64_t *) get_ethtool_phy_stats;
    void (*)(struct dsa_switch *, int, struct ethtool_wolinfo *) get_wol;
    int (*)(struct dsa_switch *, int, struct ethtool_wolinfo *) set_wol;
    int (*)(struct dsa_switch *, int, struct ethtool_ts_info *) get_ts_info;
    int (*)(struct dsa_switch *) suspend;
    int (*)(struct dsa_switch *) resume;
    int (*)(struct dsa_switch *, int, struct phy_device *) port_enable;
    void (*)(struct dsa_switch *, int) port_disable;
    int (*)(struct dsa_switch *, int, struct ethtool_eee *) set_mac_eee;
    int (*)(struct dsa_switch *, int, struct ethtool_eee *) get_mac_eee;
    int (*)(struct dsa_switch *) get_eeprom_len;
    int (*)(struct dsa_switch *, struct ethtool_eeprom *, u8 *) get_eeprom;
    int (*)(struct dsa_switch *, struct ethtool_eeprom *, u8 *) set_eeprom;
    int (*)(struct dsa_switch *, int) get_regs_len;
    void (*)(struct dsa_switch *, int, struct ethtool_regs *, void *) get_regs;
    int (*)(struct dsa_switch *, unsigned int) set_ageing_time;
    int (*)(struct dsa_switch *, int, struct net_device *) port_bridge_join;
    void (*)(struct dsa_switch *, int, struct net_device *) port_bridge_leave;
    void (*)(struct dsa_switch *, int, u8) port_stp_state_set;
    void (*)(struct dsa_switch *, int) port_fast_age;
    int (*)(struct dsa_switch *, int, bool, bool) port_egress_floods;
    int (*)(struct dsa_switch *, int, bool) port_vlan_filtering;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_vlan *) port_vlan_prepare;
    void (*)(struct dsa_switch *, int, const struct switchdev_obj_port_vlan *) port_vlan_add;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_vlan *) port_vlan_del;
    int (*)(struct dsa_switch *, int, const unsigned char *, u16) port_fdb_add;
    int (*)(struct dsa_switch *, int, const unsigned char *, u16) port_fdb_del;
    int (*)(struct dsa_switch *, int, dsa_fdb_dump_cb_t *, void *) port_fdb_dump;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_mdb *) port_mdb_prepare;
    void (*)(struct dsa_switch *, int, const struct switchdev_obj_port_mdb *) port_mdb_add;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_mdb *) port_mdb_del;
    int (*)(struct dsa_switch *, int, struct ethtool_rxnfc *, u32 *) get_rxnfc;
    int (*)(struct dsa_switch *, int, struct ethtool_rxnfc *) set_rxnfc;
    int (*)(struct dsa_switch *, int, struct dsa_mall_mirror_tc_entry *, bool) port_mirror_add;
    void (*)(struct dsa_switch *, int, struct dsa_mall_mirror_tc_entry *) port_mirror_del;
    int (*)(struct dsa_switch *, int, enum tc_setup_type, void *) port_setup_tc;
    int (*)(struct dsa_switch *, int, int, struct net_device *) crosschip_bridge_join;
    void (*)(struct dsa_switch *, int, int, struct net_device *) crosschip_bridge_leave;
    int (*)(struct dsa_switch *, int, struct ifreq *) port_hwtstamp_get;
    int (*)(struct dsa_switch *, int, struct ifreq *) port_hwtstamp_set;
    bool (*)(struct dsa_switch *, int, struct sk_buff *, unsigned int) port_txtstamp;
    bool (*)(struct dsa_switch *, int, struct sk_buff *, unsigned int) port_rxtstamp;
    netdev_tx_t (*)(struct dsa_switch *, int, struct sk_buff *) port_deferred_xmit;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct dsa_switch_ops {
    enum dsa_tag_protocol (*)(struct dsa_switch *, int) get_tag_protocol;
    int (*)(struct dsa_switch *) setup;
    void (*)(struct dsa_switch *) teardown;
    u32 (*)(struct dsa_switch *, int) get_phy_flags;
    int (*)(struct dsa_switch *, int, int) phy_read;
    int (*)(struct dsa_switch *, int, int, u16) phy_write;
    void (*)(struct dsa_switch *, int, struct phy_device *) adjust_link;
    void (*)(struct dsa_switch *, int, struct fixed_phy_status *) fixed_link_update;
    void (*)(struct dsa_switch *, int, long unsigned int *, struct phylink_link_state *) phylink_validate;
    int (*)(struct dsa_switch *, int, struct phylink_link_state *) phylink_mac_link_state;
    void (*)(struct dsa_switch *, int, unsigned int, const struct phylink_link_state *) phylink_mac_config;
    void (*)(struct dsa_switch *, int) phylink_mac_an_restart;
    void (*)(struct dsa_switch *, int, unsigned int, phy_interface_t) phylink_mac_link_down;
    void (*)(struct dsa_switch *, int, unsigned int, phy_interface_t, struct phy_device *) phylink_mac_link_up;
    void (*)(struct dsa_switch *, int, struct phylink_link_state *) phylink_fixed_state;
    void (*)(struct dsa_switch *, int, u32, uint8_t *) get_strings;
    void (*)(struct dsa_switch *, int, uint64_t *) get_ethtool_stats;
    int (*)(struct dsa_switch *, int, int) get_sset_count;
    void (*)(struct dsa_switch *, int, uint64_t *) get_ethtool_phy_stats;
    void (*)(struct dsa_switch *, int, struct ethtool_wolinfo *) get_wol;
    int (*)(struct dsa_switch *, int, struct ethtool_wolinfo *) set_wol;
    int (*)(struct dsa_switch *, int, struct ethtool_ts_info *) get_ts_info;
    int (*)(struct dsa_switch *) suspend;
    int (*)(struct dsa_switch *) resume;
    int (*)(struct dsa_switch *, int, struct phy_device *) port_enable;
    void (*)(struct dsa_switch *, int) port_disable;
    int (*)(struct dsa_switch *, int, struct ethtool_eee *) set_mac_eee;
    int (*)(struct dsa_switch *, int, struct ethtool_eee *) get_mac_eee;
    int (*)(struct dsa_switch *) get_eeprom_len;
    int (*)(struct dsa_switch *, struct ethtool_eeprom *, u8 *) get_eeprom;
    int (*)(struct dsa_switch *, struct ethtool_eeprom *, u8 *) set_eeprom;
    int (*)(struct dsa_switch *, int) get_regs_len;
    void (*)(struct dsa_switch *, int, struct ethtool_regs *, void *) get_regs;
    int (*)(struct dsa_switch *, unsigned int) set_ageing_time;
    int (*)(struct dsa_switch *, int, struct net_device *) port_bridge_join;
    void (*)(struct dsa_switch *, int, struct net_device *) port_bridge_leave;
    void (*)(struct dsa_switch *, int, u8) port_stp_state_set;
    void (*)(struct dsa_switch *, int) port_fast_age;
    int (*)(struct dsa_switch *, int, bool, bool) port_egress_floods;
    int (*)(struct dsa_switch *, int, bool) port_vlan_filtering;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_vlan *) port_vlan_prepare;
    void (*)(struct dsa_switch *, int, const struct switchdev_obj_port_vlan *) port_vlan_add;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_vlan *) port_vlan_del;
    int (*)(struct dsa_switch *, int, const unsigned char *, u16) port_fdb_add;
    int (*)(struct dsa_switch *, int, const unsigned char *, u16) port_fdb_del;
    int (*)(struct dsa_switch *, int, dsa_fdb_dump_cb_t *, void *) port_fdb_dump;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_mdb *) port_mdb_prepare;
    void (*)(struct dsa_switch *, int, const struct switchdev_obj_port_mdb *) port_mdb_add;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_mdb *) port_mdb_del;
    int (*)(struct dsa_switch *, int, struct ethtool_rxnfc *, u32 *) get_rxnfc;
    int (*)(struct dsa_switch *, int, struct ethtool_rxnfc *) set_rxnfc;
    int (*)(struct dsa_switch *, int, struct dsa_mall_mirror_tc_entry *, bool) port_mirror_add;
    void (*)(struct dsa_switch *, int, struct dsa_mall_mirror_tc_entry *) port_mirror_del;
    int (*)(struct dsa_switch *, int, enum tc_setup_type, void *) port_setup_tc;
    int (*)(struct dsa_switch *, int, int, struct net_device *) crosschip_bridge_join;
    void (*)(struct dsa_switch *, int, int, struct net_device *) crosschip_bridge_leave;
    int (*)(struct dsa_switch *, int, struct ifreq *) port_hwtstamp_get;
    int (*)(struct dsa_switch *, int, struct ifreq *) port_hwtstamp_set;
    bool (*)(struct dsa_switch *, int, struct sk_buff *, unsigned int) port_txtstamp;
    bool (*)(struct dsa_switch *, int, struct sk_buff *, unsigned int) port_rxtstamp;
    netdev_tx_t (*)(struct dsa_switch *, int, struct sk_buff *) port_deferred_xmit;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct dsa_switch_ops {
    enum dsa_tag_protocol (*)(struct dsa_switch *, int) get_tag_protocol;
    int (*)(struct dsa_switch *) setup;
    void (*)(struct dsa_switch *) teardown;
    u32 (*)(struct dsa_switch *, int) get_phy_flags;
    int (*)(struct dsa_switch *, int, int) phy_read;
    int (*)(struct dsa_switch *, int, int, u16) phy_write;
    void (*)(struct dsa_switch *, int, struct phy_device *) adjust_link;
    void (*)(struct dsa_switch *, int, struct fixed_phy_status *) fixed_link_update;
    void (*)(struct dsa_switch *, int, long unsigned int *, struct phylink_link_state *) phylink_validate;
    int (*)(struct dsa_switch *, int, struct phylink_link_state *) phylink_mac_link_state;
    void (*)(struct dsa_switch *, int, unsigned int, const struct phylink_link_state *) phylink_mac_config;
    void (*)(struct dsa_switch *, int) phylink_mac_an_restart;
    void (*)(struct dsa_switch *, int, unsigned int, phy_interface_t) phylink_mac_link_down;
    void (*)(struct dsa_switch *, int, unsigned int, phy_interface_t, struct phy_device *) phylink_mac_link_up;
    void (*)(struct dsa_switch *, int, struct phylink_link_state *) phylink_fixed_state;
    void (*)(struct dsa_switch *, int, u32, uint8_t *) get_strings;
    void (*)(struct dsa_switch *, int, uint64_t *) get_ethtool_stats;
    int (*)(struct dsa_switch *, int, int) get_sset_count;
    void (*)(struct dsa_switch *, int, uint64_t *) get_ethtool_phy_stats;
    void (*)(struct dsa_switch *, int, struct ethtool_wolinfo *) get_wol;
    int (*)(struct dsa_switch *, int, struct ethtool_wolinfo *) set_wol;
    int (*)(struct dsa_switch *, int, struct ethtool_ts_info *) get_ts_info;
    int (*)(struct dsa_switch *) suspend;
    int (*)(struct dsa_switch *) resume;
    int (*)(struct dsa_switch *, int, struct phy_device *) port_enable;
    void (*)(struct dsa_switch *, int) port_disable;
    int (*)(struct dsa_switch *, int, struct ethtool_eee *) set_mac_eee;
    int (*)(struct dsa_switch *, int, struct ethtool_eee *) get_mac_eee;
    int (*)(struct dsa_switch *) get_eeprom_len;
    int (*)(struct dsa_switch *, struct ethtool_eeprom *, u8 *) get_eeprom;
    int (*)(struct dsa_switch *, struct ethtool_eeprom *, u8 *) set_eeprom;
    int (*)(struct dsa_switch *, int) get_regs_len;
    void (*)(struct dsa_switch *, int, struct ethtool_regs *, void *) get_regs;
    int (*)(struct dsa_switch *, unsigned int) set_ageing_time;
    int (*)(struct dsa_switch *, int, struct net_device *) port_bridge_join;
    void (*)(struct dsa_switch *, int, struct net_device *) port_bridge_leave;
    void (*)(struct dsa_switch *, int, u8) port_stp_state_set;
    void (*)(struct dsa_switch *, int) port_fast_age;
    int (*)(struct dsa_switch *, int, bool, bool) port_egress_floods;
    int (*)(struct dsa_switch *, int, bool) port_vlan_filtering;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_vlan *) port_vlan_prepare;
    void (*)(struct dsa_switch *, int, const struct switchdev_obj_port_vlan *) port_vlan_add;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_vlan *) port_vlan_del;
    int (*)(struct dsa_switch *, int, const unsigned char *, u16) port_fdb_add;
    int (*)(struct dsa_switch *, int, const unsigned char *, u16) port_fdb_del;
    int (*)(struct dsa_switch *, int, dsa_fdb_dump_cb_t *, void *) port_fdb_dump;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_mdb *) port_mdb_prepare;
    void (*)(struct dsa_switch *, int, const struct switchdev_obj_port_mdb *) port_mdb_add;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_mdb *) port_mdb_del;
    int (*)(struct dsa_switch *, int, struct ethtool_rxnfc *, u32 *) get_rxnfc;
    int (*)(struct dsa_switch *, int, struct ethtool_rxnfc *) set_rxnfc;
    int (*)(struct dsa_switch *, int, struct dsa_mall_mirror_tc_entry *, bool) port_mirror_add;
    void (*)(struct dsa_switch *, int, struct dsa_mall_mirror_tc_entry *) port_mirror_del;
    int (*)(struct dsa_switch *, int, enum tc_setup_type, void *) port_setup_tc;
    int (*)(struct dsa_switch *, int, int, struct net_device *) crosschip_bridge_join;
    void (*)(struct dsa_switch *, int, int, struct net_device *) crosschip_bridge_leave;
    int (*)(struct dsa_switch *, int, struct ifreq *) port_hwtstamp_get;
    int (*)(struct dsa_switch *, int, struct ifreq *) port_hwtstamp_set;
    bool (*)(struct dsa_switch *, int, struct sk_buff *, unsigned int) port_txtstamp;
    bool (*)(struct dsa_switch *, int, struct sk_buff *, unsigned int) port_rxtstamp;
    netdev_tx_t (*)(struct dsa_switch *, int, struct sk_buff *) port_deferred_xmit;
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
struct dsa_switch_ops {
    enum dsa_tag_protocol (*)(struct dsa_switch *, int) get_tag_protocol;
    int (*)(struct dsa_switch *) setup;
    void (*)(struct dsa_switch *) teardown;
    u32 (*)(struct dsa_switch *, int) get_phy_flags;
    int (*)(struct dsa_switch *, int, int) phy_read;
    int (*)(struct dsa_switch *, int, int, u16) phy_write;
    void (*)(struct dsa_switch *, int, struct phy_device *) adjust_link;
    void (*)(struct dsa_switch *, int, struct fixed_phy_status *) fixed_link_update;
    void (*)(struct dsa_switch *, int, long unsigned int *, struct phylink_link_state *) phylink_validate;
    int (*)(struct dsa_switch *, int, struct phylink_link_state *) phylink_mac_link_state;
    void (*)(struct dsa_switch *, int, unsigned int, const struct phylink_link_state *) phylink_mac_config;
    void (*)(struct dsa_switch *, int) phylink_mac_an_restart;
    void (*)(struct dsa_switch *, int, unsigned int, phy_interface_t) phylink_mac_link_down;
    void (*)(struct dsa_switch *, int, unsigned int, phy_interface_t, struct phy_device *) phylink_mac_link_up;
    void (*)(struct dsa_switch *, int, struct phylink_link_state *) phylink_fixed_state;
    void (*)(struct dsa_switch *, int, u32, uint8_t *) get_strings;
    void (*)(struct dsa_switch *, int, uint64_t *) get_ethtool_stats;
    int (*)(struct dsa_switch *, int, int) get_sset_count;
    void (*)(struct dsa_switch *, int, uint64_t *) get_ethtool_phy_stats;
    void (*)(struct dsa_switch *, int, struct ethtool_wolinfo *) get_wol;
    int (*)(struct dsa_switch *, int, struct ethtool_wolinfo *) set_wol;
    int (*)(struct dsa_switch *, int, struct ethtool_ts_info *) get_ts_info;
    int (*)(struct dsa_switch *) suspend;
    int (*)(struct dsa_switch *) resume;
    int (*)(struct dsa_switch *, int, struct phy_device *) port_enable;
    void (*)(struct dsa_switch *, int) port_disable;
    int (*)(struct dsa_switch *, int, struct ethtool_eee *) set_mac_eee;
    int (*)(struct dsa_switch *, int, struct ethtool_eee *) get_mac_eee;
    int (*)(struct dsa_switch *) get_eeprom_len;
    int (*)(struct dsa_switch *, struct ethtool_eeprom *, u8 *) get_eeprom;
    int (*)(struct dsa_switch *, struct ethtool_eeprom *, u8 *) set_eeprom;
    int (*)(struct dsa_switch *, int) get_regs_len;
    void (*)(struct dsa_switch *, int, struct ethtool_regs *, void *) get_regs;
    int (*)(struct dsa_switch *, unsigned int) set_ageing_time;
    int (*)(struct dsa_switch *, int, struct net_device *) port_bridge_join;
    void (*)(struct dsa_switch *, int, struct net_device *) port_bridge_leave;
    void (*)(struct dsa_switch *, int, u8) port_stp_state_set;
    void (*)(struct dsa_switch *, int) port_fast_age;
    int (*)(struct dsa_switch *, int, bool, bool) port_egress_floods;
    int (*)(struct dsa_switch *, int, bool) port_vlan_filtering;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_vlan *) port_vlan_prepare;
    void (*)(struct dsa_switch *, int, const struct switchdev_obj_port_vlan *) port_vlan_add;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_vlan *) port_vlan_del;
    int (*)(struct dsa_switch *, int, const unsigned char *, u16) port_fdb_add;
    int (*)(struct dsa_switch *, int, const unsigned char *, u16) port_fdb_del;
    int (*)(struct dsa_switch *, int, dsa_fdb_dump_cb_t *, void *) port_fdb_dump;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_mdb *) port_mdb_prepare;
    void (*)(struct dsa_switch *, int, const struct switchdev_obj_port_mdb *) port_mdb_add;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_mdb *) port_mdb_del;
    int (*)(struct dsa_switch *, int, struct ethtool_rxnfc *, u32 *) get_rxnfc;
    int (*)(struct dsa_switch *, int, struct ethtool_rxnfc *) set_rxnfc;
    int (*)(struct dsa_switch *, int, struct dsa_mall_mirror_tc_entry *, bool) port_mirror_add;
    void (*)(struct dsa_switch *, int, struct dsa_mall_mirror_tc_entry *) port_mirror_del;
    int (*)(struct dsa_switch *, int, enum tc_setup_type, void *) port_setup_tc;
    int (*)(struct dsa_switch *, int, int, struct net_device *) crosschip_bridge_join;
    void (*)(struct dsa_switch *, int, int, struct net_device *) crosschip_bridge_leave;
    int (*)(struct dsa_switch *, int, struct ifreq *) port_hwtstamp_get;
    int (*)(struct dsa_switch *, int, struct ifreq *) port_hwtstamp_set;
    bool (*)(struct dsa_switch *, int, struct sk_buff *, unsigned int) port_txtstamp;
    bool (*)(struct dsa_switch *, int, struct sk_buff *, unsigned int) port_rxtstamp;
    netdev_tx_t (*)(struct dsa_switch *, int, struct sk_buff *) port_deferred_xmit;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct dsa_switch_ops {
    enum dsa_tag_protocol (*)(struct dsa_switch *, int) get_tag_protocol;
    int (*)(struct dsa_switch *) setup;
    void (*)(struct dsa_switch *) teardown;
    u32 (*)(struct dsa_switch *, int) get_phy_flags;
    int (*)(struct dsa_switch *, int, int) phy_read;
    int (*)(struct dsa_switch *, int, int, u16) phy_write;
    void (*)(struct dsa_switch *, int, struct phy_device *) adjust_link;
    void (*)(struct dsa_switch *, int, struct fixed_phy_status *) fixed_link_update;
    void (*)(struct dsa_switch *, int, long unsigned int *, struct phylink_link_state *) phylink_validate;
    int (*)(struct dsa_switch *, int, struct phylink_link_state *) phylink_mac_link_state;
    void (*)(struct dsa_switch *, int, unsigned int, const struct phylink_link_state *) phylink_mac_config;
    void (*)(struct dsa_switch *, int) phylink_mac_an_restart;
    void (*)(struct dsa_switch *, int, unsigned int, phy_interface_t) phylink_mac_link_down;
    void (*)(struct dsa_switch *, int, unsigned int, phy_interface_t, struct phy_device *) phylink_mac_link_up;
    void (*)(struct dsa_switch *, int, struct phylink_link_state *) phylink_fixed_state;
    void (*)(struct dsa_switch *, int, u32, uint8_t *) get_strings;
    void (*)(struct dsa_switch *, int, uint64_t *) get_ethtool_stats;
    int (*)(struct dsa_switch *, int, int) get_sset_count;
    void (*)(struct dsa_switch *, int, uint64_t *) get_ethtool_phy_stats;
    void (*)(struct dsa_switch *, int, struct ethtool_wolinfo *) get_wol;
    int (*)(struct dsa_switch *, int, struct ethtool_wolinfo *) set_wol;
    int (*)(struct dsa_switch *, int, struct ethtool_ts_info *) get_ts_info;
    int (*)(struct dsa_switch *) suspend;
    int (*)(struct dsa_switch *) resume;
    int (*)(struct dsa_switch *, int, struct phy_device *) port_enable;
    void (*)(struct dsa_switch *, int) port_disable;
    int (*)(struct dsa_switch *, int, struct ethtool_eee *) set_mac_eee;
    int (*)(struct dsa_switch *, int, struct ethtool_eee *) get_mac_eee;
    int (*)(struct dsa_switch *) get_eeprom_len;
    int (*)(struct dsa_switch *, struct ethtool_eeprom *, u8 *) get_eeprom;
    int (*)(struct dsa_switch *, struct ethtool_eeprom *, u8 *) set_eeprom;
    int (*)(struct dsa_switch *, int) get_regs_len;
    void (*)(struct dsa_switch *, int, struct ethtool_regs *, void *) get_regs;
    int (*)(struct dsa_switch *, unsigned int) set_ageing_time;
    int (*)(struct dsa_switch *, int, struct net_device *) port_bridge_join;
    void (*)(struct dsa_switch *, int, struct net_device *) port_bridge_leave;
    void (*)(struct dsa_switch *, int, u8) port_stp_state_set;
    void (*)(struct dsa_switch *, int) port_fast_age;
    int (*)(struct dsa_switch *, int, bool, bool) port_egress_floods;
    int (*)(struct dsa_switch *, int, bool) port_vlan_filtering;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_vlan *) port_vlan_prepare;
    void (*)(struct dsa_switch *, int, const struct switchdev_obj_port_vlan *) port_vlan_add;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_vlan *) port_vlan_del;
    int (*)(struct dsa_switch *, int, const unsigned char *, u16) port_fdb_add;
    int (*)(struct dsa_switch *, int, const unsigned char *, u16) port_fdb_del;
    int (*)(struct dsa_switch *, int, dsa_fdb_dump_cb_t *, void *) port_fdb_dump;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_mdb *) port_mdb_prepare;
    void (*)(struct dsa_switch *, int, const struct switchdev_obj_port_mdb *) port_mdb_add;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_mdb *) port_mdb_del;
    int (*)(struct dsa_switch *, int, struct ethtool_rxnfc *, u32 *) get_rxnfc;
    int (*)(struct dsa_switch *, int, struct ethtool_rxnfc *) set_rxnfc;
    int (*)(struct dsa_switch *, int, struct dsa_mall_mirror_tc_entry *, bool) port_mirror_add;
    void (*)(struct dsa_switch *, int, struct dsa_mall_mirror_tc_entry *) port_mirror_del;
    int (*)(struct dsa_switch *, int, enum tc_setup_type, void *) port_setup_tc;
    int (*)(struct dsa_switch *, int, int, struct net_device *) crosschip_bridge_join;
    void (*)(struct dsa_switch *, int, int, struct net_device *) crosschip_bridge_leave;
    int (*)(struct dsa_switch *, int, struct ifreq *) port_hwtstamp_get;
    int (*)(struct dsa_switch *, int, struct ifreq *) port_hwtstamp_set;
    bool (*)(struct dsa_switch *, int, struct sk_buff *, unsigned int) port_txtstamp;
    bool (*)(struct dsa_switch *, int, struct sk_buff *, unsigned int) port_rxtstamp;
    netdev_tx_t (*)(struct dsa_switch *, int, struct sk_buff *) port_deferred_xmit;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct dsa_switch_ops {
    enum dsa_tag_protocol (*)(struct dsa_switch *, int) get_tag_protocol;
    int (*)(struct dsa_switch *) setup;
    void (*)(struct dsa_switch *) teardown;
    u32 (*)(struct dsa_switch *, int) get_phy_flags;
    int (*)(struct dsa_switch *, int, int) phy_read;
    int (*)(struct dsa_switch *, int, int, u16) phy_write;
    void (*)(struct dsa_switch *, int, struct phy_device *) adjust_link;
    void (*)(struct dsa_switch *, int, struct fixed_phy_status *) fixed_link_update;
    void (*)(struct dsa_switch *, int, long unsigned int *, struct phylink_link_state *) phylink_validate;
    int (*)(struct dsa_switch *, int, struct phylink_link_state *) phylink_mac_link_state;
    void (*)(struct dsa_switch *, int, unsigned int, const struct phylink_link_state *) phylink_mac_config;
    void (*)(struct dsa_switch *, int) phylink_mac_an_restart;
    void (*)(struct dsa_switch *, int, unsigned int, phy_interface_t) phylink_mac_link_down;
    void (*)(struct dsa_switch *, int, unsigned int, phy_interface_t, struct phy_device *) phylink_mac_link_up;
    void (*)(struct dsa_switch *, int, struct phylink_link_state *) phylink_fixed_state;
    void (*)(struct dsa_switch *, int, u32, uint8_t *) get_strings;
    void (*)(struct dsa_switch *, int, uint64_t *) get_ethtool_stats;
    int (*)(struct dsa_switch *, int, int) get_sset_count;
    void (*)(struct dsa_switch *, int, uint64_t *) get_ethtool_phy_stats;
    void (*)(struct dsa_switch *, int, struct ethtool_wolinfo *) get_wol;
    int (*)(struct dsa_switch *, int, struct ethtool_wolinfo *) set_wol;
    int (*)(struct dsa_switch *, int, struct ethtool_ts_info *) get_ts_info;
    int (*)(struct dsa_switch *) suspend;
    int (*)(struct dsa_switch *) resume;
    int (*)(struct dsa_switch *, int, struct phy_device *) port_enable;
    void (*)(struct dsa_switch *, int) port_disable;
    int (*)(struct dsa_switch *, int, struct ethtool_eee *) set_mac_eee;
    int (*)(struct dsa_switch *, int, struct ethtool_eee *) get_mac_eee;
    int (*)(struct dsa_switch *) get_eeprom_len;
    int (*)(struct dsa_switch *, struct ethtool_eeprom *, u8 *) get_eeprom;
    int (*)(struct dsa_switch *, struct ethtool_eeprom *, u8 *) set_eeprom;
    int (*)(struct dsa_switch *, int) get_regs_len;
    void (*)(struct dsa_switch *, int, struct ethtool_regs *, void *) get_regs;
    int (*)(struct dsa_switch *, unsigned int) set_ageing_time;
    int (*)(struct dsa_switch *, int, struct net_device *) port_bridge_join;
    void (*)(struct dsa_switch *, int, struct net_device *) port_bridge_leave;
    void (*)(struct dsa_switch *, int, u8) port_stp_state_set;
    void (*)(struct dsa_switch *, int) port_fast_age;
    int (*)(struct dsa_switch *, int, bool, bool) port_egress_floods;
    int (*)(struct dsa_switch *, int, bool) port_vlan_filtering;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_vlan *) port_vlan_prepare;
    void (*)(struct dsa_switch *, int, const struct switchdev_obj_port_vlan *) port_vlan_add;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_vlan *) port_vlan_del;
    int (*)(struct dsa_switch *, int, const unsigned char *, u16) port_fdb_add;
    int (*)(struct dsa_switch *, int, const unsigned char *, u16) port_fdb_del;
    int (*)(struct dsa_switch *, int, dsa_fdb_dump_cb_t *, void *) port_fdb_dump;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_mdb *) port_mdb_prepare;
    void (*)(struct dsa_switch *, int, const struct switchdev_obj_port_mdb *) port_mdb_add;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_mdb *) port_mdb_del;
    int (*)(struct dsa_switch *, int, struct ethtool_rxnfc *, u32 *) get_rxnfc;
    int (*)(struct dsa_switch *, int, struct ethtool_rxnfc *) set_rxnfc;
    int (*)(struct dsa_switch *, int, struct dsa_mall_mirror_tc_entry *, bool) port_mirror_add;
    void (*)(struct dsa_switch *, int, struct dsa_mall_mirror_tc_entry *) port_mirror_del;
    int (*)(struct dsa_switch *, int, enum tc_setup_type, void *) port_setup_tc;
    int (*)(struct dsa_switch *, int, int, struct net_device *) crosschip_bridge_join;
    void (*)(struct dsa_switch *, int, int, struct net_device *) crosschip_bridge_leave;
    int (*)(struct dsa_switch *, int, struct ifreq *) port_hwtstamp_get;
    int (*)(struct dsa_switch *, int, struct ifreq *) port_hwtstamp_set;
    bool (*)(struct dsa_switch *, int, struct sk_buff *, unsigned int) port_txtstamp;
    bool (*)(struct dsa_switch *, int, struct sk_buff *, unsigned int) port_rxtstamp;
    netdev_tx_t (*)(struct dsa_switch *, int, struct sk_buff *) port_deferred_xmit;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct dsa_switch_ops {
    enum dsa_tag_protocol (*)(struct dsa_switch *, int) get_tag_protocol;
    int (*)(struct dsa_switch *) setup;
    void (*)(struct dsa_switch *) teardown;
    u32 (*)(struct dsa_switch *, int) get_phy_flags;
    int (*)(struct dsa_switch *, int, int) phy_read;
    int (*)(struct dsa_switch *, int, int, u16) phy_write;
    void (*)(struct dsa_switch *, int, struct phy_device *) adjust_link;
    void (*)(struct dsa_switch *, int, struct fixed_phy_status *) fixed_link_update;
    void (*)(struct dsa_switch *, int, long unsigned int *, struct phylink_link_state *) phylink_validate;
    int (*)(struct dsa_switch *, int, struct phylink_link_state *) phylink_mac_link_state;
    void (*)(struct dsa_switch *, int, unsigned int, const struct phylink_link_state *) phylink_mac_config;
    void (*)(struct dsa_switch *, int) phylink_mac_an_restart;
    void (*)(struct dsa_switch *, int, unsigned int, phy_interface_t) phylink_mac_link_down;
    void (*)(struct dsa_switch *, int, unsigned int, phy_interface_t, struct phy_device *) phylink_mac_link_up;
    void (*)(struct dsa_switch *, int, struct phylink_link_state *) phylink_fixed_state;
    void (*)(struct dsa_switch *, int, u32, uint8_t *) get_strings;
    void (*)(struct dsa_switch *, int, uint64_t *) get_ethtool_stats;
    int (*)(struct dsa_switch *, int, int) get_sset_count;
    void (*)(struct dsa_switch *, int, uint64_t *) get_ethtool_phy_stats;
    void (*)(struct dsa_switch *, int, struct ethtool_wolinfo *) get_wol;
    int (*)(struct dsa_switch *, int, struct ethtool_wolinfo *) set_wol;
    int (*)(struct dsa_switch *, int, struct ethtool_ts_info *) get_ts_info;
    int (*)(struct dsa_switch *) suspend;
    int (*)(struct dsa_switch *) resume;
    int (*)(struct dsa_switch *, int, struct phy_device *) port_enable;
    void (*)(struct dsa_switch *, int) port_disable;
    int (*)(struct dsa_switch *, int, struct ethtool_eee *) set_mac_eee;
    int (*)(struct dsa_switch *, int, struct ethtool_eee *) get_mac_eee;
    int (*)(struct dsa_switch *) get_eeprom_len;
    int (*)(struct dsa_switch *, struct ethtool_eeprom *, u8 *) get_eeprom;
    int (*)(struct dsa_switch *, struct ethtool_eeprom *, u8 *) set_eeprom;
    int (*)(struct dsa_switch *, int) get_regs_len;
    void (*)(struct dsa_switch *, int, struct ethtool_regs *, void *) get_regs;
    int (*)(struct dsa_switch *, unsigned int) set_ageing_time;
    int (*)(struct dsa_switch *, int, struct net_device *) port_bridge_join;
    void (*)(struct dsa_switch *, int, struct net_device *) port_bridge_leave;
    void (*)(struct dsa_switch *, int, u8) port_stp_state_set;
    void (*)(struct dsa_switch *, int) port_fast_age;
    int (*)(struct dsa_switch *, int, bool, bool) port_egress_floods;
    int (*)(struct dsa_switch *, int, bool) port_vlan_filtering;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_vlan *) port_vlan_prepare;
    void (*)(struct dsa_switch *, int, const struct switchdev_obj_port_vlan *) port_vlan_add;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_vlan *) port_vlan_del;
    int (*)(struct dsa_switch *, int, const unsigned char *, u16) port_fdb_add;
    int (*)(struct dsa_switch *, int, const unsigned char *, u16) port_fdb_del;
    int (*)(struct dsa_switch *, int, dsa_fdb_dump_cb_t *, void *) port_fdb_dump;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_mdb *) port_mdb_prepare;
    void (*)(struct dsa_switch *, int, const struct switchdev_obj_port_mdb *) port_mdb_add;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_mdb *) port_mdb_del;
    int (*)(struct dsa_switch *, int, struct ethtool_rxnfc *, u32 *) get_rxnfc;
    int (*)(struct dsa_switch *, int, struct ethtool_rxnfc *) set_rxnfc;
    int (*)(struct dsa_switch *, int, struct dsa_mall_mirror_tc_entry *, bool) port_mirror_add;
    void (*)(struct dsa_switch *, int, struct dsa_mall_mirror_tc_entry *) port_mirror_del;
    int (*)(struct dsa_switch *, int, enum tc_setup_type, void *) port_setup_tc;
    int (*)(struct dsa_switch *, int, int, struct net_device *) crosschip_bridge_join;
    void (*)(struct dsa_switch *, int, int, struct net_device *) crosschip_bridge_leave;
    int (*)(struct dsa_switch *, int, struct ifreq *) port_hwtstamp_get;
    int (*)(struct dsa_switch *, int, struct ifreq *) port_hwtstamp_set;
    bool (*)(struct dsa_switch *, int, struct sk_buff *, unsigned int) port_txtstamp;
    bool (*)(struct dsa_switch *, int, struct sk_buff *, unsigned int) port_rxtstamp;
    netdev_tx_t (*)(struct dsa_switch *, int, struct sk_buff *) port_deferred_xmit;
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
struct dsa_switch_ops {
    struct list_head list;
    const char * (*)(struct device *, struct device *, int, void * *) probe;
    enum dsa_tag_protocol (*)(struct dsa_switch *) get_tag_protocol;
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
    void (*)(struct dsa_switch *, int) port_fast_age;
    int (*)(struct dsa_switch *, int, bool) port_vlan_filtering;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_vlan *, struct switchdev_trans *) port_vlan_prepare;
    void (*)(struct dsa_switch *, int, const struct switchdev_obj_port_vlan *, struct switchdev_trans *) port_vlan_add;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_vlan *) port_vlan_del;
    int (*)(struct dsa_switch *, int, struct switchdev_obj_port_vlan *, int (*)(struct switchdev_obj *)) port_vlan_dump;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_fdb *, struct switchdev_trans *) port_fdb_prepare;
    void (*)(struct dsa_switch *, int, const struct switchdev_obj_port_fdb *, struct switchdev_trans *) port_fdb_add;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_fdb *) port_fdb_del;
    int (*)(struct dsa_switch *, int, struct switchdev_obj_port_fdb *, int (*)(struct switchdev_obj *)) port_fdb_dump;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_mdb *, struct switchdev_trans *) port_mdb_prepare;
    void (*)(struct dsa_switch *, int, const struct switchdev_obj_port_mdb *, struct switchdev_trans *) port_mdb_add;
    int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_mdb *) port_mdb_del;
    int (*)(struct dsa_switch *, int, struct switchdev_obj_port_mdb *, int (*)(struct switchdev_obj *)) port_mdb_dump;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct dsa_switch *, int, struct ethtool_rxnfc *, u32 *) get_rxnfc</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct dsa_switch *, int, struct ethtool_rxnfc *) set_rxnfc</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct dsa_switch *, int, struct dsa_mall_mirror_tc_entry *, bool) port_mirror_add</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct dsa_switch *, int, struct dsa_mall_mirror_tc_entry *) port_mirror_del</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct dsa_switch *, int, int, struct net_device *) crosschip_bridge_join</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct dsa_switch *, int, int, struct net_device *) crosschip_bridge_leave</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head list</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct dsa_switch *, int *) get_temp</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct dsa_switch *, int *) get_temp_limit</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct dsa_switch *, int) set_temp_limit</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct dsa_switch *, bool *) get_temp_alarm</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct dsa_switch *, int) port_bridge_leave</code> ➡️ <code>void (*)(struct dsa_switch *, int, struct net_device *) port_bridge_leave</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct dsa_switch *, int, struct switchdev_obj_port_vlan *, int (*)(struct switchdev_obj *)) port_vlan_dump</code> ➡️ <code>int (*)(struct dsa_switch *, int, struct switchdev_obj_port_vlan *, switchdev_obj_dump_cb_t *) port_vlan_dump</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct dsa_switch *, int, struct switchdev_obj_port_fdb *, int (*)(struct switchdev_obj *)) port_fdb_dump</code> ➡️ <code>int (*)(struct dsa_switch *, int, struct switchdev_obj_port_fdb *, switchdev_obj_dump_cb_t *) port_fdb_dump</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct dsa_switch *, int, struct switchdev_obj_port_mdb *, int (*)(struct switchdev_obj *)) port_mdb_dump</code> ➡️ <code>int (*)(struct dsa_switch *, int, struct switchdev_obj_port_mdb *, switchdev_obj_dump_cb_t *) port_mdb_dump</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct dsa_switch *, int, struct ethtool_eee *) set_mac_eee</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct dsa_switch *, int, struct ethtool_eee *) get_mac_eee</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct dsa_switch *, u8 *) set_addr</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct dsa_switch *, int, struct phy_device *, struct ethtool_eee *) set_eee</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct dsa_switch *, int, struct ethtool_eee *) get_eee</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct dsa_switch *, int, struct switchdev_obj_port_vlan *, switchdev_obj_dump_cb_t *) port_vlan_dump</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_fdb *, struct switchdev_trans *) port_fdb_prepare</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct dsa_switch *, int, struct switchdev_obj_port_mdb *, switchdev_obj_dump_cb_t *) port_mdb_dump</code>
</li>
<li>
<b>Field type changed. </b>
<code>enum dsa_tag_protocol (*)(struct dsa_switch *) get_tag_protocol</code> ➡️ <code>enum dsa_tag_protocol (*)(struct dsa_switch *, int) get_tag_protocol</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct dsa_switch *, int, const struct switchdev_obj_port_fdb *, struct switchdev_trans *) port_fdb_add</code> ➡️ <code>int (*)(struct dsa_switch *, int, const unsigned char *, u16) port_fdb_add</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_fdb *) port_fdb_del</code> ➡️ <code>int (*)(struct dsa_switch *, int, const unsigned char *, u16) port_fdb_del</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct dsa_switch *, int, struct switchdev_obj_port_fdb *, switchdev_obj_dump_cb_t *) port_fdb_dump</code> ➡️ <code>int (*)(struct dsa_switch *, int, dsa_fdb_dump_cb_t *, void *) port_fdb_dump</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>void (*)(struct dsa_switch *, int, long unsigned int *, struct phylink_link_state *) phylink_validate</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct dsa_switch *, int, struct phylink_link_state *) phylink_mac_link_state</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct dsa_switch *, int, unsigned int, const struct phylink_link_state *) phylink_mac_config</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct dsa_switch *, int) phylink_mac_an_restart</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct dsa_switch *, int, unsigned int, phy_interface_t) phylink_mac_link_down</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct dsa_switch *, int, unsigned int, phy_interface_t, struct phy_device *) phylink_mac_link_up</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct dsa_switch *, int, struct phylink_link_state *) phylink_fixed_state</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct dsa_switch *, int, uint64_t *) get_ethtool_phy_stats</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct dsa_switch *, int, struct ethtool_ts_info *) get_ts_info</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct dsa_switch *, int, struct ifreq *) port_hwtstamp_get</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct dsa_switch *, int, struct ifreq *) port_hwtstamp_set</code>
</li>
<li>
<b>Field added. </b>
<code>bool (*)(struct dsa_switch *, int, struct sk_buff *, unsigned int) port_txtstamp</code>
</li>
<li>
<b>Field added. </b>
<code>bool (*)(struct dsa_switch *, int, struct sk_buff *, unsigned int) port_rxtstamp</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct dsa_switch *, int, uint8_t *) get_strings</code> ➡️ <code>void (*)(struct dsa_switch *, int, u32, uint8_t *) get_strings</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct dsa_switch *) get_sset_count</code> ➡️ <code>int (*)(struct dsa_switch *, int, int) get_sset_count</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_vlan *, struct switchdev_trans *) port_vlan_prepare</code> ➡️ <code>int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_vlan *) port_vlan_prepare</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct dsa_switch *, int, const struct switchdev_obj_port_vlan *, struct switchdev_trans *) port_vlan_add</code> ➡️ <code>void (*)(struct dsa_switch *, int, const struct switchdev_obj_port_vlan *) port_vlan_add</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_mdb *, struct switchdev_trans *) port_mdb_prepare</code> ➡️ <code>int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_mdb *) port_mdb_prepare</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct dsa_switch *, int, const struct switchdev_obj_port_mdb *, struct switchdev_trans *) port_mdb_add</code> ➡️ <code>void (*)(struct dsa_switch *, int, const struct switchdev_obj_port_mdb *) port_mdb_add</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>void (*)(struct dsa_switch *) teardown</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct dsa_switch *, int, bool, bool) port_egress_floods</code>
</li>
<li>
<b>Field added. </b>
<code>netdev_tx_t (*)(struct dsa_switch *, int, struct sk_buff *) port_deferred_xmit</code>
</li>
<li>
<b>Field removed. </b>
<code>const char * (*)(struct device *, struct device *, int, void * *) probe</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct dsa_switch *, int, long unsigned int *, struct phylink_link_state *) phylink_validate</code> ➡️ <code>void (*)(struct dsa_switch *, int, long unsigned int *, struct phylink_link_state *) phylink_validate</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct dsa_switch *, int, struct phylink_link_state *) phylink_mac_link_state</code> ➡️ <code>int (*)(struct dsa_switch *, int, struct phylink_link_state *) phylink_mac_link_state</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct dsa_switch *, int, unsigned int, const struct phylink_link_state *) phylink_mac_config</code> ➡️ <code>void (*)(struct dsa_switch *, int, unsigned int, const struct phylink_link_state *) phylink_mac_config</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct dsa_switch *, int, struct phylink_link_state *) phylink_fixed_state</code> ➡️ <code>void (*)(struct dsa_switch *, int, struct phylink_link_state *) phylink_fixed_state</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct dsa_switch *, int, struct phy_device *) port_disable</code> ➡️ <code>void (*)(struct dsa_switch *, int) port_disable</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct dsa_switch *, int, enum tc_setup_type, void *) port_setup_tc</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct dsa_switch *, int, struct flow_cls_offload *, bool) cls_flower_add</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct dsa_switch *, int, struct flow_cls_offload *, bool) cls_flower_del</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct dsa_switch *, int, struct flow_cls_offload *, bool) cls_flower_stats</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct dsa_switch *, int, struct dsa_mall_policer_tc_entry *) port_policer_add</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct dsa_switch *, int) port_policer_del</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct dsa_switch *, u32, struct devlink_param_gset_ctx *) devlink_param_get</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct dsa_switch *, u32, struct devlink_param_gset_ctx *) devlink_param_set</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct dsa_switch *, int, int) port_change_mtu</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct dsa_switch *, int) port_max_mtu</code>
</li>
<li>
<b>Field removed. </b>
<code>netdev_tx_t (*)(struct dsa_switch *, int, struct sk_buff *) port_deferred_xmit</code>
</li>
<li>
<b>Field type changed. </b>
<code>enum dsa_tag_protocol (*)(struct dsa_switch *, int) get_tag_protocol</code> ➡️ <code>enum dsa_tag_protocol (*)(struct dsa_switch *, int, enum dsa_tag_protocol) get_tag_protocol</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct dsa_switch *, int, unsigned int, phy_interface_t, struct phy_device *) phylink_mac_link_up</code> ➡️ <code>void (*)(struct dsa_switch *, int, unsigned int, phy_interface_t, struct phy_device *, int, int, bool, bool) phylink_mac_link_up</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct dsa_switch *, int, int, struct net_device *) crosschip_bridge_join</code> ➡️ <code>int (*)(struct dsa_switch *, int, int, int, struct net_device *) crosschip_bridge_join</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct dsa_switch *, int, int, struct net_device *) crosschip_bridge_leave</code> ➡️ <code>void (*)(struct dsa_switch *, int, int, int, struct net_device *) crosschip_bridge_leave</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct dsa_switch *, int, struct netdev_notifier_changeupper_info *) port_prechangeupper</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct dsa_switch *, struct devlink_info_req *, struct netlink_ext_ack *) devlink_info_get</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct dsa_switch *, int, bool) port_vlan_filtering</code> ➡️ <code>int (*)(struct dsa_switch *, int, bool, struct switchdev_trans *) port_vlan_filtering</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct dsa_switch *, int, enum dsa_tag_protocol) change_tag_protocol</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct dsa_switch *, int, struct rtnl_link_stats64 *) get_stats64</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct dsa_switch *, int, struct ethtool_test *, u64 *) self_test</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct dsa_switch *, int, struct switchdev_brport_flags, struct netlink_ext_ack *) port_pre_bridge_flags</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct dsa_switch *, int, struct switchdev_brport_flags, struct netlink_ext_ack *) port_bridge_flags</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct dsa_switch *, int, bool, struct netlink_ext_ack *) port_set_mrouter</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct dsa_switch *, int, int) crosschip_lag_change</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct dsa_switch *, int, int, struct net_device *, struct netdev_lag_upper_info *) crosschip_lag_join</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct dsa_switch *, int, int, struct net_device *) crosschip_lag_leave</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct dsa_switch *, unsigned int, u16, struct devlink_sb_pool_info *) devlink_sb_pool_get</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct dsa_switch *, unsigned int, u16, u32, enum devlink_sb_threshold_type, struct netlink_ext_ack *) devlink_sb_pool_set</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct dsa_switch *, int, unsigned int, u16, u32 *) devlink_sb_port_pool_get</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct dsa_switch *, int, unsigned int, u16, u32, struct netlink_ext_ack *) devlink_sb_port_pool_set</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct dsa_switch *, int, unsigned int, u16, enum devlink_sb_pool_type, u16 *, u32 *) devlink_sb_tc_pool_bind_get</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct dsa_switch *, int, unsigned int, u16, enum devlink_sb_pool_type, u16, u32, struct netlink_ext_ack *) devlink_sb_tc_pool_bind_set</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct dsa_switch *, unsigned int) devlink_sb_occ_snapshot</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct dsa_switch *, unsigned int) devlink_sb_occ_max_clear</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct dsa_switch *, int, unsigned int, u16, u32 *, u32 *) devlink_sb_occ_port_pool_get</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct dsa_switch *, int, unsigned int, u16, enum devlink_sb_pool_type, u32 *, u32 *) devlink_sb_occ_tc_port_bind_get</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct dsa_switch *, int) port_lag_change</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct dsa_switch *, int, struct net_device *, struct netdev_lag_upper_info *) port_lag_join</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct dsa_switch *, int, struct net_device *) port_lag_leave</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct dsa_switch *, int, struct net_device *) port_hsr_join</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct dsa_switch *, int, struct net_device *) port_hsr_leave</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct dsa_switch *, int, const struct switchdev_obj_mrp *) port_mrp_add</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct dsa_switch *, int, const struct switchdev_obj_mrp *) port_mrp_del</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct dsa_switch *, int, const struct switchdev_obj_ring_role_mrp *) port_mrp_add_ring_role</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct dsa_switch *, int, const struct switchdev_obj_ring_role_mrp *) port_mrp_del_ring_role</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct dsa_switch *, int, bool, bool) port_egress_floods</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_vlan *) port_vlan_prepare</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_mdb *) port_mdb_prepare</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct dsa_switch *, int, bool, struct switchdev_trans *) port_vlan_filtering</code> ➡️ <code>int (*)(struct dsa_switch *, int, bool, struct netlink_ext_ack *) port_vlan_filtering</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct dsa_switch *, int, const struct switchdev_obj_port_vlan *) port_vlan_add</code> ➡️ <code>int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_vlan *, struct netlink_ext_ack *) port_vlan_add</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct dsa_switch *, int, const struct switchdev_obj_port_mdb *) port_mdb_add</code> ➡️ <code>int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_mdb *) port_mdb_add</code>
</li>
<li>
<b>Field type changed. </b>
<code>bool (*)(struct dsa_switch *, int, struct sk_buff *, unsigned int) port_txtstamp</code> ➡️ <code>void (*)(struct dsa_switch *, int, struct sk_buff *) port_txtstamp</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct dsa_switch *, int) port_setup</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct dsa_switch *, int) port_teardown</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct dsa_switch *, int, struct net_device *, int) port_bridge_tx_fwd_offload</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct dsa_switch *, int, struct net_device *, int) port_bridge_tx_fwd_unoffload</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct dsa_switch *, int, u16, u16) tag_8021q_vlan_add</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct dsa_switch *, int, u16) tag_8021q_vlan_del</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct dsa_switch *, int, bool, struct netlink_ext_ack *) port_set_mrouter</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct dsa_switch *, enum dsa_tag_protocol) connect_tag_protocol</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct dsa_switch *, int, struct phylink_config *) phylink_get_caps</code>
</li>
<li>
<b>Field added. </b>
<code>struct phylink_pcs * (*)(struct dsa_switch *, int, phy_interface_t) phylink_mac_select_pcs</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct dsa_switch *, int, struct ethtool_eth_phy_stats *) get_eth_phy_stats</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct dsa_switch *, int, struct ethtool_eth_mac_stats *) get_eth_mac_stats</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct dsa_switch *, int, struct ethtool_eth_ctrl_stats *) get_eth_ctrl_stats</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct dsa_switch *, int) port_get_default_prio</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct dsa_switch *, int, u8) port_set_default_prio</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct dsa_switch *, int, u8) port_get_dscp_prio</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct dsa_switch *, int, u8, u8) port_add_dscp_prio</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct dsa_switch *, int, u8, u8) port_del_dscp_prio</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct dsa_switch *, int, const struct switchdev_mst_state *) port_mst_state_set</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct dsa_switch *, int, u16) port_vlan_fast_age</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct dsa_switch *, int, bool, bool) port_set_host_flood</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct dsa_switch *, struct dsa_bridge, const struct switchdev_vlan_msti *) vlan_msti_set</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct dsa_switch *, struct dsa_lag, const unsigned char *, u16, struct dsa_db) lag_fdb_add</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct dsa_switch *, struct dsa_lag, const unsigned char *, u16, struct dsa_db) lag_fdb_del</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct dsa_switch *, const struct net_device *, bool) master_state_change</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct dsa_switch *, int, struct net_device *, int) port_bridge_tx_fwd_offload</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct dsa_switch *, int, struct net_device *, int) port_bridge_tx_fwd_unoffload</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct dsa_switch *, int, enum dsa_tag_protocol) change_tag_protocol</code> ➡️ <code>int (*)(struct dsa_switch *, enum dsa_tag_protocol) change_tag_protocol</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct dsa_switch *, int, struct net_device *) port_bridge_join</code> ➡️ <code>int (*)(struct dsa_switch *, int, struct dsa_bridge, bool *, struct netlink_ext_ack *) port_bridge_join</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct dsa_switch *, int, struct net_device *) port_bridge_leave</code> ➡️ <code>void (*)(struct dsa_switch *, int, struct dsa_bridge) port_bridge_leave</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct dsa_switch *, int, const unsigned char *, u16) port_fdb_add</code> ➡️ <code>int (*)(struct dsa_switch *, int, const unsigned char *, u16, struct dsa_db) port_fdb_add</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct dsa_switch *, int, const unsigned char *, u16) port_fdb_del</code> ➡️ <code>int (*)(struct dsa_switch *, int, const unsigned char *, u16, struct dsa_db) port_fdb_del</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_mdb *) port_mdb_add</code> ➡️ <code>int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_mdb *, struct dsa_db) port_mdb_add</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_mdb *) port_mdb_del</code> ➡️ <code>int (*)(struct dsa_switch *, int, const struct switchdev_obj_port_mdb *, struct dsa_db) port_mdb_del</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct dsa_switch *, int, struct dsa_mall_mirror_tc_entry *, bool) port_mirror_add</code> ➡️ <code>int (*)(struct dsa_switch *, int, struct dsa_mall_mirror_tc_entry *, bool, struct netlink_ext_ack *) port_mirror_add</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct dsa_switch *, int, int, int, struct net_device *) crosschip_bridge_join</code> ➡️ <code>int (*)(struct dsa_switch *, int, int, int, struct dsa_bridge, struct netlink_ext_ack *) crosschip_bridge_join</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct dsa_switch *, int, int, int, struct net_device *) crosschip_bridge_leave</code> ➡️ <code>void (*)(struct dsa_switch *, int, int, int, struct dsa_bridge) crosschip_bridge_leave</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct dsa_switch *, int, int, struct net_device *, struct netdev_lag_upper_info *) crosschip_lag_join</code> ➡️ <code>int (*)(struct dsa_switch *, int, int, struct dsa_lag, struct netdev_lag_upper_info *) crosschip_lag_join</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct dsa_switch *, int, int, struct net_device *) crosschip_lag_leave</code> ➡️ <code>int (*)(struct dsa_switch *, int, int, struct dsa_lag) crosschip_lag_leave</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct dsa_switch *, int, struct net_device *, struct netdev_lag_upper_info *) port_lag_join</code> ➡️ <code>int (*)(struct dsa_switch *, int, struct dsa_lag, struct netdev_lag_upper_info *) port_lag_join</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct dsa_switch *, int, struct net_device *) port_lag_leave</code> ➡️ <code>int (*)(struct dsa_switch *, int, struct dsa_lag) port_lag_leave</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct dsa_switch *, int, struct net_device *, struct netlink_ext_ack *) port_change_master</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct dsa_switch *, int, struct ethtool_rmon_stats *, const struct ethtool_rmon_hist_range * *) get_rmon_stats</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct dsa_switch *, int, struct ethtool_pause_stats *) get_pause_stats</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct dsa_switch *, int, long unsigned int *, struct phylink_link_state *) phylink_validate</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct dsa_switch *, int, int, struct dsa_lag, struct netdev_lag_upper_info *) crosschip_lag_join</code> ➡️ <code>int (*)(struct dsa_switch *, int, int, struct dsa_lag, struct netdev_lag_upper_info *, struct netlink_ext_ack *) crosschip_lag_join</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct dsa_switch *, int, struct dsa_lag, struct netdev_lag_upper_info *) port_lag_join</code> ➡️ <code>int (*)(struct dsa_switch *, int, struct dsa_lag, struct netdev_lag_upper_info *, struct netlink_ext_ack *) port_lag_join</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct dsa_switch *, int, unsigned int, phy_interface_t) phylink_mac_prepare</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct dsa_switch *, int, unsigned int, phy_interface_t) phylink_mac_finish</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct dsa_switch *, int, struct ethtool_mm_state *) get_mm</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct dsa_switch *, int, struct ethtool_mm_cfg *, struct netlink_ext_ack *) set_mm</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct dsa_switch *, int, struct ethtool_mm_stats *) get_mm_stats</code>
</li>
<li>
<b>Field added. </b>
<code>struct dsa_port * (*)(struct dsa_switch *) preferred_default_local_cpu_port</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct dsa_switch *, int, struct net_device *, struct netlink_ext_ack *) port_change_conduit</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct dsa_switch *, int, const unsigned char *) port_set_mac_address</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct dsa_switch *, const struct net_device *, bool) conduit_state_change</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct dsa_switch *, int, struct net_device *, struct netlink_ext_ack *) port_change_master</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct dsa_switch *, int, struct phylink_link_state *) phylink_mac_link_state</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct dsa_switch *, int) phylink_mac_an_restart</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct dsa_switch *, const struct net_device *, bool) master_state_change</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct dsa_switch *, int, struct net_device *) port_hsr_join</code> ➡️ <code>int (*)(struct dsa_switch *, int, struct net_device *, struct netlink_ext_ack *) port_hsr_join</code>
</li>
</ul>
</details>
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
