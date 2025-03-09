# Function: <code>fscrypt_policies_equal</code>

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
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
bool fscrypt_policies_equal(const union fscrypt_policy * policy1, const union fscrypt_policy * policy2)
```

```json
{
  "name": "fscrypt_policies_equal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582313008,
      "name": "fscrypt_policies_equal",
      "external": true,
      "loc": "fs/crypto/policy.c:23",
      "file": "fs/crypto/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582313008,
      "name": "fscrypt_policies_equal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
bool fscrypt_policies_equal(const union fscrypt_policy * policy1, const union fscrypt_policy * policy2)
```

```json
{
  "name": "fscrypt_policies_equal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582600720,
      "name": "fscrypt_policies_equal",
      "external": true,
      "loc": "fs/crypto/policy.c:26",
      "file": "fs/crypto/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582600720,
      "name": "fscrypt_policies_equal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
bool fscrypt_policies_equal(const union fscrypt_policy * policy1, const union fscrypt_policy * policy2)
```

```json
{
  "name": "fscrypt_policies_equal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582671104,
      "name": "fscrypt_policies_equal",
      "external": true,
      "loc": "fs/crypto/policy.c:26",
      "file": "fs/crypto/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/policy.c:fscrypt_set_test_dummy_encryption",
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582671104,
      "name": "fscrypt_policies_equal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
bool fscrypt_policies_equal(const union fscrypt_policy * policy1, const union fscrypt_policy * policy2)
```

```json
{
  "name": "fscrypt_policies_equal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582699904,
      "name": "fscrypt_policies_equal",
      "external": true,
      "loc": "fs/crypto/policy.c:26",
      "file": "fs/crypto/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/policy.c:fscrypt_set_test_dummy_encryption",
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582699904,
      "name": "fscrypt_policies_equal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
bool fscrypt_policies_equal(const union fscrypt_policy * policy1, const union fscrypt_policy * policy2)
```

```json
{
  "name": "fscrypt_policies_equal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583025904,
      "name": "fscrypt_policies_equal",
      "external": true,
      "loc": "fs/crypto/policy.c:26",
      "file": "fs/crypto/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/policy.c:fscrypt_set_test_dummy_encryption",
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583025904,
      "name": "fscrypt_policies_equal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
bool fscrypt_policies_equal(const union fscrypt_policy * policy1, const union fscrypt_policy * policy2)
```

```json
{
  "name": "fscrypt_policies_equal",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583498375,
      "name": "fscrypt_policies_equal",
      "external": true,
      "loc": "fs/crypto/policy.c:27",
      "file": "fs/crypto/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/policy.c:fscrypt_dummy_policies_equal"
      ],
      "caller_func": [
        "fs/crypto/policy.c:fscrypt_parse_test_dummy_encryption",
        "fs/crypto/policy.c:fscrypt_has_permitted_context",
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583498480,
      "name": "fscrypt_policies_equal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
bool fscrypt_policies_equal(const union fscrypt_policy * policy1, const union fscrypt_policy * policy2)
```

```json
{
  "name": "fscrypt_policies_equal",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584094887,
      "name": "fscrypt_policies_equal",
      "external": true,
      "loc": "fs/crypto/policy.c:27",
      "file": "fs/crypto/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/policy.c:fscrypt_dummy_policies_equal"
      ],
      "caller_func": [
        "fs/crypto/policy.c:fscrypt_parse_test_dummy_encryption",
        "fs/crypto/policy.c:fscrypt_has_permitted_context",
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584095008,
      "name": "fscrypt_policies_equal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
bool fscrypt_policies_equal(const union fscrypt_policy * policy1, const union fscrypt_policy * policy2)
```

```json
{
  "name": "fscrypt_policies_equal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584321824,
      "name": "fscrypt_policies_equal",
      "external": true,
      "loc": "fs/crypto/policy.c:27",
      "file": "fs/crypto/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:setup_file_encryption_key",
        "fs/crypto/policy.c:fscrypt_dummy_policies_equal",
        "fs/crypto/policy.c:fscrypt_parse_test_dummy_encryption",
        "fs/crypto/policy.c:fscrypt_has_permitted_context",
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584321824,
      "name": "fscrypt_policies_equal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
bool fscrypt_policies_equal(const union fscrypt_policy * policy1, const union fscrypt_policy * policy2)
```

```json
{
  "name": "fscrypt_policies_equal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584539328,
      "name": "fscrypt_policies_equal",
      "external": true,
      "loc": "fs/crypto/policy.c:27",
      "file": "fs/crypto/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:setup_file_encryption_key",
        "fs/crypto/policy.c:fscrypt_dummy_policies_equal",
        "fs/crypto/policy.c:fscrypt_parse_test_dummy_encryption",
        "fs/crypto/policy.c:fscrypt_has_permitted_context",
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584539328,
      "name": "fscrypt_policies_equal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
bool fscrypt_policies_equal(const union fscrypt_policy * policy1, const union fscrypt_policy * policy2)
```

```json
{
  "name": "fscrypt_policies_equal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493891424,
      "name": "fscrypt_policies_equal",
      "external": true,
      "loc": "fs/crypto/policy.c:23",
      "file": "fs/crypto/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493891424,
      "name": "fscrypt_policies_equal",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
bool fscrypt_policies_equal(const union fscrypt_policy * policy1, const union fscrypt_policy * policy2)
```

```json
{
  "name": "fscrypt_policies_equal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227371560,
      "name": "fscrypt_policies_equal",
      "external": true,
      "loc": "fs/crypto/policy.c:23",
      "file": "fs/crypto/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227371560,
      "name": "fscrypt_policies_equal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
bool fscrypt_policies_equal(const union fscrypt_policy * policy1, const union fscrypt_policy * policy2)
```

```json
{
  "name": "fscrypt_policies_equal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287527744,
      "name": "fscrypt_policies_equal",
      "external": true,
      "loc": "fs/crypto/policy.c:23",
      "file": "fs/crypto/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287527744,
      "name": "fscrypt_policies_equal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
bool fscrypt_policies_equal(const union fscrypt_policy * policy1, const union fscrypt_policy * policy2)
```

```json
{
  "name": "fscrypt_policies_equal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273451388,
      "name": "fscrypt_policies_equal",
      "external": true,
      "loc": "fs/crypto/policy.c:23",
      "file": "fs/crypto/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273451388,
      "name": "fscrypt_policies_equal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
bool fscrypt_policies_equal(const union fscrypt_policy * policy1, const union fscrypt_policy * policy2)
```

```json
{
  "name": "fscrypt_policies_equal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582281744,
      "name": "fscrypt_policies_equal",
      "external": true,
      "loc": "fs/crypto/policy.c:23",
      "file": "fs/crypto/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582281744,
      "name": "fscrypt_policies_equal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
bool fscrypt_policies_equal(const union fscrypt_policy * policy1, const union fscrypt_policy * policy2)
```

```json
{
  "name": "fscrypt_policies_equal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582219504,
      "name": "fscrypt_policies_equal",
      "external": true,
      "loc": "fs/crypto/policy.c:23",
      "file": "fs/crypto/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582219504,
      "name": "fscrypt_policies_equal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
bool fscrypt_policies_equal(const union fscrypt_policy * policy1, const union fscrypt_policy * policy2)
```

```json
{
  "name": "fscrypt_policies_equal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582272224,
      "name": "fscrypt_policies_equal",
      "external": true,
      "loc": "fs/crypto/policy.c:23",
      "file": "fs/crypto/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582272224,
      "name": "fscrypt_policies_equal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
bool fscrypt_policies_equal(const union fscrypt_policy * policy1, const union fscrypt_policy * policy2)
```

```json
{
  "name": "fscrypt_policies_equal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582350784,
      "name": "fscrypt_policies_equal",
      "external": true,
      "loc": "fs/crypto/policy.c:23",
      "file": "fs/crypto/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582350784,
      "name": "fscrypt_policies_equal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
bool fscrypt_policies_equal(const union fscrypt_policy * policy1, const union fscrypt_policy * policy2)
```
</details>
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
