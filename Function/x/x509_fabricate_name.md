# Function: <code>x509_fabricate_name</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int x509_fabricate_name(struct x509_parse_context * ctx, size_t hdrlen, unsigned char tag, char * * _name, size_t vlen)
```

```json
{
  "name": "x509_fabricate_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582698048,
      "name": "x509_fabricate_name",
      "external": false,
      "loc": "crypto/asymmetric_keys/x509_cert_parser.c:292",
      "file": "crypto/asymmetric_keys/x509_cert_parser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_note_issuer",
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_note_subject"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582698048,
      "name": "x509_fabricate_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 803
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "x509_fabricate_name",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582977040,
      "name": "x509_fabricate_name",
      "external": false,
      "loc": "crypto/asymmetric_keys/x509_cert_parser.c:302",
      "file": "crypto/asymmetric_keys/x509_cert_parser.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_note_subject",
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_note_issuer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582977040,
      "name": "x509_fabricate_name.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 786
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "x509_fabricate_name",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583081616,
      "name": "x509_fabricate_name",
      "external": false,
      "loc": "crypto/asymmetric_keys/x509_cert_parser.c:301",
      "file": "crypto/asymmetric_keys/x509_cert_parser.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_note_subject",
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_note_issuer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583081616,
      "name": "x509_fabricate_name.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 786
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "x509_fabricate_name",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583137776,
      "name": "x509_fabricate_name",
      "external": false,
      "loc": "crypto/asymmetric_keys/x509_cert_parser.c:302",
      "file": "crypto/asymmetric_keys/x509_cert_parser.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_note_subject",
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_note_issuer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583137776,
      "name": "x509_fabricate_name.constprop.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 778
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "x509_fabricate_name",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583312608,
      "name": "x509_fabricate_name",
      "external": false,
      "loc": "crypto/asymmetric_keys/x509_cert_parser.c:302",
      "file": "crypto/asymmetric_keys/x509_cert_parser.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_note_subject",
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_note_issuer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583312608,
      "name": "x509_fabricate_name.constprop.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 778
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "x509_fabricate_name",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583521232,
      "name": "x509_fabricate_name",
      "external": false,
      "loc": "crypto/asymmetric_keys/x509_cert_parser.c:311",
      "file": "crypto/asymmetric_keys/x509_cert_parser.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_note_subject",
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_note_issuer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583521232,
      "name": "x509_fabricate_name.constprop.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 785
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "x509_fabricate_name",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583645008,
      "name": "x509_fabricate_name",
      "external": false,
      "loc": "crypto/asymmetric_keys/x509_cert_parser.c:308",
      "file": "crypto/asymmetric_keys/x509_cert_parser.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_note_subject",
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_note_issuer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583645008,
      "name": "x509_fabricate_name.constprop.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 785
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
  "name": "x509_fabricate_name",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583831632,
      "name": "x509_fabricate_name",
      "external": false,
      "loc": "crypto/asymmetric_keys/x509_cert_parser.c:328",
      "file": "crypto/asymmetric_keys/x509_cert_parser.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_note_subject",
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_note_issuer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583831632,
      "name": "x509_fabricate_name.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 770
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
  "name": "x509_fabricate_name",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583933568,
      "name": "x509_fabricate_name",
      "external": false,
      "loc": "crypto/asymmetric_keys/x509_cert_parser.c:328",
      "file": "crypto/asymmetric_keys/x509_cert_parser.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_note_subject",
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_note_issuer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583933568,
      "name": "x509_fabricate_name.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 770
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
  "name": "x509_fabricate_name",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584324432,
      "name": "x509_fabricate_name",
      "external": false,
      "loc": "crypto/asymmetric_keys/x509_cert_parser.c:328",
      "file": "crypto/asymmetric_keys/x509_cert_parser.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_note_subject",
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_note_issuer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584324432,
      "name": "x509_fabricate_name.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 777
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
  "name": "x509_fabricate_name",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584442688,
      "name": "x509_fabricate_name",
      "external": false,
      "loc": "crypto/asymmetric_keys/x509_cert_parser.c:338",
      "file": "crypto/asymmetric_keys/x509_cert_parser.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_note_subject",
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_note_issuer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584442688,
      "name": "x509_fabricate_name.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 777
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
  "name": "x509_fabricate_name",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584477376,
      "name": "x509_fabricate_name",
      "external": false,
      "loc": "crypto/asymmetric_keys/x509_cert_parser.c:364",
      "file": "crypto/asymmetric_keys/x509_cert_parser.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_note_subject",
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_note_issuer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584477376,
      "name": "x509_fabricate_name.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 777
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
  "name": "x509_fabricate_name",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584875600,
      "name": "x509_fabricate_name",
      "external": false,
      "loc": "crypto/asymmetric_keys/x509_cert_parser.c:364",
      "file": "crypto/asymmetric_keys/x509_cert_parser.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_note_subject",
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_note_issuer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584875600,
      "name": "x509_fabricate_name.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 777
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "x509_fabricate_name",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585572496,
      "name": "x509_fabricate_name",
      "external": false,
      "loc": "crypto/asymmetric_keys/x509_cert_parser.c:366",
      "file": "crypto/asymmetric_keys/x509_cert_parser.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_note_subject",
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_note_issuer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585572496,
      "name": "x509_fabricate_name.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 805
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "x509_fabricate_name",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586337024,
      "name": "x509_fabricate_name",
      "external": false,
      "loc": "crypto/asymmetric_keys/x509_cert_parser.c:366",
      "file": "crypto/asymmetric_keys/x509_cert_parser.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_note_subject",
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_note_issuer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586337024,
      "name": "x509_fabricate_name.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 805
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "x509_fabricate_name",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586583472,
      "name": "x509_fabricate_name",
      "external": false,
      "loc": "crypto/asymmetric_keys/x509_cert_parser.c:366",
      "file": "crypto/asymmetric_keys/x509_cert_parser.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_note_subject",
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_note_issuer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586583472,
      "name": "x509_fabricate_name.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 840
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "x509_fabricate_name",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586852112,
      "name": "x509_fabricate_name",
      "external": false,
      "loc": "crypto/asymmetric_keys/x509_cert_parser.c:376",
      "file": "crypto/asymmetric_keys/x509_cert_parser.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_note_subject",
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_note_issuer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586852112,
      "name": "x509_fabricate_name.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 890
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
  "name": "x509_fabricate_name",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495751904,
      "name": "x509_fabricate_name",
      "external": false,
      "loc": "crypto/asymmetric_keys/x509_cert_parser.c:328",
      "file": "crypto/asymmetric_keys/x509_cert_parser.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_note_subject",
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_note_issuer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495751904,
      "name": "x509_fabricate_name.isra.0",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "x509_fabricate_name",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229105472,
      "name": "x509_fabricate_name",
      "external": false,
      "loc": "crypto/asymmetric_keys/x509_cert_parser.c:328",
      "file": "crypto/asymmetric_keys/x509_cert_parser.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_note_subject",
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_note_issuer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229105472,
      "name": "x509_fabricate_name.constprop.0",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "x509_fabricate_name",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055289916736,
      "name": "x509_fabricate_name",
      "external": false,
      "loc": "crypto/asymmetric_keys/x509_cert_parser.c:328",
      "file": "crypto/asymmetric_keys/x509_cert_parser.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_note_subject",
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_note_issuer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289916736,
      "name": "x509_fabricate_name.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 732
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "x509_fabricate_name",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274900568,
      "name": "x509_fabricate_name",
      "external": false,
      "loc": "crypto/asymmetric_keys/x509_cert_parser.c:328",
      "file": "crypto/asymmetric_keys/x509_cert_parser.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_note_subject",
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_note_issuer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274900568,
      "name": "x509_fabricate_name.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 400
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
  "name": "x509_fabricate_name",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583902304,
      "name": "x509_fabricate_name",
      "external": false,
      "loc": "crypto/asymmetric_keys/x509_cert_parser.c:328",
      "file": "crypto/asymmetric_keys/x509_cert_parser.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_note_subject",
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_note_issuer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583902304,
      "name": "x509_fabricate_name.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 770
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
  "name": "x509_fabricate_name",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583839360,
      "name": "x509_fabricate_name",
      "external": false,
      "loc": "crypto/asymmetric_keys/x509_cert_parser.c:328",
      "file": "crypto/asymmetric_keys/x509_cert_parser.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_note_subject",
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_note_issuer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583839360,
      "name": "x509_fabricate_name.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 770
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
  "name": "x509_fabricate_name",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583886064,
      "name": "x509_fabricate_name",
      "external": false,
      "loc": "crypto/asymmetric_keys/x509_cert_parser.c:328",
      "file": "crypto/asymmetric_keys/x509_cert_parser.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_note_subject",
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_note_issuer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583886064,
      "name": "x509_fabricate_name.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 770
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
  "name": "x509_fabricate_name",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583987136,
      "name": "x509_fabricate_name",
      "external": false,
      "loc": "crypto/asymmetric_keys/x509_cert_parser.c:328",
      "file": "crypto/asymmetric_keys/x509_cert_parser.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_note_subject",
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_note_issuer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583987136,
      "name": "x509_fabricate_name.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 770
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
<summary>Removed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➖</summary>

```c
int x509_fabricate_name(struct x509_parse_context * ctx, size_t hdrlen, unsigned char tag, char * * _name, size_t vlen)
```
</details>
</li>
</ul>
