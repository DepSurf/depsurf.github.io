# Function: <code>mptcp_pm_add_addr_received</code>

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
void mptcp_pm_add_addr_received(struct mptcp_sock * msk, const struct mptcp_addr_info * addr)
```

```json
{
  "name": "mptcp_pm_add_addr_received",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591110480,
      "name": "mptcp_pm_add_addr_received",
      "external": true,
      "loc": "net/mptcp/pm.c:132",
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
      "addr": 18446744071591110480,
      "name": "mptcp_pm_add_addr_received",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
void mptcp_pm_add_addr_received(struct mptcp_sock * msk, const struct mptcp_addr_info * addr)
```

```json
{
  "name": "mptcp_pm_add_addr_received",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591193168,
      "name": "mptcp_pm_add_addr_received",
      "external": true,
      "loc": "net/mptcp/pm.c:171",
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
      "addr": 18446744071591193168,
      "name": "mptcp_pm_add_addr_received",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 261
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
void mptcp_pm_add_addr_received(struct mptcp_sock * msk, const struct mptcp_addr_info * addr)
```

```json
{
  "name": "mptcp_pm_add_addr_received",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591130656,
      "name": "mptcp_pm_add_addr_received",
      "external": true,
      "loc": "net/mptcp/pm.c:178",
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
      "addr": 18446744071591130656,
      "name": "mptcp_pm_add_addr_received",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
void mptcp_pm_add_addr_received(struct mptcp_sock * msk, const struct mptcp_addr_info * addr)
```

```json
{
  "name": "mptcp_pm_add_addr_received",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_pm_add_addr_received",
      "external": true,
      "loc": "net/mptcp/pm.c:180",
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
      "addr": 18446744071592754948,
      "name": "mptcp_pm_add_addr_received.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071591979376,
      "name": "mptcp_pm_add_addr_received",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 290
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
void mptcp_pm_add_addr_received(const struct sock * ssk, const struct mptcp_addr_info * addr)
```

```json
{
  "name": "mptcp_pm_add_addr_received",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_pm_add_addr_received",
      "external": true,
      "loc": "net/mptcp/pm.c:202",
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
      "addr": 18446744071594642065,
      "name": "mptcp_pm_add_addr_received.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071593709344,
      "name": "mptcp_pm_add_addr_received",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 351
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
void mptcp_pm_add_addr_received(const struct sock * ssk, const struct mptcp_addr_info * addr)
```

```json
{
  "name": "mptcp_pm_add_addr_received",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_pm_add_addr_received",
      "external": true,
      "loc": "net/mptcp/pm.c:202",
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
      "addr": 18446744071596371388,
      "name": "mptcp_pm_add_addr_received.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071595643648,
      "name": "mptcp_pm_add_addr_received",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 346
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
void mptcp_pm_add_addr_received(const struct sock * ssk, const struct mptcp_addr_info * addr)
```

```json
{
  "name": "mptcp_pm_add_addr_received",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_pm_add_addr_received",
      "external": true,
      "loc": "net/mptcp/pm.c:219",
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
      "addr": 18446744071596900635,
      "name": "mptcp_pm_add_addr_received.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071596152048,
      "name": "mptcp_pm_add_addr_received",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 346
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
void mptcp_pm_add_addr_received(const struct sock * ssk, const struct mptcp_addr_info * addr)
```

```json
{
  "name": "mptcp_pm_add_addr_received",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_pm_add_addr_received",
      "external": true,
      "loc": "net/mptcp/pm.c:219",
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
      "addr": 18446744071597825841,
      "name": "mptcp_pm_add_addr_received.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071597026064,
      "name": "mptcp_pm_add_addr_received",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 346
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
void mptcp_pm_add_addr_received(struct mptcp_sock * msk, const struct mptcp_addr_info * addr)
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct sock * ssk</code>
</li>
<li>
<b>Param removed. </b>
<code>struct mptcp_sock * msk</code>
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
