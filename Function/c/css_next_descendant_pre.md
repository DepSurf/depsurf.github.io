# Function: <code>css_next_descendant_pre</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct cgroup_subsys_state * css_next_descendant_pre(struct cgroup_subsys_state * pos, struct cgroup_subsys_state * root)
```

```json
{
  "name": "css_next_descendant_pre",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579984496,
      "name": "css_next_descendant_pre",
      "external": true,
      "loc": "kernel/cgroup.c:3833",
      "file": "kernel/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup_freezer.c:freezer_write",
        "kernel/cgroup_freezer.c:freezer_write",
        "kernel/cpuset.c:update_domain_attr_tree",
        "kernel/cpuset.c:update_domain_attr_tree",
        "kernel/cpuset.c:generate_sched_domains",
        "kernel/cpuset.c:generate_sched_domains",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cpuset.c:cpuset_hotplug_workfn",
        "mm/memcontrol.c:mem_cgroup_css_offline",
        "mm/memcontrol.c:mem_cgroup_css_offline",
        "mm/memcontrol.c:mem_cgroup_iter",
        "security/device_cgroup.c:devcgroup_access_write",
        "security/device_cgroup.c:devcgroup_access_write",
        "block/blk-cgroup.c:blkg_stat_recursive_sum",
        "block/blk-cgroup.c:blkg_stat_recursive_sum",
        "block/blk-cgroup.c:blkg_rwstat_recursive_sum",
        "block/blk-cgroup.c:blkg_rwstat_recursive_sum",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579984496,
      "name": "css_next_descendant_pre",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct cgroup_subsys_state * css_next_descendant_pre(struct cgroup_subsys_state * pos, struct cgroup_subsys_state * root)
```

```json
{
  "name": "css_next_descendant_pre",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580011648,
      "name": "css_next_descendant_pre",
      "external": true,
      "loc": "kernel/cgroup.c:4022",
      "file": "kernel/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup_freezer.c:freezer_write",
        "kernel/cgroup_freezer.c:freezer_write",
        "kernel/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/cpuset.c:generate_sched_domains",
        "kernel/cpuset.c:generate_sched_domains",
        "kernel/cpuset.c:update_domain_attr_tree",
        "kernel/cpuset.c:update_domain_attr_tree",
        "mm/memcontrol.c:mem_cgroup_iter",
        "security/device_cgroup.c:devcgroup_access_write",
        "security/device_cgroup.c:devcgroup_access_write",
        "block/blk-cgroup.c:blkg_rwstat_recursive_sum",
        "block/blk-cgroup.c:blkg_rwstat_recursive_sum",
        "block/blk-cgroup.c:blkg_stat_recursive_sum",
        "block/blk-cgroup.c:blkg_stat_recursive_sum",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580011648,
      "name": "css_next_descendant_pre",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct cgroup_subsys_state * css_next_descendant_pre(struct cgroup_subsys_state * pos, struct cgroup_subsys_state * root)
```

```json
{
  "name": "css_next_descendant_pre",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580045232,
      "name": "css_next_descendant_pre",
      "external": true,
      "loc": "kernel/cgroup.c:4033",
      "file": "kernel/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup_freezer.c:freezer_write",
        "kernel/cgroup_freezer.c:freezer_write",
        "kernel/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/cpuset.c:generate_sched_domains",
        "kernel/cpuset.c:generate_sched_domains",
        "kernel/cpuset.c:update_domain_attr_tree",
        "kernel/cpuset.c:update_domain_attr_tree",
        "kernel/bpf/cgroup.c:__cgroup_bpf_update",
        "kernel/bpf/cgroup.c:__cgroup_bpf_update",
        "kernel/bpf/cgroup.c:__cgroup_bpf_update",
        "kernel/bpf/cgroup.c:__cgroup_bpf_update",
        "mm/memcontrol.c:mem_cgroup_iter",
        "security/device_cgroup.c:devcgroup_access_write",
        "security/device_cgroup.c:devcgroup_access_write",
        "block/blk-cgroup.c:blkg_rwstat_recursive_sum",
        "block/blk-cgroup.c:blkg_rwstat_recursive_sum",
        "block/blk-cgroup.c:blkg_stat_recursive_sum",
        "block/blk-cgroup.c:blkg_stat_recursive_sum",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580045232,
      "name": "css_next_descendant_pre",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct cgroup_subsys_state * css_next_descendant_pre(struct cgroup_subsys_state * pos, struct cgroup_subsys_state * root)
```

```json
{
  "name": "css_next_descendant_pre",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580047760,
      "name": "css_next_descendant_pre",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:3520",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/freezer.c:freezer_write",
        "kernel/cgroup/freezer.c:freezer_write",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:update_domain_attr_tree",
        "kernel/cgroup/cpuset.c:update_domain_attr_tree",
        "kernel/bpf/cgroup.c:__cgroup_bpf_update",
        "kernel/bpf/cgroup.c:__cgroup_bpf_update",
        "kernel/bpf/cgroup.c:__cgroup_bpf_update",
        "kernel/bpf/cgroup.c:__cgroup_bpf_update",
        "mm/memcontrol.c:mem_cgroup_iter",
        "security/device_cgroup.c:devcgroup_access_write",
        "security/device_cgroup.c:devcgroup_access_write",
        "block/blk-cgroup.c:blkg_rwstat_recursive_sum",
        "block/blk-cgroup.c:blkg_rwstat_recursive_sum",
        "block/blk-cgroup.c:blkg_stat_recursive_sum",
        "block/blk-cgroup.c:blkg_stat_recursive_sum",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580047760,
      "name": "css_next_descendant_pre",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct cgroup_subsys_state * css_next_descendant_pre(struct cgroup_subsys_state * pos, struct cgroup_subsys_state * root)
```

```json
{
  "name": "css_next_descendant_pre",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580097632,
      "name": "css_next_descendant_pre",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:3889",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_save_control",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/freezer.c:freezer_write",
        "kernel/cgroup/freezer.c:freezer_write",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:update_domain_attr_tree",
        "kernel/cgroup/cpuset.c:update_domain_attr_tree",
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "mm/memcontrol.c:mem_cgroup_iter",
        "security/device_cgroup.c:devcgroup_access_write",
        "security/device_cgroup.c:devcgroup_access_write",
        "block/blk-cgroup.c:blkg_rwstat_recursive_sum",
        "block/blk-cgroup.c:blkg_rwstat_recursive_sum",
        "block/blk-cgroup.c:blkg_stat_recursive_sum",
        "block/blk-cgroup.c:blkg_stat_recursive_sum",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580097632,
      "name": "css_next_descendant_pre",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct cgroup_subsys_state * css_next_descendant_pre(struct cgroup_subsys_state * pos, struct cgroup_subsys_state * root)
```

```json
{
  "name": "css_next_descendant_pre",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580157317,
      "name": "css_next_descendant_pre",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:3926",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_save_control",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_save_control",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/freezer.c:freezer_write",
        "kernel/cgroup/freezer.c:freezer_write",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:update_domain_attr_tree",
        "kernel/cgroup/cpuset.c:update_domain_attr_tree",
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "mm/memcontrol.c:mem_cgroup_iter",
        "security/device_cgroup.c:devcgroup_access_write",
        "security/device_cgroup.c:devcgroup_access_write",
        "block/blk-cgroup.c:blkg_rwstat_recursive_sum",
        "block/blk-cgroup.c:blkg_rwstat_recursive_sum",
        "block/blk-cgroup.c:blkg_stat_recursive_sum",
        "block/blk-cgroup.c:blkg_stat_recursive_sum",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580156800,
      "name": "css_next_descendant_pre",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct cgroup_subsys_state * css_next_descendant_pre(struct cgroup_subsys_state * pos, struct cgroup_subsys_state * root)
```

```json
{
  "name": "css_next_descendant_pre",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580212063,
      "name": "css_next_descendant_pre",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:3990",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_save_control",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_save_control",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/freezer.c:freezer_write",
        "kernel/cgroup/freezer.c:freezer_write",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:update_domain_attr_tree",
        "kernel/cgroup/cpuset.c:update_domain_attr_tree",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "mm/memcontrol.c:mem_cgroup_iter",
        "security/device_cgroup.c:devcgroup_access_write",
        "security/device_cgroup.c:devcgroup_access_write",
        "block/blk-cgroup.c:blkg_rwstat_recursive_sum",
        "block/blk-cgroup.c:blkg_rwstat_recursive_sum",
        "block/blk-cgroup.c:blkg_stat_recursive_sum",
        "block/blk-cgroup.c:blkg_stat_recursive_sum",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580204528,
      "name": "css_next_descendant_pre",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct cgroup_subsys_state * css_next_descendant_pre(struct cgroup_subsys_state * pos, struct cgroup_subsys_state * root)
```

```json
{
  "name": "css_next_descendant_pre",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580260630,
      "name": "css_next_descendant_pre",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4246",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_save_control",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_save_control",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:update_domain_attr_tree",
        "kernel/cgroup/cpuset.c:update_domain_attr_tree",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "mm/memcontrol.c:mem_cgroup_iter",
        "security/device_cgroup.c:devcgroup_access_write",
        "security/device_cgroup.c:devcgroup_access_write",
        "block/blk-cgroup.c:blkg_rwstat_recursive_sum",
        "block/blk-cgroup.c:blkg_rwstat_recursive_sum",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580251808,
      "name": "css_next_descendant_pre",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct cgroup_subsys_state * css_next_descendant_pre(struct cgroup_subsys_state * pos, struct cgroup_subsys_state * root)
```

```json
{
  "name": "css_next_descendant_pre",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580308873,
      "name": "css_next_descendant_pre",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4248",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_save_control",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses"
      ],
      "caller_func": [
        "kernel/sched/core.c:cpu_util_update_eff",
        "kernel/sched/core.c:cpu_util_update_eff",
        "kernel/cgroup/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_save_control",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:update_domain_attr_tree",
        "kernel/cgroup/cpuset.c:update_domain_attr_tree",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "mm/memcontrol.c:mem_cgroup_iter",
        "security/device_cgroup.c:devcgroup_access_write",
        "security/device_cgroup.c:devcgroup_access_write",
        "block/blk-cgroup.c:blkg_rwstat_recursive_sum",
        "block/blk-cgroup.c:blkg_rwstat_recursive_sum",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580300048,
      "name": "css_next_descendant_pre",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct cgroup_subsys_state * css_next_descendant_pre(struct cgroup_subsys_state * pos, struct cgroup_subsys_state * root)
```

```json
{
  "name": "css_next_descendant_pre",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580360082,
      "name": "css_next_descendant_pre",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4190",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup/cgroup.c:cgroup_enable_threaded",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_save_control",
        "kernel/cgroup/cgroup.c:cgroup_save_control",
        "kernel/cgroup/cgroup.c:cgroup_save_control",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses"
      ],
      "caller_func": [
        "kernel/sched/core.c:cpu_util_update_eff",
        "kernel/sched/core.c:cpu_util_update_eff",
        "kernel/cgroup/cgroup.c:cgroup_enable_threaded",
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/legacy_freezer.c:freezer_change_state",
        "kernel/cgroup/legacy_freezer.c:freezer_change_state",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:update_nodemasks_hier",
        "kernel/cgroup/cpuset.c:update_nodemasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:rebuild_root_domains",
        "kernel/cgroup/cpuset.c:rebuild_root_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:update_domain_attr_tree",
        "kernel/cgroup/cpuset.c:update_domain_attr_tree",
        "kernel/bpf/cgroup.c:replace_effective_prog",
        "kernel/bpf/cgroup.c:replace_effective_prog",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "mm/memcontrol.c:mem_cgroup_iter",
        "security/device_cgroup.c:propagate_exception",
        "security/device_cgroup.c:propagate_exception",
        "block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum",
        "block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580353584,
      "name": "css_next_descendant_pre",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct cgroup_subsys_state * css_next_descendant_pre(struct cgroup_subsys_state * pos, struct cgroup_subsys_state * root)
```

```json
{
  "name": "css_next_descendant_pre",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580346882,
      "name": "css_next_descendant_pre",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4191",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup/cgroup.c:cgroup_enable_threaded",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_save_control",
        "kernel/cgroup/cgroup.c:cgroup_save_control",
        "kernel/cgroup/cgroup.c:cgroup_save_control",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses"
      ],
      "caller_func": [
        "kernel/sched/core.c:cpu_util_update_eff",
        "kernel/sched/core.c:cpu_util_update_eff",
        "kernel/cgroup/cgroup.c:cgroup_enable_threaded",
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/legacy_freezer.c:freezer_change_state",
        "kernel/cgroup/legacy_freezer.c:freezer_change_state",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:update_nodemasks_hier",
        "kernel/cgroup/cpuset.c:update_nodemasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:rebuild_root_domains",
        "kernel/cgroup/cpuset.c:rebuild_root_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:update_domain_attr_tree",
        "kernel/cgroup/cpuset.c:update_domain_attr_tree",
        "kernel/bpf/cgroup.c:replace_effective_prog",
        "kernel/bpf/cgroup.c:replace_effective_prog",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "mm/memcontrol.c:mem_cgroup_iter",
        "security/device_cgroup.c:propagate_exception",
        "security/device_cgroup.c:propagate_exception",
        "block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum",
        "block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580340032,
      "name": "css_next_descendant_pre",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct cgroup_subsys_state * css_next_descendant_pre(struct cgroup_subsys_state * pos, struct cgroup_subsys_state * root)
```

```json
{
  "name": "css_next_descendant_pre",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580350513,
      "name": "css_next_descendant_pre",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4204",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_save_control",
        "kernel/cgroup/cgroup.c:cgroup_save_control",
        "kernel/cgroup/cgroup.c:cgroup_save_control",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses"
      ],
      "caller_func": [
        "kernel/sched/core.c:cpu_util_update_eff",
        "kernel/sched/core.c:cpu_util_update_eff",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/legacy_freezer.c:freezer_change_state",
        "kernel/cgroup/legacy_freezer.c:freezer_change_state",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:update_nodemasks_hier",
        "kernel/cgroup/cpuset.c:update_nodemasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:update_domain_attr_tree",
        "kernel/cgroup/cpuset.c:update_domain_attr_tree",
        "kernel/bpf/cgroup.c:cgroup_bpf_replace",
        "kernel/bpf/cgroup.c:cgroup_bpf_replace",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "mm/memcontrol.c:mem_cgroup_iter",
        "security/device_cgroup.c:propagate_exception",
        "security/device_cgroup.c:propagate_exception",
        "block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum",
        "block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580343200,
      "name": "css_next_descendant_pre",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct cgroup_subsys_state * css_next_descendant_pre(struct cgroup_subsys_state * pos, struct cgroup_subsys_state * root)
```

```json
{
  "name": "css_next_descendant_pre",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580506709,
      "name": "css_next_descendant_pre",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4379",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_save_control",
        "kernel/cgroup/cgroup.c:cgroup_save_control",
        "kernel/cgroup/cgroup.c:cgroup_save_control",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses"
      ],
      "caller_func": [
        "kernel/sched/core.c:cpu_util_update_eff",
        "kernel/sched/core.c:cpu_util_update_eff",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/legacy_freezer.c:freezer_change_state",
        "kernel/cgroup/legacy_freezer.c:freezer_change_state",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:update_nodemasks_hier",
        "kernel/cgroup/cpuset.c:update_nodemasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:update_domain_attr_tree",
        "kernel/cgroup/cpuset.c:update_domain_attr_tree",
        "kernel/bpf/cgroup.c:cgroup_bpf_replace",
        "kernel/bpf/cgroup.c:cgroup_bpf_replace",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "mm/memcontrol.c:mem_cgroup_iter",
        "security/device_cgroup.c:propagate_exception",
        "security/device_cgroup.c:propagate_exception",
        "block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum",
        "block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580498816,
      "name": "css_next_descendant_pre",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct cgroup_subsys_state * css_next_descendant_pre(struct cgroup_subsys_state * pos, struct cgroup_subsys_state * root)
```

```json
{
  "name": "css_next_descendant_pre",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580695971,
      "name": "css_next_descendant_pre",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4390",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_save_control",
        "kernel/cgroup/cgroup.c:cgroup_save_control",
        "kernel/cgroup/cgroup.c:cgroup_save_control",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses"
      ],
      "caller_func": [
        "kernel/sched/core.c:cpu_util_update_eff",
        "kernel/sched/core.c:cpu_util_update_eff",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/legacy_freezer.c:freezer_change_state",
        "kernel/cgroup/legacy_freezer.c:freezer_change_state",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:update_nodemasks_hier",
        "kernel/cgroup/cpuset.c:update_nodemasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:update_domain_attr_tree",
        "kernel/cgroup/cpuset.c:update_domain_attr_tree",
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:cgroup_bpf_replace",
        "kernel/bpf/cgroup.c:cgroup_bpf_replace",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "mm/list_lru.c:memcg_reparent_list_lrus",
        "mm/list_lru.c:memcg_reparent_list_lrus",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat",
        "security/device_cgroup.c:propagate_exception",
        "security/device_cgroup.c:propagate_exception",
        "block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum",
        "block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580698480,
      "name": "css_next_descendant_pre",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 199
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct cgroup_subsys_state * css_next_descendant_pre(struct cgroup_subsys_state * pos, struct cgroup_subsys_state * root)
```

```json
{
  "name": "css_next_descendant_pre",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580966371,
      "name": "css_next_descendant_pre",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4587",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_save_control",
        "kernel/cgroup/cgroup.c:cgroup_save_control",
        "kernel/cgroup/cgroup.c:cgroup_save_control",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses"
      ],
      "caller_func": [
        "kernel/sched/core.c:cpu_util_update_eff",
        "kernel/sched/core.c:cpu_util_update_eff",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/legacy_freezer.c:freezer_change_state",
        "kernel/cgroup/legacy_freezer.c:freezer_change_state",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:update_nodemasks_hier",
        "kernel/cgroup/cpuset.c:update_nodemasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:update_domain_attr_tree",
        "kernel/cgroup/cpuset.c:update_domain_attr_tree",
        "kernel/bpf/cgroup_iter.c:cgroup_iter_seq_next",
        "kernel/bpf/cgroup_iter.c:cgroup_iter_seq_start",
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:cgroup_bpf_replace",
        "kernel/bpf/cgroup.c:cgroup_bpf_replace",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "mm/list_lru.c:memcg_reparent_list_lrus",
        "mm/list_lru.c:memcg_reparent_list_lrus",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat",
        "security/device_cgroup.c:propagate_exception",
        "security/device_cgroup.c:propagate_exception",
        "block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum",
        "block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580969872,
      "name": "css_next_descendant_pre",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 199
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct cgroup_subsys_state * css_next_descendant_pre(struct cgroup_subsys_state * pos, struct cgroup_subsys_state * root)
```

```json
{
  "name": "css_next_descendant_pre",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581054760,
      "name": "css_next_descendant_pre",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4564",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_save_control",
        "kernel/cgroup/cgroup.c:cgroup_save_control",
        "kernel/cgroup/cgroup.c:cgroup_save_control",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses"
      ],
      "caller_func": [
        "kernel/sched/core.c:cpu_util_update_eff",
        "kernel/sched/core.c:cpu_util_update_eff",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/legacy_freezer.c:freezer_change_state",
        "kernel/cgroup/legacy_freezer.c:freezer_change_state",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:update_nodemasks_hier",
        "kernel/cgroup/cpuset.c:update_nodemasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:update_domain_attr_tree",
        "kernel/cgroup/cpuset.c:update_domain_attr_tree",
        "kernel/bpf/cgroup_iter.c:cgroup_iter_seq_next",
        "kernel/bpf/cgroup_iter.c:cgroup_iter_seq_start",
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:cgroup_bpf_replace",
        "kernel/bpf/cgroup.c:cgroup_bpf_replace",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "mm/list_lru.c:memcg_reparent_list_lrus",
        "mm/list_lru.c:memcg_reparent_list_lrus",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat",
        "security/device_cgroup.c:propagate_exception",
        "security/device_cgroup.c:propagate_exception",
        "block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum",
        "block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581058896,
      "name": "css_next_descendant_pre",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct cgroup_subsys_state * css_next_descendant_pre(struct cgroup_subsys_state * pos, struct cgroup_subsys_state * root)
```

```json
{
  "name": "css_next_descendant_pre",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581152600,
      "name": "css_next_descendant_pre",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4594",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_save_control",
        "kernel/cgroup/cgroup.c:cgroup_save_control",
        "kernel/cgroup/cgroup.c:cgroup_save_control",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses"
      ],
      "caller_func": [
        "kernel/sched/core.c:cpu_util_update_eff",
        "kernel/sched/core.c:cpu_util_update_eff",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/legacy_freezer.c:freezer_change_state",
        "kernel/cgroup/legacy_freezer.c:freezer_change_state",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:update_nodemasks_hier",
        "kernel/cgroup/cpuset.c:update_nodemasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:update_domain_attr_tree",
        "kernel/cgroup/cpuset.c:update_domain_attr_tree",
        "kernel/bpf/cgroup_iter.c:bpf_iter_css_next",
        "kernel/bpf/cgroup_iter.c:cgroup_iter_seq_next",
        "kernel/bpf/cgroup_iter.c:cgroup_iter_seq_start",
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:cgroup_bpf_replace",
        "kernel/bpf/cgroup.c:cgroup_bpf_replace",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "mm/list_lru.c:memcg_reparent_list_lrus",
        "mm/list_lru.c:memcg_reparent_list_lrus",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat",
        "security/device_cgroup.c:propagate_exception",
        "security/device_cgroup.c:propagate_exception",
        "block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum",
        "block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581156064,
      "name": "css_next_descendant_pre",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
struct cgroup_subsys_state * css_next_descendant_pre(struct cgroup_subsys_state * pos, struct cgroup_subsys_state * root)
```

```json
{
  "name": "css_next_descendant_pre",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491561044,
      "name": "css_next_descendant_pre",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4248",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_save_control",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses"
      ],
      "caller_func": [
        "kernel/sched/core.c:cpu_util_update_eff",
        "kernel/sched/core.c:cpu_util_update_eff",
        "kernel/sched/core.c:cpu_util_update_eff",
        "kernel/cgroup/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_save_control",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:update_domain_attr_tree",
        "kernel/cgroup/cpuset.c:update_domain_attr_tree",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "mm/memcontrol.c:mem_cgroup_iter",
        "security/device_cgroup.c:devcgroup_access_write",
        "security/device_cgroup.c:devcgroup_access_write",
        "block/blk-cgroup.c:blkg_rwstat_recursive_sum",
        "block/blk-cgroup.c:blkg_rwstat_recursive_sum",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491551424,
      "name": "css_next_descendant_pre",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
struct cgroup_subsys_state * css_next_descendant_pre(struct cgroup_subsys_state * pos, struct cgroup_subsys_state * root)
```

```json
{
  "name": "css_next_descendant_pre",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225525460,
      "name": "css_next_descendant_pre",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4248",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_save_control"
      ],
      "caller_func": [
        "kernel/sched/core.c:cpu_util_update_eff",
        "kernel/sched/core.c:cpu_util_update_eff",
        "kernel/cgroup/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_save_control",
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:update_domain_attr_tree",
        "kernel/cgroup/cpuset.c:update_domain_attr_tree",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "mm/memcontrol.c:mem_cgroup_iter",
        "security/device_cgroup.c:devcgroup_access_write",
        "security/device_cgroup.c:devcgroup_access_write",
        "block/blk-cgroup.c:blkg_rwstat_recursive_sum",
        "block/blk-cgroup.c:blkg_rwstat_recursive_sum",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225515604,
      "name": "css_next_descendant_pre",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
struct cgroup_subsys_state * css_next_descendant_pre(struct cgroup_subsys_state * pos, struct cgroup_subsys_state * root)
```

```json
{
  "name": "css_next_descendant_pre",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284536712,
      "name": "css_next_descendant_pre",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4248",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_save_control",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses"
      ],
      "caller_func": [
        "kernel/sched/core.c:cpu_util_update_eff",
        "kernel/sched/core.c:cpu_util_update_eff",
        "kernel/sched/core.c:cpu_util_update_eff",
        "kernel/cgroup/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_save_control",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:update_domain_attr_tree",
        "kernel/cgroup/cpuset.c:update_domain_attr_tree",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:mem_cgroup_iter",
        "security/device_cgroup.c:devcgroup_access_write",
        "security/device_cgroup.c:devcgroup_access_write",
        "block/blk-cgroup.c:blkg_rwstat_recursive_sum",
        "block/blk-cgroup.c:blkg_rwstat_recursive_sum",
        "block/blk-cgroup.c:blkg_rwstat_recursive_sum",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284523312,
      "name": "css_next_descendant_pre",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
struct cgroup_subsys_state * css_next_descendant_pre(struct cgroup_subsys_state * pos, struct cgroup_subsys_state * root)
```

```json
{
  "name": "css_next_descendant_pre",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271974766,
      "name": "css_next_descendant_pre",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4248",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_save_control",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_save_control",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:update_domain_attr_tree",
        "kernel/cgroup/cpuset.c:update_domain_attr_tree",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "mm/memcontrol.c:mem_cgroup_iter",
        "security/device_cgroup.c:devcgroup_access_write",
        "security/device_cgroup.c:devcgroup_access_write",
        "block/blk-cgroup.c:blkg_rwstat_recursive_sum",
        "block/blk-cgroup.c:blkg_rwstat_recursive_sum",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271965924,
      "name": "css_next_descendant_pre",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
struct cgroup_subsys_state * css_next_descendant_pre(struct cgroup_subsys_state * pos, struct cgroup_subsys_state * root)
```

```json
{
  "name": "css_next_descendant_pre",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580277673,
      "name": "css_next_descendant_pre",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4248",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_save_control",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses"
      ],
      "caller_func": [
        "kernel/sched/core.c:cpu_util_update_eff",
        "kernel/sched/core.c:cpu_util_update_eff",
        "kernel/cgroup/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_save_control",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:update_domain_attr_tree",
        "kernel/cgroup/cpuset.c:update_domain_attr_tree",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "mm/memcontrol.c:mem_cgroup_iter",
        "security/device_cgroup.c:devcgroup_access_write",
        "security/device_cgroup.c:devcgroup_access_write",
        "block/blk-cgroup.c:blkg_rwstat_recursive_sum",
        "block/blk-cgroup.c:blkg_rwstat_recursive_sum",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580268848,
      "name": "css_next_descendant_pre",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
struct cgroup_subsys_state * css_next_descendant_pre(struct cgroup_subsys_state * pos, struct cgroup_subsys_state * root)
```

```json
{
  "name": "css_next_descendant_pre",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580225161,
      "name": "css_next_descendant_pre",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4248",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_save_control",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses"
      ],
      "caller_func": [
        "kernel/sched/core.c:cpu_util_update_eff",
        "kernel/sched/core.c:cpu_util_update_eff",
        "kernel/cgroup/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_save_control",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:update_domain_attr_tree",
        "kernel/cgroup/cpuset.c:update_domain_attr_tree",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "mm/memcontrol.c:mem_cgroup_iter",
        "security/device_cgroup.c:devcgroup_access_write",
        "security/device_cgroup.c:devcgroup_access_write",
        "block/blk-cgroup.c:blkg_rwstat_recursive_sum",
        "block/blk-cgroup.c:blkg_rwstat_recursive_sum",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580216352,
      "name": "css_next_descendant_pre",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
struct cgroup_subsys_state * css_next_descendant_pre(struct cgroup_subsys_state * pos, struct cgroup_subsys_state * root)
```

```json
{
  "name": "css_next_descendant_pre",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580268921,
      "name": "css_next_descendant_pre",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4248",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_save_control",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_save_control",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:update_domain_attr_tree",
        "kernel/cgroup/cpuset.c:update_domain_attr_tree",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "mm/memcontrol.c:mem_cgroup_iter",
        "security/device_cgroup.c:devcgroup_access_write",
        "security/device_cgroup.c:devcgroup_access_write",
        "block/blk-cgroup.c:blkg_rwstat_recursive_sum",
        "block/blk-cgroup.c:blkg_rwstat_recursive_sum",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580260096,
      "name": "css_next_descendant_pre",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
struct cgroup_subsys_state * css_next_descendant_pre(struct cgroup_subsys_state * pos, struct cgroup_subsys_state * root)
```

```json
{
  "name": "css_next_descendant_pre",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580322361,
      "name": "css_next_descendant_pre",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4248",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_save_control",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses"
      ],
      "caller_func": [
        "kernel/sched/core.c:cpu_util_update_eff",
        "kernel/sched/core.c:cpu_util_update_eff",
        "kernel/cgroup/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_save_control",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:update_domain_attr_tree",
        "kernel/cgroup/cpuset.c:update_domain_attr_tree",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "mm/memcontrol.c:mem_cgroup_iter",
        "security/device_cgroup.c:devcgroup_access_write",
        "security/device_cgroup.c:devcgroup_access_write",
        "block/blk-cgroup.c:blkg_rwstat_recursive_sum",
        "block/blk-cgroup.c:blkg_rwstat_recursive_sum",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580313456,
      "name": "css_next_descendant_pre",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
