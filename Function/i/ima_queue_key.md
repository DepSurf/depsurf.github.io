# Function: <code>ima_queue_key</code>

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
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
bool ima_queue_key(struct key * keyring, const void * payload, size_t payload_len)
```

```json
{
  "name": "ima_queue_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584206224,
      "name": "ima_queue_key",
      "external": true,
      "loc": "security/integrity/ima/ima_queue_keys.c:98",
      "file": "security/integrity/ima/ima_queue_keys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_asymmetric_keys.c:ima_post_key_create_or_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584206224,
      "name": "ima_queue_key",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
bool ima_queue_key(struct key * keyring, const void * payload, size_t payload_len)
```

```json
{
  "name": "ima_queue_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584324656,
      "name": "ima_queue_key",
      "external": true,
      "loc": "security/integrity/ima/ima_queue_keys.c:103",
      "file": "security/integrity/ima/ima_queue_keys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_asymmetric_keys.c:ima_post_key_create_or_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584324656,
      "name": "ima_queue_key",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
bool ima_queue_key(struct key * keyring, const void * payload, size_t payload_len)
```

```json
{
  "name": "ima_queue_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584358608,
      "name": "ima_queue_key",
      "external": true,
      "loc": "security/integrity/ima/ima_queue_keys.c:104",
      "file": "security/integrity/ima/ima_queue_keys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_asymmetric_keys.c:ima_post_key_create_or_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584358608,
      "name": "ima_queue_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 421
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
bool ima_queue_key(struct key * keyring, const void * payload, size_t payload_len)
```

```json
{
  "name": "ima_queue_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_queue_key",
      "external": true,
      "loc": "security/integrity/ima/ima_queue_keys.c:104",
      "file": "security/integrity/ima/ima_queue_keys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_asymmetric_keys.c:ima_post_key_create_or_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592309823,
      "name": "ima_queue_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071584751680,
      "name": "ima_queue_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 433
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
bool ima_queue_key(struct key * keyring, const void * payload, size_t payload_len)
```

```json
{
  "name": "ima_queue_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_queue_key",
      "external": true,
      "loc": "security/integrity/ima/ima_queue_keys.c:104",
      "file": "security/integrity/ima/ima_queue_keys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_asymmetric_keys.c:ima_post_key_create_or_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594092148,
      "name": "ima_queue_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071585432736,
      "name": "ima_queue_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 415
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
bool ima_queue_key(struct key * keyring, const void * payload, size_t payload_len)
```

```json
{
  "name": "ima_queue_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_queue_key",
      "external": true,
      "loc": "security/integrity/ima/ima_queue_keys.c:104",
      "file": "security/integrity/ima/ima_queue_keys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_asymmetric_keys.c:ima_post_key_create_or_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596103061,
      "name": "ima_queue_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071586189728,
      "name": "ima_queue_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 415
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
bool ima_queue_key(struct key * keyring, const void * payload, size_t payload_len)
```

```json
{
  "name": "ima_queue_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_queue_key",
      "external": true,
      "loc": "security/integrity/ima/ima_queue_keys.c:104",
      "file": "security/integrity/ima/ima_queue_keys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_asymmetric_keys.c:ima_post_key_create_or_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596626167,
      "name": "ima_queue_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071586427456,
      "name": "ima_queue_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 415
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
bool ima_queue_key(struct key * keyring, const void * payload, size_t payload_len)
```

```json
{
  "name": "ima_queue_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_queue_key",
      "external": true,
      "loc": "security/integrity/ima/ima_queue_keys.c:104",
      "file": "security/integrity/ima/ima_queue_keys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_asymmetric_keys.c:ima_post_key_create_or_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597531809,
      "name": "ima_queue_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071586692560,
      "name": "ima_queue_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 462
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
bool ima_queue_key(struct key * keyring, const void * payload, size_t payload_len)
```
</details>
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
