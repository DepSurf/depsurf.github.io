# Function: <code>__key_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__key_get",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579509902,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:226",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:prepare_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582022800,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:226",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582188323,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:226",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/key.c:key_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582189946,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:226",
      "file": "security/keys/keyring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyring.c:keyring_gc_select_iterator",
        "security/keys/keyring.c:keyring_search_aux",
        "security/keys/keyring.c:find_key_to_update",
        "security/keys/keyring.c:__key_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582194890,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:226",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:keyctl_change_reqkey_auth"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582202576,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:226",
      "file": "security/keys/process_keys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:install_session_keyring_to_cred",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:key_change_session_keyring"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582205492,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:226",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:construct_get_dest_keyring",
        "security/keys/request_key.c:construct_get_dest_keyring",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/request_key.c:request_key_and_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582209056,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:226",
      "file": "security/keys/request_key_auth.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key_auth.c:request_key_auth_new",
        "security/keys/request_key_auth.c:request_key_auth_new"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__key_get",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579524062,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:243",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:prepare_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582235456,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:243",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582404723,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:243",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/key.c:key_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582406394,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:243",
      "file": "security/keys/keyring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyring.c:keyring_gc_select_iterator",
        "security/keys/keyring.c:__key_link",
        "security/keys/keyring.c:find_key_to_update",
        "security/keys/keyring.c:keyring_search_aux"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582411402,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:243",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:keyctl_change_reqkey_auth"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582422251,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:243",
      "file": "security/keys/process_keys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:install_session_keyring_to_cred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582424728,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:243",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/request_key.c:construct_get_dest_keyring",
        "security/keys/request_key.c:construct_get_dest_keyring",
        "security/keys/request_key.c:call_sbin_request_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582426014,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:243",
      "file": "security/keys/request_key_auth.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key_auth.c:request_key_auth_new",
        "security/keys/request_key_auth.c:request_key_auth_new"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__key_get",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579547710,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:243",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:prepare_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582324944,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:243",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582496915,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:243",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/key.c:key_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582498586,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:243",
      "file": "security/keys/keyring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyring.c:keyring_gc_select_iterator",
        "security/keys/keyring.c:__key_link",
        "security/keys/keyring.c:find_key_to_update",
        "security/keys/keyring.c:keyring_search_aux"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582503594,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:243",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:keyctl_change_reqkey_auth"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582514427,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:243",
      "file": "security/keys/process_keys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:install_session_keyring_to_cred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582516904,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:243",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/request_key.c:construct_get_dest_keyring",
        "security/keys/request_key.c:construct_get_dest_keyring",
        "security/keys/request_key.c:call_sbin_request_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582518190,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:243",
      "file": "security/keys/request_key_auth.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key_auth.c:request_key_auth_new",
        "security/keys/request_key_auth.c:request_key_auth_new"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__key_get",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579534398,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:251",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:prepare_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582409723,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:251",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582579384,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:251",
      "file": "security/keys/keyring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyring.c:keyring_gc_select_iterator",
        "security/keys/keyring.c:__key_link",
        "security/keys/keyring.c:find_key_to_update",
        "security/keys/keyring.c:keyring_search_aux"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582584986,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:251",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:keyctl_change_reqkey_auth"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582595963,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:251",
      "file": "security/keys/process_keys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:install_session_keyring_to_cred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582598300,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:251",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/request_key.c:construct_get_dest_keyring",
        "security/keys/request_key.c:construct_get_dest_keyring",
        "security/keys/request_key.c:call_sbin_request_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582599711,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:251",
      "file": "security/keys/request_key_auth.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key_auth.c:request_key_auth_new",
        "security/keys/request_key_auth.c:request_key_auth_new"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583135467,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:251",
      "file": "crypto/asymmetric_keys/restrict.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
