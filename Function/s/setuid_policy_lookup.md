# Function: <code>setuid_policy_lookup</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
enum sid_policy_type setuid_policy_lookup(kuid_t src, kuid_t dst)
```

```json
{
  "name": "setuid_policy_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583666624,
      "name": "setuid_policy_lookup",
      "external": false,
      "loc": "security/safesetid/lsm.c:50",
      "file": "security/safesetid/lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/safesetid/lsm.c:uid_permitted_for_cred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583666624,
      "name": "setuid_policy_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
enum sid_policy_type setuid_policy_lookup(kuid_t src, kuid_t dst)
```

```json
{
  "name": "setuid_policy_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583772912,
      "name": "setuid_policy_lookup",
      "external": false,
      "loc": "security/safesetid/lsm.c:50",
      "file": "security/safesetid/lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/safesetid/lsm.c:uid_permitted_for_cred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583772912,
      "name": "setuid_policy_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "setuid_policy_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584163132,
      "name": "setuid_policy_lookup",
      "external": false,
      "loc": "security/safesetid/lsm.c:50",
      "file": "security/safesetid/lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/safesetid/lsm.c:uid_permitted_for_cred"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
enum sid_policy_type setuid_policy_lookup(kuid_t src, kuid_t dst)
```

```json
{
  "name": "setuid_policy_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495574240,
      "name": "setuid_policy_lookup",
      "external": false,
      "loc": "security/safesetid/lsm.c:50",
      "file": "security/safesetid/lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/safesetid/lsm.c:uid_permitted_for_cred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495574240,
      "name": "setuid_policy_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
enum sid_policy_type setuid_policy_lookup(kuid_t src, kuid_t dst)
```

```json
{
  "name": "setuid_policy_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228936408,
      "name": "setuid_policy_lookup",
      "external": false,
      "loc": "security/safesetid/lsm.c:50",
      "file": "security/safesetid/lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/safesetid/lsm.c:uid_permitted_for_cred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228936408,
      "name": "setuid_policy_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
enum sid_policy_type setuid_policy_lookup(kuid_t src, kuid_t dst)
```

```json
{
  "name": "setuid_policy_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289669712,
      "name": "setuid_policy_lookup",
      "external": false,
      "loc": "security/safesetid/lsm.c:50",
      "file": "security/safesetid/lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/safesetid/lsm.c:uid_permitted_for_cred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289669712,
      "name": "setuid_policy_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
enum sid_policy_type setuid_policy_lookup(kuid_t src, kuid_t dst)
```

```json
{
  "name": "setuid_policy_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274741636,
      "name": "setuid_policy_lookup",
      "external": false,
      "loc": "security/safesetid/lsm.c:50",
      "file": "security/safesetid/lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/safesetid/lsm.c:uid_permitted_for_cred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274741636,
      "name": "setuid_policy_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
enum sid_policy_type setuid_policy_lookup(kuid_t src, kuid_t dst)
```

```json
{
  "name": "setuid_policy_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583741648,
      "name": "setuid_policy_lookup",
      "external": false,
      "loc": "security/safesetid/lsm.c:50",
      "file": "security/safesetid/lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/safesetid/lsm.c:uid_permitted_for_cred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583741648,
      "name": "setuid_policy_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
enum sid_policy_type setuid_policy_lookup(kuid_t src, kuid_t dst)
```

```json
{
  "name": "setuid_policy_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583678704,
      "name": "setuid_policy_lookup",
      "external": false,
      "loc": "security/safesetid/lsm.c:50",
      "file": "security/safesetid/lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/safesetid/lsm.c:uid_permitted_for_cred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583678704,
      "name": "setuid_policy_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
enum sid_policy_type setuid_policy_lookup(kuid_t src, kuid_t dst)
```

```json
{
  "name": "setuid_policy_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583725424,
      "name": "setuid_policy_lookup",
      "external": false,
      "loc": "security/safesetid/lsm.c:50",
      "file": "security/safesetid/lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/safesetid/lsm.c:uid_permitted_for_cred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583725424,
      "name": "setuid_policy_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
enum sid_policy_type setuid_policy_lookup(kuid_t src, kuid_t dst)
```

```json
{
  "name": "setuid_policy_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583826144,
      "name": "setuid_policy_lookup",
      "external": false,
      "loc": "security/safesetid/lsm.c:50",
      "file": "security/safesetid/lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/safesetid/lsm.c:uid_permitted_for_cred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583826144,
      "name": "setuid_policy_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
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
enum sid_policy_type setuid_policy_lookup(kuid_t src, kuid_t dst)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
enum sid_policy_type setuid_policy_lookup(kuid_t src, kuid_t dst)
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
