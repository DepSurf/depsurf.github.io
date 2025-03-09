# Function: <code>_setuid_policy_lookup</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
enum sid_policy_type _setuid_policy_lookup(struct setuid_ruleset * policy, kuid_t src, kuid_t dst)
```

```json
{
  "name": "_setuid_policy_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583666648,
      "name": "_setuid_policy_lookup",
      "external": true,
      "loc": "security/safesetid/lsm.c:30",
      "file": "security/safesetid/lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/safesetid/lsm.c:setuid_policy_lookup"
      ],
      "caller_func": [
        "security/safesetid/securityfs.c:safesetid_file_write",
        "security/safesetid/securityfs.c:safesetid_file_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583666976,
      "name": "_setuid_policy_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
enum sid_policy_type _setuid_policy_lookup(struct setuid_ruleset * policy, kuid_t src, kuid_t dst)
```

```json
{
  "name": "_setuid_policy_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583772936,
      "name": "_setuid_policy_lookup",
      "external": true,
      "loc": "security/safesetid/lsm.c:30",
      "file": "security/safesetid/lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/safesetid/lsm.c:setuid_policy_lookup"
      ],
      "caller_func": [
        "security/safesetid/securityfs.c:safesetid_file_write",
        "security/safesetid/securityfs.c:safesetid_file_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583773248,
      "name": "_setuid_policy_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
enum sid_policy_type _setuid_policy_lookup(struct setuid_ruleset * policy, kuid_t src, kuid_t dst)
```

```json
{
  "name": "_setuid_policy_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584163144,
      "name": "_setuid_policy_lookup",
      "external": true,
      "loc": "security/safesetid/lsm.c:30",
      "file": "security/safesetid/lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/safesetid/lsm.c:uid_permitted_for_cred"
      ],
      "caller_func": [
        "security/safesetid/securityfs.c:handle_policy_update",
        "security/safesetid/securityfs.c:verify_ruleset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584163552,
      "name": "_setuid_policy_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
    }
  ]
}
```
</details>
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
enum sid_policy_type _setuid_policy_lookup(struct setuid_ruleset * policy, kuid_t src, kuid_t dst)
```

```json
{
  "name": "_setuid_policy_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495574284,
      "name": "_setuid_policy_lookup",
      "external": true,
      "loc": "security/safesetid/lsm.c:30",
      "file": "security/safesetid/lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/safesetid/lsm.c:setuid_policy_lookup"
      ],
      "caller_func": [
        "security/safesetid/securityfs.c:safesetid_file_write",
        "security/safesetid/securityfs.c:safesetid_file_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495574784,
      "name": "_setuid_policy_lookup",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
enum sid_policy_type _setuid_policy_lookup(struct setuid_ruleset * policy, kuid_t src, kuid_t dst)
```

```json
{
  "name": "_setuid_policy_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228936452,
      "name": "_setuid_policy_lookup",
      "external": true,
      "loc": "security/safesetid/lsm.c:30",
      "file": "security/safesetid/lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/safesetid/lsm.c:setuid_policy_lookup"
      ],
      "caller_func": [
        "security/safesetid/securityfs.c:safesetid_file_write",
        "security/safesetid/securityfs.c:safesetid_file_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228936920,
      "name": "_setuid_policy_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
enum sid_policy_type _setuid_policy_lookup(struct setuid_ruleset * policy, kuid_t src, kuid_t dst)
```

```json
{
  "name": "_setuid_policy_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055289669760,
      "name": "_setuid_policy_lookup",
      "external": true,
      "loc": "security/safesetid/lsm.c:30",
      "file": "security/safesetid/lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/safesetid/lsm.c:setuid_policy_lookup"
      ],
      "caller_func": [
        "security/safesetid/securityfs.c:safesetid_file_write",
        "security/safesetid/securityfs.c:safesetid_file_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289670416,
      "name": "_setuid_policy_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
enum sid_policy_type _setuid_policy_lookup(struct setuid_ruleset * policy, kuid_t src, kuid_t dst)
```

```json
{
  "name": "_setuid_policy_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274741676,
      "name": "_setuid_policy_lookup",
      "external": true,
      "loc": "security/safesetid/lsm.c:30",
      "file": "security/safesetid/lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/safesetid/lsm.c:setuid_policy_lookup"
      ],
      "caller_func": [
        "security/safesetid/securityfs.c:safesetid_file_write",
        "security/safesetid/securityfs.c:safesetid_file_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274742096,
      "name": "_setuid_policy_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
enum sid_policy_type _setuid_policy_lookup(struct setuid_ruleset * policy, kuid_t src, kuid_t dst)
```

```json
{
  "name": "_setuid_policy_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583741672,
      "name": "_setuid_policy_lookup",
      "external": true,
      "loc": "security/safesetid/lsm.c:30",
      "file": "security/safesetid/lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/safesetid/lsm.c:setuid_policy_lookup"
      ],
      "caller_func": [
        "security/safesetid/securityfs.c:safesetid_file_write",
        "security/safesetid/securityfs.c:safesetid_file_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583741984,
      "name": "_setuid_policy_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
enum sid_policy_type _setuid_policy_lookup(struct setuid_ruleset * policy, kuid_t src, kuid_t dst)
```

```json
{
  "name": "_setuid_policy_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583678728,
      "name": "_setuid_policy_lookup",
      "external": true,
      "loc": "security/safesetid/lsm.c:30",
      "file": "security/safesetid/lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/safesetid/lsm.c:setuid_policy_lookup"
      ],
      "caller_func": [
        "security/safesetid/securityfs.c:safesetid_file_write",
        "security/safesetid/securityfs.c:safesetid_file_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583679040,
      "name": "_setuid_policy_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
enum sid_policy_type _setuid_policy_lookup(struct setuid_ruleset * policy, kuid_t src, kuid_t dst)
```

```json
{
  "name": "_setuid_policy_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583725448,
      "name": "_setuid_policy_lookup",
      "external": true,
      "loc": "security/safesetid/lsm.c:30",
      "file": "security/safesetid/lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/safesetid/lsm.c:setuid_policy_lookup"
      ],
      "caller_func": [
        "security/safesetid/securityfs.c:safesetid_file_write",
        "security/safesetid/securityfs.c:safesetid_file_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583725760,
      "name": "_setuid_policy_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
enum sid_policy_type _setuid_policy_lookup(struct setuid_ruleset * policy, kuid_t src, kuid_t dst)
```

```json
{
  "name": "_setuid_policy_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583826183,
      "name": "_setuid_policy_lookup",
      "external": true,
      "loc": "security/safesetid/lsm.c:30",
      "file": "security/safesetid/lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/safesetid/lsm.c:setuid_policy_lookup"
      ],
      "caller_func": [
        "security/safesetid/securityfs.c:safesetid_file_write",
        "security/safesetid/securityfs.c:safesetid_file_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583826512,
      "name": "_setuid_policy_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
enum sid_policy_type _setuid_policy_lookup(struct setuid_ruleset * policy, kuid_t src, kuid_t dst)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
enum sid_policy_type _setuid_policy_lookup(struct setuid_ruleset * policy, kuid_t src, kuid_t dst)
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
