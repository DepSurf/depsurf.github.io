# Function: <code>mptcp_userspace_pm_append_new_local_addr</code>

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
int mptcp_userspace_pm_append_new_local_addr(struct mptcp_sock * msk, struct mptcp_pm_addr_entry * entry)
```

```json
{
  "name": "mptcp_userspace_pm_append_new_local_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593742848,
      "name": "mptcp_userspace_pm_append_new_local_addr",
      "external": true,
      "loc": "net/mptcp/pm_userspace.c:28",
      "file": "net/mptcp/pm_userspace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/pm_userspace.c:mptcp_nl_cmd_announce",
        "net/mptcp/pm_userspace.c:mptcp_userspace_pm_get_local_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593742848,
      "name": "mptcp_userspace_pm_append_new_local_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 453
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
int mptcp_userspace_pm_append_new_local_addr(struct mptcp_sock * msk, struct mptcp_pm_addr_entry * entry)
```

```json
{
  "name": "mptcp_userspace_pm_append_new_local_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595679392,
      "name": "mptcp_userspace_pm_append_new_local_addr",
      "external": true,
      "loc": "net/mptcp/pm_userspace.c:28",
      "file": "net/mptcp/pm_userspace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/pm_userspace.c:mptcp_nl_cmd_announce",
        "net/mptcp/pm_userspace.c:mptcp_userspace_pm_get_local_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595679392,
      "name": "mptcp_userspace_pm_append_new_local_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 429
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
int mptcp_userspace_pm_append_new_local_addr(struct mptcp_sock * msk, struct mptcp_pm_addr_entry * entry)
```

```json
{
  "name": "mptcp_userspace_pm_append_new_local_addr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596189568,
      "name": "mptcp_userspace_pm_append_new_local_addr",
      "external": false,
      "loc": "net/mptcp/pm_userspace.c:28",
      "file": "net/mptcp/pm_userspace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_create",
        "net/mptcp/pm_userspace.c:mptcp_nl_cmd_announce",
        "net/mptcp/pm_userspace.c:mptcp_userspace_pm_get_local_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596189568,
      "name": "mptcp_userspace_pm_append_new_local_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 432
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
int mptcp_userspace_pm_append_new_local_addr(struct mptcp_sock * msk, struct mptcp_pm_addr_entry * entry, bool needs_id)
```

```json
{
  "name": "mptcp_userspace_pm_append_new_local_addr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597065008,
      "name": "mptcp_userspace_pm_append_new_local_addr",
      "external": false,
      "loc": "net/mptcp/pm_userspace.c:28",
      "file": "net/mptcp/pm_userspace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/pm_userspace.c:mptcp_pm_nl_subflow_create_doit",
        "net/mptcp/pm_userspace.c:mptcp_pm_nl_announce_doit",
        "net/mptcp/pm_userspace.c:mptcp_userspace_pm_get_local_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597065008,
      "name": "mptcp_userspace_pm_append_new_local_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 453
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
int mptcp_userspace_pm_append_new_local_addr(struct mptcp_sock * msk, struct mptcp_pm_addr_entry * entry)
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool needs_id</code>
</li>
</ul>
</details>
</li>
</ul>
