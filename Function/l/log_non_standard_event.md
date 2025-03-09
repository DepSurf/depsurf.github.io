# Function: <code>log_non_standard_event</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void log_non_standard_event(const uuid_le * sec_type, const uuid_le * fru_id, const char * fru_text, const u8 sev, const u8 * err, const u32 len)
```

```json
{
  "name": "log_non_standard_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586859408,
      "name": "log_non_standard_event",
      "external": true,
      "loc": "drivers/ras/ras.c:16",
      "file": "drivers/ras/ras.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586859408,
      "name": "log_non_standard_event",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void log_non_standard_event(const uuid_le * sec_type, const uuid_le * fru_id, const char * fru_text, const u8 sev, const u8 * err, const u32 len)
```

```json
{
  "name": "log_non_standard_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587347136,
      "name": "log_non_standard_event",
      "external": true,
      "loc": "drivers/ras/ras.c:17",
      "file": "drivers/ras/ras.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/apei/ghes.c:ghes_do_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587347136,
      "name": "log_non_standard_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
void log_non_standard_event(const uuid_le * sec_type, const uuid_le * fru_id, const char * fru_text, const u8 sev, const u8 * err, const u32 len)
```

```json
{
  "name": "log_non_standard_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587650480,
      "name": "log_non_standard_event",
      "external": true,
      "loc": "drivers/ras/ras.c:17",
      "file": "drivers/ras/ras.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587650480,
      "name": "log_non_standard_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
void log_non_standard_event(const uuid_le * sec_type, const uuid_le * fru_id, const char * fru_text, const u8 sev, const u8 * err, const u32 len)
```

```json
{
  "name": "log_non_standard_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587780480,
      "name": "log_non_standard_event",
      "external": true,
      "loc": "drivers/ras/ras.c:17",
      "file": "drivers/ras/ras.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587780480,
      "name": "log_non_standard_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
void log_non_standard_event(const guid_t * sec_type, const guid_t * fru_id, const char * fru_text, const u8 sev, const u8 * err, const u32 len)
```

```json
{
  "name": "log_non_standard_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588085488,
      "name": "log_non_standard_event",
      "external": true,
      "loc": "drivers/ras/ras.c:17",
      "file": "drivers/ras/ras.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588085488,
      "name": "log_non_standard_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
void log_non_standard_event(const guid_t * sec_type, const guid_t * fru_id, const char * fru_text, const u8 sev, const u8 * err, const u32 len)
```

```json
{
  "name": "log_non_standard_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588291296,
      "name": "log_non_standard_event",
      "external": true,
      "loc": "drivers/ras/ras.c:17",
      "file": "drivers/ras/ras.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588291296,
      "name": "log_non_standard_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
void log_non_standard_event(const guid_t * sec_type, const guid_t * fru_id, const char * fru_text, const u8 sev, const u8 * err, const u32 len)
```

```json
{
  "name": "log_non_standard_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589171840,
      "name": "log_non_standard_event",
      "external": true,
      "loc": "drivers/ras/ras.c:17",
      "file": "drivers/ras/ras.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589171840,
      "name": "log_non_standard_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
void log_non_standard_event(const guid_t * sec_type, const guid_t * fru_id, const char * fru_text, const u8 sev, const u8 * err, const u32 len)
```

```json
{
  "name": "log_non_standard_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589168688,
      "name": "log_non_standard_event",
      "external": true,
      "loc": "drivers/ras/ras.c:17",
      "file": "drivers/ras/ras.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589168688,
      "name": "log_non_standard_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
void log_non_standard_event(const guid_t * sec_type, const guid_t * fru_id, const char * fru_text, const u8 sev, const u8 * err, const u32 len)
```

```json
{
  "name": "log_non_standard_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589062576,
      "name": "log_non_standard_event",
      "external": true,
      "loc": "drivers/ras/ras.c:17",
      "file": "drivers/ras/ras.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589062576,
      "name": "log_non_standard_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
void log_non_standard_event(const guid_t * sec_type, const guid_t * fru_id, const char * fru_text, const u8 sev, const u8 * err, const u32 len)
```

```json
{
  "name": "log_non_standard_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589780832,
      "name": "log_non_standard_event",
      "external": true,
      "loc": "drivers/ras/ras.c:17",
      "file": "drivers/ras/ras.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589780832,
      "name": "log_non_standard_event",
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
void log_non_standard_event(const guid_t * sec_type, const guid_t * fru_id, const char * fru_text, const u8 sev, const u8 * err, const u32 len)
```

```json
{
  "name": "log_non_standard_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591291648,
      "name": "log_non_standard_event",
      "external": true,
      "loc": "drivers/ras/ras.c:17",
      "file": "drivers/ras/ras.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591291648,
      "name": "log_non_standard_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
void log_non_standard_event(const guid_t * sec_type, const guid_t * fru_id, const char * fru_text, const u8 sev, const u8 * err, const u32 len)
```

```json
{
  "name": "log_non_standard_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593041744,
      "name": "log_non_standard_event",
      "external": true,
      "loc": "drivers/ras/ras.c:17",
      "file": "drivers/ras/ras.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593041744,
      "name": "log_non_standard_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
void log_non_standard_event(const guid_t * sec_type, const guid_t * fru_id, const char * fru_text, const u8 sev, const u8 * err, const u32 len)
```

```json
{
  "name": "log_non_standard_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593493840,
      "name": "log_non_standard_event",
      "external": true,
      "loc": "drivers/ras/ras.c:17",
      "file": "drivers/ras/ras.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593493840,
      "name": "log_non_standard_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
void log_non_standard_event(const guid_t * sec_type, const guid_t * fru_id, const char * fru_text, const u8 sev, const u8 * err, const u32 len)
```

```json
{
  "name": "log_non_standard_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594241120,
      "name": "log_non_standard_event",
      "external": true,
      "loc": "drivers/ras/ras.c:17",
      "file": "drivers/ras/ras.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594241120,
      "name": "log_non_standard_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
void log_non_standard_event(const guid_t * sec_type, const guid_t * fru_id, const char * fru_text, const u8 sev, const u8 * err, const u32 len)
```

```json
{
  "name": "log_non_standard_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501814096,
      "name": "log_non_standard_event",
      "external": true,
      "loc": "drivers/ras/ras.c:17",
      "file": "drivers/ras/ras.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501814096,
      "name": "log_non_standard_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
void log_non_standard_event(const guid_t * sec_type, const guid_t * fru_id, const char * fru_text, const u8 sev, const u8 * err, const u32 len)
```

```json
{
  "name": "log_non_standard_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234333564,
      "name": "log_non_standard_event",
      "external": true,
      "loc": "drivers/ras/ras.c:17",
      "file": "drivers/ras/ras.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3234333564,
      "name": "log_non_standard_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
void log_non_standard_event(const guid_t * sec_type, const guid_t * fru_id, const char * fru_text, const u8 sev, const u8 * err, const u32 len)
```

```json
{
  "name": "log_non_standard_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295210336,
      "name": "log_non_standard_event",
      "external": true,
      "loc": "drivers/ras/ras.c:17",
      "file": "drivers/ras/ras.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295210336,
      "name": "log_non_standard_event",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void log_non_standard_event(const guid_t * sec_type, const guid_t * fru_id, const char * fru_text, const u8 sev, const u8 * err, const u32 len)
```

```json
{
  "name": "log_non_standard_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278161410,
      "name": "log_non_standard_event",
      "external": true,
      "loc": "drivers/ras/ras.c:17",
      "file": "drivers/ras/ras.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278161410,
      "name": "log_non_standard_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void log_non_standard_event(const guid_t * sec_type, const guid_t * fru_id, const char * fru_text, const u8 sev, const u8 * err, const u32 len)
```

```json
{
  "name": "log_non_standard_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587895056,
      "name": "log_non_standard_event",
      "external": true,
      "loc": "drivers/ras/ras.c:17",
      "file": "drivers/ras/ras.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587895056,
      "name": "log_non_standard_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
void log_non_standard_event(const guid_t * sec_type, const guid_t * fru_id, const char * fru_text, const u8 sev, const u8 * err, const u32 len)
```

```json
{
  "name": "log_non_standard_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587614336,
      "name": "log_non_standard_event",
      "external": true,
      "loc": "drivers/ras/ras.c:17",
      "file": "drivers/ras/ras.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587614336,
      "name": "log_non_standard_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
void log_non_standard_event(const guid_t * sec_type, const guid_t * fru_id, const char * fru_text, const u8 sev, const u8 * err, const u32 len)
```

```json
{
  "name": "log_non_standard_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588228352,
      "name": "log_non_standard_event",
      "external": true,
      "loc": "drivers/ras/ras.c:17",
      "file": "drivers/ras/ras.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588228352,
      "name": "log_non_standard_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
void log_non_standard_event(const guid_t * sec_type, const guid_t * fru_id, const char * fru_text, const u8 sev, const u8 * err, const u32 len)
```

```json
{
  "name": "log_non_standard_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588363648,
      "name": "log_non_standard_event",
      "external": true,
      "loc": "drivers/ras/ras.c:17",
      "file": "drivers/ras/ras.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588363648,
      "name": "log_non_standard_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void log_non_standard_event(const uuid_le * sec_type, const uuid_le * fru_id, const char * fru_text, const u8 sev, const u8 * err, const u32 len)
```
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
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const uuid_le * sec_type</code> ➡️ <code>const guid_t * sec_type</code>
</li>
<li>
<b>Param type changed. </b>
<code>const uuid_le * fru_id</code> ➡️ <code>const guid_t * fru_id</code>
</li>
</ul>
</details>
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
