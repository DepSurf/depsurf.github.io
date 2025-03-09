# Function: <code>key_validate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int key_validate(const struct key * key)
```

```json
{
  "name": "key_validate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582201808,
      "name": "key_validate",
      "external": true,
      "loc": "security/keys/permission.c:89",
      "file": "security/keys/permission.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/crypto_key.c:_ext4_get_encryption_info",
        "fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/process_keys.c:search_process_keyrings",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/request_key.c:wait_for_key_construction",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582201808,
      "name": "key_validate",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int key_validate(const struct key * key)
```

```json
{
  "name": "key_validate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582418528,
      "name": "key_validate",
      "external": true,
      "loc": "security/keys/permission.c:89",
      "file": "security/keys/permission.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:search_process_keyrings",
        "security/keys/request_key.c:wait_for_key_construction",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/dh.c:mpi_from_key",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582418528,
      "name": "key_validate",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int key_validate(const struct key * key)
```

```json
{
  "name": "key_validate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582510704,
      "name": "key_validate",
      "external": true,
      "loc": "security/keys/permission.c:89",
      "file": "security/keys/permission.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:search_process_keyrings",
        "security/keys/request_key.c:wait_for_key_construction",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/dh.c:mpi_from_key",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582510704,
      "name": "key_validate",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int key_validate(const struct key * key)
```

```json
{
  "name": "key_validate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582592464,
      "name": "key_validate",
      "external": true,
      "loc": "security/keys/permission.c:89",
      "file": "security/keys/permission.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:search_process_keyrings",
        "security/keys/request_key.c:wait_for_key_construction",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/dh.c:dh_data_from_key",
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582592464,
      "name": "key_validate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
int key_validate(const struct key * key)
```

```json
{
  "name": "key_validate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582745648,
      "name": "key_validate",
      "external": true,
      "loc": "security/keys/permission.c:89",
      "file": "security/keys/permission.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:search_process_keyrings",
        "security/keys/request_key.c:wait_for_key_construction",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/dh.c:dh_data_from_key",
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582745648,
      "name": "key_validate",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int key_validate(const struct key * key)
```

```json
{
  "name": "key_validate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582945696,
      "name": "key_validate",
      "external": true,
      "loc": "security/keys/permission.c:89",
      "file": "security/keys/permission.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:search_process_keyrings",
        "security/keys/request_key.c:wait_for_key_construction",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/dh.c:dh_data_from_key",
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582945696,
      "name": "key_validate",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int key_validate(const struct key * key)
```

```json
{
  "name": "key_validate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583054800,
      "name": "key_validate",
      "external": true,
      "loc": "security/keys/permission.c:89",
      "file": "security/keys/permission.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:search_process_keyrings",
        "security/keys/request_key.c:wait_for_key_construction",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/dh.c:dh_data_from_key",
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583054800,
      "name": "key_validate",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int key_validate(const struct key * key)
```

```json
{
  "name": "key_validate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583238208,
      "name": "key_validate",
      "external": true,
      "loc": "security/keys/permission.c:85",
      "file": "security/keys/permission.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:search_process_keyrings_rcu",
        "security/keys/request_key.c:wait_for_key_construction",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/dh.c:dh_data_from_key",
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583238208,
      "name": "key_validate",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int key_validate(const struct key * key)
```

```json
{
  "name": "key_validate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583344032,
      "name": "key_validate",
      "external": true,
      "loc": "security/keys/permission.c:85",
      "file": "security/keys/permission.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:search_process_keyrings_rcu",
        "security/keys/request_key.c:wait_for_key_construction",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/dh.c:dh_data_from_key",
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583344032,
      "name": "key_validate",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int key_validate(const struct key * key)
```

```json
{
  "name": "key_validate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583678800,
      "name": "key_validate",
      "external": true,
      "loc": "security/keys/permission.c:102",
      "file": "security/keys/permission.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:search_process_keyrings_rcu",
        "security/keys/request_key.c:wait_for_key_construction",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/dh.c:dh_data_from_key",
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583678800,
      "name": "key_validate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
int key_validate(const struct key * key)
```

```json
{
  "name": "key_validate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583800304,
      "name": "key_validate",
      "external": true,
      "loc": "security/keys/permission.c:102",
      "file": "security/keys/permission.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:search_process_keyrings_rcu",
        "security/keys/request_key.c:wait_for_key_construction",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/dh.c:dh_data_from_key",
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583800304,
      "name": "key_validate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
int key_validate(const struct key * key)
```

```json
{
  "name": "key_validate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583824496,
      "name": "key_validate",
      "external": true,
      "loc": "security/keys/permission.c:102",
      "file": "security/keys/permission.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:search_process_keyrings_rcu",
        "security/keys/request_key.c:wait_for_key_construction",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/dh.c:dh_data_from_key",
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583824496,
      "name": "key_validate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
int key_validate(const struct key * key)
```

```json
{
  "name": "key_validate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584187536,
      "name": "key_validate",
      "external": true,
      "loc": "security/keys/permission.c:102",
      "file": "security/keys/permission.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:search_process_keyrings_rcu",
        "security/keys/request_key.c:wait_for_key_construction",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/dh.c:dh_data_from_key",
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584187536,
      "name": "key_validate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
int key_validate(const struct key * key)
```

```json
{
  "name": "key_validate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584788368,
      "name": "key_validate",
      "external": true,
      "loc": "security/keys/permission.c:102",
      "file": "security/keys/permission.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:search_process_keyrings_rcu",
        "security/keys/request_key.c:wait_for_key_construction",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/dh.c:dh_data_from_key",
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584788368,
      "name": "key_validate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
int key_validate(const struct key * key)
```

```json
{
  "name": "key_validate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585485648,
      "name": "key_validate",
      "external": true,
      "loc": "security/keys/permission.c:102",
      "file": "security/keys/permission.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_verify_pkcs7_signature",
        "fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:search_process_keyrings_rcu",
        "security/keys/request_key.c:wait_for_key_construction",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/dh.c:dh_data_from_key",
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585485648,
      "name": "key_validate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
int key_validate(const struct key * key)
```

```json
{
  "name": "key_validate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585717120,
      "name": "key_validate",
      "external": true,
      "loc": "security/keys/permission.c:102",
      "file": "security/keys/permission.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_verify_pkcs7_signature",
        "fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:search_process_keyrings_rcu",
        "security/keys/request_key.c:wait_for_key_construction",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/dh.c:dh_data_from_key",
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585717120,
      "name": "key_validate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
int key_validate(const struct key * key)
```

```json
{
  "name": "key_validate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585964240,
      "name": "key_validate",
      "external": true,
      "loc": "security/keys/permission.c:102",
      "file": "security/keys/permission.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_verify_pkcs7_signature",
        "fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:search_process_keyrings_rcu",
        "security/keys/request_key.c:wait_for_key_construction",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/dh.c:dh_data_from_key",
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585964240,
      "name": "key_validate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
int key_validate(const struct key * key)
```

```json
{
  "name": "key_validate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495088152,
      "name": "key_validate",
      "external": true,
      "loc": "security/keys/permission.c:85",
      "file": "security/keys/permission.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:search_process_keyrings_rcu",
        "security/keys/request_key.c:wait_for_key_construction",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/dh.c:dh_data_from_key",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495088152,
      "name": "key_validate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
int key_validate(const struct key * key)
```

```json
{
  "name": "key_validate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228481808,
      "name": "key_validate",
      "external": true,
      "loc": "security/keys/permission.c:85",
      "file": "security/keys/permission.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:search_process_keyrings_rcu",
        "security/keys/request_key.c:wait_for_key_construction",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/dh.c:dh_data_from_key",
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common",
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228481808,
      "name": "key_validate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
int key_validate(const struct key * key)
```

```json
{
  "name": "key_validate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288988224,
      "name": "key_validate",
      "external": true,
      "loc": "security/keys/permission.c:85",
      "file": "security/keys/permission.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:search_process_keyrings_rcu",
        "security/keys/request_key.c:wait_for_key_construction",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/dh.c:dh_data_from_key",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288988224,
      "name": "key_validate",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int key_validate(const struct key * key)
```

```json
{
  "name": "key_validate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274351200,
      "name": "key_validate",
      "external": true,
      "loc": "security/keys/permission.c:85",
      "file": "security/keys/permission.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:search_process_keyrings_rcu",
        "security/keys/request_key.c:wait_for_key_construction",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/dh.c:dh_data_from_key",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274351200,
      "name": "key_validate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
int key_validate(const struct key * key)
```

```json
{
  "name": "key_validate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583312768,
      "name": "key_validate",
      "external": true,
      "loc": "security/keys/permission.c:85",
      "file": "security/keys/permission.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:search_process_keyrings_rcu",
        "security/keys/request_key.c:wait_for_key_construction",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/dh.c:dh_data_from_key",
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583312768,
      "name": "key_validate",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int key_validate(const struct key * key)
```

```json
{
  "name": "key_validate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583249872,
      "name": "key_validate",
      "external": true,
      "loc": "security/keys/permission.c:85",
      "file": "security/keys/permission.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:search_process_keyrings_rcu",
        "security/keys/request_key.c:wait_for_key_construction",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/dh.c:dh_data_from_key",
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583249872,
      "name": "key_validate",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int key_validate(const struct key * key)
```

```json
{
  "name": "key_validate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583296800,
      "name": "key_validate",
      "external": true,
      "loc": "security/keys/permission.c:85",
      "file": "security/keys/permission.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:search_process_keyrings_rcu",
        "security/keys/request_key.c:wait_for_key_construction",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/dh.c:dh_data_from_key",
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583296800,
      "name": "key_validate",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int key_validate(const struct key * key)
```

```json
{
  "name": "key_validate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583391440,
      "name": "key_validate",
      "external": true,
      "loc": "security/keys/permission.c:85",
      "file": "security/keys/permission.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:search_process_keyrings_rcu",
        "security/keys/request_key.c:wait_for_key_construction",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/dh.c:dh_data_from_key",
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583391440,
      "name": "key_validate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
