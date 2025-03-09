# Function: <code>key_link</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int key_link(struct key * keyring, struct key * key)
```

```json
{
  "name": "key_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582194512,
      "name": "key_link",
      "external": true,
      "loc": "security/keys/keyring.c:1214",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:keyctl_keyring_link",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/process_keys.c:install_user_keyrings",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/persistent.c:keyctl_get_persistent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582194512,
      "name": "key_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
int key_link(struct key * keyring, struct key * key)
```

```json
{
  "name": "key_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582411024,
      "name": "key_link",
      "external": true,
      "loc": "security/keys/keyring.c:1248",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:system_trusted_keyring_init",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:keyctl_keyring_link",
        "security/keys/process_keys.c:install_user_keyrings",
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/persistent.c:keyctl_get_persistent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582411024,
      "name": "key_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
int key_link(struct key * keyring, struct key * key)
```

```json
{
  "name": "key_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582503216,
      "name": "key_link",
      "external": true,
      "loc": "security/keys/keyring.c:1248",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:system_trusted_keyring_init",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:keyctl_keyring_link",
        "security/keys/process_keys.c:install_user_keyrings",
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/persistent.c:keyctl_get_persistent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582503216,
      "name": "key_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
int key_link(struct key * keyring, struct key * key)
```

```json
{
  "name": "key_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582584448,
      "name": "key_link",
      "external": true,
      "loc": "security/keys/keyring.c:1361",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:system_trusted_keyring_init",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:keyctl_keyring_link",
        "security/keys/process_keys.c:install_user_keyrings",
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/persistent.c:keyctl_get_persistent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582584448,
      "name": "key_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
int key_link(struct key * keyring, struct key * key)
```

```json
{
  "name": "key_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582737536,
      "name": "key_link",
      "external": true,
      "loc": "security/keys/keyring.c:1363",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:system_trusted_keyring_init",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:keyctl_keyring_link",
        "security/keys/process_keys.c:install_user_keyrings",
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/persistent.c:keyctl_get_persistent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582737536,
      "name": "key_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
int key_link(struct key * keyring, struct key * key)
```

```json
{
  "name": "key_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582936192,
      "name": "key_link",
      "external": true,
      "loc": "security/keys/keyring.c:1356",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:system_trusted_keyring_init",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:keyctl_keyring_link",
        "security/keys/process_keys.c:install_user_keyrings",
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/persistent.c:keyctl_get_persistent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582936192,
      "name": "key_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
int key_link(struct key * keyring, struct key * key)
```

```json
{
  "name": "key_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583044736,
      "name": "key_link",
      "external": true,
      "loc": "security/keys/keyring.c:1354",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:system_trusted_keyring_init",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:keyctl_keyring_link",
        "security/keys/process_keys.c:install_user_keyrings",
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/persistent.c:keyctl_get_persistent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583044736,
      "name": "key_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
int key_link(struct key * keyring, struct key * key)
```

```json
{
  "name": "key_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583227184,
      "name": "key_link",
      "external": true,
      "loc": "security/keys/keyring.c:1435",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:system_trusted_keyring_init",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:keyctl_keyring_link",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/persistent.c:keyctl_get_persistent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583227184,
      "name": "key_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
int key_link(struct key * keyring, struct key * key)
```

```json
{
  "name": "key_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583332992,
      "name": "key_link",
      "external": true,
      "loc": "security/keys/keyring.c:1435",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:system_trusted_keyring_init",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:keyctl_keyring_link",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/persistent.c:keyctl_get_persistent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583332992,
      "name": "key_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
int key_link(struct key * keyring, struct key * key)
```

```json
{
  "name": "key_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583666928,
      "name": "key_link",
      "external": true,
      "loc": "security/keys/keyring.c:1435",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:system_trusted_keyring_init",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:keyctl_keyring_link",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/persistent.c:key_get_persistent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583666928,
      "name": "key_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
int key_link(struct key * keyring, struct key * key)
```

```json
{
  "name": "key_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583788400,
      "name": "key_link",
      "external": true,
      "loc": "security/keys/keyring.c:1435",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:system_trusted_keyring_init",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:keyctl_keyring_link",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/persistent.c:key_get_persistent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583788400,
      "name": "key_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 306
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
int key_link(struct key * keyring, struct key * key)
```

```json
{
  "name": "key_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583812528,
      "name": "key_link",
      "external": true,
      "loc": "security/keys/keyring.c:1435",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:system_trusted_keyring_init",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:keyctl_keyring_link",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/persistent.c:key_get_persistent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583812528,
      "name": "key_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 306
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
int key_link(struct key * keyring, struct key * key)
```

```json
{
  "name": "key_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584175568,
      "name": "key_link",
      "external": true,
      "loc": "security/keys/keyring.c:1435",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:system_trusted_keyring_init",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:keyctl_keyring_link",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/persistent.c:key_get_persistent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584175568,
      "name": "key_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 306
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
int key_link(struct key * keyring, struct key * key)
```

```json
{
  "name": "key_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584775664,
      "name": "key_link",
      "external": true,
      "loc": "security/keys/keyring.c:1435",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:system_trusted_keyring_init",
        "certs/system_keyring.c:set_machine_trusted_keys",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:keyctl_keyring_link",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/persistent.c:key_get_persistent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584775664,
      "name": "key_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 327
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
int key_link(struct key * keyring, struct key * key)
```

```json
{
  "name": "key_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585472192,
      "name": "key_link",
      "external": true,
      "loc": "security/keys/keyring.c:1435",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:system_trusted_keyring_init",
        "certs/system_keyring.c:set_machine_trusted_keys",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:keyctl_keyring_link",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/persistent.c:key_get_persistent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585472192,
      "name": "key_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 327
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
int key_link(struct key * keyring, struct key * key)
```

```json
{
  "name": "key_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585703776,
      "name": "key_link",
      "external": true,
      "loc": "security/keys/keyring.c:1435",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:system_trusted_keyring_init",
        "certs/system_keyring.c:set_machine_trusted_keys",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:keyctl_keyring_link",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/persistent.c:key_get_persistent",
        "net/handshake/tlshd.c:tls_handshake_accept"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585703776,
      "name": "key_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 327
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
int key_link(struct key * keyring, struct key * key)
```

```json
{
  "name": "key_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585950816,
      "name": "key_link",
      "external": true,
      "loc": "security/keys/keyring.c:1435",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:system_trusted_keyring_init",
        "certs/system_keyring.c:set_machine_trusted_keys",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:keyctl_keyring_link",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/persistent.c:key_get_persistent",
        "net/handshake/tlshd.c:tls_handshake_accept"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585950816,
      "name": "key_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 327
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
int key_link(struct key * keyring, struct key * key)
```

```json
{
  "name": "key_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495076264,
      "name": "key_link",
      "external": true,
      "loc": "security/keys/keyring.c:1435",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:system_trusted_keyring_init",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:keyctl_keyring_link",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/persistent.c:keyctl_get_persistent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495076264,
      "name": "key_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
int key_link(struct key * keyring, struct key * key)
```

```json
{
  "name": "key_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228471588,
      "name": "key_link",
      "external": true,
      "loc": "security/keys/keyring.c:1435",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:system_trusted_keyring_init",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:keyctl_keyring_link",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/persistent.c:keyctl_get_persistent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228471588,
      "name": "key_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
int key_link(struct key * keyring, struct key * key)
```

```json
{
  "name": "key_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288973968,
      "name": "key_link",
      "external": true,
      "loc": "security/keys/keyring.c:1435",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:system_trusted_keyring_init",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:keyctl_keyring_link",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/persistent.c:keyctl_get_persistent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288973968,
      "name": "key_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
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
int key_link(struct key * keyring, struct key * key)
```

```json
{
  "name": "key_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274342866,
      "name": "key_link",
      "external": true,
      "loc": "security/keys/keyring.c:1435",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:system_trusted_keyring_init",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:keyctl_keyring_link",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/persistent.c:keyctl_get_persistent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274342866,
      "name": "key_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
int key_link(struct key * keyring, struct key * key)
```

```json
{
  "name": "key_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583301728,
      "name": "key_link",
      "external": true,
      "loc": "security/keys/keyring.c:1435",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:system_trusted_keyring_init",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:keyctl_keyring_link",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/persistent.c:keyctl_get_persistent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583301728,
      "name": "key_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
int key_link(struct key * keyring, struct key * key)
```

```json
{
  "name": "key_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583238864,
      "name": "key_link",
      "external": true,
      "loc": "security/keys/keyring.c:1435",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:system_trusted_keyring_init",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:keyctl_keyring_link",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/persistent.c:keyctl_get_persistent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583238864,
      "name": "key_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
int key_link(struct key * keyring, struct key * key)
```

```json
{
  "name": "key_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583285760,
      "name": "key_link",
      "external": true,
      "loc": "security/keys/keyring.c:1435",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:system_trusted_keyring_init",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:keyctl_keyring_link",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/persistent.c:keyctl_get_persistent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583285760,
      "name": "key_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
int key_link(struct key * keyring, struct key * key)
```

```json
{
  "name": "key_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583380352,
      "name": "key_link",
      "external": true,
      "loc": "security/keys/keyring.c:1435",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:system_trusted_keyring_init",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:keyctl_keyring_link",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/persistent.c:keyctl_get_persistent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583380352,
      "name": "key_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
