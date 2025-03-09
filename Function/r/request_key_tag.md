# Function: <code>request_key_tag</code>

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
struct key * request_key_tag(struct key_type * type, const char * description, struct key_tag * domain_tag, const char * callout_info)
```

```json
{
  "name": "request_key_tag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583245728,
      "name": "request_key_tag",
      "external": true,
      "loc": "security/keys/request_key.c:690",
      "file": "security/keys/request_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyinfo.c:find_and_lock_process_key",
        "fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig",
        "fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig",
        "security/keys/encrypted-keys/masterkey_trusted.c:request_trusted_key",
        "security/integrity/digsig.c:integrity_digsig_verify",
        "security/integrity/digsig_asymmetric.c:asymmetric_verify",
        "security/integrity/evm/evm_crypto.c:evm_init_key",
        "lib/digsig.c:digsig_verify",
        "drivers/nvdimm/security.c:nvdimm_request_key",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583245728,
      "name": "request_key_tag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
struct key * request_key_tag(struct key_type * type, const char * description, struct key_tag * domain_tag, const char * callout_info)
```

```json
{
  "name": "request_key_tag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583351552,
      "name": "request_key_tag",
      "external": true,
      "loc": "security/keys/request_key.c:690",
      "file": "security/keys/request_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup_v1.c:find_and_lock_process_key",
        "fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig",
        "fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig",
        "security/keys/encrypted-keys/masterkey_trusted.c:request_trusted_key",
        "security/integrity/digsig_asymmetric.c:asymmetric_verify",
        "security/integrity/evm/evm_crypto.c:evm_init_key",
        "lib/digsig.c:digsig_verify",
        "drivers/nvdimm/security.c:nvdimm_request_key",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583351552,
      "name": "request_key_tag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
struct key * request_key_tag(struct key_type * type, const char * description, struct key_tag * domain_tag, const char * callout_info)
```

```json
{
  "name": "request_key_tag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583687600,
      "name": "request_key_tag",
      "external": true,
      "loc": "security/keys/request_key.c:690",
      "file": "security/keys/request_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup_v1.c:find_and_lock_process_key",
        "fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig",
        "fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig",
        "security/keys/encrypted-keys/encrypted.c:request_master_key",
        "security/keys/encrypted-keys/masterkey_trusted.c:request_trusted_key",
        "security/integrity/digsig_asymmetric.c:request_asymmetric_key",
        "security/integrity/evm/evm_crypto.c:evm_init_key",
        "lib/digsig.c:digsig_verify",
        "drivers/nvdimm/security.c:nvdimm_request_key",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583687600,
      "name": "request_key_tag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
struct key * request_key_tag(struct key_type * type, const char * description, struct key_tag * domain_tag, const char * callout_info)
```

```json
{
  "name": "request_key_tag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583809184,
      "name": "request_key_tag",
      "external": true,
      "loc": "security/keys/request_key.c:690",
      "file": "security/keys/request_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup_v1.c:find_and_lock_process_key",
        "fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig",
        "fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig",
        "security/keys/encrypted-keys/encrypted.c:request_master_key",
        "security/keys/encrypted-keys/masterkey_trusted.c:request_trusted_key",
        "security/integrity/digsig_asymmetric.c:request_asymmetric_key",
        "security/integrity/evm/evm_crypto.c:evm_init_key",
        "lib/digsig.c:digsig_verify",
        "drivers/nvdimm/security.c:nvdimm_request_key",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583809184,
      "name": "request_key_tag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
struct key * request_key_tag(struct key_type * type, const char * description, struct key_tag * domain_tag, const char * callout_info)
```

```json
{
  "name": "request_key_tag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583833456,
      "name": "request_key_tag",
      "external": true,
      "loc": "security/keys/request_key.c:690",
      "file": "security/keys/request_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup_v1.c:find_and_lock_process_key",
        "fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig",
        "fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig",
        "security/keys/encrypted-keys/encrypted.c:request_master_key",
        "security/keys/encrypted-keys/masterkey_trusted.c:request_trusted_key",
        "security/integrity/digsig_asymmetric.c:request_asymmetric_key",
        "security/integrity/evm/evm_crypto.c:evm_init_key",
        "lib/digsig.c:digsig_verify",
        "drivers/nvdimm/security.c:nvdimm_request_key",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583833456,
      "name": "request_key_tag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
struct key * request_key_tag(struct key_type * type, const char * description, struct key_tag * domain_tag, const char * callout_info)
```

```json
{
  "name": "request_key_tag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584196448,
      "name": "request_key_tag",
      "external": true,
      "loc": "security/keys/request_key.c:690",
      "file": "security/keys/request_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup_v1.c:find_and_lock_process_key",
        "fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig",
        "fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig",
        "security/keys/encrypted-keys/encrypted.c:request_master_key",
        "security/keys/encrypted-keys/masterkey_trusted.c:request_trusted_key",
        "security/integrity/digsig_asymmetric.c:request_asymmetric_key",
        "security/integrity/evm/evm_crypto.c:evm_init_key",
        "lib/digsig.c:digsig_verify",
        "drivers/nvdimm/security.c:nvdimm_request_key",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584196448,
      "name": "request_key_tag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
struct key * request_key_tag(struct key_type * type, const char * description, struct key_tag * domain_tag, const char * callout_info)
```

```json
{
  "name": "request_key_tag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584798000,
      "name": "request_key_tag",
      "external": true,
      "loc": "security/keys/request_key.c:690",
      "file": "security/keys/request_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup_v1.c:find_and_lock_process_key",
        "fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig",
        "fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig",
        "security/keys/encrypted-keys/encrypted.c:request_master_key",
        "security/keys/encrypted-keys/masterkey_trusted.c:request_trusted_key",
        "security/integrity/digsig_asymmetric.c:request_asymmetric_key",
        "security/integrity/evm/evm_crypto.c:evm_init_key",
        "lib/digsig.c:digsig_verify",
        "drivers/nvdimm/security.c:nvdimm_request_key",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584798000,
      "name": "request_key_tag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
struct key * request_key_tag(struct key_type * type, const char * description, struct key_tag * domain_tag, const char * callout_info)
```

```json
{
  "name": "request_key_tag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585495776,
      "name": "request_key_tag",
      "external": true,
      "loc": "security/keys/request_key.c:690",
      "file": "security/keys/request_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup_v1.c:find_and_lock_process_key",
        "fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig",
        "fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig",
        "security/keys/encrypted-keys/encrypted.c:request_master_key",
        "security/keys/encrypted-keys/masterkey_trusted.c:request_trusted_key",
        "security/integrity/digsig_asymmetric.c:request_asymmetric_key",
        "security/integrity/evm/evm_crypto.c:evm_init_key",
        "lib/digsig.c:digsig_verify",
        "drivers/nvdimm/security.c:nvdimm_request_key",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585495776,
      "name": "request_key_tag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
struct key * request_key_tag(struct key_type * type, const char * description, struct key_tag * domain_tag, const char * callout_info)
```

```json
{
  "name": "request_key_tag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585727328,
      "name": "request_key_tag",
      "external": true,
      "loc": "security/keys/request_key.c:706",
      "file": "security/keys/request_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup_v1.c:find_and_lock_process_key",
        "fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig",
        "fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig",
        "security/keys/encrypted-keys/encrypted.c:request_master_key",
        "security/keys/encrypted-keys/masterkey_trusted.c:request_trusted_key",
        "security/integrity/digsig_asymmetric.c:request_asymmetric_key",
        "security/integrity/evm/evm_crypto.c:evm_init_key",
        "lib/digsig.c:digsig_verify",
        "drivers/nvdimm/security.c:nvdimm_request_key",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585727328,
      "name": "request_key_tag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
struct key * request_key_tag(struct key_type * type, const char * description, struct key_tag * domain_tag, const char * callout_info)
```

```json
{
  "name": "request_key_tag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585974512,
      "name": "request_key_tag",
      "external": true,
      "loc": "security/keys/request_key.c:706",
      "file": "security/keys/request_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup_v1.c:find_and_lock_process_key",
        "fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig",
        "fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig",
        "security/keys/encrypted-keys/encrypted.c:request_master_key",
        "security/keys/encrypted-keys/masterkey_trusted.c:request_trusted_key",
        "security/integrity/digsig_asymmetric.c:request_asymmetric_key",
        "security/integrity/evm/evm_crypto.c:evm_init_key",
        "lib/digsig.c:digsig_verify",
        "drivers/nvdimm/security.c:nvdimm_request_key",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585974512,
      "name": "request_key_tag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
struct key * request_key_tag(struct key_type * type, const char * description, struct key_tag * domain_tag, const char * callout_info)
```

```json
{
  "name": "request_key_tag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495095784,
      "name": "request_key_tag",
      "external": true,
      "loc": "security/keys/request_key.c:690",
      "file": "security/keys/request_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup_v1.c:find_and_lock_process_key",
        "fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig",
        "fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig",
        "security/keys/encrypted-keys/masterkey_trusted.c:request_trusted_key",
        "security/integrity/digsig_asymmetric.c:asymmetric_verify",
        "security/integrity/evm/evm_crypto.c:evm_init_key",
        "lib/digsig.c:digsig_verify",
        "drivers/nvdimm/security.c:nvdimm_request_key",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495095784,
      "name": "request_key_tag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
struct key * request_key_tag(struct key_type * type, const char * description, struct key_tag * domain_tag, const char * callout_info)
```

```json
{
  "name": "request_key_tag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228489336,
      "name": "request_key_tag",
      "external": true,
      "loc": "security/keys/request_key.c:690",
      "file": "security/keys/request_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup_v1.c:find_and_lock_process_key",
        "fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig",
        "fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig",
        "security/keys/encrypted-keys/encrypted.c:request_master_key",
        "security/keys/encrypted-keys/masterkey_trusted.c:request_trusted_key",
        "security/integrity/digsig_asymmetric.c:asymmetric_verify",
        "security/integrity/evm/evm_crypto.c:evm_init_key",
        "lib/digsig.c:digsig_verify",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228489336,
      "name": "request_key_tag",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct key * request_key_tag(struct key_type * type, const char * description, struct key_tag * domain_tag, const char * callout_info)
```

```json
{
  "name": "request_key_tag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288998352,
      "name": "request_key_tag",
      "external": true,
      "loc": "security/keys/request_key.c:690",
      "file": "security/keys/request_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup_v1.c:find_and_lock_process_key",
        "fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig",
        "fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig",
        "security/keys/encrypted-keys/masterkey_trusted.c:request_trusted_key",
        "security/integrity/digsig_asymmetric.c:asymmetric_verify",
        "security/integrity/evm/evm_crypto.c:evm_init_key",
        "lib/digsig.c:digsig_verify",
        "drivers/nvdimm/security.c:nvdimm_request_key",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288998352,
      "name": "request_key_tag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
struct key * request_key_tag(struct key_type * type, const char * description, struct key_tag * domain_tag, const char * callout_info)
```

```json
{
  "name": "request_key_tag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274357504,
      "name": "request_key_tag",
      "external": true,
      "loc": "security/keys/request_key.c:690",
      "file": "security/keys/request_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup_v1.c:find_and_lock_process_key",
        "fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig",
        "fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig",
        "security/keys/encrypted-keys/masterkey_trusted.c:request_trusted_key",
        "security/integrity/digsig_asymmetric.c:asymmetric_verify",
        "security/integrity/evm/evm_crypto.c:evm_init_key",
        "lib/digsig.c:digsig_verify",
        "drivers/nvdimm/security.c:nvdimm_request_key",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274357504,
      "name": "request_key_tag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
struct key * request_key_tag(struct key_type * type, const char * description, struct key_tag * domain_tag, const char * callout_info)
```

```json
{
  "name": "request_key_tag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583320288,
      "name": "request_key_tag",
      "external": true,
      "loc": "security/keys/request_key.c:690",
      "file": "security/keys/request_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup_v1.c:find_and_lock_process_key",
        "fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig",
        "fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig",
        "security/keys/encrypted-keys/masterkey_trusted.c:request_trusted_key",
        "security/integrity/digsig_asymmetric.c:asymmetric_verify",
        "security/integrity/evm/evm_crypto.c:evm_init_key",
        "lib/digsig.c:digsig_verify",
        "drivers/nvdimm/security.c:nvdimm_request_key",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583320288,
      "name": "request_key_tag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
struct key * request_key_tag(struct key_type * type, const char * description, struct key_tag * domain_tag, const char * callout_info)
```

```json
{
  "name": "request_key_tag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583257392,
      "name": "request_key_tag",
      "external": true,
      "loc": "security/keys/request_key.c:690",
      "file": "security/keys/request_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup_v1.c:find_and_lock_process_key",
        "fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig",
        "fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig",
        "security/keys/encrypted-keys/masterkey_trusted.c:request_trusted_key",
        "security/integrity/digsig_asymmetric.c:asymmetric_verify",
        "security/integrity/evm/evm_crypto.c:evm_init_key",
        "lib/digsig.c:digsig_verify",
        "drivers/nvdimm/security.c:nvdimm_request_key",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583257392,
      "name": "request_key_tag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
struct key * request_key_tag(struct key_type * type, const char * description, struct key_tag * domain_tag, const char * callout_info)
```

```json
{
  "name": "request_key_tag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583304064,
      "name": "request_key_tag",
      "external": true,
      "loc": "security/keys/request_key.c:690",
      "file": "security/keys/request_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup_v1.c:find_and_lock_process_key",
        "fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig",
        "fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig",
        "security/keys/encrypted-keys/masterkey_trusted.c:request_trusted_key",
        "security/integrity/digsig_asymmetric.c:asymmetric_verify",
        "security/integrity/evm/evm_crypto.c:evm_init_key",
        "lib/digsig.c:digsig_verify",
        "drivers/nvdimm/security.c:nvdimm_request_key",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583304064,
      "name": "request_key_tag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
struct key * request_key_tag(struct key_type * type, const char * description, struct key_tag * domain_tag, const char * callout_info)
```

```json
{
  "name": "request_key_tag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583399024,
      "name": "request_key_tag",
      "external": true,
      "loc": "security/keys/request_key.c:690",
      "file": "security/keys/request_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup_v1.c:find_and_lock_process_key",
        "fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig",
        "fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig",
        "security/keys/encrypted-keys/masterkey_trusted.c:request_trusted_key",
        "security/integrity/digsig_asymmetric.c:asymmetric_verify",
        "security/integrity/evm/evm_crypto.c:evm_init_key",
        "lib/digsig.c:digsig_verify",
        "drivers/nvdimm/security.c:nvdimm_request_key",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583399024,
      "name": "request_key_tag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
struct key * request_key_tag(struct key_type * type, const char * description, struct key_tag * domain_tag, const char * callout_info)
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
