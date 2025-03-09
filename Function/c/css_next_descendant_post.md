# Function: <code>css_next_descendant_post</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct cgroup_subsys_state * css_next_descendant_post(struct cgroup_subsys_state * pos, struct cgroup_subsys_state * root)
```

```json
{
  "name": "css_next_descendant_post",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579985424,
      "name": "css_next_descendant_post",
      "external": true,
      "loc": "kernel/cgroup.c:3927",
      "file": "kernel/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup_freezer.c:freezer_read",
        "kernel/cgroup_freezer.c:freezer_read",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:blk_throtl_drain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579985424,
      "name": "css_next_descendant_post",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct cgroup_subsys_state * css_next_descendant_post(struct cgroup_subsys_state * pos, struct cgroup_subsys_state * root)
```

```json
{
  "name": "css_next_descendant_post",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580019646,
      "name": "css_next_descendant_post",
      "external": true,
      "loc": "kernel/cgroup.c:4116",
      "file": "kernel/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup.c:cgroup_lock_and_drain_offline"
      ],
      "caller_func": [
        "kernel/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup_freezer.c:freezer_read",
        "kernel/cgroup_freezer.c:freezer_read",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:blk_throtl_drain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580003472,
      "name": "css_next_descendant_post.part.26",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071580013728,
      "name": "css_next_descendant_post",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct cgroup_subsys_state * css_next_descendant_post(struct cgroup_subsys_state * pos, struct cgroup_subsys_state * root)
```

```json
{
  "name": "css_next_descendant_post",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580053326,
      "name": "css_next_descendant_post",
      "external": true,
      "loc": "kernel/cgroup.c:4127",
      "file": "kernel/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup.c:cgroup_lock_and_drain_offline"
      ],
      "caller_func": [
        "kernel/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup_freezer.c:freezer_read",
        "kernel/cgroup_freezer.c:freezer_read",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:blk_throtl_drain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580035056,
      "name": "css_next_descendant_post.part.32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071580047312,
      "name": "css_next_descendant_post",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct cgroup_subsys_state * css_next_descendant_post(struct cgroup_subsys_state * pos, struct cgroup_subsys_state * root)
```

```json
{
  "name": "css_next_descendant_post",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580053844,
      "name": "css_next_descendant_post",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:3614",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/freezer.c:freezer_read",
        "kernel/cgroup/freezer.c:freezer_read",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_upgrade_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580034960,
      "name": "css_next_descendant_post.part.30",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071580050368,
      "name": "css_next_descendant_post",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct cgroup_subsys_state * css_next_descendant_post(struct cgroup_subsys_state * pos, struct cgroup_subsys_state * root)
```

```json
{
  "name": "css_next_descendant_post",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580100506,
      "name": "css_next_descendant_post",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:3983",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_restore_control",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_restore_control",
        "kernel/cgroup/cgroup.c:cgroup_restore_control",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/freezer.c:freezer_read",
        "kernel/cgroup/freezer.c:freezer_read",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_upgrade_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580082864,
      "name": "css_next_descendant_post.part.32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071580100288,
      "name": "css_next_descendant_post",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct cgroup_subsys_state * css_next_descendant_post(struct cgroup_subsys_state * pos, struct cgroup_subsys_state * root)
```

```json
{
  "name": "css_next_descendant_post",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580159573,
      "name": "css_next_descendant_post",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4020",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_restore_control",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_restore_control",
        "kernel/cgroup/cgroup.c:cgroup_restore_control",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/freezer.c:freezer_read",
        "kernel/cgroup/freezer.c:freezer_read",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_upgrade_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580141808,
      "name": "css_next_descendant_post.part.35",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071580159392,
      "name": "css_next_descendant_post",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct cgroup_subsys_state * css_next_descendant_post(struct cgroup_subsys_state * pos, struct cgroup_subsys_state * root)
```

```json
{
  "name": "css_next_descendant_post",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580207253,
      "name": "css_next_descendant_post",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4084",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/freezer.c:freezer_read",
        "kernel/cgroup/freezer.c:freezer_read",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_upgrade_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580188592,
      "name": "css_next_descendant_post.part.36",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071580207136,
      "name": "css_next_descendant_post",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct cgroup_subsys_state * css_next_descendant_post(struct cgroup_subsys_state * pos, struct cgroup_subsys_state * root)
```

```json
{
  "name": "css_next_descendant_post",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580255349,
      "name": "css_next_descendant_post",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4341",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/legacy_freezer.c:freezer_read",
        "kernel/cgroup/legacy_freezer.c:freezer_read",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_upgrade_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580234512,
      "name": "css_next_descendant_post.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071580255232,
      "name": "css_next_descendant_post",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct cgroup_subsys_state * css_next_descendant_post(struct cgroup_subsys_state * pos, struct cgroup_subsys_state * root)
```

```json
{
  "name": "css_next_descendant_post",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580303605,
      "name": "css_next_descendant_post",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4343",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/legacy_freezer.c:freezer_read",
        "kernel/cgroup/legacy_freezer.c:freezer_read",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_upgrade_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580282720,
      "name": "css_next_descendant_post.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071580303488,
      "name": "css_next_descendant_post",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
struct cgroup_subsys_state * css_next_descendant_post(struct cgroup_subsys_state * pos, struct cgroup_subsys_state * root)
```

```json
{
  "name": "css_next_descendant_post",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580372893,
      "name": "css_next_descendant_post",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4285",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/legacy_freezer.c:freezer_read",
        "kernel/cgroup/legacy_freezer.c:freezer_read",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:blk_throtl_update_limit_valid",
        "block/blk-throttle.c:blk_throtl_update_limit_valid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580372720,
      "name": "css_next_descendant_post",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
struct cgroup_subsys_state * css_next_descendant_post(struct cgroup_subsys_state * pos, struct cgroup_subsys_state * root)
```

```json
{
  "name": "css_next_descendant_post",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580359757,
      "name": "css_next_descendant_post",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4286",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/legacy_freezer.c:freezer_read",
        "kernel/cgroup/legacy_freezer.c:freezer_read",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_upgrade_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580359584,
      "name": "css_next_descendant_post",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
struct cgroup_subsys_state * css_next_descendant_post(struct cgroup_subsys_state * pos, struct cgroup_subsys_state * root)
```

```json
{
  "name": "css_next_descendant_post",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580362861,
      "name": "css_next_descendant_post",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4299",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/legacy_freezer.c:freezer_read",
        "kernel/cgroup/legacy_freezer.c:freezer_read",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_upgrade_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580362704,
      "name": "css_next_descendant_post",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
struct cgroup_subsys_state * css_next_descendant_post(struct cgroup_subsys_state * pos, struct cgroup_subsys_state * root)
```

```json
{
  "name": "css_next_descendant_post",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580521453,
      "name": "css_next_descendant_post",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4474",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/legacy_freezer.c:freezer_read",
        "kernel/cgroup/legacy_freezer.c:freezer_read",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_upgrade_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580521296,
      "name": "css_next_descendant_post",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
struct cgroup_subsys_state * css_next_descendant_post(struct cgroup_subsys_state * pos, struct cgroup_subsys_state * root)
```

```json
{
  "name": "css_next_descendant_post",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580718637,
      "name": "css_next_descendant_post",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4485",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_restore_control",
        "kernel/cgroup/cgroup.c:cgroup_restore_control",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_restore_control",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/legacy_freezer.c:freezer_read",
        "kernel/cgroup/legacy_freezer.c:freezer_read",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_can_upgrade",
        "block/blk-throttle.c:throtl_can_upgrade",
        "block/blk-throttle.c:blk_throtl_cancel_bios",
        "block/blk-throttle.c:blk_throtl_cancel_bios"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580718320,
      "name": "css_next_descendant_post",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
struct cgroup_subsys_state * css_next_descendant_post(struct cgroup_subsys_state * pos, struct cgroup_subsys_state * root)
```

```json
{
  "name": "css_next_descendant_post",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580993373,
      "name": "css_next_descendant_post",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4682",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_restore_control",
        "kernel/cgroup/cgroup.c:cgroup_restore_control",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_restore_control",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/legacy_freezer.c:freezer_read",
        "kernel/cgroup/legacy_freezer.c:freezer_read",
        "kernel/bpf/cgroup_iter.c:cgroup_iter_seq_next",
        "kernel/bpf/cgroup_iter.c:cgroup_iter_seq_start",
        "block/blk-throttle.c:blk_throtl_cancel_bios",
        "block/blk-throttle.c:blk_throtl_cancel_bios"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580993024,
      "name": "css_next_descendant_post",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
struct cgroup_subsys_state * css_next_descendant_post(struct cgroup_subsys_state * pos, struct cgroup_subsys_state * root)
```

```json
{
  "name": "css_next_descendant_post",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581080941,
      "name": "css_next_descendant_post",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4659",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_restore_control",
        "kernel/cgroup/cgroup.c:cgroup_restore_control",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_restore_control",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/legacy_freezer.c:freezer_read",
        "kernel/cgroup/legacy_freezer.c:freezer_read",
        "kernel/bpf/cgroup_iter.c:cgroup_iter_seq_next",
        "kernel/bpf/cgroup_iter.c:cgroup_iter_seq_start",
        "block/blk-throttle.c:blk_throtl_cancel_bios",
        "block/blk-throttle.c:blk_throtl_cancel_bios"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581080592,
      "name": "css_next_descendant_post",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
struct cgroup_subsys_state * css_next_descendant_post(struct cgroup_subsys_state * pos, struct cgroup_subsys_state * root)
```

```json
{
  "name": "css_next_descendant_post",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581178461,
      "name": "css_next_descendant_post",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4689",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_restore_control",
        "kernel/cgroup/cgroup.c:cgroup_restore_control",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_restore_control",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/legacy_freezer.c:freezer_read",
        "kernel/cgroup/legacy_freezer.c:freezer_read",
        "kernel/bpf/cgroup_iter.c:bpf_iter_css_next",
        "kernel/bpf/cgroup_iter.c:cgroup_iter_seq_next",
        "kernel/bpf/cgroup_iter.c:cgroup_iter_seq_start",
        "block/blk-throttle.c:blk_throtl_cancel_bios",
        "block/blk-throttle.c:blk_throtl_cancel_bios"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581178112,
      "name": "css_next_descendant_post",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
struct cgroup_subsys_state * css_next_descendant_post(struct cgroup_subsys_state * pos, struct cgroup_subsys_state * root)
```

```json
{
  "name": "css_next_descendant_post",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491555276,
      "name": "css_next_descendant_post",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4343",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/legacy_freezer.c:freezer_read",
        "kernel/cgroup/legacy_freezer.c:freezer_read",
        "kernel/cgroup/legacy_freezer.c:freezer_read",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_upgrade_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491531064,
      "name": "css_next_descendant_post.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446603336491555096,
      "name": "css_next_descendant_post",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
struct cgroup_subsys_state * css_next_descendant_post(struct cgroup_subsys_state * pos, struct cgroup_subsys_state * root)
```

```json
{
  "name": "css_next_descendant_post",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225519256,
      "name": "css_next_descendant_post",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4343",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/legacy_freezer.c:freezer_read",
        "kernel/cgroup/legacy_freezer.c:freezer_read",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:blk_throtl_update_limit_valid",
        "block/blk-throttle.c:blk_throtl_update_limit_valid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225498904,
      "name": "css_next_descendant_post.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 3225519104,
      "name": "css_next_descendant_post",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
struct cgroup_subsys_state * css_next_descendant_post(struct cgroup_subsys_state * pos, struct cgroup_subsys_state * root)
```

```json
{
  "name": "css_next_descendant_post",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284527748,
      "name": "css_next_descendant_post",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4343",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/legacy_freezer.c:freezer_read",
        "kernel/cgroup/legacy_freezer.c:freezer_read",
        "kernel/cgroup/legacy_freezer.c:freezer_read",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_upgrade_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284498400,
      "name": "css_next_descendant_post.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 13835058055284527504,
      "name": "css_next_descendant_post",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
struct cgroup_subsys_state * css_next_descendant_post(struct cgroup_subsys_state * pos, struct cgroup_subsys_state * root)
```

```json
{
  "name": "css_next_descendant_post",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271969422,
      "name": "css_next_descendant_post",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4343",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/legacy_freezer.c:freezer_read",
        "kernel/cgroup/legacy_freezer.c:freezer_read",
        "kernel/cgroup/legacy_freezer.c:freezer_read",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_upgrade_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271950436,
      "name": "css_next_descendant_post.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446743936271969246,
      "name": "css_next_descendant_post",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct cgroup_subsys_state * css_next_descendant_post(struct cgroup_subsys_state * pos, struct cgroup_subsys_state * root)
```

```json
{
  "name": "css_next_descendant_post",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580272405,
      "name": "css_next_descendant_post",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4343",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/legacy_freezer.c:freezer_read",
        "kernel/cgroup/legacy_freezer.c:freezer_read",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_upgrade_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580251520,
      "name": "css_next_descendant_post.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071580272288,
      "name": "css_next_descendant_post",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct cgroup_subsys_state * css_next_descendant_post(struct cgroup_subsys_state * pos, struct cgroup_subsys_state * root)
```

```json
{
  "name": "css_next_descendant_post",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580219909,
      "name": "css_next_descendant_post",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4343",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/legacy_freezer.c:freezer_read",
        "kernel/cgroup/legacy_freezer.c:freezer_read",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_upgrade_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580199072,
      "name": "css_next_descendant_post.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071580219792,
      "name": "css_next_descendant_post",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct cgroup_subsys_state * css_next_descendant_post(struct cgroup_subsys_state * pos, struct cgroup_subsys_state * root)
```

```json
{
  "name": "css_next_descendant_post",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580263653,
      "name": "css_next_descendant_post",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4343",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/legacy_freezer.c:freezer_read",
        "kernel/cgroup/legacy_freezer.c:freezer_read",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_upgrade_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580242768,
      "name": "css_next_descendant_post.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071580263536,
      "name": "css_next_descendant_post",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct cgroup_subsys_state * css_next_descendant_post(struct cgroup_subsys_state * pos, struct cgroup_subsys_state * root)
```

```json
{
  "name": "css_next_descendant_post",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580316997,
      "name": "css_next_descendant_post",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4343",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/legacy_freezer.c:freezer_read",
        "kernel/cgroup/legacy_freezer.c:freezer_read",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_upgrade_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580297328,
      "name": "css_next_descendant_post.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071580316880,
      "name": "css_next_descendant_post",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
