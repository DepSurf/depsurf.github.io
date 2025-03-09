# Function: <code>devlink_trap_group_item_put</code>

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
void devlink_trap_group_item_put(struct devlink * devlink, struct devlink_trap_group_item * group_item)
```

```json
{
  "name": "devlink_trap_group_item_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588821264,
      "name": "devlink_trap_group_item_put",
      "external": false,
      "loc": "net/core/devlink.c:7737",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_traps_register",
        "net/core/devlink.c:devlink_trap_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588821264,
      "name": "devlink_trap_group_item_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "devlink_trap_group_item_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336502397344,
      "name": "devlink_trap_group_item_put",
      "external": false,
      "loc": "net/core/devlink.c:7737",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_traps_register",
        "net/core/devlink.c:devlink_trap_unregister"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "devlink_trap_group_item_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3235132932,
      "name": "devlink_trap_group_item_put",
      "external": false,
      "loc": "net/core/devlink.c:7737",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_traps_register",
        "net/core/devlink.c:devlink_trap_unregister"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void devlink_trap_group_item_put(struct devlink * devlink, struct devlink_trap_group_item * group_item)
```

```json
{
  "name": "devlink_trap_group_item_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295936944,
      "name": "devlink_trap_group_item_put",
      "external": false,
      "loc": "net/core/devlink.c:7737",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_traps_register",
        "net/core/devlink.c:devlink_trap_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295936944,
      "name": "devlink_trap_group_item_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "devlink_trap_group_item_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278609054,
      "name": "devlink_trap_group_item_put",
      "external": false,
      "loc": "net/core/devlink.c:7737",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_traps_register",
        "net/core/devlink.c:devlink_trap_unregister"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void devlink_trap_group_item_put(struct devlink * devlink, struct devlink_trap_group_item * group_item)
```

```json
{
  "name": "devlink_trap_group_item_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588427648,
      "name": "devlink_trap_group_item_put",
      "external": false,
      "loc": "net/core/devlink.c:7737",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_traps_register",
        "net/core/devlink.c:devlink_trap_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588427648,
      "name": "devlink_trap_group_item_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
void devlink_trap_group_item_put(struct devlink * devlink, struct devlink_trap_group_item * group_item)
```

```json
{
  "name": "devlink_trap_group_item_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588140336,
      "name": "devlink_trap_group_item_put",
      "external": false,
      "loc": "net/core/devlink.c:7737",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_traps_register",
        "net/core/devlink.c:devlink_trap_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588140336,
      "name": "devlink_trap_group_item_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
void devlink_trap_group_item_put(struct devlink * devlink, struct devlink_trap_group_item * group_item)
```

```json
{
  "name": "devlink_trap_group_item_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588759824,
      "name": "devlink_trap_group_item_put",
      "external": false,
      "loc": "net/core/devlink.c:7737",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_traps_register",
        "net/core/devlink.c:devlink_trap_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588759824,
      "name": "devlink_trap_group_item_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
void devlink_trap_group_item_put(struct devlink * devlink, struct devlink_trap_group_item * group_item)
```

```json
{
  "name": "devlink_trap_group_item_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588900352,
      "name": "devlink_trap_group_item_put",
      "external": false,
      "loc": "net/core/devlink.c:7737",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_traps_register",
        "net/core/devlink.c:devlink_trap_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588900352,
      "name": "devlink_trap_group_item_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
void devlink_trap_group_item_put(struct devlink * devlink, struct devlink_trap_group_item * group_item)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void devlink_trap_group_item_put(struct devlink * devlink, struct devlink_trap_group_item * group_item)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void devlink_trap_group_item_put(struct devlink * devlink, struct devlink_trap_group_item * group_item)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void devlink_trap_group_item_put(struct devlink * devlink, struct devlink_trap_group_item * group_item)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void devlink_trap_group_item_put(struct devlink * devlink, struct devlink_trap_group_item * group_item)
```
</details>
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
