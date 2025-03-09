# Function: <code>ima_should_queue_key</code>

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
bool ima_should_queue_key()
```

```json
{
  "name": "ima_should_queue_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584206464,
      "name": "ima_should_queue_key",
      "external": true,
      "loc": "security/integrity/ima/ima_queue_keys.c:166",
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
      "addr": 18446744071584206464,
      "name": "ima_should_queue_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
bool ima_should_queue_key()
```

```json
{
  "name": "ima_should_queue_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584324896,
      "name": "ima_should_queue_key",
      "external": true,
      "loc": "security/integrity/ima/ima_queue_keys.c:171",
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
      "addr": 18446744071584324896,
      "name": "ima_should_queue_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
bool ima_should_queue_key()
```

```json
{
  "name": "ima_should_queue_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584359376,
      "name": "ima_should_queue_key",
      "external": true,
      "loc": "security/integrity/ima/ima_queue_keys.c:174",
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
      "addr": 18446744071584359376,
      "name": "ima_should_queue_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
bool ima_should_queue_key()
```

```json
{
  "name": "ima_should_queue_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_should_queue_key",
      "external": true,
      "loc": "security/integrity/ima/ima_queue_keys.c:174",
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
      "addr": 18446744071592309924,
      "name": "ima_should_queue_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071584752544,
      "name": "ima_should_queue_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
bool ima_should_queue_key()
```

```json
{
  "name": "ima_should_queue_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_should_queue_key",
      "external": true,
      "loc": "security/integrity/ima/ima_queue_keys.c:174",
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
      "addr": 18446744071594092250,
      "name": "ima_should_queue_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071585433600,
      "name": "ima_should_queue_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
bool ima_should_queue_key()
```

```json
{
  "name": "ima_should_queue_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_should_queue_key",
      "external": true,
      "loc": "security/integrity/ima/ima_queue_keys.c:174",
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
      "addr": 18446744071596103163,
      "name": "ima_should_queue_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071586190640,
      "name": "ima_should_queue_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
bool ima_should_queue_key()
```

```json
{
  "name": "ima_should_queue_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_should_queue_key",
      "external": true,
      "loc": "security/integrity/ima/ima_queue_keys.c:174",
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
      "addr": 18446744071596626269,
      "name": "ima_should_queue_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071586428368,
      "name": "ima_should_queue_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
bool ima_should_queue_key()
```

```json
{
  "name": "ima_should_queue_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_should_queue_key",
      "external": true,
      "loc": "security/integrity/ima/ima_queue_keys.c:174",
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
      "addr": 18446744071597531911,
      "name": "ima_should_queue_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071586693520,
      "name": "ima_should_queue_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
bool ima_should_queue_key()
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
