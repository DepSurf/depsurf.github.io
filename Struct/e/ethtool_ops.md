# Struct: <code>ethtool_ops</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct ethtool_ops {
    int (*)(struct net_device *, struct ethtool_cmd *) get_settings;
    int (*)(struct net_device *, struct ethtool_cmd *) set_settings;
    void (*)(struct net_device *, struct ethtool_drvinfo *) get_drvinfo;
    int (*)(struct net_device *) get_regs_len;
    void (*)(struct net_device *, struct ethtool_regs *, void *) get_regs;
    void (*)(struct net_device *, struct ethtool_wolinfo *) get_wol;
    int (*)(struct net_device *, struct ethtool_wolinfo *) set_wol;
    u32 (*)(struct net_device *) get_msglevel;
    void (*)(struct net_device *, u32) set_msglevel;
    int (*)(struct net_device *) nway_reset;
    u32 (*)(struct net_device *) get_link;
    int (*)(struct net_device *) get_eeprom_len;
    int (*)(struct net_device *, struct ethtool_eeprom *, u8 *) get_eeprom;
    int (*)(struct net_device *, struct ethtool_eeprom *, u8 *) set_eeprom;
    int (*)(struct net_device *, struct ethtool_coalesce *) get_coalesce;
    int (*)(struct net_device *, struct ethtool_coalesce *) set_coalesce;
    void (*)(struct net_device *, struct ethtool_ringparam *) get_ringparam;
    int (*)(struct net_device *, struct ethtool_ringparam *) set_ringparam;
    void (*)(struct net_device *, struct ethtool_pauseparam *) get_pauseparam;
    int (*)(struct net_device *, struct ethtool_pauseparam *) set_pauseparam;
    void (*)(struct net_device *, struct ethtool_test *, u64 *) self_test;
    void (*)(struct net_device *, u32, u8 *) get_strings;
    int (*)(struct net_device *, enum ethtool_phys_id_state) set_phys_id;
    void (*)(struct net_device *, struct ethtool_stats *, u64 *) get_ethtool_stats;
    int (*)(struct net_device *) begin;
    void (*)(struct net_device *) complete;
    u32 (*)(struct net_device *) get_priv_flags;
    int (*)(struct net_device *, u32) set_priv_flags;
    int (*)(struct net_device *, int) get_sset_count;
    int (*)(struct net_device *, struct ethtool_rxnfc *, u32 *) get_rxnfc;
    int (*)(struct net_device *, struct ethtool_rxnfc *) set_rxnfc;
    int (*)(struct net_device *, struct ethtool_flash *) flash_device;
    int (*)(struct net_device *, u32 *) reset;
    u32 (*)(struct net_device *) get_rxfh_key_size;
    u32 (*)(struct net_device *) get_rxfh_indir_size;
    int (*)(struct net_device *, u32 *, u8 *, u8 *) get_rxfh;
    int (*)(struct net_device *, const u32 *, const u8 *, const u8) set_rxfh;
    void (*)(struct net_device *, struct ethtool_channels *) get_channels;
    int (*)(struct net_device *, struct ethtool_channels *) set_channels;
    int (*)(struct net_device *, struct ethtool_dump *) get_dump_flag;
    int (*)(struct net_device *, struct ethtool_dump *, void *) get_dump_data;
    int (*)(struct net_device *, struct ethtool_dump *) set_dump;
    int (*)(struct net_device *, struct ethtool_ts_info *) get_ts_info;
    int (*)(struct net_device *, struct ethtool_modinfo *) get_module_info;
    int (*)(struct net_device *, struct ethtool_eeprom *, u8 *) get_module_eeprom;
    int (*)(struct net_device *, struct ethtool_eee *) get_eee;
    int (*)(struct net_device *, struct ethtool_eee *) set_eee;
    int (*)(struct net_device *, const struct ethtool_tunable *, void *) get_tunable;
    int (*)(struct net_device *, const struct ethtool_tunable *, const void *) set_tunable;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct ethtool_ops {
    int (*)(struct net_device *, struct ethtool_cmd *) get_settings;
    int (*)(struct net_device *, struct ethtool_cmd *) set_settings;
    void (*)(struct net_device *, struct ethtool_drvinfo *) get_drvinfo;
    int (*)(struct net_device *) get_regs_len;
    void (*)(struct net_device *, struct ethtool_regs *, void *) get_regs;
    void (*)(struct net_device *, struct ethtool_wolinfo *) get_wol;
    int (*)(struct net_device *, struct ethtool_wolinfo *) set_wol;
    u32 (*)(struct net_device *) get_msglevel;
    void (*)(struct net_device *, u32) set_msglevel;
    int (*)(struct net_device *) nway_reset;
    u32 (*)(struct net_device *) get_link;
    int (*)(struct net_device *) get_eeprom_len;
    int (*)(struct net_device *, struct ethtool_eeprom *, u8 *) get_eeprom;
    int (*)(struct net_device *, struct ethtool_eeprom *, u8 *) set_eeprom;
    int (*)(struct net_device *, struct ethtool_coalesce *) get_coalesce;
    int (*)(struct net_device *, struct ethtool_coalesce *) set_coalesce;
    void (*)(struct net_device *, struct ethtool_ringparam *) get_ringparam;
    int (*)(struct net_device *, struct ethtool_ringparam *) set_ringparam;
    void (*)(struct net_device *, struct ethtool_pauseparam *) get_pauseparam;
    int (*)(struct net_device *, struct ethtool_pauseparam *) set_pauseparam;
    void (*)(struct net_device *, struct ethtool_test *, u64 *) self_test;
    void (*)(struct net_device *, u32, u8 *) get_strings;
    int (*)(struct net_device *, enum ethtool_phys_id_state) set_phys_id;
    void (*)(struct net_device *, struct ethtool_stats *, u64 *) get_ethtool_stats;
    int (*)(struct net_device *) begin;
    void (*)(struct net_device *) complete;
    u32 (*)(struct net_device *) get_priv_flags;
    int (*)(struct net_device *, u32) set_priv_flags;
    int (*)(struct net_device *, int) get_sset_count;
    int (*)(struct net_device *, struct ethtool_rxnfc *, u32 *) get_rxnfc;
    int (*)(struct net_device *, struct ethtool_rxnfc *) set_rxnfc;
    int (*)(struct net_device *, struct ethtool_flash *) flash_device;
    int (*)(struct net_device *, u32 *) reset;
    u32 (*)(struct net_device *) get_rxfh_key_size;
    u32 (*)(struct net_device *) get_rxfh_indir_size;
    int (*)(struct net_device *, u32 *, u8 *, u8 *) get_rxfh;
    int (*)(struct net_device *, const u32 *, const u8 *, const u8) set_rxfh;
    void (*)(struct net_device *, struct ethtool_channels *) get_channels;
    int (*)(struct net_device *, struct ethtool_channels *) set_channels;
    int (*)(struct net_device *, struct ethtool_dump *) get_dump_flag;
    int (*)(struct net_device *, struct ethtool_dump *, void *) get_dump_data;
    int (*)(struct net_device *, struct ethtool_dump *) set_dump;
    int (*)(struct net_device *, struct ethtool_ts_info *) get_ts_info;
    int (*)(struct net_device *, struct ethtool_modinfo *) get_module_info;
    int (*)(struct net_device *, struct ethtool_eeprom *, u8 *) get_module_eeprom;
    int (*)(struct net_device *, struct ethtool_eee *) get_eee;
    int (*)(struct net_device *, struct ethtool_eee *) set_eee;
    int (*)(struct net_device *, const struct ethtool_tunable *, void *) get_tunable;
    int (*)(struct net_device *, const struct ethtool_tunable *, const void *) set_tunable;
    int (*)(struct net_device *, u32, struct ethtool_coalesce *) get_per_queue_coalesce;
    int (*)(struct net_device *, u32, struct ethtool_coalesce *) set_per_queue_coalesce;
    int (*)(struct net_device *, struct ethtool_link_ksettings *) get_link_ksettings;
    int (*)(struct net_device *, const struct ethtool_link_ksettings *) set_link_ksettings;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct ethtool_ops {
    int (*)(struct net_device *, struct ethtool_cmd *) get_settings;
    int (*)(struct net_device *, struct ethtool_cmd *) set_settings;
    void (*)(struct net_device *, struct ethtool_drvinfo *) get_drvinfo;
    int (*)(struct net_device *) get_regs_len;
    void (*)(struct net_device *, struct ethtool_regs *, void *) get_regs;
    void (*)(struct net_device *, struct ethtool_wolinfo *) get_wol;
    int (*)(struct net_device *, struct ethtool_wolinfo *) set_wol;
    u32 (*)(struct net_device *) get_msglevel;
    void (*)(struct net_device *, u32) set_msglevel;
    int (*)(struct net_device *) nway_reset;
    u32 (*)(struct net_device *) get_link;
    int (*)(struct net_device *) get_eeprom_len;
    int (*)(struct net_device *, struct ethtool_eeprom *, u8 *) get_eeprom;
    int (*)(struct net_device *, struct ethtool_eeprom *, u8 *) set_eeprom;
    int (*)(struct net_device *, struct ethtool_coalesce *) get_coalesce;
    int (*)(struct net_device *, struct ethtool_coalesce *) set_coalesce;
    void (*)(struct net_device *, struct ethtool_ringparam *) get_ringparam;
    int (*)(struct net_device *, struct ethtool_ringparam *) set_ringparam;
    void (*)(struct net_device *, struct ethtool_pauseparam *) get_pauseparam;
    int (*)(struct net_device *, struct ethtool_pauseparam *) set_pauseparam;
    void (*)(struct net_device *, struct ethtool_test *, u64 *) self_test;
    void (*)(struct net_device *, u32, u8 *) get_strings;
    int (*)(struct net_device *, enum ethtool_phys_id_state) set_phys_id;
    void (*)(struct net_device *, struct ethtool_stats *, u64 *) get_ethtool_stats;
    int (*)(struct net_device *) begin;
    void (*)(struct net_device *) complete;
    u32 (*)(struct net_device *) get_priv_flags;
    int (*)(struct net_device *, u32) set_priv_flags;
    int (*)(struct net_device *, int) get_sset_count;
    int (*)(struct net_device *, struct ethtool_rxnfc *, u32 *) get_rxnfc;
    int (*)(struct net_device *, struct ethtool_rxnfc *) set_rxnfc;
    int (*)(struct net_device *, struct ethtool_flash *) flash_device;
    int (*)(struct net_device *, u32 *) reset;
    u32 (*)(struct net_device *) get_rxfh_key_size;
    u32 (*)(struct net_device *) get_rxfh_indir_size;
    int (*)(struct net_device *, u32 *, u8 *, u8 *) get_rxfh;
    int (*)(struct net_device *, const u32 *, const u8 *, const u8) set_rxfh;
    void (*)(struct net_device *, struct ethtool_channels *) get_channels;
    int (*)(struct net_device *, struct ethtool_channels *) set_channels;
    int (*)(struct net_device *, struct ethtool_dump *) get_dump_flag;
    int (*)(struct net_device *, struct ethtool_dump *, void *) get_dump_data;
    int (*)(struct net_device *, struct ethtool_dump *) set_dump;
    int (*)(struct net_device *, struct ethtool_ts_info *) get_ts_info;
    int (*)(struct net_device *, struct ethtool_modinfo *) get_module_info;
    int (*)(struct net_device *, struct ethtool_eeprom *, u8 *) get_module_eeprom;
    int (*)(struct net_device *, struct ethtool_eee *) get_eee;
    int (*)(struct net_device *, struct ethtool_eee *) set_eee;
    int (*)(struct net_device *, const struct ethtool_tunable *, void *) get_tunable;
    int (*)(struct net_device *, const struct ethtool_tunable *, const void *) set_tunable;
    int (*)(struct net_device *, u32, struct ethtool_coalesce *) get_per_queue_coalesce;
    int (*)(struct net_device *, u32, struct ethtool_coalesce *) set_per_queue_coalesce;
    int (*)(struct net_device *, struct ethtool_link_ksettings *) get_link_ksettings;
    int (*)(struct net_device *, const struct ethtool_link_ksettings *) set_link_ksettings;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct ethtool_ops {
    int (*)(struct net_device *, struct ethtool_cmd *) get_settings;
    int (*)(struct net_device *, struct ethtool_cmd *) set_settings;
    void (*)(struct net_device *, struct ethtool_drvinfo *) get_drvinfo;
    int (*)(struct net_device *) get_regs_len;
    void (*)(struct net_device *, struct ethtool_regs *, void *) get_regs;
    void (*)(struct net_device *, struct ethtool_wolinfo *) get_wol;
    int (*)(struct net_device *, struct ethtool_wolinfo *) set_wol;
    u32 (*)(struct net_device *) get_msglevel;
    void (*)(struct net_device *, u32) set_msglevel;
    int (*)(struct net_device *) nway_reset;
    u32 (*)(struct net_device *) get_link;
    int (*)(struct net_device *) get_eeprom_len;
    int (*)(struct net_device *, struct ethtool_eeprom *, u8 *) get_eeprom;
    int (*)(struct net_device *, struct ethtool_eeprom *, u8 *) set_eeprom;
    int (*)(struct net_device *, struct ethtool_coalesce *) get_coalesce;
    int (*)(struct net_device *, struct ethtool_coalesce *) set_coalesce;
    void (*)(struct net_device *, struct ethtool_ringparam *) get_ringparam;
    int (*)(struct net_device *, struct ethtool_ringparam *) set_ringparam;
    void (*)(struct net_device *, struct ethtool_pauseparam *) get_pauseparam;
    int (*)(struct net_device *, struct ethtool_pauseparam *) set_pauseparam;
    void (*)(struct net_device *, struct ethtool_test *, u64 *) self_test;
    void (*)(struct net_device *, u32, u8 *) get_strings;
    int (*)(struct net_device *, enum ethtool_phys_id_state) set_phys_id;
    void (*)(struct net_device *, struct ethtool_stats *, u64 *) get_ethtool_stats;
    int (*)(struct net_device *) begin;
    void (*)(struct net_device *) complete;
    u32 (*)(struct net_device *) get_priv_flags;
    int (*)(struct net_device *, u32) set_priv_flags;
    int (*)(struct net_device *, int) get_sset_count;
    int (*)(struct net_device *, struct ethtool_rxnfc *, u32 *) get_rxnfc;
    int (*)(struct net_device *, struct ethtool_rxnfc *) set_rxnfc;
    int (*)(struct net_device *, struct ethtool_flash *) flash_device;
    int (*)(struct net_device *, u32 *) reset;
    u32 (*)(struct net_device *) get_rxfh_key_size;
    u32 (*)(struct net_device *) get_rxfh_indir_size;
    int (*)(struct net_device *, u32 *, u8 *, u8 *) get_rxfh;
    int (*)(struct net_device *, const u32 *, const u8 *, const u8) set_rxfh;
    void (*)(struct net_device *, struct ethtool_channels *) get_channels;
    int (*)(struct net_device *, struct ethtool_channels *) set_channels;
    int (*)(struct net_device *, struct ethtool_dump *) get_dump_flag;
    int (*)(struct net_device *, struct ethtool_dump *, void *) get_dump_data;
    int (*)(struct net_device *, struct ethtool_dump *) set_dump;
    int (*)(struct net_device *, struct ethtool_ts_info *) get_ts_info;
    int (*)(struct net_device *, struct ethtool_modinfo *) get_module_info;
    int (*)(struct net_device *, struct ethtool_eeprom *, u8 *) get_module_eeprom;
    int (*)(struct net_device *, struct ethtool_eee *) get_eee;
    int (*)(struct net_device *, struct ethtool_eee *) set_eee;
    int (*)(struct net_device *, const struct ethtool_tunable *, void *) get_tunable;
    int (*)(struct net_device *, const struct ethtool_tunable *, const void *) set_tunable;
    int (*)(struct net_device *, u32, struct ethtool_coalesce *) get_per_queue_coalesce;
    int (*)(struct net_device *, u32, struct ethtool_coalesce *) set_per_queue_coalesce;
    int (*)(struct net_device *, struct ethtool_link_ksettings *) get_link_ksettings;
    int (*)(struct net_device *, const struct ethtool_link_ksettings *) set_link_ksettings;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct ethtool_ops {
    int (*)(struct net_device *, struct ethtool_cmd *) get_settings;
    int (*)(struct net_device *, struct ethtool_cmd *) set_settings;
    void (*)(struct net_device *, struct ethtool_drvinfo *) get_drvinfo;
    int (*)(struct net_device *) get_regs_len;
    void (*)(struct net_device *, struct ethtool_regs *, void *) get_regs;
    void (*)(struct net_device *, struct ethtool_wolinfo *) get_wol;
    int (*)(struct net_device *, struct ethtool_wolinfo *) set_wol;
    u32 (*)(struct net_device *) get_msglevel;
    void (*)(struct net_device *, u32) set_msglevel;
    int (*)(struct net_device *) nway_reset;
    u32 (*)(struct net_device *) get_link;
    int (*)(struct net_device *) get_eeprom_len;
    int (*)(struct net_device *, struct ethtool_eeprom *, u8 *) get_eeprom;
    int (*)(struct net_device *, struct ethtool_eeprom *, u8 *) set_eeprom;
    int (*)(struct net_device *, struct ethtool_coalesce *) get_coalesce;
    int (*)(struct net_device *, struct ethtool_coalesce *) set_coalesce;
    void (*)(struct net_device *, struct ethtool_ringparam *) get_ringparam;
    int (*)(struct net_device *, struct ethtool_ringparam *) set_ringparam;
    void (*)(struct net_device *, struct ethtool_pauseparam *) get_pauseparam;
    int (*)(struct net_device *, struct ethtool_pauseparam *) set_pauseparam;
    void (*)(struct net_device *, struct ethtool_test *, u64 *) self_test;
    void (*)(struct net_device *, u32, u8 *) get_strings;
    int (*)(struct net_device *, enum ethtool_phys_id_state) set_phys_id;
    void (*)(struct net_device *, struct ethtool_stats *, u64 *) get_ethtool_stats;
    int (*)(struct net_device *) begin;
    void (*)(struct net_device *) complete;
    u32 (*)(struct net_device *) get_priv_flags;
    int (*)(struct net_device *, u32) set_priv_flags;
    int (*)(struct net_device *, int) get_sset_count;
    int (*)(struct net_device *, struct ethtool_rxnfc *, u32 *) get_rxnfc;
    int (*)(struct net_device *, struct ethtool_rxnfc *) set_rxnfc;
    int (*)(struct net_device *, struct ethtool_flash *) flash_device;
    int (*)(struct net_device *, u32 *) reset;
    u32 (*)(struct net_device *) get_rxfh_key_size;
    u32 (*)(struct net_device *) get_rxfh_indir_size;
    int (*)(struct net_device *, u32 *, u8 *, u8 *) get_rxfh;
    int (*)(struct net_device *, const u32 *, const u8 *, const u8) set_rxfh;
    void (*)(struct net_device *, struct ethtool_channels *) get_channels;
    int (*)(struct net_device *, struct ethtool_channels *) set_channels;
    int (*)(struct net_device *, struct ethtool_dump *) get_dump_flag;
    int (*)(struct net_device *, struct ethtool_dump *, void *) get_dump_data;
    int (*)(struct net_device *, struct ethtool_dump *) set_dump;
    int (*)(struct net_device *, struct ethtool_ts_info *) get_ts_info;
    int (*)(struct net_device *, struct ethtool_modinfo *) get_module_info;
    int (*)(struct net_device *, struct ethtool_eeprom *, u8 *) get_module_eeprom;
    int (*)(struct net_device *, struct ethtool_eee *) get_eee;
    int (*)(struct net_device *, struct ethtool_eee *) set_eee;
    int (*)(struct net_device *, const struct ethtool_tunable *, void *) get_tunable;
    int (*)(struct net_device *, const struct ethtool_tunable *, const void *) set_tunable;
    int (*)(struct net_device *, u32, struct ethtool_coalesce *) get_per_queue_coalesce;
    int (*)(struct net_device *, u32, struct ethtool_coalesce *) set_per_queue_coalesce;
    int (*)(struct net_device *, struct ethtool_link_ksettings *) get_link_ksettings;
    int (*)(struct net_device *, const struct ethtool_link_ksettings *) set_link_ksettings;
    int (*)(struct net_device *, struct ethtool_fecparam *) get_fecparam;
    int (*)(struct net_device *, struct ethtool_fecparam *) set_fecparam;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct ethtool_ops {
    int (*)(struct net_device *, struct ethtool_cmd *) get_settings;
    int (*)(struct net_device *, struct ethtool_cmd *) set_settings;
    void (*)(struct net_device *, struct ethtool_drvinfo *) get_drvinfo;
    int (*)(struct net_device *) get_regs_len;
    void (*)(struct net_device *, struct ethtool_regs *, void *) get_regs;
    void (*)(struct net_device *, struct ethtool_wolinfo *) get_wol;
    int (*)(struct net_device *, struct ethtool_wolinfo *) set_wol;
    u32 (*)(struct net_device *) get_msglevel;
    void (*)(struct net_device *, u32) set_msglevel;
    int (*)(struct net_device *) nway_reset;
    u32 (*)(struct net_device *) get_link;
    int (*)(struct net_device *) get_eeprom_len;
    int (*)(struct net_device *, struct ethtool_eeprom *, u8 *) get_eeprom;
    int (*)(struct net_device *, struct ethtool_eeprom *, u8 *) set_eeprom;
    int (*)(struct net_device *, struct ethtool_coalesce *) get_coalesce;
    int (*)(struct net_device *, struct ethtool_coalesce *) set_coalesce;
    void (*)(struct net_device *, struct ethtool_ringparam *) get_ringparam;
    int (*)(struct net_device *, struct ethtool_ringparam *) set_ringparam;
    void (*)(struct net_device *, struct ethtool_pauseparam *) get_pauseparam;
    int (*)(struct net_device *, struct ethtool_pauseparam *) set_pauseparam;
    void (*)(struct net_device *, struct ethtool_test *, u64 *) self_test;
    void (*)(struct net_device *, u32, u8 *) get_strings;
    int (*)(struct net_device *, enum ethtool_phys_id_state) set_phys_id;
    void (*)(struct net_device *, struct ethtool_stats *, u64 *) get_ethtool_stats;
    int (*)(struct net_device *) begin;
    void (*)(struct net_device *) complete;
    u32 (*)(struct net_device *) get_priv_flags;
    int (*)(struct net_device *, u32) set_priv_flags;
    int (*)(struct net_device *, int) get_sset_count;
    int (*)(struct net_device *, struct ethtool_rxnfc *, u32 *) get_rxnfc;
    int (*)(struct net_device *, struct ethtool_rxnfc *) set_rxnfc;
    int (*)(struct net_device *, struct ethtool_flash *) flash_device;
    int (*)(struct net_device *, u32 *) reset;
    u32 (*)(struct net_device *) get_rxfh_key_size;
    u32 (*)(struct net_device *) get_rxfh_indir_size;
    int (*)(struct net_device *, u32 *, u8 *, u8 *) get_rxfh;
    int (*)(struct net_device *, const u32 *, const u8 *, const u8) set_rxfh;
    int (*)(struct net_device *, u32 *, u8 *, u8 *, u32) get_rxfh_context;
    int (*)(struct net_device *, const u32 *, const u8 *, const u8, u32 *, bool) set_rxfh_context;
    void (*)(struct net_device *, struct ethtool_channels *) get_channels;
    int (*)(struct net_device *, struct ethtool_channels *) set_channels;
    int (*)(struct net_device *, struct ethtool_dump *) get_dump_flag;
    int (*)(struct net_device *, struct ethtool_dump *, void *) get_dump_data;
    int (*)(struct net_device *, struct ethtool_dump *) set_dump;
    int (*)(struct net_device *, struct ethtool_ts_info *) get_ts_info;
    int (*)(struct net_device *, struct ethtool_modinfo *) get_module_info;
    int (*)(struct net_device *, struct ethtool_eeprom *, u8 *) get_module_eeprom;
    int (*)(struct net_device *, struct ethtool_eee *) get_eee;
    int (*)(struct net_device *, struct ethtool_eee *) set_eee;
    int (*)(struct net_device *, const struct ethtool_tunable *, void *) get_tunable;
    int (*)(struct net_device *, const struct ethtool_tunable *, const void *) set_tunable;
    int (*)(struct net_device *, u32, struct ethtool_coalesce *) get_per_queue_coalesce;
    int (*)(struct net_device *, u32, struct ethtool_coalesce *) set_per_queue_coalesce;
    int (*)(struct net_device *, struct ethtool_link_ksettings *) get_link_ksettings;
    int (*)(struct net_device *, const struct ethtool_link_ksettings *) set_link_ksettings;
    int (*)(struct net_device *, struct ethtool_fecparam *) get_fecparam;
    int (*)(struct net_device *, struct ethtool_fecparam *) set_fecparam;
    void (*)(struct net_device *, struct ethtool_stats *, u64 *) get_ethtool_phy_stats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct ethtool_ops {
    void (*)(struct net_device *, struct ethtool_drvinfo *) get_drvinfo;
    int (*)(struct net_device *) get_regs_len;
    void (*)(struct net_device *, struct ethtool_regs *, void *) get_regs;
    void (*)(struct net_device *, struct ethtool_wolinfo *) get_wol;
    int (*)(struct net_device *, struct ethtool_wolinfo *) set_wol;
    u32 (*)(struct net_device *) get_msglevel;
    void (*)(struct net_device *, u32) set_msglevel;
    int (*)(struct net_device *) nway_reset;
    u32 (*)(struct net_device *) get_link;
    int (*)(struct net_device *) get_eeprom_len;
    int (*)(struct net_device *, struct ethtool_eeprom *, u8 *) get_eeprom;
    int (*)(struct net_device *, struct ethtool_eeprom *, u8 *) set_eeprom;
    int (*)(struct net_device *, struct ethtool_coalesce *) get_coalesce;
    int (*)(struct net_device *, struct ethtool_coalesce *) set_coalesce;
    void (*)(struct net_device *, struct ethtool_ringparam *) get_ringparam;
    int (*)(struct net_device *, struct ethtool_ringparam *) set_ringparam;
    void (*)(struct net_device *, struct ethtool_pauseparam *) get_pauseparam;
    int (*)(struct net_device *, struct ethtool_pauseparam *) set_pauseparam;
    void (*)(struct net_device *, struct ethtool_test *, u64 *) self_test;
    void (*)(struct net_device *, u32, u8 *) get_strings;
    int (*)(struct net_device *, enum ethtool_phys_id_state) set_phys_id;
    void (*)(struct net_device *, struct ethtool_stats *, u64 *) get_ethtool_stats;
    int (*)(struct net_device *) begin;
    void (*)(struct net_device *) complete;
    u32 (*)(struct net_device *) get_priv_flags;
    int (*)(struct net_device *, u32) set_priv_flags;
    int (*)(struct net_device *, int) get_sset_count;
    int (*)(struct net_device *, struct ethtool_rxnfc *, u32 *) get_rxnfc;
    int (*)(struct net_device *, struct ethtool_rxnfc *) set_rxnfc;
    int (*)(struct net_device *, struct ethtool_flash *) flash_device;
    int (*)(struct net_device *, u32 *) reset;
    u32 (*)(struct net_device *) get_rxfh_key_size;
    u32 (*)(struct net_device *) get_rxfh_indir_size;
    int (*)(struct net_device *, u32 *, u8 *, u8 *) get_rxfh;
    int (*)(struct net_device *, const u32 *, const u8 *, const u8) set_rxfh;
    int (*)(struct net_device *, u32 *, u8 *, u8 *, u32) get_rxfh_context;
    int (*)(struct net_device *, const u32 *, const u8 *, const u8, u32 *, bool) set_rxfh_context;
    void (*)(struct net_device *, struct ethtool_channels *) get_channels;
    int (*)(struct net_device *, struct ethtool_channels *) set_channels;
    int (*)(struct net_device *, struct ethtool_dump *) get_dump_flag;
    int (*)(struct net_device *, struct ethtool_dump *, void *) get_dump_data;
    int (*)(struct net_device *, struct ethtool_dump *) set_dump;
    int (*)(struct net_device *, struct ethtool_ts_info *) get_ts_info;
    int (*)(struct net_device *, struct ethtool_modinfo *) get_module_info;
    int (*)(struct net_device *, struct ethtool_eeprom *, u8 *) get_module_eeprom;
    int (*)(struct net_device *, struct ethtool_eee *) get_eee;
    int (*)(struct net_device *, struct ethtool_eee *) set_eee;
    int (*)(struct net_device *, const struct ethtool_tunable *, void *) get_tunable;
    int (*)(struct net_device *, const struct ethtool_tunable *, const void *) set_tunable;
    int (*)(struct net_device *, u32, struct ethtool_coalesce *) get_per_queue_coalesce;
    int (*)(struct net_device *, u32, struct ethtool_coalesce *) set_per_queue_coalesce;
    int (*)(struct net_device *, struct ethtool_link_ksettings *) get_link_ksettings;
    int (*)(struct net_device *, const struct ethtool_link_ksettings *) set_link_ksettings;
    int (*)(struct net_device *, struct ethtool_fecparam *) get_fecparam;
    int (*)(struct net_device *, struct ethtool_fecparam *) set_fecparam;
    void (*)(struct net_device *, struct ethtool_stats *, u64 *) get_ethtool_phy_stats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct ethtool_ops {
    void (*)(struct net_device *, struct ethtool_drvinfo *) get_drvinfo;
    int (*)(struct net_device *) get_regs_len;
    void (*)(struct net_device *, struct ethtool_regs *, void *) get_regs;
    void (*)(struct net_device *, struct ethtool_wolinfo *) get_wol;
    int (*)(struct net_device *, struct ethtool_wolinfo *) set_wol;
    u32 (*)(struct net_device *) get_msglevel;
    void (*)(struct net_device *, u32) set_msglevel;
    int (*)(struct net_device *) nway_reset;
    u32 (*)(struct net_device *) get_link;
    int (*)(struct net_device *) get_eeprom_len;
    int (*)(struct net_device *, struct ethtool_eeprom *, u8 *) get_eeprom;
    int (*)(struct net_device *, struct ethtool_eeprom *, u8 *) set_eeprom;
    int (*)(struct net_device *, struct ethtool_coalesce *) get_coalesce;
    int (*)(struct net_device *, struct ethtool_coalesce *) set_coalesce;
    void (*)(struct net_device *, struct ethtool_ringparam *) get_ringparam;
    int (*)(struct net_device *, struct ethtool_ringparam *) set_ringparam;
    void (*)(struct net_device *, struct ethtool_pauseparam *) get_pauseparam;
    int (*)(struct net_device *, struct ethtool_pauseparam *) set_pauseparam;
    void (*)(struct net_device *, struct ethtool_test *, u64 *) self_test;
    void (*)(struct net_device *, u32, u8 *) get_strings;
    int (*)(struct net_device *, enum ethtool_phys_id_state) set_phys_id;
    void (*)(struct net_device *, struct ethtool_stats *, u64 *) get_ethtool_stats;
    int (*)(struct net_device *) begin;
    void (*)(struct net_device *) complete;
    u32 (*)(struct net_device *) get_priv_flags;
    int (*)(struct net_device *, u32) set_priv_flags;
    int (*)(struct net_device *, int) get_sset_count;
    int (*)(struct net_device *, struct ethtool_rxnfc *, u32 *) get_rxnfc;
    int (*)(struct net_device *, struct ethtool_rxnfc *) set_rxnfc;
    int (*)(struct net_device *, struct ethtool_flash *) flash_device;
    int (*)(struct net_device *, u32 *) reset;
    u32 (*)(struct net_device *) get_rxfh_key_size;
    u32 (*)(struct net_device *) get_rxfh_indir_size;
    int (*)(struct net_device *, u32 *, u8 *, u8 *) get_rxfh;
    int (*)(struct net_device *, const u32 *, const u8 *, const u8) set_rxfh;
    int (*)(struct net_device *, u32 *, u8 *, u8 *, u32) get_rxfh_context;
    int (*)(struct net_device *, const u32 *, const u8 *, const u8, u32 *, bool) set_rxfh_context;
    void (*)(struct net_device *, struct ethtool_channels *) get_channels;
    int (*)(struct net_device *, struct ethtool_channels *) set_channels;
    int (*)(struct net_device *, struct ethtool_dump *) get_dump_flag;
    int (*)(struct net_device *, struct ethtool_dump *, void *) get_dump_data;
    int (*)(struct net_device *, struct ethtool_dump *) set_dump;
    int (*)(struct net_device *, struct ethtool_ts_info *) get_ts_info;
    int (*)(struct net_device *, struct ethtool_modinfo *) get_module_info;
    int (*)(struct net_device *, struct ethtool_eeprom *, u8 *) get_module_eeprom;
    int (*)(struct net_device *, struct ethtool_eee *) get_eee;
    int (*)(struct net_device *, struct ethtool_eee *) set_eee;
    int (*)(struct net_device *, const struct ethtool_tunable *, void *) get_tunable;
    int (*)(struct net_device *, const struct ethtool_tunable *, const void *) set_tunable;
    int (*)(struct net_device *, u32, struct ethtool_coalesce *) get_per_queue_coalesce;
    int (*)(struct net_device *, u32, struct ethtool_coalesce *) set_per_queue_coalesce;
    int (*)(struct net_device *, struct ethtool_link_ksettings *) get_link_ksettings;
    int (*)(struct net_device *, const struct ethtool_link_ksettings *) set_link_ksettings;
    int (*)(struct net_device *, struct ethtool_fecparam *) get_fecparam;
    int (*)(struct net_device *, struct ethtool_fecparam *) set_fecparam;
    void (*)(struct net_device *, struct ethtool_stats *, u64 *) get_ethtool_phy_stats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct ethtool_ops {
    void (*)(struct net_device *, struct ethtool_drvinfo *) get_drvinfo;
    int (*)(struct net_device *) get_regs_len;
    void (*)(struct net_device *, struct ethtool_regs *, void *) get_regs;
    void (*)(struct net_device *, struct ethtool_wolinfo *) get_wol;
    int (*)(struct net_device *, struct ethtool_wolinfo *) set_wol;
    u32 (*)(struct net_device *) get_msglevel;
    void (*)(struct net_device *, u32) set_msglevel;
    int (*)(struct net_device *) nway_reset;
    u32 (*)(struct net_device *) get_link;
    int (*)(struct net_device *) get_eeprom_len;
    int (*)(struct net_device *, struct ethtool_eeprom *, u8 *) get_eeprom;
    int (*)(struct net_device *, struct ethtool_eeprom *, u8 *) set_eeprom;
    int (*)(struct net_device *, struct ethtool_coalesce *) get_coalesce;
    int (*)(struct net_device *, struct ethtool_coalesce *) set_coalesce;
    void (*)(struct net_device *, struct ethtool_ringparam *) get_ringparam;
    int (*)(struct net_device *, struct ethtool_ringparam *) set_ringparam;
    void (*)(struct net_device *, struct ethtool_pauseparam *) get_pauseparam;
    int (*)(struct net_device *, struct ethtool_pauseparam *) set_pauseparam;
    void (*)(struct net_device *, struct ethtool_test *, u64 *) self_test;
    void (*)(struct net_device *, u32, u8 *) get_strings;
    int (*)(struct net_device *, enum ethtool_phys_id_state) set_phys_id;
    void (*)(struct net_device *, struct ethtool_stats *, u64 *) get_ethtool_stats;
    int (*)(struct net_device *) begin;
    void (*)(struct net_device *) complete;
    u32 (*)(struct net_device *) get_priv_flags;
    int (*)(struct net_device *, u32) set_priv_flags;
    int (*)(struct net_device *, int) get_sset_count;
    int (*)(struct net_device *, struct ethtool_rxnfc *, u32 *) get_rxnfc;
    int (*)(struct net_device *, struct ethtool_rxnfc *) set_rxnfc;
    int (*)(struct net_device *, struct ethtool_flash *) flash_device;
    int (*)(struct net_device *, u32 *) reset;
    u32 (*)(struct net_device *) get_rxfh_key_size;
    u32 (*)(struct net_device *) get_rxfh_indir_size;
    int (*)(struct net_device *, u32 *, u8 *, u8 *) get_rxfh;
    int (*)(struct net_device *, const u32 *, const u8 *, const u8) set_rxfh;
    int (*)(struct net_device *, u32 *, u8 *, u8 *, u32) get_rxfh_context;
    int (*)(struct net_device *, const u32 *, const u8 *, const u8, u32 *, bool) set_rxfh_context;
    void (*)(struct net_device *, struct ethtool_channels *) get_channels;
    int (*)(struct net_device *, struct ethtool_channels *) set_channels;
    int (*)(struct net_device *, struct ethtool_dump *) get_dump_flag;
    int (*)(struct net_device *, struct ethtool_dump *, void *) get_dump_data;
    int (*)(struct net_device *, struct ethtool_dump *) set_dump;
    int (*)(struct net_device *, struct ethtool_ts_info *) get_ts_info;
    int (*)(struct net_device *, struct ethtool_modinfo *) get_module_info;
    int (*)(struct net_device *, struct ethtool_eeprom *, u8 *) get_module_eeprom;
    int (*)(struct net_device *, struct ethtool_eee *) get_eee;
    int (*)(struct net_device *, struct ethtool_eee *) set_eee;
    int (*)(struct net_device *, const struct ethtool_tunable *, void *) get_tunable;
    int (*)(struct net_device *, const struct ethtool_tunable *, const void *) set_tunable;
    int (*)(struct net_device *, u32, struct ethtool_coalesce *) get_per_queue_coalesce;
    int (*)(struct net_device *, u32, struct ethtool_coalesce *) set_per_queue_coalesce;
    int (*)(struct net_device *, struct ethtool_link_ksettings *) get_link_ksettings;
    int (*)(struct net_device *, const struct ethtool_link_ksettings *) set_link_ksettings;
    int (*)(struct net_device *, struct ethtool_fecparam *) get_fecparam;
    int (*)(struct net_device *, struct ethtool_fecparam *) set_fecparam;
    void (*)(struct net_device *, struct ethtool_stats *, u64 *) get_ethtool_phy_stats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct ethtool_ops {
    u32 supported_coalesce_params;
    void (*)(struct net_device *, struct ethtool_drvinfo *) get_drvinfo;
    int (*)(struct net_device *) get_regs_len;
    void (*)(struct net_device *, struct ethtool_regs *, void *) get_regs;
    void (*)(struct net_device *, struct ethtool_wolinfo *) get_wol;
    int (*)(struct net_device *, struct ethtool_wolinfo *) set_wol;
    u32 (*)(struct net_device *) get_msglevel;
    void (*)(struct net_device *, u32) set_msglevel;
    int (*)(struct net_device *) nway_reset;
    u32 (*)(struct net_device *) get_link;
    int (*)(struct net_device *) get_eeprom_len;
    int (*)(struct net_device *, struct ethtool_eeprom *, u8 *) get_eeprom;
    int (*)(struct net_device *, struct ethtool_eeprom *, u8 *) set_eeprom;
    int (*)(struct net_device *, struct ethtool_coalesce *) get_coalesce;
    int (*)(struct net_device *, struct ethtool_coalesce *) set_coalesce;
    void (*)(struct net_device *, struct ethtool_ringparam *) get_ringparam;
    int (*)(struct net_device *, struct ethtool_ringparam *) set_ringparam;
    void (*)(struct net_device *, struct ethtool_pauseparam *) get_pauseparam;
    int (*)(struct net_device *, struct ethtool_pauseparam *) set_pauseparam;
    void (*)(struct net_device *, struct ethtool_test *, u64 *) self_test;
    void (*)(struct net_device *, u32, u8 *) get_strings;
    int (*)(struct net_device *, enum ethtool_phys_id_state) set_phys_id;
    void (*)(struct net_device *, struct ethtool_stats *, u64 *) get_ethtool_stats;
    int (*)(struct net_device *) begin;
    void (*)(struct net_device *) complete;
    u32 (*)(struct net_device *) get_priv_flags;
    int (*)(struct net_device *, u32) set_priv_flags;
    int (*)(struct net_device *, int) get_sset_count;
    int (*)(struct net_device *, struct ethtool_rxnfc *, u32 *) get_rxnfc;
    int (*)(struct net_device *, struct ethtool_rxnfc *) set_rxnfc;
    int (*)(struct net_device *, struct ethtool_flash *) flash_device;
    int (*)(struct net_device *, u32 *) reset;
    u32 (*)(struct net_device *) get_rxfh_key_size;
    u32 (*)(struct net_device *) get_rxfh_indir_size;
    int (*)(struct net_device *, u32 *, u8 *, u8 *) get_rxfh;
    int (*)(struct net_device *, const u32 *, const u8 *, const u8) set_rxfh;
    int (*)(struct net_device *, u32 *, u8 *, u8 *, u32) get_rxfh_context;
    int (*)(struct net_device *, const u32 *, const u8 *, const u8, u32 *, bool) set_rxfh_context;
    void (*)(struct net_device *, struct ethtool_channels *) get_channels;
    int (*)(struct net_device *, struct ethtool_channels *) set_channels;
    int (*)(struct net_device *, struct ethtool_dump *) get_dump_flag;
    int (*)(struct net_device *, struct ethtool_dump *, void *) get_dump_data;
    int (*)(struct net_device *, struct ethtool_dump *) set_dump;
    int (*)(struct net_device *, struct ethtool_ts_info *) get_ts_info;
    int (*)(struct net_device *, struct ethtool_modinfo *) get_module_info;
    int (*)(struct net_device *, struct ethtool_eeprom *, u8 *) get_module_eeprom;
    int (*)(struct net_device *, struct ethtool_eee *) get_eee;
    int (*)(struct net_device *, struct ethtool_eee *) set_eee;
    int (*)(struct net_device *, const struct ethtool_tunable *, void *) get_tunable;
    int (*)(struct net_device *, const struct ethtool_tunable *, const void *) set_tunable;
    int (*)(struct net_device *, u32, struct ethtool_coalesce *) get_per_queue_coalesce;
    int (*)(struct net_device *, u32, struct ethtool_coalesce *) set_per_queue_coalesce;
    int (*)(struct net_device *, struct ethtool_link_ksettings *) get_link_ksettings;
    int (*)(struct net_device *, const struct ethtool_link_ksettings *) set_link_ksettings;
    int (*)(struct net_device *, struct ethtool_fecparam *) get_fecparam;
    int (*)(struct net_device *, struct ethtool_fecparam *) set_fecparam;
    void (*)(struct net_device *, struct ethtool_stats *, u64 *) get_ethtool_phy_stats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct ethtool_ops {
    u32 supported_coalesce_params;
    void (*)(struct net_device *, struct ethtool_drvinfo *) get_drvinfo;
    int (*)(struct net_device *) get_regs_len;
    void (*)(struct net_device *, struct ethtool_regs *, void *) get_regs;
    void (*)(struct net_device *, struct ethtool_wolinfo *) get_wol;
    int (*)(struct net_device *, struct ethtool_wolinfo *) set_wol;
    u32 (*)(struct net_device *) get_msglevel;
    void (*)(struct net_device *, u32) set_msglevel;
    int (*)(struct net_device *) nway_reset;
    u32 (*)(struct net_device *) get_link;
    int (*)(struct net_device *, struct ethtool_link_ext_state_info *) get_link_ext_state;
    int (*)(struct net_device *) get_eeprom_len;
    int (*)(struct net_device *, struct ethtool_eeprom *, u8 *) get_eeprom;
    int (*)(struct net_device *, struct ethtool_eeprom *, u8 *) set_eeprom;
    int (*)(struct net_device *, struct ethtool_coalesce *) get_coalesce;
    int (*)(struct net_device *, struct ethtool_coalesce *) set_coalesce;
    void (*)(struct net_device *, struct ethtool_ringparam *) get_ringparam;
    int (*)(struct net_device *, struct ethtool_ringparam *) set_ringparam;
    void (*)(struct net_device *, struct ethtool_pause_stats *) get_pause_stats;
    void (*)(struct net_device *, struct ethtool_pauseparam *) get_pauseparam;
    int (*)(struct net_device *, struct ethtool_pauseparam *) set_pauseparam;
    void (*)(struct net_device *, struct ethtool_test *, u64 *) self_test;
    void (*)(struct net_device *, u32, u8 *) get_strings;
    int (*)(struct net_device *, enum ethtool_phys_id_state) set_phys_id;
    void (*)(struct net_device *, struct ethtool_stats *, u64 *) get_ethtool_stats;
    int (*)(struct net_device *) begin;
    void (*)(struct net_device *) complete;
    u32 (*)(struct net_device *) get_priv_flags;
    int (*)(struct net_device *, u32) set_priv_flags;
    int (*)(struct net_device *, int) get_sset_count;
    int (*)(struct net_device *, struct ethtool_rxnfc *, u32 *) get_rxnfc;
    int (*)(struct net_device *, struct ethtool_rxnfc *) set_rxnfc;
    int (*)(struct net_device *, struct ethtool_flash *) flash_device;
    int (*)(struct net_device *, u32 *) reset;
    u32 (*)(struct net_device *) get_rxfh_key_size;
    u32 (*)(struct net_device *) get_rxfh_indir_size;
    int (*)(struct net_device *, u32 *, u8 *, u8 *) get_rxfh;
    int (*)(struct net_device *, const u32 *, const u8 *, const u8) set_rxfh;
    int (*)(struct net_device *, u32 *, u8 *, u8 *, u32) get_rxfh_context;
    int (*)(struct net_device *, const u32 *, const u8 *, const u8, u32 *, bool) set_rxfh_context;
    void (*)(struct net_device *, struct ethtool_channels *) get_channels;
    int (*)(struct net_device *, struct ethtool_channels *) set_channels;
    int (*)(struct net_device *, struct ethtool_dump *) get_dump_flag;
    int (*)(struct net_device *, struct ethtool_dump *, void *) get_dump_data;
    int (*)(struct net_device *, struct ethtool_dump *) set_dump;
    int (*)(struct net_device *, struct ethtool_ts_info *) get_ts_info;
    int (*)(struct net_device *, struct ethtool_modinfo *) get_module_info;
    int (*)(struct net_device *, struct ethtool_eeprom *, u8 *) get_module_eeprom;
    int (*)(struct net_device *, struct ethtool_eee *) get_eee;
    int (*)(struct net_device *, struct ethtool_eee *) set_eee;
    int (*)(struct net_device *, const struct ethtool_tunable *, void *) get_tunable;
    int (*)(struct net_device *, const struct ethtool_tunable *, const void *) set_tunable;
    int (*)(struct net_device *, u32, struct ethtool_coalesce *) get_per_queue_coalesce;
    int (*)(struct net_device *, u32, struct ethtool_coalesce *) set_per_queue_coalesce;
    int (*)(struct net_device *, struct ethtool_link_ksettings *) get_link_ksettings;
    int (*)(struct net_device *, const struct ethtool_link_ksettings *) set_link_ksettings;
    int (*)(struct net_device *, struct ethtool_fecparam *) get_fecparam;
    int (*)(struct net_device *, struct ethtool_fecparam *) set_fecparam;
    void (*)(struct net_device *, struct ethtool_stats *, u64 *) get_ethtool_phy_stats;
    int (*)(struct net_device *, const struct ethtool_tunable *, void *) get_phy_tunable;
    int (*)(struct net_device *, const struct ethtool_tunable *, const void *) set_phy_tunable;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct ethtool_ops {
    u32 cap_link_lanes_supported;
    u32 supported_coalesce_params;
    void (*)(struct net_device *, struct ethtool_drvinfo *) get_drvinfo;
    int (*)(struct net_device *) get_regs_len;
    void (*)(struct net_device *, struct ethtool_regs *, void *) get_regs;
    void (*)(struct net_device *, struct ethtool_wolinfo *) get_wol;
    int (*)(struct net_device *, struct ethtool_wolinfo *) set_wol;
    u32 (*)(struct net_device *) get_msglevel;
    void (*)(struct net_device *, u32) set_msglevel;
    int (*)(struct net_device *) nway_reset;
    u32 (*)(struct net_device *) get_link;
    int (*)(struct net_device *, struct ethtool_link_ext_state_info *) get_link_ext_state;
    int (*)(struct net_device *) get_eeprom_len;
    int (*)(struct net_device *, struct ethtool_eeprom *, u8 *) get_eeprom;
    int (*)(struct net_device *, struct ethtool_eeprom *, u8 *) set_eeprom;
    int (*)(struct net_device *, struct ethtool_coalesce *) get_coalesce;
    int (*)(struct net_device *, struct ethtool_coalesce *) set_coalesce;
    void (*)(struct net_device *, struct ethtool_ringparam *) get_ringparam;
    int (*)(struct net_device *, struct ethtool_ringparam *) set_ringparam;
    void (*)(struct net_device *, struct ethtool_pause_stats *) get_pause_stats;
    void (*)(struct net_device *, struct ethtool_pauseparam *) get_pauseparam;
    int (*)(struct net_device *, struct ethtool_pauseparam *) set_pauseparam;
    void (*)(struct net_device *, struct ethtool_test *, u64 *) self_test;
    void (*)(struct net_device *, u32, u8 *) get_strings;
    int (*)(struct net_device *, enum ethtool_phys_id_state) set_phys_id;
    void (*)(struct net_device *, struct ethtool_stats *, u64 *) get_ethtool_stats;
    int (*)(struct net_device *) begin;
    void (*)(struct net_device *) complete;
    u32 (*)(struct net_device *) get_priv_flags;
    int (*)(struct net_device *, u32) set_priv_flags;
    int (*)(struct net_device *, int) get_sset_count;
    int (*)(struct net_device *, struct ethtool_rxnfc *, u32 *) get_rxnfc;
    int (*)(struct net_device *, struct ethtool_rxnfc *) set_rxnfc;
    int (*)(struct net_device *, struct ethtool_flash *) flash_device;
    int (*)(struct net_device *, u32 *) reset;
    u32 (*)(struct net_device *) get_rxfh_key_size;
    u32 (*)(struct net_device *) get_rxfh_indir_size;
    int (*)(struct net_device *, u32 *, u8 *, u8 *) get_rxfh;
    int (*)(struct net_device *, const u32 *, const u8 *, const u8) set_rxfh;
    int (*)(struct net_device *, u32 *, u8 *, u8 *, u32) get_rxfh_context;
    int (*)(struct net_device *, const u32 *, const u8 *, const u8, u32 *, bool) set_rxfh_context;
    void (*)(struct net_device *, struct ethtool_channels *) get_channels;
    int (*)(struct net_device *, struct ethtool_channels *) set_channels;
    int (*)(struct net_device *, struct ethtool_dump *) get_dump_flag;
    int (*)(struct net_device *, struct ethtool_dump *, void *) get_dump_data;
    int (*)(struct net_device *, struct ethtool_dump *) set_dump;
    int (*)(struct net_device *, struct ethtool_ts_info *) get_ts_info;
    int (*)(struct net_device *, struct ethtool_modinfo *) get_module_info;
    int (*)(struct net_device *, struct ethtool_eeprom *, u8 *) get_module_eeprom;
    int (*)(struct net_device *, struct ethtool_eee *) get_eee;
    int (*)(struct net_device *, struct ethtool_eee *) set_eee;
    int (*)(struct net_device *, const struct ethtool_tunable *, void *) get_tunable;
    int (*)(struct net_device *, const struct ethtool_tunable *, const void *) set_tunable;
    int (*)(struct net_device *, u32, struct ethtool_coalesce *) get_per_queue_coalesce;
    int (*)(struct net_device *, u32, struct ethtool_coalesce *) set_per_queue_coalesce;
    int (*)(struct net_device *, struct ethtool_link_ksettings *) get_link_ksettings;
    int (*)(struct net_device *, const struct ethtool_link_ksettings *) set_link_ksettings;
    void (*)(struct net_device *, struct ethtool_fec_stats *) get_fec_stats;
    int (*)(struct net_device *, struct ethtool_fecparam *) get_fecparam;
    int (*)(struct net_device *, struct ethtool_fecparam *) set_fecparam;
    void (*)(struct net_device *, struct ethtool_stats *, u64 *) get_ethtool_phy_stats;
    int (*)(struct net_device *, const struct ethtool_tunable *, void *) get_phy_tunable;
    int (*)(struct net_device *, const struct ethtool_tunable *, const void *) set_phy_tunable;
    int (*)(struct net_device *, const struct ethtool_module_eeprom *, struct netlink_ext_ack *) get_module_eeprom_by_page;
    void (*)(struct net_device *, struct ethtool_eth_phy_stats *) get_eth_phy_stats;
    void (*)(struct net_device *, struct ethtool_eth_mac_stats *) get_eth_mac_stats;
    void (*)(struct net_device *, struct ethtool_eth_ctrl_stats *) get_eth_ctrl_stats;
    void (*)(struct net_device *, struct ethtool_rmon_stats *, const struct ethtool_rmon_hist_range * *) get_rmon_stats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct ethtool_ops {
    u32 cap_link_lanes_supported;
    u32 supported_coalesce_params;
    void (*)(struct net_device *, struct ethtool_drvinfo *) get_drvinfo;
    int (*)(struct net_device *) get_regs_len;
    void (*)(struct net_device *, struct ethtool_regs *, void *) get_regs;
    void (*)(struct net_device *, struct ethtool_wolinfo *) get_wol;
    int (*)(struct net_device *, struct ethtool_wolinfo *) set_wol;
    u32 (*)(struct net_device *) get_msglevel;
    void (*)(struct net_device *, u32) set_msglevel;
    int (*)(struct net_device *) nway_reset;
    u32 (*)(struct net_device *) get_link;
    int (*)(struct net_device *, struct ethtool_link_ext_state_info *) get_link_ext_state;
    int (*)(struct net_device *) get_eeprom_len;
    int (*)(struct net_device *, struct ethtool_eeprom *, u8 *) get_eeprom;
    int (*)(struct net_device *, struct ethtool_eeprom *, u8 *) set_eeprom;
    int (*)(struct net_device *, struct ethtool_coalesce *, struct kernel_ethtool_coalesce *, struct netlink_ext_ack *) get_coalesce;
    int (*)(struct net_device *, struct ethtool_coalesce *, struct kernel_ethtool_coalesce *, struct netlink_ext_ack *) set_coalesce;
    void (*)(struct net_device *, struct ethtool_ringparam *) get_ringparam;
    int (*)(struct net_device *, struct ethtool_ringparam *) set_ringparam;
    void (*)(struct net_device *, struct ethtool_pause_stats *) get_pause_stats;
    void (*)(struct net_device *, struct ethtool_pauseparam *) get_pauseparam;
    int (*)(struct net_device *, struct ethtool_pauseparam *) set_pauseparam;
    void (*)(struct net_device *, struct ethtool_test *, u64 *) self_test;
    void (*)(struct net_device *, u32, u8 *) get_strings;
    int (*)(struct net_device *, enum ethtool_phys_id_state) set_phys_id;
    void (*)(struct net_device *, struct ethtool_stats *, u64 *) get_ethtool_stats;
    int (*)(struct net_device *) begin;
    void (*)(struct net_device *) complete;
    u32 (*)(struct net_device *) get_priv_flags;
    int (*)(struct net_device *, u32) set_priv_flags;
    int (*)(struct net_device *, int) get_sset_count;
    int (*)(struct net_device *, struct ethtool_rxnfc *, u32 *) get_rxnfc;
    int (*)(struct net_device *, struct ethtool_rxnfc *) set_rxnfc;
    int (*)(struct net_device *, struct ethtool_flash *) flash_device;
    int (*)(struct net_device *, u32 *) reset;
    u32 (*)(struct net_device *) get_rxfh_key_size;
    u32 (*)(struct net_device *) get_rxfh_indir_size;
    int (*)(struct net_device *, u32 *, u8 *, u8 *) get_rxfh;
    int (*)(struct net_device *, const u32 *, const u8 *, const u8) set_rxfh;
    int (*)(struct net_device *, u32 *, u8 *, u8 *, u32) get_rxfh_context;
    int (*)(struct net_device *, const u32 *, const u8 *, const u8, u32 *, bool) set_rxfh_context;
    void (*)(struct net_device *, struct ethtool_channels *) get_channels;
    int (*)(struct net_device *, struct ethtool_channels *) set_channels;
    int (*)(struct net_device *, struct ethtool_dump *) get_dump_flag;
    int (*)(struct net_device *, struct ethtool_dump *, void *) get_dump_data;
    int (*)(struct net_device *, struct ethtool_dump *) set_dump;
    int (*)(struct net_device *, struct ethtool_ts_info *) get_ts_info;
    int (*)(struct net_device *, struct ethtool_modinfo *) get_module_info;
    int (*)(struct net_device *, struct ethtool_eeprom *, u8 *) get_module_eeprom;
    int (*)(struct net_device *, struct ethtool_eee *) get_eee;
    int (*)(struct net_device *, struct ethtool_eee *) set_eee;
    int (*)(struct net_device *, const struct ethtool_tunable *, void *) get_tunable;
    int (*)(struct net_device *, const struct ethtool_tunable *, const void *) set_tunable;
    int (*)(struct net_device *, u32, struct ethtool_coalesce *) get_per_queue_coalesce;
    int (*)(struct net_device *, u32, struct ethtool_coalesce *) set_per_queue_coalesce;
    int (*)(struct net_device *, struct ethtool_link_ksettings *) get_link_ksettings;
    int (*)(struct net_device *, const struct ethtool_link_ksettings *) set_link_ksettings;
    void (*)(struct net_device *, struct ethtool_fec_stats *) get_fec_stats;
    int (*)(struct net_device *, struct ethtool_fecparam *) get_fecparam;
    int (*)(struct net_device *, struct ethtool_fecparam *) set_fecparam;
    void (*)(struct net_device *, struct ethtool_stats *, u64 *) get_ethtool_phy_stats;
    int (*)(struct net_device *, const struct ethtool_tunable *, void *) get_phy_tunable;
    int (*)(struct net_device *, const struct ethtool_tunable *, const void *) set_phy_tunable;
    int (*)(struct net_device *, const struct ethtool_module_eeprom *, struct netlink_ext_ack *) get_module_eeprom_by_page;
    void (*)(struct net_device *, struct ethtool_eth_phy_stats *) get_eth_phy_stats;
    void (*)(struct net_device *, struct ethtool_eth_mac_stats *) get_eth_mac_stats;
    void (*)(struct net_device *, struct ethtool_eth_ctrl_stats *) get_eth_ctrl_stats;
    void (*)(struct net_device *, struct ethtool_rmon_stats *, const struct ethtool_rmon_hist_range * *) get_rmon_stats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct ethtool_ops {
    u32 cap_link_lanes_supported;
    u32 supported_coalesce_params;
    u32 supported_ring_params;
    void (*)(struct net_device *, struct ethtool_drvinfo *) get_drvinfo;
    int (*)(struct net_device *) get_regs_len;
    void (*)(struct net_device *, struct ethtool_regs *, void *) get_regs;
    void (*)(struct net_device *, struct ethtool_wolinfo *) get_wol;
    int (*)(struct net_device *, struct ethtool_wolinfo *) set_wol;
    u32 (*)(struct net_device *) get_msglevel;
    void (*)(struct net_device *, u32) set_msglevel;
    int (*)(struct net_device *) nway_reset;
    u32 (*)(struct net_device *) get_link;
    int (*)(struct net_device *, struct ethtool_link_ext_state_info *) get_link_ext_state;
    int (*)(struct net_device *) get_eeprom_len;
    int (*)(struct net_device *, struct ethtool_eeprom *, u8 *) get_eeprom;
    int (*)(struct net_device *, struct ethtool_eeprom *, u8 *) set_eeprom;
    int (*)(struct net_device *, struct ethtool_coalesce *, struct kernel_ethtool_coalesce *, struct netlink_ext_ack *) get_coalesce;
    int (*)(struct net_device *, struct ethtool_coalesce *, struct kernel_ethtool_coalesce *, struct netlink_ext_ack *) set_coalesce;
    void (*)(struct net_device *, struct ethtool_ringparam *, struct kernel_ethtool_ringparam *, struct netlink_ext_ack *) get_ringparam;
    int (*)(struct net_device *, struct ethtool_ringparam *, struct kernel_ethtool_ringparam *, struct netlink_ext_ack *) set_ringparam;
    void (*)(struct net_device *, struct ethtool_pause_stats *) get_pause_stats;
    void (*)(struct net_device *, struct ethtool_pauseparam *) get_pauseparam;
    int (*)(struct net_device *, struct ethtool_pauseparam *) set_pauseparam;
    void (*)(struct net_device *, struct ethtool_test *, u64 *) self_test;
    void (*)(struct net_device *, u32, u8 *) get_strings;
    int (*)(struct net_device *, enum ethtool_phys_id_state) set_phys_id;
    void (*)(struct net_device *, struct ethtool_stats *, u64 *) get_ethtool_stats;
    int (*)(struct net_device *) begin;
    void (*)(struct net_device *) complete;
    u32 (*)(struct net_device *) get_priv_flags;
    int (*)(struct net_device *, u32) set_priv_flags;
    int (*)(struct net_device *, int) get_sset_count;
    int (*)(struct net_device *, struct ethtool_rxnfc *, u32 *) get_rxnfc;
    int (*)(struct net_device *, struct ethtool_rxnfc *) set_rxnfc;
    int (*)(struct net_device *, struct ethtool_flash *) flash_device;
    int (*)(struct net_device *, u32 *) reset;
    u32 (*)(struct net_device *) get_rxfh_key_size;
    u32 (*)(struct net_device *) get_rxfh_indir_size;
    int (*)(struct net_device *, u32 *, u8 *, u8 *) get_rxfh;
    int (*)(struct net_device *, const u32 *, const u8 *, const u8) set_rxfh;
    int (*)(struct net_device *, u32 *, u8 *, u8 *, u32) get_rxfh_context;
    int (*)(struct net_device *, const u32 *, const u8 *, const u8, u32 *, bool) set_rxfh_context;
    void (*)(struct net_device *, struct ethtool_channels *) get_channels;
    int (*)(struct net_device *, struct ethtool_channels *) set_channels;
    int (*)(struct net_device *, struct ethtool_dump *) get_dump_flag;
    int (*)(struct net_device *, struct ethtool_dump *, void *) get_dump_data;
    int (*)(struct net_device *, struct ethtool_dump *) set_dump;
    int (*)(struct net_device *, struct ethtool_ts_info *) get_ts_info;
    int (*)(struct net_device *, struct ethtool_modinfo *) get_module_info;
    int (*)(struct net_device *, struct ethtool_eeprom *, u8 *) get_module_eeprom;
    int (*)(struct net_device *, struct ethtool_eee *) get_eee;
    int (*)(struct net_device *, struct ethtool_eee *) set_eee;
    int (*)(struct net_device *, const struct ethtool_tunable *, void *) get_tunable;
    int (*)(struct net_device *, const struct ethtool_tunable *, const void *) set_tunable;
    int (*)(struct net_device *, u32, struct ethtool_coalesce *) get_per_queue_coalesce;
    int (*)(struct net_device *, u32, struct ethtool_coalesce *) set_per_queue_coalesce;
    int (*)(struct net_device *, struct ethtool_link_ksettings *) get_link_ksettings;
    int (*)(struct net_device *, const struct ethtool_link_ksettings *) set_link_ksettings;
    void (*)(struct net_device *, struct ethtool_fec_stats *) get_fec_stats;
    int (*)(struct net_device *, struct ethtool_fecparam *) get_fecparam;
    int (*)(struct net_device *, struct ethtool_fecparam *) set_fecparam;
    void (*)(struct net_device *, struct ethtool_stats *, u64 *) get_ethtool_phy_stats;
    int (*)(struct net_device *, const struct ethtool_tunable *, void *) get_phy_tunable;
    int (*)(struct net_device *, const struct ethtool_tunable *, const void *) set_phy_tunable;
    int (*)(struct net_device *, const struct ethtool_module_eeprom *, struct netlink_ext_ack *) get_module_eeprom_by_page;
    void (*)(struct net_device *, struct ethtool_eth_phy_stats *) get_eth_phy_stats;
    void (*)(struct net_device *, struct ethtool_eth_mac_stats *) get_eth_mac_stats;
    void (*)(struct net_device *, struct ethtool_eth_ctrl_stats *) get_eth_ctrl_stats;
    void (*)(struct net_device *, struct ethtool_rmon_stats *, const struct ethtool_rmon_hist_range * *) get_rmon_stats;
    int (*)(struct net_device *, struct ethtool_module_power_mode_params *, struct netlink_ext_ack *) get_module_power_mode;
    int (*)(struct net_device *, const struct ethtool_module_power_mode_params *, struct netlink_ext_ack *) set_module_power_mode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct ethtool_ops {
    u32 cap_link_lanes_supported;
    u32 supported_coalesce_params;
    u32 supported_ring_params;
    void (*)(struct net_device *, struct ethtool_drvinfo *) get_drvinfo;
    int (*)(struct net_device *) get_regs_len;
    void (*)(struct net_device *, struct ethtool_regs *, void *) get_regs;
    void (*)(struct net_device *, struct ethtool_wolinfo *) get_wol;
    int (*)(struct net_device *, struct ethtool_wolinfo *) set_wol;
    u32 (*)(struct net_device *) get_msglevel;
    void (*)(struct net_device *, u32) set_msglevel;
    int (*)(struct net_device *) nway_reset;
    u32 (*)(struct net_device *) get_link;
    int (*)(struct net_device *, struct ethtool_link_ext_state_info *) get_link_ext_state;
    void (*)(struct net_device *, struct ethtool_link_ext_stats *) get_link_ext_stats;
    int (*)(struct net_device *) get_eeprom_len;
    int (*)(struct net_device *, struct ethtool_eeprom *, u8 *) get_eeprom;
    int (*)(struct net_device *, struct ethtool_eeprom *, u8 *) set_eeprom;
    int (*)(struct net_device *, struct ethtool_coalesce *, struct kernel_ethtool_coalesce *, struct netlink_ext_ack *) get_coalesce;
    int (*)(struct net_device *, struct ethtool_coalesce *, struct kernel_ethtool_coalesce *, struct netlink_ext_ack *) set_coalesce;
    void (*)(struct net_device *, struct ethtool_ringparam *, struct kernel_ethtool_ringparam *, struct netlink_ext_ack *) get_ringparam;
    int (*)(struct net_device *, struct ethtool_ringparam *, struct kernel_ethtool_ringparam *, struct netlink_ext_ack *) set_ringparam;
    void (*)(struct net_device *, struct ethtool_pause_stats *) get_pause_stats;
    void (*)(struct net_device *, struct ethtool_pauseparam *) get_pauseparam;
    int (*)(struct net_device *, struct ethtool_pauseparam *) set_pauseparam;
    void (*)(struct net_device *, struct ethtool_test *, u64 *) self_test;
    void (*)(struct net_device *, u32, u8 *) get_strings;
    int (*)(struct net_device *, enum ethtool_phys_id_state) set_phys_id;
    void (*)(struct net_device *, struct ethtool_stats *, u64 *) get_ethtool_stats;
    int (*)(struct net_device *) begin;
    void (*)(struct net_device *) complete;
    u32 (*)(struct net_device *) get_priv_flags;
    int (*)(struct net_device *, u32) set_priv_flags;
    int (*)(struct net_device *, int) get_sset_count;
    int (*)(struct net_device *, struct ethtool_rxnfc *, u32 *) get_rxnfc;
    int (*)(struct net_device *, struct ethtool_rxnfc *) set_rxnfc;
    int (*)(struct net_device *, struct ethtool_flash *) flash_device;
    int (*)(struct net_device *, u32 *) reset;
    u32 (*)(struct net_device *) get_rxfh_key_size;
    u32 (*)(struct net_device *) get_rxfh_indir_size;
    int (*)(struct net_device *, u32 *, u8 *, u8 *) get_rxfh;
    int (*)(struct net_device *, const u32 *, const u8 *, const u8) set_rxfh;
    int (*)(struct net_device *, u32 *, u8 *, u8 *, u32) get_rxfh_context;
    int (*)(struct net_device *, const u32 *, const u8 *, const u8, u32 *, bool) set_rxfh_context;
    void (*)(struct net_device *, struct ethtool_channels *) get_channels;
    int (*)(struct net_device *, struct ethtool_channels *) set_channels;
    int (*)(struct net_device *, struct ethtool_dump *) get_dump_flag;
    int (*)(struct net_device *, struct ethtool_dump *, void *) get_dump_data;
    int (*)(struct net_device *, struct ethtool_dump *) set_dump;
    int (*)(struct net_device *, struct ethtool_ts_info *) get_ts_info;
    int (*)(struct net_device *, struct ethtool_modinfo *) get_module_info;
    int (*)(struct net_device *, struct ethtool_eeprom *, u8 *) get_module_eeprom;
    int (*)(struct net_device *, struct ethtool_eee *) get_eee;
    int (*)(struct net_device *, struct ethtool_eee *) set_eee;
    int (*)(struct net_device *, const struct ethtool_tunable *, void *) get_tunable;
    int (*)(struct net_device *, const struct ethtool_tunable *, const void *) set_tunable;
    int (*)(struct net_device *, u32, struct ethtool_coalesce *) get_per_queue_coalesce;
    int (*)(struct net_device *, u32, struct ethtool_coalesce *) set_per_queue_coalesce;
    int (*)(struct net_device *, struct ethtool_link_ksettings *) get_link_ksettings;
    int (*)(struct net_device *, const struct ethtool_link_ksettings *) set_link_ksettings;
    void (*)(struct net_device *, struct ethtool_fec_stats *) get_fec_stats;
    int (*)(struct net_device *, struct ethtool_fecparam *) get_fecparam;
    int (*)(struct net_device *, struct ethtool_fecparam *) set_fecparam;
    void (*)(struct net_device *, struct ethtool_stats *, u64 *) get_ethtool_phy_stats;
    int (*)(struct net_device *, const struct ethtool_tunable *, void *) get_phy_tunable;
    int (*)(struct net_device *, const struct ethtool_tunable *, const void *) set_phy_tunable;
    int (*)(struct net_device *, const struct ethtool_module_eeprom *, struct netlink_ext_ack *) get_module_eeprom_by_page;
    void (*)(struct net_device *, struct ethtool_eth_phy_stats *) get_eth_phy_stats;
    void (*)(struct net_device *, struct ethtool_eth_mac_stats *) get_eth_mac_stats;
    void (*)(struct net_device *, struct ethtool_eth_ctrl_stats *) get_eth_ctrl_stats;
    void (*)(struct net_device *, struct ethtool_rmon_stats *, const struct ethtool_rmon_hist_range * *) get_rmon_stats;
    int (*)(struct net_device *, struct ethtool_module_power_mode_params *, struct netlink_ext_ack *) get_module_power_mode;
    int (*)(struct net_device *, const struct ethtool_module_power_mode_params *, struct netlink_ext_ack *) set_module_power_mode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct ethtool_ops {
    u32 cap_link_lanes_supported;
    u32 supported_coalesce_params;
    u32 supported_ring_params;
    void (*)(struct net_device *, struct ethtool_drvinfo *) get_drvinfo;
    int (*)(struct net_device *) get_regs_len;
    void (*)(struct net_device *, struct ethtool_regs *, void *) get_regs;
    void (*)(struct net_device *, struct ethtool_wolinfo *) get_wol;
    int (*)(struct net_device *, struct ethtool_wolinfo *) set_wol;
    u32 (*)(struct net_device *) get_msglevel;
    void (*)(struct net_device *, u32) set_msglevel;
    int (*)(struct net_device *) nway_reset;
    u32 (*)(struct net_device *) get_link;
    int (*)(struct net_device *, struct ethtool_link_ext_state_info *) get_link_ext_state;
    void (*)(struct net_device *, struct ethtool_link_ext_stats *) get_link_ext_stats;
    int (*)(struct net_device *) get_eeprom_len;
    int (*)(struct net_device *, struct ethtool_eeprom *, u8 *) get_eeprom;
    int (*)(struct net_device *, struct ethtool_eeprom *, u8 *) set_eeprom;
    int (*)(struct net_device *, struct ethtool_coalesce *, struct kernel_ethtool_coalesce *, struct netlink_ext_ack *) get_coalesce;
    int (*)(struct net_device *, struct ethtool_coalesce *, struct kernel_ethtool_coalesce *, struct netlink_ext_ack *) set_coalesce;
    void (*)(struct net_device *, struct ethtool_ringparam *, struct kernel_ethtool_ringparam *, struct netlink_ext_ack *) get_ringparam;
    int (*)(struct net_device *, struct ethtool_ringparam *, struct kernel_ethtool_ringparam *, struct netlink_ext_ack *) set_ringparam;
    void (*)(struct net_device *, struct ethtool_pause_stats *) get_pause_stats;
    void (*)(struct net_device *, struct ethtool_pauseparam *) get_pauseparam;
    int (*)(struct net_device *, struct ethtool_pauseparam *) set_pauseparam;
    void (*)(struct net_device *, struct ethtool_test *, u64 *) self_test;
    void (*)(struct net_device *, u32, u8 *) get_strings;
    int (*)(struct net_device *, enum ethtool_phys_id_state) set_phys_id;
    void (*)(struct net_device *, struct ethtool_stats *, u64 *) get_ethtool_stats;
    int (*)(struct net_device *) begin;
    void (*)(struct net_device *) complete;
    u32 (*)(struct net_device *) get_priv_flags;
    int (*)(struct net_device *, u32) set_priv_flags;
    int (*)(struct net_device *, int) get_sset_count;
    int (*)(struct net_device *, struct ethtool_rxnfc *, u32 *) get_rxnfc;
    int (*)(struct net_device *, struct ethtool_rxnfc *) set_rxnfc;
    int (*)(struct net_device *, struct ethtool_flash *) flash_device;
    int (*)(struct net_device *, u32 *) reset;
    u32 (*)(struct net_device *) get_rxfh_key_size;
    u32 (*)(struct net_device *) get_rxfh_indir_size;
    int (*)(struct net_device *, u32 *, u8 *, u8 *) get_rxfh;
    int (*)(struct net_device *, const u32 *, const u8 *, const u8) set_rxfh;
    int (*)(struct net_device *, u32 *, u8 *, u8 *, u32) get_rxfh_context;
    int (*)(struct net_device *, const u32 *, const u8 *, const u8, u32 *, bool) set_rxfh_context;
    void (*)(struct net_device *, struct ethtool_channels *) get_channels;
    int (*)(struct net_device *, struct ethtool_channels *) set_channels;
    int (*)(struct net_device *, struct ethtool_dump *) get_dump_flag;
    int (*)(struct net_device *, struct ethtool_dump *, void *) get_dump_data;
    int (*)(struct net_device *, struct ethtool_dump *) set_dump;
    int (*)(struct net_device *, struct ethtool_ts_info *) get_ts_info;
    int (*)(struct net_device *, struct ethtool_modinfo *) get_module_info;
    int (*)(struct net_device *, struct ethtool_eeprom *, u8 *) get_module_eeprom;
    int (*)(struct net_device *, struct ethtool_eee *) get_eee;
    int (*)(struct net_device *, struct ethtool_eee *) set_eee;
    int (*)(struct net_device *, const struct ethtool_tunable *, void *) get_tunable;
    int (*)(struct net_device *, const struct ethtool_tunable *, const void *) set_tunable;
    int (*)(struct net_device *, u32, struct ethtool_coalesce *) get_per_queue_coalesce;
    int (*)(struct net_device *, u32, struct ethtool_coalesce *) set_per_queue_coalesce;
    int (*)(struct net_device *, struct ethtool_link_ksettings *) get_link_ksettings;
    int (*)(struct net_device *, const struct ethtool_link_ksettings *) set_link_ksettings;
    void (*)(struct net_device *, struct ethtool_fec_stats *) get_fec_stats;
    int (*)(struct net_device *, struct ethtool_fecparam *) get_fecparam;
    int (*)(struct net_device *, struct ethtool_fecparam *) set_fecparam;
    void (*)(struct net_device *, struct ethtool_stats *, u64 *) get_ethtool_phy_stats;
    int (*)(struct net_device *, const struct ethtool_tunable *, void *) get_phy_tunable;
    int (*)(struct net_device *, const struct ethtool_tunable *, const void *) set_phy_tunable;
    int (*)(struct net_device *, const struct ethtool_module_eeprom *, struct netlink_ext_ack *) get_module_eeprom_by_page;
    void (*)(struct net_device *, struct ethtool_eth_phy_stats *) get_eth_phy_stats;
    void (*)(struct net_device *, struct ethtool_eth_mac_stats *) get_eth_mac_stats;
    void (*)(struct net_device *, struct ethtool_eth_ctrl_stats *) get_eth_ctrl_stats;
    void (*)(struct net_device *, struct ethtool_rmon_stats *, const struct ethtool_rmon_hist_range * *) get_rmon_stats;
    int (*)(struct net_device *, struct ethtool_module_power_mode_params *, struct netlink_ext_ack *) get_module_power_mode;
    int (*)(struct net_device *, const struct ethtool_module_power_mode_params *, struct netlink_ext_ack *) set_module_power_mode;
    int (*)(struct net_device *, struct ethtool_mm_state *) get_mm;
    int (*)(struct net_device *, struct ethtool_mm_cfg *, struct netlink_ext_ack *) set_mm;
    void (*)(struct net_device *, struct ethtool_mm_stats *) get_mm_stats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct ethtool_ops {
    u32 cap_link_lanes_supported;
    u32 cap_rss_ctx_supported;
    u32 cap_rss_sym_xor_supported;
    u32 supported_coalesce_params;
    u32 supported_ring_params;
    void (*)(struct net_device *, struct ethtool_drvinfo *) get_drvinfo;
    int (*)(struct net_device *) get_regs_len;
    void (*)(struct net_device *, struct ethtool_regs *, void *) get_regs;
    void (*)(struct net_device *, struct ethtool_wolinfo *) get_wol;
    int (*)(struct net_device *, struct ethtool_wolinfo *) set_wol;
    u32 (*)(struct net_device *) get_msglevel;
    void (*)(struct net_device *, u32) set_msglevel;
    int (*)(struct net_device *) nway_reset;
    u32 (*)(struct net_device *) get_link;
    int (*)(struct net_device *, struct ethtool_link_ext_state_info *) get_link_ext_state;
    void (*)(struct net_device *, struct ethtool_link_ext_stats *) get_link_ext_stats;
    int (*)(struct net_device *) get_eeprom_len;
    int (*)(struct net_device *, struct ethtool_eeprom *, u8 *) get_eeprom;
    int (*)(struct net_device *, struct ethtool_eeprom *, u8 *) set_eeprom;
    int (*)(struct net_device *, struct ethtool_coalesce *, struct kernel_ethtool_coalesce *, struct netlink_ext_ack *) get_coalesce;
    int (*)(struct net_device *, struct ethtool_coalesce *, struct kernel_ethtool_coalesce *, struct netlink_ext_ack *) set_coalesce;
    void (*)(struct net_device *, struct ethtool_ringparam *, struct kernel_ethtool_ringparam *, struct netlink_ext_ack *) get_ringparam;
    int (*)(struct net_device *, struct ethtool_ringparam *, struct kernel_ethtool_ringparam *, struct netlink_ext_ack *) set_ringparam;
    void (*)(struct net_device *, struct ethtool_pause_stats *) get_pause_stats;
    void (*)(struct net_device *, struct ethtool_pauseparam *) get_pauseparam;
    int (*)(struct net_device *, struct ethtool_pauseparam *) set_pauseparam;
    void (*)(struct net_device *, struct ethtool_test *, u64 *) self_test;
    void (*)(struct net_device *, u32, u8 *) get_strings;
    int (*)(struct net_device *, enum ethtool_phys_id_state) set_phys_id;
    void (*)(struct net_device *, struct ethtool_stats *, u64 *) get_ethtool_stats;
    int (*)(struct net_device *) begin;
    void (*)(struct net_device *) complete;
    u32 (*)(struct net_device *) get_priv_flags;
    int (*)(struct net_device *, u32) set_priv_flags;
    int (*)(struct net_device *, int) get_sset_count;
    int (*)(struct net_device *, struct ethtool_rxnfc *, u32 *) get_rxnfc;
    int (*)(struct net_device *, struct ethtool_rxnfc *) set_rxnfc;
    int (*)(struct net_device *, struct ethtool_flash *) flash_device;
    int (*)(struct net_device *, u32 *) reset;
    u32 (*)(struct net_device *) get_rxfh_key_size;
    u32 (*)(struct net_device *) get_rxfh_indir_size;
    int (*)(struct net_device *, struct ethtool_rxfh_param *) get_rxfh;
    int (*)(struct net_device *, struct ethtool_rxfh_param *, struct netlink_ext_ack *) set_rxfh;
    void (*)(struct net_device *, struct ethtool_channels *) get_channels;
    int (*)(struct net_device *, struct ethtool_channels *) set_channels;
    int (*)(struct net_device *, struct ethtool_dump *) get_dump_flag;
    int (*)(struct net_device *, struct ethtool_dump *, void *) get_dump_data;
    int (*)(struct net_device *, struct ethtool_dump *) set_dump;
    int (*)(struct net_device *, struct ethtool_ts_info *) get_ts_info;
    int (*)(struct net_device *, struct ethtool_modinfo *) get_module_info;
    int (*)(struct net_device *, struct ethtool_eeprom *, u8 *) get_module_eeprom;
    int (*)(struct net_device *, struct ethtool_eee *) get_eee;
    int (*)(struct net_device *, struct ethtool_eee *) set_eee;
    int (*)(struct net_device *, const struct ethtool_tunable *, void *) get_tunable;
    int (*)(struct net_device *, const struct ethtool_tunable *, const void *) set_tunable;
    int (*)(struct net_device *, u32, struct ethtool_coalesce *) get_per_queue_coalesce;
    int (*)(struct net_device *, u32, struct ethtool_coalesce *) set_per_queue_coalesce;
    int (*)(struct net_device *, struct ethtool_link_ksettings *) get_link_ksettings;
    int (*)(struct net_device *, const struct ethtool_link_ksettings *) set_link_ksettings;
    void (*)(struct net_device *, struct ethtool_fec_stats *) get_fec_stats;
    int (*)(struct net_device *, struct ethtool_fecparam *) get_fecparam;
    int (*)(struct net_device *, struct ethtool_fecparam *) set_fecparam;
    void (*)(struct net_device *, struct ethtool_stats *, u64 *) get_ethtool_phy_stats;
    int (*)(struct net_device *, const struct ethtool_tunable *, void *) get_phy_tunable;
    int (*)(struct net_device *, const struct ethtool_tunable *, const void *) set_phy_tunable;
    int (*)(struct net_device *, const struct ethtool_module_eeprom *, struct netlink_ext_ack *) get_module_eeprom_by_page;
    void (*)(struct net_device *, struct ethtool_eth_phy_stats *) get_eth_phy_stats;
    void (*)(struct net_device *, struct ethtool_eth_mac_stats *) get_eth_mac_stats;
    void (*)(struct net_device *, struct ethtool_eth_ctrl_stats *) get_eth_ctrl_stats;
    void (*)(struct net_device *, struct ethtool_rmon_stats *, const struct ethtool_rmon_hist_range * *) get_rmon_stats;
    int (*)(struct net_device *, struct ethtool_module_power_mode_params *, struct netlink_ext_ack *) get_module_power_mode;
    int (*)(struct net_device *, const struct ethtool_module_power_mode_params *, struct netlink_ext_ack *) set_module_power_mode;
    int (*)(struct net_device *, struct ethtool_mm_state *) get_mm;
    int (*)(struct net_device *, struct ethtool_mm_cfg *, struct netlink_ext_ack *) set_mm;
    void (*)(struct net_device *, struct ethtool_mm_stats *) get_mm_stats;
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
struct ethtool_ops {
    void (*)(struct net_device *, struct ethtool_drvinfo *) get_drvinfo;
    int (*)(struct net_device *) get_regs_len;
    void (*)(struct net_device *, struct ethtool_regs *, void *) get_regs;
    void (*)(struct net_device *, struct ethtool_wolinfo *) get_wol;
    int (*)(struct net_device *, struct ethtool_wolinfo *) set_wol;
    u32 (*)(struct net_device *) get_msglevel;
    void (*)(struct net_device *, u32) set_msglevel;
    int (*)(struct net_device *) nway_reset;
    u32 (*)(struct net_device *) get_link;
    int (*)(struct net_device *) get_eeprom_len;
    int (*)(struct net_device *, struct ethtool_eeprom *, u8 *) get_eeprom;
    int (*)(struct net_device *, struct ethtool_eeprom *, u8 *) set_eeprom;
    int (*)(struct net_device *, struct ethtool_coalesce *) get_coalesce;
    int (*)(struct net_device *, struct ethtool_coalesce *) set_coalesce;
    void (*)(struct net_device *, struct ethtool_ringparam *) get_ringparam;
    int (*)(struct net_device *, struct ethtool_ringparam *) set_ringparam;
    void (*)(struct net_device *, struct ethtool_pauseparam *) get_pauseparam;
    int (*)(struct net_device *, struct ethtool_pauseparam *) set_pauseparam;
    void (*)(struct net_device *, struct ethtool_test *, u64 *) self_test;
    void (*)(struct net_device *, u32, u8 *) get_strings;
    int (*)(struct net_device *, enum ethtool_phys_id_state) set_phys_id;
    void (*)(struct net_device *, struct ethtool_stats *, u64 *) get_ethtool_stats;
    int (*)(struct net_device *) begin;
    void (*)(struct net_device *) complete;
    u32 (*)(struct net_device *) get_priv_flags;
    int (*)(struct net_device *, u32) set_priv_flags;
    int (*)(struct net_device *, int) get_sset_count;
    int (*)(struct net_device *, struct ethtool_rxnfc *, u32 *) get_rxnfc;
    int (*)(struct net_device *, struct ethtool_rxnfc *) set_rxnfc;
    int (*)(struct net_device *, struct ethtool_flash *) flash_device;
    int (*)(struct net_device *, u32 *) reset;
    u32 (*)(struct net_device *) get_rxfh_key_size;
    u32 (*)(struct net_device *) get_rxfh_indir_size;
    int (*)(struct net_device *, u32 *, u8 *, u8 *) get_rxfh;
    int (*)(struct net_device *, const u32 *, const u8 *, const u8) set_rxfh;
    int (*)(struct net_device *, u32 *, u8 *, u8 *, u32) get_rxfh_context;
    int (*)(struct net_device *, const u32 *, const u8 *, const u8, u32 *, bool) set_rxfh_context;
    void (*)(struct net_device *, struct ethtool_channels *) get_channels;
    int (*)(struct net_device *, struct ethtool_channels *) set_channels;
    int (*)(struct net_device *, struct ethtool_dump *) get_dump_flag;
    int (*)(struct net_device *, struct ethtool_dump *, void *) get_dump_data;
    int (*)(struct net_device *, struct ethtool_dump *) set_dump;
    int (*)(struct net_device *, struct ethtool_ts_info *) get_ts_info;
    int (*)(struct net_device *, struct ethtool_modinfo *) get_module_info;
    int (*)(struct net_device *, struct ethtool_eeprom *, u8 *) get_module_eeprom;
    int (*)(struct net_device *, struct ethtool_eee *) get_eee;
    int (*)(struct net_device *, struct ethtool_eee *) set_eee;
    int (*)(struct net_device *, const struct ethtool_tunable *, void *) get_tunable;
    int (*)(struct net_device *, const struct ethtool_tunable *, const void *) set_tunable;
    int (*)(struct net_device *, u32, struct ethtool_coalesce *) get_per_queue_coalesce;
    int (*)(struct net_device *, u32, struct ethtool_coalesce *) set_per_queue_coalesce;
    int (*)(struct net_device *, struct ethtool_link_ksettings *) get_link_ksettings;
    int (*)(struct net_device *, const struct ethtool_link_ksettings *) set_link_ksettings;
    int (*)(struct net_device *, struct ethtool_fecparam *) get_fecparam;
    int (*)(struct net_device *, struct ethtool_fecparam *) set_fecparam;
    void (*)(struct net_device *, struct ethtool_stats *, u64 *) get_ethtool_phy_stats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct ethtool_ops {
    void (*)(struct net_device *, struct ethtool_drvinfo *) get_drvinfo;
    int (*)(struct net_device *) get_regs_len;
    void (*)(struct net_device *, struct ethtool_regs *, void *) get_regs;
    void (*)(struct net_device *, struct ethtool_wolinfo *) get_wol;
    int (*)(struct net_device *, struct ethtool_wolinfo *) set_wol;
    u32 (*)(struct net_device *) get_msglevel;
    void (*)(struct net_device *, u32) set_msglevel;
    int (*)(struct net_device *) nway_reset;
    u32 (*)(struct net_device *) get_link;
    int (*)(struct net_device *) get_eeprom_len;
    int (*)(struct net_device *, struct ethtool_eeprom *, u8 *) get_eeprom;
    int (*)(struct net_device *, struct ethtool_eeprom *, u8 *) set_eeprom;
    int (*)(struct net_device *, struct ethtool_coalesce *) get_coalesce;
    int (*)(struct net_device *, struct ethtool_coalesce *) set_coalesce;
    void (*)(struct net_device *, struct ethtool_ringparam *) get_ringparam;
    int (*)(struct net_device *, struct ethtool_ringparam *) set_ringparam;
    void (*)(struct net_device *, struct ethtool_pauseparam *) get_pauseparam;
    int (*)(struct net_device *, struct ethtool_pauseparam *) set_pauseparam;
    void (*)(struct net_device *, struct ethtool_test *, u64 *) self_test;
    void (*)(struct net_device *, u32, u8 *) get_strings;
    int (*)(struct net_device *, enum ethtool_phys_id_state) set_phys_id;
    void (*)(struct net_device *, struct ethtool_stats *, u64 *) get_ethtool_stats;
    int (*)(struct net_device *) begin;
    void (*)(struct net_device *) complete;
    u32 (*)(struct net_device *) get_priv_flags;
    int (*)(struct net_device *, u32) set_priv_flags;
    int (*)(struct net_device *, int) get_sset_count;
    int (*)(struct net_device *, struct ethtool_rxnfc *, u32 *) get_rxnfc;
    int (*)(struct net_device *, struct ethtool_rxnfc *) set_rxnfc;
    int (*)(struct net_device *, struct ethtool_flash *) flash_device;
    int (*)(struct net_device *, u32 *) reset;
    u32 (*)(struct net_device *) get_rxfh_key_size;
    u32 (*)(struct net_device *) get_rxfh_indir_size;
    int (*)(struct net_device *, u32 *, u8 *, u8 *) get_rxfh;
    int (*)(struct net_device *, const u32 *, const u8 *, const u8) set_rxfh;
    int (*)(struct net_device *, u32 *, u8 *, u8 *, u32) get_rxfh_context;
    int (*)(struct net_device *, const u32 *, const u8 *, const u8, u32 *, bool) set_rxfh_context;
    void (*)(struct net_device *, struct ethtool_channels *) get_channels;
    int (*)(struct net_device *, struct ethtool_channels *) set_channels;
    int (*)(struct net_device *, struct ethtool_dump *) get_dump_flag;
    int (*)(struct net_device *, struct ethtool_dump *, void *) get_dump_data;
    int (*)(struct net_device *, struct ethtool_dump *) set_dump;
    int (*)(struct net_device *, struct ethtool_ts_info *) get_ts_info;
    int (*)(struct net_device *, struct ethtool_modinfo *) get_module_info;
    int (*)(struct net_device *, struct ethtool_eeprom *, u8 *) get_module_eeprom;
    int (*)(struct net_device *, struct ethtool_eee *) get_eee;
    int (*)(struct net_device *, struct ethtool_eee *) set_eee;
    int (*)(struct net_device *, const struct ethtool_tunable *, void *) get_tunable;
    int (*)(struct net_device *, const struct ethtool_tunable *, const void *) set_tunable;
    int (*)(struct net_device *, u32, struct ethtool_coalesce *) get_per_queue_coalesce;
    int (*)(struct net_device *, u32, struct ethtool_coalesce *) set_per_queue_coalesce;
    int (*)(struct net_device *, struct ethtool_link_ksettings *) get_link_ksettings;
    int (*)(struct net_device *, const struct ethtool_link_ksettings *) set_link_ksettings;
    int (*)(struct net_device *, struct ethtool_fecparam *) get_fecparam;
    int (*)(struct net_device *, struct ethtool_fecparam *) set_fecparam;
    void (*)(struct net_device *, struct ethtool_stats *, u64 *) get_ethtool_phy_stats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct ethtool_ops {
    void (*)(struct net_device *, struct ethtool_drvinfo *) get_drvinfo;
    int (*)(struct net_device *) get_regs_len;
    void (*)(struct net_device *, struct ethtool_regs *, void *) get_regs;
    void (*)(struct net_device *, struct ethtool_wolinfo *) get_wol;
    int (*)(struct net_device *, struct ethtool_wolinfo *) set_wol;
    u32 (*)(struct net_device *) get_msglevel;
    void (*)(struct net_device *, u32) set_msglevel;
    int (*)(struct net_device *) nway_reset;
    u32 (*)(struct net_device *) get_link;
    int (*)(struct net_device *) get_eeprom_len;
    int (*)(struct net_device *, struct ethtool_eeprom *, u8 *) get_eeprom;
    int (*)(struct net_device *, struct ethtool_eeprom *, u8 *) set_eeprom;
    int (*)(struct net_device *, struct ethtool_coalesce *) get_coalesce;
    int (*)(struct net_device *, struct ethtool_coalesce *) set_coalesce;
    void (*)(struct net_device *, struct ethtool_ringparam *) get_ringparam;
    int (*)(struct net_device *, struct ethtool_ringparam *) set_ringparam;
    void (*)(struct net_device *, struct ethtool_pauseparam *) get_pauseparam;
    int (*)(struct net_device *, struct ethtool_pauseparam *) set_pauseparam;
    void (*)(struct net_device *, struct ethtool_test *, u64 *) self_test;
    void (*)(struct net_device *, u32, u8 *) get_strings;
    int (*)(struct net_device *, enum ethtool_phys_id_state) set_phys_id;
    void (*)(struct net_device *, struct ethtool_stats *, u64 *) get_ethtool_stats;
    int (*)(struct net_device *) begin;
    void (*)(struct net_device *) complete;
    u32 (*)(struct net_device *) get_priv_flags;
    int (*)(struct net_device *, u32) set_priv_flags;
    int (*)(struct net_device *, int) get_sset_count;
    int (*)(struct net_device *, struct ethtool_rxnfc *, u32 *) get_rxnfc;
    int (*)(struct net_device *, struct ethtool_rxnfc *) set_rxnfc;
    int (*)(struct net_device *, struct ethtool_flash *) flash_device;
    int (*)(struct net_device *, u32 *) reset;
    u32 (*)(struct net_device *) get_rxfh_key_size;
    u32 (*)(struct net_device *) get_rxfh_indir_size;
    int (*)(struct net_device *, u32 *, u8 *, u8 *) get_rxfh;
    int (*)(struct net_device *, const u32 *, const u8 *, const u8) set_rxfh;
    int (*)(struct net_device *, u32 *, u8 *, u8 *, u32) get_rxfh_context;
    int (*)(struct net_device *, const u32 *, const u8 *, const u8, u32 *, bool) set_rxfh_context;
    void (*)(struct net_device *, struct ethtool_channels *) get_channels;
    int (*)(struct net_device *, struct ethtool_channels *) set_channels;
    int (*)(struct net_device *, struct ethtool_dump *) get_dump_flag;
    int (*)(struct net_device *, struct ethtool_dump *, void *) get_dump_data;
    int (*)(struct net_device *, struct ethtool_dump *) set_dump;
    int (*)(struct net_device *, struct ethtool_ts_info *) get_ts_info;
    int (*)(struct net_device *, struct ethtool_modinfo *) get_module_info;
    int (*)(struct net_device *, struct ethtool_eeprom *, u8 *) get_module_eeprom;
    int (*)(struct net_device *, struct ethtool_eee *) get_eee;
    int (*)(struct net_device *, struct ethtool_eee *) set_eee;
    int (*)(struct net_device *, const struct ethtool_tunable *, void *) get_tunable;
    int (*)(struct net_device *, const struct ethtool_tunable *, const void *) set_tunable;
    int (*)(struct net_device *, u32, struct ethtool_coalesce *) get_per_queue_coalesce;
    int (*)(struct net_device *, u32, struct ethtool_coalesce *) set_per_queue_coalesce;
    int (*)(struct net_device *, struct ethtool_link_ksettings *) get_link_ksettings;
    int (*)(struct net_device *, const struct ethtool_link_ksettings *) set_link_ksettings;
    int (*)(struct net_device *, struct ethtool_fecparam *) get_fecparam;
    int (*)(struct net_device *, struct ethtool_fecparam *) set_fecparam;
    void (*)(struct net_device *, struct ethtool_stats *, u64 *) get_ethtool_phy_stats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct ethtool_ops {
    void (*)(struct net_device *, struct ethtool_drvinfo *) get_drvinfo;
    int (*)(struct net_device *) get_regs_len;
    void (*)(struct net_device *, struct ethtool_regs *, void *) get_regs;
    void (*)(struct net_device *, struct ethtool_wolinfo *) get_wol;
    int (*)(struct net_device *, struct ethtool_wolinfo *) set_wol;
    u32 (*)(struct net_device *) get_msglevel;
    void (*)(struct net_device *, u32) set_msglevel;
    int (*)(struct net_device *) nway_reset;
    u32 (*)(struct net_device *) get_link;
    int (*)(struct net_device *) get_eeprom_len;
    int (*)(struct net_device *, struct ethtool_eeprom *, u8 *) get_eeprom;
    int (*)(struct net_device *, struct ethtool_eeprom *, u8 *) set_eeprom;
    int (*)(struct net_device *, struct ethtool_coalesce *) get_coalesce;
    int (*)(struct net_device *, struct ethtool_coalesce *) set_coalesce;
    void (*)(struct net_device *, struct ethtool_ringparam *) get_ringparam;
    int (*)(struct net_device *, struct ethtool_ringparam *) set_ringparam;
    void (*)(struct net_device *, struct ethtool_pauseparam *) get_pauseparam;
    int (*)(struct net_device *, struct ethtool_pauseparam *) set_pauseparam;
    void (*)(struct net_device *, struct ethtool_test *, u64 *) self_test;
    void (*)(struct net_device *, u32, u8 *) get_strings;
    int (*)(struct net_device *, enum ethtool_phys_id_state) set_phys_id;
    void (*)(struct net_device *, struct ethtool_stats *, u64 *) get_ethtool_stats;
    int (*)(struct net_device *) begin;
    void (*)(struct net_device *) complete;
    u32 (*)(struct net_device *) get_priv_flags;
    int (*)(struct net_device *, u32) set_priv_flags;
    int (*)(struct net_device *, int) get_sset_count;
    int (*)(struct net_device *, struct ethtool_rxnfc *, u32 *) get_rxnfc;
    int (*)(struct net_device *, struct ethtool_rxnfc *) set_rxnfc;
    int (*)(struct net_device *, struct ethtool_flash *) flash_device;
    int (*)(struct net_device *, u32 *) reset;
    u32 (*)(struct net_device *) get_rxfh_key_size;
    u32 (*)(struct net_device *) get_rxfh_indir_size;
    int (*)(struct net_device *, u32 *, u8 *, u8 *) get_rxfh;
    int (*)(struct net_device *, const u32 *, const u8 *, const u8) set_rxfh;
    int (*)(struct net_device *, u32 *, u8 *, u8 *, u32) get_rxfh_context;
    int (*)(struct net_device *, const u32 *, const u8 *, const u8, u32 *, bool) set_rxfh_context;
    void (*)(struct net_device *, struct ethtool_channels *) get_channels;
    int (*)(struct net_device *, struct ethtool_channels *) set_channels;
    int (*)(struct net_device *, struct ethtool_dump *) get_dump_flag;
    int (*)(struct net_device *, struct ethtool_dump *, void *) get_dump_data;
    int (*)(struct net_device *, struct ethtool_dump *) set_dump;
    int (*)(struct net_device *, struct ethtool_ts_info *) get_ts_info;
    int (*)(struct net_device *, struct ethtool_modinfo *) get_module_info;
    int (*)(struct net_device *, struct ethtool_eeprom *, u8 *) get_module_eeprom;
    int (*)(struct net_device *, struct ethtool_eee *) get_eee;
    int (*)(struct net_device *, struct ethtool_eee *) set_eee;
    int (*)(struct net_device *, const struct ethtool_tunable *, void *) get_tunable;
    int (*)(struct net_device *, const struct ethtool_tunable *, const void *) set_tunable;
    int (*)(struct net_device *, u32, struct ethtool_coalesce *) get_per_queue_coalesce;
    int (*)(struct net_device *, u32, struct ethtool_coalesce *) set_per_queue_coalesce;
    int (*)(struct net_device *, struct ethtool_link_ksettings *) get_link_ksettings;
    int (*)(struct net_device *, const struct ethtool_link_ksettings *) set_link_ksettings;
    int (*)(struct net_device *, struct ethtool_fecparam *) get_fecparam;
    int (*)(struct net_device *, struct ethtool_fecparam *) set_fecparam;
    void (*)(struct net_device *, struct ethtool_stats *, u64 *) get_ethtool_phy_stats;
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
struct ethtool_ops {
    void (*)(struct net_device *, struct ethtool_drvinfo *) get_drvinfo;
    int (*)(struct net_device *) get_regs_len;
    void (*)(struct net_device *, struct ethtool_regs *, void *) get_regs;
    void (*)(struct net_device *, struct ethtool_wolinfo *) get_wol;
    int (*)(struct net_device *, struct ethtool_wolinfo *) set_wol;
    u32 (*)(struct net_device *) get_msglevel;
    void (*)(struct net_device *, u32) set_msglevel;
    int (*)(struct net_device *) nway_reset;
    u32 (*)(struct net_device *) get_link;
    int (*)(struct net_device *) get_eeprom_len;
    int (*)(struct net_device *, struct ethtool_eeprom *, u8 *) get_eeprom;
    int (*)(struct net_device *, struct ethtool_eeprom *, u8 *) set_eeprom;
    int (*)(struct net_device *, struct ethtool_coalesce *) get_coalesce;
    int (*)(struct net_device *, struct ethtool_coalesce *) set_coalesce;
    void (*)(struct net_device *, struct ethtool_ringparam *) get_ringparam;
    int (*)(struct net_device *, struct ethtool_ringparam *) set_ringparam;
    void (*)(struct net_device *, struct ethtool_pauseparam *) get_pauseparam;
    int (*)(struct net_device *, struct ethtool_pauseparam *) set_pauseparam;
    void (*)(struct net_device *, struct ethtool_test *, u64 *) self_test;
    void (*)(struct net_device *, u32, u8 *) get_strings;
    int (*)(struct net_device *, enum ethtool_phys_id_state) set_phys_id;
    void (*)(struct net_device *, struct ethtool_stats *, u64 *) get_ethtool_stats;
    int (*)(struct net_device *) begin;
    void (*)(struct net_device *) complete;
    u32 (*)(struct net_device *) get_priv_flags;
    int (*)(struct net_device *, u32) set_priv_flags;
    int (*)(struct net_device *, int) get_sset_count;
    int (*)(struct net_device *, struct ethtool_rxnfc *, u32 *) get_rxnfc;
    int (*)(struct net_device *, struct ethtool_rxnfc *) set_rxnfc;
    int (*)(struct net_device *, struct ethtool_flash *) flash_device;
    int (*)(struct net_device *, u32 *) reset;
    u32 (*)(struct net_device *) get_rxfh_key_size;
    u32 (*)(struct net_device *) get_rxfh_indir_size;
    int (*)(struct net_device *, u32 *, u8 *, u8 *) get_rxfh;
    int (*)(struct net_device *, const u32 *, const u8 *, const u8) set_rxfh;
    int (*)(struct net_device *, u32 *, u8 *, u8 *, u32) get_rxfh_context;
    int (*)(struct net_device *, const u32 *, const u8 *, const u8, u32 *, bool) set_rxfh_context;
    void (*)(struct net_device *, struct ethtool_channels *) get_channels;
    int (*)(struct net_device *, struct ethtool_channels *) set_channels;
    int (*)(struct net_device *, struct ethtool_dump *) get_dump_flag;
    int (*)(struct net_device *, struct ethtool_dump *, void *) get_dump_data;
    int (*)(struct net_device *, struct ethtool_dump *) set_dump;
    int (*)(struct net_device *, struct ethtool_ts_info *) get_ts_info;
    int (*)(struct net_device *, struct ethtool_modinfo *) get_module_info;
    int (*)(struct net_device *, struct ethtool_eeprom *, u8 *) get_module_eeprom;
    int (*)(struct net_device *, struct ethtool_eee *) get_eee;
    int (*)(struct net_device *, struct ethtool_eee *) set_eee;
    int (*)(struct net_device *, const struct ethtool_tunable *, void *) get_tunable;
    int (*)(struct net_device *, const struct ethtool_tunable *, const void *) set_tunable;
    int (*)(struct net_device *, u32, struct ethtool_coalesce *) get_per_queue_coalesce;
    int (*)(struct net_device *, u32, struct ethtool_coalesce *) set_per_queue_coalesce;
    int (*)(struct net_device *, struct ethtool_link_ksettings *) get_link_ksettings;
    int (*)(struct net_device *, const struct ethtool_link_ksettings *) set_link_ksettings;
    int (*)(struct net_device *, struct ethtool_fecparam *) get_fecparam;
    int (*)(struct net_device *, struct ethtool_fecparam *) set_fecparam;
    void (*)(struct net_device *, struct ethtool_stats *, u64 *) get_ethtool_phy_stats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct ethtool_ops {
    void (*)(struct net_device *, struct ethtool_drvinfo *) get_drvinfo;
    int (*)(struct net_device *) get_regs_len;
    void (*)(struct net_device *, struct ethtool_regs *, void *) get_regs;
    void (*)(struct net_device *, struct ethtool_wolinfo *) get_wol;
    int (*)(struct net_device *, struct ethtool_wolinfo *) set_wol;
    u32 (*)(struct net_device *) get_msglevel;
    void (*)(struct net_device *, u32) set_msglevel;
    int (*)(struct net_device *) nway_reset;
    u32 (*)(struct net_device *) get_link;
    int (*)(struct net_device *) get_eeprom_len;
    int (*)(struct net_device *, struct ethtool_eeprom *, u8 *) get_eeprom;
    int (*)(struct net_device *, struct ethtool_eeprom *, u8 *) set_eeprom;
    int (*)(struct net_device *, struct ethtool_coalesce *) get_coalesce;
    int (*)(struct net_device *, struct ethtool_coalesce *) set_coalesce;
    void (*)(struct net_device *, struct ethtool_ringparam *) get_ringparam;
    int (*)(struct net_device *, struct ethtool_ringparam *) set_ringparam;
    void (*)(struct net_device *, struct ethtool_pauseparam *) get_pauseparam;
    int (*)(struct net_device *, struct ethtool_pauseparam *) set_pauseparam;
    void (*)(struct net_device *, struct ethtool_test *, u64 *) self_test;
    void (*)(struct net_device *, u32, u8 *) get_strings;
    int (*)(struct net_device *, enum ethtool_phys_id_state) set_phys_id;
    void (*)(struct net_device *, struct ethtool_stats *, u64 *) get_ethtool_stats;
    int (*)(struct net_device *) begin;
    void (*)(struct net_device *) complete;
    u32 (*)(struct net_device *) get_priv_flags;
    int (*)(struct net_device *, u32) set_priv_flags;
    int (*)(struct net_device *, int) get_sset_count;
    int (*)(struct net_device *, struct ethtool_rxnfc *, u32 *) get_rxnfc;
    int (*)(struct net_device *, struct ethtool_rxnfc *) set_rxnfc;
    int (*)(struct net_device *, struct ethtool_flash *) flash_device;
    int (*)(struct net_device *, u32 *) reset;
    u32 (*)(struct net_device *) get_rxfh_key_size;
    u32 (*)(struct net_device *) get_rxfh_indir_size;
    int (*)(struct net_device *, u32 *, u8 *, u8 *) get_rxfh;
    int (*)(struct net_device *, const u32 *, const u8 *, const u8) set_rxfh;
    int (*)(struct net_device *, u32 *, u8 *, u8 *, u32) get_rxfh_context;
    int (*)(struct net_device *, const u32 *, const u8 *, const u8, u32 *, bool) set_rxfh_context;
    void (*)(struct net_device *, struct ethtool_channels *) get_channels;
    int (*)(struct net_device *, struct ethtool_channels *) set_channels;
    int (*)(struct net_device *, struct ethtool_dump *) get_dump_flag;
    int (*)(struct net_device *, struct ethtool_dump *, void *) get_dump_data;
    int (*)(struct net_device *, struct ethtool_dump *) set_dump;
    int (*)(struct net_device *, struct ethtool_ts_info *) get_ts_info;
    int (*)(struct net_device *, struct ethtool_modinfo *) get_module_info;
    int (*)(struct net_device *, struct ethtool_eeprom *, u8 *) get_module_eeprom;
    int (*)(struct net_device *, struct ethtool_eee *) get_eee;
    int (*)(struct net_device *, struct ethtool_eee *) set_eee;
    int (*)(struct net_device *, const struct ethtool_tunable *, void *) get_tunable;
    int (*)(struct net_device *, const struct ethtool_tunable *, const void *) set_tunable;
    int (*)(struct net_device *, u32, struct ethtool_coalesce *) get_per_queue_coalesce;
    int (*)(struct net_device *, u32, struct ethtool_coalesce *) set_per_queue_coalesce;
    int (*)(struct net_device *, struct ethtool_link_ksettings *) get_link_ksettings;
    int (*)(struct net_device *, const struct ethtool_link_ksettings *) set_link_ksettings;
    int (*)(struct net_device *, struct ethtool_fecparam *) get_fecparam;
    int (*)(struct net_device *, struct ethtool_fecparam *) set_fecparam;
    void (*)(struct net_device *, struct ethtool_stats *, u64 *) get_ethtool_phy_stats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct ethtool_ops {
    void (*)(struct net_device *, struct ethtool_drvinfo *) get_drvinfo;
    int (*)(struct net_device *) get_regs_len;
    void (*)(struct net_device *, struct ethtool_regs *, void *) get_regs;
    void (*)(struct net_device *, struct ethtool_wolinfo *) get_wol;
    int (*)(struct net_device *, struct ethtool_wolinfo *) set_wol;
    u32 (*)(struct net_device *) get_msglevel;
    void (*)(struct net_device *, u32) set_msglevel;
    int (*)(struct net_device *) nway_reset;
    u32 (*)(struct net_device *) get_link;
    int (*)(struct net_device *) get_eeprom_len;
    int (*)(struct net_device *, struct ethtool_eeprom *, u8 *) get_eeprom;
    int (*)(struct net_device *, struct ethtool_eeprom *, u8 *) set_eeprom;
    int (*)(struct net_device *, struct ethtool_coalesce *) get_coalesce;
    int (*)(struct net_device *, struct ethtool_coalesce *) set_coalesce;
    void (*)(struct net_device *, struct ethtool_ringparam *) get_ringparam;
    int (*)(struct net_device *, struct ethtool_ringparam *) set_ringparam;
    void (*)(struct net_device *, struct ethtool_pauseparam *) get_pauseparam;
    int (*)(struct net_device *, struct ethtool_pauseparam *) set_pauseparam;
    void (*)(struct net_device *, struct ethtool_test *, u64 *) self_test;
    void (*)(struct net_device *, u32, u8 *) get_strings;
    int (*)(struct net_device *, enum ethtool_phys_id_state) set_phys_id;
    void (*)(struct net_device *, struct ethtool_stats *, u64 *) get_ethtool_stats;
    int (*)(struct net_device *) begin;
    void (*)(struct net_device *) complete;
    u32 (*)(struct net_device *) get_priv_flags;
    int (*)(struct net_device *, u32) set_priv_flags;
    int (*)(struct net_device *, int) get_sset_count;
    int (*)(struct net_device *, struct ethtool_rxnfc *, u32 *) get_rxnfc;
    int (*)(struct net_device *, struct ethtool_rxnfc *) set_rxnfc;
    int (*)(struct net_device *, struct ethtool_flash *) flash_device;
    int (*)(struct net_device *, u32 *) reset;
    u32 (*)(struct net_device *) get_rxfh_key_size;
    u32 (*)(struct net_device *) get_rxfh_indir_size;
    int (*)(struct net_device *, u32 *, u8 *, u8 *) get_rxfh;
    int (*)(struct net_device *, const u32 *, const u8 *, const u8) set_rxfh;
    int (*)(struct net_device *, u32 *, u8 *, u8 *, u32) get_rxfh_context;
    int (*)(struct net_device *, const u32 *, const u8 *, const u8, u32 *, bool) set_rxfh_context;
    void (*)(struct net_device *, struct ethtool_channels *) get_channels;
    int (*)(struct net_device *, struct ethtool_channels *) set_channels;
    int (*)(struct net_device *, struct ethtool_dump *) get_dump_flag;
    int (*)(struct net_device *, struct ethtool_dump *, void *) get_dump_data;
    int (*)(struct net_device *, struct ethtool_dump *) set_dump;
    int (*)(struct net_device *, struct ethtool_ts_info *) get_ts_info;
    int (*)(struct net_device *, struct ethtool_modinfo *) get_module_info;
    int (*)(struct net_device *, struct ethtool_eeprom *, u8 *) get_module_eeprom;
    int (*)(struct net_device *, struct ethtool_eee *) get_eee;
    int (*)(struct net_device *, struct ethtool_eee *) set_eee;
    int (*)(struct net_device *, const struct ethtool_tunable *, void *) get_tunable;
    int (*)(struct net_device *, const struct ethtool_tunable *, const void *) set_tunable;
    int (*)(struct net_device *, u32, struct ethtool_coalesce *) get_per_queue_coalesce;
    int (*)(struct net_device *, u32, struct ethtool_coalesce *) set_per_queue_coalesce;
    int (*)(struct net_device *, struct ethtool_link_ksettings *) get_link_ksettings;
    int (*)(struct net_device *, const struct ethtool_link_ksettings *) set_link_ksettings;
    int (*)(struct net_device *, struct ethtool_fecparam *) get_fecparam;
    int (*)(struct net_device *, struct ethtool_fecparam *) set_fecparam;
    void (*)(struct net_device *, struct ethtool_stats *, u64 *) get_ethtool_phy_stats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct ethtool_ops {
    void (*)(struct net_device *, struct ethtool_drvinfo *) get_drvinfo;
    int (*)(struct net_device *) get_regs_len;
    void (*)(struct net_device *, struct ethtool_regs *, void *) get_regs;
    void (*)(struct net_device *, struct ethtool_wolinfo *) get_wol;
    int (*)(struct net_device *, struct ethtool_wolinfo *) set_wol;
    u32 (*)(struct net_device *) get_msglevel;
    void (*)(struct net_device *, u32) set_msglevel;
    int (*)(struct net_device *) nway_reset;
    u32 (*)(struct net_device *) get_link;
    int (*)(struct net_device *) get_eeprom_len;
    int (*)(struct net_device *, struct ethtool_eeprom *, u8 *) get_eeprom;
    int (*)(struct net_device *, struct ethtool_eeprom *, u8 *) set_eeprom;
    int (*)(struct net_device *, struct ethtool_coalesce *) get_coalesce;
    int (*)(struct net_device *, struct ethtool_coalesce *) set_coalesce;
    void (*)(struct net_device *, struct ethtool_ringparam *) get_ringparam;
    int (*)(struct net_device *, struct ethtool_ringparam *) set_ringparam;
    void (*)(struct net_device *, struct ethtool_pauseparam *) get_pauseparam;
    int (*)(struct net_device *, struct ethtool_pauseparam *) set_pauseparam;
    void (*)(struct net_device *, struct ethtool_test *, u64 *) self_test;
    void (*)(struct net_device *, u32, u8 *) get_strings;
    int (*)(struct net_device *, enum ethtool_phys_id_state) set_phys_id;
    void (*)(struct net_device *, struct ethtool_stats *, u64 *) get_ethtool_stats;
    int (*)(struct net_device *) begin;
    void (*)(struct net_device *) complete;
    u32 (*)(struct net_device *) get_priv_flags;
    int (*)(struct net_device *, u32) set_priv_flags;
    int (*)(struct net_device *, int) get_sset_count;
    int (*)(struct net_device *, struct ethtool_rxnfc *, u32 *) get_rxnfc;
    int (*)(struct net_device *, struct ethtool_rxnfc *) set_rxnfc;
    int (*)(struct net_device *, struct ethtool_flash *) flash_device;
    int (*)(struct net_device *, u32 *) reset;
    u32 (*)(struct net_device *) get_rxfh_key_size;
    u32 (*)(struct net_device *) get_rxfh_indir_size;
    int (*)(struct net_device *, u32 *, u8 *, u8 *) get_rxfh;
    int (*)(struct net_device *, const u32 *, const u8 *, const u8) set_rxfh;
    int (*)(struct net_device *, u32 *, u8 *, u8 *, u32) get_rxfh_context;
    int (*)(struct net_device *, const u32 *, const u8 *, const u8, u32 *, bool) set_rxfh_context;
    void (*)(struct net_device *, struct ethtool_channels *) get_channels;
    int (*)(struct net_device *, struct ethtool_channels *) set_channels;
    int (*)(struct net_device *, struct ethtool_dump *) get_dump_flag;
    int (*)(struct net_device *, struct ethtool_dump *, void *) get_dump_data;
    int (*)(struct net_device *, struct ethtool_dump *) set_dump;
    int (*)(struct net_device *, struct ethtool_ts_info *) get_ts_info;
    int (*)(struct net_device *, struct ethtool_modinfo *) get_module_info;
    int (*)(struct net_device *, struct ethtool_eeprom *, u8 *) get_module_eeprom;
    int (*)(struct net_device *, struct ethtool_eee *) get_eee;
    int (*)(struct net_device *, struct ethtool_eee *) set_eee;
    int (*)(struct net_device *, const struct ethtool_tunable *, void *) get_tunable;
    int (*)(struct net_device *, const struct ethtool_tunable *, const void *) set_tunable;
    int (*)(struct net_device *, u32, struct ethtool_coalesce *) get_per_queue_coalesce;
    int (*)(struct net_device *, u32, struct ethtool_coalesce *) set_per_queue_coalesce;
    int (*)(struct net_device *, struct ethtool_link_ksettings *) get_link_ksettings;
    int (*)(struct net_device *, const struct ethtool_link_ksettings *) set_link_ksettings;
    int (*)(struct net_device *, struct ethtool_fecparam *) get_fecparam;
    int (*)(struct net_device *, struct ethtool_fecparam *) set_fecparam;
    void (*)(struct net_device *, struct ethtool_stats *, u64 *) get_ethtool_phy_stats;
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
<code>int (*)(struct net_device *, u32, struct ethtool_coalesce *) get_per_queue_coalesce</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct net_device *, u32, struct ethtool_coalesce *) set_per_queue_coalesce</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct net_device *, struct ethtool_link_ksettings *) get_link_ksettings</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct net_device *, const struct ethtool_link_ksettings *) set_link_ksettings</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct net_device *, struct ethtool_fecparam *) get_fecparam</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct net_device *, struct ethtool_fecparam *) set_fecparam</code>
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
<code>int (*)(struct net_device *, u32 *, u8 *, u8 *, u32) get_rxfh_context</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct net_device *, const u32 *, const u8 *, const u8, u32 *, bool) set_rxfh_context</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct net_device *, struct ethtool_stats *, u64 *) get_ethtool_phy_stats</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>int (*)(struct net_device *, struct ethtool_cmd *) get_settings</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct net_device *, struct ethtool_cmd *) set_settings</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
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
<code>u32 supported_coalesce_params</code>
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
<code>int (*)(struct net_device *, struct ethtool_link_ext_state_info *) get_link_ext_state</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct net_device *, struct ethtool_pause_stats *) get_pause_stats</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct net_device *, const struct ethtool_tunable *, void *) get_phy_tunable</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct net_device *, const struct ethtool_tunable *, const void *) set_phy_tunable</code>
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
<code>u32 cap_link_lanes_supported</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct net_device *, struct ethtool_fec_stats *) get_fec_stats</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct net_device *, const struct ethtool_module_eeprom *, struct netlink_ext_ack *) get_module_eeprom_by_page</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct net_device *, struct ethtool_eth_phy_stats *) get_eth_phy_stats</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct net_device *, struct ethtool_eth_mac_stats *) get_eth_mac_stats</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct net_device *, struct ethtool_eth_ctrl_stats *) get_eth_ctrl_stats</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct net_device *, struct ethtool_rmon_stats *, const struct ethtool_rmon_hist_range * *) get_rmon_stats</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>int (*)(struct net_device *, struct ethtool_coalesce *) get_coalesce</code> ➡️ <code>int (*)(struct net_device *, struct ethtool_coalesce *, struct kernel_ethtool_coalesce *, struct netlink_ext_ack *) get_coalesce</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct net_device *, struct ethtool_coalesce *) set_coalesce</code> ➡️ <code>int (*)(struct net_device *, struct ethtool_coalesce *, struct kernel_ethtool_coalesce *, struct netlink_ext_ack *) set_coalesce</code>
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
<code>u32 supported_ring_params</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct net_device *, struct ethtool_module_power_mode_params *, struct netlink_ext_ack *) get_module_power_mode</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct net_device *, const struct ethtool_module_power_mode_params *, struct netlink_ext_ack *) set_module_power_mode</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct net_device *, struct ethtool_ringparam *) get_ringparam</code> ➡️ <code>void (*)(struct net_device *, struct ethtool_ringparam *, struct kernel_ethtool_ringparam *, struct netlink_ext_ack *) get_ringparam</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct net_device *, struct ethtool_ringparam *) set_ringparam</code> ➡️ <code>int (*)(struct net_device *, struct ethtool_ringparam *, struct kernel_ethtool_ringparam *, struct netlink_ext_ack *) set_ringparam</code>
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
<code>void (*)(struct net_device *, struct ethtool_link_ext_stats *) get_link_ext_stats</code>
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
<code>int (*)(struct net_device *, struct ethtool_mm_state *) get_mm</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct net_device *, struct ethtool_mm_cfg *, struct netlink_ext_ack *) set_mm</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct net_device *, struct ethtool_mm_stats *) get_mm_stats</code>
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
<code>u32 cap_rss_ctx_supported</code>
</li>
<li>
<b>Field added. </b>
<code>u32 cap_rss_sym_xor_supported</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct net_device *, u32 *, u8 *, u8 *, u32) get_rxfh_context</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct net_device *, const u32 *, const u8 *, const u8, u32 *, bool) set_rxfh_context</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct net_device *, u32 *, u8 *, u8 *) get_rxfh</code> ➡️ <code>int (*)(struct net_device *, struct ethtool_rxfh_param *) get_rxfh</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct net_device *, const u32 *, const u8 *, const u8) set_rxfh</code> ➡️ <code>int (*)(struct net_device *, struct ethtool_rxfh_param *, struct netlink_ext_ack *) set_rxfh</code>
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
