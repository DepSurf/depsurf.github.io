# Function: <code>__request_module</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __request_module(bool wait, const char * fmt, void (anon))
```

```json
{
  "name": "__request_module",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579461552,
      "name": "__request_module",
      "external": true,
      "loc": "kernel/kmod.c:124",
      "file": "kernel/kmod.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zpool.c:zpool_has_pool",
        "mm/zpool.c:zpool_create_pool",
        "fs/char_dev.c:base_probe",
        "fs/char_dev.c:base_probe",
        "fs/filesystems.c:get_fs_type",
        "fs/quota/dquot.c:vfs_load_quota_inode",
        "crypto/api.c:crypto_larval_lookup",
        "crypto/api.c:crypto_larval_lookup",
        "block/elevator.c:elevator_get",
        "block/elevator.c:load_default_elevator_module",
        "block/genhd.c:base_probe",
        "block/genhd.c:base_probe",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:fb_open",
        "drivers/char/misc.c:misc_open",
        "drivers/scsi/scsi_dh.c:scsi_dh_attach",
        "drivers/scsi/scsi_dh.c:store_dh_state",
        "drivers/net/phy/phy_device.c:phy_device_create",
        "drivers/net/ppp/ppp_generic.c:ppp_set_compress",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:md_setup_cluster",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/dm-target.c:dm_get_target_type",
        "net/socket.c:sock_ioctl",
        "net/socket.c:sock_ioctl",
        "net/socket.c:sock_ioctl",
        "net/socket.c:__sock_create",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/sched/sch_api.c:qdisc_set_default",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/cls_api.c:tc_ctl_tfilter",
        "net/sched/act_api.c:tcf_action_init_1",
        "net/sched/ematch.c:tcf_em_tree_validate",
        "net/netlink/af_netlink.c:netlink_create",
        "net/netlink/genetlink.c:ctrl_getfamily",
        "net/netfilter/nf_log.c:nf_logger_find_get",
        "net/ipv4/tcp_cong.c:tcp_set_default_congestion_control",
        "net/xfrm/xfrm_state.c:xfrm_get_mode",
        "net/xfrm/xfrm_state.c:__xfrm_init_state",
        "net/ipv6/af_inet6.c:inet6_create",
        "net/ipv6/af_inet6.c:inet6_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579461552,
      "name": "__request_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 725
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int __request_module(bool wait, const char * fmt, void (anon))
```

```json
{
  "name": "__request_module",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579474800,
      "name": "__request_module",
      "external": true,
      "loc": "kernel/kmod.c:124",
      "file": "kernel/kmod.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zpool.c:zpool_create_pool",
        "mm/zpool.c:zpool_has_pool",
        "fs/char_dev.c:base_probe",
        "fs/char_dev.c:base_probe",
        "fs/filesystems.c:get_fs_type",
        "fs/quota/dquot.c:vfs_load_quota_inode",
        "crypto/api.c:crypto_larval_lookup",
        "crypto/api.c:crypto_larval_lookup",
        "block/elevator.c:elevator_get",
        "block/elevator.c:load_default_elevator_module",
        "block/genhd.c:base_probe",
        "block/genhd.c:base_probe",
        "drivers/video/fbdev/core/fbmem.c:fb_open",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/char/misc.c:misc_open",
        "drivers/scsi/scsi_dh.c:scsi_dh_attach",
        "drivers/net/phy/phy_device.c:phy_device_create",
        "drivers/net/ppp/ppp_generic.c:ppp_set_compress",
        "drivers/md/md.c:md_setup_cluster",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:level_store",
        "drivers/md/dm-target.c:dm_get_target_type",
        "drivers/cpufreq/powernow-k8.c:powernowk8_init",
        "net/socket.c:__sock_create",
        "net/socket.c:sock_ioctl",
        "net/socket.c:sock_ioctl",
        "net/socket.c:sock_ioctl",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/lwtunnel.c:lwtunnel_build_state",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/sch_api.c:qdisc_set_default",
        "net/sched/cls_api.c:tc_ctl_tfilter",
        "net/sched/act_api.c:tcf_action_init_1",
        "net/sched/ematch.c:tcf_em_tree_validate",
        "net/netlink/af_netlink.c:netlink_create",
        "net/netlink/genetlink.c:ctrl_getfamily",
        "net/ipv4/tcp_cong.c:tcp_set_default_congestion_control",
        "net/xfrm/xfrm_state.c:__xfrm_init_state",
        "net/xfrm/xfrm_state.c:xfrm_get_mode",
        "net/ipv6/af_inet6.c:inet6_create",
        "net/ipv6/af_inet6.c:inet6_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579474800,
      "name": "__request_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 721
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int __request_module(bool wait, const char * fmt, void (anon))
```

```json
{
  "name": "__request_module",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579495200,
      "name": "__request_module",
      "external": true,
      "loc": "kernel/kmod.c:124",
      "file": "kernel/kmod.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zpool.c:zpool_create_pool",
        "mm/zpool.c:zpool_has_pool",
        "fs/char_dev.c:base_probe",
        "fs/char_dev.c:base_probe",
        "fs/filesystems.c:get_fs_type",
        "fs/quota/dquot.c:vfs_load_quota_inode",
        "crypto/api.c:crypto_larval_lookup",
        "crypto/api.c:crypto_larval_lookup",
        "block/elevator.c:elevator_get",
        "block/elevator.c:load_default_elevator_module",
        "block/genhd.c:base_probe",
        "block/genhd.c:base_probe",
        "drivers/video/fbdev/core/fbmem.c:fb_open",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/char/misc.c:misc_open",
        "drivers/scsi/scsi_dh.c:scsi_dh_attach",
        "drivers/net/phy/phy_device.c:phy_device_create",
        "drivers/net/ppp/ppp_generic.c:ppp_set_compress",
        "drivers/md/md.c:md_setup_cluster",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:level_store",
        "drivers/md/dm-target.c:dm_get_target_type",
        "drivers/cpufreq/powernow-k8.c:powernowk8_init",
        "net/socket.c:__sock_create",
        "net/socket.c:sock_ioctl",
        "net/socket.c:sock_ioctl",
        "net/socket.c:sock_ioctl",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/lwtunnel.c:lwtunnel_valid_encap_type",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/sch_api.c:qdisc_set_default",
        "net/sched/cls_api.c:tc_ctl_tfilter",
        "net/sched/act_api.c:tcf_action_init_1",
        "net/sched/ematch.c:tcf_em_tree_validate",
        "net/netlink/af_netlink.c:netlink_create",
        "net/netlink/genetlink.c:ctrl_getfamily",
        "net/ipv4/tcp_cong.c:tcp_set_default_congestion_control",
        "net/xfrm/xfrm_state.c:__xfrm_init_state",
        "net/xfrm/xfrm_state.c:xfrm_get_mode",
        "net/ipv6/af_inet6.c:inet6_create",
        "net/ipv6/af_inet6.c:inet6_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579495200,
      "name": "__request_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 721
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int __request_module(bool wait, const char * fmt, void (anon))
```

```json
{
  "name": "__request_module",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579484912,
      "name": "__request_module",
      "external": true,
      "loc": "kernel/kmod.c:151",
      "file": "kernel/kmod.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zpool.c:zpool_create_pool",
        "mm/zpool.c:zpool_has_pool",
        "fs/char_dev.c:base_probe",
        "fs/char_dev.c:base_probe",
        "fs/filesystems.c:get_fs_type",
        "fs/quota/dquot.c:vfs_load_quota_inode",
        "block/elevator.c:elevator_get",
        "block/elevator.c:load_default_elevator_module",
        "block/genhd.c:base_probe",
        "block/genhd.c:base_probe",
        "drivers/pwm/core.c:pwm_get",
        "drivers/video/fbdev/core/fbmem.c:fb_open",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/char/misc.c:misc_open",
        "drivers/scsi/scsi_dh.c:scsi_dh_attach",
        "drivers/net/phy/phy_device.c:phy_device_create",
        "drivers/net/ppp/ppp_generic.c:ppp_set_compress",
        "drivers/md/md.c:md_setup_cluster",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:level_store",
        "drivers/md/dm-target.c:dm_get_target_type",
        "net/socket.c:__sock_create",
        "net/socket.c:sock_ioctl",
        "net/socket.c:sock_ioctl",
        "net/socket.c:sock_ioctl",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/sch_api.c:qdisc_set_default",
        "net/sched/cls_api.c:tc_ctl_tfilter",
        "net/sched/act_api.c:tcf_action_init_1",
        "net/sched/act_api.c:tcf_action_init_1",
        "net/netlink/af_netlink.c:netlink_create",
        "net/netlink/genetlink.c:ctrl_getfamily",
        "net/ipv4/tcp_cong.c:tcp_set_default_congestion_control",
        "net/ipv4/tcp_ulp.c:tcp_set_ulp",
        "net/xfrm/xfrm_state.c:__xfrm_init_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579484912,
      "name": "__request_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1123
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int __request_module(bool wait, const char * fmt, void (anon))
```

```json
{
  "name": "__request_module",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579569824,
      "name": "__request_module",
      "external": true,
      "loc": "kernel/kmod.c:125",
      "file": "kernel/kmod.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zpool.c:zpool_create_pool",
        "mm/zpool.c:zpool_has_pool",
        "fs/char_dev.c:base_probe",
        "fs/char_dev.c:base_probe",
        "fs/filesystems.c:get_fs_type",
        "fs/quota/dquot.c:vfs_load_quota_inode",
        "block/elevator.c:elevator_get",
        "block/elevator.c:load_default_elevator_module",
        "block/genhd.c:base_probe",
        "block/genhd.c:base_probe",
        "drivers/pwm/core.c:pwm_get",
        "drivers/video/fbdev/core/fbmem.c:fb_open",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/char/misc.c:misc_open",
        "drivers/scsi/scsi_dh.c:scsi_dh_attach",
        "drivers/net/phy/phy_device.c:phy_device_create",
        "drivers/net/ppp/ppp_generic.c:ppp_set_compress",
        "drivers/md/md.c:md_setup_cluster",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:level_store",
        "drivers/md/dm-target.c:dm_get_target_type",
        "net/socket.c:__sock_create",
        "net/socket.c:sock_ioctl",
        "net/socket.c:sock_ioctl",
        "net/socket.c:sock_ioctl",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/sch_api.c:qdisc_set_default",
        "net/sched/cls_api.c:tc_ctl_tfilter",
        "net/sched/act_api.c:tcf_action_init_1",
        "net/sched/act_api.c:tcf_action_init_1",
        "net/netlink/af_netlink.c:netlink_create",
        "net/netlink/genetlink.c:ctrl_getfamily",
        "net/ipv4/tcp_ulp.c:tcp_set_ulp",
        "net/xfrm/xfrm_state.c:__xfrm_init_state",
        "net/xfrm/xfrm_state.c:__xfrm_init_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579569824,
      "name": "__request_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1057
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
int __request_module(bool wait, const char * fmt, void (anon))
```

```json
{
  "name": "__request_module",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__request_module",
      "external": true,
      "loc": "kernel/kmod.c:125",
      "file": "kernel/kmod.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zpool.c:zpool_create_pool",
        "mm/zpool.c:zpool_has_pool",
        "fs/char_dev.c:base_probe",
        "fs/char_dev.c:base_probe",
        "fs/filesystems.c:get_fs_type",
        "fs/quota/dquot.c:vfs_load_quota_inode",
        "crypto/api.c:crypto_alg_mod_lookup",
        "crypto/api.c:crypto_alg_mod_lookup",
        "block/elevator.c:elevator_get",
        "block/elevator.c:load_default_elevator_module",
        "block/genhd.c:base_probe",
        "block/genhd.c:base_probe",
        "drivers/pwm/core.c:pwm_get",
        "drivers/video/fbdev/core/fbmem.c:fb_open",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/char/misc.c:misc_open",
        "drivers/scsi/scsi_dh.c:scsi_dh_attach",
        "drivers/net/phy/phy_device.c:phy_device_create",
        "drivers/net/ppp/ppp_generic.c:ppp_set_compress",
        "drivers/md/md.c:md_setup_cluster",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:level_store",
        "drivers/md/dm-target.c:dm_get_target_type",
        "net/socket.c:__sock_create",
        "net/socket.c:sock_ioctl",
        "net/socket.c:sock_ioctl",
        "net/socket.c:sock_ioctl",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/lwtunnel.c:lwtunnel_valid_encap_type",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/sch_api.c:qdisc_set_default",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/act_api.c:tcf_action_init_1",
        "net/netlink/af_netlink.c:netlink_create",
        "net/netlink/genetlink.c:ctrl_getfamily",
        "net/ipv4/tcp_ulp.c:tcp_set_ulp",
        "net/ipv4/bpfilter/sockopt.c:bpfilter_mbox_request",
        "net/xfrm/xfrm_state.c:__xfrm_init_state",
        "net/xfrm/xfrm_state.c:__xfrm_init_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579598963,
      "name": "__request_module.cold.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    },
    {
      "addr": 18446744071579598000,
      "name": "__request_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 963
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int __request_module(bool wait, const char * fmt, void (anon))
```

```json
{
  "name": "__request_module",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__request_module",
      "external": true,
      "loc": "kernel/kmod.c:125",
      "file": "kernel/kmod.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zpool.c:zpool_create_pool",
        "mm/zpool.c:zpool_has_pool",
        "fs/char_dev.c:base_probe",
        "fs/char_dev.c:base_probe",
        "fs/filesystems.c:get_fs_type",
        "fs/quota/dquot.c:vfs_load_quota_inode",
        "crypto/api.c:crypto_alg_mod_lookup",
        "crypto/api.c:crypto_alg_mod_lookup",
        "block/genhd.c:base_probe",
        "block/genhd.c:base_probe",
        "drivers/pwm/core.c:pwm_get",
        "drivers/video/fbdev/core/fbmem.c:fb_open",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/char/misc.c:misc_open",
        "drivers/scsi/scsi_dh.c:scsi_dh_attach",
        "drivers/net/phy/phy_device.c:phy_device_create",
        "drivers/net/phy/phy_device.c:phy_device_create",
        "drivers/net/ppp/ppp_generic.c:ppp_set_compress",
        "drivers/md/md.c:md_setup_cluster",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:level_store",
        "drivers/md/dm-target.c:dm_get_target_type",
        "net/socket.c:__sock_create",
        "net/socket.c:sock_ioctl",
        "net/socket.c:sock_ioctl",
        "net/socket.c:sock_ioctl",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/lwtunnel.c:lwtunnel_valid_encap_type",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/sch_api.c:qdisc_set_default",
        "net/sched/act_api.c:tcf_action_init_1",
        "net/sched/act_api.c:tcf_action_init_1",
        "net/netlink/af_netlink.c:netlink_create",
        "net/netlink/genetlink.c:ctrl_getfamily",
        "net/ipv4/tcp_ulp.c:tcp_set_ulp",
        "net/ipv4/bpfilter/sockopt.c:bpfilter_mbox_request",
        "net/xfrm/xfrm_state.c:__xfrm_init_state",
        "net/xfrm/xfrm_state.c:__xfrm_init_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579636048,
      "name": "__request_module.cold.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    },
    {
      "addr": 18446744071579635104,
      "name": "__request_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 944
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int __request_module(bool wait, const char * fmt, void (anon))
```

```json
{
  "name": "__request_module",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__request_module",
      "external": true,
      "loc": "kernel/kmod.c:125",
      "file": "kernel/kmod.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zpool.c:zpool_create_pool",
        "mm/zpool.c:zpool_has_pool",
        "fs/char_dev.c:base_probe",
        "fs/char_dev.c:base_probe",
        "fs/filesystems.c:get_fs_type",
        "fs/quota/dquot.c:vfs_load_quota_inode",
        "crypto/api.c:crypto_alg_mod_lookup",
        "crypto/api.c:crypto_alg_mod_lookup",
        "block/genhd.c:base_probe",
        "block/genhd.c:base_probe",
        "drivers/pwm/core.c:pwm_get",
        "drivers/video/fbdev/core/fbmem.c:fb_open",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl",
        "drivers/char/misc.c:misc_open",
        "drivers/scsi/scsi_dh.c:scsi_dh_attach",
        "drivers/net/phy/phy_device.c:phy_request_driver_module",
        "drivers/net/ppp/ppp_generic.c:ppp_set_compress",
        "drivers/md/md.c:md_setup_cluster",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:level_store",
        "drivers/md/dm-target.c:dm_get_target_type",
        "drivers/cpufreq/cpufreq.c:store_scaling_governor",
        "drivers/devfreq/devfreq.c:try_then_request_governor",
        "drivers/devfreq/devfreq.c:try_then_request_governor",
        "net/socket.c:__sock_create",
        "net/socket.c:sock_ioctl",
        "net/socket.c:sock_ioctl",
        "net/socket.c:sock_ioctl",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/lwtunnel.c:lwtunnel_valid_encap_type",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/sch_api.c:qdisc_set_default",
        "net/sched/act_api.c:tcf_action_init_1",
        "net/sched/act_api.c:tcf_action_init_1",
        "net/netlink/af_netlink.c:netlink_create",
        "net/netlink/genetlink.c:ctrl_getfamily",
        "net/ipv4/tcp_ulp.c:tcp_set_ulp",
        "net/ipv4/bpfilter/sockopt.c:bpfilter_mbox_request",
        "net/xfrm/xfrm_state.c:__xfrm_init_state",
        "net/xfrm/xfrm_state.c:__xfrm_init_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579660852,
      "name": "__request_module.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    },
    {
      "addr": 18446744071579659920,
      "name": "__request_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 932
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int __request_module(bool wait, const char * fmt, void (anon))
```

```json
{
  "name": "__request_module",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__request_module",
      "external": true,
      "loc": "kernel/kmod.c:125",
      "file": "kernel/kmod.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zpool.c:zpool_create_pool",
        "mm/zpool.c:zpool_has_pool",
        "fs/char_dev.c:base_probe",
        "fs/char_dev.c:base_probe",
        "fs/filesystems.c:get_fs_type",
        "fs/quota/dquot.c:vfs_load_quota_inode",
        "crypto/api.c:crypto_alg_mod_lookup",
        "crypto/api.c:crypto_alg_mod_lookup",
        "block/elevator.c:elevator_get",
        "block/genhd.c:base_probe",
        "block/genhd.c:base_probe",
        "drivers/pwm/core.c:pwm_get",
        "drivers/video/fbdev/core/fbmem.c:fb_open",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl",
        "drivers/char/misc.c:misc_open",
        "drivers/scsi/scsi_dh.c:scsi_dh_attach",
        "drivers/net/phy/phy_device.c:phy_request_driver_module",
        "drivers/net/ppp/ppp_generic.c:ppp_set_compress",
        "drivers/md/md.c:md_setup_cluster",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:level_store",
        "drivers/md/dm-target.c:dm_get_target_type",
        "drivers/cpufreq/cpufreq.c:store_scaling_governor",
        "net/socket.c:__sock_create",
        "net/socket.c:sock_ioctl",
        "net/socket.c:sock_ioctl",
        "net/socket.c:sock_ioctl",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/lwtunnel.c:lwtunnel_valid_encap_type",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/sch_api.c:qdisc_set_default",
        "net/sched/act_api.c:tcf_action_init_1",
        "net/sched/act_api.c:tcf_action_init_1",
        "net/netlink/af_netlink.c:netlink_create",
        "net/netlink/genetlink.c:ctrl_getfamily",
        "net/ipv4/tcp_ulp.c:tcp_set_ulp",
        "net/ipv4/bpfilter/sockopt.c:bpfilter_mbox_request",
        "net/xfrm/xfrm_state.c:__xfrm_init_state",
        "net/xfrm/xfrm_state.c:__xfrm_init_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579697924,
      "name": "__request_module.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    },
    {
      "addr": 18446744071579696992,
      "name": "__request_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 932
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int __request_module(bool wait, const char * fmt, void (anon))
```

```json
{
  "name": "__request_module",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__request_module",
      "external": true,
      "loc": "kernel/kmod.c:125",
      "file": "kernel/kmod.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zpool.c:zpool_create_pool",
        "mm/zpool.c:zpool_has_pool",
        "fs/char_dev.c:base_probe",
        "fs/char_dev.c:base_probe",
        "fs/exec.c:search_binary_handler",
        "fs/filesystems.c:get_fs_type",
        "fs/quota/dquot.c:find_quota_format",
        "fs/nls/nls_base.c:load_nls_default",
        "crypto/api.c:crypto_alg_mod_lookup",
        "crypto/api.c:crypto_alg_mod_lookup",
        "crypto/api.c:crypto_alg_mod_lookup",
        "block/elevator.c:elevator_get",
        "block/genhd.c:base_probe",
        "block/genhd.c:base_probe",
        "drivers/pwm/core.c:pwm_get",
        "drivers/video/fbdev/core/fbmem.c:fb_open",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl",
        "drivers/char/misc.c:misc_open",
        "drivers/scsi/scsi_dh.c:scsi_dh_attach",
        "drivers/net/phy/phy_device.c:phy_request_driver_module",
        "drivers/net/ppp/ppp_generic.c:ppp_set_compress",
        "drivers/md/md.c:md_setup_cluster",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:level_store",
        "drivers/md/dm-target.c:dm_get_target_type",
        "drivers/cpufreq/cpufreq.c:store_scaling_governor",
        "drivers/cpufreq/powernow-k8.c:__request_acpi_cpufreq",
        "net/socket.c:__sock_create",
        "net/socket.c:sock_ioctl",
        "net/socket.c:sock_ioctl",
        "net/socket.c:sock_ioctl",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/dev_ioctl.c:dev_load",
        "net/core/dev_ioctl.c:dev_load",
        "net/core/lwtunnel.c:lwtunnel_valid_encap_type",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/sch_api.c:qdisc_set_default",
        "net/sched/act_api.c:tcf_action_init_1",
        "net/sched/act_api.c:tcf_action_init_1",
        "net/netlink/af_netlink.c:netlink_create",
        "net/netlink/genetlink.c:ctrl_getfamily",
        "net/netfilter/nf_log.c:nf_logger_find_get",
        "net/ipv4/tcp_ulp.c:tcp_set_ulp",
        "net/ipv4/bpfilter/sockopt.c:bpfilter_mbox_request",
        "net/xfrm/xfrm_state.c:__xfrm_init_state",
        "net/xfrm/xfrm_state.c:__xfrm_init_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579738666,
      "name": "__request_module.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    },
    {
      "addr": 18446744071579737936,
      "name": "__request_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 730
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int __request_module(bool wait, const char * fmt, void (anon))
```

```json
{
  "name": "__request_module",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__request_module",
      "external": true,
      "loc": "kernel/kmod.c:124",
      "file": "kernel/kmod.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zpool.c:zpool_create_pool",
        "mm/zpool.c:zpool_has_pool",
        "fs/char_dev.c:base_probe",
        "fs/char_dev.c:base_probe",
        "fs/exec.c:search_binary_handler",
        "fs/filesystems.c:get_fs_type",
        "fs/quota/dquot.c:find_quota_format",
        "fs/nls/nls_base.c:load_nls_default",
        "crypto/api.c:crypto_alg_mod_lookup",
        "crypto/api.c:crypto_alg_mod_lookup",
        "crypto/api.c:crypto_alg_mod_lookup",
        "block/elevator.c:elevator_get",
        "block/genhd.c:blk_request_module",
        "block/genhd.c:blk_request_module",
        "drivers/pwm/core.c:pwm_get",
        "drivers/video/fbdev/core/fbmem.c:fb_open",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl",
        "drivers/char/misc.c:misc_open",
        "drivers/scsi/scsi_dh.c:scsi_dh_attach",
        "drivers/net/phy/phy_device.c:phy_request_driver_module",
        "drivers/net/ppp/ppp_generic.c:ppp_set_compress",
        "drivers/md/md.c:md_setup_cluster",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:level_store",
        "drivers/md/dm-target.c:dm_get_target_type",
        "drivers/cpufreq/cpufreq.c:store_scaling_governor",
        "drivers/cpufreq/powernow-k8.c:__request_acpi_cpufreq",
        "net/socket.c:__sock_create",
        "net/socket.c:sock_ioctl",
        "net/socket.c:sock_ioctl",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/dev_ioctl.c:dev_load",
        "net/core/dev_ioctl.c:dev_load",
        "net/core/lwtunnel.c:lwtunnel_valid_encap_type",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/sch_api.c:qdisc_set_default",
        "net/sched/act_api.c:tc_action_load_ops",
        "net/sched/act_api.c:tc_action_load_ops",
        "net/netlink/af_netlink.c:netlink_create",
        "net/netlink/genetlink.c:ctrl_getfamily",
        "net/netfilter/nf_log.c:nf_logger_find_get",
        "net/ipv4/tcp_ulp.c:tcp_set_ulp",
        "net/ipv4/bpfilter/sockopt.c:bpfilter_mbox_request",
        "net/xfrm/xfrm_state.c:__xfrm_init_state",
        "net/xfrm/xfrm_state.c:__xfrm_init_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591281630,
      "name": "__request_module.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    },
    {
      "addr": 18446744071579719504,
      "name": "__request_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 701
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int __request_module(bool wait, const char * fmt, void (anon))
```

```json
{
  "name": "__request_module",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__request_module",
      "external": true,
      "loc": "kernel/kmod.c:124",
      "file": "kernel/kmod.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zpool.c:zpool_create_pool",
        "mm/zpool.c:zpool_has_pool",
        "fs/char_dev.c:base_probe",
        "fs/char_dev.c:base_probe",
        "fs/exec.c:search_binary_handler",
        "fs/filesystems.c:get_fs_type",
        "fs/quota/dquot.c:dquot_load_quota_sb",
        "fs/nls/nls_base.c:load_nls_default",
        "crypto/api.c:crypto_alg_mod_lookup",
        "crypto/api.c:crypto_alg_mod_lookup",
        "crypto/api.c:crypto_alg_mod_lookup",
        "block/elevator.c:elevator_get",
        "block/genhd.c:blk_request_module",
        "block/genhd.c:blk_request_module",
        "drivers/pwm/core.c:pwm_get",
        "drivers/video/fbdev/core/fbmem.c:fb_open",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl",
        "drivers/char/misc.c:misc_open",
        "drivers/scsi/scsi_dh.c:scsi_dh_attach",
        "drivers/net/phy/phy_device.c:phy_request_driver_module",
        "drivers/net/ppp/ppp_generic.c:ppp_set_compress",
        "drivers/md/md.c:md_setup_cluster",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:level_store",
        "drivers/md/dm-target.c:dm_get_target_type",
        "drivers/cpufreq/cpufreq.c:store_scaling_governor",
        "net/socket.c:__sock_create",
        "net/socket.c:sock_ioctl",
        "net/socket.c:sock_ioctl",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/dev_ioctl.c:dev_load",
        "net/core/dev_ioctl.c:dev_load",
        "net/core/lwtunnel.c:lwtunnel_valid_encap_type",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/sch_api.c:qdisc_set_default",
        "net/sched/act_api.c:tc_action_load_ops",
        "net/sched/act_api.c:tc_action_load_ops",
        "net/netlink/af_netlink.c:netlink_create",
        "net/netlink/genetlink.c:ctrl_getfamily",
        "net/ipv4/tcp_ulp.c:tcp_set_ulp",
        "net/ipv4/bpfilter/sockopt.c:bpfilter_mbox_request",
        "net/xfrm/xfrm_state.c:__xfrm_init_state",
        "net/xfrm/xfrm_state.c:__xfrm_init_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591224577,
      "name": "__request_module.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
    },
    {
      "addr": 18446744071579726640,
      "name": "__request_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 908
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int __request_module(bool wait, const char * fmt, void (anon))
```

```json
{
  "name": "__request_module",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__request_module",
      "external": true,
      "loc": "kernel/kmod.c:124",
      "file": "kernel/kmod.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zpool.c:zpool_create_pool",
        "mm/zpool.c:zpool_has_pool",
        "fs/char_dev.c:base_probe",
        "fs/char_dev.c:base_probe",
        "fs/exec.c:search_binary_handler",
        "fs/filesystems.c:get_fs_type",
        "fs/quota/dquot.c:dquot_load_quota_sb",
        "fs/nls/nls_base.c:load_nls_default",
        "crypto/api.c:crypto_alg_mod_lookup",
        "crypto/api.c:crypto_alg_mod_lookup",
        "crypto/api.c:crypto_alg_mod_lookup",
        "block/elevator.c:elevator_get",
        "block/genhd.c:blk_request_module",
        "block/genhd.c:blk_request_module",
        "drivers/pwm/core.c:pwm_get",
        "drivers/video/fbdev/core/fbmem.c:fb_open",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl",
        "drivers/char/misc.c:misc_open",
        "drivers/scsi/scsi_dh.c:scsi_dh_attach",
        "drivers/net/phy/phy_device.c:phy_request_driver_module",
        "drivers/net/ppp/ppp_generic.c:ppp_set_compress",
        "drivers/md/md.c:md_setup_cluster",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:level_store",
        "drivers/md/dm-target.c:dm_get_target_type",
        "drivers/cpufreq/cpufreq.c:store_scaling_governor",
        "net/socket.c:__sock_create",
        "net/socket.c:sock_ioctl",
        "net/socket.c:br_ioctl_call",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/dev_ioctl.c:dev_load",
        "net/core/dev_ioctl.c:dev_load",
        "net/core/lwtunnel.c:lwtunnel_valid_encap_type",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/sch_api.c:qdisc_set_default",
        "net/sched/act_api.c:tc_action_load_ops",
        "net/sched/act_api.c:tc_action_load_ops",
        "net/netlink/af_netlink.c:netlink_create",
        "net/netlink/genetlink.c:ctrl_getfamily",
        "net/ipv4/tcp_ulp.c:tcp_set_ulp",
        "net/ipv4/bpfilter/sockopt.c:bpfilter_mbox_request",
        "net/xfrm/xfrm_state.c:__xfrm_init_state",
        "net/xfrm/xfrm_state.c:__xfrm_init_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592106303,
      "name": "__request_module.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
    },
    {
      "addr": 18446744071579806688,
      "name": "__request_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 908
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int __request_module(bool wait, const char * fmt, void (anon))
```

```json
{
  "name": "__request_module",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__request_module",
      "external": true,
      "loc": "kernel/kmod.c:124",
      "file": "kernel/kmod.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zpool.c:zpool_create_pool",
        "mm/zpool.c:zpool_has_pool",
        "fs/char_dev.c:base_probe",
        "fs/char_dev.c:base_probe",
        "fs/exec.c:search_binary_handler",
        "fs/filesystems.c:get_fs_type",
        "fs/quota/dquot.c:dquot_load_quota_sb",
        "fs/nls/nls_base.c:load_nls_default",
        "fs/unicode/utf8-core.c:utf8_load",
        "crypto/api.c:crypto_alg_mod_lookup",
        "crypto/api.c:crypto_alg_mod_lookup",
        "crypto/api.c:crypto_alg_mod_lookup",
        "crypto/api.c:crypto_wait_for_test",
        "block/elevator.c:elevator_get",
        "block/genhd.c:blk_request_module",
        "block/genhd.c:blk_request_module",
        "drivers/pwm/core.c:pwm_get",
        "drivers/video/fbdev/core/fbmem.c:fb_open",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl",
        "drivers/char/misc.c:misc_open",
        "drivers/scsi/scsi_dh.c:scsi_dh_attach",
        "drivers/net/phy/phy_device.c:phy_request_driver_module",
        "drivers/net/ppp/ppp_generic.c:ppp_set_compress",
        "drivers/md/md.c:md_setup_cluster",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:level_store",
        "drivers/md/dm-target.c:dm_get_target_type",
        "drivers/cpufreq/cpufreq.c:store_scaling_governor",
        "drivers/cpufreq/powernow-k8.c:powernowk8_init",
        "net/socket.c:__sock_create",
        "net/socket.c:sock_ioctl",
        "net/socket.c:br_ioctl_call",
        "net/core/sock.c:sock_load_diag_module",
        "net/core/sock.c:sock_load_diag_module",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/lwtunnel.c:lwtunnel_valid_encap_type",
        "net/sched/sch_api.c:qdisc_set_default",
        "net/sched/act_api.c:tc_action_load_ops",
        "net/sched/act_api.c:tc_action_load_ops",
        "net/netlink/af_netlink.c:netlink_create",
        "net/netlink/genetlink.c:ctrl_getfamily",
        "net/ipv4/tcp_ulp.c:tcp_set_ulp",
        "net/ipv4/bpfilter/sockopt.c:bpfilter_mbox_request",
        "net/xfrm/xfrm_state.c:__xfrm_init_state",
        "net/xfrm/xfrm_state.c:__xfrm_init_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593873978,
      "name": "__request_module.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    },
    {
      "addr": 18446744071579916784,
      "name": "__request_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1007
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int __request_module(bool wait, const char * fmt, void (anon))
```

```json
{
  "name": "__request_module",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580071184,
      "name": "__request_module",
      "external": true,
      "loc": "kernel/kmod.c:124",
      "file": "kernel/kmod.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zpool.c:zpool_create_pool",
        "mm/zpool.c:zpool_has_pool",
        "fs/char_dev.c:base_probe",
        "fs/char_dev.c:base_probe",
        "fs/exec.c:search_binary_handler",
        "fs/filesystems.c:get_fs_type",
        "fs/quota/dquot.c:dquot_load_quota_sb",
        "fs/nls/nls_base.c:load_nls_default",
        "fs/unicode/utf8-core.c:utf8_load",
        "crypto/api.c:crypto_alg_mod_lookup",
        "crypto/api.c:crypto_alg_mod_lookup",
        "crypto/api.c:crypto_alg_mod_lookup",
        "crypto/api.c:crypto_wait_for_test",
        "block/elevator.c:elv_iosched_store",
        "block/genhd.c:blk_request_module",
        "block/genhd.c:blk_request_module",
        "drivers/pwm/core.c:pwm_get",
        "drivers/video/fbdev/core/fbmem.c:fb_open",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl",
        "drivers/char/misc.c:misc_open",
        "drivers/scsi/scsi_dh.c:scsi_dh_attach",
        "drivers/net/phy/phy_device.c:phy_request_driver_module",
        "drivers/net/ppp/ppp_generic.c:ppp_set_compress",
        "drivers/md/md.c:md_setup_cluster",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:level_store",
        "drivers/md/dm-target.c:dm_get_target_type",
        "drivers/cpufreq/cpufreq.c:store_scaling_governor",
        "drivers/cpufreq/powernow-k8.c:powernowk8_init",
        "net/socket.c:__sock_create",
        "net/socket.c:sock_ioctl",
        "net/socket.c:br_ioctl_call",
        "net/core/sock.c:sock_load_diag_module",
        "net/core/sock.c:sock_load_diag_module",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/lwtunnel.c:lwtunnel_valid_encap_type",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/sch_api.c:qdisc_set_default",
        "net/sched/act_api.c:tc_action_load_ops",
        "net/sched/act_api.c:tc_action_load_ops",
        "net/netlink/af_netlink.c:netlink_create",
        "net/netlink/genetlink.c:ctrl_getfamily",
        "net/ipv4/tcp_ulp.c:tcp_set_ulp",
        "net/ipv4/bpfilter/sockopt.c:bpfilter_mbox_request",
        "net/xfrm/xfrm_state.c:__xfrm_init_state",
        "net/xfrm/xfrm_state.c:__xfrm_init_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580071184,
      "name": "__request_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1069
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int __request_module(bool wait, const char * fmt, void (anon))
```

```json
{
  "name": "__request_module",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580816976,
      "name": "__request_module",
      "external": true,
      "loc": "kernel/module/kmod.c:132",
      "file": "kernel/module/kmod.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zpool.c:zpool_create_pool",
        "mm/zpool.c:zpool_has_pool",
        "fs/char_dev.c:base_probe",
        "fs/char_dev.c:base_probe",
        "fs/exec.c:search_binary_handler",
        "fs/filesystems.c:get_fs_type",
        "fs/quota/dquot.c:dquot_load_quota_sb",
        "fs/nls/nls_base.c:load_nls_default",
        "fs/unicode/utf8-core.c:utf8_load",
        "crypto/api.c:crypto_alg_mod_lookup",
        "crypto/api.c:crypto_alg_mod_lookup",
        "crypto/api.c:crypto_alg_mod_lookup",
        "crypto/api.c:crypto_wait_for_test",
        "block/elevator.c:elv_iosched_store",
        "block/genhd.c:blk_request_module",
        "block/genhd.c:blk_request_module",
        "drivers/pwm/core.c:pwm_get",
        "drivers/video/fbdev/core/fbmem.c:fb_open",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl",
        "drivers/char/misc.c:misc_open",
        "drivers/scsi/scsi_dh.c:scsi_dh_attach",
        "drivers/net/phy/phy_device.c:phy_request_driver_module",
        "drivers/net/ppp/ppp_generic.c:ppp_set_compress",
        "drivers/md/md.c:md_setup_cluster",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:level_store",
        "drivers/md/dm-target.c:dm_get_target_type",
        "drivers/cpufreq/cpufreq.c:store_scaling_governor",
        "drivers/cpufreq/powernow-k8.c:powernowk8_init",
        "net/socket.c:__sock_create",
        "net/socket.c:sock_ioctl",
        "net/socket.c:br_ioctl_call",
        "net/core/sock.c:sock_load_diag_module",
        "net/core/sock.c:sock_load_diag_module",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/lwtunnel.c:lwtunnel_valid_encap_type",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/sch_api.c:qdisc_set_default",
        "net/sched/act_api.c:tc_action_load_ops",
        "net/sched/act_api.c:tc_action_load_ops",
        "net/netlink/af_netlink.c:netlink_create",
        "net/netlink/genetlink.c:ctrl_getfamily",
        "net/ipv4/tcp_ulp.c:tcp_set_ulp",
        "net/ipv4/bpfilter/sockopt.c:bpfilter_mbox_request",
        "net/xfrm/xfrm_state.c:__xfrm_init_state",
        "net/xfrm/xfrm_state.c:__xfrm_init_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580816976,
      "name": "__request_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 705
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int __request_module(bool wait, const char * fmt, void (anon))
```

```json
{
  "name": "__request_module",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580906368,
      "name": "__request_module",
      "external": true,
      "loc": "kernel/module/kmod.c:132",
      "file": "kernel/module/kmod.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zpool.c:zpool_create_pool",
        "mm/zpool.c:zpool_has_pool",
        "fs/char_dev.c:base_probe",
        "fs/char_dev.c:base_probe",
        "fs/exec.c:search_binary_handler",
        "fs/filesystems.c:get_fs_type",
        "fs/quota/dquot.c:dquot_load_quota_sb",
        "fs/nls/nls_base.c:load_nls_default",
        "fs/unicode/utf8-core.c:utf8_load",
        "crypto/api.c:crypto_alg_mod_lookup",
        "crypto/api.c:crypto_alg_mod_lookup",
        "crypto/api.c:crypto_alg_mod_lookup",
        "crypto/api.c:crypto_wait_for_test",
        "block/elevator.c:elv_iosched_store",
        "block/genhd.c:blk_request_module",
        "block/genhd.c:blk_request_module",
        "drivers/pwm/core.c:pwm_get",
        "drivers/video/fbdev/core/fb_chrdev.c:fb_open",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl",
        "drivers/char/misc.c:misc_open",
        "drivers/scsi/scsi_dh.c:scsi_dh_attach",
        "drivers/gpu/drm/drm_encoder_slave.c:drm_i2c_encoder_init",
        "drivers/net/phy/phy_device.c:phy_request_driver_module",
        "drivers/net/ppp/ppp_generic.c:ppp_set_compress",
        "drivers/md/md.c:md_setup_cluster",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:level_store",
        "drivers/md/dm-target.c:dm_get_target_type",
        "drivers/cpufreq/cpufreq.c:store_scaling_governor",
        "drivers/cpufreq/powernow-k8.c:powernowk8_init",
        "net/socket.c:__sock_create",
        "net/socket.c:sock_ioctl",
        "net/socket.c:br_ioctl_call",
        "net/core/sock.c:sock_load_diag_module",
        "net/core/sock.c:sock_load_diag_module",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/lwtunnel.c:lwtunnel_valid_encap_type",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/sch_api.c:qdisc_set_default",
        "net/sched/act_api.c:tc_action_load_ops",
        "net/sched/act_api.c:tc_action_load_ops",
        "net/netlink/af_netlink.c:netlink_create",
        "net/netlink/genetlink.c:ctrl_getfamily",
        "net/netfilter/nf_bpf_link.c:get_proto_defrag_hook",
        "net/ipv4/tcp_ulp.c:tcp_set_ulp",
        "net/xfrm/xfrm_state.c:__xfrm_init_state",
        "net/xfrm/xfrm_state.c:__xfrm_init_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580906368,
      "name": "__request_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 754
    }
  ]
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
int __request_module(bool wait, const char * fmt, void (anon))
```

```json
{
  "name": "__request_module",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490878160,
      "name": "__request_module",
      "external": true,
      "loc": "kernel/kmod.c:125",
      "file": "kernel/kmod.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zpool.c:zpool_create_pool",
        "mm/zpool.c:zpool_has_pool",
        "fs/char_dev.c:base_probe",
        "fs/char_dev.c:base_probe",
        "fs/filesystems.c:get_fs_type",
        "fs/quota/dquot.c:vfs_load_quota_inode",
        "crypto/api.c:crypto_alg_mod_lookup",
        "crypto/api.c:crypto_alg_mod_lookup",
        "block/genhd.c:base_probe",
        "block/genhd.c:base_probe",
        "drivers/pwm/core.c:pwm_get",
        "drivers/video/fbdev/core/fbmem.c:fb_open",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl",
        "drivers/char/misc.c:misc_open",
        "drivers/scsi/scsi_dh.c:scsi_dh_attach",
        "drivers/net/phy/phy_device.c:phy_request_driver_module",
        "drivers/net/ppp/ppp_generic.c:ppp_set_compress",
        "drivers/md/md.c:md_setup_cluster",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:level_store",
        "drivers/md/dm-target.c:dm_get_target_type",
        "drivers/cpufreq/cpufreq.c:store_scaling_governor",
        "drivers/of/device.c:of_device_request_module",
        "drivers/devfreq/devfreq.c:try_then_request_governor",
        "drivers/devfreq/devfreq.c:try_then_request_governor",
        "net/socket.c:__sock_create",
        "net/socket.c:sock_ioctl",
        "net/socket.c:sock_ioctl",
        "net/socket.c:sock_ioctl",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/lwtunnel.c:lwtunnel_valid_encap_type",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/sch_api.c:qdisc_set_default",
        "net/sched/act_api.c:tcf_action_init_1",
        "net/sched/act_api.c:tcf_action_init_1",
        "net/netlink/af_netlink.c:netlink_create",
        "net/netlink/genetlink.c:ctrl_getfamily",
        "net/ipv4/tcp_ulp.c:tcp_set_ulp",
        "net/ipv4/bpfilter/sockopt.c:bpfilter_mbox_request",
        "net/xfrm/xfrm_state.c:__xfrm_init_state",
        "net/xfrm/xfrm_state.c:__xfrm_init_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490878160,
      "name": "__request_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1176
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int __request_module(bool wait, const char * fmt, void (anon))
```

```json
{
  "name": "__request_module",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224894904,
      "name": "__request_module",
      "external": true,
      "loc": "kernel/kmod.c:125",
      "file": "kernel/kmod.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zpool.c:zpool_create_pool",
        "mm/zpool.c:zpool_has_pool",
        "fs/char_dev.c:base_probe",
        "fs/char_dev.c:base_probe",
        "fs/filesystems.c:get_fs_type",
        "fs/quota/dquot.c:vfs_load_quota_inode",
        "crypto/api.c:crypto_alg_mod_lookup",
        "crypto/api.c:crypto_alg_mod_lookup",
        "block/elevator.c:elevator_get",
        "block/genhd.c:base_probe",
        "block/genhd.c:base_probe",
        "drivers/pwm/core.c:pwm_get",
        "drivers/video/fbdev/core/fbmem.c:fb_open",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl",
        "drivers/char/misc.c:misc_open",
        "drivers/scsi/scsi_dh.c:scsi_dh_attach",
        "drivers/mtd/mtdpart.c:parse_mtd_partitions",
        "drivers/mtd/mtdpart.c:parse_mtd_partitions",
        "drivers/mtd/chips/chipreg.c:do_map_probe",
        "drivers/net/phy/phy_device.c:phy_request_driver_module",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/md/md.c:md_setup_cluster",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:level_store",
        "drivers/md/dm-target.c:dm_get_target_type",
        "drivers/cpufreq/cpufreq.c:store_scaling_governor",
        "drivers/of/device.c:of_device_request_module",
        "sound/sound_core.c:soundcore_open",
        "sound/sound_core.c:soundcore_open",
        "sound/sound_core.c:soundcore_open",
        "sound/sound_core.c:soundcore_open",
        "sound/core/sound.c:snd_open",
        "sound/core/timer.c:snd_timer_open",
        "sound/core/timer.c:snd_timer_open",
        "net/socket.c:__sock_create",
        "net/socket.c:sock_ioctl",
        "net/socket.c:sock_ioctl",
        "net/socket.c:sock_ioctl",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/lwtunnel.c:lwtunnel_valid_encap_type",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/sch_api.c:qdisc_set_default",
        "net/sched/act_api.c:tcf_action_init_1",
        "net/sched/act_api.c:tcf_action_init_1",
        "net/netlink/af_netlink.c:netlink_create",
        "net/netlink/genetlink.c:ctrl_getfamily",
        "net/ipv4/tcp_ulp.c:tcp_set_ulp",
        "net/ipv4/bpfilter/sockopt.c:bpfilter_mbox_request",
        "net/xfrm/xfrm_state.c:__xfrm_init_state",
        "net/xfrm/xfrm_state.c:__xfrm_init_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224894904,
      "name": "__request_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1168
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int __request_module(bool wait, const char * fmt, void (anon))
```

```json
{
  "name": "__request_module",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283710848,
      "name": "__request_module",
      "external": true,
      "loc": "kernel/kmod.c:125",
      "file": "kernel/kmod.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zpool.c:zpool_create_pool",
        "mm/zpool.c:zpool_has_pool",
        "fs/char_dev.c:base_probe",
        "fs/char_dev.c:base_probe",
        "fs/filesystems.c:get_fs_type",
        "fs/quota/dquot.c:vfs_load_quota_inode",
        "crypto/api.c:crypto_alg_mod_lookup",
        "crypto/api.c:crypto_alg_mod_lookup",
        "block/elevator.c:elevator_get",
        "block/genhd.c:base_probe",
        "block/genhd.c:base_probe",
        "drivers/pwm/core.c:pwm_get",
        "drivers/video/fbdev/core/fbmem.c:fb_open",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl",
        "drivers/char/misc.c:misc_open",
        "drivers/scsi/scsi_dh.c:scsi_dh_attach",
        "drivers/net/phy/phy_device.c:phy_request_driver_module",
        "drivers/net/ppp/ppp_generic.c:ppp_set_compress",
        "drivers/md/md.c:md_setup_cluster",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:level_store",
        "drivers/md/dm-target.c:dm_get_target_type",
        "drivers/cpufreq/cpufreq.c:store_scaling_governor",
        "drivers/of/device.c:of_device_request_module",
        "net/socket.c:__sock_create",
        "net/socket.c:sock_ioctl",
        "net/socket.c:sock_ioctl",
        "net/socket.c:sock_ioctl",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/lwtunnel.c:lwtunnel_valid_encap_type",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/sch_api.c:qdisc_set_default",
        "net/sched/act_api.c:tcf_action_init_1",
        "net/sched/act_api.c:tcf_action_init_1",
        "net/netlink/af_netlink.c:netlink_create",
        "net/netlink/genetlink.c:ctrl_getfamily",
        "net/ipv4/tcp_ulp.c:tcp_set_ulp",
        "net/ipv4/bpfilter/sockopt.c:bpfilter_mbox_request",
        "net/xfrm/xfrm_state.c:__xfrm_init_state",
        "net/xfrm/xfrm_state.c:__xfrm_init_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283710848,
      "name": "__request_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1384
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int __request_module(bool wait, const char * fmt, void (anon))
```

```json
{
  "name": "__request_module",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271530528,
      "name": "__request_module",
      "external": true,
      "loc": "kernel/kmod.c:125",
      "file": "kernel/kmod.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zpool.c:zpool_create_pool",
        "mm/zpool.c:zpool_has_pool",
        "fs/char_dev.c:base_probe",
        "fs/char_dev.c:base_probe",
        "fs/filesystems.c:get_fs_type",
        "fs/quota/dquot.c:vfs_load_quota_inode",
        "crypto/api.c:crypto_alg_mod_lookup",
        "crypto/api.c:crypto_alg_mod_lookup",
        "block/elevator.c:elevator_get",
        "block/genhd.c:base_probe",
        "block/genhd.c:base_probe",
        "drivers/pwm/core.c:pwm_get",
        "drivers/video/fbdev/core/fbmem.c:fb_open",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl",
        "drivers/char/misc.c:misc_open",
        "drivers/scsi/scsi_dh.c:scsi_dh_attach",
        "drivers/net/phy/phy_device.c:phy_request_driver_module",
        "drivers/net/ppp/ppp_generic.c:ppp_set_compress",
        "drivers/md/md.c:md_setup_cluster",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:level_store",
        "drivers/md/dm-target.c:dm_get_target_type",
        "drivers/of/device.c:of_device_request_module",
        "net/socket.c:__sock_create",
        "net/socket.c:sock_ioctl",
        "net/socket.c:sock_ioctl",
        "net/socket.c:sock_ioctl",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/lwtunnel.c:lwtunnel_valid_encap_type",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/sch_api.c:qdisc_set_default",
        "net/sched/act_api.c:tcf_action_init_1",
        "net/sched/act_api.c:tcf_action_init_1",
        "net/netlink/af_netlink.c:netlink_create",
        "net/netlink/genetlink.c:ctrl_getfamily",
        "net/ipv4/tcp_ulp.c:tcp_set_ulp",
        "net/ipv4/bpfilter/sockopt.c:bpfilter_mbox_request",
        "net/xfrm/xfrm_state.c:__xfrm_init_state",
        "net/xfrm/xfrm_state.c:__xfrm_init_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271530528,
      "name": "__request_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 892
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int __request_module(bool wait, const char * fmt, void (anon))
```

```json
{
  "name": "__request_module",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__request_module",
      "external": true,
      "loc": "kernel/kmod.c:125",
      "file": "kernel/kmod.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zpool.c:zpool_create_pool",
        "mm/zpool.c:zpool_has_pool",
        "fs/char_dev.c:base_probe",
        "fs/char_dev.c:base_probe",
        "fs/filesystems.c:get_fs_type",
        "fs/quota/dquot.c:vfs_load_quota_inode",
        "crypto/api.c:crypto_alg_mod_lookup",
        "crypto/api.c:crypto_alg_mod_lookup",
        "block/elevator.c:elevator_get",
        "block/genhd.c:base_probe",
        "block/genhd.c:base_probe",
        "drivers/pwm/core.c:pwm_get",
        "drivers/video/fbdev/core/fbmem.c:fb_open",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl",
        "drivers/char/misc.c:misc_open",
        "drivers/scsi/scsi_dh.c:scsi_dh_attach",
        "drivers/net/phy/phy_device.c:phy_request_driver_module",
        "drivers/net/ppp/ppp_generic.c:ppp_set_compress",
        "drivers/md/md.c:md_setup_cluster",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:level_store",
        "drivers/md/dm-target.c:dm_get_target_type",
        "drivers/cpufreq/cpufreq.c:store_scaling_governor",
        "net/socket.c:__sock_create",
        "net/socket.c:sock_ioctl",
        "net/socket.c:sock_ioctl",
        "net/socket.c:sock_ioctl",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/lwtunnel.c:lwtunnel_valid_encap_type",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/sch_api.c:qdisc_set_default",
        "net/sched/act_api.c:tcf_action_init_1",
        "net/sched/act_api.c:tcf_action_init_1",
        "net/netlink/af_netlink.c:netlink_create",
        "net/netlink/genetlink.c:ctrl_getfamily",
        "net/ipv4/tcp_ulp.c:tcp_set_ulp",
        "net/ipv4/bpfilter/sockopt.c:bpfilter_mbox_request",
        "net/xfrm/xfrm_state.c:__xfrm_init_state",
        "net/xfrm/xfrm_state.c:__xfrm_init_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579674244,
      "name": "__request_module.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    },
    {
      "addr": 18446744071579673312,
      "name": "__request_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 932
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int __request_module(bool wait, const char * fmt, void (anon))
```

```json
{
  "name": "__request_module",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__request_module",
      "external": true,
      "loc": "kernel/kmod.c:125",
      "file": "kernel/kmod.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zpool.c:zpool_create_pool",
        "mm/zpool.c:zpool_has_pool",
        "fs/char_dev.c:base_probe",
        "fs/char_dev.c:base_probe",
        "fs/filesystems.c:get_fs_type",
        "fs/quota/dquot.c:vfs_load_quota_inode",
        "crypto/api.c:crypto_alg_mod_lookup",
        "crypto/api.c:crypto_alg_mod_lookup",
        "block/elevator.c:elevator_get",
        "block/genhd.c:base_probe",
        "block/genhd.c:base_probe",
        "drivers/video/fbdev/core/fbmem.c:fb_open",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl",
        "drivers/char/misc.c:misc_open",
        "drivers/scsi/scsi_dh.c:scsi_dh_attach",
        "drivers/net/phy/phy_device.c:phy_request_driver_module",
        "drivers/net/ppp/ppp_generic.c:ppp_set_compress",
        "drivers/md/md.c:md_setup_cluster",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:level_store",
        "drivers/md/dm-target.c:dm_get_target_type",
        "drivers/cpufreq/cpufreq.c:store_scaling_governor",
        "net/socket.c:__sock_create",
        "net/socket.c:sock_ioctl",
        "net/socket.c:sock_ioctl",
        "net/socket.c:sock_ioctl",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/lwtunnel.c:lwtunnel_valid_encap_type",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/sch_api.c:qdisc_set_default",
        "net/sched/act_api.c:tcf_action_init_1",
        "net/sched/act_api.c:tcf_action_init_1",
        "net/netlink/af_netlink.c:netlink_create",
        "net/netlink/genetlink.c:ctrl_getfamily",
        "net/ipv4/tcp_ulp.c:tcp_set_ulp",
        "net/ipv4/bpfilter/sockopt.c:bpfilter_mbox_request",
        "net/xfrm/xfrm_state.c:__xfrm_init_state",
        "net/xfrm/xfrm_state.c:__xfrm_init_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579602580,
      "name": "__request_module.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    },
    {
      "addr": 18446744071579601648,
      "name": "__request_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 932
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int __request_module(bool wait, const char * fmt, void (anon))
```

```json
{
  "name": "__request_module",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__request_module",
      "external": true,
      "loc": "kernel/kmod.c:125",
      "file": "kernel/kmod.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zpool.c:zpool_create_pool",
        "mm/zpool.c:zpool_has_pool",
        "fs/char_dev.c:base_probe",
        "fs/char_dev.c:base_probe",
        "fs/filesystems.c:get_fs_type",
        "fs/quota/dquot.c:vfs_load_quota_inode",
        "crypto/api.c:crypto_alg_mod_lookup",
        "crypto/api.c:crypto_alg_mod_lookup",
        "block/elevator.c:elevator_get",
        "block/genhd.c:base_probe",
        "block/genhd.c:base_probe",
        "drivers/pwm/core.c:pwm_get",
        "drivers/video/fbdev/core/fbmem.c:fb_open",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl",
        "drivers/char/misc.c:misc_open",
        "drivers/scsi/scsi_dh.c:scsi_dh_attach",
        "drivers/net/phy/phy_device.c:phy_request_driver_module",
        "drivers/net/ppp/ppp_generic.c:ppp_set_compress",
        "drivers/md/md.c:md_setup_cluster",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:level_store",
        "drivers/md/dm-target.c:dm_get_target_type",
        "drivers/cpufreq/cpufreq.c:store_scaling_governor",
        "net/socket.c:__sock_create",
        "net/socket.c:sock_ioctl",
        "net/socket.c:sock_ioctl",
        "net/socket.c:sock_ioctl",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/lwtunnel.c:lwtunnel_valid_encap_type",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/sch_api.c:qdisc_set_default",
        "net/sched/act_api.c:tcf_action_init_1",
        "net/sched/act_api.c:tcf_action_init_1",
        "net/netlink/af_netlink.c:netlink_create",
        "net/netlink/genetlink.c:ctrl_getfamily",
        "net/netfilter/nfnetlink.c:nfnetlink_rcv_batch",
        "net/netfilter/nfnetlink.c:nfnetlink_rcv_msg",
        "net/netfilter/nfnetlink_queue.c:nfqnl_recv_config",
        "net/netfilter/nfnetlink_log.c:nfulnl_recv_config",
        "net/netfilter/nf_conntrack_helper.c:nf_nat_helper_try_module_get",
        "net/netfilter/nf_conntrack_helper.c:nf_conntrack_helper_try_module_get",
        "net/netfilter/nf_conntrack_proto.c:nf_ct_netns_do_get",
        "net/netfilter/nf_conntrack_netlink.c:ctnetlink_create_expect",
        "net/netfilter/nf_conntrack_netlink.c:ctnetlink_create_conntrack",
        "net/ipv4/tcp_ulp.c:tcp_set_ulp",
        "net/ipv4/bpfilter/sockopt.c:bpfilter_mbox_request",
        "net/xfrm/xfrm_state.c:__xfrm_init_state",
        "net/xfrm/xfrm_state.c:__xfrm_init_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579671476,
      "name": "__request_module.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    },
    {
      "addr": 18446744071579670544,
      "name": "__request_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 932
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int __request_module(bool wait, const char * fmt, void (anon))
```

```json
{
  "name": "__request_module",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__request_module",
      "external": true,
      "loc": "kernel/kmod.c:125",
      "file": "kernel/kmod.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zpool.c:zpool_create_pool",
        "mm/zpool.c:zpool_has_pool",
        "fs/char_dev.c:base_probe",
        "fs/char_dev.c:base_probe",
        "fs/filesystems.c:get_fs_type",
        "fs/quota/dquot.c:vfs_load_quota_inode",
        "crypto/api.c:crypto_alg_mod_lookup",
        "crypto/api.c:crypto_alg_mod_lookup",
        "block/elevator.c:elevator_get",
        "block/genhd.c:base_probe",
        "block/genhd.c:base_probe",
        "drivers/pwm/core.c:pwm_get",
        "drivers/video/fbdev/core/fbmem.c:fb_open",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl",
        "drivers/char/misc.c:misc_open",
        "drivers/scsi/scsi_dh.c:scsi_dh_attach",
        "drivers/net/phy/phy_device.c:phy_request_driver_module",
        "drivers/net/ppp/ppp_generic.c:ppp_set_compress",
        "drivers/md/md.c:md_setup_cluster",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:level_store",
        "drivers/md/dm-target.c:dm_get_target_type",
        "drivers/cpufreq/cpufreq.c:store_scaling_governor",
        "net/socket.c:__sock_create",
        "net/socket.c:sock_ioctl",
        "net/socket.c:sock_ioctl",
        "net/socket.c:sock_ioctl",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/lwtunnel.c:lwtunnel_valid_encap_type",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/sch_api.c:qdisc_set_default",
        "net/sched/act_api.c:tcf_action_init_1",
        "net/sched/act_api.c:tcf_action_init_1",
        "net/netlink/af_netlink.c:netlink_create",
        "net/netlink/genetlink.c:ctrl_getfamily",
        "net/ipv4/tcp_ulp.c:tcp_set_ulp",
        "net/ipv4/bpfilter/sockopt.c:bpfilter_mbox_request",
        "net/xfrm/xfrm_state.c:__xfrm_init_state",
        "net/xfrm/xfrm_state.c:__xfrm_init_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579705608,
      "name": "__request_module.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    },
    {
      "addr": 18446744071579704656,
      "name": "__request_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 952
    }
  ]
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
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
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
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
