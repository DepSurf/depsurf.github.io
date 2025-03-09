# Function: <code>integrity_audit_message</code>

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
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void integrity_audit_message(int audit_msgno, struct inode * inode, const unsigned char * fname, const char * op, const char * cause, int result, int audit_info, int errno)
```

```json
{
  "name": "integrity_audit_message",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584288880,
      "name": "integrity_audit_message",
      "external": true,
      "loc": "security/integrity/integrity_audit.c:36",
      "file": "security/integrity/integrity_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/ima/ima_main.c:process_buffer_measurement",
        "security/integrity/ima/ima_queue_keys.c:ima_alloc_key_entry",
        "security/integrity/ima/ima_queue_keys.c:ima_alloc_key_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584288880,
      "name": "integrity_audit_message",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 427
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
void integrity_audit_message(int audit_msgno, struct inode * inode, const unsigned char * fname, const char * op, const char * cause, int result, int audit_info, int errno)
```

```json
{
  "name": "integrity_audit_message",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584322720,
      "name": "integrity_audit_message",
      "external": true,
      "loc": "security/integrity/integrity_audit.c:36",
      "file": "security/integrity/integrity_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/ima/ima_main.c:process_buffer_measurement",
        "security/integrity/ima/ima_queue_keys.c:ima_queue_key",
        "security/integrity/ima/ima_queue_keys.c:ima_queue_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584322720,
      "name": "integrity_audit_message",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void integrity_audit_message(int audit_msgno, struct inode * inode, const unsigned char * fname, const char * op, const char * cause, int result, int audit_info, int errno)
```

```json
{
  "name": "integrity_audit_message",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584709856,
      "name": "integrity_audit_message",
      "external": true,
      "loc": "security/integrity/integrity_audit.c:36",
      "file": "security/integrity/integrity_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/ima/ima_main.c:process_buffer_measurement",
        "security/integrity/ima/ima_queue_keys.c:ima_queue_key",
        "security/integrity/ima/ima_queue_keys.c:ima_queue_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584709856,
      "name": "integrity_audit_message",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 425
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
void integrity_audit_message(int audit_msgno, struct inode * inode, const unsigned char * fname, const char * op, const char * cause, int result, int audit_info, int errno)
```

```json
{
  "name": "integrity_audit_message",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585383616,
      "name": "integrity_audit_message",
      "external": true,
      "loc": "security/integrity/integrity_audit.c:36",
      "file": "security/integrity/integrity_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/ima/ima_main.c:process_buffer_measurement",
        "security/integrity/ima/ima_queue_keys.c:ima_queue_key",
        "security/integrity/ima/ima_queue_keys.c:ima_queue_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585383616,
      "name": "integrity_audit_message",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 456
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
void integrity_audit_message(int audit_msgno, struct inode * inode, const unsigned char * fname, const char * op, const char * cause, int result, int audit_info, int errno)
```

```json
{
  "name": "integrity_audit_message",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586135312,
      "name": "integrity_audit_message",
      "external": true,
      "loc": "security/integrity/integrity_audit.c:36",
      "file": "security/integrity/integrity_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/ima/ima_main.c:process_buffer_measurement",
        "security/integrity/ima/ima_queue_keys.c:ima_queue_key",
        "security/integrity/ima/ima_queue_keys.c:ima_queue_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586135312,
      "name": "integrity_audit_message",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 456
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
void integrity_audit_message(int audit_msgno, struct inode * inode, const unsigned char * fname, const char * op, const char * cause, int result, int audit_info, int errno)
```

```json
{
  "name": "integrity_audit_message",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586373184,
      "name": "integrity_audit_message",
      "external": true,
      "loc": "security/integrity/integrity_audit.c:36",
      "file": "security/integrity/integrity_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/ima/ima_main.c:process_buffer_measurement",
        "security/integrity/ima/ima_queue_keys.c:ima_queue_key",
        "security/integrity/ima/ima_queue_keys.c:ima_queue_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586373184,
      "name": "integrity_audit_message",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 456
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
void integrity_audit_message(int audit_msgno, struct inode * inode, const unsigned char * fname, const char * op, const char * cause, int result, int audit_info, int errno)
```

```json
{
  "name": "integrity_audit_message",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586637728,
      "name": "integrity_audit_message",
      "external": true,
      "loc": "security/integrity/integrity_audit.c:36",
      "file": "security/integrity/integrity_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/ima/ima_main.c:process_buffer_measurement",
        "security/integrity/ima/ima_queue_keys.c:ima_queue_key",
        "security/integrity/ima/ima_queue_keys.c:ima_queue_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586637728,
      "name": "integrity_audit_message",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 456
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
void integrity_audit_message(int audit_msgno, struct inode * inode, const unsigned char * fname, const char * op, const char * cause, int result, int audit_info, int errno)
```
</details>
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
