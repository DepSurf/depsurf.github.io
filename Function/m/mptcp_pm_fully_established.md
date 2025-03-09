# Function: <code>mptcp_pm_fully_established</code>

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
void mptcp_pm_fully_established(struct mptcp_sock * msk)
```

```json
{
  "name": "mptcp_pm_fully_established",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591110096,
      "name": "mptcp_pm_fully_established",
      "external": true,
      "loc": "net/mptcp/pm.c:86",
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
      "addr": 18446744071591110096,
      "name": "mptcp_pm_fully_established",
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
void mptcp_pm_fully_established(struct mptcp_sock * msk)
```

```json
{
  "name": "mptcp_pm_fully_established",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591192768,
      "name": "mptcp_pm_fully_established",
      "external": true,
      "loc": "net/mptcp/pm.c:119",
      "file": "net/mptcp/pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_stream_accept",
        "net/mptcp/options.c:check_fully_established"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591192768,
      "name": "mptcp_pm_fully_established",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
void mptcp_pm_fully_established(struct mptcp_sock * msk, const struct sock * ssk, gfp_t gfp)
```

```json
{
  "name": "mptcp_pm_fully_established",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591130208,
      "name": "mptcp_pm_fully_established",
      "external": true,
      "loc": "net/mptcp/pm.c:124",
      "file": "net/mptcp/pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_stream_accept",
        "net/mptcp/options.c:check_fully_established"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591130208,
      "name": "mptcp_pm_fully_established",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
void mptcp_pm_fully_established(struct mptcp_sock * msk, const struct sock * ssk, gfp_t gfp)
```

```json
{
  "name": "mptcp_pm_fully_established",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_pm_fully_established",
      "external": true,
      "loc": "net/mptcp/pm.c:126",
      "file": "net/mptcp/pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_stream_accept",
        "net/mptcp/options.c:check_fully_established"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592754888,
      "name": "mptcp_pm_fully_established.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071591978912,
      "name": "mptcp_pm_fully_established",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
void mptcp_pm_fully_established(struct mptcp_sock * msk, const struct sock * ssk, gfp_t gfp)
```

```json
{
  "name": "mptcp_pm_fully_established",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_pm_fully_established",
      "external": true,
      "loc": "net/mptcp/pm.c:129",
      "file": "net/mptcp/pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_stream_accept",
        "net/mptcp/options.c:check_fully_established"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594641926,
      "name": "mptcp_pm_fully_established.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071593708608,
      "name": "mptcp_pm_fully_established",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void mptcp_pm_fully_established(struct mptcp_sock * msk, const struct sock * ssk, gfp_t gfp)
```

```json
{
  "name": "mptcp_pm_fully_established",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_pm_fully_established",
      "external": true,
      "loc": "net/mptcp/pm.c:129",
      "file": "net/mptcp/pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_stream_accept",
        "net/mptcp/options.c:check_fully_established"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596371249,
      "name": "mptcp_pm_fully_established.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071595642848,
      "name": "mptcp_pm_fully_established",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void mptcp_pm_fully_established(struct mptcp_sock * msk, const struct sock * ssk)
```

```json
{
  "name": "mptcp_pm_fully_established",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_pm_fully_established",
      "external": true,
      "loc": "net/mptcp/pm.c:138",
      "file": "net/mptcp/pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/subflow.c:subflow_syn_recv_sock",
        "net/mptcp/options.c:check_fully_established"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596900551,
      "name": "mptcp_pm_fully_established.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071596151248,
      "name": "mptcp_pm_fully_established",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
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
void mptcp_pm_fully_established(struct mptcp_sock * msk, const struct sock * ssk)
```

```json
{
  "name": "mptcp_pm_fully_established",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_pm_fully_established",
      "external": true,
      "loc": "net/mptcp/pm.c:138",
      "file": "net/mptcp/pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/subflow.c:subflow_syn_recv_sock",
        "net/mptcp/options.c:check_fully_established"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597825757,
      "name": "mptcp_pm_fully_established.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071597025264,
      "name": "mptcp_pm_fully_established",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
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
void mptcp_pm_fully_established(struct mptcp_sock * msk)
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
<b>Param added. </b>
<code>const struct sock * ssk</code>
</li>
<li>
<b>Param added. </b>
<code>gfp_t gfp</code>
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>gfp_t gfp</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
