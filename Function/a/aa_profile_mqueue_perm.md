# Function: <code>aa_profile_mqueue_perm</code>

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
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int aa_profile_mqueue_perm(struct aa_profile * profile, const struct path * path, u32 request, char * buffer, struct common_audit_data * sa)
```

```json
{
  "name": "aa_profile_mqueue_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "aa_profile_mqueue_perm",
      "external": true,
      "loc": "security/apparmor/ipc.c:137",
      "file": "security/apparmor/ipc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/ipc.c:aa_mqueue_perm",
        "security/apparmor/file.c:__file_mqueue_perm",
        "security/apparmor/file.c:__file_mqueue_perm",
        "security/apparmor/file.c:__file_mqueue_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594086563,
      "name": "aa_profile_mqueue_perm.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071585206080,
      "name": "aa_profile_mqueue_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 409
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
int aa_profile_mqueue_perm(struct aa_profile * profile, const struct path * path, u32 request, char * buffer, struct apparmor_audit_data * ad)
```

```json
{
  "name": "aa_profile_mqueue_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585937824,
      "name": "aa_profile_mqueue_perm",
      "external": true,
      "loc": "security/apparmor/ipc.c:145",
      "file": "security/apparmor/ipc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/ipc.c:aa_mqueue_perm",
        "security/apparmor/file.c:__file_mqueue_perm",
        "security/apparmor/file.c:__file_mqueue_perm",
        "security/apparmor/file.c:__file_mqueue_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585937824,
      "name": "aa_profile_mqueue_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 406
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
int aa_profile_mqueue_perm(struct aa_profile * profile, const struct path * path, u32 request, char * buffer, struct apparmor_audit_data * ad)
```

```json
{
  "name": "aa_profile_mqueue_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586170256,
      "name": "aa_profile_mqueue_perm",
      "external": true,
      "loc": "security/apparmor/ipc.c:145",
      "file": "security/apparmor/ipc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/ipc.c:aa_mqueue_perm",
        "security/apparmor/file.c:__file_mqueue_perm",
        "security/apparmor/file.c:__file_mqueue_perm",
        "security/apparmor/file.c:__file_mqueue_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586170256,
      "name": "aa_profile_mqueue_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 410
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
int aa_profile_mqueue_perm(struct aa_profile * profile, const struct path * path, u32 request, char * buffer, struct apparmor_audit_data * ad)
```

```json
{
  "name": "aa_profile_mqueue_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586421472,
      "name": "aa_profile_mqueue_perm",
      "external": true,
      "loc": "security/apparmor/ipc.c:144",
      "file": "security/apparmor/ipc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/ipc.c:aa_mqueue_perm",
        "security/apparmor/file.c:__file_mqueue_perm",
        "security/apparmor/file.c:__file_mqueue_perm",
        "security/apparmor/file.c:__file_mqueue_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586421472,
      "name": "aa_profile_mqueue_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 421
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
int aa_profile_mqueue_perm(struct aa_profile * profile, const struct path * path, u32 request, char * buffer, struct common_audit_data * sa)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct apparmor_audit_data * ad</code>
</li>
<li>
<b>Param removed. </b>
<code>struct common_audit_data * sa</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
