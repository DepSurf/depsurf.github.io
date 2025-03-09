# Function: <code>verify_pefile_signature</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int verify_pefile_signature(const void * pebuf, unsigned int pelen, struct key * trusted_keyring, enum key_being_used_for usage, bool * _trusted)
```

```json
{
  "name": "verify_pefile_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582710176,
      "name": "verify_pefile_signature",
      "external": true,
      "loc": "crypto/asymmetric_keys/verify_pefile.c:420",
      "file": "crypto/asymmetric_keys/verify_pefile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kexec-bzimage64.c:bzImage64_verify_sig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582710176,
      "name": "verify_pefile_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1524
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
int verify_pefile_signature(const void * pebuf, unsigned int pelen, struct key * trusted_keys, enum key_being_used_for usage)
```

```json
{
  "name": "verify_pefile_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582986336,
      "name": "verify_pefile_signature",
      "external": true,
      "loc": "crypto/asymmetric_keys/verify_pefile.c:419",
      "file": "crypto/asymmetric_keys/verify_pefile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kexec-bzimage64.c:bzImage64_verify_sig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582986336,
      "name": "verify_pefile_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2522
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
int verify_pefile_signature(const void * pebuf, unsigned int pelen, struct key * trusted_keys, enum key_being_used_for usage)
```

```json
{
  "name": "verify_pefile_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583090896,
      "name": "verify_pefile_signature",
      "external": true,
      "loc": "crypto/asymmetric_keys/verify_pefile.c:419",
      "file": "crypto/asymmetric_keys/verify_pefile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kexec-bzimage64.c:bzImage64_verify_sig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583090896,
      "name": "verify_pefile_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2522
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
int verify_pefile_signature(const void * pebuf, unsigned int pelen, struct key * trusted_keys, enum key_being_used_for usage)
```

```json
{
  "name": "verify_pefile_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583148576,
      "name": "verify_pefile_signature",
      "external": true,
      "loc": "crypto/asymmetric_keys/verify_pefile.c:419",
      "file": "crypto/asymmetric_keys/verify_pefile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kexec-bzimage64.c:bzImage64_verify_sig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583148576,
      "name": "verify_pefile_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1321
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
int verify_pefile_signature(const void * pebuf, unsigned int pelen, struct key * trusted_keys, enum key_being_used_for usage)
```

```json
{
  "name": "verify_pefile_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583322496,
      "name": "verify_pefile_signature",
      "external": true,
      "loc": "crypto/asymmetric_keys/verify_pefile.c:419",
      "file": "crypto/asymmetric_keys/verify_pefile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kexec-bzimage64.c:bzImage64_verify_sig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583322496,
      "name": "verify_pefile_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2559
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
int verify_pefile_signature(const void * pebuf, unsigned int pelen, struct key * trusted_keys, enum key_being_used_for usage)
```

```json
{
  "name": "verify_pefile_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583531184,
      "name": "verify_pefile_signature",
      "external": true,
      "loc": "crypto/asymmetric_keys/verify_pefile.c:419",
      "file": "crypto/asymmetric_keys/verify_pefile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kexec-bzimage64.c:bzImage64_verify_sig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583531184,
      "name": "verify_pefile_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2558
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
int verify_pefile_signature(const void * pebuf, unsigned int pelen, struct key * trusted_keys, enum key_being_used_for usage)
```

```json
{
  "name": "verify_pefile_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583654608,
      "name": "verify_pefile_signature",
      "external": true,
      "loc": "crypto/asymmetric_keys/verify_pefile.c:419",
      "file": "crypto/asymmetric_keys/verify_pefile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kexec-bzimage64.c:bzImage64_verify_sig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583654608,
      "name": "verify_pefile_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2579
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
int verify_pefile_signature(const void * pebuf, unsigned int pelen, struct key * trusted_keys, enum key_being_used_for usage)
```

```json
{
  "name": "verify_pefile_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583842752,
      "name": "verify_pefile_signature",
      "external": true,
      "loc": "crypto/asymmetric_keys/verify_pefile.c:416",
      "file": "crypto/asymmetric_keys/verify_pefile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kexec-bzimage64.c:bzImage64_verify_sig",
        "arch/x86/kernel/kexec-bzimage64.c:bzImage64_verify_sig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583842752,
      "name": "verify_pefile_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1337
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
int verify_pefile_signature(const void * pebuf, unsigned int pelen, struct key * trusted_keys, enum key_being_used_for usage)
```

```json
{
  "name": "verify_pefile_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583944864,
      "name": "verify_pefile_signature",
      "external": true,
      "loc": "crypto/asymmetric_keys/verify_pefile.c:416",
      "file": "crypto/asymmetric_keys/verify_pefile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kexec-bzimage64.c:bzImage64_verify_sig",
        "arch/x86/kernel/kexec-bzimage64.c:bzImage64_verify_sig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583944864,
      "name": "verify_pefile_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1337
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
int verify_pefile_signature(const void * pebuf, unsigned int pelen, struct key * trusted_keys, enum key_being_used_for usage)
```

```json
{
  "name": "verify_pefile_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584337520,
      "name": "verify_pefile_signature",
      "external": true,
      "loc": "crypto/asymmetric_keys/verify_pefile.c:416",
      "file": "crypto/asymmetric_keys/verify_pefile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kexec-bzimage64.c:bzImage64_verify_sig",
        "arch/x86/kernel/kexec-bzimage64.c:bzImage64_verify_sig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584337520,
      "name": "verify_pefile_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
int verify_pefile_signature(const void * pebuf, unsigned int pelen, struct key * trusted_keys, enum key_being_used_for usage)
```

```json
{
  "name": "verify_pefile_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584455120,
      "name": "verify_pefile_signature",
      "external": true,
      "loc": "crypto/asymmetric_keys/verify_pefile.c:416",
      "file": "crypto/asymmetric_keys/verify_pefile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kexec-bzimage64.c:bzImage64_verify_sig",
        "arch/x86/kernel/kexec-bzimage64.c:bzImage64_verify_sig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584455120,
      "name": "verify_pefile_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
int verify_pefile_signature(const void * pebuf, unsigned int pelen, struct key * trusted_keys, enum key_being_used_for usage)
```

```json
{
  "name": "verify_pefile_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584490208,
      "name": "verify_pefile_signature",
      "external": true,
      "loc": "crypto/asymmetric_keys/verify_pefile.c:416",
      "file": "crypto/asymmetric_keys/verify_pefile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kexec-bzimage64.c:bzImage64_verify_sig",
        "arch/x86/kernel/kexec-bzimage64.c:bzImage64_verify_sig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584490208,
      "name": "verify_pefile_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
int verify_pefile_signature(const void * pebuf, unsigned int pelen, struct key * trusted_keys, enum key_being_used_for usage)
```

```json
{
  "name": "verify_pefile_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584888544,
      "name": "verify_pefile_signature",
      "external": true,
      "loc": "crypto/asymmetric_keys/verify_pefile.c:416",
      "file": "crypto/asymmetric_keys/verify_pefile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kexec-bzimage64.c:bzImage64_verify_sig",
        "arch/x86/kernel/kexec-bzimage64.c:bzImage64_verify_sig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584888544,
      "name": "verify_pefile_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 227
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
int verify_pefile_signature(const void * pebuf, unsigned int pelen, struct key * trusted_keys, enum key_being_used_for usage)
```

```json
{
  "name": "verify_pefile_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585586368,
      "name": "verify_pefile_signature",
      "external": true,
      "loc": "crypto/asymmetric_keys/verify_pefile.c:416",
      "file": "crypto/asymmetric_keys/verify_pefile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:kexec_kernel_verify_pe_sig",
        "kernel/kexec_file.c:kexec_kernel_verify_pe_sig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585586368,
      "name": "verify_pefile_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 245
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
int verify_pefile_signature(const void * pebuf, unsigned int pelen, struct key * trusted_keys, enum key_being_used_for usage)
```

```json
{
  "name": "verify_pefile_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586352576,
      "name": "verify_pefile_signature",
      "external": true,
      "loc": "crypto/asymmetric_keys/verify_pefile.c:416",
      "file": "crypto/asymmetric_keys/verify_pefile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:kexec_kernel_verify_pe_sig",
        "kernel/kexec_file.c:kexec_kernel_verify_pe_sig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586352576,
      "name": "verify_pefile_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 245
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
int verify_pefile_signature(const void * pebuf, unsigned int pelen, struct key * trusted_keys, enum key_being_used_for usage)
```

```json
{
  "name": "verify_pefile_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586599184,
      "name": "verify_pefile_signature",
      "external": true,
      "loc": "crypto/asymmetric_keys/verify_pefile.c:420",
      "file": "crypto/asymmetric_keys/verify_pefile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:kexec_kernel_verify_pe_sig",
        "kernel/kexec_file.c:kexec_kernel_verify_pe_sig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586599184,
      "name": "verify_pefile_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 245
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
int verify_pefile_signature(const void * pebuf, unsigned int pelen, struct key * trusted_keys, enum key_being_used_for usage)
```

```json
{
  "name": "verify_pefile_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586868528,
      "name": "verify_pefile_signature",
      "external": true,
      "loc": "crypto/asymmetric_keys/verify_pefile.c:420",
      "file": "crypto/asymmetric_keys/verify_pefile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:kexec_kernel_verify_pe_sig",
        "kernel/kexec_file.c:kexec_kernel_verify_pe_sig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586868528,
      "name": "verify_pefile_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 245
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
int verify_pefile_signature(const void * pebuf, unsigned int pelen, struct key * trusted_keys, enum key_being_used_for usage)
```

```json
{
  "name": "verify_pefile_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495765024,
      "name": "verify_pefile_signature",
      "external": true,
      "loc": "crypto/asymmetric_keys/verify_pefile.c:416",
      "file": "crypto/asymmetric_keys/verify_pefile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495765024,
      "name": "verify_pefile_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1336
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
int verify_pefile_signature(const void * pebuf, unsigned int pelen, struct key * trusted_keys, enum key_being_used_for usage)
```

```json
{
  "name": "verify_pefile_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229116756,
      "name": "verify_pefile_signature",
      "external": true,
      "loc": "crypto/asymmetric_keys/verify_pefile.c:416",
      "file": "crypto/asymmetric_keys/verify_pefile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3229116756,
      "name": "verify_pefile_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1868
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
int verify_pefile_signature(const void * pebuf, unsigned int pelen, struct key * trusted_keys, enum key_being_used_for usage)
```

```json
{
  "name": "verify_pefile_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289935584,
      "name": "verify_pefile_signature",
      "external": true,
      "loc": "crypto/asymmetric_keys/verify_pefile.c:416",
      "file": "crypto/asymmetric_keys/verify_pefile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289935584,
      "name": "verify_pefile_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1704
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
int verify_pefile_signature(const void * pebuf, unsigned int pelen, struct key * trusted_keys, enum key_being_used_for usage)
```

```json
{
  "name": "verify_pefile_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274910384,
      "name": "verify_pefile_signature",
      "external": true,
      "loc": "crypto/asymmetric_keys/verify_pefile.c:416",
      "file": "crypto/asymmetric_keys/verify_pefile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274910384,
      "name": "verify_pefile_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2272
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
int verify_pefile_signature(const void * pebuf, unsigned int pelen, struct key * trusted_keys, enum key_being_used_for usage)
```

```json
{
  "name": "verify_pefile_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583913600,
      "name": "verify_pefile_signature",
      "external": true,
      "loc": "crypto/asymmetric_keys/verify_pefile.c:416",
      "file": "crypto/asymmetric_keys/verify_pefile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kexec-bzimage64.c:bzImage64_verify_sig",
        "arch/x86/kernel/kexec-bzimage64.c:bzImage64_verify_sig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583913600,
      "name": "verify_pefile_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1337
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
int verify_pefile_signature(const void * pebuf, unsigned int pelen, struct key * trusted_keys, enum key_being_used_for usage)
```

```json
{
  "name": "verify_pefile_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583850656,
      "name": "verify_pefile_signature",
      "external": true,
      "loc": "crypto/asymmetric_keys/verify_pefile.c:416",
      "file": "crypto/asymmetric_keys/verify_pefile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kexec-bzimage64.c:bzImage64_verify_sig",
        "arch/x86/kernel/kexec-bzimage64.c:bzImage64_verify_sig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583850656,
      "name": "verify_pefile_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1337
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
int verify_pefile_signature(const void * pebuf, unsigned int pelen, struct key * trusted_keys, enum key_being_used_for usage)
```

```json
{
  "name": "verify_pefile_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583897360,
      "name": "verify_pefile_signature",
      "external": true,
      "loc": "crypto/asymmetric_keys/verify_pefile.c:416",
      "file": "crypto/asymmetric_keys/verify_pefile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583897360,
      "name": "verify_pefile_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1337
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
int verify_pefile_signature(const void * pebuf, unsigned int pelen, struct key * trusted_keys, enum key_being_used_for usage)
```

```json
{
  "name": "verify_pefile_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583998400,
      "name": "verify_pefile_signature",
      "external": true,
      "loc": "crypto/asymmetric_keys/verify_pefile.c:416",
      "file": "crypto/asymmetric_keys/verify_pefile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kexec-bzimage64.c:bzImage64_verify_sig",
        "arch/x86/kernel/kexec-bzimage64.c:bzImage64_verify_sig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583998400,
      "name": "verify_pefile_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1337
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct key * trusted_keys</code>
</li>
<li>
<b>Param removed. </b>
<code>struct key * trusted_keyring</code>
</li>
<li>
<b>Param removed. </b>
<code>bool * _trusted</code>
</li>
</ul>
</details>
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
