# Function: <code>devlink_trap_item_lookup</code>

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
struct devlink_trap_item * devlink_trap_item_lookup(struct devlink * devlink, const char * name)
```

```json
{
  "name": "devlink_trap_item_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588787872,
      "name": "devlink_trap_item_lookup",
      "external": false,
      "loc": "net/core/devlink.c:5262",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_traps_unregister",
        "net/core/devlink.c:devlink_traps_register",
        "net/core/devlink.c:devlink_trap_unregister",
        "net/core/devlink.c:devlink_nl_cmd_trap_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_trap_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588787872,
      "name": "devlink_trap_item_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
  "name": "devlink_trap_item_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589720152,
      "name": "devlink_trap_item_lookup",
      "external": false,
      "loc": "net/core/devlink.c:5850",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_traps_unregister",
        "net/core/devlink.c:devlink_trap_unregister",
        "net/core/devlink.c:devlink_trap_register",
        "net/core/devlink.c:devlink_nl_cmd_trap_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_trap_get_doit"
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
  "name": "devlink_trap_item_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589748408,
      "name": "devlink_trap_item_lookup",
      "external": false,
      "loc": "net/core/devlink.c:6701",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_traps_unregister",
        "net/core/devlink.c:devlink_trap_unregister",
        "net/core/devlink.c:devlink_trap_register",
        "net/core/devlink.c:devlink_nl_cmd_trap_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_trap_get_doit"
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
  "name": "devlink_trap_item_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589640214,
      "name": "devlink_trap_item_lookup",
      "external": false,
      "loc": "net/core/devlink.c:6904",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_traps_unregister",
        "net/core/devlink.c:devlink_traps_register",
        "net/core/devlink.c:devlink_trap_unregister",
        "net/core/devlink.c:devlink_nl_cmd_trap_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_trap_get_doit"
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
  "name": "devlink_trap_item_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590396214,
      "name": "devlink_trap_item_lookup",
      "external": false,
      "loc": "net/core/devlink.c:7530",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_traps_unregister",
        "net/core/devlink.c:devlink_traps_register",
        "net/core/devlink.c:devlink_trap_unregister",
        "net/core/devlink.c:devlink_nl_cmd_trap_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_trap_get_doit"
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
  "name": "devlink_trap_item_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591974550,
      "name": "devlink_trap_item_lookup",
      "external": false,
      "loc": "net/core/devlink.c:8023",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_traps_unregister",
        "net/core/devlink.c:devlink_traps_register",
        "net/core/devlink.c:devlink_trap_unregister",
        "net/core/devlink.c:devlink_nl_cmd_trap_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_trap_get_doit"
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
  "name": "devlink_trap_item_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593785580,
      "name": "devlink_trap_item_lookup",
      "external": false,
      "loc": "net/core/devlink.c:8558",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devl_traps_unregister",
        "net/core/devlink.c:devlink_trap_unregister",
        "net/core/devlink.c:devlink_nl_cmd_trap_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_trap_get_doit"
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
  "name": "devlink_trap_item_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595884760,
      "name": "devlink_trap_item_lookup",
      "external": false,
      "loc": "net/devlink/leftover.c:5414",
      "file": "net/devlink/leftover.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/devlink/leftover.c:devl_traps_unregister",
        "net/devlink/leftover.c:devlink_trap_unregister",
        "net/devlink/leftover.c:devlink_nl_cmd_trap_set_doit",
        "net/devlink/leftover.c:devlink_nl_cmd_trap_get_doit"
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
  "name": "devlink_trap_item_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596764056,
      "name": "devlink_trap_item_lookup",
      "external": false,
      "loc": "net/devlink/trap.c:86",
      "file": "net/devlink/trap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/devlink/trap.c:devl_traps_unregister",
        "net/devlink/trap.c:devlink_trap_unregister",
        "net/devlink/trap.c:devlink_nl_trap_set_doit",
        "net/devlink/trap.c:devlink_nl_trap_get_doit"
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
struct devlink_trap_item * devlink_trap_item_lookup(struct devlink * devlink, const char * name)
```

```json
{
  "name": "devlink_trap_item_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502357928,
      "name": "devlink_trap_item_lookup",
      "external": false,
      "loc": "net/core/devlink.c:5262",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_traps_unregister",
        "net/core/devlink.c:devlink_traps_register",
        "net/core/devlink.c:devlink_trap_unregister",
        "net/core/devlink.c:devlink_nl_cmd_trap_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_trap_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502357928,
      "name": "devlink_trap_item_lookup",
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
struct devlink_trap_item * devlink_trap_item_lookup(struct devlink * devlink, const char * name)
```

```json
{
  "name": "devlink_trap_item_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235095816,
      "name": "devlink_trap_item_lookup",
      "external": false,
      "loc": "net/core/devlink.c:5262",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_traps_unregister",
        "net/core/devlink.c:devlink_traps_register",
        "net/core/devlink.c:devlink_trap_unregister",
        "net/core/devlink.c:devlink_nl_cmd_trap_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_trap_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235095816,
      "name": "devlink_trap_item_lookup",
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
struct devlink_trap_item * devlink_trap_item_lookup(struct devlink * devlink, const char * name)
```

```json
{
  "name": "devlink_trap_item_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295884096,
      "name": "devlink_trap_item_lookup",
      "external": false,
      "loc": "net/core/devlink.c:5262",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_traps_unregister",
        "net/core/devlink.c:devlink_traps_register",
        "net/core/devlink.c:devlink_trap_unregister",
        "net/core/devlink.c:devlink_nl_cmd_trap_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_trap_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295884096,
      "name": "devlink_trap_item_lookup",
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
struct devlink_trap_item * devlink_trap_item_lookup(struct devlink * devlink, const char * name)
```

```json
{
  "name": "devlink_trap_item_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278575308,
      "name": "devlink_trap_item_lookup",
      "external": false,
      "loc": "net/core/devlink.c:5262",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_traps_unregister",
        "net/core/devlink.c:devlink_traps_register",
        "net/core/devlink.c:devlink_trap_unregister",
        "net/core/devlink.c:devlink_nl_cmd_trap_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_trap_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278575308,
      "name": "devlink_trap_item_lookup",
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
struct devlink_trap_item * devlink_trap_item_lookup(struct devlink * devlink, const char * name)
```

```json
{
  "name": "devlink_trap_item_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588394256,
      "name": "devlink_trap_item_lookup",
      "external": false,
      "loc": "net/core/devlink.c:5262",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_traps_unregister",
        "net/core/devlink.c:devlink_traps_register",
        "net/core/devlink.c:devlink_trap_unregister",
        "net/core/devlink.c:devlink_nl_cmd_trap_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_trap_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588394256,
      "name": "devlink_trap_item_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
struct devlink_trap_item * devlink_trap_item_lookup(struct devlink * devlink, const char * name)
```

```json
{
  "name": "devlink_trap_item_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588106944,
      "name": "devlink_trap_item_lookup",
      "external": false,
      "loc": "net/core/devlink.c:5262",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_traps_unregister",
        "net/core/devlink.c:devlink_traps_register",
        "net/core/devlink.c:devlink_trap_unregister",
        "net/core/devlink.c:devlink_nl_cmd_trap_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_trap_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588106944,
      "name": "devlink_trap_item_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
struct devlink_trap_item * devlink_trap_item_lookup(struct devlink * devlink, const char * name)
```

```json
{
  "name": "devlink_trap_item_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588726432,
      "name": "devlink_trap_item_lookup",
      "external": false,
      "loc": "net/core/devlink.c:5262",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_traps_unregister",
        "net/core/devlink.c:devlink_traps_register",
        "net/core/devlink.c:devlink_trap_unregister",
        "net/core/devlink.c:devlink_nl_cmd_trap_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_trap_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588726432,
      "name": "devlink_trap_item_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
struct devlink_trap_item * devlink_trap_item_lookup(struct devlink * devlink, const char * name)
```

```json
{
  "name": "devlink_trap_item_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588866848,
      "name": "devlink_trap_item_lookup",
      "external": false,
      "loc": "net/core/devlink.c:5262",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_traps_unregister",
        "net/core/devlink.c:devlink_traps_register",
        "net/core/devlink.c:devlink_trap_unregister",
        "net/core/devlink.c:devlink_nl_cmd_trap_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_trap_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588866848,
      "name": "devlink_trap_item_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
struct devlink_trap_item * devlink_trap_item_lookup(struct devlink * devlink, const char * name)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
struct devlink_trap_item * devlink_trap_item_lookup(struct devlink * devlink, const char * name)
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
