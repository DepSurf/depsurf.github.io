# Function: <code>devlink_trap_group_item_lookup</code>

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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct devlink_trap_group_item * devlink_trap_group_item_lookup(struct devlink * devlink, const char * name)
```

```json
{
  "name": "devlink_trap_group_item_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588787760,
      "name": "devlink_trap_group_item_lookup",
      "external": false,
      "loc": "net/core/devlink.c:5572",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_traps_register",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588787760,
      "name": "devlink_trap_group_item_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "devlink_trap_group_item_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589705257,
      "name": "devlink_trap_group_item_lookup",
      "external": false,
      "loc": "net/core/devlink.c:6164",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_trap_group_register",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "devlink_trap_group_item_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589735337,
      "name": "devlink_trap_group_item_lookup",
      "external": false,
      "loc": "net/core/devlink.c:7010",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_trap_group_register",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "devlink_trap_group_item_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589614813,
      "name": "devlink_trap_group_item_lookup",
      "external": false,
      "loc": "net/core/devlink.c:7213",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_trap_groups_register",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "devlink_trap_group_item_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590372748,
      "name": "devlink_trap_group_item_lookup",
      "external": false,
      "loc": "net/core/devlink.c:7892",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_trap_groups_register",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "devlink_trap_group_item_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591958938,
      "name": "devlink_trap_group_item_lookup",
      "external": false,
      "loc": "net/core/devlink.c:8385",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_trap_groups_register",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "devlink_trap_group_item_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593761780,
      "name": "devlink_trap_group_item_lookup",
      "external": false,
      "loc": "net/core/devlink.c:8914",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devl_trap_groups_register",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "devlink_trap_group_item_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595869692,
      "name": "devlink_trap_group_item_lookup",
      "external": false,
      "loc": "net/devlink/leftover.c:5766",
      "file": "net/devlink/leftover.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/devlink/leftover.c:devl_trap_groups_register",
        "net/devlink/leftover.c:devlink_nl_cmd_trap_group_set_doit",
        "net/devlink/leftover.c:devlink_nl_cmd_trap_group_get_doit"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "devlink_trap_group_item_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596759622,
      "name": "devlink_trap_group_item_lookup",
      "external": false,
      "loc": "net/devlink/trap.c:436",
      "file": "net/devlink/trap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/devlink/trap.c:devl_trap_groups_register",
        "net/devlink/trap.c:devlink_nl_trap_group_set_doit",
        "net/devlink/trap.c:devlink_nl_trap_group_get_doit"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
struct devlink_trap_group_item * devlink_trap_group_item_lookup(struct devlink * devlink, const char * name)
```

```json
{
  "name": "devlink_trap_group_item_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502357792,
      "name": "devlink_trap_group_item_lookup",
      "external": false,
      "loc": "net/core/devlink.c:5572",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_traps_register",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502357792,
      "name": "devlink_trap_group_item_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
struct devlink_trap_group_item * devlink_trap_group_item_lookup(struct devlink * devlink, const char * name)
```

```json
{
  "name": "devlink_trap_group_item_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235095364,
      "name": "devlink_trap_group_item_lookup",
      "external": false,
      "loc": "net/core/devlink.c:5572",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_traps_register",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235095364,
      "name": "devlink_trap_group_item_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
struct devlink_trap_group_item * devlink_trap_group_item_lookup(struct devlink * devlink, const char * name)
```

```json
{
  "name": "devlink_trap_group_item_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295883520,
      "name": "devlink_trap_group_item_lookup",
      "external": false,
      "loc": "net/core/devlink.c:5572",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_traps_register",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295883520,
      "name": "devlink_trap_group_item_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 576
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
struct devlink_trap_group_item * devlink_trap_group_item_lookup(struct devlink * devlink, const char * name)
```

```json
{
  "name": "devlink_trap_group_item_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278575202,
      "name": "devlink_trap_group_item_lookup",
      "external": false,
      "loc": "net/core/devlink.c:5572",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_traps_register",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278575202,
      "name": "devlink_trap_group_item_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct devlink_trap_group_item * devlink_trap_group_item_lookup(struct devlink * devlink, const char * name)
```

```json
{
  "name": "devlink_trap_group_item_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588394144,
      "name": "devlink_trap_group_item_lookup",
      "external": false,
      "loc": "net/core/devlink.c:5572",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_traps_register",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588394144,
      "name": "devlink_trap_group_item_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct devlink_trap_group_item * devlink_trap_group_item_lookup(struct devlink * devlink, const char * name)
```

```json
{
  "name": "devlink_trap_group_item_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588106832,
      "name": "devlink_trap_group_item_lookup",
      "external": false,
      "loc": "net/core/devlink.c:5572",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_traps_register",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588106832,
      "name": "devlink_trap_group_item_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct devlink_trap_group_item * devlink_trap_group_item_lookup(struct devlink * devlink, const char * name)
```

```json
{
  "name": "devlink_trap_group_item_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588726320,
      "name": "devlink_trap_group_item_lookup",
      "external": false,
      "loc": "net/core/devlink.c:5572",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_traps_register",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588726320,
      "name": "devlink_trap_group_item_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct devlink_trap_group_item * devlink_trap_group_item_lookup(struct devlink * devlink, const char * name)
```

```json
{
  "name": "devlink_trap_group_item_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588866736,
      "name": "devlink_trap_group_item_lookup",
      "external": false,
      "loc": "net/core/devlink.c:5572",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_traps_register",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588866736,
      "name": "devlink_trap_group_item_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
<details>
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
struct devlink_trap_group_item * devlink_trap_group_item_lookup(struct devlink * devlink, const char * name)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
struct devlink_trap_group_item * devlink_trap_group_item_lookup(struct devlink * devlink, const char * name)
```
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
