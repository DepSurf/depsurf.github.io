# Function: <code>free_listener</code>

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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void free_listener(struct aa_listener * listener)
```

```json
{
  "name": "free_listener",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586093968,
      "name": "free_listener",
      "external": false,
      "loc": "security/apparmor/notify.c:108",
      "file": "security/apparmor/notify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/notify.c:aa_listener_unotif_recv",
        "security/apparmor/notify.c:aa_do_notification",
        "security/apparmor/notify.c:aa_do_notification",
        "security/apparmor/notify.c:aa_do_notification",
        "security/apparmor/notify.c:__listener_complete_user_pending",
        "security/apparmor/notify.c:free_listener",
        "security/apparmor/notify.c:free_listener"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586093968,
      "name": "free_listener",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 728
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
void free_listener(struct aa_listener * listener)
```

```json
{
  "name": "free_listener",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586331712,
      "name": "free_listener",
      "external": false,
      "loc": "security/apparmor/notify.c:166",
      "file": "security/apparmor/notify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/notify.c:__listener_complete_held_user_pending",
        "security/apparmor/notify.c:aa_do_notification",
        "security/apparmor/notify.c:aa_do_notification",
        "security/apparmor/notify.c:aa_do_notification",
        "security/apparmor/notify.c:free_listener",
        "security/apparmor/notify.c:free_listener",
        "security/apparmor/notify.c:__listener_del_knotif"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586331712,
      "name": "free_listener",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 866
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
void free_listener(struct aa_listener * listener)
```

```json
{
  "name": "free_listener",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586598720,
      "name": "free_listener",
      "external": false,
      "loc": "security/apparmor/notify.c:168",
      "file": "security/apparmor/notify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/notify.c:__listener_complete_held_user_pending",
        "security/apparmor/notify.c:aa_do_notification",
        "security/apparmor/notify.c:aa_do_notification",
        "security/apparmor/notify.c:aa_do_notification",
        "security/apparmor/notify.c:free_listener",
        "security/apparmor/notify.c:free_listener",
        "security/apparmor/notify.c:__listener_del_knotif"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586598720,
      "name": "free_listener",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 866
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
void free_listener(struct aa_listener * listener)
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
