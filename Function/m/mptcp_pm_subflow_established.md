# Function: <code>mptcp_pm_subflow_established</code>

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
void mptcp_pm_subflow_established(struct mptcp_sock * msk, struct mptcp_subflow_context * subflow)
```

```json
{
  "name": "mptcp_pm_subflow_established",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591110288,
      "name": "mptcp_pm_subflow_established",
      "external": true,
      "loc": "net/mptcp/pm.c:109",
      "file": "net/mptcp/pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/options.c:mptcp_incoming_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591110288,
      "name": "mptcp_pm_subflow_established",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
void mptcp_pm_subflow_established(struct mptcp_sock * msk, struct mptcp_subflow_context * subflow)
```

```json
{
  "name": "mptcp_pm_subflow_established",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591192976,
      "name": "mptcp_pm_subflow_established",
      "external": true,
      "loc": "net/mptcp/pm.c:148",
      "file": "net/mptcp/pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/options.c:check_fully_established"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591192976,
      "name": "mptcp_pm_subflow_established",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
void mptcp_pm_subflow_established(struct mptcp_sock * msk)
```

```json
{
  "name": "mptcp_pm_subflow_established",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591130464,
      "name": "mptcp_pm_subflow_established",
      "external": true,
      "loc": "net/mptcp/pm.c:156",
      "file": "net/mptcp/pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/options.c:check_fully_established",
        "net/mptcp/pm_netlink.c:mptcp_pm_add_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591130464,
      "name": "mptcp_pm_subflow_established",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void mptcp_pm_subflow_established(struct mptcp_sock * msk)
```

```json
{
  "name": "mptcp_pm_subflow_established",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_pm_subflow_established",
      "external": true,
      "loc": "net/mptcp/pm.c:158",
      "file": "net/mptcp/pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/options.c:check_fully_established",
        "net/mptcp/pm_netlink.c:mptcp_pm_add_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592754908,
      "name": "mptcp_pm_subflow_established.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071591979184,
      "name": "mptcp_pm_subflow_established",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void mptcp_pm_subflow_established(struct mptcp_sock * msk)
```

```json
{
  "name": "mptcp_pm_subflow_established",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_pm_subflow_established",
      "external": true,
      "loc": "net/mptcp/pm.c:161",
      "file": "net/mptcp/pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/options.c:check_fully_established",
        "net/mptcp/pm_netlink.c:mptcp_pm_add_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594641947,
      "name": "mptcp_pm_subflow_established.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071593708912,
      "name": "mptcp_pm_subflow_established",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void mptcp_pm_subflow_established(struct mptcp_sock * msk)
```

```json
{
  "name": "mptcp_pm_subflow_established",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_pm_subflow_established",
      "external": true,
      "loc": "net/mptcp/pm.c:161",
      "file": "net/mptcp/pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/options.c:check_fully_established",
        "net/mptcp/pm_netlink.c:mptcp_pm_add_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596371270,
      "name": "mptcp_pm_subflow_established.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071595643184,
      "name": "mptcp_pm_subflow_established",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void mptcp_pm_subflow_established(struct mptcp_sock * msk)
```

```json
{
  "name": "mptcp_pm_subflow_established",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_pm_subflow_established",
      "external": true,
      "loc": "net/mptcp/pm.c:170",
      "file": "net/mptcp/pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/options.c:check_fully_established",
        "net/mptcp/pm_netlink.c:mptcp_pm_add_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596900572,
      "name": "mptcp_pm_subflow_established.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071596151584,
      "name": "mptcp_pm_subflow_established",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void mptcp_pm_subflow_established(struct mptcp_sock * msk)
```

```json
{
  "name": "mptcp_pm_subflow_established",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_pm_subflow_established",
      "external": true,
      "loc": "net/mptcp/pm.c:170",
      "file": "net/mptcp/pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/options.c:check_fully_established",
        "net/mptcp/pm_netlink.c:mptcp_pm_add_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597825778,
      "name": "mptcp_pm_subflow_established.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071597025600,
      "name": "mptcp_pm_subflow_established",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
void mptcp_pm_subflow_established(struct mptcp_sock * msk, struct mptcp_subflow_context * subflow)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct mptcp_subflow_context * subflow</code>
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
