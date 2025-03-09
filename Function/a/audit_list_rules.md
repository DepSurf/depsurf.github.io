# Function: <code>audit_list_rules</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "audit_list_rules",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580046276,
      "name": "audit_list_rules",
      "external": false,
      "loc": "kernel/auditfilter.c:1034",
      "file": "kernel/auditfilter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/auditfilter.c:audit_list_rules_send"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void audit_list_rules(__u32 portid, int seq, struct sk_buff_head * q)
```

```json
{
  "name": "audit_list_rules",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580073888,
      "name": "audit_list_rules",
      "external": false,
      "loc": "kernel/auditfilter.c:1034",
      "file": "kernel/auditfilter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditfilter.c:audit_list_rules_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580073888,
      "name": "audit_list_rules",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 704
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void audit_list_rules(__u32 portid, int seq, struct sk_buff_head * q)
```

```json
{
  "name": "audit_list_rules",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580114096,
      "name": "audit_list_rules",
      "external": false,
      "loc": "kernel/auditfilter.c:1036",
      "file": "kernel/auditfilter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditfilter.c:audit_list_rules_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580114096,
      "name": "audit_list_rules",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 704
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "audit_list_rules",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580124271,
      "name": "audit_list_rules",
      "external": false,
      "loc": "kernel/auditfilter.c:1036",
      "file": "kernel/auditfilter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/auditfilter.c:audit_list_rules_send"
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
  "name": "audit_list_rules",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580176767,
      "name": "audit_list_rules",
      "external": false,
      "loc": "kernel/auditfilter.c:1061",
      "file": "kernel/auditfilter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/auditfilter.c:audit_list_rules_send"
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
  "name": "audit_list_rules",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580236550,
      "name": "audit_list_rules",
      "external": false,
      "loc": "kernel/auditfilter.c:1060",
      "file": "kernel/auditfilter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/auditfilter.c:audit_list_rules_send"
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
  "name": "audit_list_rules",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580289174,
      "name": "audit_list_rules",
      "external": false,
      "loc": "kernel/auditfilter.c:1058",
      "file": "kernel/auditfilter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/auditfilter.c:audit_list_rules_send"
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
  "name": "audit_list_rules",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580339984,
      "name": "audit_list_rules",
      "external": false,
      "loc": "kernel/auditfilter.c:1062",
      "file": "kernel/auditfilter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/auditfilter.c:audit_list_rules_send"
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
  "name": "audit_list_rules",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580388784,
      "name": "audit_list_rules",
      "external": false,
      "loc": "kernel/auditfilter.c:1069",
      "file": "kernel/auditfilter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/auditfilter.c:audit_list_rules_send"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void audit_list_rules(int seq, struct sk_buff_head * q)
```

```json
{
  "name": "audit_list_rules",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580462848,
      "name": "audit_list_rules",
      "external": false,
      "loc": "kernel/auditfilter.c:1070",
      "file": "kernel/auditfilter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditfilter.c:audit_list_rules_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580462848,
      "name": "audit_list_rules",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
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
void audit_list_rules(int seq, struct sk_buff_head * q)
```

```json
{
  "name": "audit_list_rules",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580451152,
      "name": "audit_list_rules",
      "external": false,
      "loc": "kernel/auditfilter.c:1070",
      "file": "kernel/auditfilter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditfilter.c:audit_list_rules_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580451152,
      "name": "audit_list_rules",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
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
  "name": "audit_list_rules",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580458997,
      "name": "audit_list_rules",
      "external": false,
      "loc": "kernel/auditfilter.c:1070",
      "file": "kernel/auditfilter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/auditfilter.c:audit_list_rules_send"
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
  "name": "audit_list_rules",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580625465,
      "name": "audit_list_rules",
      "external": false,
      "loc": "kernel/auditfilter.c:1070",
      "file": "kernel/auditfilter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/auditfilter.c:audit_list_rules_send"
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
  "name": "audit_list_rules",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580831129,
      "name": "audit_list_rules",
      "external": false,
      "loc": "kernel/auditfilter.c:1078",
      "file": "kernel/auditfilter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/auditfilter.c:audit_list_rules_send"
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
  "name": "audit_list_rules",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581117881,
      "name": "audit_list_rules",
      "external": false,
      "loc": "kernel/auditfilter.c:1078",
      "file": "kernel/auditfilter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/auditfilter.c:audit_list_rules_send"
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
  "name": "audit_list_rules",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581209529,
      "name": "audit_list_rules",
      "external": false,
      "loc": "kernel/auditfilter.c:1078",
      "file": "kernel/auditfilter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/auditfilter.c:audit_list_rules_send"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "audit_list_rules",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581315560,
      "name": "audit_list_rules",
      "external": false,
      "loc": "kernel/auditfilter.c:1079",
      "file": "kernel/auditfilter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/auditfilter.c:audit_list_rules_send"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "audit_list_rules",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491654908,
      "name": "audit_list_rules",
      "external": false,
      "loc": "kernel/auditfilter.c:1069",
      "file": "kernel/auditfilter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/auditfilter.c:audit_list_rules_send"
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
  "name": "audit_list_rules",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225608216,
      "name": "audit_list_rules",
      "external": false,
      "loc": "kernel/auditfilter.c:1069",
      "file": "kernel/auditfilter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/auditfilter.c:audit_list_rules_send"
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
  "name": "audit_list_rules",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055284656624,
      "name": "audit_list_rules",
      "external": false,
      "loc": "kernel/auditfilter.c:1069",
      "file": "kernel/auditfilter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/auditfilter.c:audit_list_rules_send"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void audit_list_rules(int seq, struct sk_buff_head * q)
```

```json
{
  "name": "audit_list_rules",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272044296,
      "name": "audit_list_rules",
      "external": false,
      "loc": "kernel/auditfilter.c:1069",
      "file": "kernel/auditfilter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditfilter.c:audit_list_rules_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272044296,
      "name": "audit_list_rules",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 620
    }
  ]
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
  "name": "audit_list_rules",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580357584,
      "name": "audit_list_rules",
      "external": false,
      "loc": "kernel/auditfilter.c:1069",
      "file": "kernel/auditfilter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/auditfilter.c:audit_list_rules_send"
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
  "name": "audit_list_rules",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580304752,
      "name": "audit_list_rules",
      "external": false,
      "loc": "kernel/auditfilter.c:1069",
      "file": "kernel/auditfilter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/auditfilter.c:audit_list_rules_send"
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
  "name": "audit_list_rules",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580348832,
      "name": "audit_list_rules",
      "external": false,
      "loc": "kernel/auditfilter.c:1069",
      "file": "kernel/auditfilter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/auditfilter.c:audit_list_rules_send"
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
  "name": "audit_list_rules",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580404112,
      "name": "audit_list_rules",
      "external": false,
      "loc": "kernel/auditfilter.c:1069",
      "file": "kernel/auditfilter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/auditfilter.c:audit_list_rules_send"
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void audit_list_rules(__u32 portid, int seq, struct sk_buff_head * q)
```
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
void audit_list_rules(__u32 portid, int seq, struct sk_buff_head * q)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void audit_list_rules(int seq, struct sk_buff_head * q)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void audit_list_rules(int seq, struct sk_buff_head * q)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
void audit_list_rules(int seq, struct sk_buff_head * q)
```
</details>
</li>
</ul>
