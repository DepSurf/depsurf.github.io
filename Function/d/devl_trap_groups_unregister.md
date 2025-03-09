# Function: <code>devl_trap_groups_unregister</code>

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
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
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
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void devl_trap_groups_unregister(struct devlink * devlink, const struct devlink_trap_group * groups, size_t groups_count)
```

```json
{
  "name": "devl_trap_groups_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593762632,
      "name": "devl_trap_groups_unregister",
      "external": true,
      "loc": "net/core/devlink.c:12711",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_trap_groups_unregister"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593761536,
      "name": "devl_trap_groups_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void devl_trap_groups_unregister(struct devlink * devlink, const struct devlink_trap_group * groups, size_t groups_count)
```

```json
{
  "name": "devl_trap_groups_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595870508,
      "name": "devl_trap_groups_unregister",
      "external": true,
      "loc": "net/devlink/leftover.c:9306",
      "file": "net/devlink/leftover.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/devlink/leftover.c:devlink_trap_groups_unregister"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595869424,
      "name": "devl_trap_groups_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void devl_trap_groups_unregister(struct devlink * devlink, const struct devlink_trap_group * groups, size_t groups_count)
```

```json
{
  "name": "devl_trap_groups_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596760492,
      "name": "devl_trap_groups_unregister",
      "external": true,
      "loc": "net/devlink/trap.c:1673",
      "file": "net/devlink/trap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/devlink/trap.c:devlink_trap_groups_unregister"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596759360,
      "name": "devl_trap_groups_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
void devl_trap_groups_unregister(struct devlink * devlink, const struct devlink_trap_group * groups, size_t groups_count)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
