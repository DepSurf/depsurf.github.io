# Function: <code>ima_measure_critical_data</code>

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
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void ima_measure_critical_data(const char * event_label, const char * event_name, const void * buf, size_t buf_len, bool hash)
```

```json
{
  "name": "ima_measure_critical_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584333376,
      "name": "ima_measure_critical_data",
      "external": true,
      "loc": "security/integrity/ima/ima_main.c:976",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ima.c:selinux_ima_measure_state_locked",
        "security/selinux/ima.c:selinux_ima_measure_state_locked",
        "security/integrity/ima/ima_init.c:ima_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584333376,
      "name": "ima_measure_critical_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int ima_measure_critical_data(const char * event_label, const char * event_name, const void * buf, size_t buf_len, bool hash, u8 * digest, size_t digest_len)
```

```json
{
  "name": "ima_measure_critical_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584721344,
      "name": "ima_measure_critical_data",
      "external": true,
      "loc": "security/integrity/ima/ima_main.c:1014",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ima.c:selinux_ima_measure_state_locked",
        "security/selinux/ima.c:selinux_ima_measure_state_locked",
        "security/integrity/ima/ima_init.c:ima_init",
        "drivers/md/dm-ima.c:dm_ima_measure_data",
        "drivers/md/dm-ima.c:dm_ima_measure_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584721344,
      "name": "ima_measure_critical_data",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int ima_measure_critical_data(const char * event_label, const char * event_name, const void * buf, size_t buf_len, bool hash, u8 * digest, size_t digest_len)
```

```json
{
  "name": "ima_measure_critical_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585396544,
      "name": "ima_measure_critical_data",
      "external": true,
      "loc": "security/integrity/ima/ima_main.c:1034",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ima.c:selinux_ima_measure_state_locked",
        "security/selinux/ima.c:selinux_ima_measure_state_locked",
        "security/integrity/ima/ima_init.c:ima_init",
        "drivers/md/dm-ima.c:dm_ima_measure_data",
        "drivers/md/dm-ima.c:dm_ima_measure_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585396544,
      "name": "ima_measure_critical_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int ima_measure_critical_data(const char * event_label, const char * event_name, const void * buf, size_t buf_len, bool hash, u8 * digest, size_t digest_len)
```

```json
{
  "name": "ima_measure_critical_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586149584,
      "name": "ima_measure_critical_data",
      "external": true,
      "loc": "security/integrity/ima/ima_main.c:1044",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ima.c:selinux_ima_measure_state_locked",
        "security/selinux/ima.c:selinux_ima_measure_state_locked",
        "security/integrity/ima/ima_init.c:ima_init",
        "drivers/md/dm-ima.c:dm_ima_measure_data",
        "drivers/md/dm-ima.c:dm_ima_measure_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586149584,
      "name": "ima_measure_critical_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int ima_measure_critical_data(const char * event_label, const char * event_name, const void * buf, size_t buf_len, bool hash, u8 * digest, size_t digest_len)
```

```json
{
  "name": "ima_measure_critical_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586387792,
      "name": "ima_measure_critical_data",
      "external": true,
      "loc": "security/integrity/ima/ima_main.c:1063",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ima.c:selinux_ima_measure_state_locked",
        "security/selinux/ima.c:selinux_ima_measure_state_locked",
        "security/integrity/ima/ima_init.c:ima_init",
        "drivers/md/dm-ima.c:dm_ima_measure_data",
        "drivers/md/dm-ima.c:dm_ima_measure_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586387792,
      "name": "ima_measure_critical_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int ima_measure_critical_data(const char * event_label, const char * event_name, const void * buf, size_t buf_len, bool hash, u8 * digest, size_t digest_len)
```

```json
{
  "name": "ima_measure_critical_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586652528,
      "name": "ima_measure_critical_data",
      "external": true,
      "loc": "security/integrity/ima/ima_main.c:1077",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ima.c:selinux_ima_measure_state_locked",
        "security/selinux/ima.c:selinux_ima_measure_state_locked",
        "security/integrity/ima/ima_init.c:ima_init",
        "drivers/md/dm-ima.c:dm_ima_measure_data",
        "drivers/md/dm-ima.c:dm_ima_measure_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586652528,
      "name": "ima_measure_critical_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
void ima_measure_critical_data(const char * event_label, const char * event_name, const void * buf, size_t buf_len, bool hash)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u8 * digest</code>
</li>
<li>
<b>Param added. </b>
<code>size_t digest_len</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
