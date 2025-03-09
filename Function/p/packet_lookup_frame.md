# Function: <code>packet_lookup_frame</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "packet_lookup_frame",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587250544,
      "name": "packet_lookup_frame",
      "external": false,
      "loc": "net/packet/af_packet.c:491",
      "file": "net/packet/af_packet.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:__tpacket_has_room",
        "net/packet/af_packet.c:packet_poll",
        "net/packet/af_packet.c:packet_poll",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:tpacket_snd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587250544,
      "name": "packet_lookup_frame.isra.53",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
  "name": "packet_lookup_frame",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587713424,
      "name": "packet_lookup_frame",
      "external": false,
      "loc": "net/packet/af_packet.c:492",
      "file": "net/packet/af_packet.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_poll",
        "net/packet/af_packet.c:packet_poll",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:__tpacket_has_room"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587713424,
      "name": "packet_lookup_frame.isra.54",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
  "name": "packet_lookup_frame",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587927648,
      "name": "packet_lookup_frame",
      "external": false,
      "loc": "net/packet/af_packet.c:491",
      "file": "net/packet/af_packet.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_poll",
        "net/packet/af_packet.c:packet_poll",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:__tpacket_has_room"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587927648,
      "name": "packet_lookup_frame.isra.58",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
  "name": "packet_lookup_frame",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588086640,
      "name": "packet_lookup_frame",
      "external": false,
      "loc": "net/packet/af_packet.c:499",
      "file": "net/packet/af_packet.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_poll",
        "net/packet/af_packet.c:packet_poll",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:__tpacket_has_room"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588086640,
      "name": "packet_lookup_frame.isra.54",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
  "name": "packet_lookup_frame",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588631184,
      "name": "packet_lookup_frame",
      "external": false,
      "loc": "net/packet/af_packet.c:494",
      "file": "net/packet/af_packet.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_poll",
        "net/packet/af_packet.c:packet_poll",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:__tpacket_has_room"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588631184,
      "name": "packet_lookup_frame.isra.55",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
