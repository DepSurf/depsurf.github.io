# Function: <code>mptcp_token_get_sock</code>

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
struct mptcp_sock * mptcp_token_get_sock(u32 token)
```

```json
{
  "name": "mptcp_token_get_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591107696,
      "name": "mptcp_token_get_sock",
      "external": true,
      "loc": "net/mptcp/token.c:153",
      "file": "net/mptcp/token.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591107696,
      "name": "mptcp_token_get_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
struct mptcp_sock * mptcp_token_get_sock(u32 token)
```

```json
{
  "name": "mptcp_token_get_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591189472,
      "name": "mptcp_token_get_sock",
      "external": true,
      "loc": "net/mptcp/token.c:242",
      "file": "net/mptcp/token.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/syncookies.c:mptcp_token_join_cookie_init_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591189472,
      "name": "mptcp_token_get_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 245
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
struct mptcp_sock * mptcp_token_get_sock(u32 token)
```

```json
{
  "name": "mptcp_token_get_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591126864,
      "name": "mptcp_token_get_sock",
      "external": true,
      "loc": "net/mptcp/token.c:242",
      "file": "net/mptcp/token.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/subflow.c:subflow_check_req",
        "net/mptcp/syncookies.c:mptcp_token_join_cookie_init_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591126864,
      "name": "mptcp_token_get_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 238
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
struct mptcp_sock * mptcp_token_get_sock(struct net * net, u32 token)
```

```json
{
  "name": "mptcp_token_get_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591974752,
      "name": "mptcp_token_get_sock",
      "external": true,
      "loc": "net/mptcp/token.c:242",
      "file": "net/mptcp/token.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/subflow.c:subflow_check_req",
        "net/mptcp/syncookies.c:mptcp_token_join_cookie_init_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591974752,
      "name": "mptcp_token_get_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
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
struct mptcp_sock * mptcp_token_get_sock(struct net * net, u32 token)
```

```json
{
  "name": "mptcp_token_get_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593703840,
      "name": "mptcp_token_get_sock",
      "external": true,
      "loc": "net/mptcp/token.c:242",
      "file": "net/mptcp/token.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/subflow.c:subflow_check_req",
        "net/mptcp/pm_userspace.c:mptcp_userspace_pm_set_flags",
        "net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_destroy",
        "net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_create",
        "net/mptcp/pm_userspace.c:mptcp_nl_cmd_remove",
        "net/mptcp/pm_userspace.c:mptcp_nl_cmd_announce",
        "net/mptcp/syncookies.c:mptcp_token_join_cookie_init_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593703840,
      "name": "mptcp_token_get_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
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
struct mptcp_sock * mptcp_token_get_sock(struct net * net, u32 token)
```

```json
{
  "name": "mptcp_token_get_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595637632,
      "name": "mptcp_token_get_sock",
      "external": true,
      "loc": "net/mptcp/token.c:242",
      "file": "net/mptcp/token.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/subflow.c:subflow_check_req",
        "net/mptcp/pm_userspace.c:mptcp_userspace_pm_set_flags",
        "net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_destroy",
        "net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_create",
        "net/mptcp/pm_userspace.c:mptcp_nl_cmd_remove",
        "net/mptcp/pm_userspace.c:mptcp_nl_cmd_announce",
        "net/mptcp/syncookies.c:mptcp_token_join_cookie_init_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595637632,
      "name": "mptcp_token_get_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
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
struct mptcp_sock * mptcp_token_get_sock(struct net * net, u32 token)
```

```json
{
  "name": "mptcp_token_get_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596145888,
      "name": "mptcp_token_get_sock",
      "external": true,
      "loc": "net/mptcp/token.c:246",
      "file": "net/mptcp/token.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/subflow.c:subflow_check_req",
        "net/mptcp/pm_userspace.c:mptcp_userspace_pm_set_flags",
        "net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_destroy",
        "net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_create",
        "net/mptcp/pm_userspace.c:mptcp_nl_cmd_remove",
        "net/mptcp/pm_userspace.c:mptcp_nl_cmd_announce",
        "net/mptcp/syncookies.c:mptcp_token_join_cookie_init_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596145888,
      "name": "mptcp_token_get_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 285
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
struct mptcp_sock * mptcp_token_get_sock(struct net * net, u32 token)
```

```json
{
  "name": "mptcp_token_get_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597019600,
      "name": "mptcp_token_get_sock",
      "external": true,
      "loc": "net/mptcp/token.c:246",
      "file": "net/mptcp/token.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/subflow.c:subflow_check_req",
        "net/mptcp/pm_userspace.c:mptcp_userspace_pm_set_flags",
        "net/mptcp/pm_userspace.c:mptcp_pm_nl_subflow_destroy_doit",
        "net/mptcp/pm_userspace.c:mptcp_pm_nl_subflow_create_doit",
        "net/mptcp/pm_userspace.c:mptcp_pm_nl_remove_doit",
        "net/mptcp/pm_userspace.c:mptcp_pm_nl_announce_doit",
        "net/mptcp/syncookies.c:mptcp_token_join_cookie_init_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597019600,
      "name": "mptcp_token_get_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 285
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
struct mptcp_sock * mptcp_token_get_sock(u32 token)
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
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct net * net</code>
</li>
<li>
<b>Param reordered. </b>
<code>token</code> ➡️ <code>net, token</code>
</li>
</ul>
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
