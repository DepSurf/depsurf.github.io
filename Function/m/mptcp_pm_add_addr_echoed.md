# Function: <code>mptcp_pm_add_addr_echoed</code>

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
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void mptcp_pm_add_addr_echoed(struct mptcp_sock * msk, struct mptcp_addr_info * addr)
```

```json
{
  "name": "mptcp_pm_add_addr_echoed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591130912,
      "name": "mptcp_pm_add_addr_echoed",
      "external": true,
      "loc": "net/mptcp/pm.c:200",
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
      "addr": 18446744071591130912,
      "name": "mptcp_pm_add_addr_echoed",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void mptcp_pm_add_addr_echoed(struct mptcp_sock * msk, struct mptcp_addr_info * addr)
```

```json
{
  "name": "mptcp_pm_add_addr_echoed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_pm_add_addr_echoed",
      "external": true,
      "loc": "net/mptcp/pm.c:204",
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
      "addr": 18446744071592754998,
      "name": "mptcp_pm_add_addr_echoed.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071591979680,
      "name": "mptcp_pm_add_addr_echoed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
void mptcp_pm_add_addr_echoed(struct mptcp_sock * msk, const struct mptcp_addr_info * addr)
```

```json
{
  "name": "mptcp_pm_add_addr_echoed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_pm_add_addr_echoed",
      "external": true,
      "loc": "net/mptcp/pm.c:235",
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
      "addr": 18446744071594642116,
      "name": "mptcp_pm_add_addr_echoed.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071593709696,
      "name": "mptcp_pm_add_addr_echoed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
void mptcp_pm_add_addr_echoed(struct mptcp_sock * msk, const struct mptcp_addr_info * addr)
```

```json
{
  "name": "mptcp_pm_add_addr_echoed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_pm_add_addr_echoed",
      "external": true,
      "loc": "net/mptcp/pm.c:235",
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
      "addr": 18446744071596371439,
      "name": "mptcp_pm_add_addr_echoed.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071595644016,
      "name": "mptcp_pm_add_addr_echoed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
void mptcp_pm_add_addr_echoed(struct mptcp_sock * msk, const struct mptcp_addr_info * addr)
```

```json
{
  "name": "mptcp_pm_add_addr_echoed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_pm_add_addr_echoed",
      "external": true,
      "loc": "net/mptcp/pm.c:252",
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
      "addr": 18446744071596900686,
      "name": "mptcp_pm_add_addr_echoed.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071596152416,
      "name": "mptcp_pm_add_addr_echoed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
void mptcp_pm_add_addr_echoed(struct mptcp_sock * msk, const struct mptcp_addr_info * addr)
```

```json
{
  "name": "mptcp_pm_add_addr_echoed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_pm_add_addr_echoed",
      "external": true,
      "loc": "net/mptcp/pm.c:252",
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
      "addr": 18446744071597825892,
      "name": "mptcp_pm_add_addr_echoed.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071597026432,
      "name": "mptcp_pm_add_addr_echoed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
void mptcp_pm_add_addr_echoed(struct mptcp_sock * msk, struct mptcp_addr_info * addr)
```
</details>
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct mptcp_addr_info * addr</code> ➡️ <code>const struct mptcp_addr_info * addr</code>
</li>
</ul>
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
