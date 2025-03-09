# Function: <code>look_up_user_keyrings</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int look_up_user_keyrings(struct key * * _user_keyring, struct key * * _user_session_keyring)
```

```json
{
  "name": "look_up_user_keyrings",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583238480,
      "name": "look_up_user_keyrings",
      "external": true,
      "loc": "security/keys/process_keys.c:74",
      "file": "security/keys/process_keys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/process_keys.c:init_root_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/request_key.c:construct_key_and_link",
        "security/keys/request_key.c:construct_key_and_link",
        "security/keys/request_key.c:call_sbin_request_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583238480,
      "name": "look_up_user_keyrings",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 767
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
int look_up_user_keyrings(struct key * * _user_keyring, struct key * * _user_session_keyring)
```

```json
{
  "name": "look_up_user_keyrings",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583344304,
      "name": "look_up_user_keyrings",
      "external": true,
      "loc": "security/keys/process_keys.c:74",
      "file": "security/keys/process_keys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/process_keys.c:init_root_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/request_key.c:construct_key_and_link",
        "security/keys/request_key.c:construct_key_and_link",
        "security/keys/request_key.c:call_sbin_request_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583344304,
      "name": "look_up_user_keyrings",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 767
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
int look_up_user_keyrings(struct key * * _user_keyring, struct key * * _user_session_keyring)
```

```json
{
  "name": "look_up_user_keyrings",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583678912,
      "name": "look_up_user_keyrings",
      "external": true,
      "loc": "security/keys/process_keys.c:74",
      "file": "security/keys/process_keys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/process_keys.c:init_root_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/request_key.c:construct_get_dest_keyring",
        "security/keys/request_key.c:construct_get_dest_keyring",
        "security/keys/request_key.c:call_sbin_request_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583678912,
      "name": "look_up_user_keyrings",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 753
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
int look_up_user_keyrings(struct key * * _user_keyring, struct key * * _user_session_keyring)
```

```json
{
  "name": "look_up_user_keyrings",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583800416,
      "name": "look_up_user_keyrings",
      "external": true,
      "loc": "security/keys/process_keys.c:74",
      "file": "security/keys/process_keys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/process_keys.c:init_root_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/request_key.c:construct_get_dest_keyring",
        "security/keys/request_key.c:construct_get_dest_keyring",
        "security/keys/request_key.c:call_sbin_request_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583800416,
      "name": "look_up_user_keyrings",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 753
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
int look_up_user_keyrings(struct key * * _user_keyring, struct key * * _user_session_keyring)
```

```json
{
  "name": "look_up_user_keyrings",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583824608,
      "name": "look_up_user_keyrings",
      "external": true,
      "loc": "security/keys/process_keys.c:74",
      "file": "security/keys/process_keys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/process_keys.c:init_root_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/request_key.c:construct_get_dest_keyring",
        "security/keys/request_key.c:construct_get_dest_keyring",
        "security/keys/request_key.c:call_sbin_request_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583824608,
      "name": "look_up_user_keyrings",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 753
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
int look_up_user_keyrings(struct key * * _user_keyring, struct key * * _user_session_keyring)
```

```json
{
  "name": "look_up_user_keyrings",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584187648,
      "name": "look_up_user_keyrings",
      "external": true,
      "loc": "security/keys/process_keys.c:74",
      "file": "security/keys/process_keys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/process_keys.c:init_root_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/request_key.c:construct_get_dest_keyring",
        "security/keys/request_key.c:construct_get_dest_keyring",
        "security/keys/request_key.c:call_sbin_request_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584187648,
      "name": "look_up_user_keyrings",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 753
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
int look_up_user_keyrings(struct key * * _user_keyring, struct key * * _user_session_keyring)
```

```json
{
  "name": "look_up_user_keyrings",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584788480,
      "name": "look_up_user_keyrings",
      "external": true,
      "loc": "security/keys/process_keys.c:74",
      "file": "security/keys/process_keys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/process_keys.c:init_root_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/request_key.c:construct_get_dest_keyring",
        "security/keys/request_key.c:construct_get_dest_keyring",
        "security/keys/request_key.c:call_sbin_request_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584788480,
      "name": "look_up_user_keyrings",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 780
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
int look_up_user_keyrings(struct key * * _user_keyring, struct key * * _user_session_keyring)
```

```json
{
  "name": "look_up_user_keyrings",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585485792,
      "name": "look_up_user_keyrings",
      "external": true,
      "loc": "security/keys/process_keys.c:74",
      "file": "security/keys/process_keys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/process_keys.c:init_root_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/request_key.c:construct_get_dest_keyring",
        "security/keys/request_key.c:construct_get_dest_keyring",
        "security/keys/request_key.c:call_sbin_request_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585485792,
      "name": "look_up_user_keyrings",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 780
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
int look_up_user_keyrings(struct key * * _user_keyring, struct key * * _user_session_keyring)
```

```json
{
  "name": "look_up_user_keyrings",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585717264,
      "name": "look_up_user_keyrings",
      "external": true,
      "loc": "security/keys/process_keys.c:74",
      "file": "security/keys/process_keys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/process_keys.c:init_root_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/request_key.c:construct_get_dest_keyring",
        "security/keys/request_key.c:construct_get_dest_keyring",
        "security/keys/request_key.c:call_sbin_request_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585717264,
      "name": "look_up_user_keyrings",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 780
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
int look_up_user_keyrings(struct key * * _user_keyring, struct key * * _user_session_keyring)
```

```json
{
  "name": "look_up_user_keyrings",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585964384,
      "name": "look_up_user_keyrings",
      "external": true,
      "loc": "security/keys/process_keys.c:74",
      "file": "security/keys/process_keys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/process_keys.c:init_root_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/request_key.c:construct_get_dest_keyring",
        "security/keys/request_key.c:construct_get_dest_keyring",
        "security/keys/request_key.c:call_sbin_request_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585964384,
      "name": "look_up_user_keyrings",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 780
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
int look_up_user_keyrings(struct key * * _user_keyring, struct key * * _user_session_keyring)
```

```json
{
  "name": "look_up_user_keyrings",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495088504,
      "name": "look_up_user_keyrings",
      "external": true,
      "loc": "security/keys/process_keys.c:74",
      "file": "security/keys/process_keys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/process_keys.c:init_root_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/request_key.c:construct_key_and_link",
        "security/keys/request_key.c:construct_key_and_link",
        "security/keys/request_key.c:call_sbin_request_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495088504,
      "name": "look_up_user_keyrings",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 684
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
int look_up_user_keyrings(struct key * * _user_keyring, struct key * * _user_session_keyring)
```

```json
{
  "name": "look_up_user_keyrings",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228482156,
      "name": "look_up_user_keyrings",
      "external": true,
      "loc": "security/keys/process_keys.c:74",
      "file": "security/keys/process_keys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/process_keys.c:init_root_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/request_key.c:construct_key_and_link",
        "security/keys/request_key.c:construct_key_and_link",
        "security/keys/request_key.c:call_sbin_request_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228482156,
      "name": "look_up_user_keyrings",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 720
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
int look_up_user_keyrings(struct key * * _user_keyring, struct key * * _user_session_keyring)
```

```json
{
  "name": "look_up_user_keyrings",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288988752,
      "name": "look_up_user_keyrings",
      "external": true,
      "loc": "security/keys/process_keys.c:74",
      "file": "security/keys/process_keys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/process_keys.c:init_root_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/request_key.c:construct_key_and_link",
        "security/keys/request_key.c:construct_key_and_link",
        "security/keys/request_key.c:call_sbin_request_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288988752,
      "name": "look_up_user_keyrings",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 928
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
int look_up_user_keyrings(struct key * * _user_keyring, struct key * * _user_session_keyring)
```

```json
{
  "name": "look_up_user_keyrings",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274351502,
      "name": "look_up_user_keyrings",
      "external": true,
      "loc": "security/keys/process_keys.c:74",
      "file": "security/keys/process_keys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/process_keys.c:init_root_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/request_key.c:construct_key_and_link",
        "security/keys/request_key.c:construct_key_and_link",
        "security/keys/request_key.c:call_sbin_request_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274351502,
      "name": "look_up_user_keyrings",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 578
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
int look_up_user_keyrings(struct key * * _user_keyring, struct key * * _user_session_keyring)
```

```json
{
  "name": "look_up_user_keyrings",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583313040,
      "name": "look_up_user_keyrings",
      "external": true,
      "loc": "security/keys/process_keys.c:74",
      "file": "security/keys/process_keys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/process_keys.c:init_root_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/request_key.c:construct_key_and_link",
        "security/keys/request_key.c:construct_key_and_link",
        "security/keys/request_key.c:call_sbin_request_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583313040,
      "name": "look_up_user_keyrings",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 767
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
int look_up_user_keyrings(struct key * * _user_keyring, struct key * * _user_session_keyring)
```

```json
{
  "name": "look_up_user_keyrings",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583250144,
      "name": "look_up_user_keyrings",
      "external": true,
      "loc": "security/keys/process_keys.c:74",
      "file": "security/keys/process_keys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/process_keys.c:init_root_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/request_key.c:construct_key_and_link",
        "security/keys/request_key.c:construct_key_and_link",
        "security/keys/request_key.c:call_sbin_request_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583250144,
      "name": "look_up_user_keyrings",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 767
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
int look_up_user_keyrings(struct key * * _user_keyring, struct key * * _user_session_keyring)
```

```json
{
  "name": "look_up_user_keyrings",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583297072,
      "name": "look_up_user_keyrings",
      "external": true,
      "loc": "security/keys/process_keys.c:74",
      "file": "security/keys/process_keys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/process_keys.c:init_root_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/request_key.c:construct_key_and_link",
        "security/keys/request_key.c:construct_key_and_link",
        "security/keys/request_key.c:call_sbin_request_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583297072,
      "name": "look_up_user_keyrings",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 767
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
int look_up_user_keyrings(struct key * * _user_keyring, struct key * * _user_session_keyring)
```

```json
{
  "name": "look_up_user_keyrings",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583391712,
      "name": "look_up_user_keyrings",
      "external": true,
      "loc": "security/keys/process_keys.c:74",
      "file": "security/keys/process_keys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/process_keys.c:init_root_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/request_key.c:construct_key_and_link",
        "security/keys/request_key.c:construct_key_and_link",
        "security/keys/request_key.c:call_sbin_request_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583391712,
      "name": "look_up_user_keyrings",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 767
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int look_up_user_keyrings(struct key * * _user_keyring, struct key * * _user_session_keyring)
```
</details>
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
