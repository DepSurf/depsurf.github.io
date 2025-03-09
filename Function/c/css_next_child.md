# Function: <code>css_next_child</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct cgroup_subsys_state * css_next_child(struct cgroup_subsys_state * pos, struct cgroup_subsys_state * parent)
```

```json
{
  "name": "css_next_child",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579975417,
      "name": "css_next_child",
      "external": true,
      "loc": "kernel/cgroup.c:3765",
      "file": "kernel/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup.c:rebind_subsystems",
        "kernel/cgroup.c:css_rightmost_descendant",
        "kernel/cgroup.c:css_next_descendant_post",
        "kernel/cgroup.c:css_next_descendant_post",
        "kernel/cgroup.c:css_has_online_children"
      ],
      "caller_func": [
        "kernel/cgroup.c:css_rightmost_descendant",
        "kernel/cgroup.c:css_next_descendant_post",
        "kernel/cgroup.c:css_has_online_children",
        "kernel/cgroup_freezer.c:freezer_read",
        "kernel/cgroup_freezer.c:freezer_read",
        "kernel/cpuset.c:cpuset_css_online",
        "kernel/cpuset.c:cpuset_css_online",
        "mm/memcontrol.c:mem_cgroup_hierarchy_write",
        "mm/memcontrol.c:memcg_activate_kmem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579984384,
      "name": "css_next_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
struct cgroup_subsys_state * css_next_child(struct cgroup_subsys_state * pos, struct cgroup_subsys_state * parent)
```

```json
{
  "name": "css_next_child",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580014901,
      "name": "css_next_child",
      "external": true,
      "loc": "kernel/cgroup.c:3954",
      "file": "kernel/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup.c:css_has_online_children",
        "kernel/cgroup.c:css_rightmost_descendant",
        "kernel/cgroup.c:rebind_subsystems"
      ],
      "caller_func": [
        "kernel/cgroup.c:css_has_online_children",
        "kernel/cgroup.c:css_rightmost_descendant",
        "kernel/cgroup_freezer.c:freezer_read",
        "kernel/cgroup_freezer.c:freezer_read",
        "kernel/cpuset.c:cpuset_css_online",
        "kernel/cpuset.c:cpuset_css_online",
        "mm/memcontrol.c:mem_cgroup_hierarchy_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580011536,
      "name": "css_next_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
struct cgroup_subsys_state * css_next_child(struct cgroup_subsys_state * pos, struct cgroup_subsys_state * parent)
```

```json
{
  "name": "css_next_child",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580048485,
      "name": "css_next_child",
      "external": true,
      "loc": "kernel/cgroup.c:3965",
      "file": "kernel/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup.c:css_has_online_children",
        "kernel/cgroup.c:css_rightmost_descendant",
        "kernel/cgroup.c:rebind_subsystems"
      ],
      "caller_func": [
        "kernel/cgroup.c:css_has_online_children",
        "kernel/cgroup.c:css_rightmost_descendant",
        "kernel/cgroup_freezer.c:freezer_read",
        "kernel/cgroup_freezer.c:freezer_read",
        "kernel/cpuset.c:cpuset_css_online",
        "kernel/cpuset.c:cpuset_css_online",
        "mm/memcontrol.c:mem_cgroup_hierarchy_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580045120,
      "name": "css_next_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
struct cgroup_subsys_state * css_next_child(struct cgroup_subsys_state * pos, struct cgroup_subsys_state * parent)
```

```json
{
  "name": "css_next_child",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580056021,
      "name": "css_next_child",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:3452",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_has_online_children",
        "kernel/cgroup/cgroup.c:css_rightmost_descendant",
        "kernel/cgroup/cgroup.c:rebind_subsystems"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:css_has_online_children",
        "kernel/cgroup/cgroup.c:css_rightmost_descendant",
        "kernel/cgroup/freezer.c:freezer_read",
        "kernel/cgroup/freezer.c:freezer_read",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "mm/memcontrol.c:mem_cgroup_hierarchy_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580047648,
      "name": "css_next_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
struct cgroup_subsys_state * css_next_child(struct cgroup_subsys_state * pos, struct cgroup_subsys_state * parent)
```

```json
{
  "name": "css_next_child",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580106213,
      "name": "css_next_child",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:3821",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_has_online_children",
        "kernel/cgroup/cgroup.c:css_rightmost_descendant",
        "kernel/cgroup/cgroup.c:rebind_subsystems"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:css_has_online_children",
        "kernel/cgroup/cgroup.c:css_rightmost_descendant",
        "kernel/cgroup/freezer.c:update_if_frozen",
        "kernel/cgroup/freezer.c:update_if_frozen",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "mm/memcontrol.c:mem_cgroup_hierarchy_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580097520,
      "name": "css_next_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
struct cgroup_subsys_state * css_next_child(struct cgroup_subsys_state * pos, struct cgroup_subsys_state * parent)
```

```json
{
  "name": "css_next_child",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580165349,
      "name": "css_next_child",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:3858",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_has_online_children",
        "kernel/cgroup/cgroup.c:css_rightmost_descendant",
        "kernel/cgroup/cgroup.c:rebind_subsystems"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:css_has_online_children",
        "kernel/cgroup/cgroup.c:css_rightmost_descendant",
        "kernel/cgroup/freezer.c:update_if_frozen",
        "kernel/cgroup/freezer.c:update_if_frozen",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "mm/memcontrol.c:mem_cgroup_hierarchy_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580156688,
      "name": "css_next_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
struct cgroup_subsys_state * css_next_child(struct cgroup_subsys_state * pos, struct cgroup_subsys_state * parent)
```

```json
{
  "name": "css_next_child",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580213093,
      "name": "css_next_child",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:3922",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_has_online_children",
        "kernel/cgroup/cgroup.c:css_rightmost_descendant",
        "kernel/cgroup/cgroup.c:rebind_subsystems"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:css_has_online_children",
        "kernel/cgroup/cgroup.c:css_rightmost_descendant",
        "kernel/cgroup/freezer.c:update_if_frozen",
        "kernel/cgroup/freezer.c:update_if_frozen",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:update_sibling_cpumasks",
        "kernel/cgroup/cpuset.c:update_sibling_cpumasks",
        "mm/memcontrol.c:mem_cgroup_hierarchy_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580204416,
      "name": "css_next_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
struct cgroup_subsys_state * css_next_child(struct cgroup_subsys_state * pos, struct cgroup_subsys_state * parent)
```

```json
{
  "name": "css_next_child",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580261645,
      "name": "css_next_child",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4178",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_has_online_children",
        "kernel/cgroup/cgroup.c:css_rightmost_descendant",
        "kernel/cgroup/cgroup.c:rebind_subsystems"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:css_has_online_children",
        "kernel/cgroup/cgroup.c:css_rightmost_descendant",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:update_sibling_cpumasks",
        "kernel/cgroup/cpuset.c:update_sibling_cpumasks",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "mm/memcontrol.c:mem_cgroup_hierarchy_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580251696,
      "name": "css_next_child",
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
struct cgroup_subsys_state * css_next_child(struct cgroup_subsys_state * pos, struct cgroup_subsys_state * parent)
```

```json
{
  "name": "css_next_child",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580309917,
      "name": "css_next_child",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4180",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_has_online_children",
        "kernel/cgroup/cgroup.c:css_rightmost_descendant",
        "kernel/cgroup/cgroup.c:rebind_subsystems"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:css_has_online_children",
        "kernel/cgroup/cgroup.c:css_rightmost_descendant",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:update_sibling_cpumasks",
        "kernel/cgroup/cpuset.c:update_sibling_cpumasks",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "mm/memcontrol.c:mem_cgroup_hierarchy_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580299936,
      "name": "css_next_child",
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
struct cgroup_subsys_state * css_next_child(struct cgroup_subsys_state * pos, struct cgroup_subsys_state * parent)
```

```json
{
  "name": "css_next_child",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580379801,
      "name": "css_next_child",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4121",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_has_online_children",
        "kernel/cgroup/cgroup.c:css_has_online_children",
        "kernel/cgroup/cgroup.c:css_rightmost_descendant",
        "kernel/cgroup/cgroup.c:css_rightmost_descendant",
        "kernel/cgroup/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_save_control",
        "kernel/cgroup/cgroup.c:cgroup_save_control",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:rebind_subsystems"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:update_sibling_cpumasks",
        "kernel/cgroup/cpuset.c:update_sibling_cpumasks",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "mm/memcontrol.c:mem_cgroup_hierarchy_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580370272,
      "name": "css_next_child",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct cgroup_subsys_state * css_next_child(struct cgroup_subsys_state * pos, struct cgroup_subsys_state * parent)
```

```json
{
  "name": "css_next_child",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580366747,
      "name": "css_next_child",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4122",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_has_online_children",
        "kernel/cgroup/cgroup.c:css_has_online_children",
        "kernel/cgroup/cgroup.c:css_rightmost_descendant",
        "kernel/cgroup/cgroup.c:css_rightmost_descendant",
        "kernel/cgroup/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_save_control",
        "kernel/cgroup/cgroup.c:cgroup_save_control",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:rebind_subsystems"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:update_sibling_cpumasks",
        "kernel/cgroup/cpuset.c:update_sibling_cpumasks",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580357168,
      "name": "css_next_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
struct cgroup_subsys_state * css_next_child(struct cgroup_subsys_state * pos, struct cgroup_subsys_state * parent)
```

```json
{
  "name": "css_next_child",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580369771,
      "name": "css_next_child",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4135",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_has_online_children",
        "kernel/cgroup/cgroup.c:css_has_online_children",
        "kernel/cgroup/cgroup.c:css_rightmost_descendant",
        "kernel/cgroup/cgroup.c:css_rightmost_descendant",
        "kernel/cgroup/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_save_control",
        "kernel/cgroup/cgroup.c:cgroup_save_control",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:rebind_subsystems"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:update_sibling_cpumasks",
        "kernel/cgroup/cpuset.c:update_sibling_cpumasks",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580360352,
      "name": "css_next_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
struct cgroup_subsys_state * css_next_child(struct cgroup_subsys_state * pos, struct cgroup_subsys_state * parent)
```

```json
{
  "name": "css_next_child",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580529659,
      "name": "css_next_child",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4310",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_has_online_children",
        "kernel/cgroup/cgroup.c:css_has_online_children",
        "kernel/cgroup/cgroup.c:css_rightmost_descendant",
        "kernel/cgroup/cgroup.c:css_rightmost_descendant",
        "kernel/cgroup/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_save_control",
        "kernel/cgroup/cgroup.c:cgroup_save_control",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:rebind_subsystems"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:update_sibling_cpumasks",
        "kernel/cgroup/cpuset.c:update_sibling_cpumasks",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580518736,
      "name": "css_next_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
struct cgroup_subsys_state * css_next_child(struct cgroup_subsys_state * pos, struct cgroup_subsys_state * parent)
```

```json
{
  "name": "css_next_child",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580726770,
      "name": "css_next_child",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4321",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_has_online_children",
        "kernel/cgroup/cgroup.c:css_has_online_children",
        "kernel/cgroup/cgroup.c:css_rightmost_descendant",
        "kernel/cgroup/cgroup.c:css_rightmost_descendant",
        "kernel/cgroup/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_restore_control",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_save_control",
        "kernel/cgroup/cgroup.c:cgroup_save_control",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:rebind_subsystems"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:update_sibling_cpumasks",
        "kernel/cgroup/cpuset.c:update_sibling_cpumasks",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580715632,
      "name": "css_next_child",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct cgroup_subsys_state * css_next_child(struct cgroup_subsys_state * pos, struct cgroup_subsys_state * parent)
```

```json
{
  "name": "css_next_child",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581002338,
      "name": "css_next_child",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4518",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_has_online_children",
        "kernel/cgroup/cgroup.c:css_has_online_children",
        "kernel/cgroup/cgroup.c:css_rightmost_descendant",
        "kernel/cgroup/cgroup.c:css_rightmost_descendant",
        "kernel/cgroup/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_restore_control",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_save_control",
        "kernel/cgroup/cgroup.c:cgroup_save_control",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:rebind_subsystems"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_sibling_cpumasks",
        "kernel/cgroup/cpuset.c:update_sibling_cpumasks",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580990192,
      "name": "css_next_child",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct cgroup_subsys_state * css_next_child(struct cgroup_subsys_state * pos, struct cgroup_subsys_state * parent)
```

```json
{
  "name": "css_next_child",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581090919,
      "name": "css_next_child",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4495",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_has_online_children",
        "kernel/cgroup/cgroup.c:css_has_online_children",
        "kernel/cgroup/cgroup.c:css_rightmost_descendant",
        "kernel/cgroup/cgroup.c:css_rightmost_descendant",
        "kernel/cgroup/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_restore_control",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_save_control",
        "kernel/cgroup/cgroup.c:cgroup_save_control",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:rebind_subsystems"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_sibling_cpumasks",
        "kernel/cgroup/cpuset.c:update_sibling_cpumasks",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581077744,
      "name": "css_next_child",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct cgroup_subsys_state * css_next_child(struct cgroup_subsys_state * pos, struct cgroup_subsys_state * parent)
```

```json
{
  "name": "css_next_child",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581188439,
      "name": "css_next_child",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4525",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_has_online_children",
        "kernel/cgroup/cgroup.c:css_has_online_children",
        "kernel/cgroup/cgroup.c:css_rightmost_descendant",
        "kernel/cgroup/cgroup.c:css_rightmost_descendant",
        "kernel/cgroup/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_restore_control",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_save_control",
        "kernel/cgroup/cgroup.c:cgroup_save_control",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:rebind_subsystems"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_sibling_cpumasks",
        "kernel/cgroup/cpuset.c:update_sibling_cpumasks",
        "kernel/cgroup/cpuset.c:compute_partition_effective_cpumask",
        "kernel/cgroup/cpuset.c:compute_partition_effective_cpumask",
        "kernel/cgroup/cpuset.c:compute_partition_effective_cpumask",
        "kernel/cgroup/cpuset.c:compute_partition_effective_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_effective_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_effective_cpumask",
        "kernel/cgroup/cpuset.c:tasks_nocpu_error",
        "kernel/cgroup/cpuset.c:tasks_nocpu_error",
        "kernel/cgroup/cpuset.c:tasks_nocpu_error",
        "kernel/cgroup/cpuset.c:tasks_nocpu_error",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581175248,
      "name": "css_next_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
struct cgroup_subsys_state * css_next_child(struct cgroup_subsys_state * pos, struct cgroup_subsys_state * parent)
```

```json
{
  "name": "css_next_child",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491562016,
      "name": "css_next_child",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4180",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_has_online_children",
        "kernel/cgroup/cgroup.c:css_rightmost_descendant",
        "kernel/cgroup/cgroup.c:rebind_subsystems"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:css_has_online_children",
        "kernel/cgroup/cgroup.c:css_rightmost_descendant",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:update_sibling_cpumasks",
        "kernel/cgroup/cpuset.c:update_sibling_cpumasks",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "mm/memcontrol.c:mem_cgroup_hierarchy_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491551272,
      "name": "css_next_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
struct cgroup_subsys_state * css_next_child(struct cgroup_subsys_state * pos, struct cgroup_subsys_state * parent)
```

```json
{
  "name": "css_next_child",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225526700,
      "name": "css_next_child",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4180",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_has_online_children",
        "kernel/cgroup/cgroup.c:css_rightmost_descendant",
        "kernel/cgroup/cgroup.c:rebind_subsystems"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:css_has_online_children",
        "kernel/cgroup/cgroup.c:css_rightmost_descendant",
        "kernel/cgroup/legacy_freezer.c:freezer_read",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:update_sibling_cpumasks",
        "kernel/cgroup/cpuset.c:update_sibling_cpumasks",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "mm/memcontrol.c:mem_cgroup_hierarchy_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225515468,
      "name": "css_next_child",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
struct cgroup_subsys_state * css_next_child(struct cgroup_subsys_state * pos, struct cgroup_subsys_state * parent)
```

```json
{
  "name": "css_next_child",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284538384,
      "name": "css_next_child",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4180",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_has_online_children",
        "kernel/cgroup/cgroup.c:css_rightmost_descendant",
        "kernel/cgroup/cgroup.c:rebind_subsystems"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:css_has_online_children",
        "kernel/cgroup/cgroup.c:css_rightmost_descendant",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:update_sibling_cpumasks",
        "kernel/cgroup/cpuset.c:update_sibling_cpumasks",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "mm/memcontrol.c:mem_cgroup_hierarchy_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284523136,
      "name": "css_next_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
struct cgroup_subsys_state * css_next_child(struct cgroup_subsys_state * pos, struct cgroup_subsys_state * parent)
```

```json
{
  "name": "css_next_child",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271975830,
      "name": "css_next_child",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4180",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_has_online_children",
        "kernel/cgroup/cgroup.c:css_rightmost_descendant",
        "kernel/cgroup/cgroup.c:rebind_subsystems"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:css_has_online_children",
        "kernel/cgroup/cgroup.c:css_rightmost_descendant",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:update_sibling_cpumasks",
        "kernel/cgroup/cpuset.c:update_sibling_cpumasks",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "mm/memcontrol.c:mem_cgroup_hierarchy_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271965796,
      "name": "css_next_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
struct cgroup_subsys_state * css_next_child(struct cgroup_subsys_state * pos, struct cgroup_subsys_state * parent)
```

```json
{
  "name": "css_next_child",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580278717,
      "name": "css_next_child",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4180",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_has_online_children",
        "kernel/cgroup/cgroup.c:css_rightmost_descendant",
        "kernel/cgroup/cgroup.c:rebind_subsystems"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:css_has_online_children",
        "kernel/cgroup/cgroup.c:css_rightmost_descendant",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:update_sibling_cpumasks",
        "kernel/cgroup/cpuset.c:update_sibling_cpumasks",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "mm/memcontrol.c:mem_cgroup_hierarchy_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580268736,
      "name": "css_next_child",
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
struct cgroup_subsys_state * css_next_child(struct cgroup_subsys_state * pos, struct cgroup_subsys_state * parent)
```

```json
{
  "name": "css_next_child",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580226205,
      "name": "css_next_child",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4180",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_has_online_children",
        "kernel/cgroup/cgroup.c:css_rightmost_descendant",
        "kernel/cgroup/cgroup.c:rebind_subsystems"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:css_has_online_children",
        "kernel/cgroup/cgroup.c:css_rightmost_descendant",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:update_sibling_cpumasks",
        "kernel/cgroup/cpuset.c:update_sibling_cpumasks",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "mm/memcontrol.c:mem_cgroup_hierarchy_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580216240,
      "name": "css_next_child",
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
struct cgroup_subsys_state * css_next_child(struct cgroup_subsys_state * pos, struct cgroup_subsys_state * parent)
```

```json
{
  "name": "css_next_child",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580269965,
      "name": "css_next_child",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4180",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_has_online_children",
        "kernel/cgroup/cgroup.c:css_rightmost_descendant",
        "kernel/cgroup/cgroup.c:rebind_subsystems"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:css_has_online_children",
        "kernel/cgroup/cgroup.c:css_rightmost_descendant",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:update_sibling_cpumasks",
        "kernel/cgroup/cpuset.c:update_sibling_cpumasks",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "mm/memcontrol.c:mem_cgroup_hierarchy_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580259984,
      "name": "css_next_child",
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
struct cgroup_subsys_state * css_next_child(struct cgroup_subsys_state * pos, struct cgroup_subsys_state * parent)
```

```json
{
  "name": "css_next_child",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580323492,
      "name": "css_next_child",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4180",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_has_online_children",
        "kernel/cgroup/cgroup.c:css_rightmost_descendant",
        "kernel/cgroup/cgroup.c:rebind_subsystems"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:css_has_online_children",
        "kernel/cgroup/cgroup.c:css_rightmost_descendant",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:update_sibling_cpumasks",
        "kernel/cgroup/cpuset.c:update_sibling_cpumasks",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "mm/memcontrol.c:mem_cgroup_hierarchy_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580313344,
      "name": "css_next_child",
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
