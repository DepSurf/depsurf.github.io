# Function: <code>process_buffer_measurement</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "process_buffer_measurement",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583676864,
      "name": "process_buffer_measurement",
      "external": false,
      "loc": "security/integrity/ima/ima_main.c:618",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_kexec_cmdline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583676864,
      "name": "process_buffer_measurement.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 376
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
void process_buffer_measurement(const void * buf, int size, const char * eventname, enum ima_hooks func, int pcr)
```

```json
{
  "name": "process_buffer_measurement",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "process_buffer_measurement",
      "external": true,
      "loc": "security/integrity/ima/ima_main.c:638",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_kexec_cmdline",
        "security/integrity/ima/ima_appraise.c:ima_check_blacklist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583788657,
      "name": "process_buffer_measurement.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071583788000,
      "name": "process_buffer_measurement",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 527
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void process_buffer_measurement(const void * buf, int size, const char * eventname, enum ima_hooks func, int pcr, const char * keyring)
```

```json
{
  "name": "process_buffer_measurement",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "process_buffer_measurement",
      "external": true,
      "loc": "security/integrity/ima/ima_main.c:738",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_kexec_cmdline",
        "security/integrity/ima/ima_appraise.c:ima_check_blacklist",
        "security/integrity/ima/ima_asymmetric_keys.c:ima_post_key_create_or_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584179828,
      "name": "process_buffer_measurement.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071584179136,
      "name": "process_buffer_measurement",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 550
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
void process_buffer_measurement(struct inode * inode, const void * buf, int size, const char * eventname, enum ima_hooks func, int pcr, const char * keyring)
```

```json
{
  "name": "process_buffer_measurement",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584298288,
      "name": "process_buffer_measurement",
      "external": true,
      "loc": "security/integrity/ima/ima_main.c:823",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_kexec_cmdline",
        "security/integrity/ima/ima_appraise.c:ima_check_blacklist",
        "security/integrity/ima/ima_asymmetric_keys.c:ima_post_key_create_or_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584298288,
      "name": "process_buffer_measurement",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 633
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void process_buffer_measurement(struct user_namespace * mnt_userns, struct inode * inode, const void * buf, int size, const char * eventname, enum ima_hooks func, int pcr, const char * func_data, bool buf_hash)
```

```json
{
  "name": "process_buffer_measurement",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "process_buffer_measurement",
      "external": true,
      "loc": "security/integrity/ima/ima_main.c:839",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_measure_critical_data",
        "security/integrity/ima/ima_main.c:ima_kexec_cmdline",
        "security/integrity/ima/ima_appraise.c:ima_check_blacklist",
        "security/integrity/ima/ima_asymmetric_keys.c:ima_post_key_create_or_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591312410,
      "name": "process_buffer_measurement.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071584332400,
      "name": "process_buffer_measurement",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 820
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
int process_buffer_measurement(struct user_namespace * mnt_userns, struct inode * inode, const void * buf, int size, const char * eventname, enum ima_hooks func, int pcr, const char * func_data, bool buf_hash, u8 * digest, size_t digest_len)
```

```json
{
  "name": "process_buffer_measurement",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "process_buffer_measurement",
      "external": true,
      "loc": "security/integrity/ima/ima_main.c:862",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_measure_critical_data",
        "security/integrity/ima/ima_main.c:ima_kexec_cmdline",
        "security/integrity/ima/ima_appraise.c:ima_check_blacklist",
        "security/integrity/ima/ima_asymmetric_keys.c:ima_post_key_create_or_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592308335,
      "name": "process_buffer_measurement.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071584720128,
      "name": "process_buffer_measurement",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1211
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
int process_buffer_measurement(struct user_namespace * mnt_userns, struct inode * inode, const void * buf, int size, const char * eventname, enum ima_hooks func, int pcr, const char * func_data, bool buf_hash, u8 * digest, size_t digest_len)
```

```json
{
  "name": "process_buffer_measurement",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "process_buffer_measurement",
      "external": true,
      "loc": "security/integrity/ima/ima_main.c:885",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_measure_critical_data",
        "security/integrity/ima/ima_main.c:ima_kexec_cmdline",
        "security/integrity/ima/ima_appraise.c:ima_check_blacklist",
        "security/integrity/ima/ima_asymmetric_keys.c:ima_post_key_create_or_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594090647,
      "name": "process_buffer_measurement.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071585395280,
      "name": "process_buffer_measurement",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1255
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
int process_buffer_measurement(struct user_namespace * mnt_userns, struct inode * inode, const void * buf, int size, const char * eventname, enum ima_hooks func, int pcr, const char * func_data, bool buf_hash, u8 * digest, size_t digest_len)
```

```json
{
  "name": "process_buffer_measurement",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586148288,
      "name": "process_buffer_measurement",
      "external": true,
      "loc": "security/integrity/ima/ima_main.c:895",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_measure_critical_data",
        "security/integrity/ima/ima_main.c:ima_kexec_cmdline",
        "security/integrity/ima/ima_appraise.c:ima_check_blacklist",
        "security/integrity/ima/ima_asymmetric_keys.c:ima_post_key_create_or_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586148288,
      "name": "process_buffer_measurement",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1267
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
int process_buffer_measurement(struct mnt_idmap * idmap, struct inode * inode, const void * buf, int size, const char * eventname, enum ima_hooks func, int pcr, const char * func_data, bool buf_hash, u8 * digest, size_t digest_len)
```

```json
{
  "name": "process_buffer_measurement",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586386496,
      "name": "process_buffer_measurement",
      "external": true,
      "loc": "security/integrity/ima/ima_main.c:914",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_measure_critical_data",
        "security/integrity/ima/ima_main.c:ima_kexec_cmdline",
        "security/integrity/ima/ima_appraise.c:ima_check_blacklist",
        "security/integrity/ima/ima_asymmetric_keys.c:ima_post_key_create_or_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586386496,
      "name": "process_buffer_measurement",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1267
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
int process_buffer_measurement(struct mnt_idmap * idmap, struct inode * inode, const void * buf, int size, const char * eventname, enum ima_hooks func, int pcr, const char * func_data, bool buf_hash, u8 * digest, size_t digest_len)
```

```json
{
  "name": "process_buffer_measurement",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586651296,
      "name": "process_buffer_measurement",
      "external": true,
      "loc": "security/integrity/ima/ima_main.c:928",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_measure_critical_data",
        "security/integrity/ima/ima_main.c:ima_kexec_cmdline",
        "security/integrity/ima/ima_appraise.c:ima_check_blacklist",
        "security/integrity/ima/ima_asymmetric_keys.c:ima_post_key_create_or_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586651296,
      "name": "process_buffer_measurement",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1211
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
void process_buffer_measurement(const void * buf, int size, const char * eventname, enum ima_hooks func, int pcr)
```

```json
{
  "name": "process_buffer_measurement",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495591200,
      "name": "process_buffer_measurement",
      "external": true,
      "loc": "security/integrity/ima/ima_main.c:638",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_kexec_cmdline",
        "security/integrity/ima/ima_appraise.c:ima_check_blacklist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495591200,
      "name": "process_buffer_measurement",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 500
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
void process_buffer_measurement(const void * buf, int size, const char * eventname, enum ima_hooks func, int pcr)
```

```json
{
  "name": "process_buffer_measurement",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228952092,
      "name": "process_buffer_measurement",
      "external": true,
      "loc": "security/integrity/ima/ima_main.c:638",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_kexec_cmdline",
        "security/integrity/ima/ima_appraise.c:ima_check_blacklist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228952092,
      "name": "process_buffer_measurement",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 544
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
void process_buffer_measurement(const void * buf, int size, const char * eventname, enum ima_hooks func, int pcr)
```

```json
{
  "name": "process_buffer_measurement",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289692464,
      "name": "process_buffer_measurement",
      "external": true,
      "loc": "security/integrity/ima/ima_main.c:638",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_kexec_cmdline",
        "security/integrity/ima/ima_appraise.c:ima_check_blacklist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289692464,
      "name": "process_buffer_measurement",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 632
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
void process_buffer_measurement(const void * buf, int size, const char * eventname, enum ima_hooks func, int pcr)
```

```json
{
  "name": "process_buffer_measurement",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274755254,
      "name": "process_buffer_measurement",
      "external": true,
      "loc": "security/integrity/ima/ima_main.c:638",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_kexec_cmdline",
        "security/integrity/ima/ima_appraise.c:ima_check_blacklist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274755254,
      "name": "process_buffer_measurement",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 486
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
void process_buffer_measurement(const void * buf, int size, const char * eventname, enum ima_hooks func, int pcr)
```

```json
{
  "name": "process_buffer_measurement",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "process_buffer_measurement",
      "external": true,
      "loc": "security/integrity/ima/ima_main.c:638",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_kexec_cmdline",
        "security/integrity/ima/ima_appraise.c:ima_check_blacklist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583757393,
      "name": "process_buffer_measurement.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071583756736,
      "name": "process_buffer_measurement",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 527
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
void process_buffer_measurement(const void * buf, int size, const char * eventname, enum ima_hooks func, int pcr)
```

```json
{
  "name": "process_buffer_measurement",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "process_buffer_measurement",
      "external": true,
      "loc": "security/integrity/ima/ima_main.c:638",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_kexec_cmdline",
        "security/integrity/ima/ima_appraise.c:ima_check_blacklist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583694449,
      "name": "process_buffer_measurement.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071583693792,
      "name": "process_buffer_measurement",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 527
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
void process_buffer_measurement(const void * buf, int size, const char * eventname, enum ima_hooks func, int pcr)
```

```json
{
  "name": "process_buffer_measurement",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "process_buffer_measurement",
      "external": true,
      "loc": "security/integrity/ima/ima_main.c:638",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_kexec_cmdline",
        "security/integrity/ima/ima_appraise.c:ima_check_blacklist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583741153,
      "name": "process_buffer_measurement.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071583740496,
      "name": "process_buffer_measurement",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 527
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
void process_buffer_measurement(const void * buf, int size, const char * eventname, enum ima_hooks func, int pcr)
```

```json
{
  "name": "process_buffer_measurement",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "process_buffer_measurement",
      "external": true,
      "loc": "security/integrity/ima/ima_main.c:638",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_kexec_cmdline",
        "security/integrity/ima/ima_appraise.c:ima_check_blacklist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583842097,
      "name": "process_buffer_measurement.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071583841440,
      "name": "process_buffer_measurement",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 527
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
void process_buffer_measurement(const void * buf, int size, const char * eventname, enum ima_hooks func, int pcr)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const char * keyring</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct inode * inode</code>
</li>
<li>
<b>Param reordered. </b>
<code>buf, size, eventname, func, pcr, keyring</code> ➡️ <code>inode, buf, size, eventname, func, pcr, keyring</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct user_namespace * mnt_userns</code>
</li>
<li>
<b>Param added. </b>
<code>const char * func_data</code>
</li>
<li>
<b>Param added. </b>
<code>bool buf_hash</code>
</li>
<li>
<b>Param removed. </b>
<code>const char * keyring</code>
</li>
<li>
<b>Param reordered. </b>
<code>inode, buf, size, eventname, func, pcr, keyring</code> ➡️ <code>mnt_userns, inode, buf, size, eventname, func, pcr, func_data, buf_hash</code>
</li>
</ul>
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mnt_idmap * idmap</code>
</li>
<li>
<b>Param removed. </b>
<code>struct user_namespace * mnt_userns</code>
</li>
</ul>
</details>
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
