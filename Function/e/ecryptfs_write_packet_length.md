# Function: <code>ecryptfs_write_packet_length</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ecryptfs_write_packet_length(char * dest, size_t size, size_t * packet_size_length)
```

```json
{
  "name": "ecryptfs_write_packet_length",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582022976,
      "name": "ecryptfs_write_packet_length",
      "external": true,
      "loc": "fs/ecryptfs/keystore.c:135",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set"
      ],
      "caller_func": [
        "fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set",
        "fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582022976,
      "name": "ecryptfs_write_packet_length",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int ecryptfs_write_packet_length(char * dest, size_t size, size_t * packet_size_length)
```

```json
{
  "name": "ecryptfs_write_packet_length",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582246568,
      "name": "ecryptfs_write_packet_length",
      "external": true,
      "loc": "fs/ecryptfs/keystore.c:136",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set",
        "fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key"
      ],
      "caller_func": [
        "fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582236400,
      "name": "ecryptfs_write_packet_length",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int ecryptfs_write_packet_length(char * dest, size_t size, size_t * packet_size_length)
```

```json
{
  "name": "ecryptfs_write_packet_length",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582336056,
      "name": "ecryptfs_write_packet_length",
      "external": true,
      "loc": "fs/ecryptfs/keystore.c:136",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set",
        "fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key"
      ],
      "caller_func": [
        "fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582325888,
      "name": "ecryptfs_write_packet_length",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int ecryptfs_write_packet_length(char * dest, size_t size, size_t * packet_size_length)
```

```json
{
  "name": "ecryptfs_write_packet_length",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582421289,
      "name": "ecryptfs_write_packet_length",
      "external": true,
      "loc": "fs/ecryptfs/keystore.c:136",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set",
        "fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key"
      ],
      "caller_func": [
        "fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582410672,
      "name": "ecryptfs_write_packet_length",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int ecryptfs_write_packet_length(char * dest, size_t size, size_t * packet_size_length)
```

```json
{
  "name": "ecryptfs_write_packet_length",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582571801,
      "name": "ecryptfs_write_packet_length",
      "external": true,
      "loc": "fs/ecryptfs/keystore.c:136",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set",
        "fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key"
      ],
      "caller_func": [
        "fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582561328,
      "name": "ecryptfs_write_packet_length",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int ecryptfs_write_packet_length(char * dest, size_t size, size_t * packet_size_length)
```

```json
{
  "name": "ecryptfs_write_packet_length",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582762197,
      "name": "ecryptfs_write_packet_length",
      "external": true,
      "loc": "fs/ecryptfs/keystore.c:136",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set",
        "fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key"
      ],
      "caller_func": [
        "fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582753520,
      "name": "ecryptfs_write_packet_length",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int ecryptfs_write_packet_length(char * dest, size_t size, size_t * packet_size_length)
```

```json
{
  "name": "ecryptfs_write_packet_length",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582866245,
      "name": "ecryptfs_write_packet_length",
      "external": true,
      "loc": "fs/ecryptfs/keystore.c:136",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set",
        "fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key"
      ],
      "caller_func": [
        "fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582857408,
      "name": "ecryptfs_write_packet_length",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int ecryptfs_write_packet_length(char * dest, size_t size, size_t * packet_size_length)
```

```json
{
  "name": "ecryptfs_write_packet_length",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583040390,
      "name": "ecryptfs_write_packet_length",
      "external": true,
      "loc": "fs/ecryptfs/keystore.c:122",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set",
        "fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key"
      ],
      "caller_func": [
        "fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583032160,
      "name": "ecryptfs_write_packet_length",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int ecryptfs_write_packet_length(char * dest, size_t size, size_t * packet_size_length)
```

```json
{
  "name": "ecryptfs_write_packet_length",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583146614,
      "name": "ecryptfs_write_packet_length",
      "external": true,
      "loc": "fs/ecryptfs/keystore.c:122",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set",
        "fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key"
      ],
      "caller_func": [
        "fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583138384,
      "name": "ecryptfs_write_packet_length",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int ecryptfs_write_packet_length(char * dest, size_t size, size_t * packet_size_length)
```

```json
{
  "name": "ecryptfs_write_packet_length",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583461092,
      "name": "ecryptfs_write_packet_length",
      "external": true,
      "loc": "fs/ecryptfs/keystore.c:122",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:write_tag_1_packet",
        "fs/ecryptfs/keystore.c:write_tag_1_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "fs/ecryptfs/keystore.c:write_tag_66_packet",
        "fs/ecryptfs/keystore.c:write_tag_66_packet",
        "fs/ecryptfs/keystore.c:write_tag_64_packet",
        "fs/ecryptfs/keystore.c:write_tag_64_packet"
      ],
      "caller_func": [
        "fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583465360,
      "name": "ecryptfs_write_packet_length",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int ecryptfs_write_packet_length(char * dest, size_t size, size_t * packet_size_length)
```

```json
{
  "name": "ecryptfs_write_packet_length",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583572196,
      "name": "ecryptfs_write_packet_length",
      "external": true,
      "loc": "fs/ecryptfs/keystore.c:122",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:write_tag_1_packet",
        "fs/ecryptfs/keystore.c:write_tag_1_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "fs/ecryptfs/keystore.c:write_tag_66_packet",
        "fs/ecryptfs/keystore.c:write_tag_66_packet",
        "fs/ecryptfs/keystore.c:write_tag_64_packet",
        "fs/ecryptfs/keystore.c:write_tag_64_packet"
      ],
      "caller_func": [
        "fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583577104,
      "name": "ecryptfs_write_packet_length",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int ecryptfs_write_packet_length(char * dest, size_t size, size_t * packet_size_length)
```

```json
{
  "name": "ecryptfs_write_packet_length",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583595336,
      "name": "ecryptfs_write_packet_length",
      "external": true,
      "loc": "fs/ecryptfs/keystore.c:122",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:write_tag_1_packet",
        "fs/ecryptfs/keystore.c:write_tag_1_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet"
      ],
      "caller_func": [
        "fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583600288,
      "name": "ecryptfs_write_packet_length",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ecryptfs_write_packet_length(char * dest, size_t size, size_t * packet_size_length)
```

```json
{
  "name": "ecryptfs_write_packet_length",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583953682,
      "name": "ecryptfs_write_packet_length",
      "external": true,
      "loc": "fs/ecryptfs/keystore.c:122",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:write_tag_1_packet",
        "fs/ecryptfs/keystore.c:write_tag_1_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet"
      ],
      "caller_func": [
        "fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583958688,
      "name": "ecryptfs_write_packet_length",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ecryptfs_write_packet_length(char * dest, size_t size, size_t * packet_size_length)
```

```json
{
  "name": "ecryptfs_write_packet_length",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584535417,
      "name": "ecryptfs_write_packet_length",
      "external": true,
      "loc": "fs/ecryptfs/keystore.c:122",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:write_tag_1_packet",
        "fs/ecryptfs/keystore.c:write_tag_1_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet"
      ],
      "caller_func": [
        "fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584540688,
      "name": "ecryptfs_write_packet_length",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ecryptfs_write_packet_length(char * dest, size_t size, size_t * packet_size_length)
```

```json
{
  "name": "ecryptfs_write_packet_length",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585208863,
      "name": "ecryptfs_write_packet_length",
      "external": true,
      "loc": "fs/ecryptfs/keystore.c:122",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:write_tag_1_packet",
        "fs/ecryptfs/keystore.c:write_tag_1_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet"
      ],
      "caller_func": [
        "fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585215088,
      "name": "ecryptfs_write_packet_length",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ecryptfs_write_packet_length(char * dest, size_t size, size_t * packet_size_length)
```

```json
{
  "name": "ecryptfs_write_packet_length",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585438097,
      "name": "ecryptfs_write_packet_length",
      "external": true,
      "loc": "fs/ecryptfs/keystore.c:122",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:write_tag_1_packet",
        "fs/ecryptfs/keystore.c:write_tag_1_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet"
      ],
      "caller_func": [
        "fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585444544,
      "name": "ecryptfs_write_packet_length",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ecryptfs_write_packet_length(char * dest, size_t size, size_t * packet_size_length)
```

```json
{
  "name": "ecryptfs_write_packet_length",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585672801,
      "name": "ecryptfs_write_packet_length",
      "external": true,
      "loc": "fs/ecryptfs/keystore.c:122",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:write_tag_1_packet",
        "fs/ecryptfs/keystore.c:write_tag_1_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet"
      ],
      "caller_func": [
        "fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585679248,
      "name": "ecryptfs_write_packet_length",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
int ecryptfs_write_packet_length(char * dest, size_t size, size_t * packet_size_length)
```

```json
{
  "name": "ecryptfs_write_packet_length",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494857984,
      "name": "ecryptfs_write_packet_length",
      "external": true,
      "loc": "fs/ecryptfs/keystore.c:122",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set",
        "fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key"
      ],
      "caller_func": [
        "fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494848848,
      "name": "ecryptfs_write_packet_length",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int ecryptfs_write_packet_length(char * dest, size_t size, size_t * packet_size_length)
```

```json
{
  "name": "ecryptfs_write_packet_length",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228276120,
      "name": "ecryptfs_write_packet_length",
      "external": true,
      "loc": "fs/ecryptfs/keystore.c:122",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set",
        "fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key"
      ],
      "caller_func": [
        "fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228267320,
      "name": "ecryptfs_write_packet_length",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int ecryptfs_write_packet_length(char * dest, size_t size, size_t * packet_size_length)
```

```json
{
  "name": "ecryptfs_write_packet_length",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055288712160,
      "name": "ecryptfs_write_packet_length",
      "external": true,
      "loc": "fs/ecryptfs/keystore.c:122",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set",
        "fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key"
      ],
      "caller_func": [
        "fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288701072,
      "name": "ecryptfs_write_packet_length",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int ecryptfs_write_packet_length(char * dest, size_t size, size_t * packet_size_length)
```

```json
{
  "name": "ecryptfs_write_packet_length",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274179424,
      "name": "ecryptfs_write_packet_length",
      "external": true,
      "loc": "fs/ecryptfs/keystore.c:122",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set",
        "fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key"
      ],
      "caller_func": [
        "fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274170666,
      "name": "ecryptfs_write_packet_length",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
int ecryptfs_write_packet_length(char * dest, size_t size, size_t * packet_size_length)
```

```json
{
  "name": "ecryptfs_write_packet_length",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583115350,
      "name": "ecryptfs_write_packet_length",
      "external": true,
      "loc": "fs/ecryptfs/keystore.c:122",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set",
        "fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key"
      ],
      "caller_func": [
        "fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583107120,
      "name": "ecryptfs_write_packet_length",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int ecryptfs_write_packet_length(char * dest, size_t size, size_t * packet_size_length)
```

```json
{
  "name": "ecryptfs_write_packet_length",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583052502,
      "name": "ecryptfs_write_packet_length",
      "external": true,
      "loc": "fs/ecryptfs/keystore.c:122",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set",
        "fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key"
      ],
      "caller_func": [
        "fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583044272,
      "name": "ecryptfs_write_packet_length",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int ecryptfs_write_packet_length(char * dest, size_t size, size_t * packet_size_length)
```

```json
{
  "name": "ecryptfs_write_packet_length",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583103958,
      "name": "ecryptfs_write_packet_length",
      "external": true,
      "loc": "fs/ecryptfs/keystore.c:122",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set",
        "fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key"
      ],
      "caller_func": [
        "fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583095728,
      "name": "ecryptfs_write_packet_length",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int ecryptfs_write_packet_length(char * dest, size_t size, size_t * packet_size_length)
```

```json
{
  "name": "ecryptfs_write_packet_length",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583193158,
      "name": "ecryptfs_write_packet_length",
      "external": true,
      "loc": "fs/ecryptfs/keystore.c:122",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set",
        "fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key"
      ],
      "caller_func": [
        "fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583184928,
      "name": "ecryptfs_write_packet_length",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
