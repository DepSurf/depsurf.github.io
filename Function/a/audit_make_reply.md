# Function: <code>audit_make_reply</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct sk_buff * audit_make_reply(__u32 portid, int seq, int type, int done, int multi, const void * payload, int size)
```

```json
{
  "name": "audit_make_reply",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580032000,
      "name": "audit_make_reply",
      "external": true,
      "loc": "kernel/audit.c:561",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditfilter.c:audit_list_rules_send",
        "kernel/auditfilter.c:audit_list_rules_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580032000,
      "name": "audit_make_reply",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct sk_buff * audit_make_reply(__u32 portid, int seq, int type, int done, int multi, const void * payload, int size)
```

```json
{
  "name": "audit_make_reply",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580064576,
      "name": "audit_make_reply",
      "external": true,
      "loc": "kernel/audit.c:558",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg",
        "kernel/auditfilter.c:audit_list_rules",
        "kernel/auditfilter.c:audit_list_rules"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580064576,
      "name": "audit_make_reply",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
struct sk_buff * audit_make_reply(__u32 portid, int seq, int type, int done, int multi, const void * payload, int size)
```

```json
{
  "name": "audit_make_reply",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580104800,
      "name": "audit_make_reply",
      "external": true,
      "loc": "kernel/audit.c:697",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg",
        "kernel/auditfilter.c:audit_list_rules",
        "kernel/auditfilter.c:audit_list_rules"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580104800,
      "name": "audit_make_reply",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct sk_buff * audit_make_reply(int seq, int type, int done, int multi, const void * payload, int size)
```

```json
{
  "name": "audit_make_reply",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580110160,
      "name": "audit_make_reply",
      "external": true,
      "loc": "kernel/audit.c:875",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg",
        "kernel/auditfilter.c:audit_list_rules_send",
        "kernel/auditfilter.c:audit_list_rules_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580110160,
      "name": "audit_make_reply",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct sk_buff * audit_make_reply(int seq, int type, int done, int multi, const void * payload, int size)
```

```json
{
  "name": "audit_make_reply",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580162720,
      "name": "audit_make_reply",
      "external": true,
      "loc": "kernel/audit.c:875",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg",
        "kernel/auditfilter.c:audit_list_rules_send",
        "kernel/auditfilter.c:audit_list_rules_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580162720,
      "name": "audit_make_reply",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct sk_buff * audit_make_reply(int seq, int type, int done, int multi, const void * payload, int size)
```

```json
{
  "name": "audit_make_reply",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580222512,
      "name": "audit_make_reply",
      "external": true,
      "loc": "kernel/audit.c:918",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg",
        "kernel/auditfilter.c:audit_list_rules_send",
        "kernel/auditfilter.c:audit_list_rules_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580222512,
      "name": "audit_make_reply",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct sk_buff * audit_make_reply(int seq, int type, int done, int multi, const void * payload, int size)
```

```json
{
  "name": "audit_make_reply",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580274928,
      "name": "audit_make_reply",
      "external": true,
      "loc": "kernel/audit.c:914",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg",
        "kernel/auditfilter.c:audit_list_rules_send",
        "kernel/auditfilter.c:audit_list_rules_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580274928,
      "name": "audit_make_reply",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct sk_buff * audit_make_reply(int seq, int type, int done, int multi, const void * payload, int size)
```

```json
{
  "name": "audit_make_reply",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580325904,
      "name": "audit_make_reply",
      "external": true,
      "loc": "kernel/audit.c:901",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg",
        "kernel/auditfilter.c:audit_list_rules_send",
        "kernel/auditfilter.c:audit_list_rules_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580325904,
      "name": "audit_make_reply",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct sk_buff * audit_make_reply(int seq, int type, int done, int multi, const void * payload, int size)
```

```json
{
  "name": "audit_make_reply",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580374704,
      "name": "audit_make_reply",
      "external": true,
      "loc": "kernel/audit.c:901",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg",
        "kernel/auditfilter.c:audit_list_rules_send",
        "kernel/auditfilter.c:audit_list_rules_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580374704,
      "name": "audit_make_reply",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct sk_buff * audit_make_reply(int seq, int type, int done, int multi, const void * payload, int size)
```

```json
{
  "name": "audit_make_reply",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580450224,
      "name": "audit_make_reply",
      "external": true,
      "loc": "kernel/audit.c:903",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg",
        "kernel/auditfilter.c:audit_list_rules",
        "kernel/auditfilter.c:audit_list_rules"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580450224,
      "name": "audit_make_reply",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
struct sk_buff * audit_make_reply(int seq, int type, int done, int multi, const void * payload, int size)
```

```json
{
  "name": "audit_make_reply",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580438832,
      "name": "audit_make_reply",
      "external": true,
      "loc": "kernel/audit.c:908",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg",
        "kernel/auditfilter.c:audit_list_rules",
        "kernel/auditfilter.c:audit_list_rules"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580438832,
      "name": "audit_make_reply",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
struct sk_buff * audit_make_reply(int seq, int type, int done, int multi, const void * payload, int size)
```

```json
{
  "name": "audit_make_reply",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580442560,
      "name": "audit_make_reply",
      "external": true,
      "loc": "kernel/audit.c:908",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditfilter.c:audit_list_rules_send",
        "kernel/auditfilter.c:audit_list_rules_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580442560,
      "name": "audit_make_reply",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct sk_buff * audit_make_reply(int seq, int type, int done, int multi, const void * payload, int size)
```

```json
{
  "name": "audit_make_reply",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580607408,
      "name": "audit_make_reply",
      "external": true,
      "loc": "kernel/audit.c:930",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditfilter.c:audit_list_rules_send",
        "kernel/auditfilter.c:audit_list_rules_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580607408,
      "name": "audit_make_reply",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct sk_buff * audit_make_reply(int seq, int type, int done, int multi, const void * payload, int size)
```

```json
{
  "name": "audit_make_reply",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580811936,
      "name": "audit_make_reply",
      "external": true,
      "loc": "kernel/audit.c:931",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditfilter.c:audit_list_rules_send",
        "kernel/auditfilter.c:audit_list_rules_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580811936,
      "name": "audit_make_reply",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
struct sk_buff * audit_make_reply(int seq, int type, int done, int multi, const void * payload, int size)
```

```json
{
  "name": "audit_make_reply",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581098032,
      "name": "audit_make_reply",
      "external": true,
      "loc": "kernel/audit.c:929",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditfilter.c:audit_list_rules_send",
        "kernel/auditfilter.c:audit_list_rules_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581098032,
      "name": "audit_make_reply",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
struct sk_buff * audit_make_reply(int seq, int type, int done, int multi, const void * payload, int size)
```

```json
{
  "name": "audit_make_reply",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581189648,
      "name": "audit_make_reply",
      "external": true,
      "loc": "kernel/audit.c:929",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditfilter.c:audit_list_rules_send",
        "kernel/auditfilter.c:audit_list_rules_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581189648,
      "name": "audit_make_reply",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
struct sk_buff * audit_make_reply(int seq, int type, int done, int multi, const void * payload, int size)
```

```json
{
  "name": "audit_make_reply",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581295856,
      "name": "audit_make_reply",
      "external": true,
      "loc": "kernel/audit.c:940",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditfilter.c:audit_list_rules_send",
        "kernel/auditfilter.c:audit_list_rules_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581295856,
      "name": "audit_make_reply",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct sk_buff * audit_make_reply(int seq, int type, int done, int multi, const void * payload, int size)
```

```json
{
  "name": "audit_make_reply",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491640048,
      "name": "audit_make_reply",
      "external": true,
      "loc": "kernel/audit.c:901",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg",
        "kernel/auditfilter.c:audit_list_rules_send",
        "kernel/auditfilter.c:audit_list_rules_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491640048,
      "name": "audit_make_reply",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct sk_buff * audit_make_reply(int seq, int type, int done, int multi, const void * payload, int size)
```

```json
{
  "name": "audit_make_reply",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225592424,
      "name": "audit_make_reply",
      "external": true,
      "loc": "kernel/audit.c:901",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg",
        "kernel/auditfilter.c:audit_list_rules_send",
        "kernel/auditfilter.c:audit_list_rules_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225592424,
      "name": "audit_make_reply",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct sk_buff * audit_make_reply(int seq, int type, int done, int multi, const void * payload, int size)
```

```json
{
  "name": "audit_make_reply",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284635376,
      "name": "audit_make_reply",
      "external": true,
      "loc": "kernel/audit.c:901",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg",
        "kernel/auditfilter.c:audit_list_rules_send",
        "kernel/auditfilter.c:audit_list_rules_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284635376,
      "name": "audit_make_reply",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct sk_buff * audit_make_reply(int seq, int type, int done, int multi, const void * payload, int size)
```

```json
{
  "name": "audit_make_reply",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272035666,
      "name": "audit_make_reply",
      "external": true,
      "loc": "kernel/audit.c:901",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg",
        "kernel/auditfilter.c:audit_list_rules",
        "kernel/auditfilter.c:audit_list_rules"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272035666,
      "name": "audit_make_reply",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct sk_buff * audit_make_reply(int seq, int type, int done, int multi, const void * payload, int size)
```

```json
{
  "name": "audit_make_reply",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580343504,
      "name": "audit_make_reply",
      "external": true,
      "loc": "kernel/audit.c:901",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg",
        "kernel/auditfilter.c:audit_list_rules_send",
        "kernel/auditfilter.c:audit_list_rules_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580343504,
      "name": "audit_make_reply",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct sk_buff * audit_make_reply(int seq, int type, int done, int multi, const void * payload, int size)
```

```json
{
  "name": "audit_make_reply",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580290672,
      "name": "audit_make_reply",
      "external": true,
      "loc": "kernel/audit.c:901",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg",
        "kernel/auditfilter.c:audit_list_rules_send",
        "kernel/auditfilter.c:audit_list_rules_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580290672,
      "name": "audit_make_reply",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct sk_buff * audit_make_reply(int seq, int type, int done, int multi, const void * payload, int size)
```

```json
{
  "name": "audit_make_reply",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580334752,
      "name": "audit_make_reply",
      "external": true,
      "loc": "kernel/audit.c:901",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg",
        "kernel/auditfilter.c:audit_list_rules_send",
        "kernel/auditfilter.c:audit_list_rules_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580334752,
      "name": "audit_make_reply",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct sk_buff * audit_make_reply(int seq, int type, int done, int multi, const void * payload, int size)
```

```json
{
  "name": "audit_make_reply",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580389984,
      "name": "audit_make_reply",
      "external": true,
      "loc": "kernel/audit.c:901",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg",
        "kernel/auditfilter.c:audit_list_rules_send",
        "kernel/auditfilter.c:audit_list_rules_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580389984,
      "name": "audit_make_reply",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
    }
  ]
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>__u32 portid</code>
</li>
<li>
<b>Param reordered. </b>
<code>portid, seq, type, done, multi, payload, size</code> ➡️ <code>seq, type, done, multi, payload, size</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
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
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
