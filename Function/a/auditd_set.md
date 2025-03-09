# Function: <code>auditd_set</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "auditd_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580117660,
      "name": "auditd_set",
      "external": false,
      "loc": "kernel/audit.c:466",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_receive_msg"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "auditd_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580169271,
      "name": "auditd_set",
      "external": false,
      "loc": "kernel/audit.c:466",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_receive_msg"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "auditd_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580229418,
      "name": "auditd_set",
      "external": false,
      "loc": "kernel/audit.c:509",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_receive_msg"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "auditd_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580281833,
      "name": "auditd_set",
      "external": false,
      "loc": "kernel/audit.c:505",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_receive_msg"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "auditd_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580332160,
      "name": "auditd_set",
      "external": false,
      "loc": "kernel/audit.c:492",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_receive_msg"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "auditd_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580381003,
      "name": "auditd_set",
      "external": false,
      "loc": "kernel/audit.c:492",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_receive_msg"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "auditd_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580457159,
      "name": "auditd_set",
      "external": false,
      "loc": "kernel/audit.c:494",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_receive_msg"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int auditd_set(struct pid * pid, u32 portid, struct net * net)
```

```json
{
  "name": "auditd_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580432960,
      "name": "auditd_set",
      "external": false,
      "loc": "kernel/audit.c:499",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580432960,
      "name": "auditd_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 310
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "auditd_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580449820,
      "name": "auditd_set",
      "external": false,
      "loc": "kernel/audit.c:499",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_receive_msg"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "auditd_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580614780,
      "name": "auditd_set",
      "external": false,
      "loc": "kernel/audit.c:499",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_receive_msg"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "auditd_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580820084,
      "name": "auditd_set",
      "external": false,
      "loc": "kernel/audit.c:500",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_receive_msg"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "auditd_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581106456,
      "name": "auditd_set",
      "external": false,
      "loc": "kernel/audit.c:498",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_receive_msg"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "auditd_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581198117,
      "name": "auditd_set",
      "external": false,
      "loc": "kernel/audit.c:498",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_receive_msg"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int auditd_set(struct pid * pid, u32 portid, struct net * net, struct sk_buff * skb, bool * ack)
```

```json
{
  "name": "auditd_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "auditd_set",
      "external": false,
      "loc": "kernel/audit.c:500",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581288576,
      "name": "auditd_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 442
    },
    {
      "addr": 18446744071597419522,
      "name": "auditd_set.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "auditd_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491646660,
      "name": "auditd_set",
      "external": false,
      "loc": "kernel/audit.c:492",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_receive_msg"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "auditd_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225598764,
      "name": "auditd_set",
      "external": false,
      "loc": "kernel/audit.c:492",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_receive_msg"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "auditd_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055284643732,
      "name": "auditd_set",
      "external": false,
      "loc": "kernel/audit.c:492",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_receive_msg"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "auditd_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272041548,
      "name": "auditd_set",
      "external": false,
      "loc": "kernel/audit.c:492",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_receive_msg"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "auditd_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580349803,
      "name": "auditd_set",
      "external": false,
      "loc": "kernel/audit.c:492",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_receive_msg"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "auditd_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580296971,
      "name": "auditd_set",
      "external": false,
      "loc": "kernel/audit.c:492",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_receive_msg"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "auditd_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580341051,
      "name": "auditd_set",
      "external": false,
      "loc": "kernel/audit.c:492",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_receive_msg"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "auditd_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580396337,
      "name": "auditd_set",
      "external": false,
      "loc": "kernel/audit.c:492",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_receive_msg"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int auditd_set(struct pid * pid, u32 portid, struct net * net)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
int auditd_set(struct pid * pid, u32 portid, struct net * net)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
int auditd_set(struct pid * pid, u32 portid, struct net * net, struct sk_buff * skb, bool * ack)
```
</details>
</li>
</ul>
