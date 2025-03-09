# Function: <code>selinux_sctp_process_new_assoc</code>

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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int selinux_sctp_process_new_assoc(struct sctp_association * asoc, struct sk_buff * skb)
```

```json
{
  "name": "selinux_sctp_process_new_assoc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "selinux_sctp_process_new_assoc",
      "external": false,
      "loc": "security/selinux/hooks.c:5249",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_sctp_assoc_established",
        "security/selinux/hooks.c:selinux_sctp_assoc_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584907056,
      "name": "selinux_sctp_process_new_assoc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 394
    },
    {
      "addr": 18446744071594076479,
      "name": "selinux_sctp_process_new_assoc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
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
int selinux_sctp_process_new_assoc(struct sctp_association * asoc, struct sk_buff * skb)
```

```json
{
  "name": "selinux_sctp_process_new_assoc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "selinux_sctp_process_new_assoc",
      "external": false,
      "loc": "security/selinux/hooks.c:5264",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_sctp_assoc_established",
        "security/selinux/hooks.c:selinux_sctp_assoc_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585615888,
      "name": "selinux_sctp_process_new_assoc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 394
    },
    {
      "addr": 18446744071596094504,
      "name": "selinux_sctp_process_new_assoc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
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
int selinux_sctp_process_new_assoc(struct sctp_association * asoc, struct sk_buff * skb)
```

```json
{
  "name": "selinux_sctp_process_new_assoc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "selinux_sctp_process_new_assoc",
      "external": false,
      "loc": "security/selinux/hooks.c:5213",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_sctp_assoc_established",
        "security/selinux/hooks.c:selinux_sctp_assoc_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585845776,
      "name": "selinux_sctp_process_new_assoc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 383
    },
    {
      "addr": 18446744071596617777,
      "name": "selinux_sctp_process_new_assoc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
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
int selinux_sctp_process_new_assoc(struct sctp_association * asoc, struct sk_buff * skb)
```

```json
{
  "name": "selinux_sctp_process_new_assoc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586090640,
      "name": "selinux_sctp_process_new_assoc",
      "external": false,
      "loc": "security/selinux/hooks.c:5309",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_sctp_assoc_established",
        "security/selinux/hooks.c:selinux_sctp_assoc_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586090640,
      "name": "selinux_sctp_process_new_assoc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
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
int selinux_sctp_process_new_assoc(struct sctp_association * asoc, struct sk_buff * skb)
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
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
