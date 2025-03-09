# Function: <code>mptcp_pm_get_local_id</code>

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
int mptcp_pm_get_local_id(struct mptcp_sock * msk, struct sock_common * skc)
```

```json
{
  "name": "mptcp_pm_get_local_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591110832,
      "name": "mptcp_pm_get_local_id",
      "external": true,
      "loc": "net/mptcp/pm.c:179",
      "file": "net/mptcp/pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/subflow.c:subflow_rebuild_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591110832,
      "name": "mptcp_pm_get_local_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
int mptcp_pm_get_local_id(struct mptcp_sock * msk, struct sock_common * skc)
```

```json
{
  "name": "mptcp_pm_get_local_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591194016,
      "name": "mptcp_pm_get_local_id",
      "external": true,
      "loc": "net/mptcp/pm.c:262",
      "file": "net/mptcp/pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/subflow.c:__mptcp_subflow_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591194016,
      "name": "mptcp_pm_get_local_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
int mptcp_pm_get_local_id(struct mptcp_sock * msk, struct sock_common * skc)
```

```json
{
  "name": "mptcp_pm_get_local_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591131856,
      "name": "mptcp_pm_get_local_id",
      "external": true,
      "loc": "net/mptcp/pm.c:306",
      "file": "net/mptcp/pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/subflow.c:__mptcp_subflow_connect",
        "net/mptcp/subflow.c:subflow_check_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591131856,
      "name": "mptcp_pm_get_local_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
int mptcp_pm_get_local_id(struct mptcp_sock * msk, struct sock_common * skc)
```

```json
{
  "name": "mptcp_pm_get_local_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591980976,
      "name": "mptcp_pm_get_local_id",
      "external": true,
      "loc": "net/mptcp/pm.c:339",
      "file": "net/mptcp/pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/subflow.c:__mptcp_subflow_connect",
        "net/mptcp/subflow.c:subflow_check_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591980976,
      "name": "mptcp_pm_get_local_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
int mptcp_pm_get_local_id(struct mptcp_sock * msk, struct sock_common * skc)
```

```json
{
  "name": "mptcp_pm_get_local_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593711264,
      "name": "mptcp_pm_get_local_id",
      "external": true,
      "loc": "net/mptcp/pm.c:399",
      "file": "net/mptcp/pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/subflow.c:subflow_v6_rebuild_header",
        "net/mptcp/subflow.c:subflow_rebuild_header",
        "net/mptcp/subflow.c:subflow_check_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593711264,
      "name": "mptcp_pm_get_local_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
int mptcp_pm_get_local_id(struct mptcp_sock * msk, struct sock_common * skc)
```

```json
{
  "name": "mptcp_pm_get_local_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595645712,
      "name": "mptcp_pm_get_local_id",
      "external": true,
      "loc": "net/mptcp/pm.c:399",
      "file": "net/mptcp/pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/subflow.c:subflow_v6_rebuild_header",
        "net/mptcp/subflow.c:subflow_rebuild_header",
        "net/mptcp/subflow.c:subflow_check_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595645712,
      "name": "mptcp_pm_get_local_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
int mptcp_pm_get_local_id(struct mptcp_sock * msk, struct sock_common * skc)
```

```json
{
  "name": "mptcp_pm_get_local_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596154112,
      "name": "mptcp_pm_get_local_id",
      "external": true,
      "loc": "net/mptcp/pm.c:416",
      "file": "net/mptcp/pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/subflow.c:subflow_v6_rebuild_header",
        "net/mptcp/subflow.c:subflow_rebuild_header",
        "net/mptcp/subflow.c:subflow_check_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596154112,
      "name": "mptcp_pm_get_local_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
int mptcp_pm_get_local_id(struct mptcp_sock * msk, struct sock_common * skc)
```

```json
{
  "name": "mptcp_pm_get_local_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597028080,
      "name": "mptcp_pm_get_local_id",
      "external": true,
      "loc": "net/mptcp/pm.c:409",
      "file": "net/mptcp/pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/subflow.c:subflow_v6_rebuild_header",
        "net/mptcp/subflow.c:subflow_rebuild_header",
        "net/mptcp/subflow.c:subflow_check_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597028080,
      "name": "mptcp_pm_get_local_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
int mptcp_pm_get_local_id(struct mptcp_sock * msk, struct sock_common * skc)
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
