# Function: <code>auditd_reset</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void auditd_reset()
```

```json
{
  "name": "auditd_reset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580101056,
      "name": "auditd_reset",
      "external": false,
      "loc": "kernel/audit.c:451",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_net_exit",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580101056,
      "name": "auditd_reset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void auditd_reset(const struct auditd_connection * ac)
```

```json
{
  "name": "auditd_reset",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580107056,
      "name": "auditd_reset",
      "external": false,
      "loc": "kernel/audit.c:587",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580107056,
      "name": "auditd_reset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void auditd_reset(const struct auditd_connection * ac)
```

```json
{
  "name": "auditd_reset",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580159728,
      "name": "auditd_reset",
      "external": false,
      "loc": "kernel/audit.c:587",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580159728,
      "name": "auditd_reset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void auditd_reset(const struct auditd_connection * ac)
```

```json
{
  "name": "auditd_reset",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580219504,
      "name": "auditd_reset",
      "external": false,
      "loc": "kernel/audit.c:630",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580219504,
      "name": "auditd_reset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void auditd_reset(const struct auditd_connection * ac)
```

```json
{
  "name": "auditd_reset",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580271952,
      "name": "auditd_reset",
      "external": false,
      "loc": "kernel/audit.c:626",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580271952,
      "name": "auditd_reset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void auditd_reset(const struct auditd_connection * ac)
```

```json
{
  "name": "auditd_reset",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580322848,
      "name": "auditd_reset",
      "external": false,
      "loc": "kernel/audit.c:613",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580322848,
      "name": "auditd_reset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void auditd_reset(const struct auditd_connection * ac)
```

```json
{
  "name": "auditd_reset",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580371648,
      "name": "auditd_reset",
      "external": false,
      "loc": "kernel/audit.c:613",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580371648,
      "name": "auditd_reset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void auditd_reset(const struct auditd_connection * ac)
```

```json
{
  "name": "auditd_reset",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580445488,
      "name": "auditd_reset",
      "external": false,
      "loc": "kernel/audit.c:615",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580445488,
      "name": "auditd_reset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void auditd_reset(const struct auditd_connection * ac)
```

```json
{
  "name": "auditd_reset",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580434000,
      "name": "auditd_reset",
      "external": false,
      "loc": "kernel/audit.c:620",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580434000,
      "name": "auditd_reset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void auditd_reset(const struct auditd_connection * ac)
```

```json
{
  "name": "auditd_reset",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580437888,
      "name": "auditd_reset",
      "external": false,
      "loc": "kernel/audit.c:620",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580437888,
      "name": "auditd_reset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void auditd_reset(const struct auditd_connection * ac)
```

```json
{
  "name": "auditd_reset",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580602720,
      "name": "auditd_reset",
      "external": false,
      "loc": "kernel/audit.c:642",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580602720,
      "name": "auditd_reset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void auditd_reset(const struct auditd_connection * ac)
```

```json
{
  "name": "auditd_reset",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580806688,
      "name": "auditd_reset",
      "external": false,
      "loc": "kernel/audit.c:643",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580806688,
      "name": "auditd_reset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void auditd_reset(const struct auditd_connection * ac)
```

```json
{
  "name": "auditd_reset",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581092576,
      "name": "auditd_reset",
      "external": false,
      "loc": "kernel/audit.c:641",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581092576,
      "name": "auditd_reset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void auditd_reset(const struct auditd_connection * ac)
```

```json
{
  "name": "auditd_reset",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581184176,
      "name": "auditd_reset",
      "external": false,
      "loc": "kernel/audit.c:641",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581184176,
      "name": "auditd_reset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void auditd_reset(const struct auditd_connection * ac)
```

```json
{
  "name": "auditd_reset",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581290352,
      "name": "auditd_reset",
      "external": false,
      "loc": "kernel/audit.c:652",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581290352,
      "name": "auditd_reset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void auditd_reset(const struct auditd_connection * ac)
```

```json
{
  "name": "auditd_reset",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491636440,
      "name": "auditd_reset",
      "external": false,
      "loc": "kernel/audit.c:613",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491636440,
      "name": "auditd_reset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void auditd_reset(const struct auditd_connection * ac)
```

```json
{
  "name": "auditd_reset",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225589176,
      "name": "auditd_reset",
      "external": false,
      "loc": "kernel/audit.c:613",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225589176,
      "name": "auditd_reset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void auditd_reset(const struct auditd_connection * ac)
```

```json
{
  "name": "auditd_reset",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284630832,
      "name": "auditd_reset",
      "external": false,
      "loc": "kernel/audit.c:613",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284630832,
      "name": "auditd_reset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void auditd_reset(const struct auditd_connection * ac)
```

```json
{
  "name": "auditd_reset",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272032828,
      "name": "auditd_reset",
      "external": false,
      "loc": "kernel/audit.c:613",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272032828,
      "name": "auditd_reset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void auditd_reset(const struct auditd_connection * ac)
```

```json
{
  "name": "auditd_reset",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580340448,
      "name": "auditd_reset",
      "external": false,
      "loc": "kernel/audit.c:613",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580340448,
      "name": "auditd_reset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void auditd_reset(const struct auditd_connection * ac)
```

```json
{
  "name": "auditd_reset",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580287616,
      "name": "auditd_reset",
      "external": false,
      "loc": "kernel/audit.c:613",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580287616,
      "name": "auditd_reset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void auditd_reset(const struct auditd_connection * ac)
```

```json
{
  "name": "auditd_reset",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580331696,
      "name": "auditd_reset",
      "external": false,
      "loc": "kernel/audit.c:613",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580331696,
      "name": "auditd_reset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void auditd_reset(const struct auditd_connection * ac)
```

```json
{
  "name": "auditd_reset",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580387008,
      "name": "auditd_reset",
      "external": false,
      "loc": "kernel/audit.c:613",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580387008,
      "name": "auditd_reset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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
<details>
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
void auditd_reset()
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct auditd_connection * ac</code>
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
