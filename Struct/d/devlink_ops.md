# Struct: <code>devlink_ops</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct devlink_ops {
    int (*)(struct devlink_port *, enum devlink_port_type) port_type_set;
    int (*)(struct devlink *, unsigned int, unsigned int) port_split;
    int (*)(struct devlink *, unsigned int) port_unsplit;
    int (*)(struct devlink *, unsigned int, u16, struct devlink_sb_pool_info *) sb_pool_get;
    int (*)(struct devlink *, unsigned int, u16, u32, enum devlink_sb_threshold_type) sb_pool_set;
    int (*)(struct devlink_port *, unsigned int, u16, u32 *) sb_port_pool_get;
    int (*)(struct devlink_port *, unsigned int, u16, u32) sb_port_pool_set;
    int (*)(struct devlink_port *, unsigned int, u16, enum devlink_sb_pool_type, u16 *, u32 *) sb_tc_pool_bind_get;
    int (*)(struct devlink_port *, unsigned int, u16, enum devlink_sb_pool_type, u16, u32) sb_tc_pool_bind_set;
    int (*)(struct devlink *, unsigned int) sb_occ_snapshot;
    int (*)(struct devlink *, unsigned int) sb_occ_max_clear;
    int (*)(struct devlink_port *, unsigned int, u16, u32 *, u32 *) sb_occ_port_pool_get;
    int (*)(struct devlink_port *, unsigned int, u16, enum devlink_sb_pool_type, u32 *, u32 *) sb_occ_tc_port_bind_get;
    int (*)(struct devlink *, u16 *) eswitch_mode_get;
    int (*)(struct devlink *, u16) eswitch_mode_set;
    int (*)(struct devlink *, u8 *) eswitch_inline_mode_get;
    int (*)(struct devlink *, u8) eswitch_inline_mode_set;
    int (*)(struct devlink *, u8 *) eswitch_encap_mode_get;
    int (*)(struct devlink *, u8) eswitch_encap_mode_set;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct devlink_ops {
    int (*)(struct devlink_port *, enum devlink_port_type) port_type_set;
    int (*)(struct devlink *, unsigned int, unsigned int) port_split;
    int (*)(struct devlink *, unsigned int) port_unsplit;
    int (*)(struct devlink *, unsigned int, u16, struct devlink_sb_pool_info *) sb_pool_get;
    int (*)(struct devlink *, unsigned int, u16, u32, enum devlink_sb_threshold_type) sb_pool_set;
    int (*)(struct devlink_port *, unsigned int, u16, u32 *) sb_port_pool_get;
    int (*)(struct devlink_port *, unsigned int, u16, u32) sb_port_pool_set;
    int (*)(struct devlink_port *, unsigned int, u16, enum devlink_sb_pool_type, u16 *, u32 *) sb_tc_pool_bind_get;
    int (*)(struct devlink_port *, unsigned int, u16, enum devlink_sb_pool_type, u16, u32) sb_tc_pool_bind_set;
    int (*)(struct devlink *, unsigned int) sb_occ_snapshot;
    int (*)(struct devlink *, unsigned int) sb_occ_max_clear;
    int (*)(struct devlink_port *, unsigned int, u16, u32 *, u32 *) sb_occ_port_pool_get;
    int (*)(struct devlink_port *, unsigned int, u16, enum devlink_sb_pool_type, u32 *, u32 *) sb_occ_tc_port_bind_get;
    int (*)(struct devlink *, u16 *) eswitch_mode_get;
    int (*)(struct devlink *, u16) eswitch_mode_set;
    int (*)(struct devlink *, u8 *) eswitch_inline_mode_get;
    int (*)(struct devlink *, u8) eswitch_inline_mode_set;
    int (*)(struct devlink *, u8 *) eswitch_encap_mode_get;
    int (*)(struct devlink *, u8) eswitch_encap_mode_set;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct devlink_ops {
    int (*)(struct devlink *, struct netlink_ext_ack *) reload;
    int (*)(struct devlink_port *, enum devlink_port_type) port_type_set;
    int (*)(struct devlink *, unsigned int, unsigned int, struct netlink_ext_ack *) port_split;
    int (*)(struct devlink *, unsigned int, struct netlink_ext_ack *) port_unsplit;
    int (*)(struct devlink *, unsigned int, u16, struct devlink_sb_pool_info *) sb_pool_get;
    int (*)(struct devlink *, unsigned int, u16, u32, enum devlink_sb_threshold_type) sb_pool_set;
    int (*)(struct devlink_port *, unsigned int, u16, u32 *) sb_port_pool_get;
    int (*)(struct devlink_port *, unsigned int, u16, u32) sb_port_pool_set;
    int (*)(struct devlink_port *, unsigned int, u16, enum devlink_sb_pool_type, u16 *, u32 *) sb_tc_pool_bind_get;
    int (*)(struct devlink_port *, unsigned int, u16, enum devlink_sb_pool_type, u16, u32) sb_tc_pool_bind_set;
    int (*)(struct devlink *, unsigned int) sb_occ_snapshot;
    int (*)(struct devlink *, unsigned int) sb_occ_max_clear;
    int (*)(struct devlink_port *, unsigned int, u16, u32 *, u32 *) sb_occ_port_pool_get;
    int (*)(struct devlink_port *, unsigned int, u16, enum devlink_sb_pool_type, u32 *, u32 *) sb_occ_tc_port_bind_get;
    int (*)(struct devlink *, u16 *) eswitch_mode_get;
    int (*)(struct devlink *, u16) eswitch_mode_set;
    int (*)(struct devlink *, u8 *) eswitch_inline_mode_get;
    int (*)(struct devlink *, u8) eswitch_inline_mode_set;
    int (*)(struct devlink *, u8 *) eswitch_encap_mode_get;
    int (*)(struct devlink *, u8) eswitch_encap_mode_set;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct devlink_ops {
    int (*)(struct devlink *, struct netlink_ext_ack *) reload;
    int (*)(struct devlink_port *, enum devlink_port_type) port_type_set;
    int (*)(struct devlink *, unsigned int, unsigned int, struct netlink_ext_ack *) port_split;
    int (*)(struct devlink *, unsigned int, struct netlink_ext_ack *) port_unsplit;
    int (*)(struct devlink *, unsigned int, u16, struct devlink_sb_pool_info *) sb_pool_get;
    int (*)(struct devlink *, unsigned int, u16, u32, enum devlink_sb_threshold_type) sb_pool_set;
    int (*)(struct devlink_port *, unsigned int, u16, u32 *) sb_port_pool_get;
    int (*)(struct devlink_port *, unsigned int, u16, u32) sb_port_pool_set;
    int (*)(struct devlink_port *, unsigned int, u16, enum devlink_sb_pool_type, u16 *, u32 *) sb_tc_pool_bind_get;
    int (*)(struct devlink_port *, unsigned int, u16, enum devlink_sb_pool_type, u16, u32) sb_tc_pool_bind_set;
    int (*)(struct devlink *, unsigned int) sb_occ_snapshot;
    int (*)(struct devlink *, unsigned int) sb_occ_max_clear;
    int (*)(struct devlink_port *, unsigned int, u16, u32 *, u32 *) sb_occ_port_pool_get;
    int (*)(struct devlink_port *, unsigned int, u16, enum devlink_sb_pool_type, u32 *, u32 *) sb_occ_tc_port_bind_get;
    int (*)(struct devlink *, u16 *) eswitch_mode_get;
    int (*)(struct devlink *, u16, struct netlink_ext_ack *) eswitch_mode_set;
    int (*)(struct devlink *, u8 *) eswitch_inline_mode_get;
    int (*)(struct devlink *, u8, struct netlink_ext_ack *) eswitch_inline_mode_set;
    int (*)(struct devlink *, u8 *) eswitch_encap_mode_get;
    int (*)(struct devlink *, u8, struct netlink_ext_ack *) eswitch_encap_mode_set;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct devlink_ops {
    int (*)(struct devlink *, struct netlink_ext_ack *) reload;
    int (*)(struct devlink_port *, enum devlink_port_type) port_type_set;
    int (*)(struct devlink *, unsigned int, unsigned int, struct netlink_ext_ack *) port_split;
    int (*)(struct devlink *, unsigned int, struct netlink_ext_ack *) port_unsplit;
    int (*)(struct devlink *, unsigned int, u16, struct devlink_sb_pool_info *) sb_pool_get;
    int (*)(struct devlink *, unsigned int, u16, u32, enum devlink_sb_threshold_type, struct netlink_ext_ack *) sb_pool_set;
    int (*)(struct devlink_port *, unsigned int, u16, u32 *) sb_port_pool_get;
    int (*)(struct devlink_port *, unsigned int, u16, u32, struct netlink_ext_ack *) sb_port_pool_set;
    int (*)(struct devlink_port *, unsigned int, u16, enum devlink_sb_pool_type, u16 *, u32 *) sb_tc_pool_bind_get;
    int (*)(struct devlink_port *, unsigned int, u16, enum devlink_sb_pool_type, u16, u32, struct netlink_ext_ack *) sb_tc_pool_bind_set;
    int (*)(struct devlink *, unsigned int) sb_occ_snapshot;
    int (*)(struct devlink *, unsigned int) sb_occ_max_clear;
    int (*)(struct devlink_port *, unsigned int, u16, u32 *, u32 *) sb_occ_port_pool_get;
    int (*)(struct devlink_port *, unsigned int, u16, enum devlink_sb_pool_type, u32 *, u32 *) sb_occ_tc_port_bind_get;
    int (*)(struct devlink *, u16 *) eswitch_mode_get;
    int (*)(struct devlink *, u16, struct netlink_ext_ack *) eswitch_mode_set;
    int (*)(struct devlink *, u8 *) eswitch_inline_mode_get;
    int (*)(struct devlink *, u8, struct netlink_ext_ack *) eswitch_inline_mode_set;
    int (*)(struct devlink *, enum devlink_eswitch_encap_mode *) eswitch_encap_mode_get;
    int (*)(struct devlink *, enum devlink_eswitch_encap_mode, struct netlink_ext_ack *) eswitch_encap_mode_set;
    int (*)(struct devlink *, struct devlink_info_req *, struct netlink_ext_ack *) info_get;
    int (*)(struct devlink *, const char *, const char *, struct netlink_ext_ack *) flash_update;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct devlink_ops {
    int (*)(struct devlink *, struct netlink_ext_ack *) reload_down;
    int (*)(struct devlink *, struct netlink_ext_ack *) reload_up;
    int (*)(struct devlink_port *, enum devlink_port_type) port_type_set;
    int (*)(struct devlink *, unsigned int, unsigned int, struct netlink_ext_ack *) port_split;
    int (*)(struct devlink *, unsigned int, struct netlink_ext_ack *) port_unsplit;
    int (*)(struct devlink *, unsigned int, u16, struct devlink_sb_pool_info *) sb_pool_get;
    int (*)(struct devlink *, unsigned int, u16, u32, enum devlink_sb_threshold_type, struct netlink_ext_ack *) sb_pool_set;
    int (*)(struct devlink_port *, unsigned int, u16, u32 *) sb_port_pool_get;
    int (*)(struct devlink_port *, unsigned int, u16, u32, struct netlink_ext_ack *) sb_port_pool_set;
    int (*)(struct devlink_port *, unsigned int, u16, enum devlink_sb_pool_type, u16 *, u32 *) sb_tc_pool_bind_get;
    int (*)(struct devlink_port *, unsigned int, u16, enum devlink_sb_pool_type, u16, u32, struct netlink_ext_ack *) sb_tc_pool_bind_set;
    int (*)(struct devlink *, unsigned int) sb_occ_snapshot;
    int (*)(struct devlink *, unsigned int) sb_occ_max_clear;
    int (*)(struct devlink_port *, unsigned int, u16, u32 *, u32 *) sb_occ_port_pool_get;
    int (*)(struct devlink_port *, unsigned int, u16, enum devlink_sb_pool_type, u32 *, u32 *) sb_occ_tc_port_bind_get;
    int (*)(struct devlink *, u16 *) eswitch_mode_get;
    int (*)(struct devlink *, u16, struct netlink_ext_ack *) eswitch_mode_set;
    int (*)(struct devlink *, u8 *) eswitch_inline_mode_get;
    int (*)(struct devlink *, u8, struct netlink_ext_ack *) eswitch_inline_mode_set;
    int (*)(struct devlink *, enum devlink_eswitch_encap_mode *) eswitch_encap_mode_get;
    int (*)(struct devlink *, enum devlink_eswitch_encap_mode, struct netlink_ext_ack *) eswitch_encap_mode_set;
    int (*)(struct devlink *, struct devlink_info_req *, struct netlink_ext_ack *) info_get;
    int (*)(struct devlink *, const char *, const char *, struct netlink_ext_ack *) flash_update;
    int (*)(struct devlink *, const struct devlink_trap *, void *) trap_init;
    void (*)(struct devlink *, const struct devlink_trap *, void *) trap_fini;
    int (*)(struct devlink *, const struct devlink_trap *, enum devlink_trap_action) trap_action_set;
    int (*)(struct devlink *, const struct devlink_trap_group *) trap_group_init;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct devlink_ops {
    int (*)(struct devlink *, bool, struct netlink_ext_ack *) reload_down;
    int (*)(struct devlink *, struct netlink_ext_ack *) reload_up;
    int (*)(struct devlink_port *, enum devlink_port_type) port_type_set;
    int (*)(struct devlink *, unsigned int, unsigned int, struct netlink_ext_ack *) port_split;
    int (*)(struct devlink *, unsigned int, struct netlink_ext_ack *) port_unsplit;
    int (*)(struct devlink *, unsigned int, u16, struct devlink_sb_pool_info *) sb_pool_get;
    int (*)(struct devlink *, unsigned int, u16, u32, enum devlink_sb_threshold_type, struct netlink_ext_ack *) sb_pool_set;
    int (*)(struct devlink_port *, unsigned int, u16, u32 *) sb_port_pool_get;
    int (*)(struct devlink_port *, unsigned int, u16, u32, struct netlink_ext_ack *) sb_port_pool_set;
    int (*)(struct devlink_port *, unsigned int, u16, enum devlink_sb_pool_type, u16 *, u32 *) sb_tc_pool_bind_get;
    int (*)(struct devlink_port *, unsigned int, u16, enum devlink_sb_pool_type, u16, u32, struct netlink_ext_ack *) sb_tc_pool_bind_set;
    int (*)(struct devlink *, unsigned int) sb_occ_snapshot;
    int (*)(struct devlink *, unsigned int) sb_occ_max_clear;
    int (*)(struct devlink_port *, unsigned int, u16, u32 *, u32 *) sb_occ_port_pool_get;
    int (*)(struct devlink_port *, unsigned int, u16, enum devlink_sb_pool_type, u32 *, u32 *) sb_occ_tc_port_bind_get;
    int (*)(struct devlink *, u16 *) eswitch_mode_get;
    int (*)(struct devlink *, u16, struct netlink_ext_ack *) eswitch_mode_set;
    int (*)(struct devlink *, u8 *) eswitch_inline_mode_get;
    int (*)(struct devlink *, u8, struct netlink_ext_ack *) eswitch_inline_mode_set;
    int (*)(struct devlink *, enum devlink_eswitch_encap_mode *) eswitch_encap_mode_get;
    int (*)(struct devlink *, enum devlink_eswitch_encap_mode, struct netlink_ext_ack *) eswitch_encap_mode_set;
    int (*)(struct devlink *, struct devlink_info_req *, struct netlink_ext_ack *) info_get;
    int (*)(struct devlink *, const char *, const char *, struct netlink_ext_ack *) flash_update;
    int (*)(struct devlink *, const struct devlink_trap *, void *) trap_init;
    void (*)(struct devlink *, const struct devlink_trap *, void *) trap_fini;
    int (*)(struct devlink *, const struct devlink_trap *, enum devlink_trap_action) trap_action_set;
    int (*)(struct devlink *, const struct devlink_trap_group *) trap_group_init;
    int (*)(struct devlink *, const struct devlink_trap_group *, const struct devlink_trap_policer *) trap_group_set;
    int (*)(struct devlink *, const struct devlink_trap_policer *) trap_policer_init;
    void (*)(struct devlink *, const struct devlink_trap_policer *) trap_policer_fini;
    int (*)(struct devlink *, const struct devlink_trap_policer *, u64, u64, struct netlink_ext_ack *) trap_policer_set;
    int (*)(struct devlink *, const struct devlink_trap_policer *, u64 *) trap_policer_counter_get;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct devlink_ops {
    u32 supported_flash_update_params;
    long unsigned int reload_actions;
    long unsigned int reload_limits;
    int (*)(struct devlink *, bool, enum devlink_reload_action, enum devlink_reload_limit, struct netlink_ext_ack *) reload_down;
    int (*)(struct devlink *, enum devlink_reload_action, enum devlink_reload_limit, u32 *, struct netlink_ext_ack *) reload_up;
    int (*)(struct devlink_port *, enum devlink_port_type) port_type_set;
    int (*)(struct devlink *, unsigned int, unsigned int, struct netlink_ext_ack *) port_split;
    int (*)(struct devlink *, unsigned int, struct netlink_ext_ack *) port_unsplit;
    int (*)(struct devlink *, unsigned int, u16, struct devlink_sb_pool_info *) sb_pool_get;
    int (*)(struct devlink *, unsigned int, u16, u32, enum devlink_sb_threshold_type, struct netlink_ext_ack *) sb_pool_set;
    int (*)(struct devlink_port *, unsigned int, u16, u32 *) sb_port_pool_get;
    int (*)(struct devlink_port *, unsigned int, u16, u32, struct netlink_ext_ack *) sb_port_pool_set;
    int (*)(struct devlink_port *, unsigned int, u16, enum devlink_sb_pool_type, u16 *, u32 *) sb_tc_pool_bind_get;
    int (*)(struct devlink_port *, unsigned int, u16, enum devlink_sb_pool_type, u16, u32, struct netlink_ext_ack *) sb_tc_pool_bind_set;
    int (*)(struct devlink *, unsigned int) sb_occ_snapshot;
    int (*)(struct devlink *, unsigned int) sb_occ_max_clear;
    int (*)(struct devlink_port *, unsigned int, u16, u32 *, u32 *) sb_occ_port_pool_get;
    int (*)(struct devlink_port *, unsigned int, u16, enum devlink_sb_pool_type, u32 *, u32 *) sb_occ_tc_port_bind_get;
    int (*)(struct devlink *, u16 *) eswitch_mode_get;
    int (*)(struct devlink *, u16, struct netlink_ext_ack *) eswitch_mode_set;
    int (*)(struct devlink *, u8 *) eswitch_inline_mode_get;
    int (*)(struct devlink *, u8, struct netlink_ext_ack *) eswitch_inline_mode_set;
    int (*)(struct devlink *, enum devlink_eswitch_encap_mode *) eswitch_encap_mode_get;
    int (*)(struct devlink *, enum devlink_eswitch_encap_mode, struct netlink_ext_ack *) eswitch_encap_mode_set;
    int (*)(struct devlink *, struct devlink_info_req *, struct netlink_ext_ack *) info_get;
    int (*)(struct devlink *, struct devlink_flash_update_params *, struct netlink_ext_ack *) flash_update;
    int (*)(struct devlink *, const struct devlink_trap *, void *) trap_init;
    void (*)(struct devlink *, const struct devlink_trap *, void *) trap_fini;
    int (*)(struct devlink *, const struct devlink_trap *, enum devlink_trap_action, struct netlink_ext_ack *) trap_action_set;
    int (*)(struct devlink *, const struct devlink_trap_group *) trap_group_init;
    int (*)(struct devlink *, const struct devlink_trap_group *, const struct devlink_trap_policer *, struct netlink_ext_ack *) trap_group_set;
    int (*)(struct devlink *, const struct devlink_trap_group *, enum devlink_trap_action, struct netlink_ext_ack *) trap_group_action_set;
    int (*)(struct devlink *, const struct devlink_trap_policer *) trap_policer_init;
    void (*)(struct devlink *, const struct devlink_trap_policer *) trap_policer_fini;
    int (*)(struct devlink *, const struct devlink_trap_policer *, u64, u64, struct netlink_ext_ack *) trap_policer_set;
    int (*)(struct devlink *, const struct devlink_trap_policer *, u64 *) trap_policer_counter_get;
    int (*)(struct devlink *, struct devlink_port *, u8 *, int *, struct netlink_ext_ack *) port_function_hw_addr_get;
    int (*)(struct devlink *, struct devlink_port *, const u8 *, int, struct netlink_ext_ack *) port_function_hw_addr_set;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct devlink_ops {
    u32 supported_flash_update_params;
    long unsigned int reload_actions;
    long unsigned int reload_limits;
    int (*)(struct devlink *, bool, enum devlink_reload_action, enum devlink_reload_limit, struct netlink_ext_ack *) reload_down;
    int (*)(struct devlink *, enum devlink_reload_action, enum devlink_reload_limit, u32 *, struct netlink_ext_ack *) reload_up;
    int (*)(struct devlink_port *, enum devlink_port_type) port_type_set;
    int (*)(struct devlink *, unsigned int, unsigned int, struct netlink_ext_ack *) port_split;
    int (*)(struct devlink *, unsigned int, struct netlink_ext_ack *) port_unsplit;
    int (*)(struct devlink *, unsigned int, u16, struct devlink_sb_pool_info *) sb_pool_get;
    int (*)(struct devlink *, unsigned int, u16, u32, enum devlink_sb_threshold_type, struct netlink_ext_ack *) sb_pool_set;
    int (*)(struct devlink_port *, unsigned int, u16, u32 *) sb_port_pool_get;
    int (*)(struct devlink_port *, unsigned int, u16, u32, struct netlink_ext_ack *) sb_port_pool_set;
    int (*)(struct devlink_port *, unsigned int, u16, enum devlink_sb_pool_type, u16 *, u32 *) sb_tc_pool_bind_get;
    int (*)(struct devlink_port *, unsigned int, u16, enum devlink_sb_pool_type, u16, u32, struct netlink_ext_ack *) sb_tc_pool_bind_set;
    int (*)(struct devlink *, unsigned int) sb_occ_snapshot;
    int (*)(struct devlink *, unsigned int) sb_occ_max_clear;
    int (*)(struct devlink_port *, unsigned int, u16, u32 *, u32 *) sb_occ_port_pool_get;
    int (*)(struct devlink_port *, unsigned int, u16, enum devlink_sb_pool_type, u32 *, u32 *) sb_occ_tc_port_bind_get;
    int (*)(struct devlink *, u16 *) eswitch_mode_get;
    int (*)(struct devlink *, u16, struct netlink_ext_ack *) eswitch_mode_set;
    int (*)(struct devlink *, u8 *) eswitch_inline_mode_get;
    int (*)(struct devlink *, u8, struct netlink_ext_ack *) eswitch_inline_mode_set;
    int (*)(struct devlink *, enum devlink_eswitch_encap_mode *) eswitch_encap_mode_get;
    int (*)(struct devlink *, enum devlink_eswitch_encap_mode, struct netlink_ext_ack *) eswitch_encap_mode_set;
    int (*)(struct devlink *, struct devlink_info_req *, struct netlink_ext_ack *) info_get;
    int (*)(struct devlink *, struct devlink_flash_update_params *, struct netlink_ext_ack *) flash_update;
    int (*)(struct devlink *, const struct devlink_trap *, void *) trap_init;
    void (*)(struct devlink *, const struct devlink_trap *, void *) trap_fini;
    int (*)(struct devlink *, const struct devlink_trap *, enum devlink_trap_action, struct netlink_ext_ack *) trap_action_set;
    int (*)(struct devlink *, const struct devlink_trap_group *) trap_group_init;
    int (*)(struct devlink *, const struct devlink_trap_group *, const struct devlink_trap_policer *, struct netlink_ext_ack *) trap_group_set;
    int (*)(struct devlink *, const struct devlink_trap_group *, enum devlink_trap_action, struct netlink_ext_ack *) trap_group_action_set;
    int (*)(struct devlink *, const struct devlink_trap_policer *) trap_policer_init;
    void (*)(struct devlink *, const struct devlink_trap_policer *) trap_policer_fini;
    int (*)(struct devlink *, const struct devlink_trap_policer *, u64, u64, struct netlink_ext_ack *) trap_policer_set;
    int (*)(struct devlink *, const struct devlink_trap_policer *, u64 *) trap_policer_counter_get;
    int (*)(struct devlink *, struct devlink_port *, u8 *, int *, struct netlink_ext_ack *) port_function_hw_addr_get;
    int (*)(struct devlink *, struct devlink_port *, const u8 *, int, struct netlink_ext_ack *) port_function_hw_addr_set;
    int (*)(struct devlink *, const struct devlink_port_new_attrs *, struct netlink_ext_ack *, unsigned int *) port_new;
    int (*)(struct devlink *, unsigned int, struct netlink_ext_ack *) port_del;
    int (*)(struct devlink *, struct devlink_port *, enum devlink_port_fn_state *, enum devlink_port_fn_opstate *, struct netlink_ext_ack *) port_fn_state_get;
    int (*)(struct devlink *, struct devlink_port *, enum devlink_port_fn_state, struct netlink_ext_ack *) port_fn_state_set;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct devlink_ops {
    u32 supported_flash_update_params;
    long unsigned int reload_actions;
    long unsigned int reload_limits;
    int (*)(struct devlink *, bool, enum devlink_reload_action, enum devlink_reload_limit, struct netlink_ext_ack *) reload_down;
    int (*)(struct devlink *, enum devlink_reload_action, enum devlink_reload_limit, u32 *, struct netlink_ext_ack *) reload_up;
    int (*)(struct devlink_port *, enum devlink_port_type) port_type_set;
    int (*)(struct devlink *, unsigned int, unsigned int, struct netlink_ext_ack *) port_split;
    int (*)(struct devlink *, unsigned int, struct netlink_ext_ack *) port_unsplit;
    int (*)(struct devlink *, unsigned int, u16, struct devlink_sb_pool_info *) sb_pool_get;
    int (*)(struct devlink *, unsigned int, u16, u32, enum devlink_sb_threshold_type, struct netlink_ext_ack *) sb_pool_set;
    int (*)(struct devlink_port *, unsigned int, u16, u32 *) sb_port_pool_get;
    int (*)(struct devlink_port *, unsigned int, u16, u32, struct netlink_ext_ack *) sb_port_pool_set;
    int (*)(struct devlink_port *, unsigned int, u16, enum devlink_sb_pool_type, u16 *, u32 *) sb_tc_pool_bind_get;
    int (*)(struct devlink_port *, unsigned int, u16, enum devlink_sb_pool_type, u16, u32, struct netlink_ext_ack *) sb_tc_pool_bind_set;
    int (*)(struct devlink *, unsigned int) sb_occ_snapshot;
    int (*)(struct devlink *, unsigned int) sb_occ_max_clear;
    int (*)(struct devlink_port *, unsigned int, u16, u32 *, u32 *) sb_occ_port_pool_get;
    int (*)(struct devlink_port *, unsigned int, u16, enum devlink_sb_pool_type, u32 *, u32 *) sb_occ_tc_port_bind_get;
    int (*)(struct devlink *, u16 *) eswitch_mode_get;
    int (*)(struct devlink *, u16, struct netlink_ext_ack *) eswitch_mode_set;
    int (*)(struct devlink *, u8 *) eswitch_inline_mode_get;
    int (*)(struct devlink *, u8, struct netlink_ext_ack *) eswitch_inline_mode_set;
    int (*)(struct devlink *, enum devlink_eswitch_encap_mode *) eswitch_encap_mode_get;
    int (*)(struct devlink *, enum devlink_eswitch_encap_mode, struct netlink_ext_ack *) eswitch_encap_mode_set;
    int (*)(struct devlink *, struct devlink_info_req *, struct netlink_ext_ack *) info_get;
    int (*)(struct devlink *, struct devlink_flash_update_params *, struct netlink_ext_ack *) flash_update;
    int (*)(struct devlink *, const struct devlink_trap *, void *) trap_init;
    void (*)(struct devlink *, const struct devlink_trap *, void *) trap_fini;
    int (*)(struct devlink *, const struct devlink_trap *, enum devlink_trap_action, struct netlink_ext_ack *) trap_action_set;
    int (*)(struct devlink *, const struct devlink_trap_group *) trap_group_init;
    int (*)(struct devlink *, const struct devlink_trap_group *, const struct devlink_trap_policer *, struct netlink_ext_ack *) trap_group_set;
    int (*)(struct devlink *, const struct devlink_trap_group *, enum devlink_trap_action, struct netlink_ext_ack *) trap_group_action_set;
    int (*)(struct devlink *, const struct devlink_trap *, u64 *) trap_drop_counter_get;
    int (*)(struct devlink *, const struct devlink_trap_policer *) trap_policer_init;
    void (*)(struct devlink *, const struct devlink_trap_policer *) trap_policer_fini;
    int (*)(struct devlink *, const struct devlink_trap_policer *, u64, u64, struct netlink_ext_ack *) trap_policer_set;
    int (*)(struct devlink *, const struct devlink_trap_policer *, u64 *) trap_policer_counter_get;
    int (*)(struct devlink_port *, u8 *, int *, struct netlink_ext_ack *) port_function_hw_addr_get;
    int (*)(struct devlink_port *, const u8 *, int, struct netlink_ext_ack *) port_function_hw_addr_set;
    int (*)(struct devlink *, const struct devlink_port_new_attrs *, struct netlink_ext_ack *, unsigned int *) port_new;
    int (*)(struct devlink *, unsigned int, struct netlink_ext_ack *) port_del;
    int (*)(struct devlink_port *, enum devlink_port_fn_state *, enum devlink_port_fn_opstate *, struct netlink_ext_ack *) port_fn_state_get;
    int (*)(struct devlink_port *, enum devlink_port_fn_state, struct netlink_ext_ack *) port_fn_state_set;
    int (*)(struct devlink_rate *, void *, u64, struct netlink_ext_ack *) rate_leaf_tx_share_set;
    int (*)(struct devlink_rate *, void *, u64, struct netlink_ext_ack *) rate_leaf_tx_max_set;
    int (*)(struct devlink_rate *, void *, u64, struct netlink_ext_ack *) rate_node_tx_share_set;
    int (*)(struct devlink_rate *, void *, u64, struct netlink_ext_ack *) rate_node_tx_max_set;
    int (*)(struct devlink_rate *, void * *, struct netlink_ext_ack *) rate_node_new;
    int (*)(struct devlink_rate *, void *, struct netlink_ext_ack *) rate_node_del;
    int (*)(struct devlink_rate *, struct devlink_rate *, void *, void *, struct netlink_ext_ack *) rate_leaf_parent_set;
    int (*)(struct devlink_rate *, struct devlink_rate *, void *, void *, struct netlink_ext_ack *) rate_node_parent_set;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct devlink_ops {
    u32 supported_flash_update_params;
    long unsigned int reload_actions;
    long unsigned int reload_limits;
    int (*)(struct devlink *, bool, enum devlink_reload_action, enum devlink_reload_limit, struct netlink_ext_ack *) reload_down;
    int (*)(struct devlink *, enum devlink_reload_action, enum devlink_reload_limit, u32 *, struct netlink_ext_ack *) reload_up;
    int (*)(struct devlink_port *, enum devlink_port_type) port_type_set;
    int (*)(struct devlink *, struct devlink_port *, unsigned int, struct netlink_ext_ack *) port_split;
    int (*)(struct devlink *, struct devlink_port *, struct netlink_ext_ack *) port_unsplit;
    int (*)(struct devlink *, unsigned int, u16, struct devlink_sb_pool_info *) sb_pool_get;
    int (*)(struct devlink *, unsigned int, u16, u32, enum devlink_sb_threshold_type, struct netlink_ext_ack *) sb_pool_set;
    int (*)(struct devlink_port *, unsigned int, u16, u32 *) sb_port_pool_get;
    int (*)(struct devlink_port *, unsigned int, u16, u32, struct netlink_ext_ack *) sb_port_pool_set;
    int (*)(struct devlink_port *, unsigned int, u16, enum devlink_sb_pool_type, u16 *, u32 *) sb_tc_pool_bind_get;
    int (*)(struct devlink_port *, unsigned int, u16, enum devlink_sb_pool_type, u16, u32, struct netlink_ext_ack *) sb_tc_pool_bind_set;
    int (*)(struct devlink *, unsigned int) sb_occ_snapshot;
    int (*)(struct devlink *, unsigned int) sb_occ_max_clear;
    int (*)(struct devlink_port *, unsigned int, u16, u32 *, u32 *) sb_occ_port_pool_get;
    int (*)(struct devlink_port *, unsigned int, u16, enum devlink_sb_pool_type, u32 *, u32 *) sb_occ_tc_port_bind_get;
    int (*)(struct devlink *, u16 *) eswitch_mode_get;
    int (*)(struct devlink *, u16, struct netlink_ext_ack *) eswitch_mode_set;
    int (*)(struct devlink *, u8 *) eswitch_inline_mode_get;
    int (*)(struct devlink *, u8, struct netlink_ext_ack *) eswitch_inline_mode_set;
    int (*)(struct devlink *, enum devlink_eswitch_encap_mode *) eswitch_encap_mode_get;
    int (*)(struct devlink *, enum devlink_eswitch_encap_mode, struct netlink_ext_ack *) eswitch_encap_mode_set;
    int (*)(struct devlink *, struct devlink_info_req *, struct netlink_ext_ack *) info_get;
    int (*)(struct devlink *, struct devlink_flash_update_params *, struct netlink_ext_ack *) flash_update;
    int (*)(struct devlink *, const struct devlink_trap *, void *) trap_init;
    void (*)(struct devlink *, const struct devlink_trap *, void *) trap_fini;
    int (*)(struct devlink *, const struct devlink_trap *, enum devlink_trap_action, struct netlink_ext_ack *) trap_action_set;
    int (*)(struct devlink *, const struct devlink_trap_group *) trap_group_init;
    int (*)(struct devlink *, const struct devlink_trap_group *, const struct devlink_trap_policer *, struct netlink_ext_ack *) trap_group_set;
    int (*)(struct devlink *, const struct devlink_trap_group *, enum devlink_trap_action, struct netlink_ext_ack *) trap_group_action_set;
    int (*)(struct devlink *, const struct devlink_trap *, u64 *) trap_drop_counter_get;
    int (*)(struct devlink *, const struct devlink_trap_policer *) trap_policer_init;
    void (*)(struct devlink *, const struct devlink_trap_policer *) trap_policer_fini;
    int (*)(struct devlink *, const struct devlink_trap_policer *, u64, u64, struct netlink_ext_ack *) trap_policer_set;
    int (*)(struct devlink *, const struct devlink_trap_policer *, u64 *) trap_policer_counter_get;
    int (*)(struct devlink_port *, u8 *, int *, struct netlink_ext_ack *) port_function_hw_addr_get;
    int (*)(struct devlink_port *, const u8 *, int, struct netlink_ext_ack *) port_function_hw_addr_set;
    int (*)(struct devlink *, const struct devlink_port_new_attrs *, struct netlink_ext_ack *, unsigned int *) port_new;
    int (*)(struct devlink *, unsigned int, struct netlink_ext_ack *) port_del;
    int (*)(struct devlink_port *, enum devlink_port_fn_state *, enum devlink_port_fn_opstate *, struct netlink_ext_ack *) port_fn_state_get;
    int (*)(struct devlink_port *, enum devlink_port_fn_state, struct netlink_ext_ack *) port_fn_state_set;
    int (*)(struct devlink_rate *, void *, u64, struct netlink_ext_ack *) rate_leaf_tx_share_set;
    int (*)(struct devlink_rate *, void *, u64, struct netlink_ext_ack *) rate_leaf_tx_max_set;
    int (*)(struct devlink_rate *, void *, u64, struct netlink_ext_ack *) rate_node_tx_share_set;
    int (*)(struct devlink_rate *, void *, u64, struct netlink_ext_ack *) rate_node_tx_max_set;
    int (*)(struct devlink_rate *, void * *, struct netlink_ext_ack *) rate_node_new;
    int (*)(struct devlink_rate *, void *, struct netlink_ext_ack *) rate_node_del;
    int (*)(struct devlink_rate *, struct devlink_rate *, void *, void *, struct netlink_ext_ack *) rate_leaf_parent_set;
    int (*)(struct devlink_rate *, struct devlink_rate *, void *, void *, struct netlink_ext_ack *) rate_node_parent_set;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct devlink_ops {
    u32 supported_flash_update_params;
    long unsigned int reload_actions;
    long unsigned int reload_limits;
    int (*)(struct devlink *, bool, enum devlink_reload_action, enum devlink_reload_limit, struct netlink_ext_ack *) reload_down;
    int (*)(struct devlink *, enum devlink_reload_action, enum devlink_reload_limit, u32 *, struct netlink_ext_ack *) reload_up;
    int (*)(struct devlink_port *, enum devlink_port_type) port_type_set;
    int (*)(struct devlink *, struct devlink_port *, unsigned int, struct netlink_ext_ack *) port_split;
    int (*)(struct devlink *, struct devlink_port *, struct netlink_ext_ack *) port_unsplit;
    int (*)(struct devlink *, unsigned int, u16, struct devlink_sb_pool_info *) sb_pool_get;
    int (*)(struct devlink *, unsigned int, u16, u32, enum devlink_sb_threshold_type, struct netlink_ext_ack *) sb_pool_set;
    int (*)(struct devlink_port *, unsigned int, u16, u32 *) sb_port_pool_get;
    int (*)(struct devlink_port *, unsigned int, u16, u32, struct netlink_ext_ack *) sb_port_pool_set;
    int (*)(struct devlink_port *, unsigned int, u16, enum devlink_sb_pool_type, u16 *, u32 *) sb_tc_pool_bind_get;
    int (*)(struct devlink_port *, unsigned int, u16, enum devlink_sb_pool_type, u16, u32, struct netlink_ext_ack *) sb_tc_pool_bind_set;
    int (*)(struct devlink *, unsigned int) sb_occ_snapshot;
    int (*)(struct devlink *, unsigned int) sb_occ_max_clear;
    int (*)(struct devlink_port *, unsigned int, u16, u32 *, u32 *) sb_occ_port_pool_get;
    int (*)(struct devlink_port *, unsigned int, u16, enum devlink_sb_pool_type, u32 *, u32 *) sb_occ_tc_port_bind_get;
    int (*)(struct devlink *, u16 *) eswitch_mode_get;
    int (*)(struct devlink *, u16, struct netlink_ext_ack *) eswitch_mode_set;
    int (*)(struct devlink *, u8 *) eswitch_inline_mode_get;
    int (*)(struct devlink *, u8, struct netlink_ext_ack *) eswitch_inline_mode_set;
    int (*)(struct devlink *, enum devlink_eswitch_encap_mode *) eswitch_encap_mode_get;
    int (*)(struct devlink *, enum devlink_eswitch_encap_mode, struct netlink_ext_ack *) eswitch_encap_mode_set;
    int (*)(struct devlink *, struct devlink_info_req *, struct netlink_ext_ack *) info_get;
    int (*)(struct devlink *, struct devlink_flash_update_params *, struct netlink_ext_ack *) flash_update;
    int (*)(struct devlink *, const struct devlink_trap *, void *) trap_init;
    void (*)(struct devlink *, const struct devlink_trap *, void *) trap_fini;
    int (*)(struct devlink *, const struct devlink_trap *, enum devlink_trap_action, struct netlink_ext_ack *) trap_action_set;
    int (*)(struct devlink *, const struct devlink_trap_group *) trap_group_init;
    int (*)(struct devlink *, const struct devlink_trap_group *, const struct devlink_trap_policer *, struct netlink_ext_ack *) trap_group_set;
    int (*)(struct devlink *, const struct devlink_trap_group *, enum devlink_trap_action, struct netlink_ext_ack *) trap_group_action_set;
    int (*)(struct devlink *, const struct devlink_trap *, u64 *) trap_drop_counter_get;
    int (*)(struct devlink *, const struct devlink_trap_policer *) trap_policer_init;
    void (*)(struct devlink *, const struct devlink_trap_policer *) trap_policer_fini;
    int (*)(struct devlink *, const struct devlink_trap_policer *, u64, u64, struct netlink_ext_ack *) trap_policer_set;
    int (*)(struct devlink *, const struct devlink_trap_policer *, u64 *) trap_policer_counter_get;
    int (*)(struct devlink_port *, u8 *, int *, struct netlink_ext_ack *) port_function_hw_addr_get;
    int (*)(struct devlink_port *, const u8 *, int, struct netlink_ext_ack *) port_function_hw_addr_set;
    int (*)(struct devlink_port *, bool *, struct netlink_ext_ack *) port_fn_roce_get;
    int (*)(struct devlink_port *, bool, struct netlink_ext_ack *) port_fn_roce_set;
    int (*)(struct devlink_port *, bool *, struct netlink_ext_ack *) port_fn_migratable_get;
    int (*)(struct devlink_port *, bool, struct netlink_ext_ack *) port_fn_migratable_set;
    int (*)(struct devlink *, const struct devlink_port_new_attrs *, struct netlink_ext_ack *, unsigned int *) port_new;
    int (*)(struct devlink *, unsigned int, struct netlink_ext_ack *) port_del;
    int (*)(struct devlink_port *, enum devlink_port_fn_state *, enum devlink_port_fn_opstate *, struct netlink_ext_ack *) port_fn_state_get;
    int (*)(struct devlink_port *, enum devlink_port_fn_state, struct netlink_ext_ack *) port_fn_state_set;
    int (*)(struct devlink_rate *, void *, u64, struct netlink_ext_ack *) rate_leaf_tx_share_set;
    int (*)(struct devlink_rate *, void *, u64, struct netlink_ext_ack *) rate_leaf_tx_max_set;
    int (*)(struct devlink_rate *, void *, u32, struct netlink_ext_ack *) rate_leaf_tx_priority_set;
    int (*)(struct devlink_rate *, void *, u32, struct netlink_ext_ack *) rate_leaf_tx_weight_set;
    int (*)(struct devlink_rate *, void *, u64, struct netlink_ext_ack *) rate_node_tx_share_set;
    int (*)(struct devlink_rate *, void *, u64, struct netlink_ext_ack *) rate_node_tx_max_set;
    int (*)(struct devlink_rate *, void *, u32, struct netlink_ext_ack *) rate_node_tx_priority_set;
    int (*)(struct devlink_rate *, void *, u32, struct netlink_ext_ack *) rate_node_tx_weight_set;
    int (*)(struct devlink_rate *, void * *, struct netlink_ext_ack *) rate_node_new;
    int (*)(struct devlink_rate *, void *, struct netlink_ext_ack *) rate_node_del;
    int (*)(struct devlink_rate *, struct devlink_rate *, void *, void *, struct netlink_ext_ack *) rate_leaf_parent_set;
    int (*)(struct devlink_rate *, struct devlink_rate *, void *, void *, struct netlink_ext_ack *) rate_node_parent_set;
    bool (*)(struct devlink *, unsigned int, struct netlink_ext_ack *) selftest_check;
    enum devlink_selftest_status (*)(struct devlink *, unsigned int, struct netlink_ext_ack *) selftest_run;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct devlink_ops {
    u32 supported_flash_update_params;
    long unsigned int reload_actions;
    long unsigned int reload_limits;
    int (*)(struct devlink *, bool, enum devlink_reload_action, enum devlink_reload_limit, struct netlink_ext_ack *) reload_down;
    int (*)(struct devlink *, enum devlink_reload_action, enum devlink_reload_limit, u32 *, struct netlink_ext_ack *) reload_up;
    int (*)(struct devlink *, unsigned int, u16, struct devlink_sb_pool_info *) sb_pool_get;
    int (*)(struct devlink *, unsigned int, u16, u32, enum devlink_sb_threshold_type, struct netlink_ext_ack *) sb_pool_set;
    int (*)(struct devlink_port *, unsigned int, u16, u32 *) sb_port_pool_get;
    int (*)(struct devlink_port *, unsigned int, u16, u32, struct netlink_ext_ack *) sb_port_pool_set;
    int (*)(struct devlink_port *, unsigned int, u16, enum devlink_sb_pool_type, u16 *, u32 *) sb_tc_pool_bind_get;
    int (*)(struct devlink_port *, unsigned int, u16, enum devlink_sb_pool_type, u16, u32, struct netlink_ext_ack *) sb_tc_pool_bind_set;
    int (*)(struct devlink *, unsigned int) sb_occ_snapshot;
    int (*)(struct devlink *, unsigned int) sb_occ_max_clear;
    int (*)(struct devlink_port *, unsigned int, u16, u32 *, u32 *) sb_occ_port_pool_get;
    int (*)(struct devlink_port *, unsigned int, u16, enum devlink_sb_pool_type, u32 *, u32 *) sb_occ_tc_port_bind_get;
    int (*)(struct devlink *, u16 *) eswitch_mode_get;
    int (*)(struct devlink *, u16, struct netlink_ext_ack *) eswitch_mode_set;
    int (*)(struct devlink *, u8 *) eswitch_inline_mode_get;
    int (*)(struct devlink *, u8, struct netlink_ext_ack *) eswitch_inline_mode_set;
    int (*)(struct devlink *, enum devlink_eswitch_encap_mode *) eswitch_encap_mode_get;
    int (*)(struct devlink *, enum devlink_eswitch_encap_mode, struct netlink_ext_ack *) eswitch_encap_mode_set;
    int (*)(struct devlink *, struct devlink_info_req *, struct netlink_ext_ack *) info_get;
    int (*)(struct devlink *, struct devlink_flash_update_params *, struct netlink_ext_ack *) flash_update;
    int (*)(struct devlink *, const struct devlink_trap *, void *) trap_init;
    void (*)(struct devlink *, const struct devlink_trap *, void *) trap_fini;
    int (*)(struct devlink *, const struct devlink_trap *, enum devlink_trap_action, struct netlink_ext_ack *) trap_action_set;
    int (*)(struct devlink *, const struct devlink_trap_group *) trap_group_init;
    int (*)(struct devlink *, const struct devlink_trap_group *, const struct devlink_trap_policer *, struct netlink_ext_ack *) trap_group_set;
    int (*)(struct devlink *, const struct devlink_trap_group *, enum devlink_trap_action, struct netlink_ext_ack *) trap_group_action_set;
    int (*)(struct devlink *, const struct devlink_trap *, u64 *) trap_drop_counter_get;
    int (*)(struct devlink *, const struct devlink_trap_policer *) trap_policer_init;
    void (*)(struct devlink *, const struct devlink_trap_policer *) trap_policer_fini;
    int (*)(struct devlink *, const struct devlink_trap_policer *, u64, u64, struct netlink_ext_ack *) trap_policer_set;
    int (*)(struct devlink *, const struct devlink_trap_policer *, u64 *) trap_policer_counter_get;
    int (*)(struct devlink *, const struct devlink_port_new_attrs *, struct netlink_ext_ack *, struct devlink_port * *) port_new;
    int (*)(struct devlink_rate *, void *, u64, struct netlink_ext_ack *) rate_leaf_tx_share_set;
    int (*)(struct devlink_rate *, void *, u64, struct netlink_ext_ack *) rate_leaf_tx_max_set;
    int (*)(struct devlink_rate *, void *, u32, struct netlink_ext_ack *) rate_leaf_tx_priority_set;
    int (*)(struct devlink_rate *, void *, u32, struct netlink_ext_ack *) rate_leaf_tx_weight_set;
    int (*)(struct devlink_rate *, void *, u64, struct netlink_ext_ack *) rate_node_tx_share_set;
    int (*)(struct devlink_rate *, void *, u64, struct netlink_ext_ack *) rate_node_tx_max_set;
    int (*)(struct devlink_rate *, void *, u32, struct netlink_ext_ack *) rate_node_tx_priority_set;
    int (*)(struct devlink_rate *, void *, u32, struct netlink_ext_ack *) rate_node_tx_weight_set;
    int (*)(struct devlink_rate *, void * *, struct netlink_ext_ack *) rate_node_new;
    int (*)(struct devlink_rate *, void *, struct netlink_ext_ack *) rate_node_del;
    int (*)(struct devlink_rate *, struct devlink_rate *, void *, void *, struct netlink_ext_ack *) rate_leaf_parent_set;
    int (*)(struct devlink_rate *, struct devlink_rate *, void *, void *, struct netlink_ext_ack *) rate_node_parent_set;
    bool (*)(struct devlink *, unsigned int, struct netlink_ext_ack *) selftest_check;
    enum devlink_selftest_status (*)(struct devlink *, unsigned int, struct netlink_ext_ack *) selftest_run;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct devlink_ops {
    u32 supported_flash_update_params;
    long unsigned int reload_actions;
    long unsigned int reload_limits;
    int (*)(struct devlink *, bool, enum devlink_reload_action, enum devlink_reload_limit, struct netlink_ext_ack *) reload_down;
    int (*)(struct devlink *, enum devlink_reload_action, enum devlink_reload_limit, u32 *, struct netlink_ext_ack *) reload_up;
    int (*)(struct devlink *, unsigned int, u16, struct devlink_sb_pool_info *) sb_pool_get;
    int (*)(struct devlink *, unsigned int, u16, u32, enum devlink_sb_threshold_type, struct netlink_ext_ack *) sb_pool_set;
    int (*)(struct devlink_port *, unsigned int, u16, u32 *) sb_port_pool_get;
    int (*)(struct devlink_port *, unsigned int, u16, u32, struct netlink_ext_ack *) sb_port_pool_set;
    int (*)(struct devlink_port *, unsigned int, u16, enum devlink_sb_pool_type, u16 *, u32 *) sb_tc_pool_bind_get;
    int (*)(struct devlink_port *, unsigned int, u16, enum devlink_sb_pool_type, u16, u32, struct netlink_ext_ack *) sb_tc_pool_bind_set;
    int (*)(struct devlink *, unsigned int) sb_occ_snapshot;
    int (*)(struct devlink *, unsigned int) sb_occ_max_clear;
    int (*)(struct devlink_port *, unsigned int, u16, u32 *, u32 *) sb_occ_port_pool_get;
    int (*)(struct devlink_port *, unsigned int, u16, enum devlink_sb_pool_type, u32 *, u32 *) sb_occ_tc_port_bind_get;
    int (*)(struct devlink *, u16 *) eswitch_mode_get;
    int (*)(struct devlink *, u16, struct netlink_ext_ack *) eswitch_mode_set;
    int (*)(struct devlink *, u8 *) eswitch_inline_mode_get;
    int (*)(struct devlink *, u8, struct netlink_ext_ack *) eswitch_inline_mode_set;
    int (*)(struct devlink *, enum devlink_eswitch_encap_mode *) eswitch_encap_mode_get;
    int (*)(struct devlink *, enum devlink_eswitch_encap_mode, struct netlink_ext_ack *) eswitch_encap_mode_set;
    int (*)(struct devlink *, struct devlink_info_req *, struct netlink_ext_ack *) info_get;
    int (*)(struct devlink *, struct devlink_flash_update_params *, struct netlink_ext_ack *) flash_update;
    int (*)(struct devlink *, const struct devlink_trap *, void *) trap_init;
    void (*)(struct devlink *, const struct devlink_trap *, void *) trap_fini;
    int (*)(struct devlink *, const struct devlink_trap *, enum devlink_trap_action, struct netlink_ext_ack *) trap_action_set;
    int (*)(struct devlink *, const struct devlink_trap_group *) trap_group_init;
    int (*)(struct devlink *, const struct devlink_trap_group *, const struct devlink_trap_policer *, struct netlink_ext_ack *) trap_group_set;
    int (*)(struct devlink *, const struct devlink_trap_group *, enum devlink_trap_action, struct netlink_ext_ack *) trap_group_action_set;
    int (*)(struct devlink *, const struct devlink_trap *, u64 *) trap_drop_counter_get;
    int (*)(struct devlink *, const struct devlink_trap_policer *) trap_policer_init;
    void (*)(struct devlink *, const struct devlink_trap_policer *) trap_policer_fini;
    int (*)(struct devlink *, const struct devlink_trap_policer *, u64, u64, struct netlink_ext_ack *) trap_policer_set;
    int (*)(struct devlink *, const struct devlink_trap_policer *, u64 *) trap_policer_counter_get;
    int (*)(struct devlink *, const struct devlink_port_new_attrs *, struct netlink_ext_ack *, struct devlink_port * *) port_new;
    int (*)(struct devlink_rate *, void *, u64, struct netlink_ext_ack *) rate_leaf_tx_share_set;
    int (*)(struct devlink_rate *, void *, u64, struct netlink_ext_ack *) rate_leaf_tx_max_set;
    int (*)(struct devlink_rate *, void *, u32, struct netlink_ext_ack *) rate_leaf_tx_priority_set;
    int (*)(struct devlink_rate *, void *, u32, struct netlink_ext_ack *) rate_leaf_tx_weight_set;
    int (*)(struct devlink_rate *, void *, u64, struct netlink_ext_ack *) rate_node_tx_share_set;
    int (*)(struct devlink_rate *, void *, u64, struct netlink_ext_ack *) rate_node_tx_max_set;
    int (*)(struct devlink_rate *, void *, u32, struct netlink_ext_ack *) rate_node_tx_priority_set;
    int (*)(struct devlink_rate *, void *, u32, struct netlink_ext_ack *) rate_node_tx_weight_set;
    int (*)(struct devlink_rate *, void * *, struct netlink_ext_ack *) rate_node_new;
    int (*)(struct devlink_rate *, void *, struct netlink_ext_ack *) rate_node_del;
    int (*)(struct devlink_rate *, struct devlink_rate *, void *, void *, struct netlink_ext_ack *) rate_leaf_parent_set;
    int (*)(struct devlink_rate *, struct devlink_rate *, void *, void *, struct netlink_ext_ack *) rate_node_parent_set;
    bool (*)(struct devlink *, unsigned int, struct netlink_ext_ack *) selftest_check;
    enum devlink_selftest_status (*)(struct devlink *, unsigned int, struct netlink_ext_ack *) selftest_run;
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
struct devlink_ops {
    int (*)(struct devlink *, struct netlink_ext_ack *) reload_down;
    int (*)(struct devlink *, struct netlink_ext_ack *) reload_up;
    int (*)(struct devlink_port *, enum devlink_port_type) port_type_set;
    int (*)(struct devlink *, unsigned int, unsigned int, struct netlink_ext_ack *) port_split;
    int (*)(struct devlink *, unsigned int, struct netlink_ext_ack *) port_unsplit;
    int (*)(struct devlink *, unsigned int, u16, struct devlink_sb_pool_info *) sb_pool_get;
    int (*)(struct devlink *, unsigned int, u16, u32, enum devlink_sb_threshold_type, struct netlink_ext_ack *) sb_pool_set;
    int (*)(struct devlink_port *, unsigned int, u16, u32 *) sb_port_pool_get;
    int (*)(struct devlink_port *, unsigned int, u16, u32, struct netlink_ext_ack *) sb_port_pool_set;
    int (*)(struct devlink_port *, unsigned int, u16, enum devlink_sb_pool_type, u16 *, u32 *) sb_tc_pool_bind_get;
    int (*)(struct devlink_port *, unsigned int, u16, enum devlink_sb_pool_type, u16, u32, struct netlink_ext_ack *) sb_tc_pool_bind_set;
    int (*)(struct devlink *, unsigned int) sb_occ_snapshot;
    int (*)(struct devlink *, unsigned int) sb_occ_max_clear;
    int (*)(struct devlink_port *, unsigned int, u16, u32 *, u32 *) sb_occ_port_pool_get;
    int (*)(struct devlink_port *, unsigned int, u16, enum devlink_sb_pool_type, u32 *, u32 *) sb_occ_tc_port_bind_get;
    int (*)(struct devlink *, u16 *) eswitch_mode_get;
    int (*)(struct devlink *, u16, struct netlink_ext_ack *) eswitch_mode_set;
    int (*)(struct devlink *, u8 *) eswitch_inline_mode_get;
    int (*)(struct devlink *, u8, struct netlink_ext_ack *) eswitch_inline_mode_set;
    int (*)(struct devlink *, enum devlink_eswitch_encap_mode *) eswitch_encap_mode_get;
    int (*)(struct devlink *, enum devlink_eswitch_encap_mode, struct netlink_ext_ack *) eswitch_encap_mode_set;
    int (*)(struct devlink *, struct devlink_info_req *, struct netlink_ext_ack *) info_get;
    int (*)(struct devlink *, const char *, const char *, struct netlink_ext_ack *) flash_update;
    int (*)(struct devlink *, const struct devlink_trap *, void *) trap_init;
    void (*)(struct devlink *, const struct devlink_trap *, void *) trap_fini;
    int (*)(struct devlink *, const struct devlink_trap *, enum devlink_trap_action) trap_action_set;
    int (*)(struct devlink *, const struct devlink_trap_group *) trap_group_init;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct devlink_ops {
    int (*)(struct devlink *, struct netlink_ext_ack *) reload_down;
    int (*)(struct devlink *, struct netlink_ext_ack *) reload_up;
    int (*)(struct devlink_port *, enum devlink_port_type) port_type_set;
    int (*)(struct devlink *, unsigned int, unsigned int, struct netlink_ext_ack *) port_split;
    int (*)(struct devlink *, unsigned int, struct netlink_ext_ack *) port_unsplit;
    int (*)(struct devlink *, unsigned int, u16, struct devlink_sb_pool_info *) sb_pool_get;
    int (*)(struct devlink *, unsigned int, u16, u32, enum devlink_sb_threshold_type, struct netlink_ext_ack *) sb_pool_set;
    int (*)(struct devlink_port *, unsigned int, u16, u32 *) sb_port_pool_get;
    int (*)(struct devlink_port *, unsigned int, u16, u32, struct netlink_ext_ack *) sb_port_pool_set;
    int (*)(struct devlink_port *, unsigned int, u16, enum devlink_sb_pool_type, u16 *, u32 *) sb_tc_pool_bind_get;
    int (*)(struct devlink_port *, unsigned int, u16, enum devlink_sb_pool_type, u16, u32, struct netlink_ext_ack *) sb_tc_pool_bind_set;
    int (*)(struct devlink *, unsigned int) sb_occ_snapshot;
    int (*)(struct devlink *, unsigned int) sb_occ_max_clear;
    int (*)(struct devlink_port *, unsigned int, u16, u32 *, u32 *) sb_occ_port_pool_get;
    int (*)(struct devlink_port *, unsigned int, u16, enum devlink_sb_pool_type, u32 *, u32 *) sb_occ_tc_port_bind_get;
    int (*)(struct devlink *, u16 *) eswitch_mode_get;
    int (*)(struct devlink *, u16, struct netlink_ext_ack *) eswitch_mode_set;
    int (*)(struct devlink *, u8 *) eswitch_inline_mode_get;
    int (*)(struct devlink *, u8, struct netlink_ext_ack *) eswitch_inline_mode_set;
    int (*)(struct devlink *, enum devlink_eswitch_encap_mode *) eswitch_encap_mode_get;
    int (*)(struct devlink *, enum devlink_eswitch_encap_mode, struct netlink_ext_ack *) eswitch_encap_mode_set;
    int (*)(struct devlink *, struct devlink_info_req *, struct netlink_ext_ack *) info_get;
    int (*)(struct devlink *, const char *, const char *, struct netlink_ext_ack *) flash_update;
    int (*)(struct devlink *, const struct devlink_trap *, void *) trap_init;
    void (*)(struct devlink *, const struct devlink_trap *, void *) trap_fini;
    int (*)(struct devlink *, const struct devlink_trap *, enum devlink_trap_action) trap_action_set;
    int (*)(struct devlink *, const struct devlink_trap_group *) trap_group_init;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct devlink_ops {
    int (*)(struct devlink *, struct netlink_ext_ack *) reload_down;
    int (*)(struct devlink *, struct netlink_ext_ack *) reload_up;
    int (*)(struct devlink_port *, enum devlink_port_type) port_type_set;
    int (*)(struct devlink *, unsigned int, unsigned int, struct netlink_ext_ack *) port_split;
    int (*)(struct devlink *, unsigned int, struct netlink_ext_ack *) port_unsplit;
    int (*)(struct devlink *, unsigned int, u16, struct devlink_sb_pool_info *) sb_pool_get;
    int (*)(struct devlink *, unsigned int, u16, u32, enum devlink_sb_threshold_type, struct netlink_ext_ack *) sb_pool_set;
    int (*)(struct devlink_port *, unsigned int, u16, u32 *) sb_port_pool_get;
    int (*)(struct devlink_port *, unsigned int, u16, u32, struct netlink_ext_ack *) sb_port_pool_set;
    int (*)(struct devlink_port *, unsigned int, u16, enum devlink_sb_pool_type, u16 *, u32 *) sb_tc_pool_bind_get;
    int (*)(struct devlink_port *, unsigned int, u16, enum devlink_sb_pool_type, u16, u32, struct netlink_ext_ack *) sb_tc_pool_bind_set;
    int (*)(struct devlink *, unsigned int) sb_occ_snapshot;
    int (*)(struct devlink *, unsigned int) sb_occ_max_clear;
    int (*)(struct devlink_port *, unsigned int, u16, u32 *, u32 *) sb_occ_port_pool_get;
    int (*)(struct devlink_port *, unsigned int, u16, enum devlink_sb_pool_type, u32 *, u32 *) sb_occ_tc_port_bind_get;
    int (*)(struct devlink *, u16 *) eswitch_mode_get;
    int (*)(struct devlink *, u16, struct netlink_ext_ack *) eswitch_mode_set;
    int (*)(struct devlink *, u8 *) eswitch_inline_mode_get;
    int (*)(struct devlink *, u8, struct netlink_ext_ack *) eswitch_inline_mode_set;
    int (*)(struct devlink *, enum devlink_eswitch_encap_mode *) eswitch_encap_mode_get;
    int (*)(struct devlink *, enum devlink_eswitch_encap_mode, struct netlink_ext_ack *) eswitch_encap_mode_set;
    int (*)(struct devlink *, struct devlink_info_req *, struct netlink_ext_ack *) info_get;
    int (*)(struct devlink *, const char *, const char *, struct netlink_ext_ack *) flash_update;
    int (*)(struct devlink *, const struct devlink_trap *, void *) trap_init;
    void (*)(struct devlink *, const struct devlink_trap *, void *) trap_fini;
    int (*)(struct devlink *, const struct devlink_trap *, enum devlink_trap_action) trap_action_set;
    int (*)(struct devlink *, const struct devlink_trap_group *) trap_group_init;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct devlink_ops {
    int (*)(struct devlink *, struct netlink_ext_ack *) reload_down;
    int (*)(struct devlink *, struct netlink_ext_ack *) reload_up;
    int (*)(struct devlink_port *, enum devlink_port_type) port_type_set;
    int (*)(struct devlink *, unsigned int, unsigned int, struct netlink_ext_ack *) port_split;
    int (*)(struct devlink *, unsigned int, struct netlink_ext_ack *) port_unsplit;
    int (*)(struct devlink *, unsigned int, u16, struct devlink_sb_pool_info *) sb_pool_get;
    int (*)(struct devlink *, unsigned int, u16, u32, enum devlink_sb_threshold_type, struct netlink_ext_ack *) sb_pool_set;
    int (*)(struct devlink_port *, unsigned int, u16, u32 *) sb_port_pool_get;
    int (*)(struct devlink_port *, unsigned int, u16, u32, struct netlink_ext_ack *) sb_port_pool_set;
    int (*)(struct devlink_port *, unsigned int, u16, enum devlink_sb_pool_type, u16 *, u32 *) sb_tc_pool_bind_get;
    int (*)(struct devlink_port *, unsigned int, u16, enum devlink_sb_pool_type, u16, u32, struct netlink_ext_ack *) sb_tc_pool_bind_set;
    int (*)(struct devlink *, unsigned int) sb_occ_snapshot;
    int (*)(struct devlink *, unsigned int) sb_occ_max_clear;
    int (*)(struct devlink_port *, unsigned int, u16, u32 *, u32 *) sb_occ_port_pool_get;
    int (*)(struct devlink_port *, unsigned int, u16, enum devlink_sb_pool_type, u32 *, u32 *) sb_occ_tc_port_bind_get;
    int (*)(struct devlink *, u16 *) eswitch_mode_get;
    int (*)(struct devlink *, u16, struct netlink_ext_ack *) eswitch_mode_set;
    int (*)(struct devlink *, u8 *) eswitch_inline_mode_get;
    int (*)(struct devlink *, u8, struct netlink_ext_ack *) eswitch_inline_mode_set;
    int (*)(struct devlink *, enum devlink_eswitch_encap_mode *) eswitch_encap_mode_get;
    int (*)(struct devlink *, enum devlink_eswitch_encap_mode, struct netlink_ext_ack *) eswitch_encap_mode_set;
    int (*)(struct devlink *, struct devlink_info_req *, struct netlink_ext_ack *) info_get;
    int (*)(struct devlink *, const char *, const char *, struct netlink_ext_ack *) flash_update;
    int (*)(struct devlink *, const struct devlink_trap *, void *) trap_init;
    void (*)(struct devlink *, const struct devlink_trap *, void *) trap_fini;
    int (*)(struct devlink *, const struct devlink_trap *, enum devlink_trap_action) trap_action_set;
    int (*)(struct devlink *, const struct devlink_trap_group *) trap_group_init;
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
struct devlink_ops {
    int (*)(struct devlink *, struct netlink_ext_ack *) reload_down;
    int (*)(struct devlink *, struct netlink_ext_ack *) reload_up;
    int (*)(struct devlink_port *, enum devlink_port_type) port_type_set;
    int (*)(struct devlink *, unsigned int, unsigned int, struct netlink_ext_ack *) port_split;
    int (*)(struct devlink *, unsigned int, struct netlink_ext_ack *) port_unsplit;
    int (*)(struct devlink *, unsigned int, u16, struct devlink_sb_pool_info *) sb_pool_get;
    int (*)(struct devlink *, unsigned int, u16, u32, enum devlink_sb_threshold_type, struct netlink_ext_ack *) sb_pool_set;
    int (*)(struct devlink_port *, unsigned int, u16, u32 *) sb_port_pool_get;
    int (*)(struct devlink_port *, unsigned int, u16, u32, struct netlink_ext_ack *) sb_port_pool_set;
    int (*)(struct devlink_port *, unsigned int, u16, enum devlink_sb_pool_type, u16 *, u32 *) sb_tc_pool_bind_get;
    int (*)(struct devlink_port *, unsigned int, u16, enum devlink_sb_pool_type, u16, u32, struct netlink_ext_ack *) sb_tc_pool_bind_set;
    int (*)(struct devlink *, unsigned int) sb_occ_snapshot;
    int (*)(struct devlink *, unsigned int) sb_occ_max_clear;
    int (*)(struct devlink_port *, unsigned int, u16, u32 *, u32 *) sb_occ_port_pool_get;
    int (*)(struct devlink_port *, unsigned int, u16, enum devlink_sb_pool_type, u32 *, u32 *) sb_occ_tc_port_bind_get;
    int (*)(struct devlink *, u16 *) eswitch_mode_get;
    int (*)(struct devlink *, u16, struct netlink_ext_ack *) eswitch_mode_set;
    int (*)(struct devlink *, u8 *) eswitch_inline_mode_get;
    int (*)(struct devlink *, u8, struct netlink_ext_ack *) eswitch_inline_mode_set;
    int (*)(struct devlink *, enum devlink_eswitch_encap_mode *) eswitch_encap_mode_get;
    int (*)(struct devlink *, enum devlink_eswitch_encap_mode, struct netlink_ext_ack *) eswitch_encap_mode_set;
    int (*)(struct devlink *, struct devlink_info_req *, struct netlink_ext_ack *) info_get;
    int (*)(struct devlink *, const char *, const char *, struct netlink_ext_ack *) flash_update;
    int (*)(struct devlink *, const struct devlink_trap *, void *) trap_init;
    void (*)(struct devlink *, const struct devlink_trap *, void *) trap_fini;
    int (*)(struct devlink *, const struct devlink_trap *, enum devlink_trap_action) trap_action_set;
    int (*)(struct devlink *, const struct devlink_trap_group *) trap_group_init;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct devlink_ops {
    int (*)(struct devlink *, struct netlink_ext_ack *) reload_down;
    int (*)(struct devlink *, struct netlink_ext_ack *) reload_up;
    int (*)(struct devlink_port *, enum devlink_port_type) port_type_set;
    int (*)(struct devlink *, unsigned int, unsigned int, struct netlink_ext_ack *) port_split;
    int (*)(struct devlink *, unsigned int, struct netlink_ext_ack *) port_unsplit;
    int (*)(struct devlink *, unsigned int, u16, struct devlink_sb_pool_info *) sb_pool_get;
    int (*)(struct devlink *, unsigned int, u16, u32, enum devlink_sb_threshold_type, struct netlink_ext_ack *) sb_pool_set;
    int (*)(struct devlink_port *, unsigned int, u16, u32 *) sb_port_pool_get;
    int (*)(struct devlink_port *, unsigned int, u16, u32, struct netlink_ext_ack *) sb_port_pool_set;
    int (*)(struct devlink_port *, unsigned int, u16, enum devlink_sb_pool_type, u16 *, u32 *) sb_tc_pool_bind_get;
    int (*)(struct devlink_port *, unsigned int, u16, enum devlink_sb_pool_type, u16, u32, struct netlink_ext_ack *) sb_tc_pool_bind_set;
    int (*)(struct devlink *, unsigned int) sb_occ_snapshot;
    int (*)(struct devlink *, unsigned int) sb_occ_max_clear;
    int (*)(struct devlink_port *, unsigned int, u16, u32 *, u32 *) sb_occ_port_pool_get;
    int (*)(struct devlink_port *, unsigned int, u16, enum devlink_sb_pool_type, u32 *, u32 *) sb_occ_tc_port_bind_get;
    int (*)(struct devlink *, u16 *) eswitch_mode_get;
    int (*)(struct devlink *, u16, struct netlink_ext_ack *) eswitch_mode_set;
    int (*)(struct devlink *, u8 *) eswitch_inline_mode_get;
    int (*)(struct devlink *, u8, struct netlink_ext_ack *) eswitch_inline_mode_set;
    int (*)(struct devlink *, enum devlink_eswitch_encap_mode *) eswitch_encap_mode_get;
    int (*)(struct devlink *, enum devlink_eswitch_encap_mode, struct netlink_ext_ack *) eswitch_encap_mode_set;
    int (*)(struct devlink *, struct devlink_info_req *, struct netlink_ext_ack *) info_get;
    int (*)(struct devlink *, const char *, const char *, struct netlink_ext_ack *) flash_update;
    int (*)(struct devlink *, const struct devlink_trap *, void *) trap_init;
    void (*)(struct devlink *, const struct devlink_trap *, void *) trap_fini;
    int (*)(struct devlink *, const struct devlink_trap *, enum devlink_trap_action) trap_action_set;
    int (*)(struct devlink *, const struct devlink_trap_group *) trap_group_init;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct devlink_ops {
    int (*)(struct devlink *, struct netlink_ext_ack *) reload_down;
    int (*)(struct devlink *, struct netlink_ext_ack *) reload_up;
    int (*)(struct devlink_port *, enum devlink_port_type) port_type_set;
    int (*)(struct devlink *, unsigned int, unsigned int, struct netlink_ext_ack *) port_split;
    int (*)(struct devlink *, unsigned int, struct netlink_ext_ack *) port_unsplit;
    int (*)(struct devlink *, unsigned int, u16, struct devlink_sb_pool_info *) sb_pool_get;
    int (*)(struct devlink *, unsigned int, u16, u32, enum devlink_sb_threshold_type, struct netlink_ext_ack *) sb_pool_set;
    int (*)(struct devlink_port *, unsigned int, u16, u32 *) sb_port_pool_get;
    int (*)(struct devlink_port *, unsigned int, u16, u32, struct netlink_ext_ack *) sb_port_pool_set;
    int (*)(struct devlink_port *, unsigned int, u16, enum devlink_sb_pool_type, u16 *, u32 *) sb_tc_pool_bind_get;
    int (*)(struct devlink_port *, unsigned int, u16, enum devlink_sb_pool_type, u16, u32, struct netlink_ext_ack *) sb_tc_pool_bind_set;
    int (*)(struct devlink *, unsigned int) sb_occ_snapshot;
    int (*)(struct devlink *, unsigned int) sb_occ_max_clear;
    int (*)(struct devlink_port *, unsigned int, u16, u32 *, u32 *) sb_occ_port_pool_get;
    int (*)(struct devlink_port *, unsigned int, u16, enum devlink_sb_pool_type, u32 *, u32 *) sb_occ_tc_port_bind_get;
    int (*)(struct devlink *, u16 *) eswitch_mode_get;
    int (*)(struct devlink *, u16, struct netlink_ext_ack *) eswitch_mode_set;
    int (*)(struct devlink *, u8 *) eswitch_inline_mode_get;
    int (*)(struct devlink *, u8, struct netlink_ext_ack *) eswitch_inline_mode_set;
    int (*)(struct devlink *, enum devlink_eswitch_encap_mode *) eswitch_encap_mode_get;
    int (*)(struct devlink *, enum devlink_eswitch_encap_mode, struct netlink_ext_ack *) eswitch_encap_mode_set;
    int (*)(struct devlink *, struct devlink_info_req *, struct netlink_ext_ack *) info_get;
    int (*)(struct devlink *, const char *, const char *, struct netlink_ext_ack *) flash_update;
    int (*)(struct devlink *, const struct devlink_trap *, void *) trap_init;
    void (*)(struct devlink *, const struct devlink_trap *, void *) trap_fini;
    int (*)(struct devlink *, const struct devlink_trap *, enum devlink_trap_action) trap_action_set;
    int (*)(struct devlink *, const struct devlink_trap_group *) trap_group_init;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct devlink_ops {
    int (*)(struct devlink *, struct netlink_ext_ack *) reload_down;
    int (*)(struct devlink *, struct netlink_ext_ack *) reload_up;
    int (*)(struct devlink_port *, enum devlink_port_type) port_type_set;
    int (*)(struct devlink *, unsigned int, unsigned int, struct netlink_ext_ack *) port_split;
    int (*)(struct devlink *, unsigned int, struct netlink_ext_ack *) port_unsplit;
    int (*)(struct devlink *, unsigned int, u16, struct devlink_sb_pool_info *) sb_pool_get;
    int (*)(struct devlink *, unsigned int, u16, u32, enum devlink_sb_threshold_type, struct netlink_ext_ack *) sb_pool_set;
    int (*)(struct devlink_port *, unsigned int, u16, u32 *) sb_port_pool_get;
    int (*)(struct devlink_port *, unsigned int, u16, u32, struct netlink_ext_ack *) sb_port_pool_set;
    int (*)(struct devlink_port *, unsigned int, u16, enum devlink_sb_pool_type, u16 *, u32 *) sb_tc_pool_bind_get;
    int (*)(struct devlink_port *, unsigned int, u16, enum devlink_sb_pool_type, u16, u32, struct netlink_ext_ack *) sb_tc_pool_bind_set;
    int (*)(struct devlink *, unsigned int) sb_occ_snapshot;
    int (*)(struct devlink *, unsigned int) sb_occ_max_clear;
    int (*)(struct devlink_port *, unsigned int, u16, u32 *, u32 *) sb_occ_port_pool_get;
    int (*)(struct devlink_port *, unsigned int, u16, enum devlink_sb_pool_type, u32 *, u32 *) sb_occ_tc_port_bind_get;
    int (*)(struct devlink *, u16 *) eswitch_mode_get;
    int (*)(struct devlink *, u16, struct netlink_ext_ack *) eswitch_mode_set;
    int (*)(struct devlink *, u8 *) eswitch_inline_mode_get;
    int (*)(struct devlink *, u8, struct netlink_ext_ack *) eswitch_inline_mode_set;
    int (*)(struct devlink *, enum devlink_eswitch_encap_mode *) eswitch_encap_mode_get;
    int (*)(struct devlink *, enum devlink_eswitch_encap_mode, struct netlink_ext_ack *) eswitch_encap_mode_set;
    int (*)(struct devlink *, struct devlink_info_req *, struct netlink_ext_ack *) info_get;
    int (*)(struct devlink *, const char *, const char *, struct netlink_ext_ack *) flash_update;
    int (*)(struct devlink *, const struct devlink_trap *, void *) trap_init;
    void (*)(struct devlink *, const struct devlink_trap *, void *) trap_fini;
    int (*)(struct devlink *, const struct devlink_trap *, enum devlink_trap_action) trap_action_set;
    int (*)(struct devlink *, const struct devlink_trap_group *) trap_group_init;
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
struct devlink_ops {
    int (*)(struct devlink_port *, enum devlink_port_type) port_type_set;
    int (*)(struct devlink *, unsigned int, unsigned int) port_split;
    int (*)(struct devlink *, unsigned int) port_unsplit;
    int (*)(struct devlink *, unsigned int, u16, struct devlink_sb_pool_info *) sb_pool_get;
    int (*)(struct devlink *, unsigned int, u16, u32, enum devlink_sb_threshold_type) sb_pool_set;
    int (*)(struct devlink_port *, unsigned int, u16, u32 *) sb_port_pool_get;
    int (*)(struct devlink_port *, unsigned int, u16, u32) sb_port_pool_set;
    int (*)(struct devlink_port *, unsigned int, u16, enum devlink_sb_pool_type, u16 *, u32 *) sb_tc_pool_bind_get;
    int (*)(struct devlink_port *, unsigned int, u16, enum devlink_sb_pool_type, u16, u32) sb_tc_pool_bind_set;
    int (*)(struct devlink *, unsigned int) sb_occ_snapshot;
    int (*)(struct devlink *, unsigned int) sb_occ_max_clear;
    int (*)(struct devlink_port *, unsigned int, u16, u32 *, u32 *) sb_occ_port_pool_get;
    int (*)(struct devlink_port *, unsigned int, u16, enum devlink_sb_pool_type, u32 *, u32 *) sb_occ_tc_port_bind_get;
    int (*)(struct devlink *, u16 *) eswitch_mode_get;
    int (*)(struct devlink *, u16) eswitch_mode_set;
    int (*)(struct devlink *, u8 *) eswitch_inline_mode_get;
    int (*)(struct devlink *, u8) eswitch_inline_mode_set;
    int (*)(struct devlink *, u8 *) eswitch_encap_mode_get;
    int (*)(struct devlink *, u8) eswitch_encap_mode_set;
}
```
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
<code>int (*)(struct devlink *, struct netlink_ext_ack *) reload</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct devlink *, unsigned int, unsigned int) port_split</code> ➡️ <code>int (*)(struct devlink *, unsigned int, unsigned int, struct netlink_ext_ack *) port_split</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct devlink *, unsigned int) port_unsplit</code> ➡️ <code>int (*)(struct devlink *, unsigned int, struct netlink_ext_ack *) port_unsplit</code>
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
<code>int (*)(struct devlink *, u16) eswitch_mode_set</code> ➡️ <code>int (*)(struct devlink *, u16, struct netlink_ext_ack *) eswitch_mode_set</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct devlink *, u8) eswitch_inline_mode_set</code> ➡️ <code>int (*)(struct devlink *, u8, struct netlink_ext_ack *) eswitch_inline_mode_set</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct devlink *, u8) eswitch_encap_mode_set</code> ➡️ <code>int (*)(struct devlink *, u8, struct netlink_ext_ack *) eswitch_encap_mode_set</code>
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
<code>int (*)(struct devlink *, struct devlink_info_req *, struct netlink_ext_ack *) info_get</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct devlink *, const char *, const char *, struct netlink_ext_ack *) flash_update</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct devlink *, unsigned int, u16, u32, enum devlink_sb_threshold_type) sb_pool_set</code> ➡️ <code>int (*)(struct devlink *, unsigned int, u16, u32, enum devlink_sb_threshold_type, struct netlink_ext_ack *) sb_pool_set</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct devlink_port *, unsigned int, u16, u32) sb_port_pool_set</code> ➡️ <code>int (*)(struct devlink_port *, unsigned int, u16, u32, struct netlink_ext_ack *) sb_port_pool_set</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct devlink_port *, unsigned int, u16, enum devlink_sb_pool_type, u16, u32) sb_tc_pool_bind_set</code> ➡️ <code>int (*)(struct devlink_port *, unsigned int, u16, enum devlink_sb_pool_type, u16, u32, struct netlink_ext_ack *) sb_tc_pool_bind_set</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct devlink *, u8 *) eswitch_encap_mode_get</code> ➡️ <code>int (*)(struct devlink *, enum devlink_eswitch_encap_mode *) eswitch_encap_mode_get</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct devlink *, u8, struct netlink_ext_ack *) eswitch_encap_mode_set</code> ➡️ <code>int (*)(struct devlink *, enum devlink_eswitch_encap_mode, struct netlink_ext_ack *) eswitch_encap_mode_set</code>
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
<code>int (*)(struct devlink *, struct netlink_ext_ack *) reload_down</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct devlink *, struct netlink_ext_ack *) reload_up</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct devlink *, const struct devlink_trap *, void *) trap_init</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct devlink *, const struct devlink_trap *, void *) trap_fini</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct devlink *, const struct devlink_trap *, enum devlink_trap_action) trap_action_set</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct devlink *, const struct devlink_trap_group *) trap_group_init</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct devlink *, struct netlink_ext_ack *) reload</code>
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
<code>int (*)(struct devlink *, const struct devlink_trap_group *, const struct devlink_trap_policer *) trap_group_set</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct devlink *, const struct devlink_trap_policer *) trap_policer_init</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct devlink *, const struct devlink_trap_policer *) trap_policer_fini</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct devlink *, const struct devlink_trap_policer *, u64, u64, struct netlink_ext_ack *) trap_policer_set</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct devlink *, const struct devlink_trap_policer *, u64 *) trap_policer_counter_get</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct devlink *, struct netlink_ext_ack *) reload_down</code> ➡️ <code>int (*)(struct devlink *, bool, struct netlink_ext_ack *) reload_down</code>
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
<code>u32 supported_flash_update_params</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int reload_actions</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int reload_limits</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct devlink *, const struct devlink_trap_group *, enum devlink_trap_action, struct netlink_ext_ack *) trap_group_action_set</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct devlink *, struct devlink_port *, u8 *, int *, struct netlink_ext_ack *) port_function_hw_addr_get</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct devlink *, struct devlink_port *, const u8 *, int, struct netlink_ext_ack *) port_function_hw_addr_set</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct devlink *, bool, struct netlink_ext_ack *) reload_down</code> ➡️ <code>int (*)(struct devlink *, bool, enum devlink_reload_action, enum devlink_reload_limit, struct netlink_ext_ack *) reload_down</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct devlink *, struct netlink_ext_ack *) reload_up</code> ➡️ <code>int (*)(struct devlink *, enum devlink_reload_action, enum devlink_reload_limit, u32 *, struct netlink_ext_ack *) reload_up</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct devlink *, const char *, const char *, struct netlink_ext_ack *) flash_update</code> ➡️ <code>int (*)(struct devlink *, struct devlink_flash_update_params *, struct netlink_ext_ack *) flash_update</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct devlink *, const struct devlink_trap *, enum devlink_trap_action) trap_action_set</code> ➡️ <code>int (*)(struct devlink *, const struct devlink_trap *, enum devlink_trap_action, struct netlink_ext_ack *) trap_action_set</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct devlink *, const struct devlink_trap_group *, const struct devlink_trap_policer *) trap_group_set</code> ➡️ <code>int (*)(struct devlink *, const struct devlink_trap_group *, const struct devlink_trap_policer *, struct netlink_ext_ack *) trap_group_set</code>
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
<code>int (*)(struct devlink *, const struct devlink_port_new_attrs *, struct netlink_ext_ack *, unsigned int *) port_new</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct devlink *, unsigned int, struct netlink_ext_ack *) port_del</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct devlink *, struct devlink_port *, enum devlink_port_fn_state *, enum devlink_port_fn_opstate *, struct netlink_ext_ack *) port_fn_state_get</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct devlink *, struct devlink_port *, enum devlink_port_fn_state, struct netlink_ext_ack *) port_fn_state_set</code>
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
<code>int (*)(struct devlink *, const struct devlink_trap *, u64 *) trap_drop_counter_get</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct devlink_rate *, void *, u64, struct netlink_ext_ack *) rate_leaf_tx_share_set</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct devlink_rate *, void *, u64, struct netlink_ext_ack *) rate_leaf_tx_max_set</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct devlink_rate *, void *, u64, struct netlink_ext_ack *) rate_node_tx_share_set</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct devlink_rate *, void *, u64, struct netlink_ext_ack *) rate_node_tx_max_set</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct devlink_rate *, void * *, struct netlink_ext_ack *) rate_node_new</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct devlink_rate *, void *, struct netlink_ext_ack *) rate_node_del</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct devlink_rate *, struct devlink_rate *, void *, void *, struct netlink_ext_ack *) rate_leaf_parent_set</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct devlink_rate *, struct devlink_rate *, void *, void *, struct netlink_ext_ack *) rate_node_parent_set</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct devlink *, struct devlink_port *, u8 *, int *, struct netlink_ext_ack *) port_function_hw_addr_get</code> ➡️ <code>int (*)(struct devlink_port *, u8 *, int *, struct netlink_ext_ack *) port_function_hw_addr_get</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct devlink *, struct devlink_port *, const u8 *, int, struct netlink_ext_ack *) port_function_hw_addr_set</code> ➡️ <code>int (*)(struct devlink_port *, const u8 *, int, struct netlink_ext_ack *) port_function_hw_addr_set</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct devlink *, struct devlink_port *, enum devlink_port_fn_state *, enum devlink_port_fn_opstate *, struct netlink_ext_ack *) port_fn_state_get</code> ➡️ <code>int (*)(struct devlink_port *, enum devlink_port_fn_state *, enum devlink_port_fn_opstate *, struct netlink_ext_ack *) port_fn_state_get</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct devlink *, struct devlink_port *, enum devlink_port_fn_state, struct netlink_ext_ack *) port_fn_state_set</code> ➡️ <code>int (*)(struct devlink_port *, enum devlink_port_fn_state, struct netlink_ext_ack *) port_fn_state_set</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>int (*)(struct devlink *, unsigned int, unsigned int, struct netlink_ext_ack *) port_split</code> ➡️ <code>int (*)(struct devlink *, struct devlink_port *, unsigned int, struct netlink_ext_ack *) port_split</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct devlink *, unsigned int, struct netlink_ext_ack *) port_unsplit</code> ➡️ <code>int (*)(struct devlink *, struct devlink_port *, struct netlink_ext_ack *) port_unsplit</code>
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
<code>int (*)(struct devlink_port *, bool *, struct netlink_ext_ack *) port_fn_roce_get</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct devlink_port *, bool, struct netlink_ext_ack *) port_fn_roce_set</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct devlink_port *, bool *, struct netlink_ext_ack *) port_fn_migratable_get</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct devlink_port *, bool, struct netlink_ext_ack *) port_fn_migratable_set</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct devlink_rate *, void *, u32, struct netlink_ext_ack *) rate_leaf_tx_priority_set</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct devlink_rate *, void *, u32, struct netlink_ext_ack *) rate_leaf_tx_weight_set</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct devlink_rate *, void *, u32, struct netlink_ext_ack *) rate_node_tx_priority_set</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct devlink_rate *, void *, u32, struct netlink_ext_ack *) rate_node_tx_weight_set</code>
</li>
<li>
<b>Field added. </b>
<code>bool (*)(struct devlink *, unsigned int, struct netlink_ext_ack *) selftest_check</code>
</li>
<li>
<b>Field added. </b>
<code>enum devlink_selftest_status (*)(struct devlink *, unsigned int, struct netlink_ext_ack *) selftest_run</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>int (*)(struct devlink_port *, enum devlink_port_type) port_type_set</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct devlink *, struct devlink_port *, unsigned int, struct netlink_ext_ack *) port_split</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct devlink *, struct devlink_port *, struct netlink_ext_ack *) port_unsplit</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct devlink_port *, u8 *, int *, struct netlink_ext_ack *) port_function_hw_addr_get</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct devlink_port *, const u8 *, int, struct netlink_ext_ack *) port_function_hw_addr_set</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct devlink_port *, bool *, struct netlink_ext_ack *) port_fn_roce_get</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct devlink_port *, bool, struct netlink_ext_ack *) port_fn_roce_set</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct devlink_port *, bool *, struct netlink_ext_ack *) port_fn_migratable_get</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct devlink_port *, bool, struct netlink_ext_ack *) port_fn_migratable_set</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct devlink *, unsigned int, struct netlink_ext_ack *) port_del</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct devlink_port *, enum devlink_port_fn_state *, enum devlink_port_fn_opstate *, struct netlink_ext_ack *) port_fn_state_get</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct devlink_port *, enum devlink_port_fn_state, struct netlink_ext_ack *) port_fn_state_set</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct devlink *, const struct devlink_port_new_attrs *, struct netlink_ext_ack *, unsigned int *) port_new</code> ➡️ <code>int (*)(struct devlink *, const struct devlink_port_new_attrs *, struct netlink_ext_ack *, struct devlink_port * *) port_new</code>
</li>
</ul>
</details>
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
