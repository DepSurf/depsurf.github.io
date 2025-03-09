# Function: <code>mod_check_sig</code>

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
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int mod_check_sig(const struct module_signature * ms, size_t file_len, const char * name)
```

```json
{
  "name": "mod_check_sig",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mod_check_sig",
      "external": true,
      "loc": "kernel/module_signature.c:21",
      "file": "kernel/module_signature.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module_signing.c:mod_verify_sig",
        "security/integrity/ima/ima_modsig.c:ima_read_modsig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580250924,
      "name": "mod_check_sig.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071580250848,
      "name": "mod_check_sig",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int mod_check_sig(const struct module_signature * ms, size_t file_len, const char * name)
```

```json
{
  "name": "mod_check_sig",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mod_check_sig",
      "external": true,
      "loc": "kernel/module_signature.c:21",
      "file": "kernel/module_signature.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module_signing.c:mod_verify_sig",
        "security/integrity/ima/ima_modsig.c:ima_read_modsig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580319404,
      "name": "mod_check_sig.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071580319328,
      "name": "mod_check_sig",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int mod_check_sig(const struct module_signature * ms, size_t file_len, const char * name)
```

```json
{
  "name": "mod_check_sig",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mod_check_sig",
      "external": true,
      "loc": "kernel/module_signature.c:21",
      "file": "kernel/module_signature.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module_signing.c:mod_verify_sig",
        "security/integrity/ima/ima_modsig.c:ima_read_modsig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591314418,
      "name": "mod_check_sig.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071580304512,
      "name": "mod_check_sig",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int mod_check_sig(const struct module_signature * ms, size_t file_len, const char * name)
```

```json
{
  "name": "mod_check_sig",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mod_check_sig",
      "external": true,
      "loc": "kernel/module_signature.c:21",
      "file": "kernel/module_signature.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module_signing.c:mod_verify_sig",
        "security/integrity/ima/ima_modsig.c:ima_read_modsig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591256851,
      "name": "mod_check_sig.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071580308064,
      "name": "mod_check_sig",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int mod_check_sig(const struct module_signature * ms, size_t file_len, const char * name)
```

```json
{
  "name": "mod_check_sig",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mod_check_sig",
      "external": true,
      "loc": "kernel/module_signature.c:21",
      "file": "kernel/module_signature.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module_signing.c:mod_verify_sig",
        "security/integrity/ima/ima_modsig.c:ima_read_modsig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592160059,
      "name": "mod_check_sig.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071580461440,
      "name": "mod_check_sig",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int mod_check_sig(const struct module_signature * ms, size_t file_len, const char * name)
```

```json
{
  "name": "mod_check_sig",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mod_check_sig",
      "external": true,
      "loc": "kernel/module_signature.c:21",
      "file": "kernel/module_signature.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/signing.c:mod_verify_sig",
        "security/integrity/ima/ima_modsig.c:ima_read_modsig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593933169,
      "name": "mod_check_sig.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071580654192,
      "name": "mod_check_sig",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int mod_check_sig(const struct module_signature * ms, size_t file_len, const char * name)
```

```json
{
  "name": "mod_check_sig",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580922032,
      "name": "mod_check_sig",
      "external": true,
      "loc": "kernel/module_signature.c:21",
      "file": "kernel/module_signature.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/signing.c:mod_verify_sig",
        "security/integrity/ima/ima_modsig.c:ima_read_modsig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580922032,
      "name": "mod_check_sig",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
int mod_check_sig(const struct module_signature * ms, size_t file_len, const char * name)
```

```json
{
  "name": "mod_check_sig",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581008976,
      "name": "mod_check_sig",
      "external": true,
      "loc": "kernel/module_signature.c:21",
      "file": "kernel/module_signature.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/signing.c:mod_verify_sig",
        "security/integrity/ima/ima_modsig.c:ima_read_modsig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581008976,
      "name": "mod_check_sig",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
int mod_check_sig(const struct module_signature * ms, size_t file_len, const char * name)
```

```json
{
  "name": "mod_check_sig",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581104848,
      "name": "mod_check_sig",
      "external": true,
      "loc": "kernel/module_signature.c:21",
      "file": "kernel/module_signature.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/signing.c:mod_verify_sig",
        "security/integrity/ima/ima_modsig.c:ima_read_modsig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581104848,
      "name": "mod_check_sig",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int mod_check_sig(const struct module_signature * ms, size_t file_len, const char * name)
```

```json
{
  "name": "mod_check_sig",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491492872,
      "name": "mod_check_sig",
      "external": true,
      "loc": "kernel/module_signature.c:21",
      "file": "kernel/module_signature.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module_signing.c:mod_verify_sig",
        "security/integrity/ima/ima_modsig.c:ima_read_modsig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491492872,
      "name": "mod_check_sig",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int mod_check_sig(const struct module_signature * ms, size_t file_len, const char * name)
```

```json
{
  "name": "mod_check_sig",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225474432,
      "name": "mod_check_sig",
      "external": true,
      "loc": "kernel/module_signature.c:21",
      "file": "kernel/module_signature.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module_signing.c:mod_verify_sig",
        "security/integrity/ima/ima_modsig.c:ima_read_modsig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225474432,
      "name": "mod_check_sig",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
int mod_check_sig(const struct module_signature * ms, size_t file_len, const char * name)
```

```json
{
  "name": "mod_check_sig",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284450112,
      "name": "mod_check_sig",
      "external": true,
      "loc": "kernel/module_signature.c:21",
      "file": "kernel/module_signature.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module_signing.c:mod_verify_sig",
        "security/integrity/ima/ima_modsig.c:ima_read_modsig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284450112,
      "name": "mod_check_sig",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
int mod_check_sig(const struct module_signature * ms, size_t file_len, const char * name)
```

```json
{
  "name": "mod_check_sig",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271936346,
      "name": "mod_check_sig",
      "external": true,
      "loc": "kernel/module_signature.c:21",
      "file": "kernel/module_signature.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module_signing.c:mod_verify_sig",
        "security/integrity/ima/ima_modsig.c:ima_read_modsig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271936346,
      "name": "mod_check_sig",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
int mod_check_sig(const struct module_signature * ms, size_t file_len, const char * name)
```

```json
{
  "name": "mod_check_sig",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mod_check_sig",
      "external": true,
      "loc": "kernel/module_signature.c:21",
      "file": "kernel/module_signature.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module_signing.c:mod_verify_sig",
        "security/integrity/ima/ima_modsig.c:ima_read_modsig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580219724,
      "name": "mod_check_sig.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071580219648,
      "name": "mod_check_sig",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int mod_check_sig(const struct module_signature * ms, size_t file_len, const char * name)
```

```json
{
  "name": "mod_check_sig",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mod_check_sig",
      "external": true,
      "loc": "kernel/module_signature.c:21",
      "file": "kernel/module_signature.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module_signing.c:mod_verify_sig",
        "security/integrity/ima/ima_modsig.c:ima_read_modsig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580167164,
      "name": "mod_check_sig.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071580167088,
      "name": "mod_check_sig",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int mod_check_sig(const struct module_signature * ms, size_t file_len, const char * name)
```

```json
{
  "name": "mod_check_sig",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mod_check_sig",
      "external": true,
      "loc": "kernel/module_signature.c:21",
      "file": "kernel/module_signature.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module_signing.c:mod_verify_sig",
        "security/integrity/ima/ima_modsig.c:ima_read_modsig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580211196,
      "name": "mod_check_sig.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071580211120,
      "name": "mod_check_sig",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int mod_check_sig(const struct module_signature * ms, size_t file_len, const char * name)
```

```json
{
  "name": "mod_check_sig",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mod_check_sig",
      "external": true,
      "loc": "kernel/module_signature.c:21",
      "file": "kernel/module_signature.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module_signing.c:mod_verify_sig",
        "security/integrity/ima/ima_modsig.c:ima_read_modsig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580263900,
      "name": "mod_check_sig.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071580263824,
      "name": "mod_check_sig",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int mod_check_sig(const struct module_signature * ms, size_t file_len, const char * name)
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
