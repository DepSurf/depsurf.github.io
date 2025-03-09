# Function: <code>net_dm_hw_trap_summary_probe</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void net_dm_hw_trap_summary_probe(void * ignore, const struct devlink * devlink, struct sk_buff * skb, const struct devlink_trap_metadata * metadata)
```

```json
{
  "name": "net_dm_hw_trap_summary_probe",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589653168,
      "name": "net_dm_hw_trap_summary_probe",
      "external": false,
      "loc": "net/core/drop_monitor.c:437",
      "file": "net/core/drop_monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589653168,
      "name": "net_dm_hw_trap_summary_probe.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 458
    },
    {
      "addr": 18446744071589653632,
      "name": "net_dm_hw_trap_summary_probe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void net_dm_hw_trap_summary_probe(void * ignore, const struct devlink * devlink, struct sk_buff * skb, const struct devlink_trap_metadata * metadata)
```

```json
{
  "name": "net_dm_hw_trap_summary_probe",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589542608,
      "name": "net_dm_hw_trap_summary_probe",
      "external": false,
      "loc": "net/core/drop_monitor.c:437",
      "file": "net/core/drop_monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589542608,
      "name": "net_dm_hw_trap_summary_probe.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 457
    },
    {
      "addr": 18446744071589543072,
      "name": "net_dm_hw_trap_summary_probe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void net_dm_hw_trap_summary_probe(void * ignore, const struct devlink * devlink, struct sk_buff * skb, const struct devlink_trap_metadata * metadata)
```

```json
{
  "name": "net_dm_hw_trap_summary_probe",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590286528,
      "name": "net_dm_hw_trap_summary_probe",
      "external": false,
      "loc": "net/core/drop_monitor.c:441",
      "file": "net/core/drop_monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590286528,
      "name": "net_dm_hw_trap_summary_probe.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 457
    },
    {
      "addr": 18446744071590286992,
      "name": "net_dm_hw_trap_summary_probe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
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
void net_dm_hw_trap_summary_probe(void * ignore, const struct devlink * devlink, struct sk_buff * skb, const struct devlink_trap_metadata * metadata)
```

```json
{
  "name": "net_dm_hw_trap_summary_probe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591869472,
      "name": "net_dm_hw_trap_summary_probe",
      "external": false,
      "loc": "net/core/drop_monitor.c:448",
      "file": "net/core/drop_monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591869472,
      "name": "net_dm_hw_trap_summary_probe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 500
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
void net_dm_hw_trap_summary_probe(void * ignore, const struct devlink * devlink, struct sk_buff * skb, const struct devlink_trap_metadata * metadata)
```

```json
{
  "name": "net_dm_hw_trap_summary_probe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593670368,
      "name": "net_dm_hw_trap_summary_probe",
      "external": false,
      "loc": "net/core/drop_monitor.c:435",
      "file": "net/core/drop_monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593670368,
      "name": "net_dm_hw_trap_summary_probe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 408
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
void net_dm_hw_trap_summary_probe(void * ignore, const struct devlink * devlink, struct sk_buff * skb, const struct devlink_trap_metadata * metadata)
```

```json
{
  "name": "net_dm_hw_trap_summary_probe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594150944,
      "name": "net_dm_hw_trap_summary_probe",
      "external": false,
      "loc": "net/core/drop_monitor.c:437",
      "file": "net/core/drop_monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594150944,
      "name": "net_dm_hw_trap_summary_probe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 408
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
void net_dm_hw_trap_summary_probe(void * ignore, const struct devlink * devlink, struct sk_buff * skb, const struct devlink_trap_metadata * metadata)
```

```json
{
  "name": "net_dm_hw_trap_summary_probe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594947248,
      "name": "net_dm_hw_trap_summary_probe",
      "external": false,
      "loc": "net/core/drop_monitor.c:437",
      "file": "net/core/drop_monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594947248,
      "name": "net_dm_hw_trap_summary_probe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 408
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
void net_dm_hw_trap_summary_probe(void * ignore, const struct devlink * devlink, struct sk_buff * skb, const struct devlink_trap_metadata * metadata)
```
</details>
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
