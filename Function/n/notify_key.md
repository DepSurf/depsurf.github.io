# Function: <code>notify_key</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void notify_key(struct key * key, enum key_notification_subtype subtype, u32 aux)
```

```json
{
  "name": "notify_key",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583653822,
      "name": "notify_key",
      "external": false,
      "loc": "security/keys/internal.h:187",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/key.c:key_revoke",
        "security/keys/key.c:key_update",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:__key_instantiate_and_link"
      ],
      "caller_func": [
        "security/keys/key.c:key_create_or_update"
      ]
    },
    {
      "addr": 18446744071583662905,
      "name": "notify_key",
      "external": false,
      "loc": "security/keys/internal.h:187",
      "file": "security/keys/keyring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyring.c:keyring_clear",
        "security/keys/keyring.c:key_move",
        "security/keys/keyring.c:key_unlink",
        "security/keys/keyring.c:__key_link",
        "security/keys/keyring.c:keyring_restrict"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583675449,
      "name": "notify_key",
      "external": false,
      "loc": "security/keys/internal.h:187",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:keyctl_set_timeout",
        "security/keys/keyctl.c:keyctl_setperm_key",
        "security/keys/keyctl.c:keyctl_chown_key"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583653072,
      "name": "notify_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void notify_key(struct key * key, enum key_notification_subtype subtype, u32 aux)
```

```json
{
  "name": "notify_key",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583775262,
      "name": "notify_key",
      "external": false,
      "loc": "security/keys/internal.h:187",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/key.c:key_revoke",
        "security/keys/key.c:key_update",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:__key_instantiate_and_link"
      ],
      "caller_func": [
        "security/keys/key.c:key_create_or_update"
      ]
    },
    {
      "addr": 18446744071583784361,
      "name": "notify_key",
      "external": false,
      "loc": "security/keys/internal.h:187",
      "file": "security/keys/keyring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyring.c:keyring_clear",
        "security/keys/keyring.c:key_move",
        "security/keys/keyring.c:key_unlink",
        "security/keys/keyring.c:__key_link",
        "security/keys/keyring.c:keyring_restrict"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583796937,
      "name": "notify_key",
      "external": false,
      "loc": "security/keys/internal.h:187",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:keyctl_set_timeout",
        "security/keys/keyctl.c:keyctl_setperm_key",
        "security/keys/keyctl.c:keyctl_chown_key"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583774512,
      "name": "notify_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void notify_key(struct key * key, enum key_notification_subtype subtype, u32 aux)
```

```json
{
  "name": "notify_key",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583799374,
      "name": "notify_key",
      "external": false,
      "loc": "security/keys/internal.h:187",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/key.c:key_revoke",
        "security/keys/key.c:key_update",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:__key_instantiate_and_link"
      ],
      "caller_func": [
        "security/keys/key.c:key_create_or_update"
      ]
    },
    {
      "addr": 18446744071583808553,
      "name": "notify_key",
      "external": false,
      "loc": "security/keys/internal.h:187",
      "file": "security/keys/keyring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyring.c:keyring_clear",
        "security/keys/keyring.c:key_move",
        "security/keys/keyring.c:key_unlink",
        "security/keys/keyring.c:__key_link",
        "security/keys/keyring.c:keyring_restrict"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583821081,
      "name": "notify_key",
      "external": false,
      "loc": "security/keys/internal.h:187",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:keyctl_set_timeout",
        "security/keys/keyctl.c:keyctl_setperm_key",
        "security/keys/keyctl.c:keyctl_chown_key"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583798624,
      "name": "notify_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void notify_key(struct key * key, enum key_notification_subtype subtype, u32 aux)
```

```json
{
  "name": "notify_key",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584161918,
      "name": "notify_key",
      "external": false,
      "loc": "security/keys/internal.h:187",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/key.c:key_revoke",
        "security/keys/key.c:key_update",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:__key_instantiate_and_link"
      ],
      "caller_func": [
        "security/keys/key.c:key_create_or_update"
      ]
    },
    {
      "addr": 18446744071584171145,
      "name": "notify_key",
      "external": false,
      "loc": "security/keys/internal.h:187",
      "file": "security/keys/keyring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyring.c:keyring_clear",
        "security/keys/keyring.c:key_move",
        "security/keys/keyring.c:key_unlink",
        "security/keys/keyring.c:__key_link",
        "security/keys/keyring.c:keyring_restrict"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584184121,
      "name": "notify_key",
      "external": false,
      "loc": "security/keys/internal.h:187",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:keyctl_set_timeout",
        "security/keys/keyctl.c:keyctl_setperm_key",
        "security/keys/keyctl.c:keyctl_chown_key"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584161168,
      "name": "notify_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "notify_key",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584761084,
      "name": "notify_key",
      "external": false,
      "loc": "security/keys/internal.h:187",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/key.c:key_revoke",
        "security/keys/key.c:key_update",
        "security/keys/key.c:key_create_or_update",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:__key_instantiate_and_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584770747,
      "name": "notify_key",
      "external": false,
      "loc": "security/keys/internal.h:187",
      "file": "security/keys/keyring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyring.c:keyring_clear",
        "security/keys/keyring.c:key_move",
        "security/keys/keyring.c:key_unlink",
        "security/keys/keyring.c:__key_link",
        "security/keys/keyring.c:keyring_restrict"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584784754,
      "name": "notify_key",
      "external": false,
      "loc": "security/keys/internal.h:187",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:keyctl_set_timeout",
        "security/keys/keyctl.c:keyctl_setperm_key",
        "security/keys/keyctl.c:keyctl_chown_key"
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
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "notify_key",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585457559,
      "name": "notify_key",
      "external": false,
      "loc": "security/keys/internal.h:185",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/key.c:key_invalidate",
        "security/keys/key.c:key_revoke",
        "security/keys/key.c:key_update",
        "security/keys/key.c:key_create_or_update",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:__key_instantiate_and_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585466955,
      "name": "notify_key",
      "external": false,
      "loc": "security/keys/internal.h:185",
      "file": "security/keys/keyring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyring.c:keyring_clear",
        "security/keys/keyring.c:key_move",
        "security/keys/keyring.c:key_unlink",
        "security/keys/keyring.c:__key_link",
        "security/keys/keyring.c:keyring_restrict"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585481794,
      "name": "notify_key",
      "external": false,
      "loc": "security/keys/internal.h:185",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:keyctl_set_timeout",
        "security/keys/keyctl.c:keyctl_setperm_key",
        "security/keys/keyctl.c:keyctl_chown_key"
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
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void notify_key(struct key * key, enum key_notification_subtype subtype, u32 aux)
```

```json
{
  "name": "notify_key",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585689079,
      "name": "notify_key",
      "external": false,
      "loc": "security/keys/internal.h:185",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/key.c:key_invalidate",
        "security/keys/key.c:key_revoke",
        "security/keys/key.c:key_update",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:__key_instantiate_and_link"
      ],
      "caller_func": [
        "security/keys/key.c:__key_create_or_update"
      ]
    },
    {
      "addr": 18446744071585698603,
      "name": "notify_key",
      "external": false,
      "loc": "security/keys/internal.h:185",
      "file": "security/keys/keyring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyring.c:keyring_clear",
        "security/keys/keyring.c:key_move",
        "security/keys/keyring.c:key_unlink",
        "security/keys/keyring.c:__key_link",
        "security/keys/keyring.c:keyring_restrict"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585713282,
      "name": "notify_key",
      "external": false,
      "loc": "security/keys/internal.h:185",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:keyctl_set_timeout",
        "security/keys/keyctl.c:keyctl_setperm_key",
        "security/keys/keyctl.c:keyctl_chown_key"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585687248,
      "name": "notify_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void notify_key(struct key * key, enum key_notification_subtype subtype, u32 aux)
```

```json
{
  "name": "notify_key",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585936135,
      "name": "notify_key",
      "external": false,
      "loc": "security/keys/internal.h:179",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/key.c:key_invalidate",
        "security/keys/key.c:key_revoke",
        "security/keys/key.c:key_update",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:__key_instantiate_and_link"
      ],
      "caller_func": [
        "security/keys/key.c:__key_create_or_update"
      ]
    },
    {
      "addr": 18446744071585945611,
      "name": "notify_key",
      "external": false,
      "loc": "security/keys/internal.h:179",
      "file": "security/keys/keyring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyring.c:keyring_clear",
        "security/keys/keyring.c:key_move",
        "security/keys/keyring.c:key_unlink",
        "security/keys/keyring.c:__key_link",
        "security/keys/keyring.c:keyring_restrict"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585960306,
      "name": "notify_key",
      "external": false,
      "loc": "security/keys/internal.h:179",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:keyctl_set_timeout",
        "security/keys/keyctl.c:keyctl_setperm_key",
        "security/keys/keyctl.c:keyctl_chown_key"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585934144,
      "name": "notify_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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
void notify_key(struct key * key, enum key_notification_subtype subtype, u32 aux)
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
void notify_key(struct key * key, enum key_notification_subtype subtype, u32 aux)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
void notify_key(struct key * key, enum key_notification_subtype subtype, u32 aux)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
