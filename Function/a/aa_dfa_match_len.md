# Function: <code>aa_dfa_match_len</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
unsigned int aa_dfa_match_len(struct aa_dfa * dfa, unsigned int start, const char * str, int len)
```

```json
{
  "name": "aa_dfa_match_len",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582487888,
      "name": "aa_dfa_match_len",
      "external": true,
      "loc": "security/apparmor/match.c:327",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:profile_query_cb",
        "security/apparmor/apparmorfs.c:profile_query_cb",
        "security/apparmor/apparmorfs.c:profile_query_cb",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/af_unix.c:match_to_prot",
        "security/apparmor/af_unix.c:profile_create_perm",
        "security/apparmor/af_unix.c:match_addr",
        "security/apparmor/af_unix.c:match_addr",
        "security/apparmor/af_unix.c:profile_sk_perm",
        "security/apparmor/af_unix.c:profile_bind_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582487888,
      "name": "aa_dfa_match_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 207
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
unsigned int aa_dfa_match_len(struct aa_dfa * dfa, unsigned int start, const char * str, int len)
```

```json
{
  "name": "aa_dfa_match_len",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582720720,
      "name": "aa_dfa_match_len",
      "external": true,
      "loc": "security/apparmor/match.c:331",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:profile_query_cb",
        "security/apparmor/apparmorfs.c:profile_query_cb",
        "security/apparmor/apparmorfs.c:profile_query_cb",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_bind_perm",
        "security/apparmor/af_unix.c:profile_sk_perm",
        "security/apparmor/af_unix.c:profile_create_perm",
        "security/apparmor/af_unix.c:profile_create_perm",
        "security/apparmor/af_unix.c:match_to_local",
        "security/apparmor/af_unix.c:match_addr",
        "security/apparmor/af_unix.c:match_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582720720,
      "name": "aa_dfa_match_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 213
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
unsigned int aa_dfa_match_len(struct aa_dfa * dfa, unsigned int start, const char * str, int len)
```

```json
{
  "name": "aa_dfa_match_len",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582815376,
      "name": "aa_dfa_match_len",
      "external": true,
      "loc": "security/apparmor/match.c:331",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:profile_query_cb",
        "security/apparmor/apparmorfs.c:profile_query_cb",
        "security/apparmor/apparmorfs.c:profile_query_cb",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_bind_perm",
        "security/apparmor/af_unix.c:profile_sk_perm",
        "security/apparmor/af_unix.c:profile_create_perm",
        "security/apparmor/af_unix.c:profile_create_perm",
        "security/apparmor/af_unix.c:match_to_local",
        "security/apparmor/af_unix.c:match_addr",
        "security/apparmor/af_unix.c:match_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582815376,
      "name": "aa_dfa_match_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 213
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
unsigned int aa_dfa_match_len(struct aa_dfa * dfa, unsigned int start, const char * str, int len)
```

```json
{
  "name": "aa_dfa_match_len",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582903152,
      "name": "aa_dfa_match_len",
      "external": true,
      "loc": "security/apparmor/match.c:331",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:profile_query_cb",
        "security/apparmor/apparmorfs.c:profile_query_cb",
        "security/apparmor/apparmorfs.c:profile_query_cb",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_bind_perm",
        "security/apparmor/af_unix.c:profile_sk_perm",
        "security/apparmor/af_unix.c:profile_create_perm",
        "security/apparmor/af_unix.c:profile_create_perm",
        "security/apparmor/af_unix.c:match_to_local",
        "security/apparmor/af_unix.c:match_addr",
        "security/apparmor/af_unix.c:match_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582903152,
      "name": "aa_dfa_match_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
unsigned int aa_dfa_match_len(struct aa_dfa * dfa, unsigned int start, const char * str, int len)
```

```json
{
  "name": "aa_dfa_match_len",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583061264,
      "name": "aa_dfa_match_len",
      "external": true,
      "loc": "security/apparmor/match.c:331",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:profile_query_cb",
        "security/apparmor/apparmorfs.c:profile_query_cb",
        "security/apparmor/apparmorfs.c:profile_query_cb",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_bind_perm",
        "security/apparmor/af_unix.c:profile_sk_perm",
        "security/apparmor/af_unix.c:profile_create_perm",
        "security/apparmor/af_unix.c:profile_create_perm",
        "security/apparmor/af_unix.c:match_to_local",
        "security/apparmor/af_unix.c:match_addr",
        "security/apparmor/af_unix.c:match_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583061264,
      "name": "aa_dfa_match_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
unsigned int aa_dfa_match_len(struct aa_dfa * dfa, unsigned int start, const char * str, int len)
```

```json
{
  "name": "aa_dfa_match_len",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583262320,
      "name": "aa_dfa_match_len",
      "external": true,
      "loc": "security/apparmor/match.c:404",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:profile_query_cb",
        "security/apparmor/apparmorfs.c:profile_query_cb",
        "security/apparmor/apparmorfs.c:profile_query_cb",
        "security/apparmor/domain.c:aa_xattrs_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/net.c:aa_profile_af_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_bind_perm",
        "security/apparmor/af_unix.c:profile_sk_perm",
        "security/apparmor/af_unix.c:profile_create_perm",
        "security/apparmor/af_unix.c:profile_create_perm",
        "security/apparmor/af_unix.c:match_to_local",
        "security/apparmor/af_unix.c:match_addr",
        "security/apparmor/af_unix.c:match_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583262320,
      "name": "aa_dfa_match_len",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
unsigned int aa_dfa_match_len(struct aa_dfa * dfa, unsigned int start, const char * str, int len)
```

```json
{
  "name": "aa_dfa_match_len",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583380176,
      "name": "aa_dfa_match_len",
      "external": true,
      "loc": "security/apparmor/match.c:404",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:profile_query_cb",
        "security/apparmor/apparmorfs.c:profile_query_cb",
        "security/apparmor/apparmorfs.c:profile_query_cb",
        "security/apparmor/domain.c:aa_xattrs_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/net.c:aa_profile_af_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_bind_perm",
        "security/apparmor/af_unix.c:profile_sk_perm",
        "security/apparmor/af_unix.c:profile_create_perm",
        "security/apparmor/af_unix.c:profile_create_perm",
        "security/apparmor/af_unix.c:match_to_local",
        "security/apparmor/af_unix.c:match_addr",
        "security/apparmor/af_unix.c:match_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583380176,
      "name": "aa_dfa_match_len",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
unsigned int aa_dfa_match_len(struct aa_dfa * dfa, unsigned int start, const char * str, int len)
```

```json
{
  "name": "aa_dfa_match_len",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583566896,
      "name": "aa_dfa_match_len",
      "external": true,
      "loc": "security/apparmor/match.c:400",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:profile_query_cb",
        "security/apparmor/apparmorfs.c:profile_query_cb",
        "security/apparmor/apparmorfs.c:profile_query_cb",
        "security/apparmor/domain.c:aa_xattrs_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/net.c:aa_profile_af_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_bind_perm",
        "security/apparmor/af_unix.c:profile_sk_perm",
        "security/apparmor/af_unix.c:profile_create_perm",
        "security/apparmor/af_unix.c:profile_create_perm",
        "security/apparmor/af_unix.c:match_to_local",
        "security/apparmor/af_unix.c:match_addr",
        "security/apparmor/af_unix.c:match_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583566896,
      "name": "aa_dfa_match_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
unsigned int aa_dfa_match_len(struct aa_dfa * dfa, unsigned int start, const char * str, int len)
```

```json
{
  "name": "aa_dfa_match_len",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583672624,
      "name": "aa_dfa_match_len",
      "external": true,
      "loc": "security/apparmor/match.c:415",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:profile_query_cb",
        "security/apparmor/apparmorfs.c:profile_query_cb",
        "security/apparmor/apparmorfs.c:profile_query_cb",
        "security/apparmor/domain.c:aa_xattrs_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/net.c:aa_profile_af_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_bind_perm",
        "security/apparmor/af_unix.c:profile_sk_perm",
        "security/apparmor/af_unix.c:profile_create_perm",
        "security/apparmor/af_unix.c:profile_create_perm",
        "security/apparmor/af_unix.c:match_to_local",
        "security/apparmor/af_unix.c:match_addr",
        "security/apparmor/af_unix.c:match_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583672624,
      "name": "aa_dfa_match_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
unsigned int aa_dfa_match_len(struct aa_dfa * dfa, unsigned int start, const char * str, int len)
```

```json
{
  "name": "aa_dfa_match_len",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584035360,
      "name": "aa_dfa_match_len",
      "external": true,
      "loc": "security/apparmor/match.c:439",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:profile_query_cb",
        "security/apparmor/apparmorfs.c:profile_query_cb",
        "security/apparmor/apparmorfs.c:profile_query_cb",
        "security/apparmor/domain.c:find_attach",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/label.c:label_components_match",
        "security/apparmor/label.c:label_components_match",
        "security/apparmor/label.c:label_components_match",
        "security/apparmor/label.c:label_components_match",
        "security/apparmor/label.c:label_compound_match",
        "security/apparmor/label.c:label_compound_match",
        "security/apparmor/label.c:label_compound_match",
        "security/apparmor/label.c:label_compound_match",
        "security/apparmor/net.c:aa_profile_af_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_bind_perm",
        "security/apparmor/af_unix.c:profile_sk_perm",
        "security/apparmor/af_unix.c:profile_create_perm",
        "security/apparmor/af_unix.c:profile_create_perm",
        "security/apparmor/af_unix.c:match_addr",
        "security/apparmor/af_unix.c:match_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584035360,
      "name": "aa_dfa_match_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
unsigned int aa_dfa_match_len(struct aa_dfa * dfa, unsigned int start, const char * str, int len)
```

```json
{
  "name": "aa_dfa_match_len",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584154608,
      "name": "aa_dfa_match_len",
      "external": true,
      "loc": "security/apparmor/match.c:439",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:profile_query_cb",
        "security/apparmor/apparmorfs.c:profile_query_cb",
        "security/apparmor/apparmorfs.c:profile_query_cb",
        "security/apparmor/domain.c:find_attach",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/label.c:label_components_match",
        "security/apparmor/label.c:label_components_match",
        "security/apparmor/label.c:label_components_match",
        "security/apparmor/label.c:label_components_match",
        "security/apparmor/label.c:label_compound_match",
        "security/apparmor/label.c:label_compound_match",
        "security/apparmor/label.c:label_compound_match",
        "security/apparmor/label.c:label_compound_match",
        "security/apparmor/net.c:aa_profile_af_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_bind_perm",
        "security/apparmor/af_unix.c:profile_sk_perm",
        "security/apparmor/af_unix.c:profile_create_perm",
        "security/apparmor/af_unix.c:profile_create_perm",
        "security/apparmor/af_unix.c:match_addr",
        "security/apparmor/af_unix.c:match_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584154608,
      "name": "aa_dfa_match_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
unsigned int aa_dfa_match_len(struct aa_dfa * dfa, unsigned int start, const char * str, int len)
```

```json
{
  "name": "aa_dfa_match_len",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584181664,
      "name": "aa_dfa_match_len",
      "external": true,
      "loc": "security/apparmor/match.c:439",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:profile_query_cb",
        "security/apparmor/apparmorfs.c:profile_query_cb",
        "security/apparmor/apparmorfs.c:profile_query_cb",
        "security/apparmor/domain.c:find_attach",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/net.c:aa_profile_af_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_bind_perm",
        "security/apparmor/af_unix.c:profile_sk_perm",
        "security/apparmor/af_unix.c:profile_create_perm",
        "security/apparmor/af_unix.c:profile_create_perm",
        "security/apparmor/af_unix.c:match_addr",
        "security/apparmor/af_unix.c:match_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584181664,
      "name": "aa_dfa_match_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
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
unsigned int aa_dfa_match_len(struct aa_dfa * dfa, unsigned int start, const char * str, int len)
```

```json
{
  "name": "aa_dfa_match_len",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584566688,
      "name": "aa_dfa_match_len",
      "external": true,
      "loc": "security/apparmor/match.c:439",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:profile_query_cb",
        "security/apparmor/apparmorfs.c:profile_query_cb",
        "security/apparmor/apparmorfs.c:profile_query_cb",
        "security/apparmor/domain.c:find_attach",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/net.c:aa_profile_af_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_bind_perm",
        "security/apparmor/af_unix.c:profile_sk_perm",
        "security/apparmor/af_unix.c:profile_create_perm",
        "security/apparmor/af_unix.c:profile_create_perm",
        "security/apparmor/af_unix.c:match_addr",
        "security/apparmor/af_unix.c:match_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584566688,
      "name": "aa_dfa_match_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
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
unsigned int aa_dfa_match_len(struct aa_dfa * dfa, unsigned int start, const char * str, int len)
```

```json
{
  "name": "aa_dfa_match_len",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585212256,
      "name": "aa_dfa_match_len",
      "external": true,
      "loc": "security/apparmor/match.c:439",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:profile_query_cb",
        "security/apparmor/apparmorfs.c:profile_query_cb",
        "security/apparmor/apparmorfs.c:profile_query_cb",
        "security/apparmor/task.c:aa_profile_ns_perm",
        "security/apparmor/domain.c:find_attach",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/file.c:__aa_path_perm",
        "security/apparmor/label.c:label_components_match",
        "security/apparmor/label.c:label_components_match",
        "security/apparmor/label.c:label_components_match",
        "security/apparmor/label.c:label_components_match",
        "security/apparmor/label.c:label_compound_match",
        "security/apparmor/label.c:label_compound_match",
        "security/apparmor/label.c:label_compound_match",
        "security/apparmor/label.c:label_compound_match",
        "security/apparmor/net.c:aa_profile_af_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_bind_perm",
        "security/apparmor/af_unix.c:profile_bind_perm",
        "security/apparmor/af_unix.c:profile_bind_perm",
        "security/apparmor/af_unix.c:profile_sk_perm",
        "security/apparmor/af_unix.c:profile_create_perm",
        "security/apparmor/af_unix.c:profile_create_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585212256,
      "name": "aa_dfa_match_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
unsigned int aa_dfa_match_len(struct aa_dfa * dfa, unsigned int start, const char * str, int len)
```

```json
{
  "name": "aa_dfa_match_len",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585944336,
      "name": "aa_dfa_match_len",
      "external": true,
      "loc": "security/apparmor/match.c:439",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:profile_query_cb",
        "security/apparmor/apparmorfs.c:profile_query_cb",
        "security/apparmor/apparmorfs.c:profile_query_cb",
        "security/apparmor/task.c:aa_profile_ns_perm",
        "security/apparmor/domain.c:find_attach",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/file.c:__aa_path_perm",
        "security/apparmor/label.c:label_components_match",
        "security/apparmor/label.c:label_components_match",
        "security/apparmor/label.c:label_components_match",
        "security/apparmor/label.c:label_components_match",
        "security/apparmor/label.c:label_compound_match",
        "security/apparmor/label.c:label_compound_match",
        "security/apparmor/label.c:label_compound_match",
        "security/apparmor/label.c:label_compound_match",
        "security/apparmor/net.c:aa_profile_af_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_bind_perm",
        "security/apparmor/af_unix.c:profile_create_perm",
        "security/apparmor/af_unix.c:profile_create_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585944336,
      "name": "aa_dfa_match_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
unsigned int aa_dfa_match_len(struct aa_dfa * dfa, unsigned int start, const char * str, int len)
```

```json
{
  "name": "aa_dfa_match_len",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586176784,
      "name": "aa_dfa_match_len",
      "external": true,
      "loc": "security/apparmor/match.c:395",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:profile_query_cb",
        "security/apparmor/apparmorfs.c:profile_query_cb",
        "security/apparmor/apparmorfs.c:profile_query_cb",
        "security/apparmor/task.c:aa_profile_ns_perm",
        "security/apparmor/domain.c:find_attach",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/file.c:__aa_path_perm",
        "security/apparmor/label.c:label_components_match",
        "security/apparmor/label.c:label_components_match",
        "security/apparmor/label.c:label_components_match",
        "security/apparmor/label.c:label_components_match",
        "security/apparmor/label.c:label_compound_match",
        "security/apparmor/label.c:label_compound_match",
        "security/apparmor/label.c:label_compound_match",
        "security/apparmor/label.c:label_compound_match",
        "security/apparmor/net.c:aa_profile_af_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_bind_perm",
        "security/apparmor/af_unix.c:profile_create_perm",
        "security/apparmor/af_unix.c:profile_create_perm",
        "security/apparmor/notify.c:notification_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586176784,
      "name": "aa_dfa_match_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
unsigned int aa_dfa_match_len(struct aa_dfa * dfa, unsigned int start, const char * str, int len)
```

```json
{
  "name": "aa_dfa_match_len",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586428064,
      "name": "aa_dfa_match_len",
      "external": true,
      "loc": "security/apparmor/match.c:395",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:profile_query_cb",
        "security/apparmor/apparmorfs.c:profile_query_cb",
        "security/apparmor/capability.c:profile_capable",
        "security/apparmor/task.c:aa_profile_ns_perm",
        "security/apparmor/domain.c:find_attach",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/file.c:__aa_path_perm",
        "security/apparmor/label.c:label_components_match",
        "security/apparmor/label.c:label_components_match",
        "security/apparmor/label.c:label_components_match",
        "security/apparmor/label.c:label_components_match",
        "security/apparmor/label.c:label_compound_match",
        "security/apparmor/label.c:label_compound_match",
        "security/apparmor/label.c:label_compound_match",
        "security/apparmor/label.c:label_compound_match",
        "security/apparmor/net.c:aa_profile_af_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_bind_perm",
        "security/apparmor/af_unix.c:profile_create_perm",
        "security/apparmor/af_unix.c:profile_create_perm",
        "security/apparmor/af_inet.c:aa_inet_file_perm",
        "security/apparmor/af_inet.c:inet_label_sock_perm",
        "security/apparmor/af_inet.c:aa_inet_opt_perm",
        "security/apparmor/af_inet.c:aa_inet_opt_perm",
        "security/apparmor/af_inet.c:aa_inet_opt_perm",
        "security/apparmor/af_inet.c:aa_inet_opt_perm",
        "security/apparmor/af_inet.c:aa_inet_accept_perm",
        "security/apparmor/af_inet.c:aa_inet_listen_perm",
        "security/apparmor/af_inet.c:aa_inet_listen_perm",
        "security/apparmor/af_inet.c:aa_inet_listen_perm",
        "security/apparmor/af_inet.c:aa_inet_bind_perm",
        "security/apparmor/af_inet.c:aa_inet_create_perm",
        "security/apparmor/af_inet.c:profile_remote_perm",
        "security/apparmor/af_inet.c:profile_remote_perm",
        "security/apparmor/af_inet.c:match_to_prot",
        "security/apparmor/af_inet.c:match_to_prot",
        "security/apparmor/af_inet.c:match_addr_label",
        "security/apparmor/af_inet.c:match_addr_label",
        "security/apparmor/af_inet.c:match_addr_label",
        "security/apparmor/af_inet.c:match_addr_label",
        "security/apparmor/notify.c:notification_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586428064,
      "name": "aa_dfa_match_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
unsigned int aa_dfa_match_len(struct aa_dfa * dfa, unsigned int start, const char * str, int len)
```

```json
{
  "name": "aa_dfa_match_len",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495467128,
      "name": "aa_dfa_match_len",
      "external": true,
      "loc": "security/apparmor/match.c:415",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:profile_query_cb",
        "security/apparmor/apparmorfs.c:profile_query_cb",
        "security/apparmor/apparmorfs.c:profile_query_cb",
        "security/apparmor/domain.c:aa_xattrs_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/net.c:aa_profile_af_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_bind_perm",
        "security/apparmor/af_unix.c:profile_sk_perm",
        "security/apparmor/af_unix.c:profile_create_perm",
        "security/apparmor/af_unix.c:match_addr",
        "security/apparmor/af_unix.c:match_addr",
        "security/apparmor/af_unix.c:match_to_prot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495467128,
      "name": "aa_dfa_match_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
unsigned int aa_dfa_match_len(struct aa_dfa * dfa, unsigned int start, const char * str, int len)
```

```json
{
  "name": "aa_dfa_match_len",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228833700,
      "name": "aa_dfa_match_len",
      "external": true,
      "loc": "security/apparmor/match.c:415",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:profile_query_cb",
        "security/apparmor/apparmorfs.c:profile_query_cb",
        "security/apparmor/apparmorfs.c:profile_query_cb",
        "security/apparmor/domain.c:aa_xattrs_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/net.c:aa_profile_af_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_bind_perm",
        "security/apparmor/af_unix.c:profile_sk_perm",
        "security/apparmor/af_unix.c:profile_create_perm",
        "security/apparmor/af_unix.c:profile_create_perm",
        "security/apparmor/af_unix.c:match_to_local",
        "security/apparmor/af_unix.c:match_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228833700,
      "name": "aa_dfa_match_len",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
unsigned int aa_dfa_match_len(struct aa_dfa * dfa, unsigned int start, const char * str, int len)
```

```json
{
  "name": "aa_dfa_match_len",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289520848,
      "name": "aa_dfa_match_len",
      "external": true,
      "loc": "security/apparmor/match.c:415",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:profile_query_cb",
        "security/apparmor/apparmorfs.c:profile_query_cb",
        "security/apparmor/apparmorfs.c:profile_query_cb",
        "security/apparmor/domain.c:aa_xattrs_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/net.c:aa_profile_af_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_bind_perm",
        "security/apparmor/af_unix.c:profile_sk_perm",
        "security/apparmor/af_unix.c:profile_create_perm",
        "security/apparmor/af_unix.c:profile_create_perm",
        "security/apparmor/af_unix.c:match_to_local",
        "security/apparmor/af_unix.c:match_addr",
        "security/apparmor/af_unix.c:match_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289520848,
      "name": "aa_dfa_match_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 364
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
unsigned int aa_dfa_match_len(struct aa_dfa * dfa, unsigned int start, const char * str, int len)
```

```json
{
  "name": "aa_dfa_match_len",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274654466,
      "name": "aa_dfa_match_len",
      "external": true,
      "loc": "security/apparmor/match.c:415",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:profile_query_cb",
        "security/apparmor/apparmorfs.c:profile_query_cb",
        "security/apparmor/apparmorfs.c:profile_query_cb",
        "security/apparmor/domain.c:aa_xattrs_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/net.c:aa_profile_af_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_bind_perm",
        "security/apparmor/af_unix.c:profile_sk_perm",
        "security/apparmor/af_unix.c:profile_create_perm",
        "security/apparmor/af_unix.c:match_addr",
        "security/apparmor/af_unix.c:match_addr",
        "security/apparmor/af_unix.c:match_to_prot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274654466,
      "name": "aa_dfa_match_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
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
unsigned int aa_dfa_match_len(struct aa_dfa * dfa, unsigned int start, const char * str, int len)
```

```json
{
  "name": "aa_dfa_match_len",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583641360,
      "name": "aa_dfa_match_len",
      "external": true,
      "loc": "security/apparmor/match.c:415",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:profile_query_cb",
        "security/apparmor/apparmorfs.c:profile_query_cb",
        "security/apparmor/apparmorfs.c:profile_query_cb",
        "security/apparmor/domain.c:aa_xattrs_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/net.c:aa_profile_af_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_bind_perm",
        "security/apparmor/af_unix.c:profile_sk_perm",
        "security/apparmor/af_unix.c:profile_create_perm",
        "security/apparmor/af_unix.c:profile_create_perm",
        "security/apparmor/af_unix.c:match_to_local",
        "security/apparmor/af_unix.c:match_addr",
        "security/apparmor/af_unix.c:match_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583641360,
      "name": "aa_dfa_match_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
unsigned int aa_dfa_match_len(struct aa_dfa * dfa, unsigned int start, const char * str, int len)
```

```json
{
  "name": "aa_dfa_match_len",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583578416,
      "name": "aa_dfa_match_len",
      "external": true,
      "loc": "security/apparmor/match.c:415",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:profile_query_cb",
        "security/apparmor/apparmorfs.c:profile_query_cb",
        "security/apparmor/apparmorfs.c:profile_query_cb",
        "security/apparmor/domain.c:aa_xattrs_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/net.c:aa_profile_af_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_bind_perm",
        "security/apparmor/af_unix.c:profile_sk_perm",
        "security/apparmor/af_unix.c:profile_create_perm",
        "security/apparmor/af_unix.c:profile_create_perm",
        "security/apparmor/af_unix.c:match_to_local",
        "security/apparmor/af_unix.c:match_addr",
        "security/apparmor/af_unix.c:match_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583578416,
      "name": "aa_dfa_match_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
unsigned int aa_dfa_match_len(struct aa_dfa * dfa, unsigned int start, const char * str, int len)
```

```json
{
  "name": "aa_dfa_match_len",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583625136,
      "name": "aa_dfa_match_len",
      "external": true,
      "loc": "security/apparmor/match.c:415",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:profile_query_cb",
        "security/apparmor/apparmorfs.c:profile_query_cb",
        "security/apparmor/apparmorfs.c:profile_query_cb",
        "security/apparmor/domain.c:aa_xattrs_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/net.c:aa_profile_af_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_bind_perm",
        "security/apparmor/af_unix.c:profile_sk_perm",
        "security/apparmor/af_unix.c:profile_create_perm",
        "security/apparmor/af_unix.c:profile_create_perm",
        "security/apparmor/af_unix.c:match_to_local",
        "security/apparmor/af_unix.c:match_addr",
        "security/apparmor/af_unix.c:match_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583625136,
      "name": "aa_dfa_match_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
unsigned int aa_dfa_match_len(struct aa_dfa * dfa, unsigned int start, const char * str, int len)
```

```json
{
  "name": "aa_dfa_match_len",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583723200,
      "name": "aa_dfa_match_len",
      "external": true,
      "loc": "security/apparmor/match.c:415",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:profile_query_cb",
        "security/apparmor/apparmorfs.c:profile_query_cb",
        "security/apparmor/apparmorfs.c:profile_query_cb",
        "security/apparmor/domain.c:aa_xattrs_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/net.c:aa_profile_af_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_bind_perm",
        "security/apparmor/af_unix.c:profile_sk_perm",
        "security/apparmor/af_unix.c:profile_create_perm",
        "security/apparmor/af_unix.c:profile_create_perm",
        "security/apparmor/af_unix.c:match_to_local",
        "security/apparmor/af_unix.c:match_addr",
        "security/apparmor/af_unix.c:match_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583723200,
      "name": "aa_dfa_match_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
