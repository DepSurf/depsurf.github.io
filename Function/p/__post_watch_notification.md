# Function: <code>__post_watch_notification</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __post_watch_notification(struct watch_list * wlist, struct watch_notification * n, const struct cred * cred, u64 id)
```

```json
{
  "name": "__post_watch_notification",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581256608,
      "name": "__post_watch_notification",
      "external": true,
      "loc": "kernel/watch_queue.c:175",
      "file": "kernel/watch_queue.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_revoke",
        "security/keys/key.c:key_update",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:__key_instantiate_and_link",
        "security/keys/keyring.c:keyring_clear",
        "security/keys/keyring.c:key_move",
        "security/keys/keyring.c:key_unlink",
        "security/keys/keyring.c:__key_link",
        "security/keys/keyring.c:keyring_restrict",
        "security/keys/keyctl.c:keyctl_set_timeout",
        "security/keys/keyctl.c:keyctl_setperm_key",
        "security/keys/keyctl.c:keyctl_chown_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581256608,
      "name": "__post_watch_notification.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
    },
    {
      "addr": 18446744071581256864,
      "name": "__post_watch_notification",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __post_watch_notification(struct watch_list * wlist, struct watch_notification * n, const struct cred * cred, u64 id)
```

```json
{
  "name": "__post_watch_notification",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581298656,
      "name": "__post_watch_notification",
      "external": true,
      "loc": "kernel/watch_queue.c:175",
      "file": "kernel/watch_queue.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_revoke",
        "security/keys/key.c:key_update",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:__key_instantiate_and_link",
        "security/keys/keyring.c:keyring_clear",
        "security/keys/keyring.c:key_move",
        "security/keys/keyring.c:key_unlink",
        "security/keys/keyring.c:__key_link",
        "security/keys/keyring.c:keyring_restrict",
        "security/keys/keyctl.c:keyctl_set_timeout",
        "security/keys/keyctl.c:keyctl_setperm_key",
        "security/keys/keyctl.c:keyctl_chown_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581298656,
      "name": "__post_watch_notification.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
    },
    {
      "addr": 18446744071581298928,
      "name": "__post_watch_notification",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __post_watch_notification(struct watch_list * wlist, struct watch_notification * n, const struct cred * cred, u64 id)
```

```json
{
  "name": "__post_watch_notification",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581316848,
      "name": "__post_watch_notification",
      "external": true,
      "loc": "kernel/watch_queue.c:175",
      "file": "kernel/watch_queue.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_revoke",
        "security/keys/key.c:key_update",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:__key_instantiate_and_link",
        "security/keys/keyring.c:keyring_clear",
        "security/keys/keyring.c:key_move",
        "security/keys/keyring.c:key_unlink",
        "security/keys/keyring.c:__key_link",
        "security/keys/keyring.c:keyring_restrict",
        "security/keys/keyctl.c:keyctl_set_timeout",
        "security/keys/keyctl.c:keyctl_setperm_key",
        "security/keys/keyctl.c:keyctl_chown_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581316848,
      "name": "__post_watch_notification",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 273
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __post_watch_notification(struct watch_list * wlist, struct watch_notification * n, const struct cred * cred, u64 id)
```

```json
{
  "name": "__post_watch_notification",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581562112,
      "name": "__post_watch_notification",
      "external": true,
      "loc": "kernel/watch_queue.c:176",
      "file": "kernel/watch_queue.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_revoke",
        "security/keys/key.c:key_update",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:__key_instantiate_and_link",
        "security/keys/keyring.c:keyring_clear",
        "security/keys/keyring.c:key_move",
        "security/keys/keyring.c:key_unlink",
        "security/keys/keyring.c:__key_link",
        "security/keys/keyring.c:keyring_restrict",
        "security/keys/keyctl.c:keyctl_set_timeout",
        "security/keys/keyctl.c:keyctl_setperm_key",
        "security/keys/keyctl.c:keyctl_chown_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581562112,
      "name": "__post_watch_notification",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 382
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __post_watch_notification(struct watch_list * wlist, struct watch_notification * n, const struct cred * cred, u64 id)
```

```json
{
  "name": "__post_watch_notification",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581913936,
      "name": "__post_watch_notification",
      "external": true,
      "loc": "kernel/watch_queue.c:198",
      "file": "kernel/watch_queue.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_revoke",
        "security/keys/key.c:key_update",
        "security/keys/key.c:key_create_or_update",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:__key_instantiate_and_link",
        "security/keys/keyring.c:keyring_clear",
        "security/keys/keyring.c:key_move",
        "security/keys/keyring.c:key_unlink",
        "security/keys/keyring.c:__key_link",
        "security/keys/keyring.c:keyring_restrict",
        "security/keys/keyctl.c:keyctl_set_timeout",
        "security/keys/keyctl.c:keyctl_setperm_key",
        "security/keys/keyctl.c:keyctl_chown_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581913488,
      "name": "__post_watch_notification.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 435
    },
    {
      "addr": 18446744071593964168,
      "name": "__post_watch_notification.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071581913936,
      "name": "__post_watch_notification",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __post_watch_notification(struct watch_list * wlist, struct watch_notification * n, const struct cred * cred, u64 id)
```

```json
{
  "name": "__post_watch_notification",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582349040,
      "name": "__post_watch_notification",
      "external": true,
      "loc": "kernel/watch_queue.c:198",
      "file": "kernel/watch_queue.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_invalidate",
        "security/keys/key.c:key_revoke",
        "security/keys/key.c:key_update",
        "security/keys/key.c:key_create_or_update",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:__key_instantiate_and_link",
        "security/keys/keyring.c:keyring_clear",
        "security/keys/keyring.c:key_move",
        "security/keys/keyring.c:key_unlink",
        "security/keys/keyring.c:__key_link",
        "security/keys/keyring.c:keyring_restrict",
        "security/keys/keyctl.c:keyctl_set_timeout",
        "security/keys/keyctl.c:keyctl_setperm_key",
        "security/keys/keyctl.c:keyctl_chown_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582348576,
      "name": "__post_watch_notification.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 435
    },
    {
      "addr": 18446744071596023801,
      "name": "__post_watch_notification.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071582349040,
      "name": "__post_watch_notification",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __post_watch_notification(struct watch_list * wlist, struct watch_notification * n, const struct cred * cred, u64 id)
```

```json
{
  "name": "__post_watch_notification",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582551456,
      "name": "__post_watch_notification",
      "external": true,
      "loc": "kernel/watch_queue.c:194",
      "file": "kernel/watch_queue.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_invalidate",
        "security/keys/key.c:key_revoke",
        "security/keys/key.c:key_update",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:__key_instantiate_and_link",
        "security/keys/keyring.c:keyring_clear",
        "security/keys/keyring.c:key_move",
        "security/keys/keyring.c:key_unlink",
        "security/keys/keyring.c:__key_link",
        "security/keys/keyring.c:keyring_restrict",
        "security/keys/keyctl.c:keyctl_set_timeout",
        "security/keys/keyctl.c:keyctl_setperm_key",
        "security/keys/keyctl.c:keyctl_chown_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582551456,
      "name": "__post_watch_notification.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 425
    },
    {
      "addr": 18446744071582551904,
      "name": "__post_watch_notification",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __post_watch_notification(struct watch_list * wlist, struct watch_notification * n, const struct cred * cred, u64 id)
```

```json
{
  "name": "__post_watch_notification",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582722032,
      "name": "__post_watch_notification",
      "external": true,
      "loc": "kernel/watch_queue.c:194",
      "file": "kernel/watch_queue.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_invalidate",
        "security/keys/key.c:key_revoke",
        "security/keys/key.c:key_update",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:__key_instantiate_and_link",
        "security/keys/keyring.c:keyring_clear",
        "security/keys/keyring.c:key_move",
        "security/keys/keyring.c:key_unlink",
        "security/keys/keyring.c:__key_link",
        "security/keys/keyring.c:keyring_restrict",
        "security/keys/keyctl.c:keyctl_set_timeout",
        "security/keys/keyctl.c:keyctl_setperm_key",
        "security/keys/keyctl.c:keyctl_chown_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582722032,
      "name": "__post_watch_notification.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 425
    },
    {
      "addr": 18446744071582722480,
      "name": "__post_watch_notification",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void __post_watch_notification(struct watch_list * wlist, struct watch_notification * n, const struct cred * cred, u64 id)
```
</details>
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