struct key * __key_get(struct key * key)
```

```json
{
  "name": "__key_get",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579560894,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:257",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:prepare_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582560360,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:257",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582736163,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:257",
      "file": "security/keys/keyring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyring.c:keyring_gc_select_iterator",
        "security/keys/keyring.c:__key_link",
        "security/keys/keyring.c:find_key_to_update",
        "security/keys/keyring.c:keyring_search_aux"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582738282,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:257",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:keyctl_change_reqkey_auth"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582749195,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:257",
      "file": "security/keys/process_keys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:install_session_keyring_to_cred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582750688,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:257",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/request_key.c:call_sbin_request_key"
      ],
      "caller_func": [
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/request_key.c:request_key_and_link"
      ]
    },
    {
      "addr": 18446744071582753189,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:257",
      "file": "security/keys/request_key_auth.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key_auth.c:request_key_auth_new",
        "security/keys/request_key_auth.c:request_key_auth_new"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583310196,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:257",
      "file": "crypto/asymmetric_keys/restrict.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582749280,
      "name": "__key_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__key_get",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579588942,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:257",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:prepare_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582752565,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:257",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582934807,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:257",
      "file": "security/keys/keyring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyring.c:keyring_gc_select_iterator",
        "security/keys/keyring.c:__key_link",
        "security/keys/keyring.c:find_key_to_update",
        "security/keys/keyring.c:keyring_search_aux"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582937882,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:257",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:keyctl_change_reqkey_auth"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582949275,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:257",
      "file": "security/keys/process_keys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:install_session_keyring_to_cred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582950736,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:257",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/request_key.c:call_sbin_request_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582953115,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:257",
      "file": "security/keys/request_key_auth.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key_auth.c:request_key_auth_new",
        "security/keys/request_key_auth.c:request_key_auth_new"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583518644,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:257",
      "file": "crypto/asymmetric_keys/restrict.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__key_get",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579625844,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:257",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:prepare_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582856421,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:257",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583043335,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:257",
      "file": "security/keys/keyring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyring.c:keyring_gc_select_iterator",
        "security/keys/keyring.c:__key_link",
        "security/keys/keyring.c:find_key_to_update",
        "security/keys/keyring.c:keyring_search_aux"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583046426,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:257",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:keyctl_change_reqkey_auth"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583058401,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:257",
      "file": "security/keys/process_keys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:install_session_keyring_to_cred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583059906,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:257",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/request_key.c:call_sbin_request_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583062226,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:257",
      "file": "security/keys/request_key_auth.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key_auth.c:request_key_auth_new",
        "security/keys/request_key_auth.c:request_key_auth_new"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583640564,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:257",
      "file": "crypto/asymmetric_keys/restrict.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__key_get",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579651088,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:279",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:prepare_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583031224,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:279",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583223854,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:279",
      "file": "security/keys/keyring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyring.c:keyring_gc_select_iterator",
        "security/keys/keyring.c:__key_link",
        "security/keys/keyring.c:find_key_to_update",
        "security/keys/keyring.c:keyring_search_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583229482,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:279",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:keyctl_change_reqkey_auth"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583242386,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:279",
      "file": "security/keys/process_keys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:install_session_keyring_to_cred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583244097,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:279",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:construct_key_and_link",
        "security/keys/request_key.c:construct_key_and_link",
        "security/keys/request_key.c:construct_key_and_link",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/request_key.c:cache_requested_key",
        "security/keys/request_key.c:check_cached_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583246770,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:279",
      "file": "security/keys/request_key_auth.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key_auth.c:request_key_auth_new",
        "security/keys/request_key_auth.c:request_key_auth_new"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583826656,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:279",
      "file": "crypto/asymmetric_keys/restrict.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__key_get",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579688224,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:279",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:prepare_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582309986,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:279",
      "file": "fs/crypto/keysetup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583137448,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:279",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583329662,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:279",
      "file": "security/keys/keyring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyring.c:keyring_gc_select_iterator",
        "security/keys/keyring.c:__key_link",
        "security/keys/keyring.c:find_key_to_update",
        "security/keys/keyring.c:keyring_search_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583335386,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:279",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:keyctl_change_reqkey_auth"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583348210,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:279",
      "file": "security/keys/process_keys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:install_session_keyring_to_cred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583349921,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:279",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:construct_key_and_link",
        "security/keys/request_key.c:construct_key_and_link",
        "security/keys/request_key.c:construct_key_and_link",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/request_key.c:cache_requested_key",
        "security/keys/request_key.c:check_cached_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583352610,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:279",
      "file": "security/keys/request_key_auth.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key_auth.c:request_key_auth_new",
        "security/keys/request_key_auth.c:request_key_auth_new"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583928624,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:279",
      "file": "crypto/asymmetric_keys/restrict.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__key_get",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579727720,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:299",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:prepare_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582596343,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:299",
      "file": "fs/crypto/keysetup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583458318,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:299",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583663626,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:299",
      "file": "security/keys/keyring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyring.c:keyring_gc_select_iterator",
        "security/keys/keyring.c:__key_link",
        "security/keys/keyring.c:find_key_to_update",
        "security/keys/keyring.c:keyring_search_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583668246,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:299",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583683360,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:299",
      "file": "security/keys/process_keys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:install_session_keyring_to_cred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583684891,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:299",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:request_key_rcu",
        "security/keys/request_key.c:construct_get_dest_keyring",
        "security/keys/request_key.c:construct_get_dest_keyring",
        "security/keys/request_key.c:construct_get_dest_keyring",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/request_key.c:cache_requested_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583688578,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:299",
      "file": "security/keys/request_key_auth.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key_auth.c:request_key_auth_new",
        "security/keys/request_key_auth.c:request_key_auth_new"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584319981,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:299",
      "file": "crypto/asymmetric_keys/restrict.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__key_get",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579706764,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:300",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:prepare_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582667191,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:300",
      "file": "fs/crypto/keysetup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup.c:fscrypt_setup_encryption_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583570078,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:300",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583785082,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:300",
      "file": "security/keys/keyring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyring.c:keyring_gc_select_iterator",
        "security/keys/keyring.c:__key_link",
        "security/keys/keyring.c:find_key_to_update",
        "security/keys/keyring.c:keyring_search_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583789734,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:300",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583804917,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:300",
      "file": "security/keys/process_keys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:install_session_keyring_to_cred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583807783,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:300",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:construct_get_dest_keyring",
        "security/keys/request_key.c:construct_get_dest_keyring",
        "security/keys/request_key.c:construct_get_dest_keyring",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/request_key.c:cache_requested_key",
        "security/keys/request_key.c:check_cached_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583810162,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:300",
      "file": "security/keys/request_key_auth.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key_auth.c:request_key_auth_new",
        "security/keys/request_key_auth.c:request_key_auth_new"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584438253,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:300",
      "file": "crypto/asymmetric_keys/restrict.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__key_get",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579713892,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:300",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:prepare_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582696099,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:300",
      "file": "fs/crypto/keysetup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup.c:fscrypt_setup_encryption_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583593214,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:300",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583809258,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:300",
      "file": "security/keys/keyring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyring.c:keyring_gc_select_iterator",
        "security/keys/keyring.c:__key_link",
        "security/keys/keyring.c:find_key_to_update",
        "security/keys/keyring.c:keyring_search_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583813894,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:300",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583829187,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:300",
      "file": "security/keys/process_keys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:install_session_keyring_to_cred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583832051,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:300",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:construct_get_dest_keyring",
        "security/keys/request_key.c:construct_get_dest_keyring",
        "security/keys/request_key.c:construct_get_dest_keyring",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/request_key.c:cache_requested_key",
        "security/keys/request_key.c:check_cached_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583834431,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:300",
      "file": "security/keys/request_key_auth.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key_auth.c:request_key_auth_new",
        "security/keys/request_key_auth.c:request_key_auth_new"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584472941,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:300",
      "file": "crypto/asymmetric_keys/restrict.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__key_get",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579792100,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:300",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:prepare_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583022045,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:300",
      "file": "fs/crypto/keysetup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup.c:fscrypt_setup_encryption_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583951518,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:300",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584171871,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:300",
      "file": "security/keys/keyring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyring.c:keyring_gc_select_iterator",
        "security/keys/keyring.c:__key_link",
        "security/keys/keyring.c:find_key_to_update",
        "security/keys/keyring.c:keyring_search_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584177030,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:300",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584192261,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:300",
      "file": "security/keys/process_keys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:install_session_keyring_to_cred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584195171,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:300",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:construct_get_dest_keyring",
        "security/keys/request_key.c:construct_get_dest_keyring",
        "security/keys/request_key.c:construct_get_dest_keyring",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/request_key.c:cache_requested_key",
        "security/keys/request_key.c:check_cached_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584197423,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:300",
      "file": "security/keys/request_key_auth.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key_auth.c:request_key_auth_new",
        "security/keys/request_key_auth.c:request_key_auth_new"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584871037,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:300",
      "file": "crypto/asymmetric_keys/restrict.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__key_get",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579899249,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:300",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:prepare_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583494073,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:300",
      "file": "fs/crypto/keysetup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup.c:fscrypt_setup_encryption_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584533147,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:300",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584771544,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:300",
      "file": "security/keys/keyring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyring.c:keyring_gc_select_iterator",
        "security/keys/keyring.c:__key_link",
        "security/keys/keyring.c:find_key_to_update",
        "security/keys/keyring.c:keyring_search_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584777111,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:300",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:get_instantiation_keyring"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584793301,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:300",
      "file": "security/keys/process_keys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:install_session_keyring_to_cred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584796651,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:300",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:construct_get_dest_keyring",
        "security/keys/request_key.c:construct_get_dest_keyring",
        "security/keys/request_key.c:construct_get_dest_keyring",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/request_key.c:cache_requested_key",
        "security/keys/request_key.c:check_cached_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584799255,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:300",
      "file": "security/keys/request_key_auth.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key_auth.c:request_key_auth_new",
        "security/keys/request_key_auth.c:request_key_auth_new"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585566856,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:300",
      "file": "crypto/asymmetric_keys/restrict.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common"
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
  "name": "__key_get",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580051233,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:306",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:prepare_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585205929,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:306",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585467800,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:306",
      "file": "security/keys/keyring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyring.c:keyring_gc_select_iterator",
        "security/keys/keyring.c:__key_link",
        "security/keys/keyring.c:find_key_to_update",
        "security/keys/keyring.c:keyring_search_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585473703,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:306",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:get_instantiation_keyring"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585490789,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:306",
      "file": "security/keys/process_keys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:install_session_keyring_to_cred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585494299,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:306",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:construct_get_dest_keyring",
        "security/keys/request_key.c:construct_get_dest_keyring",
        "security/keys/request_key.c:construct_get_dest_keyring",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/request_key.c:cache_requested_key",
        "security/keys/request_key.c:check_cached_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585497207,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:306",
      "file": "security/keys/request_key_auth.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key_auth.c:request_key_auth_new",
        "security/keys/request_key_auth.c:request_key_auth_new"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586330840,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:306",
      "file": "crypto/asymmetric_keys/restrict.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__key_get",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580105681,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:306",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:prepare_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585434969,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:306",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585699448,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:306",
      "file": "security/keys/keyring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyring.c:keyring_gc_select_iterator",
        "security/keys/keyring.c:__key_link",
        "security/keys/keyring.c:find_key_to_update",
        "security/keys/keyring.c:keyring_search_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585705159,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:306",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:get_instantiation_keyring"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585722277,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:306",
      "file": "security/keys/process_keys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:install_session_keyring_to_cred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585725975,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:306",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:construct_get_dest_keyring",
        "security/keys/request_key.c:construct_get_dest_keyring",
        "security/keys/request_key.c:construct_get_dest_keyring",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/request_key.c:cache_requested_key",
        "security/keys/request_key.c:check_cached_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585728757,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:306",
      "file": "security/keys/request_key_auth.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key_auth.c:request_key_auth_new",
        "security/keys/request_key_auth.c:request_key_auth_new"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586577368,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:306",
      "file": "crypto/asymmetric_keys/restrict.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__key_get",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580151323,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:306",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:prepare_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585669673,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:306",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585946505,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:306",
      "file": "security/keys/keyring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyring.c:keyring_gc_select_iterator",
        "security/keys/keyring.c:__key_link",
        "security/keys/keyring.c:find_key_to_update",
        "security/keys/keyring.c:keyring_search_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585952199,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:306",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:get_instantiation_keyring"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585969425,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:306",
      "file": "security/keys/process_keys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:install_session_keyring_to_cred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585973159,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:306",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:construct_get_dest_keyring",
        "security/keys/request_key.c:construct_get_dest_keyring",
        "security/keys/request_key.c:construct_get_dest_keyring",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/request_key.c:cache_requested_key",
        "security/keys/request_key.c:check_cached_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585975987,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:306",
      "file": "security/keys/request_key_auth.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key_auth.c:request_key_auth_new",
        "security/keys/request_key_auth.c:request_key_auth_new"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586845800,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:306",
      "file": "crypto/asymmetric_keys/restrict.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "__key_get",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490864548,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:279",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:prepare_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493887848,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:279",
      "file": "fs/crypto/keysetup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494847780,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:279",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495070624,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:279",
      "file": "security/keys/keyring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyring.c:keyring_gc_select_iterator",
        "security/keys/keyring.c:__key_link",
        "security/keys/keyring.c:find_key_to_update",
        "security/keys/keyring.c:keyring_search_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495077592,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:279",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:keyctl_change_reqkey_auth"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495092304,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:279",
      "file": "security/keys/process_keys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:install_session_keyring_to_cred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495094296,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:279",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:construct_key_and_link",
        "security/keys/request_key.c:construct_key_and_link",
        "security/keys/request_key.c:construct_key_and_link",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/request_key.c:cache_requested_key",
        "security/keys/request_key.c:check_cached_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495097512,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:279",
      "file": "security/keys/request_key_auth.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key_auth.c:request_key_auth_new",
        "security/keys/request_key_auth.c:request_key_auth_new"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495747436,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:279",
      "file": "crypto/asymmetric_keys/restrict.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "__key_get",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224884248,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:279",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:prepare_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 3227368656,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:279",
      "file": "fs/crypto/keysetup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info"
      ],
      "caller_func": []
    },
    {
      "addr": 3228266368,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:279",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig"
      ],
      "caller_func": []
    },
    {
      "addr": 3228467196,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:279",
      "file": "security/keys/keyring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyring.c:keyring_gc_select_iterator",
        "security/keys/keyring.c:__key_link",
        "security/keys/keyring.c:find_key_to_update",
        "security/keys/keyring.c:keyring_search_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 3228472716,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:279",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:keyctl_change_reqkey_auth"
      ],
      "caller_func": []
    },
    {
      "addr": 3228485984,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:279",
      "file": "security/keys/process_keys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:install_session_keyring_to_cred"
      ],
      "caller_func": []
    },
    {
      "addr": 3228486780,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:279",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:construct_key_and_link",
        "security/keys/request_key.c:construct_key_and_link",
        "security/keys/request_key.c:construct_key_and_link",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/request_key.c:cache_requested_key",
        "security/keys/request_key.c:check_cached_key"
      ],
      "caller_func": []
    },
    {
      "addr": 3228490640,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:279",
      "file": "security/keys/request_key_auth.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key_auth.c:request_key_auth_new",
        "security/keys/request_key_auth.c:request_key_auth_new"
      ],
      "caller_func": []
    },
    {
      "addr": 3229100712,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:279",
      "file": "crypto/asymmetric_keys/restrict.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "__key_get",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283695232,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:279",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:prepare_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287523780,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:279",
      "file": "fs/crypto/keysetup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288699712,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:279",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288964496,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:279",
      "file": "security/keys/keyring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyring.c:keyring_gc_select_iterator",
        "security/keys/keyring.c:__key_link",
        "security/keys/keyring.c:find_key_to_update",
        "security/keys/keyring.c:keyring_search_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288975436,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:279",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:keyctl_change_reqkey_auth"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288993824,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:279",
      "file": "security/keys/process_keys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:install_session_keyring_to_cred"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288994948,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:279",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:construct_key_and_link",
        "security/keys/request_key.c:construct_key_and_link",
        "security/keys/request_key.c:construct_key_and_link",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/request_key.c:cache_requested_key",
        "security/keys/request_key.c:check_cached_key"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289000060,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:279",
      "file": "security/keys/request_key_auth.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key_auth.c:request_key_auth_new",
        "security/keys/request_key_auth.c:request_key_auth_new"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289910252,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:279",
      "file": "crypto/asymmetric_keys/restrict.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "__key_get",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271522186,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:279",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:prepare_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273448666,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:279",
      "file": "fs/crypto/keysetup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274169358,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:279",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274337750,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:279",
      "file": "security/keys/keyring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyring.c:keyring_gc_select_iterator",
        "security/keys/keyring.c:__key_link",
        "security/keys/keyring.c:find_key_to_update",
        "security/keys/keyring.c:keyring_search_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274343832,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:279",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:keyctl_change_reqkey_auth"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274354656,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:279",
      "file": "security/keys/process_keys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:install_session_keyring_to_cred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274355178,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:279",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:request_key_rcu",
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/request_key.c:construct_key_and_link",
        "security/keys/request_key.c:construct_key_and_link",
        "security/keys/request_key.c:construct_key_and_link",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/request_key.c:check_cached_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274358586,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:279",
      "file": "security/keys/request_key_auth.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key_auth.c:request_key_auth_new",
        "security/keys/request_key_auth.c:request_key_auth_new"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274895958,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:279",
      "file": "crypto/asymmetric_keys/restrict.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__key_get",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579664544,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:279",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:prepare_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582278722,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:279",
      "file": "fs/crypto/keysetup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583106184,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:279",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583298398,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:279",
      "file": "security/keys/keyring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyring.c:keyring_gc_select_iterator",
        "security/keys/keyring.c:__key_link",
        "security/keys/keyring.c:find_key_to_update",
        "security/keys/keyring.c:keyring_search_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583304122,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:279",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:keyctl_change_reqkey_auth"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583316946,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:279",
      "file": "security/keys/process_keys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:install_session_keyring_to_cred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583318657,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:279",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:construct_key_and_link",
        "security/keys/request_key.c:construct_key_and_link",
        "security/keys/request_key.c:construct_key_and_link",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/request_key.c:cache_requested_key",
        "security/keys/request_key.c:check_cached_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583321346,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:279",
      "file": "security/keys/request_key_auth.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key_auth.c:request_key_auth_new",
        "security/keys/request_key_auth.c:request_key_auth_new"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583897360,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:279",
      "file": "crypto/asymmetric_keys/restrict.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__key_get",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579592896,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:279",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:prepare_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582216482,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:279",
      "file": "fs/crypto/keysetup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583043336,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:279",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583235534,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:279",
      "file": "security/keys/keyring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyring.c:keyring_gc_select_iterator",
        "security/keys/keyring.c:__key_link",
        "security/keys/keyring.c:find_key_to_update",
        "security/keys/keyring.c:keyring_search_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583241258,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:279",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:keyctl_change_reqkey_auth"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583254050,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:279",
      "file": "security/keys/process_keys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:install_session_keyring_to_cred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583255761,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:279",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:construct_key_and_link",
        "security/keys/request_key.c:construct_key_and_link",
        "security/keys/request_key.c:construct_key_and_link",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/request_key.c:cache_requested_key",
        "security/keys/request_key.c:check_cached_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583258450,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:279",
      "file": "security/keys/request_key_auth.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key_auth.c:request_key_auth_new",
        "security/keys/request_key_auth.c:request_key_auth_new"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583834416,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:279",
      "file": "crypto/asymmetric_keys/restrict.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__key_get",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579661808,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:279",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:prepare_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582269202,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:279",
      "file": "fs/crypto/keysetup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583094792,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:279",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583282430,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:279",
      "file": "security/keys/keyring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyring.c:keyring_gc_select_iterator",
        "security/keys/keyring.c:__key_link",
        "security/keys/keyring.c:find_key_to_update",
        "security/keys/keyring.c:keyring_search_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583288154,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:279",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:keyctl_change_reqkey_auth"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583300978,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:279",
      "file": "security/keys/process_keys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:install_session_keyring_to_cred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583302465,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:279",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:construct_key_and_link",
        "security/keys/request_key.c:construct_key_and_link",
        "security/keys/request_key.c:construct_key_and_link",
        "security/keys/request_key.c:call_sbin_request_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583305122,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:279",
      "file": "security/keys/request_key_auth.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key_auth.c:request_key_auth_new",
        "security/keys/request_key_auth.c:request_key_auth_new"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583881120,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:279",
      "file": "crypto/asymmetric_keys/restrict.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__key_get",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579695808,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:279",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:prepare_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582347762,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:279",
      "file": "fs/crypto/keysetup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583183992,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:279",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583376974,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:279",
      "file": "security/keys/keyring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyring.c:keyring_gc_select_iterator",
        "security/keys/keyring.c:__key_link",
        "security/keys/keyring.c:find_key_to_update",
        "security/keys/keyring.c:keyring_search_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583382762,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:279",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:keyctl_change_reqkey_auth"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583395618,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:279",
      "file": "security/keys/process_keys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:install_session_keyring_to_cred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583397314,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:279",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:construct_key_and_link",
        "security/keys/request_key.c:construct_key_and_link",
        "security/keys/request_key.c:construct_key_and_link",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/request_key.c:cache_requested_key",
        "security/keys/request_key.c:check_cached_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583400082,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:279",
      "file": "security/keys/request_key_auth.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key_auth.c:request_key_auth_new",
        "security/keys/request_key_auth.c:request_key_auth_new"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583982192,
      "name": "__key_get",
      "external": false,
      "loc": "include/linux/key.h:279",
      "file": "crypto/asymmetric_keys/restrict.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
struct key * __key_get(struct key * key)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
struct key * __key_get(struct key * key)
```
</details>
</li>
</ul>
