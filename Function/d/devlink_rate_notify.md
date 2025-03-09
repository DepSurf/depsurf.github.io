# Function: <code>devlink_rate_notify</code>

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
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void devlink_rate_notify(struct devlink_rate * devlink_rate, enum devlink_command cmd)
```

```json
{
  "name": "devlink_rate_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590368704,
      "name": "devlink_rate_notify",
      "external": false,
      "loc": "net/core/devlink.c:1063",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_rate_leaf_destroy",
        "net/core/devlink.c:devlink_rate_leaf_create",
        "net/core/devlink.c:devlink_nl_cmd_rate_del_doit",
        "net/core/devlink.c:devlink_nl_cmd_rate_new_doit",
        "net/core/devlink.c:devlink_nl_cmd_rate_set_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590368704,
      "name": "devlink_rate_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void devlink_rate_notify(struct devlink_rate * devlink_rate, enum devlink_command cmd)
```

```json
{
  "name": "devlink_rate_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591966848,
      "name": "devlink_rate_notify",
      "external": false,
      "loc": "net/core/devlink.c:1288",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devl_rate_leaf_destroy",
        "net/core/devlink.c:devl_rate_leaf_create",
        "net/core/devlink.c:devlink_unregister",
        "net/core/devlink.c:devlink_register",
        "net/core/devlink.c:devlink_nl_cmd_rate_del_doit",
        "net/core/devlink.c:devlink_nl_cmd_rate_new_doit",
        "net/core/devlink.c:devlink_nl_cmd_rate_set_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591966848,
      "name": "devlink_rate_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
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
void devlink_rate_notify(struct devlink_rate * devlink_rate, enum devlink_command cmd)
```

```json
{
  "name": "devlink_rate_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593770272,
      "name": "devlink_rate_notify",
      "external": false,
      "loc": "net/core/devlink.c:1514",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devl_rate_leaf_destroy",
        "net/core/devlink.c:devl_rate_leaf_create",
        "net/core/devlink.c:devlink_notify_unregister",
        "net/core/devlink.c:devlink_notify_register",
        "net/core/devlink.c:devlink_nl_cmd_rate_del_doit",
        "net/core/devlink.c:devlink_nl_cmd_rate_new_doit",
        "net/core/devlink.c:devlink_nl_cmd_rate_set_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593770272,
      "name": "devlink_rate_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
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
void devlink_rate_notify(struct devlink_rate * devlink_rate, enum devlink_command cmd)
```

```json
{
  "name": "devlink_rate_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595877136,
      "name": "devlink_rate_notify",
      "external": false,
      "loc": "net/devlink/leftover.c:981",
      "file": "net/devlink/leftover.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/devlink/leftover.c:devl_rate_leaf_destroy",
        "net/devlink/leftover.c:devl_rate_leaf_create",
        "net/devlink/leftover.c:devlink_notify_unregister",
        "net/devlink/leftover.c:devlink_notify_register",
        "net/devlink/leftover.c:devlink_nl_cmd_rate_del_doit",
        "net/devlink/leftover.c:devlink_nl_cmd_rate_new_doit",
        "net/devlink/leftover.c:devlink_nl_cmd_rate_set_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595877136,
      "name": "devlink_rate_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 263
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
void devlink_rate_notify(struct devlink_rate * devlink_rate, enum devlink_command cmd)
```

```json
{
  "name": "devlink_rate_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596771968,
      "name": "devlink_rate_notify",
      "external": false,
      "loc": "net/devlink/rate.c:140",
      "file": "net/devlink/rate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/devlink/rate.c:devl_rate_leaf_destroy",
        "net/devlink/rate.c:devl_rate_leaf_create",
        "net/devlink/rate.c:devlink_nl_rate_del_doit",
        "net/devlink/rate.c:devlink_nl_rate_new_doit",
        "net/devlink/rate.c:devlink_nl_rate_set_doit",
        "net/devlink/rate.c:devlink_rates_notify_unregister",
        "net/devlink/rate.c:devlink_rates_notify_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596771968,
      "name": "devlink_rate_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 441
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
void devlink_rate_notify(struct devlink_rate * devlink_rate, enum devlink_command cmd)
```
</details>
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
