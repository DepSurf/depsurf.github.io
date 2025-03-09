# Function: <code>ima_log_string_op</code>

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
void ima_log_string_op(struct audit_buffer * ab, char * key, char * value, bool (*)(kuid_t, kuid_t) rule_operator)
```

```json
{
  "name": "ima_log_string_op",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583011296,
      "name": "ima_log_string_op",
      "external": false,
      "loc": "security/integrity/ima/ima_policy.c:591",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583011296,
      "name": "ima_log_string_op",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
void ima_log_string_op(struct audit_buffer * ab, char * key, char * value, bool (*)(kuid_t, kuid_t) rule_operator)
```

```json
{
  "name": "ima_log_string_op",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583176304,
      "name": "ima_log_string_op",
      "external": false,
      "loc": "security/integrity/ima/ima_policy.c:591",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583176304,
      "name": "ima_log_string_op",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
void ima_log_string_op(struct audit_buffer * ab, char * key, char * value, bool (*)(kuid_t, kuid_t) rule_operator)
```

```json
{
  "name": "ima_log_string_op",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583382432,
      "name": "ima_log_string_op",
      "external": false,
      "loc": "security/integrity/ima/ima_policy.c:615",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583382432,
      "name": "ima_log_string_op",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
void ima_log_string_op(struct audit_buffer * ab, char * key, char * value, bool (*)(kuid_t, kuid_t) rule_operator)
```

```json
{
  "name": "ima_log_string_op",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583501680,
      "name": "ima_log_string_op",
      "external": false,
      "loc": "security/integrity/ima/ima_policy.c:742",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583501680,
      "name": "ima_log_string_op",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
void ima_log_string_op(struct audit_buffer * ab, char * key, char * value, bool (*)(kuid_t, kuid_t) rule_operator)
```

```json
{
  "name": "ima_log_string_op",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583688624,
      "name": "ima_log_string_op",
      "external": false,
      "loc": "security/integrity/ima/ima_policy.c:827",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583688624,
      "name": "ima_log_string_op",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
void ima_log_string_op(struct audit_buffer * ab, char * key, char * value, bool (*)(kuid_t, kuid_t) rule_operator)
```

```json
{
  "name": "ima_log_string_op",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583796320,
      "name": "ima_log_string_op",
      "external": false,
      "loc": "security/integrity/ima/ima_policy.c:841",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583796320,
      "name": "ima_log_string_op",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ima_log_string_op(struct audit_buffer * ab, char * key, char * value, bool (*)(kuid_t, kuid_t) rule_operator)
```

```json
{
  "name": "ima_log_string_op",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584190495,
      "name": "ima_log_string_op",
      "external": false,
      "loc": "security/integrity/ima/ima_policy.c:955",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule"
      ],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584188976,
      "name": "ima_log_string_op",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ima_log_string_op(struct audit_buffer * ab, char * key, char * value, bool (*)(kuid_t, kuid_t) rule_operator)
```

```json
{
  "name": "ima_log_string_op",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584309439,
      "name": "ima_log_string_op",
      "external": false,
      "loc": "security/integrity/ima/ima_policy.c:1000",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule"
      ],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584307472,
      "name": "ima_log_string_op",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ima_log_string_op(struct audit_buffer * ab, char * key, char * value, bool (*)(kuid_t, kuid_t) rule_operator)
```

```json
{
  "name": "ima_log_string_op",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584344032,
      "name": "ima_log_string_op",
      "external": false,
      "loc": "security/integrity/ima/ima_policy.c:1041",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule"
      ],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584341888,
      "name": "ima_log_string_op",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ima_log_string_op(struct audit_buffer * ab, char * key, char * value, bool (*)(kuid_t, kuid_t) rule_operator)
```

```json
{
  "name": "ima_log_string_op",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584734160,
      "name": "ima_log_string_op",
      "external": false,
      "loc": "security/integrity/ima/ima_policy.c:1097",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule"
      ],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584730816,
      "name": "ima_log_string_op",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
void ima_log_string_op(struct audit_buffer * ab, char * key, char * value, enum policy_opt rule_operator)
```

```json
{
  "name": "ima_log_string_op",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585411349,
      "name": "ima_log_string_op",
      "external": false,
      "loc": "security/integrity/ima/ima_policy.c:1146",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule"
      ],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585407264,
      "name": "ima_log_string_op",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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
void ima_log_string_op(struct audit_buffer * ab, char * key, char * value, enum policy_opt rule_operator)
```

```json
{
  "name": "ima_log_string_op",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586165717,
      "name": "ima_log_string_op",
      "external": false,
      "loc": "security/integrity/ima/ima_policy.c:1193",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule"
      ],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586162400,
      "name": "ima_log_string_op",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ima_log_string_op(struct audit_buffer * ab, char * key, char * value, enum policy_opt rule_operator)
```

```json
{
  "name": "ima_log_string_op",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586403555,
      "name": "ima_log_string_op",
      "external": false,
      "loc": "security/integrity/ima/ima_policy.c:1195",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule"
      ],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586400224,
      "name": "ima_log_string_op",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ima_log_string_op(struct audit_buffer * ab, char * key, char * value, enum policy_opt rule_operator)
```

```json
{
  "name": "ima_log_string_op",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586668483,
      "name": "ima_log_string_op",
      "external": false,
      "loc": "security/integrity/ima/ima_policy.c:1188",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule"
      ],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586665200,
      "name": "ima_log_string_op",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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
void ima_log_string_op(struct audit_buffer * ab, char * key, char * value, bool (*)(kuid_t, kuid_t) rule_operator)
```

```json
{
  "name": "ima_log_string_op",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495599512,
      "name": "ima_log_string_op",
      "external": false,
      "loc": "security/integrity/ima/ima_policy.c:841",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495599512,
      "name": "ima_log_string_op",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
void ima_log_string_op(struct audit_buffer * ab, char * key, char * value, bool (*)(kuid_t, kuid_t) rule_operator)
```

```json
{
  "name": "ima_log_string_op",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228960288,
      "name": "ima_log_string_op",
      "external": false,
      "loc": "security/integrity/ima/ima_policy.c:841",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228960288,
      "name": "ima_log_string_op",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
void ima_log_string_op(struct audit_buffer * ab, char * key, char * value, bool (*)(kuid_t, kuid_t) rule_operator)
```

```json
{
  "name": "ima_log_string_op",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289704080,
      "name": "ima_log_string_op",
      "external": false,
      "loc": "security/integrity/ima/ima_policy.c:841",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289704080,
      "name": "ima_log_string_op",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
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
void ima_log_string_op(struct audit_buffer * ab, char * key, char * value, bool (*)(kuid_t, kuid_t) rule_operator)
```

```json
{
  "name": "ima_log_string_op",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274762278,
      "name": "ima_log_string_op",
      "external": false,
      "loc": "security/integrity/ima/ima_policy.c:841",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274762278,
      "name": "ima_log_string_op",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
void ima_log_string_op(struct audit_buffer * ab, char * key, char * value, bool (*)(kuid_t, kuid_t) rule_operator)
```

```json
{
  "name": "ima_log_string_op",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583765056,
      "name": "ima_log_string_op",
      "external": false,
      "loc": "security/integrity/ima/ima_policy.c:841",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583765056,
      "name": "ima_log_string_op",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
void ima_log_string_op(struct audit_buffer * ab, char * key, char * value, bool (*)(kuid_t, kuid_t) rule_operator)
```

```json
{
  "name": "ima_log_string_op",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583702112,
      "name": "ima_log_string_op",
      "external": false,
      "loc": "security/integrity/ima/ima_policy.c:841",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583702112,
      "name": "ima_log_string_op",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
void ima_log_string_op(struct audit_buffer * ab, char * key, char * value, bool (*)(kuid_t, kuid_t) rule_operator)
```

```json
{
  "name": "ima_log_string_op",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583748816,
      "name": "ima_log_string_op",
      "external": false,
      "loc": "security/integrity/ima/ima_policy.c:841",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583748816,
      "name": "ima_log_string_op",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
void ima_log_string_op(struct audit_buffer * ab, char * key, char * value, bool (*)(kuid_t, kuid_t) rule_operator)
```

```json
{
  "name": "ima_log_string_op",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583849760,
      "name": "ima_log_string_op",
      "external": false,
      "loc": "security/integrity/ima/ima_policy.c:841",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583849760,
      "name": "ima_log_string_op",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
void ima_log_string_op(struct audit_buffer * ab, char * key, char * value, bool (*)(kuid_t, kuid_t) rule_operator)
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>bool (*)(kuid_t, kuid_t) rule_operator</code> ➡️ <code>enum policy_opt rule_operator</code>
</li>
</ul>
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
