# Function: <code>audit_rule_change</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int audit_rule_change(int type, __u32 portid, int seq, void * data, size_t datasz)
```

```json
{
  "name": "audit_rule_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580043088,
      "name": "audit_rule_change",
      "external": true,
      "loc": "kernel/auditfilter.c:1092",
      "file": "kernel/auditfilter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580043088,
      "name": "audit_rule_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3053
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
int audit_rule_change(int type, __u32 portid, int seq, void * data, size_t datasz)
```

```json
{
  "name": "audit_rule_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580076112,
      "name": "audit_rule_change",
      "external": true,
      "loc": "kernel/auditfilter.c:1092",
      "file": "kernel/auditfilter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580076112,
      "name": "audit_rule_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2958
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
int audit_rule_change(int type, __u32 portid, int seq, void * data, size_t datasz)
```

```json
{
  "name": "audit_rule_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580116320,
      "name": "audit_rule_change",
      "external": true,
      "loc": "kernel/auditfilter.c:1093",
      "file": "kernel/auditfilter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580116320,
      "name": "audit_rule_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2983
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
int audit_rule_change(int type, int seq, void * data, size_t datasz)
```

```json
{
  "name": "audit_rule_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580121168,
      "name": "audit_rule_change",
      "external": true,
      "loc": "kernel/auditfilter.c:1092",
      "file": "kernel/auditfilter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580121168,
      "name": "audit_rule_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2976
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
int audit_rule_change(int type, int seq, void * data, size_t datasz)
```

```json
{
  "name": "audit_rule_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580173648,
      "name": "audit_rule_change",
      "external": true,
      "loc": "kernel/auditfilter.c:1117",
      "file": "kernel/auditfilter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580173648,
      "name": "audit_rule_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2980
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
int audit_rule_change(int type, int seq, void * data, size_t datasz)
```

```json
{
  "name": "audit_rule_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "audit_rule_change",
      "external": true,
      "loc": "kernel/auditfilter.c:1114",
      "file": "kernel/auditfilter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580238895,
      "name": "audit_rule_change.cold.19",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071580233456,
      "name": "audit_rule_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2950
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int audit_rule_change(int type, int seq, void * data, size_t datasz)
```

```json
{
  "name": "audit_rule_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "audit_rule_change",
      "external": true,
      "loc": "kernel/auditfilter.c:1112",
      "file": "kernel/auditfilter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580291663,
      "name": "audit_rule_change.cold.19",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071580285856,
      "name": "audit_rule_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3184
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int audit_rule_change(int type, int seq, void * data, size_t datasz)
```

```json
{
  "name": "audit_rule_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "audit_rule_change",
      "external": true,
      "loc": "kernel/auditfilter.c:1116",
      "file": "kernel/auditfilter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580342593,
      "name": "audit_rule_change.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071580338864,
      "name": "audit_rule_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 985
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
int audit_rule_change(int type, int seq, void * data, size_t datasz)
```

```json
{
  "name": "audit_rule_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580387632,
      "name": "audit_rule_change",
      "external": true,
      "loc": "kernel/auditfilter.c:1123",
      "file": "kernel/auditfilter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580387632,
      "name": "audit_rule_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1015
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
int audit_rule_change(int type, int seq, void * data, size_t datasz)
```

```json
{
  "name": "audit_rule_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580466624,
      "name": "audit_rule_change",
      "external": true,
      "loc": "kernel/auditfilter.c:1124",
      "file": "kernel/auditfilter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580466624,
      "name": "audit_rule_change",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int audit_rule_change(int type, int seq, void * data, size_t datasz)
```

```json
{
  "name": "audit_rule_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580454864,
      "name": "audit_rule_change",
      "external": true,
      "loc": "kernel/auditfilter.c:1124",
      "file": "kernel/auditfilter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580454864,
      "name": "audit_rule_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 436
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
int audit_rule_change(int type, int seq, void * data, size_t datasz)
```

```json
{
  "name": "audit_rule_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580458384,
      "name": "audit_rule_change",
      "external": true,
      "loc": "kernel/auditfilter.c:1124",
      "file": "kernel/auditfilter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580458384,
      "name": "audit_rule_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 433
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
int audit_rule_change(int type, int seq, void * data, size_t datasz)
```

```json
{
  "name": "audit_rule_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580624848,
      "name": "audit_rule_change",
      "external": true,
      "loc": "kernel/auditfilter.c:1124",
      "file": "kernel/auditfilter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580624848,
      "name": "audit_rule_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 433
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
int audit_rule_change(int type, int seq, void * data, size_t datasz)
```

```json
{
  "name": "audit_rule_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580830496,
      "name": "audit_rule_change",
      "external": true,
      "loc": "kernel/auditfilter.c:1132",
      "file": "kernel/auditfilter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580830496,
      "name": "audit_rule_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 460
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
int audit_rule_change(int type, int seq, void * data, size_t datasz)
```

```json
{
  "name": "audit_rule_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581117232,
      "name": "audit_rule_change",
      "external": true,
      "loc": "kernel/auditfilter.c:1132",
      "file": "kernel/auditfilter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581117232,
      "name": "audit_rule_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 460
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
int audit_rule_change(int type, int seq, void * data, size_t datasz)
```

```json
{
  "name": "audit_rule_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581208848,
      "name": "audit_rule_change",
      "external": true,
      "loc": "kernel/auditfilter.c:1132",
      "file": "kernel/auditfilter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581208848,
      "name": "audit_rule_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 484
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
int audit_rule_change(int type, int seq, void * data, size_t datasz)
```

```json
{
  "name": "audit_rule_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581314832,
      "name": "audit_rule_change",
      "external": true,
      "loc": "kernel/auditfilter.c:1133",
      "file": "kernel/auditfilter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581314832,
      "name": "audit_rule_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 487
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
int audit_rule_change(int type, int seq, void * data, size_t datasz)
```

```json
{
  "name": "audit_rule_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491653776,
      "name": "audit_rule_change",
      "external": true,
      "loc": "kernel/auditfilter.c:1123",
      "file": "kernel/auditfilter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491653776,
      "name": "audit_rule_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 980
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
int audit_rule_change(int type, int seq, void * data, size_t datasz)
```

```json
{
  "name": "audit_rule_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225607008,
      "name": "audit_rule_change",
      "external": true,
      "loc": "kernel/auditfilter.c:1123",
      "file": "kernel/auditfilter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225607008,
      "name": "audit_rule_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1064
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
int audit_rule_change(int type, int seq, void * data, size_t datasz)
```

```json
{
  "name": "audit_rule_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284655152,
      "name": "audit_rule_change",
      "external": true,
      "loc": "kernel/auditfilter.c:1123",
      "file": "kernel/auditfilter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284655152,
      "name": "audit_rule_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1248
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
int audit_rule_change(int type, int seq, void * data, size_t datasz)
```

```json
{
  "name": "audit_rule_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272047994,
      "name": "audit_rule_change",
      "external": true,
      "loc": "kernel/auditfilter.c:1123",
      "file": "kernel/auditfilter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272047994,
      "name": "audit_rule_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 850
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
int audit_rule_change(int type, int seq, void * data, size_t datasz)
```

```json
{
  "name": "audit_rule_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580356432,
      "name": "audit_rule_change",
      "external": true,
      "loc": "kernel/auditfilter.c:1123",
      "file": "kernel/auditfilter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580356432,
      "name": "audit_rule_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1015
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
int audit_rule_change(int type, int seq, void * data, size_t datasz)
```

```json
{
  "name": "audit_rule_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580303600,
      "name": "audit_rule_change",
      "external": true,
      "loc": "kernel/auditfilter.c:1123",
      "file": "kernel/auditfilter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580303600,
      "name": "audit_rule_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1015
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
int audit_rule_change(int type, int seq, void * data, size_t datasz)
```

```json
{
  "name": "audit_rule_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580347680,
      "name": "audit_rule_change",
      "external": true,
      "loc": "kernel/auditfilter.c:1123",
      "file": "kernel/auditfilter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580347680,
      "name": "audit_rule_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1015
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
int audit_rule_change(int type, int seq, void * data, size_t datasz)
```

```json
{
  "name": "audit_rule_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580402960,
      "name": "audit_rule_change",
      "external": true,
      "loc": "kernel/auditfilter.c:1123",
      "file": "kernel/auditfilter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580402960,
      "name": "audit_rule_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1015
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
<code>type, portid, seq, data, datasz</code> ➡️ <code>type, seq, data, datasz</code>
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
