# Function: <code>restrict_link_by_signature</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int restrict_link_by_signature(struct key * trust_keyring, const struct key_type * type, const union key_payload * payload)
```

```json
{
  "name": "restrict_link_by_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582974928,
      "name": "restrict_link_by_signature",
      "external": true,
      "loc": "crypto/asymmetric_keys/restrict.c:72",
      "file": "crypto/asymmetric_keys/restrict.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:restrict_link_by_builtin_and_secondary_trusted",
        "certs/system_keyring.c:restrict_link_by_builtin_trusted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582974928,
      "name": "restrict_link_by_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
int restrict_link_by_signature(struct key * trust_keyring, const struct key_type * type, const union key_payload * payload)
```

```json
{
  "name": "restrict_link_by_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583079504,
      "name": "restrict_link_by_signature",
      "external": true,
      "loc": "crypto/asymmetric_keys/restrict.c:72",
      "file": "crypto/asymmetric_keys/restrict.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:restrict_link_by_builtin_and_secondary_trusted",
        "certs/system_keyring.c:restrict_link_by_builtin_trusted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583079504,
      "name": "restrict_link_by_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
int restrict_link_by_signature(struct key * dest_keyring, const struct key_type * type, const union key_payload * payload, struct key * trust_keyring)
```

```json
{
  "name": "restrict_link_by_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583135552,
      "name": "restrict_link_by_signature",
      "external": true,
      "loc": "crypto/asymmetric_keys/restrict.c:73",
      "file": "crypto/asymmetric_keys/restrict.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:restrict_link_by_builtin_and_secondary_trusted",
        "certs/system_keyring.c:restrict_link_by_builtin_trusted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583135552,
      "name": "restrict_link_by_signature",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int restrict_link_by_signature(struct key * dest_keyring, const struct key_type * type, const union key_payload * payload, struct key * trust_keyring)
```

```json
{
  "name": "restrict_link_by_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583310224,
      "name": "restrict_link_by_signature",
      "external": true,
      "loc": "crypto/asymmetric_keys/restrict.c:74",
      "file": "crypto/asymmetric_keys/restrict.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:restrict_link_by_builtin_and_secondary_trusted",
        "certs/system_keyring.c:restrict_link_by_builtin_trusted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583310224,
      "name": "restrict_link_by_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
int restrict_link_by_signature(struct key * dest_keyring, const struct key_type * type, const union key_payload * payload, struct key * trust_keyring)
```

```json
{
  "name": "restrict_link_by_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583518832,
      "name": "restrict_link_by_signature",
      "external": true,
      "loc": "crypto/asymmetric_keys/restrict.c:74",
      "file": "crypto/asymmetric_keys/restrict.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:restrict_link_by_builtin_and_secondary_trusted",
        "certs/system_keyring.c:restrict_link_by_builtin_trusted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583518832,
      "name": "restrict_link_by_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
int restrict_link_by_signature(struct key * dest_keyring, const struct key_type * type, const union key_payload * payload, struct key * trust_keyring)
```

```json
{
  "name": "restrict_link_by_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583640752,
      "name": "restrict_link_by_signature",
      "external": true,
      "loc": "crypto/asymmetric_keys/restrict.c:74",
      "file": "crypto/asymmetric_keys/restrict.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:restrict_link_by_builtin_and_secondary_trusted",
        "certs/system_keyring.c:restrict_link_by_builtin_trusted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583640752,
      "name": "restrict_link_by_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
int restrict_link_by_signature(struct key * dest_keyring, const struct key_type * type, const union key_payload * payload, struct key * trust_keyring)
```

```json
{
  "name": "restrict_link_by_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583826848,
      "name": "restrict_link_by_signature",
      "external": true,
      "loc": "crypto/asymmetric_keys/restrict.c:70",
      "file": "crypto/asymmetric_keys/restrict.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:restrict_link_by_builtin_and_secondary_trusted",
        "certs/system_keyring.c:restrict_link_by_builtin_trusted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583826848,
      "name": "restrict_link_by_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 229
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
int restrict_link_by_signature(struct key * dest_keyring, const struct key_type * type, const union key_payload * payload, struct key * trust_keyring)
```

```json
{
  "name": "restrict_link_by_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583928816,
      "name": "restrict_link_by_signature",
      "external": true,
      "loc": "crypto/asymmetric_keys/restrict.c:70",
      "file": "crypto/asymmetric_keys/restrict.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:restrict_link_by_builtin_and_secondary_trusted",
        "certs/system_keyring.c:restrict_link_by_builtin_trusted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583928816,
      "name": "restrict_link_by_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 229
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
int restrict_link_by_signature(struct key * dest_keyring, const struct key_type * type, const union key_payload * payload, struct key * trust_keyring)
```

```json
{
  "name": "restrict_link_by_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584320192,
      "name": "restrict_link_by_signature",
      "external": true,
      "loc": "crypto/asymmetric_keys/restrict.c:70",
      "file": "crypto/asymmetric_keys/restrict.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:restrict_link_by_builtin_and_secondary_trusted",
        "certs/system_keyring.c:restrict_link_by_builtin_trusted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584320192,
      "name": "restrict_link_by_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 229
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
int restrict_link_by_signature(struct key * dest_keyring, const struct key_type * type, const union key_payload * payload, struct key * trust_keyring)
```

```json
{
  "name": "restrict_link_by_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584438464,
      "name": "restrict_link_by_signature",
      "external": true,
      "loc": "crypto/asymmetric_keys/restrict.c:70",
      "file": "crypto/asymmetric_keys/restrict.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:restrict_link_by_builtin_and_secondary_trusted",
        "certs/system_keyring.c:restrict_link_by_builtin_trusted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584438464,
      "name": "restrict_link_by_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 229
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
int restrict_link_by_signature(struct key * dest_keyring, const struct key_type * type, const union key_payload * payload, struct key * trust_keyring)
```

```json
{
  "name": "restrict_link_by_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584473136,
      "name": "restrict_link_by_signature",
      "external": true,
      "loc": "crypto/asymmetric_keys/restrict.c:70",
      "file": "crypto/asymmetric_keys/restrict.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:restrict_link_by_builtin_and_secondary_trusted",
        "certs/system_keyring.c:restrict_link_by_builtin_trusted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584473136,
      "name": "restrict_link_by_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 229
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int restrict_link_by_signature(struct key * dest_keyring, const struct key_type * type, const union key_payload * payload, struct key * trust_keyring)
```

```json
{
  "name": "restrict_link_by_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "restrict_link_by_signature",
      "external": true,
      "loc": "crypto/asymmetric_keys/restrict.c:70",
      "file": "crypto/asymmetric_keys/restrict.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:restrict_link_by_builtin_and_secondary_trusted",
        "certs/system_keyring.c:restrict_link_by_builtin_trusted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592311221,
      "name": "restrict_link_by_signature.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071584871232,
      "name": "restrict_link_by_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 257
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
int restrict_link_by_signature(struct key * dest_keyring, const struct key_type * type, const union key_payload * payload, struct key * trust_keyring)
```

```json
{
  "name": "restrict_link_by_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "restrict_link_by_signature",
      "external": true,
      "loc": "crypto/asymmetric_keys/restrict.c:70",
      "file": "crypto/asymmetric_keys/restrict.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:restrict_link_by_builtin_secondary_and_machine",
        "certs/system_keyring.c:restrict_link_by_builtin_secondary_and_machine",
        "certs/system_keyring.c:restrict_link_by_builtin_trusted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594093570,
      "name": "restrict_link_by_signature.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071585567104,
      "name": "restrict_link_by_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 298
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
int restrict_link_by_signature(struct key * dest_keyring, const struct key_type * type, const union key_payload * payload, struct key * trust_keyring)
```

```json
{
  "name": "restrict_link_by_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "restrict_link_by_signature",
      "external": true,
      "loc": "crypto/asymmetric_keys/restrict.c:70",
      "file": "crypto/asymmetric_keys/restrict.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:restrict_link_by_builtin_secondary_and_machine",
        "certs/system_keyring.c:restrict_link_by_builtin_secondary_and_machine",
        "certs/system_keyring.c:restrict_link_by_builtin_trusted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596103813,
      "name": "restrict_link_by_signature.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071586331104,
      "name": "restrict_link_by_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 298
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
int restrict_link_by_signature(struct key * dest_keyring, const struct key_type * type, const union key_payload * payload, struct key * trust_keyring)
```

```json
{
  "name": "restrict_link_by_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "restrict_link_by_signature",
      "external": true,
      "loc": "crypto/asymmetric_keys/restrict.c:70",
      "file": "crypto/asymmetric_keys/restrict.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:restrict_link_by_builtin_secondary_and_machine",
        "certs/system_keyring.c:restrict_link_by_builtin_secondary_and_machine",
        "certs/system_keyring.c:restrict_link_by_builtin_trusted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596627201,
      "name": "restrict_link_by_signature.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071586577632,
      "name": "restrict_link_by_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 298
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
int restrict_link_by_signature(struct key * dest_keyring, const struct key_type * type, const union key_payload * payload, struct key * trust_keyring)
```

```json
{
  "name": "restrict_link_by_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "restrict_link_by_signature",
      "external": true,
      "loc": "crypto/asymmetric_keys/restrict.c:70",
      "file": "crypto/asymmetric_keys/restrict.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:restrict_link_by_builtin_secondary_and_machine",
        "certs/system_keyring.c:restrict_link_by_builtin_secondary_and_machine",
        "certs/system_keyring.c:restrict_link_by_builtin_trusted",
        "crypto/asymmetric_keys/restrict.c:restrict_link_by_digsig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597533060,
      "name": "restrict_link_by_signature.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071586846064,
      "name": "restrict_link_by_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 298
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
int restrict_link_by_signature(struct key * dest_keyring, const struct key_type * type, const union key_payload * payload, struct key * trust_keyring)
```

```json
{
  "name": "restrict_link_by_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495747672,
      "name": "restrict_link_by_signature",
      "external": true,
      "loc": "crypto/asymmetric_keys/restrict.c:70",
      "file": "crypto/asymmetric_keys/restrict.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:restrict_link_by_builtin_and_secondary_trusted",
        "certs/system_keyring.c:restrict_link_by_builtin_trusted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495747672,
      "name": "restrict_link_by_signature",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int restrict_link_by_signature(struct key * dest_keyring, const struct key_type * type, const union key_payload * payload, struct key * trust_keyring)
```

```json
{
  "name": "restrict_link_by_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229100964,
      "name": "restrict_link_by_signature",
      "external": true,
      "loc": "crypto/asymmetric_keys/restrict.c:70",
      "file": "crypto/asymmetric_keys/restrict.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:restrict_link_by_builtin_and_secondary_trusted",
        "certs/system_keyring.c:restrict_link_by_builtin_trusted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229100964,
      "name": "restrict_link_by_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
int restrict_link_by_signature(struct key * dest_keyring, const struct key_type * type, const union key_payload * payload, struct key * trust_keyring)
```

```json
{
  "name": "restrict_link_by_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289910752,
      "name": "restrict_link_by_signature",
      "external": true,
      "loc": "crypto/asymmetric_keys/restrict.c:70",
      "file": "crypto/asymmetric_keys/restrict.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:restrict_link_by_builtin_and_secondary_trusted",
        "certs/system_keyring.c:restrict_link_by_builtin_trusted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289910752,
      "name": "restrict_link_by_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 408
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
int restrict_link_by_signature(struct key * dest_keyring, const struct key_type * type, const union key_payload * payload, struct key * trust_keyring)
```

```json
{
  "name": "restrict_link_by_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274896126,
      "name": "restrict_link_by_signature",
      "external": true,
      "loc": "crypto/asymmetric_keys/restrict.c:70",
      "file": "crypto/asymmetric_keys/restrict.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:restrict_link_by_builtin_and_secondary_trusted",
        "certs/system_keyring.c:restrict_link_by_builtin_trusted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274896126,
      "name": "restrict_link_by_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
int restrict_link_by_signature(struct key * dest_keyring, const struct key_type * type, const union key_payload * payload, struct key * trust_keyring)
```

```json
{
  "name": "restrict_link_by_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583897552,
      "name": "restrict_link_by_signature",
      "external": true,
      "loc": "crypto/asymmetric_keys/restrict.c:70",
      "file": "crypto/asymmetric_keys/restrict.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:restrict_link_by_builtin_and_secondary_trusted",
        "certs/system_keyring.c:restrict_link_by_builtin_trusted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583897552,
      "name": "restrict_link_by_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 229
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
int restrict_link_by_signature(struct key * dest_keyring, const struct key_type * type, const union key_payload * payload, struct key * trust_keyring)
```

```json
{
  "name": "restrict_link_by_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583834608,
      "name": "restrict_link_by_signature",
      "external": true,
      "loc": "crypto/asymmetric_keys/restrict.c:70",
      "file": "crypto/asymmetric_keys/restrict.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:restrict_link_by_builtin_and_secondary_trusted",
        "certs/system_keyring.c:restrict_link_by_builtin_trusted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583834608,
      "name": "restrict_link_by_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 229
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
int restrict_link_by_signature(struct key * dest_keyring, const struct key_type * type, const union key_payload * payload, struct key * trust_keyring)
```

```json
{
  "name": "restrict_link_by_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583881312,
      "name": "restrict_link_by_signature",
      "external": true,
      "loc": "crypto/asymmetric_keys/restrict.c:70",
      "file": "crypto/asymmetric_keys/restrict.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:restrict_link_by_builtin_and_secondary_trusted",
        "certs/system_keyring.c:restrict_link_by_builtin_trusted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583881312,
      "name": "restrict_link_by_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 229
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
int restrict_link_by_signature(struct key * dest_keyring, const struct key_type * type, const union key_payload * payload, struct key * trust_keyring)
```

```json
{
  "name": "restrict_link_by_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583982384,
      "name": "restrict_link_by_signature",
      "external": true,
      "loc": "crypto/asymmetric_keys/restrict.c:70",
      "file": "crypto/asymmetric_keys/restrict.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:restrict_link_by_builtin_and_secondary_trusted",
        "certs/system_keyring.c:restrict_link_by_builtin_trusted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583982384,
      "name": "restrict_link_by_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 229
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int restrict_link_by_signature(struct key * trust_keyring, const struct key_type * type, const union key_payload * payload)
```
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct key * dest_keyring</code>
</li>
<li>
<b>Param reordered. </b>
<code>trust_keyring, type, payload</code> ➡️ <code>dest_keyring, type, payload, trust_keyring</code>
</li>
</ul>
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
