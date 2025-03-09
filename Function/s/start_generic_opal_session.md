# Function: <code>start_generic_opal_session</code>

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
int start_generic_opal_session(struct opal_dev * dev, enum opal_uid auth, enum opal_uid sp_type, const char * key, u8 key_len)
```

```json
{
  "name": "start_generic_opal_session",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583424336,
      "name": "start_generic_opal_session",
      "external": false,
      "loc": "block/sed-opal.c:1228",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:start_admin1LSP_opal_session",
        "block/sed-opal.c:start_anybodyASP_opal_session"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583424336,
      "name": "start_generic_opal_session",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 972
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
int start_generic_opal_session(struct opal_dev * dev, enum opal_uid auth, enum opal_uid sp_type, const char * key, u8 key_len)
```

```json
{
  "name": "start_generic_opal_session",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583604016,
      "name": "start_generic_opal_session",
      "external": false,
      "loc": "block/sed-opal.c:1240",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:start_admin1LSP_opal_session",
        "block/sed-opal.c:start_anybodyASP_opal_session"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583604016,
      "name": "start_generic_opal_session",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 972
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
int start_generic_opal_session(struct opal_dev * dev, enum opal_uid auth, enum opal_uid sp_type, const char * key, u8 key_len)
```

```json
{
  "name": "start_generic_opal_session",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583820352,
      "name": "start_generic_opal_session",
      "external": false,
      "loc": "block/sed-opal.c:1257",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:start_admin1LSP_opal_session",
        "block/sed-opal.c:start_anybodyASP_opal_session"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583820352,
      "name": "start_generic_opal_session",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 961
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
int start_generic_opal_session(struct opal_dev * dev, enum opal_uid auth, enum opal_uid sp_type, const char * key, u8 key_len)
```

```json
{
  "name": "start_generic_opal_session",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583903664,
      "name": "start_generic_opal_session",
      "external": false,
      "loc": "block/sed-opal.c:1257",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:start_admin1LSP_opal_session",
        "block/sed-opal.c:start_anybodyASP_opal_session"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583903664,
      "name": "start_generic_opal_session",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 961
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "start_generic_opal_session",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584087637,
      "name": "start_generic_opal_session",
      "external": false,
      "loc": "block/sed-opal.c:1322",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/sed-opal.c:start_PSID_opal_session",
        "block/sed-opal.c:start_admin1LSP_opal_session",
        "block/sed-opal.c:start_anybodyASP_opal_session"
      ],
      "caller_func": [
        "block/sed-opal.c:start_PSID_opal_session",
        "block/sed-opal.c:start_admin1LSP_opal_session",
        "block/sed-opal.c:start_anybodyASP_opal_session"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584087088,
      "name": "start_generic_opal_session.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 450
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "start_generic_opal_session",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584210341,
      "name": "start_generic_opal_session",
      "external": false,
      "loc": "block/sed-opal.c:1327",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/sed-opal.c:start_PSID_opal_session",
        "block/sed-opal.c:start_admin1LSP_opal_session",
        "block/sed-opal.c:start_anybodyASP_opal_session"
      ],
      "caller_func": [
        "block/sed-opal.c:start_PSID_opal_session",
        "block/sed-opal.c:start_admin1LSP_opal_session",
        "block/sed-opal.c:start_anybodyASP_opal_session"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584209792,
      "name": "start_generic_opal_session.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 450
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "start_generic_opal_session",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584611861,
      "name": "start_generic_opal_session",
      "external": false,
      "loc": "block/sed-opal.c:1398",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/sed-opal.c:start_PSID_opal_session",
        "block/sed-opal.c:start_admin1LSP_opal_session",
        "block/sed-opal.c:start_anybodyASP_opal_session"
      ],
      "caller_func": [
        "block/sed-opal.c:start_PSID_opal_session",
        "block/sed-opal.c:start_admin1LSP_opal_session",
        "block/sed-opal.c:start_anybodyASP_opal_session"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584611184,
      "name": "start_generic_opal_session.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 444
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "start_generic_opal_session",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584730709,
      "name": "start_generic_opal_session",
      "external": false,
      "loc": "block/sed-opal.c:1398",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/sed-opal.c:start_PSID_opal_session",
        "block/sed-opal.c:start_admin1LSP_opal_session",
        "block/sed-opal.c:start_anybodyASP_opal_session"
      ],
      "caller_func": [
        "block/sed-opal.c:start_PSID_opal_session",
        "block/sed-opal.c:start_admin1LSP_opal_session",
        "block/sed-opal.c:start_anybodyASP_opal_session"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584730032,
      "name": "start_generic_opal_session.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 444
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "start_generic_opal_session",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584758133,
      "name": "start_generic_opal_session",
      "external": false,
      "loc": "block/sed-opal.c:1398",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/sed-opal.c:start_PSID_opal_session",
        "block/sed-opal.c:start_admin1LSP_opal_session",
        "block/sed-opal.c:start_anybodyASP_opal_session"
      ],
      "caller_func": [
        "block/sed-opal.c:start_PSID_opal_session",
        "block/sed-opal.c:start_admin1LSP_opal_session",
        "block/sed-opal.c:start_anybodyASP_opal_session"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584757456,
      "name": "start_generic_opal_session.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 447
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "start_generic_opal_session",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585186693,
      "name": "start_generic_opal_session",
      "external": false,
      "loc": "block/sed-opal.c:1398",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/sed-opal.c:start_PSID_opal_session",
        "block/sed-opal.c:start_admin1LSP_opal_session",
        "block/sed-opal.c:start_anybodyASP_opal_session"
      ],
      "caller_func": [
        "block/sed-opal.c:start_PSID_opal_session",
        "block/sed-opal.c:start_admin1LSP_opal_session",
        "block/sed-opal.c:start_anybodyASP_opal_session"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585185936,
      "name": "start_generic_opal_session.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 520
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
int start_generic_opal_session(struct opal_dev * dev, enum opal_uid auth, enum opal_uid sp_type, const char * key, u8 key_len)
```

```json
{
  "name": "start_generic_opal_session",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585923184,
      "name": "start_generic_opal_session",
      "external": false,
      "loc": "block/sed-opal.c:1398",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:start_PSID_opal_session",
        "block/sed-opal.c:start_admin1LSP_opal_session",
        "block/sed-opal.c:start_anybodyASP_opal_session"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585923184,
      "name": "start_generic_opal_session",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 562
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
int start_generic_opal_session(struct opal_dev * dev, enum opal_uid auth, enum opal_uid sp_type, const char * key, u8 key_len)
```

```json
{
  "name": "start_generic_opal_session",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586714320,
      "name": "start_generic_opal_session",
      "external": false,
      "loc": "block/sed-opal.c:1438",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:start_PSID_opal_session",
        "block/sed-opal.c:start_admin1LSP_opal_session",
        "block/sed-opal.c:start_anybodyASP_opal_session"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586714320,
      "name": "start_generic_opal_session",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 562
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
int start_generic_opal_session(struct opal_dev * dev, enum opal_uid auth, enum opal_uid sp_type, const char * key, u8 key_len)
```

```json
{
  "name": "start_generic_opal_session",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586976208,
      "name": "start_generic_opal_session",
      "external": false,
      "loc": "block/sed-opal.c:1575",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:start_PSID_opal_session",
        "block/sed-opal.c:start_admin1LSP_opal_session",
        "block/sed-opal.c:start_anybodyASP_opal_session"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586976208,
      "name": "start_generic_opal_session",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 572
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
int start_generic_opal_session(struct opal_dev * dev, enum opal_uid auth, enum opal_uid sp_type, const char * key, u8 key_len)
```

```json
{
  "name": "start_generic_opal_session",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587255120,
      "name": "start_generic_opal_session",
      "external": false,
      "loc": "block/sed-opal.c:1692",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:start_PSID_opal_session",
        "block/sed-opal.c:start_admin1LSP_opal_session",
        "block/sed-opal.c:start_anybodyASP_opal_session"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587255120,
      "name": "start_generic_opal_session",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 572
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "start_generic_opal_session",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496081564,
      "name": "start_generic_opal_session",
      "external": false,
      "loc": "block/sed-opal.c:1327",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/sed-opal.c:start_PSID_opal_session",
        "block/sed-opal.c:start_admin1LSP_opal_session",
        "block/sed-opal.c:start_anybodyASP_opal_session"
      ],
      "caller_func": [
        "block/sed-opal.c:start_PSID_opal_session",
        "block/sed-opal.c:start_admin1LSP_opal_session",
        "block/sed-opal.c:start_anybodyASP_opal_session"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496080912,
      "name": "start_generic_opal_session.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 488
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "start_generic_opal_session",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229410340,
      "name": "start_generic_opal_session",
      "external": false,
      "loc": "block/sed-opal.c:1327",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/sed-opal.c:start_PSID_opal_session",
        "block/sed-opal.c:start_admin1LSP_opal_session",
        "block/sed-opal.c:start_anybodyASP_opal_session"
      ],
      "caller_func": [
        "block/sed-opal.c:start_PSID_opal_session",
        "block/sed-opal.c:start_admin1LSP_opal_session",
        "block/sed-opal.c:start_anybodyASP_opal_session"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229409708,
      "name": "start_generic_opal_session.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 492
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
int start_generic_opal_session(struct opal_dev * dev, enum opal_uid auth, enum opal_uid sp_type, const char * key, u8 key_len)
```

```json
{
  "name": "start_generic_opal_session",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290320128,
      "name": "start_generic_opal_session",
      "external": false,
      "loc": "block/sed-opal.c:1327",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:start_PSID_opal_session",
        "block/sed-opal.c:start_admin1LSP_opal_session",
        "block/sed-opal.c:start_anybodyASP_opal_session"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290320128,
      "name": "start_generic_opal_session",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 728
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
int start_generic_opal_session(struct opal_dev * dev, enum opal_uid auth, enum opal_uid sp_type, const char * key, u8 key_len)
```

```json
{
  "name": "start_generic_opal_session",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275151200,
      "name": "start_generic_opal_session",
      "external": false,
      "loc": "block/sed-opal.c:1327",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:start_PSID_opal_session",
        "block/sed-opal.c:start_admin1LSP_opal_session",
        "block/sed-opal.c:start_anybodyASP_opal_session"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275151200,
      "name": "start_generic_opal_session",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 552
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "start_generic_opal_session",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584179077,
      "name": "start_generic_opal_session",
      "external": false,
      "loc": "block/sed-opal.c:1327",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/sed-opal.c:start_PSID_opal_session",
        "block/sed-opal.c:start_admin1LSP_opal_session",
        "block/sed-opal.c:start_anybodyASP_opal_session"
      ],
      "caller_func": [
        "block/sed-opal.c:start_PSID_opal_session",
        "block/sed-opal.c:start_admin1LSP_opal_session",
        "block/sed-opal.c:start_anybodyASP_opal_session"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584178528,
      "name": "start_generic_opal_session.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 450
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "start_generic_opal_session",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584114325,
      "name": "start_generic_opal_session",
      "external": false,
      "loc": "block/sed-opal.c:1327",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/sed-opal.c:start_PSID_opal_session",
        "block/sed-opal.c:start_admin1LSP_opal_session",
        "block/sed-opal.c:start_anybodyASP_opal_session"
      ],
      "caller_func": [
        "block/sed-opal.c:start_PSID_opal_session",
        "block/sed-opal.c:start_admin1LSP_opal_session",
        "block/sed-opal.c:start_anybodyASP_opal_session"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584113776,
      "name": "start_generic_opal_session.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 450
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "start_generic_opal_session",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584162837,
      "name": "start_generic_opal_session",
      "external": false,
      "loc": "block/sed-opal.c:1327",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/sed-opal.c:start_PSID_opal_session",
        "block/sed-opal.c:start_admin1LSP_opal_session",
        "block/sed-opal.c:start_anybodyASP_opal_session"
      ],
      "caller_func": [
        "block/sed-opal.c:start_PSID_opal_session",
        "block/sed-opal.c:start_admin1LSP_opal_session",
        "block/sed-opal.c:start_anybodyASP_opal_session"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584162288,
      "name": "start_generic_opal_session.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 450
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "start_generic_opal_session",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584267221,
      "name": "start_generic_opal_session",
      "external": false,
      "loc": "block/sed-opal.c:1327",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/sed-opal.c:start_PSID_opal_session",
        "block/sed-opal.c:start_admin1LSP_opal_session",
        "block/sed-opal.c:start_anybodyASP_opal_session"
      ],
      "caller_func": [
        "block/sed-opal.c:start_PSID_opal_session",
        "block/sed-opal.c:start_admin1LSP_opal_session",
        "block/sed-opal.c:start_anybodyASP_opal_session"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584266672,
      "name": "start_generic_opal_session.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 450
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
int start_generic_opal_session(struct opal_dev * dev, enum opal_uid auth, enum opal_uid sp_type, const char * key, u8 key_len)
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
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
int start_generic_opal_session(struct opal_dev * dev, enum opal_uid auth, enum opal_uid sp_type, const char * key, u8 key_len)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
int start_generic_opal_session(struct opal_dev * dev, enum opal_uid auth, enum opal_uid sp_type, const char * key, u8 key_len)
```
</details>
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
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
int start_generic_opal_session(struct opal_dev * dev, enum opal_uid auth, enum opal_uid sp_type, const char * key, u8 key_len)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
int start_generic_opal_session(struct opal_dev * dev, enum opal_uid auth, enum opal_uid sp_type, const char * key, u8 key_len)
```
</details>
</li>
</ul>
