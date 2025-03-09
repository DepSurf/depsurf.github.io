# Function: <code>devlink_linecard_notify</code>

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
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void devlink_linecard_notify(struct devlink_linecard * linecard, enum devlink_command cmd)
```

```json
{
  "name": "devlink_linecard_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591944384,
      "name": "devlink_linecard_notify",
      "external": false,
      "loc": "net/core/devlink.c:2111",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_linecard_deactivate",
        "net/core/devlink.c:devlink_linecard_activate",
        "net/core/devlink.c:devlink_linecard_provision_fail",
        "net/core/devlink.c:devlink_linecard_provision_clear",
        "net/core/devlink.c:devlink_linecard_provision_set",
        "net/core/devlink.c:devlink_linecard_destroy",
        "net/core/devlink.c:devlink_linecard_create",
        "net/core/devlink.c:devlink_register",
        "net/core/devlink.c:devlink_nl_cmd_linecard_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_linecard_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_linecard_set_doit",
        "net/core/devlink.c:devlink_linecard_type_set",
        "net/core/devlink.c:devlink_linecard_type_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591944384,
      "name": "devlink_linecard_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 278
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
void devlink_linecard_notify(struct devlink_linecard * linecard, enum devlink_command cmd)
```

```json
{
  "name": "devlink_linecard_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593749712,
      "name": "devlink_linecard_notify",
      "external": false,
      "loc": "net/core/devlink.c:2414",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_linecard_nested_dl_set",
        "net/core/devlink.c:devlink_linecard_deactivate",
        "net/core/devlink.c:devlink_linecard_activate",
        "net/core/devlink.c:devlink_linecard_provision_fail",
        "net/core/devlink.c:devlink_linecard_provision_clear",
        "net/core/devlink.c:devlink_linecard_provision_set",
        "net/core/devlink.c:devlink_linecard_destroy",
        "net/core/devlink.c:devlink_linecard_create",
        "net/core/devlink.c:devlink_notify_register",
        "net/core/devlink.c:devlink_nl_cmd_linecard_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_linecard_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_linecard_set_doit",
        "net/core/devlink.c:devlink_linecard_type_set",
        "net/core/devlink.c:devlink_linecard_type_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593749712,
      "name": "devlink_linecard_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 278
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
void devlink_linecard_notify(struct devlink_linecard * linecard, enum devlink_command cmd)
```

```json
{
  "name": "devlink_linecard_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595885792,
      "name": "devlink_linecard_notify",
      "external": false,
      "loc": "net/devlink/leftover.c:1786",
      "file": "net/devlink/leftover.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/devlink/leftover.c:devlink_linecard_nested_dl_set",
        "net/devlink/leftover.c:devlink_linecard_deactivate",
        "net/devlink/leftover.c:devlink_linecard_activate",
        "net/devlink/leftover.c:devlink_linecard_provision_fail",
        "net/devlink/leftover.c:devlink_linecard_provision_clear",
        "net/devlink/leftover.c:devlink_linecard_provision_set",
        "net/devlink/leftover.c:devl_linecard_destroy",
        "net/devlink/leftover.c:devl_linecard_create",
        "net/devlink/leftover.c:devlink_notify_unregister",
        "net/devlink/leftover.c:devlink_notify_register",
        "net/devlink/leftover.c:devlink_nl_cmd_linecard_set_doit",
        "net/devlink/leftover.c:devlink_nl_cmd_linecard_set_doit",
        "net/devlink/leftover.c:devlink_nl_cmd_linecard_set_doit",
        "net/devlink/leftover.c:devlink_linecard_type_set",
        "net/devlink/leftover.c:devlink_linecard_type_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595885792,
      "name": "devlink_linecard_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 279
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
void devlink_linecard_notify(struct devlink_linecard * linecard, enum devlink_command cmd)
```

```json
{
  "name": "devlink_linecard_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596776480,
      "name": "devlink_linecard_notify",
      "external": false,
      "loc": "net/devlink/linecard.c:129",
      "file": "net/devlink/linecard.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/devlink/linecard.c:devlink_linecard_rel_notify_cb",
        "net/devlink/linecard.c:devlink_linecard_deactivate",
        "net/devlink/linecard.c:devlink_linecard_activate",
        "net/devlink/linecard.c:devlink_linecard_provision_fail",
        "net/devlink/linecard.c:devlink_linecard_provision_clear",
        "net/devlink/linecard.c:devlink_linecard_provision_set",
        "net/devlink/linecard.c:devl_linecard_destroy",
        "net/devlink/linecard.c:devl_linecard_create",
        "net/devlink/linecard.c:devlink_nl_linecard_set_doit",
        "net/devlink/linecard.c:devlink_nl_linecard_set_doit",
        "net/devlink/linecard.c:devlink_nl_linecard_set_doit",
        "net/devlink/linecard.c:devlink_linecard_type_set",
        "net/devlink/linecard.c:devlink_linecard_type_set",
        "net/devlink/linecard.c:devlink_linecards_notify_unregister",
        "net/devlink/linecard.c:devlink_linecards_notify_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596776480,
      "name": "devlink_linecard_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 437
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void devlink_linecard_notify(struct devlink_linecard * linecard, enum devlink_command cmd)
```
</details>
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