void * packet_lookup_frame(struct packet_sock * po, struct packet_ring_buffer * rb, unsigned int position, int status)
```

```json
{
  "name": "packet_lookup_frame",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588994832,
      "name": "packet_lookup_frame",
      "external": false,
      "loc": "net/packet/af_packet.c:470",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_poll",
        "net/packet/af_packet.c:packet_poll",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588994832,
      "name": "packet_lookup_frame",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
void * packet_lookup_frame(struct packet_sock * po, struct packet_ring_buffer * rb, unsigned int position, int status)
```

```json
{
  "name": "packet_lookup_frame",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589218464,
      "name": "packet_lookup_frame",
      "external": false,
      "loc": "net/packet/af_packet.c:471",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_poll",
        "net/packet/af_packet.c:packet_poll",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589218464,
      "name": "packet_lookup_frame",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
void * packet_lookup_frame(const struct packet_sock * po, const struct packet_ring_buffer * rb, unsigned int position, int status)
```

```json
{
  "name": "packet_lookup_frame",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589673376,
      "name": "packet_lookup_frame",
      "external": false,
      "loc": "net/packet/af_packet.c:463",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_poll",
        "net/packet/af_packet.c:packet_poll",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589673376,
      "name": "packet_lookup_frame",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
void * packet_lookup_frame(const struct packet_sock * po, const struct packet_ring_buffer * rb, unsigned int position, int status)
```

```json
{
  "name": "packet_lookup_frame",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589897616,
      "name": "packet_lookup_frame",
      "external": false,
      "loc": "net/packet/af_packet.c:463",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_poll",
        "net/packet/af_packet.c:packet_poll",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589897616,
      "name": "packet_lookup_frame",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
  "name": "packet_lookup_frame",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590927888,
      "name": "packet_lookup_frame",
      "external": false,
      "loc": "net/packet/af_packet.c:470",
      "file": "net/packet/af_packet.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_poll",
        "net/packet/af_packet.c:packet_poll",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590927888,
      "name": "packet_lookup_frame.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
  "name": "packet_lookup_frame",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590991648,
      "name": "packet_lookup_frame",
      "external": false,
      "loc": "net/packet/af_packet.c:474",
      "file": "net/packet/af_packet.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_poll",
        "net/packet/af_packet.c:packet_poll",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590991648,
      "name": "packet_lookup_frame.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
  "name": "packet_lookup_frame",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590922240,
      "name": "packet_lookup_frame",
      "external": false,
      "loc": "net/packet/af_packet.c:475",
      "file": "net/packet/af_packet.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_poll",
        "net/packet/af_packet.c:packet_poll",
        "net/packet/af_packet.c:tpacket_snd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590922240,
      "name": "packet_lookup_frame.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
  "name": "packet_lookup_frame",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591759008,
      "name": "packet_lookup_frame",
      "external": false,
      "loc": "net/packet/af_packet.c:476",
      "file": "net/packet/af_packet.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_poll",
        "net/packet/af_packet.c:packet_poll",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591759008,
      "name": "packet_lookup_frame.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
  "name": "packet_lookup_frame",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593467856,
      "name": "packet_lookup_frame",
      "external": false,
      "loc": "net/packet/af_packet.c:512",
      "file": "net/packet/af_packet.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_poll",
        "net/packet/af_packet.c:packet_poll",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:__packet_rcv_has_room",
        "net/packet/af_packet.c:__packet_rcv_has_room"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593467856,
      "name": "packet_lookup_frame.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
  "name": "packet_lookup_frame",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595384992,
      "name": "packet_lookup_frame",
      "external": false,
      "loc": "net/packet/af_packet.c:512",
      "file": "net/packet/af_packet.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_poll",
        "net/packet/af_packet.c:packet_poll",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:__packet_rcv_has_room",
        "net/packet/af_packet.c:__packet_rcv_has_room"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595384992,
      "name": "packet_lookup_frame.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
  "name": "packet_lookup_frame",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595779568,
      "name": "packet_lookup_frame",
      "external": false,
      "loc": "net/packet/af_packet.c:514",
      "file": "net/packet/af_packet.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_poll",
        "net/packet/af_packet.c:packet_poll",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:__packet_rcv_has_room",
        "net/packet/af_packet.c:__packet_rcv_has_room"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595779568,
      "name": "packet_lookup_frame.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
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
  "name": "packet_lookup_frame",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596630016,
      "name": "packet_lookup_frame",
      "external": false,
      "loc": "net/packet/af_packet.c:514",
      "file": "net/packet/af_packet.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_poll",
        "net/packet/af_packet.c:packet_poll",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:__packet_rcv_has_room",
        "net/packet/af_packet.c:__packet_rcv_has_room"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596630016,
      "name": "packet_lookup_frame.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
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
void * packet_lookup_frame(const struct packet_sock * po, const struct packet_ring_buffer * rb, unsigned int position, int status)
```

```json
{
  "name": "packet_lookup_frame",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503618808,
      "name": "packet_lookup_frame",
      "external": false,
      "loc": "net/packet/af_packet.c:463",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_poll",
        "net/packet/af_packet.c:packet_poll",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503618808,
      "name": "packet_lookup_frame",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
void * packet_lookup_frame(const struct packet_sock * po, const struct packet_ring_buffer * rb, unsigned int position, int status)
```

```json
{
  "name": "packet_lookup_frame",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236272392,
      "name": "packet_lookup_frame",
      "external": false,
      "loc": "net/packet/af_packet.c:463",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_poll",
        "net/packet/af_packet.c:packet_poll",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236272392,
      "name": "packet_lookup_frame",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
void * packet_lookup_frame(const struct packet_sock * po, const struct packet_ring_buffer * rb, unsigned int position, int status)
```

```json
{
  "name": "packet_lookup_frame",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297444128,
      "name": "packet_lookup_frame",
      "external": false,
      "loc": "net/packet/af_packet.c:463",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_poll",
        "net/packet/af_packet.c:packet_poll",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297444128,
      "name": "packet_lookup_frame",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void * packet_lookup_frame(const struct packet_sock * po, const struct packet_ring_buffer * rb, unsigned int position, int status)
```

```json
{
  "name": "packet_lookup_frame",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279572974,
      "name": "packet_lookup_frame",
      "external": false,
      "loc": "net/packet/af_packet.c:463",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_poll",
        "net/packet/af_packet.c:packet_poll",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279572974,
      "name": "packet_lookup_frame",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void * packet_lookup_frame(const struct packet_sock * po, const struct packet_ring_buffer * rb, unsigned int position, int status)
```

```json
{
  "name": "packet_lookup_frame",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589501984,
      "name": "packet_lookup_frame",
      "external": false,
      "loc": "net/packet/af_packet.c:463",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_poll",
        "net/packet/af_packet.c:packet_poll",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589501984,
      "name": "packet_lookup_frame",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
void * packet_lookup_frame(const struct packet_sock * po, const struct packet_ring_buffer * rb, unsigned int position, int status)
```

```json
{
  "name": "packet_lookup_frame",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589228048,
      "name": "packet_lookup_frame",
      "external": false,
      "loc": "net/packet/af_packet.c:463",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_poll",
        "net/packet/af_packet.c:packet_poll",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589228048,
      "name": "packet_lookup_frame",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
void * packet_lookup_frame(const struct packet_sock * po, const struct packet_ring_buffer * rb, unsigned int position, int status)
```

```json
{
  "name": "packet_lookup_frame",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589943248,
      "name": "packet_lookup_frame",
      "external": false,
      "loc": "net/packet/af_packet.c:463",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_poll",
        "net/packet/af_packet.c:packet_poll",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589943248,
      "name": "packet_lookup_frame",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
void * packet_lookup_frame(const struct packet_sock * po, const struct packet_ring_buffer * rb, unsigned int position, int status)
```

```json
{
  "name": "packet_lookup_frame",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589995536,
      "name": "packet_lookup_frame",
      "external": false,
      "loc": "net/packet/af_packet.c:463",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_poll",
        "net/packet/af_packet.c:packet_poll",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589995536,
      "name": "packet_lookup_frame",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void * packet_lookup_frame(struct packet_sock * po, struct packet_ring_buffer * rb, unsigned int position, int status)
```
</details>
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
<code>struct packet_sock * po</code> ➡️ <code>const struct packet_sock * po</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct packet_ring_buffer * rb</code> ➡️ <code>const struct packet_ring_buffer * rb</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void * packet_lookup_frame(const struct packet_sock * po, const struct packet_ring_buffer * rb, unsigned int position, int status)
```
</details>
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
