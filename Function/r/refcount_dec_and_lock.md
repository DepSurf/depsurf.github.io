# Function: <code>refcount_dec_and_lock</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool refcount_dec_and_lock(refcount_t * r, spinlock_t * lock)
```

```json
{
  "name": "refcount_dec_and_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583483184,
      "name": "refcount_dec_and_lock",
      "external": true,
      "loc": "lib/refcount.c:337",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583483184,
      "name": "refcount_dec_and_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool refcount_dec_and_lock(refcount_t * r, spinlock_t * lock)
```

```json
{
  "name": "refcount_dec_and_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583664192,
      "name": "refcount_dec_and_lock",
      "external": true,
      "loc": "lib/refcount.c:338",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/mark.c:fsnotify_put_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583664192,
      "name": "refcount_dec_and_lock",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool refcount_dec_and_lock(refcount_t * r, spinlock_t * lock)
```

```json
{
  "name": "refcount_dec_and_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583881776,
      "name": "refcount_dec_and_lock",
      "external": true,
      "loc": "lib/refcount.c:338",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/mark.c:fsnotify_put_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583881776,
      "name": "refcount_dec_and_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool refcount_dec_and_lock(refcount_t * r, spinlock_t * lock)
```

```json
{
  "name": "refcount_dec_and_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583965952,
      "name": "refcount_dec_and_lock",
      "external": true,
      "loc": "lib/refcount.c:337",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/mark.c:fsnotify_put_mark",
        "fs/crypto/keyinfo.c:put_crypt_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583965952,
      "name": "refcount_dec_and_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool refcount_dec_and_lock(refcount_t * r, spinlock_t * lock)
```

```json
{
  "name": "refcount_dec_and_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584145808,
      "name": "refcount_dec_and_lock",
      "external": true,
      "loc": "lib/refcount.c:345",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/mark.c:fsnotify_put_mark",
        "fs/crypto/keyinfo.c:put_crypt_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584145808,
      "name": "refcount_dec_and_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
bool refcount_dec_and_lock(refcount_t * r, spinlock_t * lock)
```

```json
{
  "name": "refcount_dec_and_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584268256,
      "name": "refcount_dec_and_lock",
      "external": true,
      "loc": "lib/refcount.c:345",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/mark.c:fsnotify_put_mark",
        "fs/crypto/keysetup_v1.c:fscrypt_put_direct_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584268256,
      "name": "refcount_dec_and_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
bool refcount_dec_and_lock(refcount_t * r, spinlock_t * lock)
```

```json
{
  "name": "refcount_dec_and_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584676320,
      "name": "refcount_dec_and_lock",
      "external": true,
      "loc": "lib/refcount.c:144",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/mark.c:fsnotify_put_mark",
        "fs/crypto/keysetup_v1.c:fscrypt_put_direct_key",
        "ipc/namespace.c:ipcns_install",
        "ipc/namespace.c:ipcns_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584676320,
      "name": "refcount_dec_and_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool refcount_dec_and_lock(refcount_t * r, spinlock_t * lock)
```

```json
{
  "name": "refcount_dec_and_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584793872,
      "name": "refcount_dec_and_lock",
      "external": true,
      "loc": "lib/refcount.c:144",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/mark.c:fsnotify_put_mark",
        "fs/crypto/keysetup_v1.c:fscrypt_put_direct_key",
        "ipc/namespace.c:ipcns_install",
        "ipc/namespace.c:ipcns_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584793872,
      "name": "refcount_dec_and_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
bool refcount_dec_and_lock(refcount_t * r, spinlock_t * lock)
```

```json
{
  "name": "refcount_dec_and_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584838112,
      "name": "refcount_dec_and_lock",
      "external": true,
      "loc": "lib/refcount.c:144",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/mark.c:fsnotify_put_mark",
        "fs/crypto/keysetup_v1.c:fscrypt_put_direct_key",
        "ipc/namespace.c:ipcns_install",
        "ipc/namespace.c:ipcns_put",
        "security/keys/key.c:key_alloc",
        "security/keys/key.c:key_alloc",
        "security/keys/key.c:key_alloc",
        "security/landlock/object.c:landlock_put_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584838112,
      "name": "refcount_dec_and_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool refcount_dec_and_lock(refcount_t * r, spinlock_t * lock)
```

```json
{
  "name": "refcount_dec_and_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585257531,
      "name": "refcount_dec_and_lock",
      "external": true,
      "loc": "lib/refcount.c:144",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/mark.c:fsnotify_put_mark",
        "fs/crypto/keysetup_v1.c:fscrypt_put_direct_key",
        "ipc/namespace.c:ipcns_install",
        "ipc/namespace.c:ipcns_put",
        "security/keys/key.c:key_alloc",
        "security/keys/key.c:key_alloc",
        "security/keys/key.c:key_alloc",
        "security/landlock/object.c:landlock_put_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592324618,
      "name": "refcount_dec_and_lock.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071585257488,
      "name": "refcount_dec_and_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
bool refcount_dec_and_lock(refcount_t * r, spinlock_t * lock)
```

```json
{
  "name": "refcount_dec_and_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "refcount_dec_and_lock",
      "external": true,
      "loc": "lib/refcount.c:144",
      "file": "lib/refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/mark.c:fsnotify_put_mark",
        "fs/crypto/keysetup_v1.c:fscrypt_put_direct_key",
        "security/keys/key.c:key_alloc",
        "security/keys/key.c:key_alloc",
        "security/keys/key.c:key_alloc",
        "security/landlock/object.c:landlock_put_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594129074,
      "name": "refcount_dec_and_lock.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071586099824,
      "name": "refcount_dec_and_lock",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
bool refcount_dec_and_lock(refcount_t * r, spinlock_t * lock)
```

```json
{
  "name": "refcount_dec_and_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "refcount_dec_and_lock",
      "external": true,
      "loc": "lib/refcount.c:144",
      "file": "lib/refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/mark.c:fsnotify_put_mark",
        "fs/crypto/keysetup_v1.c:fscrypt_put_direct_key",
        "security/keys/key.c:key_alloc",
        "security/keys/key.c:key_alloc",
        "security/keys/key.c:key_alloc",
        "security/landlock/object.c:landlock_put_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596116090,
      "name": "refcount_dec_and_lock.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071587084560,
      "name": "refcount_dec_and_lock",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
bool refcount_dec_and_lock(refcount_t * r, spinlock_t * lock)
```

```json
{
  "name": "refcount_dec_and_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "refcount_dec_and_lock",
      "external": true,
      "loc": "lib/refcount.c:144",
      "file": "lib/refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/mark.c:fsnotify_put_mark",
        "fs/crypto/keysetup_v1.c:fscrypt_put_direct_key",
        "security/keys/key.c:key_alloc",
        "security/keys/key.c:key_alloc",
        "security/keys/key.c:key_alloc",
        "security/landlock/object.c:landlock_put_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596641829,
      "name": "refcount_dec_and_lock.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071587343232,
      "name": "refcount_dec_and_lock",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
bool refcount_dec_and_lock(refcount_t * r, spinlock_t * lock)
```

```json
{
  "name": "refcount_dec_and_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "refcount_dec_and_lock",
      "external": true,
      "loc": "lib/refcount.c:144",
      "file": "lib/refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/mark.c:fsnotify_put_mark",
        "fs/crypto/keysetup_v1.c:fscrypt_put_direct_key",
        "security/keys/key.c:key_alloc",
        "security/keys/key.c:key_alloc",
        "security/keys/key.c:key_alloc",
        "security/landlock/object.c:landlock_put_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597549894,
      "name": "refcount_dec_and_lock.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071587626752,
      "name": "refcount_dec_and_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
bool refcount_dec_and_lock(refcount_t * r, spinlock_t * lock)
```

```json
{
  "name": "refcount_dec_and_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496151728,
      "name": "refcount_dec_and_lock",
      "external": true,
      "loc": "lib/refcount.c:345",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/mark.c:fsnotify_put_mark",
        "fs/crypto/keysetup_v1.c:fscrypt_put_direct_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496151728,
      "name": "refcount_dec_and_lock",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
bool refcount_dec_and_lock(refcount_t * r, spinlock_t * lock)
```

```json
{
  "name": "refcount_dec_and_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229472848,
      "name": "refcount_dec_and_lock",
      "external": true,
      "loc": "lib/refcount.c:345",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/mark.c:fsnotify_put_mark",
        "fs/crypto/keysetup_v1.c:fscrypt_put_direct_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229472848,
      "name": "refcount_dec_and_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
bool refcount_dec_and_lock(refcount_t * r, spinlock_t * lock)
```

```json
{
  "name": "refcount_dec_and_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290412320,
      "name": "refcount_dec_and_lock",
      "external": true,
      "loc": "lib/refcount.c:345",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/mark.c:fsnotify_put_mark",
        "fs/crypto/keysetup_v1.c:fscrypt_put_direct_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290412320,
      "name": "refcount_dec_and_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
bool refcount_dec_and_lock(refcount_t * r, spinlock_t * lock)
```

```json
{
  "name": "refcount_dec_and_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275205360,
      "name": "refcount_dec_and_lock",
      "external": true,
      "loc": "lib/refcount.c:345",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/mark.c:fsnotify_put_mark",
        "fs/crypto/keysetup_v1.c:fscrypt_put_direct_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275205360,
      "name": "refcount_dec_and_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
bool refcount_dec_and_lock(refcount_t * r, spinlock_t * lock)
```

```json
{
  "name": "refcount_dec_and_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584236992,
      "name": "refcount_dec_and_lock",
      "external": true,
      "loc": "lib/refcount.c:345",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/mark.c:fsnotify_put_mark",
        "fs/crypto/keysetup_v1.c:fscrypt_put_direct_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584236992,
      "name": "refcount_dec_and_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
bool refcount_dec_and_lock(refcount_t * r, spinlock_t * lock)
```

```json
{
  "name": "refcount_dec_and_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584172192,
      "name": "refcount_dec_and_lock",
      "external": true,
      "loc": "lib/refcount.c:345",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/mark.c:fsnotify_put_mark",
        "fs/crypto/keysetup_v1.c:fscrypt_put_direct_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584172192,
      "name": "refcount_dec_and_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
bool refcount_dec_and_lock(refcount_t * r, spinlock_t * lock)
```

```json
{
  "name": "refcount_dec_and_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584220752,
      "name": "refcount_dec_and_lock",
      "external": true,
      "loc": "lib/refcount.c:345",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/mark.c:fsnotify_put_mark",
        "fs/crypto/keysetup_v1.c:fscrypt_put_direct_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584220752,
      "name": "refcount_dec_and_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
bool refcount_dec_and_lock(refcount_t * r, spinlock_t * lock)
```

```json
{
  "name": "refcount_dec_and_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584325584,
      "name": "refcount_dec_and_lock",
      "external": true,
      "loc": "lib/refcount.c:345",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/mark.c:fsnotify_put_mark",
        "fs/crypto/keysetup_v1.c:fscrypt_put_direct_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584325584,
      "name": "refcount_dec_and_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
bool refcount_dec_and_lock(refcount_t * r, spinlock_t * lock)
```
</details>
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
