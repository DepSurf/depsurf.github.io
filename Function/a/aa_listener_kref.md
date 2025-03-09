# Function: <code>aa_listener_kref</code>

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
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void aa_listener_kref(struct kref * kref)
```

```json
{
  "name": "aa_listener_kref",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586100718,
      "name": "aa_listener_kref",
      "external": true,
      "loc": "security/apparmor/notify.c:164",
      "file": "security/apparmor/notify.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/notify.c:aa_listener_unotif_recv",
        "security/apparmor/notify.c:aa_do_notification",
        "security/apparmor/notify.c:aa_do_notification",
        "security/apparmor/notify.c:aa_do_notification",
        "security/apparmor/notify.c:__listener_complete_user_pending",
        "security/apparmor/notify.c:free_listener",
        "security/apparmor/notify.c:free_listener"
      ],
      "caller_func": [
        "security/apparmor/apparmorfs.c:listener_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586096752,
      "name": "aa_listener_kref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void aa_listener_kref(struct kref * kref)
```

```json
{
  "name": "aa_listener_kref",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586332750,
      "name": "aa_listener_kref",
      "external": true,
      "loc": "security/apparmor/notify.c:224",
      "file": "security/apparmor/notify.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/notify.c:__listener_complete_held_user_pending",
        "security/apparmor/notify.c:aa_do_notification",
        "security/apparmor/notify.c:aa_do_notification",
        "security/apparmor/notify.c:aa_do_notification",
        "security/apparmor/notify.c:free_listener",
        "security/apparmor/notify.c:free_listener",
        "security/apparmor/notify.c:__listener_del_knotif"
      ],
      "caller_func": [
        "security/apparmor/apparmorfs.c:listener_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586333968,
      "name": "aa_listener_kref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void aa_listener_kref(struct kref * kref)
```

```json
{
  "name": "aa_listener_kref",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586599758,
      "name": "aa_listener_kref",
      "external": true,
      "loc": "security/apparmor/notify.c:226",
      "file": "security/apparmor/notify.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/notify.c:__listener_complete_held_user_pending",
        "security/apparmor/notify.c:aa_do_notification",
        "security/apparmor/notify.c:aa_do_notification",
        "security/apparmor/notify.c:aa_do_notification",
        "security/apparmor/notify.c:free_listener",
        "security/apparmor/notify.c:free_listener",
        "security/apparmor/notify.c:__listener_del_knotif"
      ],
      "caller_func": [
        "security/apparmor/apparmorfs.c:listener_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586601024,
      "name": "aa_listener_kref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
void aa_listener_kref(struct kref * kref)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
