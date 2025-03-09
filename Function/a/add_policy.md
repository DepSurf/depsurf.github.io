# Function: <code>add_policy</code>

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
int add_policy(struct nl_policy_dump * * statep, const struct nla_policy * policy, unsigned int maxtype)
```

```json
{
  "name": "add_policy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589844688,
      "name": "add_policy",
      "external": false,
      "loc": "net/netlink/policy.c:27",
      "file": "net/netlink/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/policy.c:netlink_policy_dump_start",
        "net/netlink/policy.c:netlink_policy_dump_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589844688,
      "name": "add_policy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
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
int add_policy(struct netlink_policy_dump_state * * statep, const struct nla_policy * policy, unsigned int maxtype)
```

```json
{
  "name": "add_policy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589882864,
      "name": "add_policy",
      "external": false,
      "loc": "net/netlink/policy.c:27",
      "file": "net/netlink/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/policy.c:netlink_policy_dump_add_policy",
        "net/netlink/policy.c:netlink_policy_dump_add_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589882864,
      "name": "add_policy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 258
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
int add_policy(struct netlink_policy_dump_state * * statep, const struct nla_policy * policy, unsigned int maxtype)
```

```json
{
  "name": "add_policy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589788880,
      "name": "add_policy",
      "external": false,
      "loc": "net/netlink/policy.c:27",
      "file": "net/netlink/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/policy.c:netlink_policy_dump_add_policy",
        "net/netlink/policy.c:netlink_policy_dump_add_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589788880,
      "name": "add_policy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
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
int add_policy(struct netlink_policy_dump_state * * statep, const struct nla_policy * policy, unsigned int maxtype)
```

```json
{
  "name": "add_policy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590548512,
      "name": "add_policy",
      "external": false,
      "loc": "net/netlink/policy.c:27",
      "file": "net/netlink/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/policy.c:netlink_policy_dump_add_policy",
        "net/netlink/policy.c:netlink_policy_dump_add_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590548512,
      "name": "add_policy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
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
int add_policy(struct netlink_policy_dump_state * * statep, const struct nla_policy * policy, unsigned int maxtype)
```

```json
{
  "name": "add_policy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592158592,
      "name": "add_policy",
      "external": false,
      "loc": "net/netlink/policy.c:27",
      "file": "net/netlink/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/policy.c:netlink_policy_dump_add_policy",
        "net/netlink/policy.c:netlink_policy_dump_add_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592158592,
      "name": "add_policy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 266
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
int add_policy(struct netlink_policy_dump_state * * statep, const struct nla_policy * policy, unsigned int maxtype)
```

```json
{
  "name": "add_policy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593985456,
      "name": "add_policy",
      "external": false,
      "loc": "net/netlink/policy.c:27",
      "file": "net/netlink/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/policy.c:netlink_policy_dump_add_policy",
        "net/netlink/policy.c:netlink_policy_dump_add_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593985456,
      "name": "add_policy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 266
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
int add_policy(struct netlink_policy_dump_state * * statep, const struct nla_policy * policy, unsigned int maxtype)
```

```json
{
  "name": "add_policy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594362560,
      "name": "add_policy",
      "external": false,
      "loc": "net/netlink/policy.c:27",
      "file": "net/netlink/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/policy.c:netlink_policy_dump_add_policy",
        "net/netlink/policy.c:netlink_policy_dump_add_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594362560,
      "name": "add_policy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
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
int add_policy(struct netlink_policy_dump_state * * statep, const struct nla_policy * policy, unsigned int maxtype)
```

```json
{
  "name": "add_policy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595163280,
      "name": "add_policy",
      "external": false,
      "loc": "net/netlink/policy.c:27",
      "file": "net/netlink/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/policy.c:netlink_policy_dump_add_policy",
        "net/netlink/policy.c:netlink_policy_dump_add_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595163280,
      "name": "add_policy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
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
int add_policy(struct nl_policy_dump * * statep, const struct nla_policy * policy, unsigned int maxtype)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct nl_policy_dump * * statep</code> ➡️ <code>struct netlink_policy_dump_state * * statep</code>
</li>
</ul>
</details>
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
