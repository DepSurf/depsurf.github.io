# Struct: <code>phy_driver</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct phy_driver {
    u32 phy_id;
    char * name;
    unsigned int phy_id_mask;
    u32 features;
    u32 flags;
    const void * driver_data;
    int (*)(struct phy_device *) soft_reset;
    int (*)(struct phy_device *) config_init;
    int (*)(struct phy_device *) probe;
    int (*)(struct phy_device *) suspend;
    int (*)(struct phy_device *) resume;
    int (*)(struct phy_device *) config_aneg;
    int (*)(struct phy_device *) aneg_done;
    int (*)(struct phy_device *) read_status;
    int (*)(struct phy_device *) ack_interrupt;
    int (*)(struct phy_device *) config_intr;
    int (*)(struct phy_device *) did_interrupt;
    void (*)(struct phy_device *) remove;
    int (*)(struct phy_device *) match_phy_device;
    int (*)(struct phy_device *, struct ethtool_ts_info *) ts_info;
    int (*)(struct phy_device *, struct ifreq *) hwtstamp;
    bool (*)(struct phy_device *, struct sk_buff *, int) rxtstamp;
    void (*)(struct phy_device *, struct sk_buff *, int) txtstamp;
    int (*)(struct phy_device *, struct ethtool_wolinfo *) set_wol;
    void (*)(struct phy_device *, struct ethtool_wolinfo *) get_wol;
    void (*)(struct phy_device *) link_change_notify;
    int (*)(struct phy_device *, int, int, int) read_mmd_indirect;
    void (*)(struct phy_device *, int, int, int, u32) write_mmd_indirect;
    int (*)(struct phy_device *, struct ethtool_modinfo *) module_info;
    int (*)(struct phy_device *, struct ethtool_eeprom *, u8 *) module_eeprom;
    struct device_driver driver;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct phy_driver {
    struct mdio_driver_common mdiodrv;
    u32 phy_id;
    char * name;
    unsigned int phy_id_mask;
    u32 features;
    u32 flags;
    const void * driver_data;
    int (*)(struct phy_device *) soft_reset;
    int (*)(struct phy_device *) config_init;
    int (*)(struct phy_device *) probe;
    int (*)(struct phy_device *) suspend;
    int (*)(struct phy_device *) resume;
    int (*)(struct phy_device *) config_aneg;
    int (*)(struct phy_device *) aneg_done;
    int (*)(struct phy_device *) read_status;
    int (*)(struct phy_device *) ack_interrupt;
    int (*)(struct phy_device *) config_intr;
    int (*)(struct phy_device *) did_interrupt;
    void (*)(struct phy_device *) remove;
    int (*)(struct phy_device *) match_phy_device;
    int (*)(struct phy_device *, struct ethtool_ts_info *) ts_info;
    int (*)(struct phy_device *, struct ifreq *) hwtstamp;
    bool (*)(struct phy_device *, struct sk_buff *, int) rxtstamp;
    void (*)(struct phy_device *, struct sk_buff *, int) txtstamp;
    int (*)(struct phy_device *, struct ethtool_wolinfo *) set_wol;
    void (*)(struct phy_device *, struct ethtool_wolinfo *) get_wol;
    void (*)(struct phy_device *) link_change_notify;
    int (*)(struct phy_device *, int, int, int) read_mmd_indirect;
    void (*)(struct phy_device *, int, int, int, u32) write_mmd_indirect;
    int (*)(struct phy_device *, struct ethtool_modinfo *) module_info;
    int (*)(struct phy_device *, struct ethtool_eeprom *, u8 *) module_eeprom;
    int (*)(struct phy_device *) get_sset_count;
    void (*)(struct phy_device *, u8 *) get_strings;
    void (*)(struct phy_device *, struct ethtool_stats *, u64 *) get_stats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct phy_driver {
    struct mdio_driver_common mdiodrv;
    u32 phy_id;
    char * name;
    unsigned int phy_id_mask;
    u32 features;
    u32 flags;
    const void * driver_data;
    int (*)(struct phy_device *) soft_reset;
    int (*)(struct phy_device *) config_init;
    int (*)(struct phy_device *) probe;
    int (*)(struct phy_device *) suspend;
    int (*)(struct phy_device *) resume;
    int (*)(struct phy_device *) config_aneg;
    int (*)(struct phy_device *) aneg_done;
    int (*)(struct phy_device *) read_status;
    int (*)(struct phy_device *) ack_interrupt;
    int (*)(struct phy_device *) config_intr;
    int (*)(struct phy_device *) did_interrupt;
    void (*)(struct phy_device *) remove;
    int (*)(struct phy_device *) match_phy_device;
    int (*)(struct phy_device *, struct ethtool_ts_info *) ts_info;
    int (*)(struct phy_device *, struct ifreq *) hwtstamp;
    bool (*)(struct phy_device *, struct sk_buff *, int) rxtstamp;
    void (*)(struct phy_device *, struct sk_buff *, int) txtstamp;
    int (*)(struct phy_device *, struct ethtool_wolinfo *) set_wol;
    void (*)(struct phy_device *, struct ethtool_wolinfo *) get_wol;
    void (*)(struct phy_device *) link_change_notify;
    int (*)(struct phy_device *, int, int, int) read_mmd_indirect;
    void (*)(struct phy_device *, int, int, int, u32) write_mmd_indirect;
    int (*)(struct phy_device *, struct ethtool_modinfo *) module_info;
    int (*)(struct phy_device *, struct ethtool_eeprom *, u8 *) module_eeprom;
    int (*)(struct phy_device *) get_sset_count;
    void (*)(struct phy_device *, u8 *) get_strings;
    void (*)(struct phy_device *, struct ethtool_stats *, u64 *) get_stats;
    int (*)(struct phy_device *, struct ethtool_tunable *, void *) get_tunable;
    int (*)(struct phy_device *, struct ethtool_tunable *, const void *) set_tunable;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct phy_driver {
    struct mdio_driver_common mdiodrv;
    u32 phy_id;
    char * name;
    unsigned int phy_id_mask;
    u32 features;
    u32 flags;
    const void * driver_data;
    int (*)(struct phy_device *) soft_reset;
    int (*)(struct phy_device *) config_init;
    int (*)(struct phy_device *) probe;
    int (*)(struct phy_device *) suspend;
    int (*)(struct phy_device *) resume;
    int (*)(struct phy_device *) config_aneg;
    int (*)(struct phy_device *) aneg_done;
    int (*)(struct phy_device *) read_status;
    int (*)(struct phy_device *) ack_interrupt;
    int (*)(struct phy_device *) config_intr;
    int (*)(struct phy_device *) did_interrupt;
    void (*)(struct phy_device *) remove;
    int (*)(struct phy_device *) match_phy_device;
    int (*)(struct phy_device *, struct ethtool_ts_info *) ts_info;
    int (*)(struct phy_device *, struct ifreq *) hwtstamp;
    bool (*)(struct phy_device *, struct sk_buff *, int) rxtstamp;
    void (*)(struct phy_device *, struct sk_buff *, int) txtstamp;
    int (*)(struct phy_device *, struct ethtool_wolinfo *) set_wol;
    void (*)(struct phy_device *, struct ethtool_wolinfo *) get_wol;
    void (*)(struct phy_device *) link_change_notify;
    int (*)(struct phy_device *, int, u16) read_mmd;
    int (*)(struct phy_device *, int, u16, u16) write_mmd;
    int (*)(struct phy_device *, struct ethtool_modinfo *) module_info;
    int (*)(struct phy_device *, struct ethtool_eeprom *, u8 *) module_eeprom;
    int (*)(struct phy_device *) get_sset_count;
    void (*)(struct phy_device *, u8 *) get_strings;
    void (*)(struct phy_device *, struct ethtool_stats *, u64 *) get_stats;
    int (*)(struct phy_device *, struct ethtool_tunable *, void *) get_tunable;
    int (*)(struct phy_device *, struct ethtool_tunable *, const void *) set_tunable;
    int (*)(struct phy_device *, bool) set_loopback;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct phy_driver {
    struct mdio_driver_common mdiodrv;
    u32 phy_id;
    char * name;
    unsigned int phy_id_mask;
    u32 features;
    u32 flags;
    const void * driver_data;
    int (*)(struct phy_device *) soft_reset;
    int (*)(struct phy_device *) config_init;
    int (*)(struct phy_device *) probe;
    int (*)(struct phy_device *) suspend;
    int (*)(struct phy_device *) resume;
    int (*)(struct phy_device *) config_aneg;
    int (*)(struct phy_device *) aneg_done;
    int (*)(struct phy_device *) read_status;
    int (*)(struct phy_device *) ack_interrupt;
    int (*)(struct phy_device *) config_intr;
    int (*)(struct phy_device *) did_interrupt;
    void (*)(struct phy_device *) remove;
    int (*)(struct phy_device *) match_phy_device;
    int (*)(struct phy_device *, struct ethtool_ts_info *) ts_info;
    int (*)(struct phy_device *, struct ifreq *) hwtstamp;
    bool (*)(struct phy_device *, struct sk_buff *, int) rxtstamp;
    void (*)(struct phy_device *, struct sk_buff *, int) txtstamp;
    int (*)(struct phy_device *, struct ethtool_wolinfo *) set_wol;
    void (*)(struct phy_device *, struct ethtool_wolinfo *) get_wol;
    void (*)(struct phy_device *) link_change_notify;
    int (*)(struct phy_device *, int, u16) read_mmd;
    int (*)(struct phy_device *, int, u16, u16) write_mmd;
    int (*)(struct phy_device *, struct ethtool_modinfo *) module_info;
    int (*)(struct phy_device *, struct ethtool_eeprom *, u8 *) module_eeprom;
    int (*)(struct phy_device *) get_sset_count;
    void (*)(struct phy_device *, u8 *) get_strings;
    void (*)(struct phy_device *, struct ethtool_stats *, u64 *) get_stats;
    int (*)(struct phy_device *, struct ethtool_tunable *, void *) get_tunable;
    int (*)(struct phy_device *, struct ethtool_tunable *, const void *) set_tunable;
    int (*)(struct phy_device *, bool) set_loopback;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct phy_driver {
    struct mdio_driver_common mdiodrv;
    u32 phy_id;
    char * name;
    u32 phy_id_mask;
    u32 features;
    u32 flags;
    const void * driver_data;
    int (*)(struct phy_device *) soft_reset;
    int (*)(struct phy_device *) config_init;
    int (*)(struct phy_device *) probe;
    int (*)(struct phy_device *) suspend;
    int (*)(struct phy_device *) resume;
    int (*)(struct phy_device *) config_aneg;
    int (*)(struct phy_device *) aneg_done;
    int (*)(struct phy_device *) read_status;
    int (*)(struct phy_device *) ack_interrupt;
    int (*)(struct phy_device *) config_intr;
    int (*)(struct phy_device *) did_interrupt;
    void (*)(struct phy_device *) remove;
    int (*)(struct phy_device *) match_phy_device;
    int (*)(struct phy_device *, struct ethtool_ts_info *) ts_info;
    int (*)(struct phy_device *, struct ifreq *) hwtstamp;
    bool (*)(struct phy_device *, struct sk_buff *, int) rxtstamp;
    void (*)(struct phy_device *, struct sk_buff *, int) txtstamp;
    int (*)(struct phy_device *, struct ethtool_wolinfo *) set_wol;
    void (*)(struct phy_device *, struct ethtool_wolinfo *) get_wol;
    void (*)(struct phy_device *) link_change_notify;
    int (*)(struct phy_device *, int, u16) read_mmd;
    int (*)(struct phy_device *, int, u16, u16) write_mmd;
    int (*)(struct phy_device *) read_page;
    int (*)(struct phy_device *, int) write_page;
    int (*)(struct phy_device *, struct ethtool_modinfo *) module_info;
    int (*)(struct phy_device *, struct ethtool_eeprom *, u8 *) module_eeprom;
    int (*)(struct phy_device *) get_sset_count;
    void (*)(struct phy_device *, u8 *) get_strings;
    void (*)(struct phy_device *, struct ethtool_stats *, u64 *) get_stats;
    int (*)(struct phy_device *, struct ethtool_tunable *, void *) get_tunable;
    int (*)(struct phy_device *, struct ethtool_tunable *, const void *) set_tunable;
    int (*)(struct phy_device *, bool) set_loopback;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct phy_driver {
    struct mdio_driver_common mdiodrv;
    u32 phy_id;
    char * name;
    u32 phy_id_mask;
    const const long unsigned int * features;
    u32 flags;
    const void * driver_data;
    int (*)(struct phy_device *) soft_reset;
    int (*)(struct phy_device *) config_init;
    int (*)(struct phy_device *) probe;
    int (*)(struct phy_device *) suspend;
    int (*)(struct phy_device *) resume;
    int (*)(struct phy_device *) config_aneg;
    int (*)(struct phy_device *) aneg_done;
    int (*)(struct phy_device *) read_status;
    int (*)(struct phy_device *) ack_interrupt;
    int (*)(struct phy_device *) config_intr;
    int (*)(struct phy_device *) did_interrupt;
    void (*)(struct phy_device *) remove;
    int (*)(struct phy_device *) match_phy_device;
    int (*)(struct phy_device *, struct ethtool_ts_info *) ts_info;
    int (*)(struct phy_device *, struct ifreq *) hwtstamp;
    bool (*)(struct phy_device *, struct sk_buff *, int) rxtstamp;
    void (*)(struct phy_device *, struct sk_buff *, int) txtstamp;
    int (*)(struct phy_device *, struct ethtool_wolinfo *) set_wol;
    void (*)(struct phy_device *, struct ethtool_wolinfo *) get_wol;
    void (*)(struct phy_device *) link_change_notify;
    int (*)(struct phy_device *, int, u16) read_mmd;
    int (*)(struct phy_device *, int, u16, u16) write_mmd;
    int (*)(struct phy_device *) read_page;
    int (*)(struct phy_device *, int) write_page;
    int (*)(struct phy_device *, struct ethtool_modinfo *) module_info;
    int (*)(struct phy_device *, struct ethtool_eeprom *, u8 *) module_eeprom;
    int (*)(struct phy_device *) get_sset_count;
    void (*)(struct phy_device *, u8 *) get_strings;
    void (*)(struct phy_device *, struct ethtool_stats *, u64 *) get_stats;
    int (*)(struct phy_device *, struct ethtool_tunable *, void *) get_tunable;
    int (*)(struct phy_device *, struct ethtool_tunable *, const void *) set_tunable;
    int (*)(struct phy_device *, bool) set_loopback;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct phy_driver {
    struct mdio_driver_common mdiodrv;
    u32 phy_id;
    char * name;
    u32 phy_id_mask;
    const const long unsigned int * features;
    u32 flags;
    const void * driver_data;
    int (*)(struct phy_device *) soft_reset;
    int (*)(struct phy_device *) config_init;
    int (*)(struct phy_device *) probe;
    int (*)(struct phy_device *) get_features;
    int (*)(struct phy_device *) suspend;
    int (*)(struct phy_device *) resume;
    int (*)(struct phy_device *) config_aneg;
    int (*)(struct phy_device *) aneg_done;
    int (*)(struct phy_device *) read_status;
    int (*)(struct phy_device *) ack_interrupt;
    int (*)(struct phy_device *) config_intr;
    int (*)(struct phy_device *) did_interrupt;
    int (*)(struct phy_device *) handle_interrupt;
    void (*)(struct phy_device *) remove;
    int (*)(struct phy_device *) match_phy_device;
    int (*)(struct phy_device *, struct ethtool_ts_info *) ts_info;
    int (*)(struct phy_device *, struct ifreq *) hwtstamp;
    bool (*)(struct phy_device *, struct sk_buff *, int) rxtstamp;
    void (*)(struct phy_device *, struct sk_buff *, int) txtstamp;
    int (*)(struct phy_device *, struct ethtool_wolinfo *) set_wol;
    void (*)(struct phy_device *, struct ethtool_wolinfo *) get_wol;
    void (*)(struct phy_device *) link_change_notify;
    int (*)(struct phy_device *, int, u16) read_mmd;
    int (*)(struct phy_device *, int, u16, u16) write_mmd;
    int (*)(struct phy_device *) read_page;
    int (*)(struct phy_device *, int) write_page;
    int (*)(struct phy_device *, struct ethtool_modinfo *) module_info;
    int (*)(struct phy_device *, struct ethtool_eeprom *, u8 *) module_eeprom;
    int (*)(struct phy_device *) get_sset_count;
    void (*)(struct phy_device *, u8 *) get_strings;
    void (*)(struct phy_device *, struct ethtool_stats *, u64 *) get_stats;
    int (*)(struct phy_device *, struct ethtool_tunable *, void *) get_tunable;
    int (*)(struct phy_device *, struct ethtool_tunable *, const void *) set_tunable;
    int (*)(struct phy_device *, bool) set_loopback;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct phy_driver {
    struct mdio_driver_common mdiodrv;
    u32 phy_id;
    char * name;
    u32 phy_id_mask;
    const const long unsigned int * features;
    u32 flags;
    const void * driver_data;
    int (*)(struct phy_device *) soft_reset;
    int (*)(struct phy_device *) config_init;
    int (*)(struct phy_device *) probe;
    int (*)(struct phy_device *) get_features;
    int (*)(struct phy_device *) suspend;
    int (*)(struct phy_device *) resume;
    int (*)(struct phy_device *) config_aneg;
    int (*)(struct phy_device *) aneg_done;
    int (*)(struct phy_device *) read_status;
    int (*)(struct phy_device *) ack_interrupt;
    int (*)(struct phy_device *) config_intr;
    int (*)(struct phy_device *) did_interrupt;
    int (*)(struct phy_device *) handle_interrupt;
    void (*)(struct phy_device *) remove;
    int (*)(struct phy_device *) match_phy_device;
    int (*)(struct phy_device *, struct ethtool_ts_info *) ts_info;
    int (*)(struct phy_device *, struct ifreq *) hwtstamp;
    bool (*)(struct phy_device *, struct sk_buff *, int) rxtstamp;
    void (*)(struct phy_device *, struct sk_buff *, int) txtstamp;
    int (*)(struct phy_device *, struct ethtool_wolinfo *) set_wol;
    void (*)(struct phy_device *, struct ethtool_wolinfo *) get_wol;
    void (*)(struct phy_device *) link_change_notify;
    int (*)(struct phy_device *, int, u16) read_mmd;
    int (*)(struct phy_device *, int, u16, u16) write_mmd;
    int (*)(struct phy_device *) read_page;
    int (*)(struct phy_device *, int) write_page;
    int (*)(struct phy_device *, struct ethtool_modinfo *) module_info;
    int (*)(struct phy_device *, struct ethtool_eeprom *, u8 *) module_eeprom;
    int (*)(struct phy_device *) get_sset_count;
    void (*)(struct phy_device *, u8 *) get_strings;
    void (*)(struct phy_device *, struct ethtool_stats *, u64 *) get_stats;
    int (*)(struct phy_device *, struct ethtool_tunable *, void *) get_tunable;
    int (*)(struct phy_device *, struct ethtool_tunable *, const void *) set_tunable;
    int (*)(struct phy_device *, bool) set_loopback;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct phy_driver {
    struct mdio_driver_common mdiodrv;
    u32 phy_id;
    char * name;
    u32 phy_id_mask;
    const const long unsigned int * features;
    u32 flags;
    const void * driver_data;
    int (*)(struct phy_device *) soft_reset;
    int (*)(struct phy_device *) config_init;
    int (*)(struct phy_device *) probe;
    int (*)(struct phy_device *) get_features;
    int (*)(struct phy_device *) suspend;
    int (*)(struct phy_device *) resume;
    int (*)(struct phy_device *) config_aneg;
    int (*)(struct phy_device *) aneg_done;
    int (*)(struct phy_device *) read_status;
    int (*)(struct phy_device *) ack_interrupt;
    int (*)(struct phy_device *) config_intr;
    int (*)(struct phy_device *) did_interrupt;
    irqreturn_t (*)(struct phy_device *) handle_interrupt;
    void (*)(struct phy_device *) remove;
    int (*)(struct phy_device *) match_phy_device;
    int (*)(struct phy_device *, struct ethtool_wolinfo *) set_wol;
    void (*)(struct phy_device *, struct ethtool_wolinfo *) get_wol;
    void (*)(struct phy_device *) link_change_notify;
    int (*)(struct phy_device *, int, u16) read_mmd;
    int (*)(struct phy_device *, int, u16, u16) write_mmd;
    int (*)(struct phy_device *) read_page;
    int (*)(struct phy_device *, int) write_page;
    int (*)(struct phy_device *, struct ethtool_modinfo *) module_info;
    int (*)(struct phy_device *, struct ethtool_eeprom *, u8 *) module_eeprom;
    int (*)(struct phy_device *) cable_test_start;
    int (*)(struct phy_device *, const struct phy_tdr_config *) cable_test_tdr_start;
    int (*)(struct phy_device *, bool *) cable_test_get_status;
    int (*)(struct phy_device *) get_sset_count;
    void (*)(struct phy_device *, u8 *) get_strings;
    void (*)(struct phy_device *, struct ethtool_stats *, u64 *) get_stats;
    int (*)(struct phy_device *, struct ethtool_tunable *, void *) get_tunable;
    int (*)(struct phy_device *, struct ethtool_tunable *, const void *) set_tunable;
    int (*)(struct phy_device *, bool) set_loopback;
    int (*)(struct phy_device *) get_sqi;
    int (*)(struct phy_device *) get_sqi_max;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct phy_driver {
    struct mdio_driver_common mdiodrv;
    u32 phy_id;
    char * name;
    u32 phy_id_mask;
    const const long unsigned int * features;
    u32 flags;
    const void * driver_data;
    int (*)(struct phy_device *) soft_reset;
    int (*)(struct phy_device *) config_init;
    int (*)(struct phy_device *) probe;
    int (*)(struct phy_device *) get_features;
    int (*)(struct phy_device *) suspend;
    int (*)(struct phy_device *) resume;
    int (*)(struct phy_device *) config_aneg;
    int (*)(struct phy_device *) aneg_done;
    int (*)(struct phy_device *) read_status;
    int (*)(struct phy_device *) config_intr;
    irqreturn_t (*)(struct phy_device *) handle_interrupt;
    void (*)(struct phy_device *) remove;
    int (*)(struct phy_device *) match_phy_device;
    int (*)(struct phy_device *, struct ethtool_wolinfo *) set_wol;
    void (*)(struct phy_device *, struct ethtool_wolinfo *) get_wol;
    void (*)(struct phy_device *) link_change_notify;
    int (*)(struct phy_device *, int, u16) read_mmd;
    int (*)(struct phy_device *, int, u16, u16) write_mmd;
    int (*)(struct phy_device *) read_page;
    int (*)(struct phy_device *, int) write_page;
    int (*)(struct phy_device *, struct ethtool_modinfo *) module_info;
    int (*)(struct phy_device *, struct ethtool_eeprom *, u8 *) module_eeprom;
    int (*)(struct phy_device *) cable_test_start;
    int (*)(struct phy_device *, const struct phy_tdr_config *) cable_test_tdr_start;
    int (*)(struct phy_device *, bool *) cable_test_get_status;
    int (*)(struct phy_device *) get_sset_count;
    void (*)(struct phy_device *, u8 *) get_strings;
    void (*)(struct phy_device *, struct ethtool_stats *, u64 *) get_stats;
    int (*)(struct phy_device *, struct ethtool_tunable *, void *) get_tunable;
    int (*)(struct phy_device *, struct ethtool_tunable *, const void *) set_tunable;
    int (*)(struct phy_device *, bool) set_loopback;
    int (*)(struct phy_device *) get_sqi;
    int (*)(struct phy_device *) get_sqi_max;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct phy_driver {
    struct mdio_driver_common mdiodrv;
    u32 phy_id;
    char * name;
    u32 phy_id_mask;
    const const long unsigned int * features;
    u32 flags;
    const void * driver_data;
    int (*)(struct phy_device *) soft_reset;
    int (*)(struct phy_device *) config_init;
    int (*)(struct phy_device *) probe;
    int (*)(struct phy_device *) get_features;
    int (*)(struct phy_device *) suspend;
    int (*)(struct phy_device *) resume;
    int (*)(struct phy_device *) config_aneg;
    int (*)(struct phy_device *) aneg_done;
    int (*)(struct phy_device *) read_status;
    int (*)(struct phy_device *) config_intr;
    irqreturn_t (*)(struct phy_device *) handle_interrupt;
    void (*)(struct phy_device *) remove;
    int (*)(struct phy_device *) match_phy_device;
    int (*)(struct phy_device *, struct ethtool_wolinfo *) set_wol;
    void (*)(struct phy_device *, struct ethtool_wolinfo *) get_wol;
    void (*)(struct phy_device *) link_change_notify;
    int (*)(struct phy_device *, int, u16) read_mmd;
    int (*)(struct phy_device *, int, u16, u16) write_mmd;
    int (*)(struct phy_device *) read_page;
    int (*)(struct phy_device *, int) write_page;
    int (*)(struct phy_device *, struct ethtool_modinfo *) module_info;
    int (*)(struct phy_device *, struct ethtool_eeprom *, u8 *) module_eeprom;
    int (*)(struct phy_device *) cable_test_start;
    int (*)(struct phy_device *, const struct phy_tdr_config *) cable_test_tdr_start;
    int (*)(struct phy_device *, bool *) cable_test_get_status;
    int (*)(struct phy_device *) get_sset_count;
    void (*)(struct phy_device *, u8 *) get_strings;
    void (*)(struct phy_device *, struct ethtool_stats *, u64 *) get_stats;
    int (*)(struct phy_device *, struct ethtool_tunable *, void *) get_tunable;
    int (*)(struct phy_device *, struct ethtool_tunable *, const void *) set_tunable;
    int (*)(struct phy_device *, bool) set_loopback;
    int (*)(struct phy_device *) get_sqi;
    int (*)(struct phy_device *) get_sqi_max;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct phy_driver {
    struct mdio_driver_common mdiodrv;
    u32 phy_id;
    char * name;
    u32 phy_id_mask;
    const const long unsigned int * features;
    u32 flags;
    const void * driver_data;
    int (*)(struct phy_device *) soft_reset;
    int (*)(struct phy_device *) config_init;
    int (*)(struct phy_device *) probe;
    int (*)(struct phy_device *) get_features;
    int (*)(struct phy_device *) suspend;
    int (*)(struct phy_device *) resume;
    int (*)(struct phy_device *) config_aneg;
    int (*)(struct phy_device *) aneg_done;
    int (*)(struct phy_device *) read_status;
    int (*)(struct phy_device *) config_intr;
    irqreturn_t (*)(struct phy_device *) handle_interrupt;
    void (*)(struct phy_device *) remove;
    int (*)(struct phy_device *) match_phy_device;
    int (*)(struct phy_device *, struct ethtool_wolinfo *) set_wol;
    void (*)(struct phy_device *, struct ethtool_wolinfo *) get_wol;
    void (*)(struct phy_device *) link_change_notify;
    int (*)(struct phy_device *, int, u16) read_mmd;
    int (*)(struct phy_device *, int, u16, u16) write_mmd;
    int (*)(struct phy_device *) read_page;
    int (*)(struct phy_device *, int) write_page;
    int (*)(struct phy_device *, struct ethtool_modinfo *) module_info;
    int (*)(struct phy_device *, struct ethtool_eeprom *, u8 *) module_eeprom;
    int (*)(struct phy_device *) cable_test_start;
    int (*)(struct phy_device *, const struct phy_tdr_config *) cable_test_tdr_start;
    int (*)(struct phy_device *, bool *) cable_test_get_status;
    int (*)(struct phy_device *) get_sset_count;
    void (*)(struct phy_device *, u8 *) get_strings;
    void (*)(struct phy_device *, struct ethtool_stats *, u64 *) get_stats;
    int (*)(struct phy_device *, struct ethtool_tunable *, void *) get_tunable;
    int (*)(struct phy_device *, struct ethtool_tunable *, const void *) set_tunable;
    int (*)(struct phy_device *, bool) set_loopback;
    int (*)(struct phy_device *) get_sqi;
    int (*)(struct phy_device *) get_sqi_max;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct phy_driver {
    struct mdio_driver_common mdiodrv;
    u32 phy_id;
    char * name;
    u32 phy_id_mask;
    const const long unsigned int * features;
    u32 flags;
    const void * driver_data;
    int (*)(struct phy_device *) soft_reset;
    int (*)(struct phy_device *) config_init;
    int (*)(struct phy_device *) probe;
    int (*)(struct phy_device *) get_features;
    int (*)(struct phy_device *) suspend;
    int (*)(struct phy_device *) resume;
    int (*)(struct phy_device *) config_aneg;
    int (*)(struct phy_device *) aneg_done;
    int (*)(struct phy_device *) read_status;
    int (*)(struct phy_device *) config_intr;
    irqreturn_t (*)(struct phy_device *) handle_interrupt;
    void (*)(struct phy_device *) remove;
    int (*)(struct phy_device *) match_phy_device;
    int (*)(struct phy_device *, struct ethtool_wolinfo *) set_wol;
    void (*)(struct phy_device *, struct ethtool_wolinfo *) get_wol;
    void (*)(struct phy_device *) link_change_notify;
    int (*)(struct phy_device *, int, u16) read_mmd;
    int (*)(struct phy_device *, int, u16, u16) write_mmd;
    int (*)(struct phy_device *) read_page;
    int (*)(struct phy_device *, int) write_page;
    int (*)(struct phy_device *, struct ethtool_modinfo *) module_info;
    int (*)(struct phy_device *, struct ethtool_eeprom *, u8 *) module_eeprom;
    int (*)(struct phy_device *) cable_test_start;
    int (*)(struct phy_device *, const struct phy_tdr_config *) cable_test_tdr_start;
    int (*)(struct phy_device *, bool *) cable_test_get_status;
    int (*)(struct phy_device *) get_sset_count;
    void (*)(struct phy_device *, u8 *) get_strings;
    void (*)(struct phy_device *, struct ethtool_stats *, u64 *) get_stats;
    int (*)(struct phy_device *, struct ethtool_tunable *, void *) get_tunable;
    int (*)(struct phy_device *, struct ethtool_tunable *, const void *) set_tunable;
    int (*)(struct phy_device *, bool) set_loopback;
    int (*)(struct phy_device *) get_sqi;
    int (*)(struct phy_device *) get_sqi_max;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct phy_driver {
    struct mdio_driver_common mdiodrv;
    u32 phy_id;
    char * name;
    u32 phy_id_mask;
    const const long unsigned int * features;
    u32 flags;
    const void * driver_data;
    int (*)(struct phy_device *) soft_reset;
    int (*)(struct phy_device *) config_init;
    int (*)(struct phy_device *) probe;
    int (*)(struct phy_device *) get_features;
    int (*)(struct phy_device *, phy_interface_t) get_rate_matching;
    int (*)(struct phy_device *) suspend;
    int (*)(struct phy_device *) resume;
    int (*)(struct phy_device *) config_aneg;
    int (*)(struct phy_device *) aneg_done;
    int (*)(struct phy_device *) read_status;
    int (*)(struct phy_device *) config_intr;
    irqreturn_t (*)(struct phy_device *) handle_interrupt;
    void (*)(struct phy_device *) remove;
    int (*)(struct phy_device *) match_phy_device;
    int (*)(struct phy_device *, struct ethtool_wolinfo *) set_wol;
    void (*)(struct phy_device *, struct ethtool_wolinfo *) get_wol;
    void (*)(struct phy_device *) link_change_notify;
    int (*)(struct phy_device *, int, u16) read_mmd;
    int (*)(struct phy_device *, int, u16, u16) write_mmd;
    int (*)(struct phy_device *) read_page;
    int (*)(struct phy_device *, int) write_page;
    int (*)(struct phy_device *, struct ethtool_modinfo *) module_info;
    int (*)(struct phy_device *, struct ethtool_eeprom *, u8 *) module_eeprom;
    int (*)(struct phy_device *) cable_test_start;
    int (*)(struct phy_device *, const struct phy_tdr_config *) cable_test_tdr_start;
    int (*)(struct phy_device *, bool *) cable_test_get_status;
    int (*)(struct phy_device *) get_sset_count;
    void (*)(struct phy_device *, u8 *) get_strings;
    void (*)(struct phy_device *, struct ethtool_stats *, u64 *) get_stats;
    int (*)(struct phy_device *, struct ethtool_tunable *, void *) get_tunable;
    int (*)(struct phy_device *, struct ethtool_tunable *, const void *) set_tunable;
    int (*)(struct phy_device *, bool) set_loopback;
    int (*)(struct phy_device *) get_sqi;
    int (*)(struct phy_device *) get_sqi_max;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct phy_driver {
    struct mdio_driver_common mdiodrv;
    u32 phy_id;
    char * name;
    u32 phy_id_mask;
    const const long unsigned int * features;
    u32 flags;
    const void * driver_data;
    int (*)(struct phy_device *) soft_reset;
    int (*)(struct phy_device *) config_init;
    int (*)(struct phy_device *) probe;
    int (*)(struct phy_device *) get_features;
    int (*)(struct phy_device *, phy_interface_t) get_rate_matching;
    int (*)(struct phy_device *) suspend;
    int (*)(struct phy_device *) resume;
    int (*)(struct phy_device *) config_aneg;
    int (*)(struct phy_device *) aneg_done;
    int (*)(struct phy_device *) read_status;
    int (*)(struct phy_device *) config_intr;
    irqreturn_t (*)(struct phy_device *) handle_interrupt;
    void (*)(struct phy_device *) remove;
    int (*)(struct phy_device *) match_phy_device;
    int (*)(struct phy_device *, struct ethtool_wolinfo *) set_wol;
    void (*)(struct phy_device *, struct ethtool_wolinfo *) get_wol;
    void (*)(struct phy_device *) link_change_notify;
    int (*)(struct phy_device *, int, u16) read_mmd;
    int (*)(struct phy_device *, int, u16, u16) write_mmd;
    int (*)(struct phy_device *) read_page;
    int (*)(struct phy_device *, int) write_page;
    int (*)(struct phy_device *, struct ethtool_modinfo *) module_info;
    int (*)(struct phy_device *, struct ethtool_eeprom *, u8 *) module_eeprom;
    int (*)(struct phy_device *) cable_test_start;
    int (*)(struct phy_device *, const struct phy_tdr_config *) cable_test_tdr_start;
    int (*)(struct phy_device *, bool *) cable_test_get_status;
    int (*)(struct phy_device *) get_sset_count;
    void (*)(struct phy_device *, u8 *) get_strings;
    void (*)(struct phy_device *, struct ethtool_stats *, u64 *) get_stats;
    int (*)(struct phy_device *, struct ethtool_tunable *, void *) get_tunable;
    int (*)(struct phy_device *, struct ethtool_tunable *, const void *) set_tunable;
    int (*)(struct phy_device *, bool) set_loopback;
    int (*)(struct phy_device *) get_sqi;
    int (*)(struct phy_device *) get_sqi_max;
    int (*)(struct phy_device *, struct phy_plca_cfg *) get_plca_cfg;
    int (*)(struct phy_device *, const struct phy_plca_cfg *) set_plca_cfg;
    int (*)(struct phy_device *, struct phy_plca_status *) get_plca_status;
    int (*)(struct phy_device *, u8, enum led_brightness) led_brightness_set;
    int (*)(struct phy_device *, u8, long unsigned int *, long unsigned int *) led_blink_set;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct phy_driver {
    struct mdio_driver_common mdiodrv;
    u32 phy_id;
    char * name;
    u32 phy_id_mask;
    const const long unsigned int * features;
    u32 flags;
    const void * driver_data;
    int (*)(struct phy_device *) soft_reset;
    int (*)(struct phy_device *) config_init;
    int (*)(struct phy_device *) probe;
    int (*)(struct phy_device *) get_features;
    int (*)(struct phy_device *, phy_interface_t) get_rate_matching;
    int (*)(struct phy_device *) suspend;
    int (*)(struct phy_device *) resume;
    int (*)(struct phy_device *) config_aneg;
    int (*)(struct phy_device *) aneg_done;
    int (*)(struct phy_device *) read_status;
    int (*)(struct phy_device *) config_intr;
    irqreturn_t (*)(struct phy_device *) handle_interrupt;
    void (*)(struct phy_device *) remove;
    int (*)(struct phy_device *) match_phy_device;
    int (*)(struct phy_device *, struct ethtool_wolinfo *) set_wol;
    void (*)(struct phy_device *, struct ethtool_wolinfo *) get_wol;
    void (*)(struct phy_device *) link_change_notify;
    int (*)(struct phy_device *, int, u16) read_mmd;
    int (*)(struct phy_device *, int, u16, u16) write_mmd;
    int (*)(struct phy_device *) read_page;
    int (*)(struct phy_device *, int) write_page;
    int (*)(struct phy_device *, struct ethtool_modinfo *) module_info;
    int (*)(struct phy_device *, struct ethtool_eeprom *, u8 *) module_eeprom;
    int (*)(struct phy_device *) cable_test_start;
    int (*)(struct phy_device *, const struct phy_tdr_config *) cable_test_tdr_start;
    int (*)(struct phy_device *, bool *) cable_test_get_status;
    int (*)(struct phy_device *) get_sset_count;
    void (*)(struct phy_device *, u8 *) get_strings;
    void (*)(struct phy_device *, struct ethtool_stats *, u64 *) get_stats;
    int (*)(struct phy_device *, struct ethtool_tunable *, void *) get_tunable;
    int (*)(struct phy_device *, struct ethtool_tunable *, const void *) set_tunable;
    int (*)(struct phy_device *, bool) set_loopback;
    int (*)(struct phy_device *) get_sqi;
    int (*)(struct phy_device *) get_sqi_max;
    int (*)(struct phy_device *, struct phy_plca_cfg *) get_plca_cfg;
    int (*)(struct phy_device *, const struct phy_plca_cfg *) set_plca_cfg;
    int (*)(struct phy_device *, struct phy_plca_status *) get_plca_status;
    int (*)(struct phy_device *, u8, enum led_brightness) led_brightness_set;
    int (*)(struct phy_device *, u8, long unsigned int *, long unsigned int *) led_blink_set;
    int (*)(struct phy_device *, u8, long unsigned int) led_hw_is_supported;
    int (*)(struct phy_device *, u8, long unsigned int) led_hw_control_set;
    int (*)(struct phy_device *, u8, long unsigned int *) led_hw_control_get;
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
struct phy_driver {
    struct mdio_driver_common mdiodrv;
    u32 phy_id;
    char * name;
    u32 phy_id_mask;
    const const long unsigned int * features;
    u32 flags;
    const void * driver_data;
    int (*)(struct phy_device *) soft_reset;
    int (*)(struct phy_device *) config_init;
    int (*)(struct phy_device *) probe;
    int (*)(struct phy_device *) get_features;
    int (*)(struct phy_device *) suspend;
    int (*)(struct phy_device *) resume;
    int (*)(struct phy_device *) config_aneg;
    int (*)(struct phy_device *) aneg_done;
    int (*)(struct phy_device *) read_status;
    int (*)(struct phy_device *) ack_interrupt;
    int (*)(struct phy_device *) config_intr;
    int (*)(struct phy_device *) did_interrupt;
    int (*)(struct phy_device *) handle_interrupt;
    void (*)(struct phy_device *) remove;
    int (*)(struct phy_device *) match_phy_device;
    int (*)(struct phy_device *, struct ethtool_ts_info *) ts_info;
    int (*)(struct phy_device *, struct ifreq *) hwtstamp;
    bool (*)(struct phy_device *, struct sk_buff *, int) rxtstamp;
    void (*)(struct phy_device *, struct sk_buff *, int) txtstamp;
    int (*)(struct phy_device *, struct ethtool_wolinfo *) set_wol;
    void (*)(struct phy_device *, struct ethtool_wolinfo *) get_wol;
    void (*)(struct phy_device *) link_change_notify;
    int (*)(struct phy_device *, int, u16) read_mmd;
    int (*)(struct phy_device *, int, u16, u16) write_mmd;
    int (*)(struct phy_device *) read_page;
    int (*)(struct phy_device *, int) write_page;
    int (*)(struct phy_device *, struct ethtool_modinfo *) module_info;
    int (*)(struct phy_device *, struct ethtool_eeprom *, u8 *) module_eeprom;
    int (*)(struct phy_device *) get_sset_count;
    void (*)(struct phy_device *, u8 *) get_strings;
    void (*)(struct phy_device *, struct ethtool_stats *, u64 *) get_stats;
    int (*)(struct phy_device *, struct ethtool_tunable *, void *) get_tunable;
    int (*)(struct phy_device *, struct ethtool_tunable *, const void *) set_tunable;
    int (*)(struct phy_device *, bool) set_loopback;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct phy_driver {
    struct mdio_driver_common mdiodrv;
    u32 phy_id;
    char * name;
    u32 phy_id_mask;
    const const long unsigned int * features;
    u32 flags;
    const void * driver_data;
    int (*)(struct phy_device *) soft_reset;
    int (*)(struct phy_device *) config_init;
    int (*)(struct phy_device *) probe;
    int (*)(struct phy_device *) get_features;
    int (*)(struct phy_device *) suspend;
    int (*)(struct phy_device *) resume;
    int (*)(struct phy_device *) config_aneg;
    int (*)(struct phy_device *) aneg_done;
    int (*)(struct phy_device *) read_status;
    int (*)(struct phy_device *) ack_interrupt;
    int (*)(struct phy_device *) config_intr;
    int (*)(struct phy_device *) did_interrupt;
    int (*)(struct phy_device *) handle_interrupt;
    void (*)(struct phy_device *) remove;
    int (*)(struct phy_device *) match_phy_device;
    int (*)(struct phy_device *, struct ethtool_ts_info *) ts_info;
    int (*)(struct phy_device *, struct ifreq *) hwtstamp;
    bool (*)(struct phy_device *, struct sk_buff *, int) rxtstamp;
    void (*)(struct phy_device *, struct sk_buff *, int) txtstamp;
    int (*)(struct phy_device *, struct ethtool_wolinfo *) set_wol;
    void (*)(struct phy_device *, struct ethtool_wolinfo *) get_wol;
    void (*)(struct phy_device *) link_change_notify;
    int (*)(struct phy_device *, int, u16) read_mmd;
    int (*)(struct phy_device *, int, u16, u16) write_mmd;
    int (*)(struct phy_device *) read_page;
    int (*)(struct phy_device *, int) write_page;
    int (*)(struct phy_device *, struct ethtool_modinfo *) module_info;
    int (*)(struct phy_device *, struct ethtool_eeprom *, u8 *) module_eeprom;
    int (*)(struct phy_device *) get_sset_count;
    void (*)(struct phy_device *, u8 *) get_strings;
    void (*)(struct phy_device *, struct ethtool_stats *, u64 *) get_stats;
    int (*)(struct phy_device *, struct ethtool_tunable *, void *) get_tunable;
    int (*)(struct phy_device *, struct ethtool_tunable *, const void *) set_tunable;
    int (*)(struct phy_device *, bool) set_loopback;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct phy_driver {
    struct mdio_driver_common mdiodrv;
    u32 phy_id;
    char * name;
    u32 phy_id_mask;
    const const long unsigned int * features;
    u32 flags;
    const void * driver_data;
    int (*)(struct phy_device *) soft_reset;
    int (*)(struct phy_device *) config_init;
    int (*)(struct phy_device *) probe;
    int (*)(struct phy_device *) get_features;
    int (*)(struct phy_device *) suspend;
    int (*)(struct phy_device *) resume;
    int (*)(struct phy_device *) config_aneg;
    int (*)(struct phy_device *) aneg_done;
    int (*)(struct phy_device *) read_status;
    int (*)(struct phy_device *) ack_interrupt;
    int (*)(struct phy_device *) config_intr;
    int (*)(struct phy_device *) did_interrupt;
    int (*)(struct phy_device *) handle_interrupt;
    void (*)(struct phy_device *) remove;
    int (*)(struct phy_device *) match_phy_device;
    int (*)(struct phy_device *, struct ethtool_ts_info *) ts_info;
    int (*)(struct phy_device *, struct ifreq *) hwtstamp;
    bool (*)(struct phy_device *, struct sk_buff *, int) rxtstamp;
    void (*)(struct phy_device *, struct sk_buff *, int) txtstamp;
    int (*)(struct phy_device *, struct ethtool_wolinfo *) set_wol;
    void (*)(struct phy_device *, struct ethtool_wolinfo *) get_wol;
    void (*)(struct phy_device *) link_change_notify;
    int (*)(struct phy_device *, int, u16) read_mmd;
    int (*)(struct phy_device *, int, u16, u16) write_mmd;
    int (*)(struct phy_device *) read_page;
    int (*)(struct phy_device *, int) write_page;
    int (*)(struct phy_device *, struct ethtool_modinfo *) module_info;
    int (*)(struct phy_device *, struct ethtool_eeprom *, u8 *) module_eeprom;
    int (*)(struct phy_device *) get_sset_count;
    void (*)(struct phy_device *, u8 *) get_strings;
    void (*)(struct phy_device *, struct ethtool_stats *, u64 *) get_stats;
    int (*)(struct phy_device *, struct ethtool_tunable *, void *) get_tunable;
    int (*)(struct phy_device *, struct ethtool_tunable *, const void *) set_tunable;
    int (*)(struct phy_device *, bool) set_loopback;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct phy_driver {
    struct mdio_driver_common mdiodrv;
    u32 phy_id;
    char * name;
    u32 phy_id_mask;
    const const long unsigned int * features;
    u32 flags;
    const void * driver_data;
    int (*)(struct phy_device *) soft_reset;
    int (*)(struct phy_device *) config_init;
    int (*)(struct phy_device *) probe;
    int (*)(struct phy_device *) get_features;
    int (*)(struct phy_device *) suspend;
    int (*)(struct phy_device *) resume;
    int (*)(struct phy_device *) config_aneg;
    int (*)(struct phy_device *) aneg_done;
    int (*)(struct phy_device *) read_status;
    int (*)(struct phy_device *) ack_interrupt;
    int (*)(struct phy_device *) config_intr;
    int (*)(struct phy_device *) did_interrupt;
    int (*)(struct phy_device *) handle_interrupt;
    void (*)(struct phy_device *) remove;
    int (*)(struct phy_device *) match_phy_device;
    int (*)(struct phy_device *, struct ethtool_ts_info *) ts_info;
    int (*)(struct phy_device *, struct ifreq *) hwtstamp;
    bool (*)(struct phy_device *, struct sk_buff *, int) rxtstamp;
    void (*)(struct phy_device *, struct sk_buff *, int) txtstamp;
    int (*)(struct phy_device *, struct ethtool_wolinfo *) set_wol;
    void (*)(struct phy_device *, struct ethtool_wolinfo *) get_wol;
    void (*)(struct phy_device *) link_change_notify;
    int (*)(struct phy_device *, int, u16) read_mmd;
    int (*)(struct phy_device *, int, u16, u16) write_mmd;
    int (*)(struct phy_device *) read_page;
    int (*)(struct phy_device *, int) write_page;
    int (*)(struct phy_device *, struct ethtool_modinfo *) module_info;
    int (*)(struct phy_device *, struct ethtool_eeprom *, u8 *) module_eeprom;
    int (*)(struct phy_device *) get_sset_count;
    void (*)(struct phy_device *, u8 *) get_strings;
    void (*)(struct phy_device *, struct ethtool_stats *, u64 *) get_stats;
    int (*)(struct phy_device *, struct ethtool_tunable *, void *) get_tunable;
    int (*)(struct phy_device *, struct ethtool_tunable *, const void *) set_tunable;
    int (*)(struct phy_device *, bool) set_loopback;
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
struct phy_driver {
    struct mdio_driver_common mdiodrv;
    u32 phy_id;
    char * name;
    u32 phy_id_mask;
    const const long unsigned int * features;
    u32 flags;
    const void * driver_data;
    int (*)(struct phy_device *) soft_reset;
    int (*)(struct phy_device *) config_init;
    int (*)(struct phy_device *) probe;
    int (*)(struct phy_device *) get_features;
    int (*)(struct phy_device *) suspend;
    int (*)(struct phy_device *) resume;
    int (*)(struct phy_device *) config_aneg;
    int (*)(struct phy_device *) aneg_done;
    int (*)(struct phy_device *) read_status;
    int (*)(struct phy_device *) ack_interrupt;
    int (*)(struct phy_device *) config_intr;
    int (*)(struct phy_device *) did_interrupt;
    int (*)(struct phy_device *) handle_interrupt;
    void (*)(struct phy_device *) remove;
    int (*)(struct phy_device *) match_phy_device;
    int (*)(struct phy_device *, struct ethtool_ts_info *) ts_info;
    int (*)(struct phy_device *, struct ifreq *) hwtstamp;
    bool (*)(struct phy_device *, struct sk_buff *, int) rxtstamp;
    void (*)(struct phy_device *, struct sk_buff *, int) txtstamp;
    int (*)(struct phy_device *, struct ethtool_wolinfo *) set_wol;
    void (*)(struct phy_device *, struct ethtool_wolinfo *) get_wol;
    void (*)(struct phy_device *) link_change_notify;
    int (*)(struct phy_device *, int, u16) read_mmd;
    int (*)(struct phy_device *, int, u16, u16) write_mmd;
    int (*)(struct phy_device *) read_page;
    int (*)(struct phy_device *, int) write_page;
    int (*)(struct phy_device *, struct ethtool_modinfo *) module_info;
    int (*)(struct phy_device *, struct ethtool_eeprom *, u8 *) module_eeprom;
    int (*)(struct phy_device *) get_sset_count;
    void (*)(struct phy_device *, u8 *) get_strings;
    void (*)(struct phy_device *, struct ethtool_stats *, u64 *) get_stats;
    int (*)(struct phy_device *, struct ethtool_tunable *, void *) get_tunable;
    int (*)(struct phy_device *, struct ethtool_tunable *, const void *) set_tunable;
    int (*)(struct phy_device *, bool) set_loopback;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct phy_driver {
    struct mdio_driver_common mdiodrv;
    u32 phy_id;
    char * name;
    u32 phy_id_mask;
    const const long unsigned int * features;
    u32 flags;
    const void * driver_data;
    int (*)(struct phy_device *) soft_reset;
    int (*)(struct phy_device *) config_init;
    int (*)(struct phy_device *) probe;
    int (*)(struct phy_device *) get_features;
    int (*)(struct phy_device *) suspend;
    int (*)(struct phy_device *) resume;
    int (*)(struct phy_device *) config_aneg;
    int (*)(struct phy_device *) aneg_done;
    int (*)(struct phy_device *) read_status;
    int (*)(struct phy_device *) ack_interrupt;
    int (*)(struct phy_device *) config_intr;
    int (*)(struct phy_device *) did_interrupt;
    int (*)(struct phy_device *) handle_interrupt;
    void (*)(struct phy_device *) remove;
    int (*)(struct phy_device *) match_phy_device;
    int (*)(struct phy_device *, struct ethtool_ts_info *) ts_info;
    int (*)(struct phy_device *, struct ifreq *) hwtstamp;
    bool (*)(struct phy_device *, struct sk_buff *, int) rxtstamp;
    void (*)(struct phy_device *, struct sk_buff *, int) txtstamp;
    int (*)(struct phy_device *, struct ethtool_wolinfo *) set_wol;
    void (*)(struct phy_device *, struct ethtool_wolinfo *) get_wol;
    void (*)(struct phy_device *) link_change_notify;
    int (*)(struct phy_device *, int, u16) read_mmd;
    int (*)(struct phy_device *, int, u16, u16) write_mmd;
    int (*)(struct phy_device *) read_page;
    int (*)(struct phy_device *, int) write_page;
    int (*)(struct phy_device *, struct ethtool_modinfo *) module_info;
    int (*)(struct phy_device *, struct ethtool_eeprom *, u8 *) module_eeprom;
    int (*)(struct phy_device *) get_sset_count;
    void (*)(struct phy_device *, u8 *) get_strings;
    void (*)(struct phy_device *, struct ethtool_stats *, u64 *) get_stats;
    int (*)(struct phy_device *, struct ethtool_tunable *, void *) get_tunable;
    int (*)(struct phy_device *, struct ethtool_tunable *, const void *) set_tunable;
    int (*)(struct phy_device *, bool) set_loopback;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct phy_driver {
    struct mdio_driver_common mdiodrv;
    u32 phy_id;
    char * name;
    u32 phy_id_mask;
    const const long unsigned int * features;
    u32 flags;
    const void * driver_data;
    int (*)(struct phy_device *) soft_reset;
    int (*)(struct phy_device *) config_init;
    int (*)(struct phy_device *) probe;
    int (*)(struct phy_device *) get_features;
    int (*)(struct phy_device *) suspend;
    int (*)(struct phy_device *) resume;
    int (*)(struct phy_device *) config_aneg;
    int (*)(struct phy_device *) aneg_done;
    int (*)(struct phy_device *) read_status;
    int (*)(struct phy_device *) ack_interrupt;
    int (*)(struct phy_device *) config_intr;
    int (*)(struct phy_device *) did_interrupt;
    int (*)(struct phy_device *) handle_interrupt;
    void (*)(struct phy_device *) remove;
    int (*)(struct phy_device *) match_phy_device;
    int (*)(struct phy_device *, struct ethtool_ts_info *) ts_info;
    int (*)(struct phy_device *, struct ifreq *) hwtstamp;
    bool (*)(struct phy_device *, struct sk_buff *, int) rxtstamp;
    void (*)(struct phy_device *, struct sk_buff *, int) txtstamp;
    int (*)(struct phy_device *, struct ethtool_wolinfo *) set_wol;
    void (*)(struct phy_device *, struct ethtool_wolinfo *) get_wol;
    void (*)(struct phy_device *) link_change_notify;
    int (*)(struct phy_device *, int, u16) read_mmd;
    int (*)(struct phy_device *, int, u16, u16) write_mmd;
    int (*)(struct phy_device *) read_page;
    int (*)(struct phy_device *, int) write_page;
    int (*)(struct phy_device *, struct ethtool_modinfo *) module_info;
    int (*)(struct phy_device *, struct ethtool_eeprom *, u8 *) module_eeprom;
    int (*)(struct phy_device *) get_sset_count;
    void (*)(struct phy_device *, u8 *) get_strings;
    void (*)(struct phy_device *, struct ethtool_stats *, u64 *) get_stats;
    int (*)(struct phy_device *, struct ethtool_tunable *, void *) get_tunable;
    int (*)(struct phy_device *, struct ethtool_tunable *, const void *) set_tunable;
    int (*)(struct phy_device *, bool) set_loopback;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct phy_driver {
    struct mdio_driver_common mdiodrv;
    u32 phy_id;
    char * name;
    u32 phy_id_mask;
    const const long unsigned int * features;
    u32 flags;
    const void * driver_data;
    int (*)(struct phy_device *) soft_reset;
    int (*)(struct phy_device *) config_init;
    int (*)(struct phy_device *) probe;
    int (*)(struct phy_device *) get_features;
    int (*)(struct phy_device *) suspend;
    int (*)(struct phy_device *) resume;
    int (*)(struct phy_device *) config_aneg;
    int (*)(struct phy_device *) aneg_done;
    int (*)(struct phy_device *) read_status;
    int (*)(struct phy_device *) ack_interrupt;
    int (*)(struct phy_device *) config_intr;
    int (*)(struct phy_device *) did_interrupt;
    int (*)(struct phy_device *) handle_interrupt;
    void (*)(struct phy_device *) remove;
    int (*)(struct phy_device *) match_phy_device;
    int (*)(struct phy_device *, struct ethtool_ts_info *) ts_info;
    int (*)(struct phy_device *, struct ifreq *) hwtstamp;
    bool (*)(struct phy_device *, struct sk_buff *, int) rxtstamp;
    void (*)(struct phy_device *, struct sk_buff *, int) txtstamp;
    int (*)(struct phy_device *, struct ethtool_wolinfo *) set_wol;
    void (*)(struct phy_device *, struct ethtool_wolinfo *) get_wol;
    void (*)(struct phy_device *) link_change_notify;
    int (*)(struct phy_device *, int, u16) read_mmd;
    int (*)(struct phy_device *, int, u16, u16) write_mmd;
    int (*)(struct phy_device *) read_page;
    int (*)(struct phy_device *, int) write_page;
    int (*)(struct phy_device *, struct ethtool_modinfo *) module_info;
    int (*)(struct phy_device *, struct ethtool_eeprom *, u8 *) module_eeprom;
    int (*)(struct phy_device *) get_sset_count;
    void (*)(struct phy_device *, u8 *) get_strings;
    void (*)(struct phy_device *, struct ethtool_stats *, u64 *) get_stats;
    int (*)(struct phy_device *, struct ethtool_tunable *, void *) get_tunable;
    int (*)(struct phy_device *, struct ethtool_tunable *, const void *) set_tunable;
    int (*)(struct phy_device *, bool) set_loopback;
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
<b>Field added. </b>
<code>struct mdio_driver_common mdiodrv</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct phy_device *) get_sset_count</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct phy_device *, u8 *) get_strings</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct phy_device *, struct ethtool_stats *, u64 *) get_stats</code>
</li>
<li>
<b>Field removed. </b>
<code>struct device_driver driver</code>
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
<code>int (*)(struct phy_device *, struct ethtool_tunable *, void *) get_tunable</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct phy_device *, struct ethtool_tunable *, const void *) set_tunable</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct phy_device *, int, u16) read_mmd</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct phy_device *, int, u16, u16) write_mmd</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct phy_device *, bool) set_loopback</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct phy_device *, int, int, int) read_mmd_indirect</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct phy_device *, int, int, int, u32) write_mmd_indirect</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct phy_device *) read_page</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct phy_device *, int) write_page</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned int phy_id_mask</code> ➡️ <code>u32 phy_id_mask</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>u32 features</code> ➡️ <code>const const long unsigned int * features</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct phy_device *) get_features</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct phy_device *) handle_interrupt</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct phy_device *) cable_test_start</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct phy_device *, const struct phy_tdr_config *) cable_test_tdr_start</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct phy_device *, bool *) cable_test_get_status</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct phy_device *) get_sqi</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct phy_device *) get_sqi_max</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct phy_device *, struct ethtool_ts_info *) ts_info</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct phy_device *, struct ifreq *) hwtstamp</code>
</li>
<li>
<b>Field removed. </b>
<code>bool (*)(struct phy_device *, struct sk_buff *, int) rxtstamp</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct phy_device *, struct sk_buff *, int) txtstamp</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct phy_device *) handle_interrupt</code> ➡️ <code>irqreturn_t (*)(struct phy_device *) handle_interrupt</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>int (*)(struct phy_device *) ack_interrupt</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct phy_device *) did_interrupt</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct phy_device *, phy_interface_t) get_rate_matching</code>
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
<code>int (*)(struct phy_device *, struct phy_plca_cfg *) get_plca_cfg</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct phy_device *, const struct phy_plca_cfg *) set_plca_cfg</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct phy_device *, struct phy_plca_status *) get_plca_status</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct phy_device *, u8, enum led_brightness) led_brightness_set</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct phy_device *, u8, long unsigned int *, long unsigned int *) led_blink_set</code>
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
<code>int (*)(struct phy_device *, u8, long unsigned int) led_hw_is_supported</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct phy_device *, u8, long unsigned int) led_hw_control_set</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct phy_device *, u8, long unsigned int *) led_hw_control_get</code>
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
