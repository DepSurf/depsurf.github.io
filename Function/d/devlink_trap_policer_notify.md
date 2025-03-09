# Function: <code>devlink_trap_policer_notify</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void devlink_trap_policer_notify(struct devlink * devlink, const struct devlink_trap_policer_item * policer_item, enum devlink_command cmd)
```

```json
{
  "name": "devlink_trap_policer_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589722656,
      "name": "devlink_trap_policer_notify",
      "external": false,
      "loc": "net/core/devlink.c:9093",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_trap_policer_unregister",
        "net/core/devlink.c:devlink_trap_policer_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589722656,
      "name": "devlink_trap_policer_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void devlink_trap_policer_notify(struct devlink * devlink, const struct devlink_trap_policer_item * policer_item, enum devlink_command cmd)
```

```json
{
  "name": "devlink_trap_policer_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589757456,
      "name": "devlink_trap_policer_notify",
      "external": false,
      "loc": "net/core/devlink.c:10047",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_trap_policer_unregister",
        "net/core/devlink.c:devlink_trap_policer_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589757456,
      "name": "devlink_trap_policer_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void devlink_trap_policer_notify(struct devlink * devlink, const struct devlink_trap_policer_item * policer_item, enum devlink_command cmd)
```

```json
{
  "name": "devlink_trap_policer_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589606160,
      "name": "devlink_trap_policer_notify",
      "external": false,
      "loc": "net/core/devlink.c:10311",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_trap_policers_register",
        "net/core/devlink.c:devlink_trap_policer_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589606160,
      "name": "devlink_trap_policer_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void devlink_trap_policer_notify(struct devlink * devlink, const struct devlink_trap_policer_item * policer_item, enum devlink_command cmd)
```

```json
{
  "name": "devlink_trap_policer_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590352880,
      "name": "devlink_trap_policer_notify",
      "external": false,
      "loc": "net/core/devlink.c:11253",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_trap_policers_register",
        "net/core/devlink.c:devlink_trap_policer_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590352880,
      "name": "devlink_trap_policer_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
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
void devlink_trap_policer_notify(struct devlink * devlink, const struct devlink_trap_policer_item * policer_item, enum devlink_command cmd)
```

```json
{
  "name": "devlink_trap_policer_notify",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591937360,
      "name": "devlink_trap_policer_notify",
      "external": false,
      "loc": "net/core/devlink.c:11849",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_trap_policers_register",
        "net/core/devlink.c:devlink_trap_policer_unregister",
        "net/core/devlink.c:devlink_unregister",
        "net/core/devlink.c:devlink_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591937360,
      "name": "devlink_trap_policer_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
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
void devlink_trap_policer_notify(struct devlink * devlink, const struct devlink_trap_policer_item * policer_item, enum devlink_command cmd)
```

```json
{
  "name": "devlink_trap_policer_notify",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593791040,
      "name": "devlink_trap_policer_notify",
      "external": false,
      "loc": "net/core/devlink.c:12742",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devl_trap_policers_register",
        "net/core/devlink.c:devlink_trap_policer_unregister",
        "net/core/devlink.c:devlink_notify_unregister",
        "net/core/devlink.c:devlink_notify_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593791040,
      "name": "devlink_trap_policer_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
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
void devlink_trap_policer_notify(struct devlink * devlink, const struct devlink_trap_policer_item * policer_item, enum devlink_command cmd)
```

```json
{
  "name": "devlink_trap_policer_notify",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595850480,
      "name": "devlink_trap_policer_notify",
      "external": false,
      "loc": "net/devlink/leftover.c:9337",
      "file": "net/devlink/leftover.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/devlink/leftover.c:devl_trap_policers_register",
        "net/devlink/leftover.c:devlink_trap_policer_unregister",
        "net/devlink/leftover.c:devlink_notify_unregister",
        "net/devlink/leftover.c:devlink_notify_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595850480,
      "name": "devlink_trap_policer_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 277
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
void devlink_trap_policer_notify(struct devlink * devlink, const struct devlink_trap_policer_item * policer_item, enum devlink_command cmd)
```

```json
{
  "name": "devlink_trap_policer_notify",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596756384,
      "name": "devlink_trap_policer_notify",
      "external": false,
      "loc": "net/devlink/trap.c:1704",
      "file": "net/devlink/trap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/devlink/trap.c:devl_trap_policers_register",
        "net/devlink/trap.c:devlink_trap_policer_unregister",
        "net/devlink/trap.c:devlink_trap_policers_notify_unregister",
        "net/devlink/trap.c:devlink_trap_policers_notify_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596756384,
      "name": "devlink_trap_policer_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 438
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void devlink_trap_policer_notify(struct devlink * devlink, const struct devlink_trap_policer_item * policer_item, enum devlink_command cmd)
```
</details>
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
