# Function: <code>common_lsm_audit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void common_lsm_audit(struct common_audit_data * a, void (*)(struct audit_buffer *, void *) pre_audit, void (*)(struct audit_buffer *, void *) post_audit)
```

```json
{
  "name": "common_lsm_audit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582409728,
      "name": "common_lsm_audit",
      "external": true,
      "loc": "security/lsm_audit.c:412",
      "file": "security/lsm_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:slow_avc_audit",
        "security/smack/smack_access.c:smack_log",
        "security/apparmor/audit.c:aa_audit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582409728,
      "name": "common_lsm_audit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1846
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
void common_lsm_audit(struct common_audit_data * a, void (*)(struct audit_buffer *, void *) pre_audit, void (*)(struct audit_buffer *, void *) post_audit)
```

```json
{
  "name": "common_lsm_audit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582631136,
      "name": "common_lsm_audit",
      "external": true,
      "loc": "security/lsm_audit.c:412",
      "file": "security/lsm_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:slow_avc_audit",
        "security/smack/smack_access.c:smack_log",
        "security/apparmor/audit.c:aa_audit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582631136,
      "name": "common_lsm_audit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1783
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
void common_lsm_audit(struct common_audit_data * a, void (*)(struct audit_buffer *, void *) pre_audit, void (*)(struct audit_buffer *, void *) post_audit)
```

```json
{
  "name": "common_lsm_audit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582724240,
      "name": "common_lsm_audit",
      "external": true,
      "loc": "security/lsm_audit.c:425",
      "file": "security/lsm_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:slow_avc_audit",
        "security/smack/smack_access.c:smack_log",
        "security/apparmor/audit.c:aa_audit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582724240,
      "name": "common_lsm_audit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1838
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
void common_lsm_audit(struct common_audit_data * a, void (*)(struct audit_buffer *, void *) pre_audit, void (*)(struct audit_buffer *, void *) post_audit)
```

```json
{
  "name": "common_lsm_audit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582816848,
      "name": "common_lsm_audit",
      "external": true,
      "loc": "security/lsm_audit.c:441",
      "file": "security/lsm_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:slow_avc_audit",
        "security/smack/smack_access.c:smack_log",
        "security/apparmor/audit.c:aa_audit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582816848,
      "name": "common_lsm_audit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1851
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
void common_lsm_audit(struct common_audit_data * a, void (*)(struct audit_buffer *, void *) pre_audit, void (*)(struct audit_buffer *, void *) post_audit)
```

```json
{
  "name": "common_lsm_audit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582973664,
      "name": "common_lsm_audit",
      "external": true,
      "loc": "security/lsm_audit.c:441",
      "file": "security/lsm_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:slow_avc_audit",
        "security/smack/smack_access.c:smack_log",
        "security/apparmor/audit.c:aa_audit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582973664,
      "name": "common_lsm_audit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1861
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
void common_lsm_audit(struct common_audit_data * a, void (*)(struct audit_buffer *, void *) pre_audit, void (*)(struct audit_buffer *, void *) post_audit)
```

```json
{
  "name": "common_lsm_audit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583175840,
      "name": "common_lsm_audit",
      "external": true,
      "loc": "security/lsm_audit.c:441",
      "file": "security/lsm_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:slow_avc_audit",
        "security/smack/smack_access.c:smack_log",
        "security/apparmor/audit.c:aa_audit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583175840,
      "name": "common_lsm_audit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
void common_lsm_audit(struct common_audit_data * a, void (*)(struct audit_buffer *, void *) pre_audit, void (*)(struct audit_buffer *, void *) post_audit)
```

```json
{
  "name": "common_lsm_audit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583292192,
      "name": "common_lsm_audit",
      "external": true,
      "loc": "security/lsm_audit.c:443",
      "file": "security/lsm_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:slow_avc_audit",
        "security/smack/smack_access.c:smack_log",
        "security/apparmor/audit.c:aa_audit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583292192,
      "name": "common_lsm_audit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
void common_lsm_audit(struct common_audit_data * a, void (*)(struct audit_buffer *, void *) pre_audit, void (*)(struct audit_buffer *, void *) post_audit)
```

```json
{
  "name": "common_lsm_audit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583479520,
      "name": "common_lsm_audit",
      "external": true,
      "loc": "security/lsm_audit.c:440",
      "file": "security/lsm_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:slow_avc_audit",
        "security/smack/smack_access.c:smack_log",
        "security/apparmor/audit.c:aa_audit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583479520,
      "name": "common_lsm_audit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
void common_lsm_audit(struct common_audit_data * a, void (*)(struct audit_buffer *, void *) pre_audit, void (*)(struct audit_buffer *, void *) post_audit)
```

```json
{
  "name": "common_lsm_audit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583585472,
      "name": "common_lsm_audit",
      "external": true,
      "loc": "security/lsm_audit.c:440",
      "file": "security/lsm_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:slow_avc_audit",
        "security/smack/smack_access.c:smack_log",
        "security/apparmor/audit.c:aa_audit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583585472,
      "name": "common_lsm_audit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
void common_lsm_audit(struct common_audit_data * a, void (*)(struct audit_buffer *, void *) pre_audit, void (*)(struct audit_buffer *, void *) post_audit)
```

```json
{
  "name": "common_lsm_audit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583938160,
      "name": "common_lsm_audit",
      "external": true,
      "loc": "security/lsm_audit.c:445",
      "file": "security/lsm_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:slow_avc_audit",
        "security/smack/smack_access.c:smack_log",
        "security/apparmor/audit.c:aa_audit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583938160,
      "name": "common_lsm_audit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
void common_lsm_audit(struct common_audit_data * a, void (*)(struct audit_buffer *, void *) pre_audit, void (*)(struct audit_buffer *, void *) post_audit)
```

```json
{
  "name": "common_lsm_audit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584058112,
      "name": "common_lsm_audit",
      "external": true,
      "loc": "security/lsm_audit.c:448",
      "file": "security/lsm_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:slow_avc_audit",
        "security/smack/smack_access.c:smack_log",
        "security/apparmor/audit.c:aa_audit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584058112,
      "name": "common_lsm_audit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
void common_lsm_audit(struct common_audit_data * a, void (*)(struct audit_buffer *, void *) pre_audit, void (*)(struct audit_buffer *, void *) post_audit)
```

```json
{
  "name": "common_lsm_audit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584086160,
      "name": "common_lsm_audit",
      "external": true,
      "loc": "security/lsm_audit.c:449",
      "file": "security/lsm_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:slow_avc_audit",
        "security/smack/smack_access.c:smack_log",
        "security/apparmor/audit.c:aa_audit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584086160,
      "name": "common_lsm_audit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
void common_lsm_audit(struct common_audit_data * a, void (*)(struct audit_buffer *, void *) pre_audit, void (*)(struct audit_buffer *, void *) post_audit)
```

```json
{
  "name": "common_lsm_audit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584459008,
      "name": "common_lsm_audit",
      "external": true,
      "loc": "security/lsm_audit.c:448",
      "file": "security/lsm_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:slow_avc_audit",
        "security/smack/smack_access.c:smack_log",
        "security/apparmor/audit.c:aa_audit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584459008,
      "name": "common_lsm_audit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
void common_lsm_audit(struct common_audit_data * a, void (*)(struct audit_buffer *, void *) pre_audit, void (*)(struct audit_buffer *, void *) post_audit)
```

```json
{
  "name": "common_lsm_audit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585093296,
      "name": "common_lsm_audit",
      "external": true,
      "loc": "security/lsm_audit.c:451",
      "file": "security/lsm_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:slow_avc_audit",
        "security/smack/smack_access.c:smack_log",
        "security/apparmor/audit.c:aa_audit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585093296,
      "name": "common_lsm_audit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
void common_lsm_audit(struct common_audit_data * a, void (*)(struct audit_buffer *, void *) pre_audit, void (*)(struct audit_buffer *, void *) post_audit)
```

```json
{
  "name": "common_lsm_audit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585816992,
      "name": "common_lsm_audit",
      "external": true,
      "loc": "security/lsm_audit.c:440",
      "file": "security/lsm_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:slow_avc_audit",
        "security/smack/smack_access.c:smack_log",
        "security/apparmor/audit.c:aa_audit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585816992,
      "name": "common_lsm_audit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
void common_lsm_audit(struct common_audit_data * a, void (*)(struct audit_buffer *, void *) pre_audit, void (*)(struct audit_buffer *, void *) post_audit)
```

```json
{
  "name": "common_lsm_audit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586048896,
      "name": "common_lsm_audit",
      "external": true,
      "loc": "security/lsm_audit.c:440",
      "file": "security/lsm_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:slow_avc_audit",
        "security/smack/smack_access.c:smack_log",
        "security/apparmor/audit.c:aa_audit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586048896,
      "name": "common_lsm_audit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
void common_lsm_audit(struct common_audit_data * a, void (*)(struct audit_buffer *, void *) pre_audit, void (*)(struct audit_buffer *, void *) post_audit)
```

```json
{
  "name": "common_lsm_audit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586297680,
      "name": "common_lsm_audit",
      "external": true,
      "loc": "security/lsm_audit.c:440",
      "file": "security/lsm_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:slow_avc_audit",
        "security/smack/smack_access.c:smack_log",
        "security/apparmor/audit.c:aa_audit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586297680,
      "name": "common_lsm_audit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
void common_lsm_audit(struct common_audit_data * a, void (*)(struct audit_buffer *, void *) pre_audit, void (*)(struct audit_buffer *, void *) post_audit)
```

```json
{
  "name": "common_lsm_audit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495364600,
      "name": "common_lsm_audit",
      "external": true,
      "loc": "security/lsm_audit.c:440",
      "file": "security/lsm_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:slow_avc_audit",
        "security/smack/smack_access.c:smack_log",
        "security/apparmor/audit.c:aa_audit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495364600,
      "name": "common_lsm_audit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
void common_lsm_audit(struct common_audit_data * a, void (*)(struct audit_buffer *, void *) pre_audit, void (*)(struct audit_buffer *, void *) post_audit)
```

```json
{
  "name": "common_lsm_audit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228739640,
      "name": "common_lsm_audit",
      "external": true,
      "loc": "security/lsm_audit.c:440",
      "file": "security/lsm_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:slow_avc_audit",
        "security/smack/smack_access.c:smack_log",
        "security/apparmor/audit.c:aa_audit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228739640,
      "name": "common_lsm_audit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
void common_lsm_audit(struct common_audit_data * a, void (*)(struct audit_buffer *, void *) pre_audit, void (*)(struct audit_buffer *, void *) post_audit)
```

```json
{
  "name": "common_lsm_audit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289377040,
      "name": "common_lsm_audit",
      "external": true,
      "loc": "security/lsm_audit.c:440",
      "file": "security/lsm_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:slow_avc_audit",
        "security/smack/smack_access.c:smack_log",
        "security/apparmor/audit.c:aa_audit",
        "security/apparmor/audit.c:aa_audit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289377040,
      "name": "common_lsm_audit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
void common_lsm_audit(struct common_audit_data * a, void (*)(struct audit_buffer *, void *) pre_audit, void (*)(struct audit_buffer *, void *) post_audit)
```

```json
{
  "name": "common_lsm_audit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274570952,
      "name": "common_lsm_audit",
      "external": true,
      "loc": "security/lsm_audit.c:440",
      "file": "security/lsm_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:slow_avc_audit",
        "security/smack/smack_access.c:smack_log",
        "security/apparmor/audit.c:aa_audit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274570952,
      "name": "common_lsm_audit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void common_lsm_audit(struct common_audit_data * a, void (*)(struct audit_buffer *, void *) pre_audit, void (*)(struct audit_buffer *, void *) post_audit)
```

```json
{
  "name": "common_lsm_audit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583554208,
      "name": "common_lsm_audit",
      "external": true,
      "loc": "security/lsm_audit.c:440",
      "file": "security/lsm_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:slow_avc_audit",
        "security/smack/smack_access.c:smack_log",
        "security/apparmor/audit.c:aa_audit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583554208,
      "name": "common_lsm_audit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
void common_lsm_audit(struct common_audit_data * a, void (*)(struct audit_buffer *, void *) pre_audit, void (*)(struct audit_buffer *, void *) post_audit)
```

```json
{
  "name": "common_lsm_audit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583491264,
      "name": "common_lsm_audit",
      "external": true,
      "loc": "security/lsm_audit.c:440",
      "file": "security/lsm_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:slow_avc_audit",
        "security/smack/smack_access.c:smack_log",
        "security/apparmor/audit.c:aa_audit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583491264,
      "name": "common_lsm_audit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
void common_lsm_audit(struct common_audit_data * a, void (*)(struct audit_buffer *, void *) pre_audit, void (*)(struct audit_buffer *, void *) post_audit)
```

```json
{
  "name": "common_lsm_audit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583537984,
      "name": "common_lsm_audit",
      "external": true,
      "loc": "security/lsm_audit.c:440",
      "file": "security/lsm_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:slow_avc_audit",
        "security/smack/smack_access.c:smack_log",
        "security/apparmor/audit.c:aa_audit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583537984,
      "name": "common_lsm_audit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
void common_lsm_audit(struct common_audit_data * a, void (*)(struct audit_buffer *, void *) pre_audit, void (*)(struct audit_buffer *, void *) post_audit)
```

```json
{
  "name": "common_lsm_audit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583634928,
      "name": "common_lsm_audit",
      "external": true,
      "loc": "security/lsm_audit.c:440",
      "file": "security/lsm_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:slow_avc_audit",
        "security/smack/smack_access.c:smack_log",
        "security/apparmor/audit.c:aa_audit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583634928,
      "name": "common_lsm_audit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
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
