# Function: <code>key_revoke</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void key_revoke(struct key * key)
```

```json
{
  "name": "key_revoke",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582184688,
      "name": "key_revoke",
      "external": true,
      "loc": "security/keys/key.c:980",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:__key_instantiate_and_link",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/keyctl.c:keyctl_revoke_key",
        "security/keys/request_key.c:complete_request_key",
        "security/keys/request_key_auth.c:request_key_auth_new",
        "net/dns_resolver/dns_key.c:exit_dns_resolver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582184688,
      "name": "key_revoke",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void key_revoke(struct key * key)
```

```json
{
  "name": "key_revoke",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582401008,
      "name": "key_revoke",
      "external": true,
      "loc": "security/keys/key.c:1008",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:__key_instantiate_and_link",
        "security/keys/keyctl.c:keyctl_revoke_key",
        "security/keys/request_key.c:complete_request_key",
        "security/keys/request_key_auth.c:request_key_auth_new",
        "net/dns_resolver/dns_key.c:exit_dns_resolver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582401008,
      "name": "key_revoke",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void key_revoke(struct key * key)
```

```json
{
  "name": "key_revoke",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582493200,
      "name": "key_revoke",
      "external": true,
      "loc": "security/keys/key.c:1008",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:__key_instantiate_and_link",
        "security/keys/keyctl.c:keyctl_revoke_key",
        "security/keys/request_key.c:complete_request_key",
        "security/keys/request_key_auth.c:request_key_auth_new",
        "net/dns_resolver/dns_key.c:exit_dns_resolver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582493200,
      "name": "key_revoke",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void key_revoke(struct key * key)
```

```json
{
  "name": "key_revoke",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582574096,
      "name": "key_revoke",
      "external": true,
      "loc": "security/keys/key.c:1008",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:__key_instantiate_and_link",
        "security/keys/keyctl.c:keyctl_revoke_key",
        "security/keys/request_key.c:complete_request_key",
        "security/keys/request_key_auth.c:request_key_auth_new",
        "net/dns_resolver/dns_key.c:exit_dns_resolver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582574096,
      "name": "key_revoke",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
void key_revoke(struct key * key)
```

```json
{
  "name": "key_revoke",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582726832,
      "name": "key_revoke",
      "external": true,
      "loc": "security/keys/key.c:1023",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:__key_instantiate_and_link",
        "security/keys/keyctl.c:keyctl_revoke_key",
        "security/keys/request_key.c:complete_request_key",
        "net/dns_resolver/dns_key.c:exit_dns_resolver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582726832,
      "name": "key_revoke",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void key_revoke(struct key * key)
```

```json
{
  "name": "key_revoke",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582925168,
      "name": "key_revoke",
      "external": true,
      "loc": "security/keys/key.c:1023",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:__key_instantiate_and_link",
        "security/keys/keyctl.c:keyctl_revoke_key",
        "security/keys/request_key.c:complete_request_key",
        "net/dns_resolver/dns_key.c:exit_dns_resolver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582925168,
      "name": "key_revoke",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void key_revoke(struct key * key)
```

```json
{
  "name": "key_revoke",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583033696,
      "name": "key_revoke",
      "external": true,
      "loc": "security/keys/key.c:1024",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:__key_instantiate_and_link",
        "security/keys/keyctl.c:keyctl_revoke_key",
        "security/keys/request_key.c:complete_request_key",
        "net/dns_resolver/dns_key.c:exit_dns_resolver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583033696,
      "name": "key_revoke",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void key_revoke(struct key * key)
```

```json
{
  "name": "key_revoke",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583215536,
      "name": "key_revoke",
      "external": true,
      "loc": "security/keys/key.c:1038",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:keyctl_revoke_key",
        "security/keys/request_key.c:complete_request_key",
        "net/dns_resolver/dns_key.c:exit_dns_resolver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583215536,
      "name": "key_revoke",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
void key_revoke(struct key * key)
```

```json
{
  "name": "key_revoke",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583321344,
      "name": "key_revoke",
      "external": true,
      "loc": "security/keys/key.c:1038",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:keyctl_revoke_key",
        "security/keys/request_key.c:complete_request_key",
        "net/dns_resolver/dns_key.c:exit_dns_resolver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583321344,
      "name": "key_revoke",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void key_revoke(struct key * key)
```

```json
{
  "name": "key_revoke",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583653728,
      "name": "key_revoke",
      "external": true,
      "loc": "security/keys/key.c:1054",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:keyctl_revoke_key",
        "security/keys/request_key.c:call_sbin_request_key",
        "net/dns_resolver/dns_key.c:exit_dns_resolver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583653728,
      "name": "key_revoke",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 246
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void key_revoke(struct key * key)
```

```json
{
  "name": "key_revoke",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583775168,
      "name": "key_revoke",
      "external": true,
      "loc": "security/keys/key.c:1058",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:keyctl_revoke_key",
        "security/keys/request_key.c:call_sbin_request_key",
        "net/dns_resolver/dns_key.c:exit_dns_resolver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583775168,
      "name": "key_revoke",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 246
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
void key_revoke(struct key * key)
```

```json
{
  "name": "key_revoke",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583799280,
      "name": "key_revoke",
      "external": true,
      "loc": "security/keys/key.c:1058",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:keyctl_revoke_key",
        "security/keys/request_key.c:call_sbin_request_key",
        "net/dns_resolver/dns_key.c:exit_dns_resolver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583799280,
      "name": "key_revoke",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 246
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
void key_revoke(struct key * key)
```

```json
{
  "name": "key_revoke",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584161824,
      "name": "key_revoke",
      "external": true,
      "loc": "security/keys/key.c:1058",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:keyctl_revoke_key",
        "security/keys/request_key.c:call_sbin_request_key",
        "net/dns_resolver/dns_key.c:exit_dns_resolver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584161824,
      "name": "key_revoke",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 246
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
void key_revoke(struct key * key)
```

```json
{
  "name": "key_revoke",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584760976,
      "name": "key_revoke",
      "external": true,
      "loc": "security/keys/key.c:1058",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:keyctl_revoke_key",
        "security/keys/request_key.c:call_sbin_request_key",
        "net/dns_resolver/dns_key.c:exit_dns_resolver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584760976,
      "name": "key_revoke",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
void key_revoke(struct key * key)
```

```json
{
  "name": "key_revoke",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585456656,
      "name": "key_revoke",
      "external": true,
      "loc": "security/keys/key.c:1058",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:keyctl_revoke_key",
        "security/keys/request_key.c:call_sbin_request_key",
        "net/dns_resolver/dns_key.c:exit_dns_resolver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585456656,
      "name": "key_revoke",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
void key_revoke(struct key * key)
```

```json
{
  "name": "key_revoke",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585688176,
      "name": "key_revoke",
      "external": true,
      "loc": "security/keys/key.c:1121",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:keyctl_revoke_key",
        "security/keys/request_key.c:call_sbin_request_key",
        "net/dns_resolver/dns_key.c:exit_dns_resolver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585688176,
      "name": "key_revoke",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
void key_revoke(struct key * key)
```

```json
{
  "name": "key_revoke",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585935232,
      "name": "key_revoke",
      "external": true,
      "loc": "security/keys/key.c:1117",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:keyctl_revoke_key",
        "security/keys/request_key.c:call_sbin_request_key",
        "net/dns_resolver/dns_key.c:exit_dns_resolver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585935232,
      "name": "key_revoke",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void key_revoke(struct key * key)
```

```json
{
  "name": "key_revoke",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495062792,
      "name": "key_revoke",
      "external": true,
      "loc": "security/keys/key.c:1038",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:keyctl_revoke_key",
        "security/keys/request_key.c:complete_request_key",
        "net/dns_resolver/dns_key.c:exit_dns_resolver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495062792,
      "name": "key_revoke",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
void key_revoke(struct key * key)
```

```json
{
  "name": "key_revoke",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228459916,
      "name": "key_revoke",
      "external": true,
      "loc": "security/keys/key.c:1038",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:keyctl_revoke_key",
        "security/keys/request_key.c:complete_request_key",
        "net/dns_resolver/dns_key.c:exit_dns_resolver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228459916,
      "name": "key_revoke",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
void key_revoke(struct key * key)
```

```json
{
  "name": "key_revoke",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288954448,
      "name": "key_revoke",
      "external": true,
      "loc": "security/keys/key.c:1038",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:keyctl_revoke_key",
        "security/keys/request_key.c:complete_request_key",
        "net/dns_resolver/dns_key.c:exit_dns_resolver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288954448,
      "name": "key_revoke",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
void key_revoke(struct key * key)
```

```json
{
  "name": "key_revoke",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274331236,
      "name": "key_revoke",
      "external": true,
      "loc": "security/keys/key.c:1038",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:keyctl_revoke_key",
        "security/keys/request_key.c:complete_request_key",
        "net/dns_resolver/dns_key.c:exit_dns_resolver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274331236,
      "name": "key_revoke",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void key_revoke(struct key * key)
```

```json
{
  "name": "key_revoke",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583290080,
      "name": "key_revoke",
      "external": true,
      "loc": "security/keys/key.c:1038",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:keyctl_revoke_key",
        "security/keys/request_key.c:complete_request_key",
        "net/dns_resolver/dns_key.c:exit_dns_resolver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583290080,
      "name": "key_revoke",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
void key_revoke(struct key * key)
```

```json
{
  "name": "key_revoke",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583227216,
      "name": "key_revoke",
      "external": true,
      "loc": "security/keys/key.c:1038",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:keyctl_revoke_key",
        "security/keys/request_key.c:complete_request_key",
        "net/dns_resolver/dns_key.c:exit_dns_resolver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583227216,
      "name": "key_revoke",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
void key_revoke(struct key * key)
```

```json
{
  "name": "key_revoke",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583274112,
      "name": "key_revoke",
      "external": true,
      "loc": "security/keys/key.c:1038",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:keyctl_revoke_key",
        "security/keys/request_key.c:complete_request_key",
        "net/dns_resolver/dns_key.c:exit_dns_resolver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583274112,
      "name": "key_revoke",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
void key_revoke(struct key * key)
```

```json
{
  "name": "key_revoke",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583368816,
      "name": "key_revoke",
      "external": true,
      "loc": "security/keys/key.c:1038",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:keyctl_revoke_key",
        "security/keys/request_key.c:complete_request_key",
        "net/dns_resolver/dns_key.c:exit_dns_resolver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583368816,
      "name": "key_revoke",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
