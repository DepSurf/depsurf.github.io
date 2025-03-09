# Function: <code>policy_admin_capable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
bool policy_admin_capable()
```

```json
{
  "name": "policy_admin_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582517008,
      "name": "policy_admin_capable",
      "external": true,
      "loc": "security/apparmor/policy.c:620",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_may_manage_policy",
        "security/apparmor/lsm.c:param_get_mode",
        "security/apparmor/lsm.c:param_get_audit",
        "security/apparmor/lsm.c:param_set_mode",
        "security/apparmor/lsm.c:param_set_audit",
        "security/apparmor/lsm.c:param_get_aabool",
        "security/apparmor/lsm.c:param_set_aabool",
        "security/apparmor/lsm.c:param_set_aalockpolicy",
        "security/apparmor/lsm.c:param_get_aauint",
        "security/apparmor/lsm.c:param_set_aauint",
        "security/apparmor/lsm.c:apparmor_dointvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582517008,
      "name": "policy_admin_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 570
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
bool policy_admin_capable(struct aa_ns * ns)
```

```json
{
  "name": "policy_admin_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582753760,
      "name": "policy_admin_capable",
      "external": true,
      "loc": "security/apparmor/policy.c:673",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_may_manage_policy",
        "security/apparmor/lsm.c:apparmor_dointvec",
        "security/apparmor/lsm.c:param_set_mode",
        "security/apparmor/lsm.c:param_set_audit",
        "security/apparmor/lsm.c:param_set_aauint",
        "security/apparmor/lsm.c:param_set_aabool",
        "security/apparmor/lsm.c:param_set_aalockpolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582753760,
      "name": "policy_admin_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
bool policy_admin_capable(struct aa_ns * ns)
```

```json
{
  "name": "policy_admin_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582848928,
      "name": "policy_admin_capable",
      "external": true,
      "loc": "security/apparmor/policy.c:674",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_may_manage_policy",
        "security/apparmor/lsm.c:apparmor_dointvec",
        "security/apparmor/lsm.c:param_set_aauint",
        "security/apparmor/lsm.c:param_set_aabool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582848928,
      "name": "policy_admin_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
bool policy_admin_capable(struct aa_ns * ns)
```

```json
{
  "name": "policy_admin_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582926336,
      "name": "policy_admin_capable",
      "external": true,
      "loc": "security/apparmor/policy.c:659",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_may_manage_policy",
        "security/apparmor/lsm.c:apparmor_dointvec",
        "security/apparmor/lsm.c:param_set_aabool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582926336,
      "name": "policy_admin_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
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
bool policy_admin_capable(struct aa_ns * ns)
```

```json
{
  "name": "policy_admin_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583086000,
      "name": "policy_admin_capable",
      "external": true,
      "loc": "security/apparmor/policy.c:660",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_may_manage_policy",
        "security/apparmor/lsm.c:apparmor_dointvec",
        "security/apparmor/lsm.c:param_set_aabool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583086000,
      "name": "policy_admin_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
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
bool policy_admin_capable(struct aa_ns * ns)
```

```json
{
  "name": "policy_admin_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583289088,
      "name": "policy_admin_capable",
      "external": true,
      "loc": "security/apparmor/policy.c:665",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_may_manage_policy",
        "security/apparmor/lsm.c:apparmor_dointvec",
        "security/apparmor/lsm.c:param_set_mode",
        "security/apparmor/lsm.c:param_set_audit",
        "security/apparmor/lsm.c:param_set_aabool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583289088,
      "name": "policy_admin_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
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
bool policy_admin_capable(struct aa_ns * ns)
```

```json
{
  "name": "policy_admin_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583407472,
      "name": "policy_admin_capable",
      "external": true,
      "loc": "security/apparmor/policy.c:665",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_may_manage_policy",
        "security/apparmor/lsm.c:apparmor_dointvec",
        "security/apparmor/lsm.c:param_set_mode",
        "security/apparmor/lsm.c:param_set_audit",
        "security/apparmor/lsm.c:param_set_aabool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583407472,
      "name": "policy_admin_capable",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
bool policy_admin_capable(struct aa_ns * ns)
```

```json
{
  "name": "policy_admin_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583593424,
      "name": "policy_admin_capable",
      "external": true,
      "loc": "security/apparmor/policy.c:660",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_may_manage_policy",
        "security/apparmor/lsm.c:apparmor_dointvec",
        "security/apparmor/lsm.c:param_set_mode",
        "security/apparmor/lsm.c:param_set_audit",
        "security/apparmor/lsm.c:param_set_aabool",
        "security/apparmor/lsm.c:param_set_aalockpolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583593424,
      "name": "policy_admin_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
bool policy_admin_capable(struct aa_ns * ns)
```

```json
{
  "name": "policy_admin_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583699584,
      "name": "policy_admin_capable",
      "external": true,
      "loc": "security/apparmor/policy.c:660",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_may_manage_policy",
        "security/apparmor/lsm.c:apparmor_dointvec",
        "security/apparmor/lsm.c:param_set_mode",
        "security/apparmor/lsm.c:param_set_audit",
        "security/apparmor/lsm.c:param_set_aabool",
        "security/apparmor/lsm.c:param_set_aalockpolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583699584,
      "name": "policy_admin_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
bool policy_admin_capable(struct aa_ns * ns)
```

```json
{
  "name": "policy_admin_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584068640,
      "name": "policy_admin_capable",
      "external": true,
      "loc": "security/apparmor/policy.c:664",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_may_manage_policy",
        "security/apparmor/lsm.c:apparmor_dointvec",
        "security/apparmor/lsm.c:param_set_mode",
        "security/apparmor/lsm.c:param_set_audit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584068640,
      "name": "policy_admin_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
bool policy_admin_capable(struct aa_ns * ns)
```

```json
{
  "name": "policy_admin_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584187504,
      "name": "policy_admin_capable",
      "external": true,
      "loc": "security/apparmor/policy.c:664",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_may_manage_policy",
        "security/apparmor/lsm.c:apparmor_dointvec",
        "security/apparmor/lsm.c:param_set_mode",
        "security/apparmor/lsm.c:param_set_audit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584187504,
      "name": "policy_admin_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
bool policy_admin_capable(struct aa_ns * ns)
```

```json
{
  "name": "policy_admin_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584214224,
      "name": "policy_admin_capable",
      "external": true,
      "loc": "security/apparmor/policy.c:664",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_may_manage_policy",
        "security/apparmor/lsm.c:apparmor_dointvec",
        "security/apparmor/lsm.c:param_set_mode",
        "security/apparmor/lsm.c:param_set_audit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584214224,
      "name": "policy_admin_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
bool policy_admin_capable(struct aa_ns * ns)
```

```json
{
  "name": "policy_admin_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "policy_admin_capable",
      "external": true,
      "loc": "security/apparmor/policy.c:664",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_may_manage_policy",
        "security/apparmor/lsm.c:apparmor_dointvec",
        "security/apparmor/lsm.c:param_set_mode",
        "security/apparmor/lsm.c:param_set_audit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592305889,
      "name": "policy_admin_capable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
    },
    {
      "addr": 18446744071584599584,
      "name": "policy_admin_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 278
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
bool policy_admin_capable(struct aa_ns * ns)
```

```json
{
  "name": "policy_admin_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495493000,
      "name": "policy_admin_capable",
      "external": true,
      "loc": "security/apparmor/policy.c:660",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_may_manage_policy",
        "security/apparmor/lsm.c:apparmor_dointvec",
        "security/apparmor/lsm.c:param_set_mode",
        "security/apparmor/lsm.c:param_set_audit",
        "security/apparmor/lsm.c:param_set_aabool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495493000,
      "name": "policy_admin_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
bool policy_admin_capable(struct aa_ns * ns)
```

```json
{
  "name": "policy_admin_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228860524,
      "name": "policy_admin_capable",
      "external": true,
      "loc": "security/apparmor/policy.c:660",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_may_manage_policy",
        "security/apparmor/lsm.c:apparmor_dointvec",
        "security/apparmor/lsm.c:param_set_mode",
        "security/apparmor/lsm.c:param_set_audit",
        "security/apparmor/lsm.c:param_set_aabool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228860524,
      "name": "policy_admin_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
bool policy_admin_capable(struct aa_ns * ns)
```

```json
{
  "name": "policy_admin_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289557232,
      "name": "policy_admin_capable",
      "external": true,
      "loc": "security/apparmor/policy.c:660",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_may_manage_policy",
        "security/apparmor/lsm.c:apparmor_dointvec",
        "security/apparmor/lsm.c:param_set_mode",
        "security/apparmor/lsm.c:param_set_audit",
        "security/apparmor/lsm.c:param_set_aabool",
        "security/apparmor/lsm.c:param_set_aalockpolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289557232,
      "name": "policy_admin_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
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
bool policy_admin_capable(struct aa_ns * ns)
```

```json
{
  "name": "policy_admin_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274676794,
      "name": "policy_admin_capable",
      "external": true,
      "loc": "security/apparmor/policy.c:660",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_may_manage_policy",
        "security/apparmor/lsm.c:apparmor_dointvec",
        "security/apparmor/lsm.c:param_set_mode",
        "security/apparmor/lsm.c:param_set_audit",
        "security/apparmor/lsm.c:param_set_aabool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274676794,
      "name": "policy_admin_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
bool policy_admin_capable(struct aa_ns * ns)
```

```json
{
  "name": "policy_admin_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583668320,
      "name": "policy_admin_capable",
      "external": true,
      "loc": "security/apparmor/policy.c:660",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_may_manage_policy",
        "security/apparmor/lsm.c:apparmor_dointvec",
        "security/apparmor/lsm.c:param_set_mode",
        "security/apparmor/lsm.c:param_set_audit",
        "security/apparmor/lsm.c:param_set_aabool",
        "security/apparmor/lsm.c:param_set_aalockpolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583668320,
      "name": "policy_admin_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
bool policy_admin_capable(struct aa_ns * ns)
```

```json
{
  "name": "policy_admin_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583605376,
      "name": "policy_admin_capable",
      "external": true,
      "loc": "security/apparmor/policy.c:660",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_may_manage_policy",
        "security/apparmor/lsm.c:apparmor_dointvec",
        "security/apparmor/lsm.c:param_set_mode",
        "security/apparmor/lsm.c:param_set_audit",
        "security/apparmor/lsm.c:param_set_aabool",
        "security/apparmor/lsm.c:param_set_aalockpolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583605376,
      "name": "policy_admin_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
bool policy_admin_capable(struct aa_ns * ns)
```

```json
{
  "name": "policy_admin_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583652096,
      "name": "policy_admin_capable",
      "external": true,
      "loc": "security/apparmor/policy.c:660",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_may_manage_policy",
        "security/apparmor/lsm.c:apparmor_dointvec",
        "security/apparmor/lsm.c:param_set_mode",
        "security/apparmor/lsm.c:param_set_audit",
        "security/apparmor/lsm.c:param_set_aabool",
        "security/apparmor/lsm.c:param_set_aalockpolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583652096,
      "name": "policy_admin_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
bool policy_admin_capable(struct aa_ns * ns)
```

```json
{
  "name": "policy_admin_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583750544,
      "name": "policy_admin_capable",
      "external": true,
      "loc": "security/apparmor/policy.c:660",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_may_manage_policy",
        "security/apparmor/lsm.c:apparmor_dointvec",
        "security/apparmor/lsm.c:param_set_mode",
        "security/apparmor/lsm.c:param_set_audit",
        "security/apparmor/lsm.c:param_set_aabool",
        "security/apparmor/lsm.c:param_set_aalockpolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583750544,
      "name": "policy_admin_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct aa_ns * ns</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
bool policy_admin_capable(struct aa_ns * ns)
```
</details>
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
