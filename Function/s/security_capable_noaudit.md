# Function: <code>security_capable_noaudit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int security_capable_noaudit(const struct cred * cred, struct user_namespace * ns, int cap)
```

```json
{
  "name": "security_capable_noaudit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582240224,
      "name": "security_capable_noaudit",
      "external": true,
      "loc": "security/security.c:190",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:has_capability_noaudit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582240224,
      "name": "security_capable_noaudit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
int security_capable_noaudit(const struct cred * cred, struct user_namespace * ns, int cap)
```

```json
{
  "name": "security_capable_noaudit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582458896,
      "name": "security_capable_noaudit",
      "external": true,
      "loc": "security/security.c:191",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:has_capability_noaudit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582458896,
      "name": "security_capable_noaudit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
int security_capable_noaudit(const struct cred * cred, struct user_namespace * ns, int cap)
```

```json
{
  "name": "security_capable_noaudit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582551360,
      "name": "security_capable_noaudit",
      "external": true,
      "loc": "security/security.c:191",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:ptracer_capable",
        "kernel/capability.c:has_capability_noaudit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582551360,
      "name": "security_capable_noaudit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
int security_capable_noaudit(const struct cred * cred, struct user_namespace * ns, int cap)
```

```json
{
  "name": "security_capable_noaudit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582638256,
      "name": "security_capable_noaudit",
      "external": true,
      "loc": "security/security.c:762",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:ptracer_capable",
        "kernel/capability.c:has_capability_noaudit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582638256,
      "name": "security_capable_noaudit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
int security_capable_noaudit(const struct cred * cred, struct user_namespace * ns, int cap)
```

```json
{
  "name": "security_capable_noaudit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582792272,
      "name": "security_capable_noaudit",
      "external": true,
      "loc": "security/security.c:712",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:ptracer_capable",
        "kernel/capability.c:has_capability_noaudit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582792272,
      "name": "security_capable_noaudit",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int security_capable_noaudit(const struct cred * cred, struct user_namespace * ns, int cap)
```

```json
{
  "name": "security_capable_noaudit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582990608,
      "name": "security_capable_noaudit",
      "external": true,
      "loc": "security/security.c:289",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:ptracer_capable",
        "kernel/capability.c:has_capability_noaudit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582990608,
      "name": "security_capable_noaudit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
    }
  ]
}
```
</details>
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
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
int security_capable_noaudit(const struct cred * cred, struct user_namespace * ns, int cap)
```
</details>
</li>
</ul>
