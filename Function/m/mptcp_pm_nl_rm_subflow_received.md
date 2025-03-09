# Function: <code>mptcp_pm_nl_rm_subflow_received</code>

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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void mptcp_pm_nl_rm_subflow_received(struct mptcp_sock * msk, u8 rm_id)
```

```json
{
  "name": "mptcp_pm_nl_rm_subflow_received",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591202832,
      "name": "mptcp_pm_nl_rm_subflow_received",
      "external": true,
      "loc": "net/mptcp/pm_netlink.c:485",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/pm.c:mptcp_pm_remove_subflow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591202832,
      "name": "mptcp_pm_nl_rm_subflow_received",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 242
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
void mptcp_pm_nl_rm_subflow_received(struct mptcp_sock * msk, const struct mptcp_rm_list * rm_list)
```

```json
{
  "name": "mptcp_pm_nl_rm_subflow_received",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591137546,
      "name": "mptcp_pm_nl_rm_subflow_received",
      "external": true,
      "loc": "net/mptcp/pm_netlink.c:650",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/pm_netlink.c:mptcp_nl_remove_id_zero_address"
      ],
      "caller_func": [
        "net/mptcp/pm.c:mptcp_pm_remove_subflow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591145744,
      "name": "mptcp_pm_nl_rm_subflow_received",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void mptcp_pm_nl_rm_subflow_received(struct mptcp_sock * msk, const struct mptcp_rm_list * rm_list)
```

```json
{
  "name": "mptcp_pm_nl_rm_subflow_received",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591987546,
      "name": "mptcp_pm_nl_rm_subflow_received",
      "external": true,
      "loc": "net/mptcp/pm_netlink.c:776",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/pm_netlink.c:mptcp_nl_remove_id_zero_address"
      ],
      "caller_func": [
        "net/mptcp/pm.c:mptcp_pm_remove_subflow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591996336,
      "name": "mptcp_pm_nl_rm_subflow_received",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void mptcp_pm_nl_rm_subflow_received(struct mptcp_sock * msk, const struct mptcp_rm_list * rm_list)
```

```json
{
  "name": "mptcp_pm_nl_rm_subflow_received",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593728574,
      "name": "mptcp_pm_nl_rm_subflow_received",
      "external": true,
      "loc": "net/mptcp/pm_netlink.c:832",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_flags",
        "net/mptcp/pm_netlink.c:mptcp_nl_remove_id_zero_address"
      ],
      "caller_func": [
        "net/mptcp/pm.c:mptcp_pm_remove_subflow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593726144,
      "name": "mptcp_pm_nl_rm_subflow_received",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void mptcp_pm_nl_rm_subflow_received(struct mptcp_sock * msk, const struct mptcp_rm_list * rm_list)
```

```json
{
  "name": "mptcp_pm_nl_rm_subflow_received",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595663491,
      "name": "mptcp_pm_nl_rm_subflow_received",
      "external": true,
      "loc": "net/mptcp/pm_netlink.c:845",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_flags",
        "net/mptcp/pm_netlink.c:mptcp_nl_remove_id_zero_address"
      ],
      "caller_func": [
        "net/mptcp/pm.c:mptcp_pm_remove_subflow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595660960,
      "name": "mptcp_pm_nl_rm_subflow_received",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void mptcp_pm_nl_rm_subflow_received(struct mptcp_sock * msk, const struct mptcp_rm_list * rm_list)
```

```json
{
  "name": "mptcp_pm_nl_rm_subflow_received",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596174776,
      "name": "mptcp_pm_nl_rm_subflow_received",
      "external": true,
      "loc": "net/mptcp/pm_netlink.c:848",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_set_flags",
        "net/mptcp/pm_netlink.c:mptcp_nl_remove_id_zero_address"
      ],
      "caller_func": [
        "net/mptcp/pm.c:mptcp_pm_remove_subflow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596169952,
      "name": "mptcp_pm_nl_rm_subflow_received",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void mptcp_pm_nl_rm_subflow_received(struct mptcp_sock * msk, const struct mptcp_rm_list * rm_list)
```

```json
{
  "name": "mptcp_pm_nl_rm_subflow_received",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071597049192,
      "name": "mptcp_pm_nl_rm_subflow_received",
      "external": true,
      "loc": "net/mptcp/pm_netlink.c:849",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_set_flags",
        "net/mptcp/pm_netlink.c:mptcp_nl_remove_id_zero_address"
      ],
      "caller_func": [
        "net/mptcp/pm.c:mptcp_pm_remove_subflow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597042784,
      "name": "mptcp_pm_nl_rm_subflow_received",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void mptcp_pm_nl_rm_subflow_received(struct mptcp_sock * msk, u8 rm_id)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct mptcp_rm_list * rm_list</code>
</li>
<li>
<b>Param removed. </b>
<code>u8 rm_id</code>
</li>
</ul>
</details>
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
