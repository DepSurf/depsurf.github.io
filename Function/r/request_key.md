# Function: <code>request_key</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct key * request_key(struct key_type * type, const char * description, const char * callout_info)
```

```json
{
  "name": "request_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582208064,
      "name": "request_key",
      "external": true,
      "loc": "security/keys/request_key.c:619",
      "file": "security/keys/request_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/crypto_key.c:_ext4_get_encryption_info",
        "fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig",
        "fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig",
        "security/keys/encrypted-keys/masterkey_trusted.c:request_trusted_key",
        "security/integrity/digsig.c:integrity_digsig_verify",
        "security/integrity/digsig_asymmetric.c:asymmetric_verify",
        "security/integrity/evm/evm_crypto.c:evm_init_key",
        "lib/digsig.c:digsig_verify",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582208064,
      "name": "request_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
struct key * request_key(struct key_type * type, const char * description, const char * callout_info)
```

```json
{
  "name": "request_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582425024,
      "name": "request_key",
      "external": true,
      "loc": "security/keys/request_key.c:619",
      "file": "security/keys/request_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig",
        "fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig",
        "security/keys/encrypted-keys/masterkey_trusted.c:request_trusted_key",
        "security/integrity/digsig.c:integrity_digsig_verify",
        "security/integrity/digsig_asymmetric.c:asymmetric_verify",
        "security/integrity/evm/evm_crypto.c:evm_init_key",
        "lib/digsig.c:digsig_verify",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582425024,
      "name": "request_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
struct key * request_key(struct key_type * type, const char * description, const char * callout_info)
```

```json
{
  "name": "request_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582517200,
      "name": "request_key",
      "external": true,
      "loc": "security/keys/request_key.c:619",
      "file": "security/keys/request_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig",
        "fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig",
        "security/keys/encrypted-keys/masterkey_trusted.c:request_trusted_key",
        "security/integrity/digsig.c:integrity_digsig_verify",
        "security/integrity/digsig_asymmetric.c:asymmetric_verify",
        "security/integrity/evm/evm_crypto.c:evm_init_key",
        "lib/digsig.c:digsig_verify",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582517200,
      "name": "request_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
struct key * request_key(struct key_type * type, const char * description, const char * callout_info)
```

```json
{
  "name": "request_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582598720,
      "name": "request_key",
      "external": true,
      "loc": "security/keys/request_key.c:620",
      "file": "security/keys/request_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig",
        "fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig",
        "security/keys/encrypted-keys/masterkey_trusted.c:request_trusted_key",
        "security/integrity/digsig.c:integrity_digsig_verify",
        "security/integrity/digsig_asymmetric.c:asymmetric_verify",
        "security/integrity/evm/evm_crypto.c:evm_init_key",
        "lib/digsig.c:digsig_verify",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582598720,
      "name": "request_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
struct key * request_key(struct key_type * type, const char * description, const char * callout_info)
```

```json
{
  "name": "request_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582752160,
      "name": "request_key",
      "external": true,
      "loc": "security/keys/request_key.c:645",
      "file": "security/keys/request_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig",
        "fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig",
        "security/keys/encrypted-keys/masterkey_trusted.c:request_trusted_key",
        "security/integrity/digsig.c:integrity_digsig_verify",
        "security/integrity/digsig_asymmetric.c:asymmetric_verify",
        "security/integrity/evm/evm_crypto.c:evm_init_key",
        "lib/digsig.c:digsig_verify",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582752160,
      "name": "request_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
struct key * request_key(struct key_type * type, const char * description, const char * callout_info)
```

```json
{
  "name": "request_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582952144,
      "name": "request_key",
      "external": true,
      "loc": "security/keys/request_key.c:645",
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
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582952144,
      "name": "request_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
struct key * request_key(struct key_type * type, const char * description, const char * callout_info)
```

```json
{
  "name": "request_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583061232,
      "name": "request_key",
      "external": true,
      "loc": "security/keys/request_key.c:632",
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
      "addr": 18446744071583061232,
      "name": "request_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "request_key",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582220539,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:319",
      "file": "fs/crypto/keyinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keyinfo.c:find_and_lock_process_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583035205,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:319",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig",
        "fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583267975,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:319",
      "file": "security/keys/encrypted-keys/encrypted.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583273349,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:319",
      "file": "security/keys/encrypted-keys/masterkey_trusted.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/encrypted-keys/masterkey_trusted.c:request_trusted_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583672860,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:319",
      "file": "security/integrity/digsig.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/digsig.c:integrity_digsig_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583673330,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:319",
      "file": "security/integrity/digsig_asymmetric.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/digsig_asymmetric.c:asymmetric_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583705253,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:319",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/evm/evm_crypto.c:evm_init_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584322280,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:319",
      "file": "lib/digsig.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/digsig.c:digsig_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586437602,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:319",
      "file": "drivers/nvdimm/security.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/security.c:nvdimm_request_key"
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
  "name": "request_key",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582310827,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:319",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup_v1.c:find_and_lock_process_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583141429,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:319",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig",
        "fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583373751,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:319",
      "file": "security/keys/encrypted-keys/encrypted.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583379445,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:319",
      "file": "security/keys/encrypted-keys/masterkey_trusted.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/encrypted-keys/masterkey_trusted.c:request_trusted_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583779743,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:319",
      "file": "security/integrity/digsig.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583780418,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:319",
      "file": "security/integrity/digsig_asymmetric.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/digsig_asymmetric.c:asymmetric_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583815029,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:319",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/evm/evm_crypto.c:evm_init_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584456968,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:319",
      "file": "lib/digsig.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/digsig.c:digsig_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586584674,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:319",
      "file": "drivers/nvdimm/security.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/security.c:nvdimm_request_key"
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
  "name": "request_key",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582597259,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:339",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup_v1.c:find_and_lock_process_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583465477,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:339",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig",
        "fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583711048,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:339",
      "file": "security/keys/encrypted-keys/encrypted.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/encrypted-keys/encrypted.c:request_master_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583717509,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:339",
      "file": "security/keys/encrypted-keys/masterkey_trusted.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/encrypted-keys/masterkey_trusted.c:request_trusted_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584170223,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:339",
      "file": "security/integrity/digsig.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584170693,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:339",
      "file": "security/integrity/digsig_asymmetric.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/digsig_asymmetric.c:request_asymmetric_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584210501,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:339",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/evm/evm_crypto.c:evm_init_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585020477,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:339",
      "file": "lib/digsig.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/digsig.c:digsig_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587370226,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:339",
      "file": "drivers/nvdimm/security.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/security.c:nvdimm_request_key"
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
  "name": "request_key",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582668107,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:340",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup_v1.c:find_and_lock_process_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583577232,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:340",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig",
        "fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583831912,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:340",
      "file": "security/keys/encrypted-keys/encrypted.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/encrypted-keys/encrypted.c:request_master_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583837685,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:340",
      "file": "security/keys/encrypted-keys/masterkey_trusted.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/encrypted-keys/masterkey_trusted.c:request_trusted_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584289391,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:340",
      "file": "security/integrity/digsig.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584289837,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:340",
      "file": "security/integrity/digsig_asymmetric.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/digsig_asymmetric.c:request_asymmetric_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584328901,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:340",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/evm/evm_crypto.c:evm_init_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585169101,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:340",
      "file": "lib/digsig.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/digsig.c:digsig_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587430914,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:340",
      "file": "drivers/nvdimm/security.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/security.c:nvdimm_request_key"
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
  "name": "request_key",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582697003,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:340",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup_v1.c:find_and_lock_process_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583600416,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:340",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig",
        "fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583857720,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:340",
      "file": "security/keys/encrypted-keys/encrypted.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/encrypted-keys/encrypted.c:request_master_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583863397,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:340",
      "file": "security/keys/encrypted-keys/masterkey_trusted.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/encrypted-keys/masterkey_trusted.c:request_trusted_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584323231,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:340",
      "file": "security/integrity/digsig.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584323677,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:340",
      "file": "security/integrity/digsig_asymmetric.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/digsig_asymmetric.c:request_asymmetric_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584363429,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:340",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/evm/evm_crypto.c:evm_init_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585049565,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:340",
      "file": "lib/digsig.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/digsig.c:digsig_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587312786,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:340",
      "file": "drivers/nvdimm/security.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/security.c:nvdimm_request_key"
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
  "name": "request_key",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583023003,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:340",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup_v1.c:find_and_lock_process_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583958816,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:340",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig",
        "fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584220968,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:340",
      "file": "security/keys/encrypted-keys/encrypted.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/encrypted-keys/encrypted.c:request_master_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584226645,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:340",
      "file": "security/keys/encrypted-keys/masterkey_trusted.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/encrypted-keys/masterkey_trusted.c:request_trusted_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584710417,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:340",
      "file": "security/integrity/digsig.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584711079,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:340",
      "file": "security/integrity/digsig_asymmetric.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/digsig_asymmetric.c:request_asymmetric_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584758485,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:340",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/evm/evm_crypto.c:evm_init_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585493213,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:340",
      "file": "lib/digsig.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/digsig.c:digsig_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587879634,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:340",
      "file": "drivers/nvdimm/security.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/security.c:nvdimm_request_key"
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
  "name": "request_key",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583495068,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:340",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup_v1.c:find_and_lock_process_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584540848,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:340",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig",
        "fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584824916,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:340",
      "file": "security/keys/encrypted-keys/encrypted.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/encrypted-keys/encrypted.c:request_master_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584831397,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:340",
      "file": "security/keys/encrypted-keys/masterkey_trusted.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/encrypted-keys/masterkey_trusted.c:request_trusted_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585384237,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:340",
      "file": "security/integrity/digsig.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585385013,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:340",
      "file": "security/integrity/digsig_asymmetric.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/digsig_asymmetric.c:request_asymmetric_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585440741,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:340",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/evm/evm_crypto.c:evm_init_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586638120,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:340",
      "file": "lib/digsig.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/digsig.c:digsig_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589229872,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:340",
      "file": "drivers/nvdimm/security.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/security.c:nvdimm_request_key"
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
  "name": "request_key",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584090844,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:346",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup_v1.c:find_and_lock_process_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585215264,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:346",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig",
        "fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585524612,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:346",
      "file": "security/keys/encrypted-keys/encrypted.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/encrypted-keys/encrypted.c:request_master_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585531957,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:346",
      "file": "security/keys/encrypted-keys/masterkey_trusted.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/encrypted-keys/masterkey_trusted.c:request_trusted_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586135965,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:346",
      "file": "security/integrity/digsig.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586136835,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:346",
      "file": "security/integrity/digsig_asymmetric.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/digsig_asymmetric.c:request_asymmetric_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586198773,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:346",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/evm/evm_crypto.c:evm_init_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587881496,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:346",
      "file": "lib/digsig.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/digsig.c:digsig_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590786912,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:346",
      "file": "drivers/nvdimm/security.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/security.c:nvdimm_request_key"
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
  "name": "request_key",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584317804,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:346",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup_v1.c:find_and_lock_process_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585444720,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:346",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig",
        "fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585756372,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:346",
      "file": "security/keys/encrypted-keys/encrypted.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/encrypted-keys/encrypted.c:request_master_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585763701,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:346",
      "file": "security/keys/encrypted-keys/masterkey_trusted.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/encrypted-keys/masterkey_trusted.c:request_trusted_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586373840,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:346",
      "file": "security/integrity/digsig.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586374661,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:346",
      "file": "security/integrity/digsig_asymmetric.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/digsig_asymmetric.c:request_asymmetric_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586436389,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:346",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/evm/evm_crypto.c:evm_init_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588153304,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:346",
      "file": "lib/digsig.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/digsig.c:digsig_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591128416,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:346",
      "file": "drivers/nvdimm/security.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/security.c:nvdimm_request_key"
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
  "name": "request_key",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584535228,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:346",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup_v1.c:find_and_lock_process_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585679424,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:346",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig",
        "fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586003796,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:346",
      "file": "security/keys/encrypted-keys/encrypted.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/encrypted-keys/encrypted.c:request_master_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586011173,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:346",
      "file": "security/keys/encrypted-keys/masterkey_trusted.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/encrypted-keys/masterkey_trusted.c:request_trusted_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586638384,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:346",
      "file": "security/integrity/digsig.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586639205,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:346",
      "file": "security/integrity/digsig_asymmetric.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/digsig_asymmetric.c:request_asymmetric_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586702165,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:346",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/evm/evm_crypto.c:evm_init_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588442904,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:346",
      "file": "lib/digsig.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/digsig.c:digsig_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591474096,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:346",
      "file": "drivers/nvdimm/security.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/security.c:nvdimm_request_key"
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
  "name": "request_key",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493888596,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:319",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup_v1.c:find_and_lock_process_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494851660,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:319",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig",
        "fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495122968,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:319",
      "file": "security/keys/encrypted-keys/encrypted.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336495128292,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:319",
      "file": "security/keys/encrypted-keys/masterkey_trusted.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/encrypted-keys/masterkey_trusted.c:request_trusted_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495582508,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:319",
      "file": "security/integrity/digsig.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336495583244,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:319",
      "file": "security/integrity/digsig_asymmetric.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/digsig_asymmetric.c:asymmetric_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495621268,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:319",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/evm/evm_crypto.c:evm_init_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496343300,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:319",
      "file": "lib/digsig.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/digsig.c:digsig_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499468168,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:319",
      "file": "drivers/nvdimm/security.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/security.c:nvdimm_request_key"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "request_key",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227369232,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:319",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup_v1.c:find_and_lock_process_key"
      ],
      "caller_func": []
    },
    {
      "addr": 3228270020,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:319",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig",
        "fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig"
      ],
      "caller_func": []
    },
    {
      "addr": 3228510116,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:319",
      "file": "security/keys/encrypted-keys/encrypted.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/encrypted-keys/encrypted.c:request_master_key"
      ],
      "caller_func": []
    },
    {
      "addr": 3228515984,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:319",
      "file": "security/keys/encrypted-keys/masterkey_trusted.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/encrypted-keys/masterkey_trusted.c:request_trusted_key"
      ],
      "caller_func": []
    },
    {
      "addr": 3228943836,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:319",
      "file": "security/integrity/digsig.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3228944532,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:319",
      "file": "security/integrity/digsig_asymmetric.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/digsig_asymmetric.c:asymmetric_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 3228980408,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:319",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/evm/evm_crypto.c:evm_init_key"
      ],
      "caller_func": []
    },
    {
      "addr": 3229676900,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:319",
      "file": "lib/digsig.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/digsig.c:digsig_verify"
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
  "name": "request_key",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287524416,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:319",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup_v1.c:find_and_lock_process_key"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288704508,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:319",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig",
        "fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289029824,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:319",
      "file": "security/keys/encrypted-keys/encrypted.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055289037176,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:319",
      "file": "security/keys/encrypted-keys/masterkey_trusted.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/encrypted-keys/masterkey_trusted.c:request_trusted_key"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289680404,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:319",
      "file": "security/integrity/digsig.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055289681416,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:319",
      "file": "security/integrity/digsig_asymmetric.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/digsig_asymmetric.c:asymmetric_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289742528,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:319",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/evm/evm_crypto.c:evm_init_key"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290668272,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:319",
      "file": "lib/digsig.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/digsig.c:digsig_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292744436,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:319",
      "file": "drivers/nvdimm/security.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/security.c:nvdimm_request_key"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "request_key",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273449052,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:319",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup_v1.c:find_and_lock_process_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274173572,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:319",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig",
        "fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274376252,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:319",
      "file": "security/keys/encrypted-keys/encrypted.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936274380636,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:319",
      "file": "security/keys/encrypted-keys/masterkey_trusted.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/encrypted-keys/masterkey_trusted.c:request_trusted_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274748250,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:319",
      "file": "security/integrity/digsig.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936274748980,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:319",
      "file": "security/integrity/digsig_asymmetric.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/digsig_asymmetric.c:asymmetric_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274780448,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:319",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/evm/evm_crypto.c:evm_init_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275392998,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:319",
      "file": "lib/digsig.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/digsig.c:digsig_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276688910,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:319",
      "file": "drivers/nvdimm/security.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/security.c:nvdimm_request_key"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "request_key",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582279563,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:319",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup_v1.c:find_and_lock_process_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583110165,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:319",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig",
        "fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583342487,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:319",
      "file": "security/keys/encrypted-keys/encrypted.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583348181,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:319",
      "file": "security/keys/encrypted-keys/masterkey_trusted.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/encrypted-keys/masterkey_trusted.c:request_trusted_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583748479,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:319",
      "file": "security/integrity/digsig.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583749154,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:319",
      "file": "security/integrity/digsig_asymmetric.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/digsig_asymmetric.c:asymmetric_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583783765,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:319",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/evm/evm_crypto.c:evm_init_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584425704,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:319",
      "file": "lib/digsig.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/digsig.c:digsig_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586275154,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:319",
      "file": "drivers/nvdimm/security.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/security.c:nvdimm_request_key"
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
  "name": "request_key",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582217323,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:319",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup_v1.c:find_and_lock_process_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583047317,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:319",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig",
        "fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583279591,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:319",
      "file": "security/keys/encrypted-keys/encrypted.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583285285,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:319",
      "file": "security/keys/encrypted-keys/masterkey_trusted.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/encrypted-keys/masterkey_trusted.c:request_trusted_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583685535,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:319",
      "file": "security/integrity/digsig.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583686210,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:319",
      "file": "security/integrity/digsig_asymmetric.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/digsig_asymmetric.c:asymmetric_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583720821,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:319",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/evm/evm_crypto.c:evm_init_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584360904,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:319",
      "file": "lib/digsig.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/digsig.c:digsig_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586093522,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:319",
      "file": "drivers/nvdimm/security.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/security.c:nvdimm_request_key"
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
  "name": "request_key",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582270043,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:319",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup_v1.c:find_and_lock_process_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583098773,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:319",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig",
        "fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583326263,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:319",
      "file": "security/keys/encrypted-keys/encrypted.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583331957,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:319",
      "file": "security/keys/encrypted-keys/masterkey_trusted.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/encrypted-keys/masterkey_trusted.c:request_trusted_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583732255,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:319",
      "file": "security/integrity/digsig.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583732930,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:319",
      "file": "security/integrity/digsig_asymmetric.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/digsig_asymmetric.c:asymmetric_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583767525,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:319",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/evm/evm_crypto.c:evm_init_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584408616,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:319",
      "file": "lib/digsig.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/digsig.c:digsig_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586532642,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:319",
      "file": "drivers/nvdimm/security.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/security.c:nvdimm_request_key"
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
  "name": "request_key",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582348603,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:319",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup_v1.c:find_and_lock_process_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583187973,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:319",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig",
        "fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583421287,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:319",
      "file": "security/keys/encrypted-keys/encrypted.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583426981,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:319",
      "file": "security/keys/encrypted-keys/masterkey_trusted.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/encrypted-keys/masterkey_trusted.c:request_trusted_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583833135,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:319",
      "file": "security/integrity/digsig.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583833810,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:319",
      "file": "security/integrity/digsig_asymmetric.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/digsig_asymmetric.c:asymmetric_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583868517,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:319",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/evm/evm_crypto.c:evm_init_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584514680,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:319",
      "file": "lib/digsig.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/digsig.c:digsig_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586644370,
      "name": "request_key",
      "external": false,
      "loc": "include/linux/key.h:319",
      "file": "drivers/nvdimm/security.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/security.c:nvdimm_request_key"
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
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
struct key * request_key(struct key_type * type, const char * description, const char * callout_info)
```
</details>
</li>
</ul>
