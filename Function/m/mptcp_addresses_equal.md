# Function: <code>mptcp_addresses_equal</code>

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
bool mptcp_addresses_equal(const struct mptcp_addr_info * a, const struct mptcp_addr_info * b, bool use_port)
```

```json
{
  "name": "mptcp_addresses_equal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593718528,
      "name": "mptcp_addresses_equal",
      "external": true,
      "loc": "net/mptcp/pm_netlink.c:61",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_flags",
        "net/mptcp/pm_netlink.c:mptcp_pm_remove_addrs_and_subflows",
        "net/mptcp/pm_netlink.c:mptcp_nl_remove_id_zero_address",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_get_local_id",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_get_local_id",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_mp_prio_send_ack",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_mp_prio_send_ack",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received",
        "net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr",
        "net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr",
        "net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr",
        "net/mptcp/pm_netlink.c:mptcp_pm_alloc_anno_list",
        "net/mptcp/pm_netlink.c:mptcp_pm_del_add_timer",
        "net/mptcp/pm_netlink.c:mptcp_pm_sport_in_anno_list",
        "net/mptcp/pm_userspace.c:mptcp_userspace_pm_append_new_local_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593718528,
      "name": "mptcp_addresses_equal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
bool mptcp_addresses_equal(const struct mptcp_addr_info * a, const struct mptcp_addr_info * b, bool use_port)
```

```json
{
  "name": "mptcp_addresses_equal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595653632,
      "name": "mptcp_addresses_equal",
      "external": true,
      "loc": "net/mptcp/pm_netlink.c:61",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_flags",
        "net/mptcp/pm_netlink.c:mptcp_pm_remove_addrs_and_subflows",
        "net/mptcp/pm_netlink.c:mptcp_nl_remove_id_zero_address",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_get_local_id",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_get_local_id",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_mp_prio_send_ack",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_mp_prio_send_ack",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received",
        "net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr",
        "net/mptcp/pm_netlink.c:mptcp_pm_alloc_anno_list",
        "net/mptcp/pm_netlink.c:mptcp_pm_del_add_timer",
        "net/mptcp/pm_netlink.c:mptcp_pm_sport_in_anno_list",
        "net/mptcp/pm_userspace.c:mptcp_userspace_pm_append_new_local_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595653632,
      "name": "mptcp_addresses_equal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
bool mptcp_addresses_equal(const struct mptcp_addr_info * a, const struct mptcp_addr_info * b, bool use_port)
```

```json
{
  "name": "mptcp_addresses_equal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596162432,
      "name": "mptcp_addresses_equal",
      "external": true,
      "loc": "net/mptcp/pm_netlink.c:61",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/pm.c:mptcp_pm_get_local_id",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_set_flags",
        "net/mptcp/pm_netlink.c:mptcp_pm_remove_addrs_and_subflows",
        "net/mptcp/pm_netlink.c:mptcp_nl_remove_id_zero_address",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_get_local_id",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_mp_prio_send_ack",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_mp_prio_send_ack",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received",
        "net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr",
        "net/mptcp/pm_netlink.c:mptcp_pm_alloc_anno_list",
        "net/mptcp/pm_netlink.c:mptcp_pm_del_add_timer",
        "net/mptcp/pm_netlink.c:mptcp_pm_sport_in_anno_list",
        "net/mptcp/pm_userspace.c:mptcp_userspace_pm_append_new_local_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596162432,
      "name": "mptcp_addresses_equal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
bool mptcp_addresses_equal(const struct mptcp_addr_info * a, const struct mptcp_addr_info * b, bool use_port)
```

```json
{
  "name": "mptcp_addresses_equal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597036480,
      "name": "mptcp_addresses_equal",
      "external": true,
      "loc": "net/mptcp/pm_netlink.c:62",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/pm.c:mptcp_pm_get_local_id",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_set_flags",
        "net/mptcp/pm_netlink.c:mptcp_pm_remove_addrs_and_subflows",
        "net/mptcp/pm_netlink.c:mptcp_nl_remove_id_zero_address",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_get_local_id",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_mp_prio_send_ack",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_mp_prio_send_ack",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received",
        "net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr",
        "net/mptcp/pm_netlink.c:mptcp_pm_alloc_anno_list",
        "net/mptcp/pm_netlink.c:mptcp_pm_del_add_timer",
        "net/mptcp/pm_netlink.c:mptcp_pm_sport_in_anno_list",
        "net/mptcp/pm_userspace.c:mptcp_userspace_pm_get_local_id",
        "net/mptcp/pm_userspace.c:mptcp_userspace_pm_append_new_local_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597036480,
      "name": "mptcp_addresses_equal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
bool mptcp_addresses_equal(const struct mptcp_addr_info * a, const struct mptcp_addr_info * b, bool use_port)
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
