# Function: <code>selinux_policy_genfs_sid</code>

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
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int selinux_policy_genfs_sid(struct selinux_policy * policy, const char * fstype, char * path, u16 orig_sclass, u32 * sid)
```

```json
{
  "name": "selinux_policy_genfs_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583996576,
      "name": "selinux_policy_genfs_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:2870",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_make_bools"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583996576,
      "name": "selinux_policy_genfs_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
int selinux_policy_genfs_sid(struct selinux_policy * policy, const char * fstype, char * path, u16 orig_sclass, u32 * sid)
```

```json
{
  "name": "selinux_policy_genfs_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584024128,
      "name": "selinux_policy_genfs_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:2938",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_make_bools"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584024128,
      "name": "selinux_policy_genfs_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
int selinux_policy_genfs_sid(struct selinux_policy * policy, const char * fstype, char * path, u16 orig_sclass, u32 * sid)
```

```json
{
  "name": "selinux_policy_genfs_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584394144,
      "name": "selinux_policy_genfs_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:2948",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_make_bools"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584394144,
      "name": "selinux_policy_genfs_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
int selinux_policy_genfs_sid(struct selinux_policy * policy, const char * fstype, const char * path, u16 orig_sclass, u32 * sid)
```

```json
{
  "name": "selinux_policy_genfs_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585020080,
      "name": "selinux_policy_genfs_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:2951",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_make_bools"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585020080,
      "name": "selinux_policy_genfs_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
int selinux_policy_genfs_sid(struct selinux_policy * policy, const char * fstype, const char * path, u16 orig_sclass, u32 * sid)
```

```json
{
  "name": "selinux_policy_genfs_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585737536,
      "name": "selinux_policy_genfs_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:2944",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_make_bools"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585737536,
      "name": "selinux_policy_genfs_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
int selinux_policy_genfs_sid(struct selinux_policy * policy, const char * fstype, const char * path, u16 orig_sclass, u32 * sid)
```

```json
{
  "name": "selinux_policy_genfs_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585968288,
      "name": "selinux_policy_genfs_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:2892",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_make_bools"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585968288,
      "name": "selinux_policy_genfs_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
int selinux_policy_genfs_sid(struct selinux_policy * policy, const char * fstype, const char * path, u16 orig_sclass, u32 * sid)
```

```json
{
  "name": "selinux_policy_genfs_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586217184,
      "name": "selinux_policy_genfs_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:2901",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586217184,
      "name": "selinux_policy_genfs_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int selinux_policy_genfs_sid(struct selinux_policy * policy, const char * fstype, char * path, u16 orig_sclass, u32 * sid)
```
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>char * path</code> ➡️ <code>const char * path</code>
</li>
</ul>
</details>
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
