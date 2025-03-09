# Function: <code>audit_cb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision ❓</summary>

```c
void audit_cb(struct audit_buffer * ab, void * va)
```

```json
{
  "name": "audit_cb",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582477712,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/capability.c:47",
      "file": "security/apparmor/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582511072,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/policy.c:583",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582522256,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/policy_unpack.c:80",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582545040,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/resource.c:33",
      "file": "security/apparmor/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582574272,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/mount.c:89",
      "file": "security/apparmor/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582477712,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071582511072,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071582522256,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 18446744071582545040,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071582574272,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1008
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Collision ❓</summary>

```c
void audit_cb(struct audit_buffer * ab, void * va)
```

```json
{
  "name": "audit_cb",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582709760,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/capability.c:47",
      "file": "security/apparmor/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582746448,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/policy.c:608",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582758736,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/policy_unpack.c:81",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582785328,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/resource.c:33",
      "file": "security/apparmor/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582815824,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/mount.c:89",
      "file": "security/apparmor/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582709760,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071582746448,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071582758736,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 18446744071582785328,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071582815824,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1008
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Collision ❓</summary>

```c
void audit_cb(struct audit_buffer * ab, void * va)
```

```json
{
  "name": "audit_cb",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582804352,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/capability.c:47",
      "file": "security/apparmor/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582841584,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/policy.c:609",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582854240,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/policy_unpack.c:81",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582880720,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/resource.c:33",
      "file": "security/apparmor/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582911680,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/mount.c:89",
      "file": "security/apparmor/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582804352,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071582841584,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071582854240,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 18446744071582880720,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071582911680,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1008
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void audit_cb(struct audit_buffer * ab, void * va)
```

```json
{
  "name": "audit_cb",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582894080,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/capability.c:48",
      "file": "security/apparmor/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582922256,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/policy.c:593",
      "file": "security/apparmor/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582930912,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/policy_unpack.c:80",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582950960,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/resource.c:34",
      "file": "security/apparmor/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582972320,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/mount.c:89",
      "file": "security/apparmor/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582894080,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071582922256,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446744071582930912,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 18446744071582950960,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
    },
    {
      "addr": 18446744071582972320,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1050
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void audit_cb(struct audit_buffer * ab, void * va)
```

```json
{
  "name": "audit_cb",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583052400,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/capability.c:48",
      "file": "security/apparmor/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583081568,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/policy.c:594",
      "file": "security/apparmor/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583091152,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/policy_unpack.c:80",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583113008,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/resource.c:34",
      "file": "security/apparmor/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583135984,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/mount.c:89",
      "file": "security/apparmor/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583052400,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071583081568,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446744071583091152,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 18446744071583113008,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
    },
    {
      "addr": 18446744071583135984,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1050
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void audit_cb(struct audit_buffer * ab, void * va)
```

```json
{
  "name": "audit_cb",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583253472,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/capability.c:48",
      "file": "security/apparmor/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583284304,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/policy.c:599",
      "file": "security/apparmor/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583294288,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/policy_unpack.c:81",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583318256,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/resource.c:34",
      "file": "security/apparmor/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583341936,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/mount.c:89",
      "file": "security/apparmor/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583253472,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071583284304,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071583294288,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    },
    {
      "addr": 18446744071583318256,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
    },
    {
      "addr": 18446744071583341936,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1067
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void audit_cb(struct audit_buffer * ab, void * va)
```

```json
{
  "name": "audit_cb",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583371056,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/capability.c:48",
      "file": "security/apparmor/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583402688,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/policy.c:599",
      "file": "security/apparmor/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583412752,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/policy_unpack.c:81",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583437216,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/resource.c:34",
      "file": "security/apparmor/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583460560,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/mount.c:90",
      "file": "security/apparmor/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583371056,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071583402688,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071583412752,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    },
    {
      "addr": 18446744071583437216,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
    },
    {
      "addr": 18446744071583460560,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1067
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void audit_cb(struct audit_buffer * ab, void * va)
```

```json
{
  "name": "audit_cb",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583558128,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/capability.c:44",
      "file": "security/apparmor/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583588928,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/policy.c:594",
      "file": "security/apparmor/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583598544,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/policy_unpack.c:77",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583622288,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/resource.c:30",
      "file": "security/apparmor/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583645088,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/mount.c:86",
      "file": "security/apparmor/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583558128,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    },
    {
      "addr": 18446744071583588928,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071583598544,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    },
    {
      "addr": 18446744071583622288,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
    },
    {
      "addr": 18446744071583645088,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 995
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void audit_cb(struct audit_buffer * ab, void * va)
```

```json
{
  "name": "audit_cb",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583663856,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/capability.c:44",
      "file": "security/apparmor/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583695088,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/policy.c:594",
      "file": "security/apparmor/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583704704,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/policy_unpack.c:77",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583728464,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/resource.c:30",
      "file": "security/apparmor/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583751376,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/mount.c:86",
      "file": "security/apparmor/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583663856,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    },
    {
      "addr": 18446744071583695088,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071583704704,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    },
    {
      "addr": 18446744071583728464,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
    },
    {
      "addr": 18446744071583751376,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 995
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void audit_cb(struct audit_buffer * ab, void * va)
```

```json
{
  "name": "audit_cb",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584025232,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/capability.c:44",
      "file": "security/apparmor/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584062160,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/policy.c:598",
      "file": "security/apparmor/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584074448,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/policy_unpack.c:78",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584110288,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/resource.c:30",
      "file": "security/apparmor/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584141280,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/mount.c:86",
      "file": "security/apparmor/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584025232,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    },
    {
      "addr": 18446744071584062160,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071584074448,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    },
    {
      "addr": 18446744071584110288,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
    },
    {
      "addr": 18446744071584141280,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void audit_cb(struct audit_buffer * ab, void * va)
```

```json
{
  "name": "audit_cb",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584144656,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/capability.c:44",
      "file": "security/apparmor/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584181248,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/policy.c:598",
      "file": "security/apparmor/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584193824,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/policy_unpack.c:78",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584229376,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/resource.c:30",
      "file": "security/apparmor/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584259696,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/mount.c:86",
      "file": "security/apparmor/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584144656,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    },
    {
      "addr": 18446744071584181248,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071584193824,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    },
    {
      "addr": 18446744071584229376,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
    },
    {
      "addr": 18446744071584259696,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void audit_cb(struct audit_buffer * ab, void * va)
```

```json
{
  "name": "audit_cb",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584171808,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/capability.c:44",
      "file": "security/apparmor/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584208240,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/policy.c:598",
      "file": "security/apparmor/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584220720,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/policy_unpack.c:78",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584254432,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/resource.c:30",
      "file": "security/apparmor/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584285280,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/mount.c:86",
      "file": "security/apparmor/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584171808,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    },
    {
      "addr": 18446744071584208240,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071584220720,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    },
    {
      "addr": 18446744071584254432,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
    },
    {
      "addr": 18446744071584285280,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void audit_cb(struct audit_buffer * ab, void * va)
```

```json
{
  "name": "audit_cb",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584556512,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/capability.c:44",
      "file": "security/apparmor/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584593504,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/policy.c:598",
      "file": "security/apparmor/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584606160,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/policy_unpack.c:78",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584640128,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/resource.c:30",
      "file": "security/apparmor/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584671360,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/mount.c:86",
      "file": "security/apparmor/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584556512,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    },
    {
      "addr": 18446744071584593504,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071584606160,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    },
    {
      "addr": 18446744071584640128,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
    },
    {
      "addr": 18446744071584671360,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void audit_cb(struct audit_buffer * ab, void * va)
```

```json
{
  "name": "audit_cb",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585199520,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/capability.c:44",
      "file": "security/apparmor/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585241632,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/policy.c:643",
      "file": "security/apparmor/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585255520,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/policy_unpack.c:76",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585296480,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/resource.c:30",
      "file": "security/apparmor/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585330992,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/mount.c:86",
      "file": "security/apparmor/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585199520,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    },
    {
      "addr": 18446744071585241632,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071585255520,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
    },
    {
      "addr": 18446744071585296480,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
    },
    {
      "addr": 18446744071585330992,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 257
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void audit_cb(struct audit_buffer * ab, void * va)
```

```json
{
  "name": "audit_cb",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585931152,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/capability.c:44",
      "file": "security/apparmor/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585974592,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/policy.c:717",
      "file": "security/apparmor/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585989504,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/policy_unpack.c:34",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586033760,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/resource.c:30",
      "file": "security/apparmor/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586071408,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/mount.c:86",
      "file": "security/apparmor/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585931152,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    },
    {
      "addr": 18446744071585974592,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071585989504,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    },
    {
      "addr": 18446744071586033760,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
    },
    {
      "addr": 18446744071586071408,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void audit_cb(struct audit_buffer * ab, void * va)
```

```json
{
  "name": "audit_cb",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586163648,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/capability.c:44",
      "file": "security/apparmor/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586206688,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/policy.c:752",
      "file": "security/apparmor/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586222032,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/policy_unpack.c:34",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586269008,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/resource.c:30",
      "file": "security/apparmor/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586306496,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/mount.c:86",
      "file": "security/apparmor/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586163648,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    },
    {
      "addr": 18446744071586206688,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071586222032,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    },
    {
      "addr": 18446744071586269008,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
    },
    {
      "addr": 18446744071586306496,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void audit_cb(struct audit_buffer * ab, void * va)
```

```json
{
  "name": "audit_cb",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586412496,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/capability.c:45",
      "file": "security/apparmor/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586458848,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/policy.c:782",
      "file": "security/apparmor/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586474592,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/policy_unpack.c:35",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586525536,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/resource.c:30",
      "file": "security/apparmor/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586563088,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/mount.c:86",
      "file": "security/apparmor/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586412496,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    },
    {
      "addr": 18446744071586458848,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071586474592,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    },
    {
      "addr": 18446744071586525536,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
    },
    {
      "addr": 18446744071586563088,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Collision, Selective Inline ❓</summary>

```c
void audit_cb(struct audit_buffer * ab, void * va)
```

```json
{
  "name": "audit_cb",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495457008,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/capability.c:44",
      "file": "security/apparmor/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336495488576,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/policy.c:594",
      "file": "security/apparmor/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336495497944,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/policy_unpack.c:77",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336495524408,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/resource.c:30",
      "file": "security/apparmor/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336495551472,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/mount.c:86",
      "file": "security/apparmor/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495457008,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    },
    {
      "addr": 18446603336495488576,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 18446603336495497944,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446603336495524408,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
    },
    {
      "addr": 18446603336495551472,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 940
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Collision, Selective Inline ❓</summary>

```c
void audit_cb(struct audit_buffer * ab, void * va)
```

```json
{
  "name": "audit_cb",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228823920,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/capability.c:44",
      "file": "security/apparmor/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3228856148,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/policy.c:594",
      "file": "security/apparmor/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3228865444,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/policy_unpack.c:77",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3228891104,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/resource.c:30",
      "file": "security/apparmor/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3228914876,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/mount.c:86",
      "file": "security/apparmor/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3228823920,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 3228856148,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 3228865444,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
    },
    {
      "addr": 3228891104,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
    },
    {
      "addr": 3228914876,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 992
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Collision, Selective Inline ❓</summary>

```c
void audit_cb(struct audit_buffer * ab, void * va)
```

```json
{
  "name": "audit_cb",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055289507280,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/capability.c:44",
      "file": "security/apparmor/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055289550272,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/policy.c:594",
      "file": "security/apparmor/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055289564864,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/policy_unpack.c:77",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055289603344,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/resource.c:30",
      "file": "security/apparmor/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055289639376,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/mount.c:86",
      "file": "security/apparmor/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289507280,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    },
    {
      "addr": 13835058055289550272,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
    },
    {
      "addr": 13835058055289564864,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
    },
    {
      "addr": 13835058055289603344,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
    },
    {
      "addr": 13835058055289639376,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1256
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Collision, Selective Inline ❓</summary>

```c
void audit_cb(struct audit_buffer * ab, void * va)
```

```json
{
  "name": "audit_cb",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274645768,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/capability.c:44",
      "file": "security/apparmor/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936274673020,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/policy.c:594",
      "file": "security/apparmor/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936274681152,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/policy_unpack.c:77",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936274702072,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/resource.c:30",
      "file": "security/apparmor/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936274722742,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/mount.c:86",
      "file": "security/apparmor/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274645768,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    },
    {
      "addr": 18446743936274673020,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446743936274681152,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
    },
    {
      "addr": 18446743936274702072,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    },
    {
      "addr": 18446743936274722742,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1032
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void audit_cb(struct audit_buffer * ab, void * va)
```

```json
{
  "name": "audit_cb",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583632592,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/capability.c:44",
      "file": "security/apparmor/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583663824,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/policy.c:594",
      "file": "security/apparmor/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583673440,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/policy_unpack.c:77",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583697200,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/resource.c:30",
      "file": "security/apparmor/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583720112,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/mount.c:86",
      "file": "security/apparmor/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583632592,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    },
    {
      "addr": 18446744071583663824,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071583673440,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    },
    {
      "addr": 18446744071583697200,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
    },
    {
      "addr": 18446744071583720112,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 995
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void audit_cb(struct audit_buffer * ab, void * va)
```

```json
{
  "name": "audit_cb",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583569648,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/capability.c:44",
      "file": "security/apparmor/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583600880,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/policy.c:594",
      "file": "security/apparmor/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583610496,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/policy_unpack.c:77",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583634256,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/resource.c:30",
      "file": "security/apparmor/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583657168,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/mount.c:86",
      "file": "security/apparmor/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583569648,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    },
    {
      "addr": 18446744071583600880,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071583610496,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    },
    {
      "addr": 18446744071583634256,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
    },
    {
      "addr": 18446744071583657168,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 995
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void audit_cb(struct audit_buffer * ab, void * va)
```

```json
{
  "name": "audit_cb",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583616368,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/capability.c:44",
      "file": "security/apparmor/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583647600,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/policy.c:594",
      "file": "security/apparmor/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583657216,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/policy_unpack.c:77",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583680976,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/resource.c:30",
      "file": "security/apparmor/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583703888,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/mount.c:86",
      "file": "security/apparmor/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583616368,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    },
    {
      "addr": 18446744071583647600,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071583657216,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    },
    {
      "addr": 18446744071583680976,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
    },
    {
      "addr": 18446744071583703888,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 995
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void audit_cb(struct audit_buffer * ab, void * va)
```

```json
{
  "name": "audit_cb",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583714224,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/capability.c:44",
      "file": "security/apparmor/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583745936,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/policy.c:594",
      "file": "security/apparmor/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583755728,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/policy_unpack.c:77",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583780704,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/resource.c:30",
      "file": "security/apparmor/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583804176,
      "name": "audit_cb",
      "external": false,
      "loc": "security/apparmor/mount.c:86",
      "file": "security/apparmor/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583714224,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    },
    {
      "addr": 18446744071583745936,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071583755728,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    },
    {
      "addr": 18446744071583780704,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
    },
    {
      "addr": 18446744071583804176,
      "name": "audit_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 995
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
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
