# Function: <code>mptcp_pm_add_addr_signal</code>

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
bool mptcp_pm_add_addr_signal(struct mptcp_sock * msk, unsigned int remaining, struct mptcp_addr_info * saddr, bool * echo, bool * port)
```

```json
{
  "name": "mptcp_pm_add_addr_signal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591193664,
      "name": "mptcp_pm_add_addr_signal",
      "external": true,
      "loc": "net/mptcp/pm.c:213",
      "file": "net/mptcp/pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/options.c:mptcp_established_options_add_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591193664,
      "name": "mptcp_pm_add_addr_signal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
bool mptcp_pm_add_addr_signal(struct mptcp_sock * msk, unsigned int remaining, struct mptcp_addr_info * saddr, bool * echo, bool * port)
```

```json
{
  "name": "mptcp_pm_add_addr_signal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591131472,
      "name": "mptcp_pm_add_addr_signal",
      "external": true,
      "loc": "net/mptcp/pm.c:252",
      "file": "net/mptcp/pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/options.c:mptcp_established_options_add_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591131472,
      "name": "mptcp_pm_add_addr_signal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
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
bool mptcp_pm_add_addr_signal(struct mptcp_sock * msk, struct sk_buff * skb, unsigned int opt_size, unsigned int remaining, struct mptcp_addr_info * addr, bool * echo, bool * port, bool * drop_other_suboptions)
```

```json
{
  "name": "mptcp_pm_add_addr_signal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_pm_add_addr_signal",
      "external": true,
      "loc": "net/mptcp/pm.c:263",
      "file": "net/mptcp/pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/options.c:mptcp_established_options_add_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592755019,
      "name": "mptcp_pm_add_addr_signal.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
    },
    {
      "addr": 18446744071591980352,
      "name": "mptcp_pm_add_addr_signal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 443
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
bool mptcp_pm_add_addr_signal(struct mptcp_sock * msk, const struct sk_buff * skb, unsigned int opt_size, unsigned int remaining, struct mptcp_addr_info * addr, bool * echo, bool * drop_other_suboptions)
```

```json
{
  "name": "mptcp_pm_add_addr_signal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_pm_add_addr_signal",
      "external": true,
      "loc": "net/mptcp/pm.c:322",
      "file": "net/mptcp/pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/options.c:mptcp_established_options_add_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594642158,
      "name": "mptcp_pm_add_addr_signal.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071593710688,
      "name": "mptcp_pm_add_addr_signal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 389
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
bool mptcp_pm_add_addr_signal(struct mptcp_sock * msk, const struct sk_buff * skb, unsigned int opt_size, unsigned int remaining, struct mptcp_addr_info * addr, bool * echo, bool * drop_other_suboptions)
```

```json
{
  "name": "mptcp_pm_add_addr_signal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_pm_add_addr_signal",
      "external": true,
      "loc": "net/mptcp/pm.c:322",
      "file": "net/mptcp/pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/options.c:mptcp_established_options_add_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596371481,
      "name": "mptcp_pm_add_addr_signal.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071595645104,
      "name": "mptcp_pm_add_addr_signal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 389
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
bool mptcp_pm_add_addr_signal(struct mptcp_sock * msk, const struct sk_buff * skb, unsigned int opt_size, unsigned int remaining, struct mptcp_addr_info * addr, bool * echo, bool * drop_other_suboptions)
```

```json
{
  "name": "mptcp_pm_add_addr_signal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_pm_add_addr_signal",
      "external": true,
      "loc": "net/mptcp/pm.c:339",
      "file": "net/mptcp/pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/options.c:mptcp_established_options_add_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596900728,
      "name": "mptcp_pm_add_addr_signal.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071596153504,
      "name": "mptcp_pm_add_addr_signal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 389
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
bool mptcp_pm_add_addr_signal(struct mptcp_sock * msk, const struct sk_buff * skb, unsigned int opt_size, unsigned int remaining, struct mptcp_addr_info * addr, bool * echo, bool * drop_other_suboptions)
```

```json
{
  "name": "mptcp_pm_add_addr_signal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_pm_add_addr_signal",
      "external": true,
      "loc": "net/mptcp/pm.c:332",
      "file": "net/mptcp/pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/options.c:mptcp_established_options_add_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597825934,
      "name": "mptcp_pm_add_addr_signal.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071597027472,
      "name": "mptcp_pm_add_addr_signal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 389
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
bool mptcp_pm_add_addr_signal(struct mptcp_sock * msk, unsigned int remaining, struct mptcp_addr_info * saddr, bool * echo, bool * port)
```
</details>
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
<code>struct sk_buff * skb</code>
</li>
<li>
<b>Param added. </b>
<code>unsigned int opt_size</code>
</li>
<li>
<b>Param added. </b>
<code>struct mptcp_addr_info * addr</code>
</li>
<li>
<b>Param added. </b>
<code>bool * drop_other_suboptions</code>
</li>
<li>
<b>Param removed. </b>
<code>struct mptcp_addr_info * saddr</code>
</li>
<li>
<b>Param reordered. </b>
<code>msk, remaining, saddr, echo, port</code> ➡️ <code>msk, skb, opt_size, remaining, addr, echo, port, drop_other_suboptions</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool * port</code>
</li>
<li>
<b>Param reordered. </b>
<code>msk, skb, opt_size, remaining, addr, echo, port, drop_other_suboptions</code> ➡️ <code>msk, skb, opt_size, remaining, addr, echo, drop_other_suboptions</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct sk_buff * skb</code> ➡️ <code>const struct sk_buff * skb</code>
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
