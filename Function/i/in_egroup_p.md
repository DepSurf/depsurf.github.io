# Function: <code>in_egroup_p</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int in_egroup_p(kgid_t grp)
```

```json
{
  "name": "in_egroup_p",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579517456,
      "name": "in_egroup_p",
      "external": true,
      "loc": "kernel/groups.c:267",
      "file": "kernel/groups.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:audit_filter_rules",
        "kernel/auditsc.c:audit_filter_rules",
        "fs/quota/quota.c:SyS_quotactl",
        "fs/proc/proc_sysctl.c:test_perm",
        "security/apparmor/policy.c:aa_may_open_profiles",
        "drivers/net/tun.c:__tun_chr_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579517456,
      "name": "in_egroup_p",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int in_egroup_p(kgid_t grp)
```

```json
{
  "name": "in_egroup_p",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579531600,
      "name": "in_egroup_p",
      "external": true,
      "loc": "kernel/groups.c:267",
      "file": "kernel/groups.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:SyS_quotactl",
        "fs/proc/proc_sysctl.c:test_perm",
        "security/apparmor/policy.c:policy_view_capable",
        "drivers/net/tun.c:__tun_chr_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579531600,
      "name": "in_egroup_p",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int in_egroup_p(kgid_t grp)
```

```json
{
  "name": "in_egroup_p",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579556560,
      "name": "in_egroup_p",
      "external": true,
      "loc": "kernel/groups.c:242",
      "file": "kernel/groups.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:SyS_quotactl",
        "fs/proc/proc_sysctl.c:test_perm",
        "security/apparmor/policy.c:policy_view_capable",
        "drivers/net/tun.c:__tun_chr_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579556560,
      "name": "in_egroup_p",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
int in_egroup_p(kgid_t grp)
```

```json
{
  "name": "in_egroup_p",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579543200,
      "name": "in_egroup_p",
      "external": true,
      "loc": "kernel/groups.c:229",
      "file": "kernel/groups.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:SyS_quotactl",
        "fs/proc/proc_sysctl.c:sysctl_perm",
        "security/apparmor/policy.c:policy_view_capable",
        "drivers/net/tun.c:__tun_chr_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579543200,
      "name": "in_egroup_p",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
int in_egroup_p(kgid_t grp)
```

```json
{
  "name": "in_egroup_p",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579571040,
      "name": "in_egroup_p",
      "external": true,
      "loc": "kernel/groups.c:231",
      "file": "kernel/groups.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:SyS_quotactl",
        "fs/proc/proc_sysctl.c:sysctl_perm",
        "security/apparmor/policy.c:policy_view_capable",
        "drivers/net/tun.c:__tun_chr_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579571040,
      "name": "in_egroup_p",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
int in_egroup_p(kgid_t grp)
```

```json
{
  "name": "in_egroup_p",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579599200,
      "name": "in_egroup_p",
      "external": true,
      "loc": "kernel/groups.c:231",
      "file": "kernel/groups.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:kernel_quotactl",
        "fs/proc/proc_sysctl.c:sysctl_perm",
        "security/apparmor/policy.c:policy_view_capable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579599200,
      "name": "in_egroup_p",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
int in_egroup_p(kgid_t grp)
```

```json
{
  "name": "in_egroup_p",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579636288,
      "name": "in_egroup_p",
      "external": true,
      "loc": "kernel/groups.c:231",
      "file": "kernel/groups.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:kernel_quotactl",
        "fs/proc/proc_sysctl.c:sysctl_perm",
        "security/apparmor/policy.c:policy_view_capable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579636288,
      "name": "in_egroup_p",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
int in_egroup_p(kgid_t grp)
```

```json
{
  "name": "in_egroup_p",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579661104,
      "name": "in_egroup_p",
      "external": true,
      "loc": "kernel/groups.c:231",
      "file": "kernel/groups.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:do_quotactl",
        "fs/proc/proc_sysctl.c:sysctl_perm",
        "security/apparmor/policy.c:policy_view_capable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579661104,
      "name": "in_egroup_p",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int in_egroup_p(kgid_t grp)
```

```json
{
  "name": "in_egroup_p",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579698176,
      "name": "in_egroup_p",
      "external": true,
      "loc": "kernel/groups.c:231",
      "file": "kernel/groups.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:do_quotactl",
        "fs/proc/proc_sysctl.c:sysctl_perm",
        "security/apparmor/policy.c:policy_view_capable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579698176,
      "name": "in_egroup_p",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int in_egroup_p(kgid_t grp)
```

```json
{
  "name": "in_egroup_p",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579739616,
      "name": "in_egroup_p",
      "external": true,
      "loc": "kernel/groups.c:231",
      "file": "kernel/groups.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:do_quotactl",
        "fs/proc/proc_sysctl.c:sysctl_perm",
        "security/apparmor/policy.c:policy_view_capable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579739616,
      "name": "in_egroup_p",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
int in_egroup_p(kgid_t grp)
```

```json
{
  "name": "in_egroup_p",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579721024,
      "name": "in_egroup_p",
      "external": true,
      "loc": "kernel/groups.c:231",
      "file": "kernel/groups.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:do_quotactl",
        "fs/proc/proc_sysctl.c:sysctl_perm",
        "security/apparmor/policy.c:policy_view_capable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579721024,
      "name": "in_egroup_p",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
int in_egroup_p(kgid_t grp)
```

```json
{
  "name": "in_egroup_p",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579728384,
      "name": "in_egroup_p",
      "external": true,
      "loc": "kernel/groups.c:226",
      "file": "kernel/groups.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:do_quotactl",
        "fs/proc/proc_sysctl.c:sysctl_perm",
        "security/apparmor/policy.c:policy_view_capable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579728384,
      "name": "in_egroup_p",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
int in_egroup_p(kgid_t grp)
```

```json
{
  "name": "in_egroup_p",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579808432,
      "name": "in_egroup_p",
      "external": true,
      "loc": "kernel/groups.c:226",
      "file": "kernel/groups.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:do_quotactl",
        "fs/proc/proc_sysctl.c:sysctl_perm",
        "security/apparmor/policy.c:policy_view_capable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579808432,
      "name": "in_egroup_p",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
int in_egroup_p(kgid_t grp)
```

```json
{
  "name": "in_egroup_p",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579918768,
      "name": "in_egroup_p",
      "external": true,
      "loc": "kernel/groups.c:226",
      "file": "kernel/groups.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:do_quotactl",
        "fs/proc/proc_sysctl.c:sysctl_perm",
        "security/apparmor/policy.c:aa_policy_view_capable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579918768,
      "name": "in_egroup_p",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
int in_egroup_p(kgid_t grp)
```

```json
{
  "name": "in_egroup_p",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580073456,
      "name": "in_egroup_p",
      "external": true,
      "loc": "kernel/groups.c:239",
      "file": "kernel/groups.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:do_quotactl",
        "fs/proc/proc_sysctl.c:sysctl_perm",
        "security/apparmor/policy.c:aa_policy_view_capable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580073456,
      "name": "in_egroup_p",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
int in_egroup_p(kgid_t grp)
```

```json
{
  "name": "in_egroup_p",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580126288,
      "name": "in_egroup_p",
      "external": true,
      "loc": "kernel/groups.c:239",
      "file": "kernel/groups.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:do_quotactl",
        "fs/proc/proc_sysctl.c:sysctl_perm",
        "security/apparmor/policy.c:aa_policy_view_capable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580126288,
      "name": "in_egroup_p",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
int in_egroup_p(kgid_t grp)
```

```json
{
  "name": "in_egroup_p",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580170640,
      "name": "in_egroup_p",
      "external": true,
      "loc": "kernel/groups.c:239",
      "file": "kernel/groups.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:do_quotactl",
        "fs/proc/proc_sysctl.c:sysctl_perm",
        "security/apparmor/policy.c:aa_policy_view_capable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580170640,
      "name": "in_egroup_p",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
int in_egroup_p(kgid_t grp)
```

```json
{
  "name": "in_egroup_p",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490879672,
      "name": "in_egroup_p",
      "external": true,
      "loc": "kernel/groups.c:231",
      "file": "kernel/groups.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:do_quotactl",
        "fs/proc/proc_sysctl.c:sysctl_perm",
        "security/apparmor/policy.c:policy_view_capable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490879672,
      "name": "in_egroup_p",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
int in_egroup_p(kgid_t grp)
```

```json
{
  "name": "in_egroup_p",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224896268,
      "name": "in_egroup_p",
      "external": true,
      "loc": "kernel/groups.c:231",
      "file": "kernel/groups.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:do_quotactl",
        "fs/proc/proc_sysctl.c:sysctl_perm",
        "security/apparmor/policy.c:policy_view_capable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224896268,
      "name": "in_egroup_p",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
int in_egroup_p(kgid_t grp)
```

```json
{
  "name": "in_egroup_p",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283712448,
      "name": "in_egroup_p",
      "external": true,
      "loc": "kernel/groups.c:231",
      "file": "kernel/groups.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:do_quotactl",
        "fs/proc/proc_sysctl.c:sysctl_perm",
        "security/apparmor/policy.c:policy_view_capable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283712448,
      "name": "in_egroup_p",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
int in_egroup_p(kgid_t grp)
```

```json
{
  "name": "in_egroup_p",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271531598,
      "name": "in_egroup_p",
      "external": true,
      "loc": "kernel/groups.c:231",
      "file": "kernel/groups.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:do_quotactl",
        "fs/proc/proc_sysctl.c:sysctl_perm",
        "security/apparmor/policy.c:policy_view_capable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271531598,
      "name": "in_egroup_p",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int in_egroup_p(kgid_t grp)
```

```json
{
  "name": "in_egroup_p",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579674496,
      "name": "in_egroup_p",
      "external": true,
      "loc": "kernel/groups.c:231",
      "file": "kernel/groups.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:do_quotactl",
        "fs/proc/proc_sysctl.c:sysctl_perm",
        "security/apparmor/policy.c:policy_view_capable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579674496,
      "name": "in_egroup_p",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int in_egroup_p(kgid_t grp)
```

```json
{
  "name": "in_egroup_p",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579602832,
      "name": "in_egroup_p",
      "external": true,
      "loc": "kernel/groups.c:231",
      "file": "kernel/groups.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:do_quotactl",
        "fs/proc/proc_sysctl.c:sysctl_perm",
        "security/apparmor/policy.c:policy_view_capable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579602832,
      "name": "in_egroup_p",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int in_egroup_p(kgid_t grp)
```

```json
{
  "name": "in_egroup_p",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579671728,
      "name": "in_egroup_p",
      "external": true,
      "loc": "kernel/groups.c:231",
      "file": "kernel/groups.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:do_quotactl",
        "fs/proc/proc_sysctl.c:sysctl_perm",
        "security/apparmor/policy.c:policy_view_capable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579671728,
      "name": "in_egroup_p",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int in_egroup_p(kgid_t grp)
```

```json
{
  "name": "in_egroup_p",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579705856,
      "name": "in_egroup_p",
      "external": true,
      "loc": "kernel/groups.c:231",
      "file": "kernel/groups.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:do_quotactl",
        "fs/proc/proc_sysctl.c:sysctl_perm",
        "security/apparmor/policy.c:policy_view_capable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579705856,
      "name": "in_egroup_p",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
