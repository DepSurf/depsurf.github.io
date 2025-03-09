# Struct: <code>dcbnl_rtnl_ops</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct dcbnl_rtnl_ops {
    int (*)(struct net_device *, struct ieee_ets *) ieee_getets;
    int (*)(struct net_device *, struct ieee_ets *) ieee_setets;
    int (*)(struct net_device *, struct ieee_maxrate *) ieee_getmaxrate;
    int (*)(struct net_device *, struct ieee_maxrate *) ieee_setmaxrate;
    int (*)(struct net_device *, struct ieee_qcn *) ieee_getqcn;
    int (*)(struct net_device *, struct ieee_qcn *) ieee_setqcn;
    int (*)(struct net_device *, struct ieee_qcn_stats *) ieee_getqcnstats;
    int (*)(struct net_device *, struct ieee_pfc *) ieee_getpfc;
    int (*)(struct net_device *, struct ieee_pfc *) ieee_setpfc;
    int (*)(struct net_device *, struct dcb_app *) ieee_getapp;
    int (*)(struct net_device *, struct dcb_app *) ieee_setapp;
    int (*)(struct net_device *, struct dcb_app *) ieee_delapp;
    int (*)(struct net_device *, struct ieee_ets *) ieee_peer_getets;
    int (*)(struct net_device *, struct ieee_pfc *) ieee_peer_getpfc;
    u8 (*)(struct net_device *) getstate;
    u8 (*)(struct net_device *, u8) setstate;
    void (*)(struct net_device *, u8 *) getpermhwaddr;
    void (*)(struct net_device *, int, u8, u8, u8, u8) setpgtccfgtx;
    void (*)(struct net_device *, int, u8) setpgbwgcfgtx;
    void (*)(struct net_device *, int, u8, u8, u8, u8) setpgtccfgrx;
    void (*)(struct net_device *, int, u8) setpgbwgcfgrx;
    void (*)(struct net_device *, int, u8 *, u8 *, u8 *, u8 *) getpgtccfgtx;
    void (*)(struct net_device *, int, u8 *) getpgbwgcfgtx;
    void (*)(struct net_device *, int, u8 *, u8 *, u8 *, u8 *) getpgtccfgrx;
    void (*)(struct net_device *, int, u8 *) getpgbwgcfgrx;
    void (*)(struct net_device *, int, u8) setpfccfg;
    void (*)(struct net_device *, int, u8 *) getpfccfg;
    u8 (*)(struct net_device *) setall;
    u8 (*)(struct net_device *, int, u8 *) getcap;
    int (*)(struct net_device *, int, u8 *) getnumtcs;
    int (*)(struct net_device *, int, u8) setnumtcs;
    u8 (*)(struct net_device *) getpfcstate;
    void (*)(struct net_device *, u8) setpfcstate;
    void (*)(struct net_device *, int, u32 *) getbcncfg;
    void (*)(struct net_device *, int, u32) setbcncfg;
    void (*)(struct net_device *, int, u8 *) getbcnrp;
    void (*)(struct net_device *, int, u8) setbcnrp;
    int (*)(struct net_device *, u8, u16, u8) setapp;
    int (*)(struct net_device *, u8, u16) getapp;
    u8 (*)(struct net_device *, int, u8 *) getfeatcfg;
    u8 (*)(struct net_device *, int, u8) setfeatcfg;
    u8 (*)(struct net_device *) getdcbx;
    u8 (*)(struct net_device *, u8) setdcbx;
    int (*)(struct net_device *, struct dcb_peer_app_info *, u16 *) peer_getappinfo;
    int (*)(struct net_device *, struct dcb_app *) peer_getapptable;
    int (*)(struct net_device *, struct cee_pg *) cee_peer_getpg;
    int (*)(struct net_device *, struct cee_pfc *) cee_peer_getpfc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct dcbnl_rtnl_ops {
    int (*)(struct net_device *, struct ieee_ets *) ieee_getets;
    int (*)(struct net_device *, struct ieee_ets *) ieee_setets;
    int (*)(struct net_device *, struct ieee_maxrate *) ieee_getmaxrate;
    int (*)(struct net_device *, struct ieee_maxrate *) ieee_setmaxrate;
    int (*)(struct net_device *, struct ieee_qcn *) ieee_getqcn;
    int (*)(struct net_device *, struct ieee_qcn *) ieee_setqcn;
    int (*)(struct net_device *, struct ieee_qcn_stats *) ieee_getqcnstats;
    int (*)(struct net_device *, struct ieee_pfc *) ieee_getpfc;
    int (*)(struct net_device *, struct ieee_pfc *) ieee_setpfc;
    int (*)(struct net_device *, struct dcb_app *) ieee_getapp;
    int (*)(struct net_device *, struct dcb_app *) ieee_setapp;
    int (*)(struct net_device *, struct dcb_app *) ieee_delapp;
    int (*)(struct net_device *, struct ieee_ets *) ieee_peer_getets;
    int (*)(struct net_device *, struct ieee_pfc *) ieee_peer_getpfc;
    u8 (*)(struct net_device *) getstate;
    u8 (*)(struct net_device *, u8) setstate;
    void (*)(struct net_device *, u8 *) getpermhwaddr;
    void (*)(struct net_device *, int, u8, u8, u8, u8) setpgtccfgtx;
    void (*)(struct net_device *, int, u8) setpgbwgcfgtx;
    void (*)(struct net_device *, int, u8, u8, u8, u8) setpgtccfgrx;
    void (*)(struct net_device *, int, u8) setpgbwgcfgrx;
    void (*)(struct net_device *, int, u8 *, u8 *, u8 *, u8 *) getpgtccfgtx;
    void (*)(struct net_device *, int, u8 *) getpgbwgcfgtx;
    void (*)(struct net_device *, int, u8 *, u8 *, u8 *, u8 *) getpgtccfgrx;
    void (*)(struct net_device *, int, u8 *) getpgbwgcfgrx;
    void (*)(struct net_device *, int, u8) setpfccfg;
    void (*)(struct net_device *, int, u8 *) getpfccfg;
    u8 (*)(struct net_device *) setall;
    u8 (*)(struct net_device *, int, u8 *) getcap;
    int (*)(struct net_device *, int, u8 *) getnumtcs;
    int (*)(struct net_device *, int, u8) setnumtcs;
    u8 (*)(struct net_device *) getpfcstate;
    void (*)(struct net_device *, u8) setpfcstate;
    void (*)(struct net_device *, int, u32 *) getbcncfg;
    void (*)(struct net_device *, int, u32) setbcncfg;
    void (*)(struct net_device *, int, u8 *) getbcnrp;
    void (*)(struct net_device *, int, u8) setbcnrp;
    int (*)(struct net_device *, u8, u16, u8) setapp;
    int (*)(struct net_device *, u8, u16) getapp;
    u8 (*)(struct net_device *, int, u8 *) getfeatcfg;
    u8 (*)(struct net_device *, int, u8) setfeatcfg;
    u8 (*)(struct net_device *) getdcbx;
    u8 (*)(struct net_device *, u8) setdcbx;
    int (*)(struct net_device *, struct dcb_peer_app_info *, u16 *) peer_getappinfo;
    int (*)(struct net_device *, struct dcb_app *) peer_getapptable;
    int (*)(struct net_device *, struct cee_pg *) cee_peer_getpg;
    int (*)(struct net_device *, struct cee_pfc *) cee_peer_getpfc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct dcbnl_rtnl_ops {
    int (*)(struct net_device *, struct ieee_ets *) ieee_getets;
    int (*)(struct net_device *, struct ieee_ets *) ieee_setets;
    int (*)(struct net_device *, struct ieee_maxrate *) ieee_getmaxrate;
    int (*)(struct net_device *, struct ieee_maxrate *) ieee_setmaxrate;
    int (*)(struct net_device *, struct ieee_qcn *) ieee_getqcn;
    int (*)(struct net_device *, struct ieee_qcn *) ieee_setqcn;
    int (*)(struct net_device *, struct ieee_qcn_stats *) ieee_getqcnstats;
    int (*)(struct net_device *, struct ieee_pfc *) ieee_getpfc;
    int (*)(struct net_device *, struct ieee_pfc *) ieee_setpfc;
    int (*)(struct net_device *, struct dcb_app *) ieee_getapp;
    int (*)(struct net_device *, struct dcb_app *) ieee_setapp;
    int (*)(struct net_device *, struct dcb_app *) ieee_delapp;
    int (*)(struct net_device *, struct ieee_ets *) ieee_peer_getets;
    int (*)(struct net_device *, struct ieee_pfc *) ieee_peer_getpfc;
    u8 (*)(struct net_device *) getstate;
    u8 (*)(struct net_device *, u8) setstate;
    void (*)(struct net_device *, u8 *) getpermhwaddr;
    void (*)(struct net_device *, int, u8, u8, u8, u8) setpgtccfgtx;
    void (*)(struct net_device *, int, u8) setpgbwgcfgtx;
    void (*)(struct net_device *, int, u8, u8, u8, u8) setpgtccfgrx;
    void (*)(struct net_device *, int, u8) setpgbwgcfgrx;
    void (*)(struct net_device *, int, u8 *, u8 *, u8 *, u8 *) getpgtccfgtx;
    void (*)(struct net_device *, int, u8 *) getpgbwgcfgtx;
    void (*)(struct net_device *, int, u8 *, u8 *, u8 *, u8 *) getpgtccfgrx;
    void (*)(struct net_device *, int, u8 *) getpgbwgcfgrx;
    void (*)(struct net_device *, int, u8) setpfccfg;
    void (*)(struct net_device *, int, u8 *) getpfccfg;
    u8 (*)(struct net_device *) setall;
    u8 (*)(struct net_device *, int, u8 *) getcap;
    int (*)(struct net_device *, int, u8 *) getnumtcs;
    int (*)(struct net_device *, int, u8) setnumtcs;
    u8 (*)(struct net_device *) getpfcstate;
    void (*)(struct net_device *, u8) setpfcstate;
    void (*)(struct net_device *, int, u32 *) getbcncfg;
    void (*)(struct net_device *, int, u32) setbcncfg;
    void (*)(struct net_device *, int, u8 *) getbcnrp;
    void (*)(struct net_device *, int, u8) setbcnrp;
    int (*)(struct net_device *, u8, u16, u8) setapp;
    int (*)(struct net_device *, u8, u16) getapp;
    u8 (*)(struct net_device *, int, u8 *) getfeatcfg;
    u8 (*)(struct net_device *, int, u8) setfeatcfg;
    u8 (*)(struct net_device *) getdcbx;
    u8 (*)(struct net_device *, u8) setdcbx;
    int (*)(struct net_device *, struct dcb_peer_app_info *, u16 *) peer_getappinfo;
    int (*)(struct net_device *, struct dcb_app *) peer_getapptable;
    int (*)(struct net_device *, struct cee_pg *) cee_peer_getpg;
    int (*)(struct net_device *, struct cee_pfc *) cee_peer_getpfc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct dcbnl_rtnl_ops {
    int (*)(struct net_device *, struct ieee_ets *) ieee_getets;
    int (*)(struct net_device *, struct ieee_ets *) ieee_setets;
    int (*)(struct net_device *, struct ieee_maxrate *) ieee_getmaxrate;
    int (*)(struct net_device *, struct ieee_maxrate *) ieee_setmaxrate;
    int (*)(struct net_device *, struct ieee_qcn *) ieee_getqcn;
    int (*)(struct net_device *, struct ieee_qcn *) ieee_setqcn;
    int (*)(struct net_device *, struct ieee_qcn_stats *) ieee_getqcnstats;
    int (*)(struct net_device *, struct ieee_pfc *) ieee_getpfc;
    int (*)(struct net_device *, struct ieee_pfc *) ieee_setpfc;
    int (*)(struct net_device *, struct dcb_app *) ieee_getapp;
    int (*)(struct net_device *, struct dcb_app *) ieee_setapp;
    int (*)(struct net_device *, struct dcb_app *) ieee_delapp;
    int (*)(struct net_device *, struct ieee_ets *) ieee_peer_getets;
    int (*)(struct net_device *, struct ieee_pfc *) ieee_peer_getpfc;
    u8 (*)(struct net_device *) getstate;
    u8 (*)(struct net_device *, u8) setstate;
    void (*)(struct net_device *, u8 *) getpermhwaddr;
    void (*)(struct net_device *, int, u8, u8, u8, u8) setpgtccfgtx;
    void (*)(struct net_device *, int, u8) setpgbwgcfgtx;
    void (*)(struct net_device *, int, u8, u8, u8, u8) setpgtccfgrx;
    void (*)(struct net_device *, int, u8) setpgbwgcfgrx;
    void (*)(struct net_device *, int, u8 *, u8 *, u8 *, u8 *) getpgtccfgtx;
    void (*)(struct net_device *, int, u8 *) getpgbwgcfgtx;
    void (*)(struct net_device *, int, u8 *, u8 *, u8 *, u8 *) getpgtccfgrx;
    void (*)(struct net_device *, int, u8 *) getpgbwgcfgrx;
    void (*)(struct net_device *, int, u8) setpfccfg;
    void (*)(struct net_device *, int, u8 *) getpfccfg;
    u8 (*)(struct net_device *) setall;
    u8 (*)(struct net_device *, int, u8 *) getcap;
    int (*)(struct net_device *, int, u8 *) getnumtcs;
    int (*)(struct net_device *, int, u8) setnumtcs;
    u8 (*)(struct net_device *) getpfcstate;
    void (*)(struct net_device *, u8) setpfcstate;
    void (*)(struct net_device *, int, u32 *) getbcncfg;
    void (*)(struct net_device *, int, u32) setbcncfg;
    void (*)(struct net_device *, int, u8 *) getbcnrp;
    void (*)(struct net_device *, int, u8) setbcnrp;
    int (*)(struct net_device *, u8, u16, u8) setapp;
    int (*)(struct net_device *, u8, u16) getapp;
    u8 (*)(struct net_device *, int, u8 *) getfeatcfg;
    u8 (*)(struct net_device *, int, u8) setfeatcfg;
    u8 (*)(struct net_device *) getdcbx;
    u8 (*)(struct net_device *, u8) setdcbx;
    int (*)(struct net_device *, struct dcb_peer_app_info *, u16 *) peer_getappinfo;
    int (*)(struct net_device *, struct dcb_app *) peer_getapptable;
    int (*)(struct net_device *, struct cee_pg *) cee_peer_getpg;
    int (*)(struct net_device *, struct cee_pfc *) cee_peer_getpfc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct dcbnl_rtnl_ops {
    int (*)(struct net_device *, struct ieee_ets *) ieee_getets;
    int (*)(struct net_device *, struct ieee_ets *) ieee_setets;
    int (*)(struct net_device *, struct ieee_maxrate *) ieee_getmaxrate;
    int (*)(struct net_device *, struct ieee_maxrate *) ieee_setmaxrate;
    int (*)(struct net_device *, struct ieee_qcn *) ieee_getqcn;
    int (*)(struct net_device *, struct ieee_qcn *) ieee_setqcn;
    int (*)(struct net_device *, struct ieee_qcn_stats *) ieee_getqcnstats;
    int (*)(struct net_device *, struct ieee_pfc *) ieee_getpfc;
    int (*)(struct net_device *, struct ieee_pfc *) ieee_setpfc;
    int (*)(struct net_device *, struct dcb_app *) ieee_getapp;
    int (*)(struct net_device *, struct dcb_app *) ieee_setapp;
    int (*)(struct net_device *, struct dcb_app *) ieee_delapp;
    int (*)(struct net_device *, struct ieee_ets *) ieee_peer_getets;
    int (*)(struct net_device *, struct ieee_pfc *) ieee_peer_getpfc;
    u8 (*)(struct net_device *) getstate;
    u8 (*)(struct net_device *, u8) setstate;
    void (*)(struct net_device *, u8 *) getpermhwaddr;
    void (*)(struct net_device *, int, u8, u8, u8, u8) setpgtccfgtx;
    void (*)(struct net_device *, int, u8) setpgbwgcfgtx;
    void (*)(struct net_device *, int, u8, u8, u8, u8) setpgtccfgrx;
    void (*)(struct net_device *, int, u8) setpgbwgcfgrx;
    void (*)(struct net_device *, int, u8 *, u8 *, u8 *, u8 *) getpgtccfgtx;
    void (*)(struct net_device *, int, u8 *) getpgbwgcfgtx;
    void (*)(struct net_device *, int, u8 *, u8 *, u8 *, u8 *) getpgtccfgrx;
    void (*)(struct net_device *, int, u8 *) getpgbwgcfgrx;
    void (*)(struct net_device *, int, u8) setpfccfg;
    void (*)(struct net_device *, int, u8 *) getpfccfg;
    u8 (*)(struct net_device *) setall;
    u8 (*)(struct net_device *, int, u8 *) getcap;
    int (*)(struct net_device *, int, u8 *) getnumtcs;
    int (*)(struct net_device *, int, u8) setnumtcs;
    u8 (*)(struct net_device *) getpfcstate;
    void (*)(struct net_device *, u8) setpfcstate;
    void (*)(struct net_device *, int, u32 *) getbcncfg;
    void (*)(struct net_device *, int, u32) setbcncfg;
    void (*)(struct net_device *, int, u8 *) getbcnrp;
    void (*)(struct net_device *, int, u8) setbcnrp;
    int (*)(struct net_device *, u8, u16, u8) setapp;
    int (*)(struct net_device *, u8, u16) getapp;
    u8 (*)(struct net_device *, int, u8 *) getfeatcfg;
    u8 (*)(struct net_device *, int, u8) setfeatcfg;
    u8 (*)(struct net_device *) getdcbx;
    u8 (*)(struct net_device *, u8) setdcbx;
    int (*)(struct net_device *, struct dcb_peer_app_info *, u16 *) peer_getappinfo;
    int (*)(struct net_device *, struct dcb_app *) peer_getapptable;
    int (*)(struct net_device *, struct cee_pg *) cee_peer_getpg;
    int (*)(struct net_device *, struct cee_pfc *) cee_peer_getpfc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct dcbnl_rtnl_ops {
    int (*)(struct net_device *, struct ieee_ets *) ieee_getets;
    int (*)(struct net_device *, struct ieee_ets *) ieee_setets;
    int (*)(struct net_device *, struct ieee_maxrate *) ieee_getmaxrate;
    int (*)(struct net_device *, struct ieee_maxrate *) ieee_setmaxrate;
    int (*)(struct net_device *, struct ieee_qcn *) ieee_getqcn;
    int (*)(struct net_device *, struct ieee_qcn *) ieee_setqcn;
    int (*)(struct net_device *, struct ieee_qcn_stats *) ieee_getqcnstats;
    int (*)(struct net_device *, struct ieee_pfc *) ieee_getpfc;
    int (*)(struct net_device *, struct ieee_pfc *) ieee_setpfc;
    int (*)(struct net_device *, struct dcb_app *) ieee_getapp;
    int (*)(struct net_device *, struct dcb_app *) ieee_setapp;
    int (*)(struct net_device *, struct dcb_app *) ieee_delapp;
    int (*)(struct net_device *, struct ieee_ets *) ieee_peer_getets;
    int (*)(struct net_device *, struct ieee_pfc *) ieee_peer_getpfc;
    u8 (*)(struct net_device *) getstate;
    u8 (*)(struct net_device *, u8) setstate;
    void (*)(struct net_device *, u8 *) getpermhwaddr;
    void (*)(struct net_device *, int, u8, u8, u8, u8) setpgtccfgtx;
    void (*)(struct net_device *, int, u8) setpgbwgcfgtx;
    void (*)(struct net_device *, int, u8, u8, u8, u8) setpgtccfgrx;
    void (*)(struct net_device *, int, u8) setpgbwgcfgrx;
    void (*)(struct net_device *, int, u8 *, u8 *, u8 *, u8 *) getpgtccfgtx;
    void (*)(struct net_device *, int, u8 *) getpgbwgcfgtx;
    void (*)(struct net_device *, int, u8 *, u8 *, u8 *, u8 *) getpgtccfgrx;
    void (*)(struct net_device *, int, u8 *) getpgbwgcfgrx;
    void (*)(struct net_device *, int, u8) setpfccfg;
    void (*)(struct net_device *, int, u8 *) getpfccfg;
    u8 (*)(struct net_device *) setall;
    u8 (*)(struct net_device *, int, u8 *) getcap;
    int (*)(struct net_device *, int, u8 *) getnumtcs;
    int (*)(struct net_device *, int, u8) setnumtcs;
    u8 (*)(struct net_device *) getpfcstate;
    void (*)(struct net_device *, u8) setpfcstate;
    void (*)(struct net_device *, int, u32 *) getbcncfg;
    void (*)(struct net_device *, int, u32) setbcncfg;
    void (*)(struct net_device *, int, u8 *) getbcnrp;
    void (*)(struct net_device *, int, u8) setbcnrp;
    int (*)(struct net_device *, u8, u16, u8) setapp;
    int (*)(struct net_device *, u8, u16) getapp;
    u8 (*)(struct net_device *, int, u8 *) getfeatcfg;
    u8 (*)(struct net_device *, int, u8) setfeatcfg;
    u8 (*)(struct net_device *) getdcbx;
    u8 (*)(struct net_device *, u8) setdcbx;
    int (*)(struct net_device *, struct dcb_peer_app_info *, u16 *) peer_getappinfo;
    int (*)(struct net_device *, struct dcb_app *) peer_getapptable;
    int (*)(struct net_device *, struct cee_pg *) cee_peer_getpg;
    int (*)(struct net_device *, struct cee_pfc *) cee_peer_getpfc;
    int (*)(struct net_device *, struct dcbnl_buffer *) dcbnl_getbuffer;
    int (*)(struct net_device *, struct dcbnl_buffer *) dcbnl_setbuffer;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct dcbnl_rtnl_ops {
    int (*)(struct net_device *, struct ieee_ets *) ieee_getets;
    int (*)(struct net_device *, struct ieee_ets *) ieee_setets;
    int (*)(struct net_device *, struct ieee_maxrate *) ieee_getmaxrate;
    int (*)(struct net_device *, struct ieee_maxrate *) ieee_setmaxrate;
    int (*)(struct net_device *, struct ieee_qcn *) ieee_getqcn;
    int (*)(struct net_device *, struct ieee_qcn *) ieee_setqcn;
    int (*)(struct net_device *, struct ieee_qcn_stats *) ieee_getqcnstats;
    int (*)(struct net_device *, struct ieee_pfc *) ieee_getpfc;
    int (*)(struct net_device *, struct ieee_pfc *) ieee_setpfc;
    int (*)(struct net_device *, struct dcb_app *) ieee_getapp;
    int (*)(struct net_device *, struct dcb_app *) ieee_setapp;
    int (*)(struct net_device *, struct dcb_app *) ieee_delapp;
    int (*)(struct net_device *, struct ieee_ets *) ieee_peer_getets;
    int (*)(struct net_device *, struct ieee_pfc *) ieee_peer_getpfc;
    u8 (*)(struct net_device *) getstate;
    u8 (*)(struct net_device *, u8) setstate;
    void (*)(struct net_device *, u8 *) getpermhwaddr;
    void (*)(struct net_device *, int, u8, u8, u8, u8) setpgtccfgtx;
    void (*)(struct net_device *, int, u8) setpgbwgcfgtx;
    void (*)(struct net_device *, int, u8, u8, u8, u8) setpgtccfgrx;
    void (*)(struct net_device *, int, u8) setpgbwgcfgrx;
    void (*)(struct net_device *, int, u8 *, u8 *, u8 *, u8 *) getpgtccfgtx;
    void (*)(struct net_device *, int, u8 *) getpgbwgcfgtx;
    void (*)(struct net_device *, int, u8 *, u8 *, u8 *, u8 *) getpgtccfgrx;
    void (*)(struct net_device *, int, u8 *) getpgbwgcfgrx;
    void (*)(struct net_device *, int, u8) setpfccfg;
    void (*)(struct net_device *, int, u8 *) getpfccfg;
    u8 (*)(struct net_device *) setall;
    u8 (*)(struct net_device *, int, u8 *) getcap;
    int (*)(struct net_device *, int, u8 *) getnumtcs;
    int (*)(struct net_device *, int, u8) setnumtcs;
    u8 (*)(struct net_device *) getpfcstate;
    void (*)(struct net_device *, u8) setpfcstate;
    void (*)(struct net_device *, int, u32 *) getbcncfg;
    void (*)(struct net_device *, int, u32) setbcncfg;
    void (*)(struct net_device *, int, u8 *) getbcnrp;
    void (*)(struct net_device *, int, u8) setbcnrp;
    int (*)(struct net_device *, u8, u16, u8) setapp;
    int (*)(struct net_device *, u8, u16) getapp;
    u8 (*)(struct net_device *, int, u8 *) getfeatcfg;
    u8 (*)(struct net_device *, int, u8) setfeatcfg;
    u8 (*)(struct net_device *) getdcbx;
    u8 (*)(struct net_device *, u8) setdcbx;
    int (*)(struct net_device *, struct dcb_peer_app_info *, u16 *) peer_getappinfo;
    int (*)(struct net_device *, struct dcb_app *) peer_getapptable;
    int (*)(struct net_device *, struct cee_pg *) cee_peer_getpg;
    int (*)(struct net_device *, struct cee_pfc *) cee_peer_getpfc;
    int (*)(struct net_device *, struct dcbnl_buffer *) dcbnl_getbuffer;
    int (*)(struct net_device *, struct dcbnl_buffer *) dcbnl_setbuffer;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct dcbnl_rtnl_ops {
    int (*)(struct net_device *, struct ieee_ets *) ieee_getets;
    int (*)(struct net_device *, struct ieee_ets *) ieee_setets;
    int (*)(struct net_device *, struct ieee_maxrate *) ieee_getmaxrate;
    int (*)(struct net_device *, struct ieee_maxrate *) ieee_setmaxrate;
    int (*)(struct net_device *, struct ieee_qcn *) ieee_getqcn;
    int (*)(struct net_device *, struct ieee_qcn *) ieee_setqcn;
    int (*)(struct net_device *, struct ieee_qcn_stats *) ieee_getqcnstats;
    int (*)(struct net_device *, struct ieee_pfc *) ieee_getpfc;
    int (*)(struct net_device *, struct ieee_pfc *) ieee_setpfc;
    int (*)(struct net_device *, struct dcb_app *) ieee_getapp;
    int (*)(struct net_device *, struct dcb_app *) ieee_setapp;
    int (*)(struct net_device *, struct dcb_app *) ieee_delapp;
    int (*)(struct net_device *, struct ieee_ets *) ieee_peer_getets;
    int (*)(struct net_device *, struct ieee_pfc *) ieee_peer_getpfc;
    u8 (*)(struct net_device *) getstate;
    u8 (*)(struct net_device *, u8) setstate;
    void (*)(struct net_device *, u8 *) getpermhwaddr;
    void (*)(struct net_device *, int, u8, u8, u8, u8) setpgtccfgtx;
    void (*)(struct net_device *, int, u8) setpgbwgcfgtx;
    void (*)(struct net_device *, int, u8, u8, u8, u8) setpgtccfgrx;
    void (*)(struct net_device *, int, u8) setpgbwgcfgrx;
    void (*)(struct net_device *, int, u8 *, u8 *, u8 *, u8 *) getpgtccfgtx;
    void (*)(struct net_device *, int, u8 *) getpgbwgcfgtx;
    void (*)(struct net_device *, int, u8 *, u8 *, u8 *, u8 *) getpgtccfgrx;
    void (*)(struct net_device *, int, u8 *) getpgbwgcfgrx;
    void (*)(struct net_device *, int, u8) setpfccfg;
    void (*)(struct net_device *, int, u8 *) getpfccfg;
    u8 (*)(struct net_device *) setall;
    u8 (*)(struct net_device *, int, u8 *) getcap;
    int (*)(struct net_device *, int, u8 *) getnumtcs;
    int (*)(struct net_device *, int, u8) setnumtcs;
    u8 (*)(struct net_device *) getpfcstate;
    void (*)(struct net_device *, u8) setpfcstate;
    void (*)(struct net_device *, int, u32 *) getbcncfg;
    void (*)(struct net_device *, int, u32) setbcncfg;
    void (*)(struct net_device *, int, u8 *) getbcnrp;
    void (*)(struct net_device *, int, u8) setbcnrp;
    int (*)(struct net_device *, u8, u16, u8) setapp;
    int (*)(struct net_device *, u8, u16) getapp;
    u8 (*)(struct net_device *, int, u8 *) getfeatcfg;
    u8 (*)(struct net_device *, int, u8) setfeatcfg;
    u8 (*)(struct net_device *) getdcbx;
    u8 (*)(struct net_device *, u8) setdcbx;
    int (*)(struct net_device *, struct dcb_peer_app_info *, u16 *) peer_getappinfo;
    int (*)(struct net_device *, struct dcb_app *) peer_getapptable;
    int (*)(struct net_device *, struct cee_pg *) cee_peer_getpg;
    int (*)(struct net_device *, struct cee_pfc *) cee_peer_getpfc;
    int (*)(struct net_device *, struct dcbnl_buffer *) dcbnl_getbuffer;
    int (*)(struct net_device *, struct dcbnl_buffer *) dcbnl_setbuffer;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct dcbnl_rtnl_ops {
    int (*)(struct net_device *, struct ieee_ets *) ieee_getets;
    int (*)(struct net_device *, struct ieee_ets *) ieee_setets;
    int (*)(struct net_device *, struct ieee_maxrate *) ieee_getmaxrate;
    int (*)(struct net_device *, struct ieee_maxrate *) ieee_setmaxrate;
    int (*)(struct net_device *, struct ieee_qcn *) ieee_getqcn;
    int (*)(struct net_device *, struct ieee_qcn *) ieee_setqcn;
    int (*)(struct net_device *, struct ieee_qcn_stats *) ieee_getqcnstats;
    int (*)(struct net_device *, struct ieee_pfc *) ieee_getpfc;
    int (*)(struct net_device *, struct ieee_pfc *) ieee_setpfc;
    int (*)(struct net_device *, struct dcb_app *) ieee_getapp;
    int (*)(struct net_device *, struct dcb_app *) ieee_setapp;
    int (*)(struct net_device *, struct dcb_app *) ieee_delapp;
    int (*)(struct net_device *, struct ieee_ets *) ieee_peer_getets;
    int (*)(struct net_device *, struct ieee_pfc *) ieee_peer_getpfc;
    u8 (*)(struct net_device *) getstate;
    u8 (*)(struct net_device *, u8) setstate;
    void (*)(struct net_device *, u8 *) getpermhwaddr;
    void (*)(struct net_device *, int, u8, u8, u8, u8) setpgtccfgtx;
    void (*)(struct net_device *, int, u8) setpgbwgcfgtx;
    void (*)(struct net_device *, int, u8, u8, u8, u8) setpgtccfgrx;
    void (*)(struct net_device *, int, u8) setpgbwgcfgrx;
    void (*)(struct net_device *, int, u8 *, u8 *, u8 *, u8 *) getpgtccfgtx;
    void (*)(struct net_device *, int, u8 *) getpgbwgcfgtx;
    void (*)(struct net_device *, int, u8 *, u8 *, u8 *, u8 *) getpgtccfgrx;
    void (*)(struct net_device *, int, u8 *) getpgbwgcfgrx;
    void (*)(struct net_device *, int, u8) setpfccfg;
    void (*)(struct net_device *, int, u8 *) getpfccfg;
    u8 (*)(struct net_device *) setall;
    u8 (*)(struct net_device *, int, u8 *) getcap;
    int (*)(struct net_device *, int, u8 *) getnumtcs;
    int (*)(struct net_device *, int, u8) setnumtcs;
    u8 (*)(struct net_device *) getpfcstate;
    void (*)(struct net_device *, u8) setpfcstate;
    void (*)(struct net_device *, int, u32 *) getbcncfg;
    void (*)(struct net_device *, int, u32) setbcncfg;
    void (*)(struct net_device *, int, u8 *) getbcnrp;
    void (*)(struct net_device *, int, u8) setbcnrp;
    int (*)(struct net_device *, u8, u16, u8) setapp;
    int (*)(struct net_device *, u8, u16) getapp;
    u8 (*)(struct net_device *, int, u8 *) getfeatcfg;
    u8 (*)(struct net_device *, int, u8) setfeatcfg;
    u8 (*)(struct net_device *) getdcbx;
    u8 (*)(struct net_device *, u8) setdcbx;
    int (*)(struct net_device *, struct dcb_peer_app_info *, u16 *) peer_getappinfo;
    int (*)(struct net_device *, struct dcb_app *) peer_getapptable;
    int (*)(struct net_device *, struct cee_pg *) cee_peer_getpg;
    int (*)(struct net_device *, struct cee_pfc *) cee_peer_getpfc;
    int (*)(struct net_device *, struct dcbnl_buffer *) dcbnl_getbuffer;
    int (*)(struct net_device *, struct dcbnl_buffer *) dcbnl_setbuffer;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct dcbnl_rtnl_ops {
    int (*)(struct net_device *, struct ieee_ets *) ieee_getets;
    int (*)(struct net_device *, struct ieee_ets *) ieee_setets;
    int (*)(struct net_device *, struct ieee_maxrate *) ieee_getmaxrate;
    int (*)(struct net_device *, struct ieee_maxrate *) ieee_setmaxrate;
    int (*)(struct net_device *, struct ieee_qcn *) ieee_getqcn;
    int (*)(struct net_device *, struct ieee_qcn *) ieee_setqcn;
    int (*)(struct net_device *, struct ieee_qcn_stats *) ieee_getqcnstats;
    int (*)(struct net_device *, struct ieee_pfc *) ieee_getpfc;
    int (*)(struct net_device *, struct ieee_pfc *) ieee_setpfc;
    int (*)(struct net_device *, struct dcb_app *) ieee_getapp;
    int (*)(struct net_device *, struct dcb_app *) ieee_setapp;
    int (*)(struct net_device *, struct dcb_app *) ieee_delapp;
    int (*)(struct net_device *, struct ieee_ets *) ieee_peer_getets;
    int (*)(struct net_device *, struct ieee_pfc *) ieee_peer_getpfc;
    u8 (*)(struct net_device *) getstate;
    u8 (*)(struct net_device *, u8) setstate;
    void (*)(struct net_device *, u8 *) getpermhwaddr;
    void (*)(struct net_device *, int, u8, u8, u8, u8) setpgtccfgtx;
    void (*)(struct net_device *, int, u8) setpgbwgcfgtx;
    void (*)(struct net_device *, int, u8, u8, u8, u8) setpgtccfgrx;
    void (*)(struct net_device *, int, u8) setpgbwgcfgrx;
    void (*)(struct net_device *, int, u8 *, u8 *, u8 *, u8 *) getpgtccfgtx;
    void (*)(struct net_device *, int, u8 *) getpgbwgcfgtx;
    void (*)(struct net_device *, int, u8 *, u8 *, u8 *, u8 *) getpgtccfgrx;
    void (*)(struct net_device *, int, u8 *) getpgbwgcfgrx;
    void (*)(struct net_device *, int, u8) setpfccfg;
    void (*)(struct net_device *, int, u8 *) getpfccfg;
    u8 (*)(struct net_device *) setall;
    u8 (*)(struct net_device *, int, u8 *) getcap;
    int (*)(struct net_device *, int, u8 *) getnumtcs;
    int (*)(struct net_device *, int, u8) setnumtcs;
    u8 (*)(struct net_device *) getpfcstate;
    void (*)(struct net_device *, u8) setpfcstate;
    void (*)(struct net_device *, int, u32 *) getbcncfg;
    void (*)(struct net_device *, int, u32) setbcncfg;
    void (*)(struct net_device *, int, u8 *) getbcnrp;
    void (*)(struct net_device *, int, u8) setbcnrp;
    int (*)(struct net_device *, u8, u16, u8) setapp;
    int (*)(struct net_device *, u8, u16) getapp;
    u8 (*)(struct net_device *, int, u8 *) getfeatcfg;
    u8 (*)(struct net_device *, int, u8) setfeatcfg;
    u8 (*)(struct net_device *) getdcbx;
    u8 (*)(struct net_device *, u8) setdcbx;
    int (*)(struct net_device *, struct dcb_peer_app_info *, u16 *) peer_getappinfo;
    int (*)(struct net_device *, struct dcb_app *) peer_getapptable;
    int (*)(struct net_device *, struct cee_pg *) cee_peer_getpg;
    int (*)(struct net_device *, struct cee_pfc *) cee_peer_getpfc;
    int (*)(struct net_device *, struct dcbnl_buffer *) dcbnl_getbuffer;
    int (*)(struct net_device *, struct dcbnl_buffer *) dcbnl_setbuffer;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct dcbnl_rtnl_ops {
    int (*)(struct net_device *, struct ieee_ets *) ieee_getets;
    int (*)(struct net_device *, struct ieee_ets *) ieee_setets;
    int (*)(struct net_device *, struct ieee_maxrate *) ieee_getmaxrate;
    int (*)(struct net_device *, struct ieee_maxrate *) ieee_setmaxrate;
    int (*)(struct net_device *, struct ieee_qcn *) ieee_getqcn;
    int (*)(struct net_device *, struct ieee_qcn *) ieee_setqcn;
    int (*)(struct net_device *, struct ieee_qcn_stats *) ieee_getqcnstats;
    int (*)(struct net_device *, struct ieee_pfc *) ieee_getpfc;
    int (*)(struct net_device *, struct ieee_pfc *) ieee_setpfc;
    int (*)(struct net_device *, struct dcb_app *) ieee_getapp;
    int (*)(struct net_device *, struct dcb_app *) ieee_setapp;
    int (*)(struct net_device *, struct dcb_app *) ieee_delapp;
    int (*)(struct net_device *, struct ieee_ets *) ieee_peer_getets;
    int (*)(struct net_device *, struct ieee_pfc *) ieee_peer_getpfc;
    u8 (*)(struct net_device *) getstate;
    u8 (*)(struct net_device *, u8) setstate;
    void (*)(struct net_device *, u8 *) getpermhwaddr;
    void (*)(struct net_device *, int, u8, u8, u8, u8) setpgtccfgtx;
    void (*)(struct net_device *, int, u8) setpgbwgcfgtx;
    void (*)(struct net_device *, int, u8, u8, u8, u8) setpgtccfgrx;
    void (*)(struct net_device *, int, u8) setpgbwgcfgrx;
    void (*)(struct net_device *, int, u8 *, u8 *, u8 *, u8 *) getpgtccfgtx;
    void (*)(struct net_device *, int, u8 *) getpgbwgcfgtx;
    void (*)(struct net_device *, int, u8 *, u8 *, u8 *, u8 *) getpgtccfgrx;
    void (*)(struct net_device *, int, u8 *) getpgbwgcfgrx;
    void (*)(struct net_device *, int, u8) setpfccfg;
    void (*)(struct net_device *, int, u8 *) getpfccfg;
    u8 (*)(struct net_device *) setall;
    u8 (*)(struct net_device *, int, u8 *) getcap;
    int (*)(struct net_device *, int, u8 *) getnumtcs;
    int (*)(struct net_device *, int, u8) setnumtcs;
    u8 (*)(struct net_device *) getpfcstate;
    void (*)(struct net_device *, u8) setpfcstate;
    void (*)(struct net_device *, int, u32 *) getbcncfg;
    void (*)(struct net_device *, int, u32) setbcncfg;
    void (*)(struct net_device *, int, u8 *) getbcnrp;
    void (*)(struct net_device *, int, u8) setbcnrp;
    int (*)(struct net_device *, u8, u16, u8) setapp;
    int (*)(struct net_device *, u8, u16) getapp;
    u8 (*)(struct net_device *, int, u8 *) getfeatcfg;
    u8 (*)(struct net_device *, int, u8) setfeatcfg;
    u8 (*)(struct net_device *) getdcbx;
    u8 (*)(struct net_device *, u8) setdcbx;
    int (*)(struct net_device *, struct dcb_peer_app_info *, u16 *) peer_getappinfo;
    int (*)(struct net_device *, struct dcb_app *) peer_getapptable;
    int (*)(struct net_device *, struct cee_pg *) cee_peer_getpg;
    int (*)(struct net_device *, struct cee_pfc *) cee_peer_getpfc;
    int (*)(struct net_device *, struct dcbnl_buffer *) dcbnl_getbuffer;
    int (*)(struct net_device *, struct dcbnl_buffer *) dcbnl_setbuffer;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct dcbnl_rtnl_ops {
    int (*)(struct net_device *, struct ieee_ets *) ieee_getets;
    int (*)(struct net_device *, struct ieee_ets *) ieee_setets;
    int (*)(struct net_device *, struct ieee_maxrate *) ieee_getmaxrate;
    int (*)(struct net_device *, struct ieee_maxrate *) ieee_setmaxrate;
    int (*)(struct net_device *, struct ieee_qcn *) ieee_getqcn;
    int (*)(struct net_device *, struct ieee_qcn *) ieee_setqcn;
    int (*)(struct net_device *, struct ieee_qcn_stats *) ieee_getqcnstats;
    int (*)(struct net_device *, struct ieee_pfc *) ieee_getpfc;
    int (*)(struct net_device *, struct ieee_pfc *) ieee_setpfc;
    int (*)(struct net_device *, struct dcb_app *) ieee_getapp;
    int (*)(struct net_device *, struct dcb_app *) ieee_setapp;
    int (*)(struct net_device *, struct dcb_app *) ieee_delapp;
    int (*)(struct net_device *, struct ieee_ets *) ieee_peer_getets;
    int (*)(struct net_device *, struct ieee_pfc *) ieee_peer_getpfc;
    u8 (*)(struct net_device *) getstate;
    u8 (*)(struct net_device *, u8) setstate;
    void (*)(struct net_device *, u8 *) getpermhwaddr;
    void (*)(struct net_device *, int, u8, u8, u8, u8) setpgtccfgtx;
    void (*)(struct net_device *, int, u8) setpgbwgcfgtx;
    void (*)(struct net_device *, int, u8, u8, u8, u8) setpgtccfgrx;
    void (*)(struct net_device *, int, u8) setpgbwgcfgrx;
    void (*)(struct net_device *, int, u8 *, u8 *, u8 *, u8 *) getpgtccfgtx;
    void (*)(struct net_device *, int, u8 *) getpgbwgcfgtx;
    void (*)(struct net_device *, int, u8 *, u8 *, u8 *, u8 *) getpgtccfgrx;
    void (*)(struct net_device *, int, u8 *) getpgbwgcfgrx;
    void (*)(struct net_device *, int, u8) setpfccfg;
    void (*)(struct net_device *, int, u8 *) getpfccfg;
    u8 (*)(struct net_device *) setall;
    u8 (*)(struct net_device *, int, u8 *) getcap;
    int (*)(struct net_device *, int, u8 *) getnumtcs;
    int (*)(struct net_device *, int, u8) setnumtcs;
    u8 (*)(struct net_device *) getpfcstate;
    void (*)(struct net_device *, u8) setpfcstate;
    void (*)(struct net_device *, int, u32 *) getbcncfg;
    void (*)(struct net_device *, int, u32) setbcncfg;
    void (*)(struct net_device *, int, u8 *) getbcnrp;
    void (*)(struct net_device *, int, u8) setbcnrp;
    int (*)(struct net_device *, u8, u16, u8) setapp;
    int (*)(struct net_device *, u8, u16) getapp;
    u8 (*)(struct net_device *, int, u8 *) getfeatcfg;
    u8 (*)(struct net_device *, int, u8) setfeatcfg;
    u8 (*)(struct net_device *) getdcbx;
    u8 (*)(struct net_device *, u8) setdcbx;
    int (*)(struct net_device *, struct dcb_peer_app_info *, u16 *) peer_getappinfo;
    int (*)(struct net_device *, struct dcb_app *) peer_getapptable;
    int (*)(struct net_device *, struct cee_pg *) cee_peer_getpg;
    int (*)(struct net_device *, struct cee_pfc *) cee_peer_getpfc;
    int (*)(struct net_device *, struct dcbnl_buffer *) dcbnl_getbuffer;
    int (*)(struct net_device *, struct dcbnl_buffer *) dcbnl_setbuffer;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct dcbnl_rtnl_ops {
    int (*)(struct net_device *, struct ieee_ets *) ieee_getets;
    int (*)(struct net_device *, struct ieee_ets *) ieee_setets;
    int (*)(struct net_device *, struct ieee_maxrate *) ieee_getmaxrate;
    int (*)(struct net_device *, struct ieee_maxrate *) ieee_setmaxrate;
    int (*)(struct net_device *, struct ieee_qcn *) ieee_getqcn;
    int (*)(struct net_device *, struct ieee_qcn *) ieee_setqcn;
    int (*)(struct net_device *, struct ieee_qcn_stats *) ieee_getqcnstats;
    int (*)(struct net_device *, struct ieee_pfc *) ieee_getpfc;
    int (*)(struct net_device *, struct ieee_pfc *) ieee_setpfc;
    int (*)(struct net_device *, struct dcb_app *) ieee_getapp;
    int (*)(struct net_device *, struct dcb_app *) ieee_setapp;
    int (*)(struct net_device *, struct dcb_app *) ieee_delapp;
    int (*)(struct net_device *, struct ieee_ets *) ieee_peer_getets;
    int (*)(struct net_device *, struct ieee_pfc *) ieee_peer_getpfc;
    u8 (*)(struct net_device *) getstate;
    u8 (*)(struct net_device *, u8) setstate;
    void (*)(struct net_device *, u8 *) getpermhwaddr;
    void (*)(struct net_device *, int, u8, u8, u8, u8) setpgtccfgtx;
    void (*)(struct net_device *, int, u8) setpgbwgcfgtx;
    void (*)(struct net_device *, int, u8, u8, u8, u8) setpgtccfgrx;
    void (*)(struct net_device *, int, u8) setpgbwgcfgrx;
    void (*)(struct net_device *, int, u8 *, u8 *, u8 *, u8 *) getpgtccfgtx;
    void (*)(struct net_device *, int, u8 *) getpgbwgcfgtx;
    void (*)(struct net_device *, int, u8 *, u8 *, u8 *, u8 *) getpgtccfgrx;
    void (*)(struct net_device *, int, u8 *) getpgbwgcfgrx;
    void (*)(struct net_device *, int, u8) setpfccfg;
    void (*)(struct net_device *, int, u8 *) getpfccfg;
    u8 (*)(struct net_device *) setall;
    u8 (*)(struct net_device *, int, u8 *) getcap;
    int (*)(struct net_device *, int, u8 *) getnumtcs;
    int (*)(struct net_device *, int, u8) setnumtcs;
    u8 (*)(struct net_device *) getpfcstate;
    void (*)(struct net_device *, u8) setpfcstate;
    void (*)(struct net_device *, int, u32 *) getbcncfg;
    void (*)(struct net_device *, int, u32) setbcncfg;
    void (*)(struct net_device *, int, u8 *) getbcnrp;
    void (*)(struct net_device *, int, u8) setbcnrp;
    int (*)(struct net_device *, u8, u16, u8) setapp;
    int (*)(struct net_device *, u8, u16) getapp;
    u8 (*)(struct net_device *, int, u8 *) getfeatcfg;
    u8 (*)(struct net_device *, int, u8) setfeatcfg;
    u8 (*)(struct net_device *) getdcbx;
    u8 (*)(struct net_device *, u8) setdcbx;
    int (*)(struct net_device *, struct dcb_peer_app_info *, u16 *) peer_getappinfo;
    int (*)(struct net_device *, struct dcb_app *) peer_getapptable;
    int (*)(struct net_device *, struct cee_pg *) cee_peer_getpg;
    int (*)(struct net_device *, struct cee_pfc *) cee_peer_getpfc;
    int (*)(struct net_device *, struct dcbnl_buffer *) dcbnl_getbuffer;
    int (*)(struct net_device *, struct dcbnl_buffer *) dcbnl_setbuffer;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct dcbnl_rtnl_ops {
    int (*)(struct net_device *, struct ieee_ets *) ieee_getets;
    int (*)(struct net_device *, struct ieee_ets *) ieee_setets;
    int (*)(struct net_device *, struct ieee_maxrate *) ieee_getmaxrate;
    int (*)(struct net_device *, struct ieee_maxrate *) ieee_setmaxrate;
    int (*)(struct net_device *, struct ieee_qcn *) ieee_getqcn;
    int (*)(struct net_device *, struct ieee_qcn *) ieee_setqcn;
    int (*)(struct net_device *, struct ieee_qcn_stats *) ieee_getqcnstats;
    int (*)(struct net_device *, struct ieee_pfc *) ieee_getpfc;
    int (*)(struct net_device *, struct ieee_pfc *) ieee_setpfc;
    int (*)(struct net_device *, struct dcb_app *) ieee_getapp;
    int (*)(struct net_device *, struct dcb_app *) ieee_setapp;
    int (*)(struct net_device *, struct dcb_app *) ieee_delapp;
    int (*)(struct net_device *, struct ieee_ets *) ieee_peer_getets;
    int (*)(struct net_device *, struct ieee_pfc *) ieee_peer_getpfc;
    u8 (*)(struct net_device *) getstate;
    u8 (*)(struct net_device *, u8) setstate;
    void (*)(struct net_device *, u8 *) getpermhwaddr;
    void (*)(struct net_device *, int, u8, u8, u8, u8) setpgtccfgtx;
    void (*)(struct net_device *, int, u8) setpgbwgcfgtx;
    void (*)(struct net_device *, int, u8, u8, u8, u8) setpgtccfgrx;
    void (*)(struct net_device *, int, u8) setpgbwgcfgrx;
    void (*)(struct net_device *, int, u8 *, u8 *, u8 *, u8 *) getpgtccfgtx;
    void (*)(struct net_device *, int, u8 *) getpgbwgcfgtx;
    void (*)(struct net_device *, int, u8 *, u8 *, u8 *, u8 *) getpgtccfgrx;
    void (*)(struct net_device *, int, u8 *) getpgbwgcfgrx;
    void (*)(struct net_device *, int, u8) setpfccfg;
    void (*)(struct net_device *, int, u8 *) getpfccfg;
    u8 (*)(struct net_device *) setall;
    u8 (*)(struct net_device *, int, u8 *) getcap;
    int (*)(struct net_device *, int, u8 *) getnumtcs;
    int (*)(struct net_device *, int, u8) setnumtcs;
    u8 (*)(struct net_device *) getpfcstate;
    void (*)(struct net_device *, u8) setpfcstate;
    void (*)(struct net_device *, int, u32 *) getbcncfg;
    void (*)(struct net_device *, int, u32) setbcncfg;
    void (*)(struct net_device *, int, u8 *) getbcnrp;
    void (*)(struct net_device *, int, u8) setbcnrp;
    int (*)(struct net_device *, u8, u16, u8) setapp;
    int (*)(struct net_device *, u8, u16) getapp;
    u8 (*)(struct net_device *, int, u8 *) getfeatcfg;
    u8 (*)(struct net_device *, int, u8) setfeatcfg;
    u8 (*)(struct net_device *) getdcbx;
    u8 (*)(struct net_device *, u8) setdcbx;
    int (*)(struct net_device *, struct dcb_peer_app_info *, u16 *) peer_getappinfo;
    int (*)(struct net_device *, struct dcb_app *) peer_getapptable;
    int (*)(struct net_device *, struct cee_pg *) cee_peer_getpg;
    int (*)(struct net_device *, struct cee_pfc *) cee_peer_getpfc;
    int (*)(struct net_device *, struct dcbnl_buffer *) dcbnl_getbuffer;
    int (*)(struct net_device *, struct dcbnl_buffer *) dcbnl_setbuffer;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct dcbnl_rtnl_ops {
    int (*)(struct net_device *, struct ieee_ets *) ieee_getets;
    int (*)(struct net_device *, struct ieee_ets *) ieee_setets;
    int (*)(struct net_device *, struct ieee_maxrate *) ieee_getmaxrate;
    int (*)(struct net_device *, struct ieee_maxrate *) ieee_setmaxrate;
    int (*)(struct net_device *, struct ieee_qcn *) ieee_getqcn;
    int (*)(struct net_device *, struct ieee_qcn *) ieee_setqcn;
    int (*)(struct net_device *, struct ieee_qcn_stats *) ieee_getqcnstats;
    int (*)(struct net_device *, struct ieee_pfc *) ieee_getpfc;
    int (*)(struct net_device *, struct ieee_pfc *) ieee_setpfc;
    int (*)(struct net_device *, struct dcb_app *) ieee_getapp;
    int (*)(struct net_device *, struct dcb_app *) ieee_setapp;
    int (*)(struct net_device *, struct dcb_app *) ieee_delapp;
    int (*)(struct net_device *, struct ieee_ets *) ieee_peer_getets;
    int (*)(struct net_device *, struct ieee_pfc *) ieee_peer_getpfc;
    u8 (*)(struct net_device *) getstate;
    u8 (*)(struct net_device *, u8) setstate;
    void (*)(struct net_device *, u8 *) getpermhwaddr;
    void (*)(struct net_device *, int, u8, u8, u8, u8) setpgtccfgtx;
    void (*)(struct net_device *, int, u8) setpgbwgcfgtx;
    void (*)(struct net_device *, int, u8, u8, u8, u8) setpgtccfgrx;
    void (*)(struct net_device *, int, u8) setpgbwgcfgrx;
    void (*)(struct net_device *, int, u8 *, u8 *, u8 *, u8 *) getpgtccfgtx;
    void (*)(struct net_device *, int, u8 *) getpgbwgcfgtx;
    void (*)(struct net_device *, int, u8 *, u8 *, u8 *, u8 *) getpgtccfgrx;
    void (*)(struct net_device *, int, u8 *) getpgbwgcfgrx;
    void (*)(struct net_device *, int, u8) setpfccfg;
    void (*)(struct net_device *, int, u8 *) getpfccfg;
    u8 (*)(struct net_device *) setall;
    u8 (*)(struct net_device *, int, u8 *) getcap;
    int (*)(struct net_device *, int, u8 *) getnumtcs;
    int (*)(struct net_device *, int, u8) setnumtcs;
    u8 (*)(struct net_device *) getpfcstate;
    void (*)(struct net_device *, u8) setpfcstate;
    void (*)(struct net_device *, int, u32 *) getbcncfg;
    void (*)(struct net_device *, int, u32) setbcncfg;
    void (*)(struct net_device *, int, u8 *) getbcnrp;
    void (*)(struct net_device *, int, u8) setbcnrp;
    int (*)(struct net_device *, u8, u16, u8) setapp;
    int (*)(struct net_device *, u8, u16) getapp;
    u8 (*)(struct net_device *, int, u8 *) getfeatcfg;
    u8 (*)(struct net_device *, int, u8) setfeatcfg;
    u8 (*)(struct net_device *) getdcbx;
    u8 (*)(struct net_device *, u8) setdcbx;
    int (*)(struct net_device *, struct dcb_peer_app_info *, u16 *) peer_getappinfo;
    int (*)(struct net_device *, struct dcb_app *) peer_getapptable;
    int (*)(struct net_device *, struct cee_pg *) cee_peer_getpg;
    int (*)(struct net_device *, struct cee_pfc *) cee_peer_getpfc;
    int (*)(struct net_device *, struct dcbnl_buffer *) dcbnl_getbuffer;
    int (*)(struct net_device *, struct dcbnl_buffer *) dcbnl_setbuffer;
    int (*)(struct net_device *, u8 *, int) dcbnl_setapptrust;
    int (*)(struct net_device *, u8 *, int *) dcbnl_getapptrust;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct dcbnl_rtnl_ops {
    int (*)(struct net_device *, struct ieee_ets *) ieee_getets;
    int (*)(struct net_device *, struct ieee_ets *) ieee_setets;
    int (*)(struct net_device *, struct ieee_maxrate *) ieee_getmaxrate;
    int (*)(struct net_device *, struct ieee_maxrate *) ieee_setmaxrate;
    int (*)(struct net_device *, struct ieee_qcn *) ieee_getqcn;
    int (*)(struct net_device *, struct ieee_qcn *) ieee_setqcn;
    int (*)(struct net_device *, struct ieee_qcn_stats *) ieee_getqcnstats;
    int (*)(struct net_device *, struct ieee_pfc *) ieee_getpfc;
    int (*)(struct net_device *, struct ieee_pfc *) ieee_setpfc;
    int (*)(struct net_device *, struct dcb_app *) ieee_getapp;
    int (*)(struct net_device *, struct dcb_app *) ieee_setapp;
    int (*)(struct net_device *, struct dcb_app *) ieee_delapp;
    int (*)(struct net_device *, struct ieee_ets *) ieee_peer_getets;
    int (*)(struct net_device *, struct ieee_pfc *) ieee_peer_getpfc;
    u8 (*)(struct net_device *) getstate;
    u8 (*)(struct net_device *, u8) setstate;
    void (*)(struct net_device *, u8 *) getpermhwaddr;
    void (*)(struct net_device *, int, u8, u8, u8, u8) setpgtccfgtx;
    void (*)(struct net_device *, int, u8) setpgbwgcfgtx;
    void (*)(struct net_device *, int, u8, u8, u8, u8) setpgtccfgrx;
    void (*)(struct net_device *, int, u8) setpgbwgcfgrx;
    void (*)(struct net_device *, int, u8 *, u8 *, u8 *, u8 *) getpgtccfgtx;
    void (*)(struct net_device *, int, u8 *) getpgbwgcfgtx;
    void (*)(struct net_device *, int, u8 *, u8 *, u8 *, u8 *) getpgtccfgrx;
    void (*)(struct net_device *, int, u8 *) getpgbwgcfgrx;
    void (*)(struct net_device *, int, u8) setpfccfg;
    void (*)(struct net_device *, int, u8 *) getpfccfg;
    u8 (*)(struct net_device *) setall;
    u8 (*)(struct net_device *, int, u8 *) getcap;
    int (*)(struct net_device *, int, u8 *) getnumtcs;
    int (*)(struct net_device *, int, u8) setnumtcs;
    u8 (*)(struct net_device *) getpfcstate;
    void (*)(struct net_device *, u8) setpfcstate;
    void (*)(struct net_device *, int, u32 *) getbcncfg;
    void (*)(struct net_device *, int, u32) setbcncfg;
    void (*)(struct net_device *, int, u8 *) getbcnrp;
    void (*)(struct net_device *, int, u8) setbcnrp;
    int (*)(struct net_device *, u8, u16, u8) setapp;
    int (*)(struct net_device *, u8, u16) getapp;
    u8 (*)(struct net_device *, int, u8 *) getfeatcfg;
    u8 (*)(struct net_device *, int, u8) setfeatcfg;
    u8 (*)(struct net_device *) getdcbx;
    u8 (*)(struct net_device *, u8) setdcbx;
    int (*)(struct net_device *, struct dcb_peer_app_info *, u16 *) peer_getappinfo;
    int (*)(struct net_device *, struct dcb_app *) peer_getapptable;
    int (*)(struct net_device *, struct cee_pg *) cee_peer_getpg;
    int (*)(struct net_device *, struct cee_pfc *) cee_peer_getpfc;
    int (*)(struct net_device *, struct dcbnl_buffer *) dcbnl_getbuffer;
    int (*)(struct net_device *, struct dcbnl_buffer *) dcbnl_setbuffer;
    int (*)(struct net_device *, u8 *, int) dcbnl_setapptrust;
    int (*)(struct net_device *, u8 *, int *) dcbnl_getapptrust;
    int (*)(struct net_device *, struct dcb_app *) dcbnl_setrewr;
    int (*)(struct net_device *, struct dcb_app *) dcbnl_delrewr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct dcbnl_rtnl_ops {
    int (*)(struct net_device *, struct ieee_ets *) ieee_getets;
    int (*)(struct net_device *, struct ieee_ets *) ieee_setets;
    int (*)(struct net_device *, struct ieee_maxrate *) ieee_getmaxrate;
    int (*)(struct net_device *, struct ieee_maxrate *) ieee_setmaxrate;
    int (*)(struct net_device *, struct ieee_qcn *) ieee_getqcn;
    int (*)(struct net_device *, struct ieee_qcn *) ieee_setqcn;
    int (*)(struct net_device *, struct ieee_qcn_stats *) ieee_getqcnstats;
    int (*)(struct net_device *, struct ieee_pfc *) ieee_getpfc;
    int (*)(struct net_device *, struct ieee_pfc *) ieee_setpfc;
    int (*)(struct net_device *, struct dcb_app *) ieee_getapp;
    int (*)(struct net_device *, struct dcb_app *) ieee_setapp;
    int (*)(struct net_device *, struct dcb_app *) ieee_delapp;
    int (*)(struct net_device *, struct ieee_ets *) ieee_peer_getets;
    int (*)(struct net_device *, struct ieee_pfc *) ieee_peer_getpfc;
    u8 (*)(struct net_device *) getstate;
    u8 (*)(struct net_device *, u8) setstate;
    void (*)(struct net_device *, u8 *) getpermhwaddr;
    void (*)(struct net_device *, int, u8, u8, u8, u8) setpgtccfgtx;
    void (*)(struct net_device *, int, u8) setpgbwgcfgtx;
    void (*)(struct net_device *, int, u8, u8, u8, u8) setpgtccfgrx;
    void (*)(struct net_device *, int, u8) setpgbwgcfgrx;
    void (*)(struct net_device *, int, u8 *, u8 *, u8 *, u8 *) getpgtccfgtx;
    void (*)(struct net_device *, int, u8 *) getpgbwgcfgtx;
    void (*)(struct net_device *, int, u8 *, u8 *, u8 *, u8 *) getpgtccfgrx;
    void (*)(struct net_device *, int, u8 *) getpgbwgcfgrx;
    void (*)(struct net_device *, int, u8) setpfccfg;
    void (*)(struct net_device *, int, u8 *) getpfccfg;
    u8 (*)(struct net_device *) setall;
    u8 (*)(struct net_device *, int, u8 *) getcap;
    int (*)(struct net_device *, int, u8 *) getnumtcs;
    int (*)(struct net_device *, int, u8) setnumtcs;
    u8 (*)(struct net_device *) getpfcstate;
    void (*)(struct net_device *, u8) setpfcstate;
    void (*)(struct net_device *, int, u32 *) getbcncfg;
    void (*)(struct net_device *, int, u32) setbcncfg;
    void (*)(struct net_device *, int, u8 *) getbcnrp;
    void (*)(struct net_device *, int, u8) setbcnrp;
    int (*)(struct net_device *, u8, u16, u8) setapp;
    int (*)(struct net_device *, u8, u16) getapp;
    u8 (*)(struct net_device *, int, u8 *) getfeatcfg;
    u8 (*)(struct net_device *, int, u8) setfeatcfg;
    u8 (*)(struct net_device *) getdcbx;
    u8 (*)(struct net_device *, u8) setdcbx;
    int (*)(struct net_device *, struct dcb_peer_app_info *, u16 *) peer_getappinfo;
    int (*)(struct net_device *, struct dcb_app *) peer_getapptable;
    int (*)(struct net_device *, struct cee_pg *) cee_peer_getpg;
    int (*)(struct net_device *, struct cee_pfc *) cee_peer_getpfc;
    int (*)(struct net_device *, struct dcbnl_buffer *) dcbnl_getbuffer;
    int (*)(struct net_device *, struct dcbnl_buffer *) dcbnl_setbuffer;
    int (*)(struct net_device *, u8 *, int) dcbnl_setapptrust;
    int (*)(struct net_device *, u8 *, int *) dcbnl_getapptrust;
    int (*)(struct net_device *, struct dcb_app *) dcbnl_setrewr;
    int (*)(struct net_device *, struct dcb_app *) dcbnl_delrewr;
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
struct dcbnl_rtnl_ops {
    int (*)(struct net_device *, struct ieee_ets *) ieee_getets;
    int (*)(struct net_device *, struct ieee_ets *) ieee_setets;
    int (*)(struct net_device *, struct ieee_maxrate *) ieee_getmaxrate;
    int (*)(struct net_device *, struct ieee_maxrate *) ieee_setmaxrate;
    int (*)(struct net_device *, struct ieee_qcn *) ieee_getqcn;
    int (*)(struct net_device *, struct ieee_qcn *) ieee_setqcn;
    int (*)(struct net_device *, struct ieee_qcn_stats *) ieee_getqcnstats;
    int (*)(struct net_device *, struct ieee_pfc *) ieee_getpfc;
    int (*)(struct net_device *, struct ieee_pfc *) ieee_setpfc;
    int (*)(struct net_device *, struct dcb_app *) ieee_getapp;
    int (*)(struct net_device *, struct dcb_app *) ieee_setapp;
    int (*)(struct net_device *, struct dcb_app *) ieee_delapp;
    int (*)(struct net_device *, struct ieee_ets *) ieee_peer_getets;
    int (*)(struct net_device *, struct ieee_pfc *) ieee_peer_getpfc;
    u8 (*)(struct net_device *) getstate;
    u8 (*)(struct net_device *, u8) setstate;
    void (*)(struct net_device *, u8 *) getpermhwaddr;
    void (*)(struct net_device *, int, u8, u8, u8, u8) setpgtccfgtx;
    void (*)(struct net_device *, int, u8) setpgbwgcfgtx;
    void (*)(struct net_device *, int, u8, u8, u8, u8) setpgtccfgrx;
    void (*)(struct net_device *, int, u8) setpgbwgcfgrx;
    void (*)(struct net_device *, int, u8 *, u8 *, u8 *, u8 *) getpgtccfgtx;
    void (*)(struct net_device *, int, u8 *) getpgbwgcfgtx;
    void (*)(struct net_device *, int, u8 *, u8 *, u8 *, u8 *) getpgtccfgrx;
    void (*)(struct net_device *, int, u8 *) getpgbwgcfgrx;
    void (*)(struct net_device *, int, u8) setpfccfg;
    void (*)(struct net_device *, int, u8 *) getpfccfg;
    u8 (*)(struct net_device *) setall;
    u8 (*)(struct net_device *, int, u8 *) getcap;
    int (*)(struct net_device *, int, u8 *) getnumtcs;
    int (*)(struct net_device *, int, u8) setnumtcs;
    u8 (*)(struct net_device *) getpfcstate;
    void (*)(struct net_device *, u8) setpfcstate;
    void (*)(struct net_device *, int, u32 *) getbcncfg;
    void (*)(struct net_device *, int, u32) setbcncfg;
    void (*)(struct net_device *, int, u8 *) getbcnrp;
    void (*)(struct net_device *, int, u8) setbcnrp;
    int (*)(struct net_device *, u8, u16, u8) setapp;
    int (*)(struct net_device *, u8, u16) getapp;
    u8 (*)(struct net_device *, int, u8 *) getfeatcfg;
    u8 (*)(struct net_device *, int, u8) setfeatcfg;
    u8 (*)(struct net_device *) getdcbx;
    u8 (*)(struct net_device *, u8) setdcbx;
    int (*)(struct net_device *, struct dcb_peer_app_info *, u16 *) peer_getappinfo;
    int (*)(struct net_device *, struct dcb_app *) peer_getapptable;
    int (*)(struct net_device *, struct cee_pg *) cee_peer_getpg;
    int (*)(struct net_device *, struct cee_pfc *) cee_peer_getpfc;
    int (*)(struct net_device *, struct dcbnl_buffer *) dcbnl_getbuffer;
    int (*)(struct net_device *, struct dcbnl_buffer *) dcbnl_setbuffer;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct dcbnl_rtnl_ops {
    int (*)(struct net_device *, struct ieee_ets *) ieee_getets;
    int (*)(struct net_device *, struct ieee_ets *) ieee_setets;
    int (*)(struct net_device *, struct ieee_maxrate *) ieee_getmaxrate;
    int (*)(struct net_device *, struct ieee_maxrate *) ieee_setmaxrate;
    int (*)(struct net_device *, struct ieee_qcn *) ieee_getqcn;
    int (*)(struct net_device *, struct ieee_qcn *) ieee_setqcn;
    int (*)(struct net_device *, struct ieee_qcn_stats *) ieee_getqcnstats;
    int (*)(struct net_device *, struct ieee_pfc *) ieee_getpfc;
    int (*)(struct net_device *, struct ieee_pfc *) ieee_setpfc;
    int (*)(struct net_device *, struct dcb_app *) ieee_getapp;
    int (*)(struct net_device *, struct dcb_app *) ieee_setapp;
    int (*)(struct net_device *, struct dcb_app *) ieee_delapp;
    int (*)(struct net_device *, struct ieee_ets *) ieee_peer_getets;
    int (*)(struct net_device *, struct ieee_pfc *) ieee_peer_getpfc;
    u8 (*)(struct net_device *) getstate;
    u8 (*)(struct net_device *, u8) setstate;
    void (*)(struct net_device *, u8 *) getpermhwaddr;
    void (*)(struct net_device *, int, u8, u8, u8, u8) setpgtccfgtx;
    void (*)(struct net_device *, int, u8) setpgbwgcfgtx;
    void (*)(struct net_device *, int, u8, u8, u8, u8) setpgtccfgrx;
    void (*)(struct net_device *, int, u8) setpgbwgcfgrx;
    void (*)(struct net_device *, int, u8 *, u8 *, u8 *, u8 *) getpgtccfgtx;
    void (*)(struct net_device *, int, u8 *) getpgbwgcfgtx;
    void (*)(struct net_device *, int, u8 *, u8 *, u8 *, u8 *) getpgtccfgrx;
    void (*)(struct net_device *, int, u8 *) getpgbwgcfgrx;
    void (*)(struct net_device *, int, u8) setpfccfg;
    void (*)(struct net_device *, int, u8 *) getpfccfg;
    u8 (*)(struct net_device *) setall;
    u8 (*)(struct net_device *, int, u8 *) getcap;
    int (*)(struct net_device *, int, u8 *) getnumtcs;
    int (*)(struct net_device *, int, u8) setnumtcs;
    u8 (*)(struct net_device *) getpfcstate;
    void (*)(struct net_device *, u8) setpfcstate;
    void (*)(struct net_device *, int, u32 *) getbcncfg;
    void (*)(struct net_device *, int, u32) setbcncfg;
    void (*)(struct net_device *, int, u8 *) getbcnrp;
    void (*)(struct net_device *, int, u8) setbcnrp;
    int (*)(struct net_device *, u8, u16, u8) setapp;
    int (*)(struct net_device *, u8, u16) getapp;
    u8 (*)(struct net_device *, int, u8 *) getfeatcfg;
    u8 (*)(struct net_device *, int, u8) setfeatcfg;
    u8 (*)(struct net_device *) getdcbx;
    u8 (*)(struct net_device *, u8) setdcbx;
    int (*)(struct net_device *, struct dcb_peer_app_info *, u16 *) peer_getappinfo;
    int (*)(struct net_device *, struct dcb_app *) peer_getapptable;
    int (*)(struct net_device *, struct cee_pg *) cee_peer_getpg;
    int (*)(struct net_device *, struct cee_pfc *) cee_peer_getpfc;
    int (*)(struct net_device *, struct dcbnl_buffer *) dcbnl_getbuffer;
    int (*)(struct net_device *, struct dcbnl_buffer *) dcbnl_setbuffer;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct dcbnl_rtnl_ops {
    int (*)(struct net_device *, struct ieee_ets *) ieee_getets;
    int (*)(struct net_device *, struct ieee_ets *) ieee_setets;
    int (*)(struct net_device *, struct ieee_maxrate *) ieee_getmaxrate;
    int (*)(struct net_device *, struct ieee_maxrate *) ieee_setmaxrate;
    int (*)(struct net_device *, struct ieee_qcn *) ieee_getqcn;
    int (*)(struct net_device *, struct ieee_qcn *) ieee_setqcn;
    int (*)(struct net_device *, struct ieee_qcn_stats *) ieee_getqcnstats;
    int (*)(struct net_device *, struct ieee_pfc *) ieee_getpfc;
    int (*)(struct net_device *, struct ieee_pfc *) ieee_setpfc;
    int (*)(struct net_device *, struct dcb_app *) ieee_getapp;
    int (*)(struct net_device *, struct dcb_app *) ieee_setapp;
    int (*)(struct net_device *, struct dcb_app *) ieee_delapp;
    int (*)(struct net_device *, struct ieee_ets *) ieee_peer_getets;
    int (*)(struct net_device *, struct ieee_pfc *) ieee_peer_getpfc;
    u8 (*)(struct net_device *) getstate;
    u8 (*)(struct net_device *, u8) setstate;
    void (*)(struct net_device *, u8 *) getpermhwaddr;
    void (*)(struct net_device *, int, u8, u8, u8, u8) setpgtccfgtx;
    void (*)(struct net_device *, int, u8) setpgbwgcfgtx;
    void (*)(struct net_device *, int, u8, u8, u8, u8) setpgtccfgrx;
    void (*)(struct net_device *, int, u8) setpgbwgcfgrx;
    void (*)(struct net_device *, int, u8 *, u8 *, u8 *, u8 *) getpgtccfgtx;
    void (*)(struct net_device *, int, u8 *) getpgbwgcfgtx;
    void (*)(struct net_device *, int, u8 *, u8 *, u8 *, u8 *) getpgtccfgrx;
    void (*)(struct net_device *, int, u8 *) getpgbwgcfgrx;
    void (*)(struct net_device *, int, u8) setpfccfg;
    void (*)(struct net_device *, int, u8 *) getpfccfg;
    u8 (*)(struct net_device *) setall;
    u8 (*)(struct net_device *, int, u8 *) getcap;
    int (*)(struct net_device *, int, u8 *) getnumtcs;
    int (*)(struct net_device *, int, u8) setnumtcs;
    u8 (*)(struct net_device *) getpfcstate;
    void (*)(struct net_device *, u8) setpfcstate;
    void (*)(struct net_device *, int, u32 *) getbcncfg;
    void (*)(struct net_device *, int, u32) setbcncfg;
    void (*)(struct net_device *, int, u8 *) getbcnrp;
    void (*)(struct net_device *, int, u8) setbcnrp;
    int (*)(struct net_device *, u8, u16, u8) setapp;
    int (*)(struct net_device *, u8, u16) getapp;
    u8 (*)(struct net_device *, int, u8 *) getfeatcfg;
    u8 (*)(struct net_device *, int, u8) setfeatcfg;
    u8 (*)(struct net_device *) getdcbx;
    u8 (*)(struct net_device *, u8) setdcbx;
    int (*)(struct net_device *, struct dcb_peer_app_info *, u16 *) peer_getappinfo;
    int (*)(struct net_device *, struct dcb_app *) peer_getapptable;
    int (*)(struct net_device *, struct cee_pg *) cee_peer_getpg;
    int (*)(struct net_device *, struct cee_pfc *) cee_peer_getpfc;
    int (*)(struct net_device *, struct dcbnl_buffer *) dcbnl_getbuffer;
    int (*)(struct net_device *, struct dcbnl_buffer *) dcbnl_setbuffer;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct dcbnl_rtnl_ops {
    int (*)(struct net_device *, struct ieee_ets *) ieee_getets;
    int (*)(struct net_device *, struct ieee_ets *) ieee_setets;
    int (*)(struct net_device *, struct ieee_maxrate *) ieee_getmaxrate;
    int (*)(struct net_device *, struct ieee_maxrate *) ieee_setmaxrate;
    int (*)(struct net_device *, struct ieee_qcn *) ieee_getqcn;
    int (*)(struct net_device *, struct ieee_qcn *) ieee_setqcn;
    int (*)(struct net_device *, struct ieee_qcn_stats *) ieee_getqcnstats;
    int (*)(struct net_device *, struct ieee_pfc *) ieee_getpfc;
    int (*)(struct net_device *, struct ieee_pfc *) ieee_setpfc;
    int (*)(struct net_device *, struct dcb_app *) ieee_getapp;
    int (*)(struct net_device *, struct dcb_app *) ieee_setapp;
    int (*)(struct net_device *, struct dcb_app *) ieee_delapp;
    int (*)(struct net_device *, struct ieee_ets *) ieee_peer_getets;
    int (*)(struct net_device *, struct ieee_pfc *) ieee_peer_getpfc;
    u8 (*)(struct net_device *) getstate;
    u8 (*)(struct net_device *, u8) setstate;
    void (*)(struct net_device *, u8 *) getpermhwaddr;
    void (*)(struct net_device *, int, u8, u8, u8, u8) setpgtccfgtx;
    void (*)(struct net_device *, int, u8) setpgbwgcfgtx;
    void (*)(struct net_device *, int, u8, u8, u8, u8) setpgtccfgrx;
    void (*)(struct net_device *, int, u8) setpgbwgcfgrx;
    void (*)(struct net_device *, int, u8 *, u8 *, u8 *, u8 *) getpgtccfgtx;
    void (*)(struct net_device *, int, u8 *) getpgbwgcfgtx;
    void (*)(struct net_device *, int, u8 *, u8 *, u8 *, u8 *) getpgtccfgrx;
    void (*)(struct net_device *, int, u8 *) getpgbwgcfgrx;
    void (*)(struct net_device *, int, u8) setpfccfg;
    void (*)(struct net_device *, int, u8 *) getpfccfg;
    u8 (*)(struct net_device *) setall;
    u8 (*)(struct net_device *, int, u8 *) getcap;
    int (*)(struct net_device *, int, u8 *) getnumtcs;
    int (*)(struct net_device *, int, u8) setnumtcs;
    u8 (*)(struct net_device *) getpfcstate;
    void (*)(struct net_device *, u8) setpfcstate;
    void (*)(struct net_device *, int, u32 *) getbcncfg;
    void (*)(struct net_device *, int, u32) setbcncfg;
    void (*)(struct net_device *, int, u8 *) getbcnrp;
    void (*)(struct net_device *, int, u8) setbcnrp;
    int (*)(struct net_device *, u8, u16, u8) setapp;
    int (*)(struct net_device *, u8, u16) getapp;
    u8 (*)(struct net_device *, int, u8 *) getfeatcfg;
    u8 (*)(struct net_device *, int, u8) setfeatcfg;
    u8 (*)(struct net_device *) getdcbx;
    u8 (*)(struct net_device *, u8) setdcbx;
    int (*)(struct net_device *, struct dcb_peer_app_info *, u16 *) peer_getappinfo;
    int (*)(struct net_device *, struct dcb_app *) peer_getapptable;
    int (*)(struct net_device *, struct cee_pg *) cee_peer_getpg;
    int (*)(struct net_device *, struct cee_pfc *) cee_peer_getpfc;
    int (*)(struct net_device *, struct dcbnl_buffer *) dcbnl_getbuffer;
    int (*)(struct net_device *, struct dcbnl_buffer *) dcbnl_setbuffer;
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
struct dcbnl_rtnl_ops {
    int (*)(struct net_device *, struct ieee_ets *) ieee_getets;
    int (*)(struct net_device *, struct ieee_ets *) ieee_setets;
    int (*)(struct net_device *, struct ieee_maxrate *) ieee_getmaxrate;
    int (*)(struct net_device *, struct ieee_maxrate *) ieee_setmaxrate;
    int (*)(struct net_device *, struct ieee_qcn *) ieee_getqcn;
    int (*)(struct net_device *, struct ieee_qcn *) ieee_setqcn;
    int (*)(struct net_device *, struct ieee_qcn_stats *) ieee_getqcnstats;
    int (*)(struct net_device *, struct ieee_pfc *) ieee_getpfc;
    int (*)(struct net_device *, struct ieee_pfc *) ieee_setpfc;
    int (*)(struct net_device *, struct dcb_app *) ieee_getapp;
    int (*)(struct net_device *, struct dcb_app *) ieee_setapp;
    int (*)(struct net_device *, struct dcb_app *) ieee_delapp;
    int (*)(struct net_device *, struct ieee_ets *) ieee_peer_getets;
    int (*)(struct net_device *, struct ieee_pfc *) ieee_peer_getpfc;
    u8 (*)(struct net_device *) getstate;
    u8 (*)(struct net_device *, u8) setstate;
    void (*)(struct net_device *, u8 *) getpermhwaddr;
    void (*)(struct net_device *, int, u8, u8, u8, u8) setpgtccfgtx;
    void (*)(struct net_device *, int, u8) setpgbwgcfgtx;
    void (*)(struct net_device *, int, u8, u8, u8, u8) setpgtccfgrx;
    void (*)(struct net_device *, int, u8) setpgbwgcfgrx;
    void (*)(struct net_device *, int, u8 *, u8 *, u8 *, u8 *) getpgtccfgtx;
    void (*)(struct net_device *, int, u8 *) getpgbwgcfgtx;
    void (*)(struct net_device *, int, u8 *, u8 *, u8 *, u8 *) getpgtccfgrx;
    void (*)(struct net_device *, int, u8 *) getpgbwgcfgrx;
    void (*)(struct net_device *, int, u8) setpfccfg;
    void (*)(struct net_device *, int, u8 *) getpfccfg;
    u8 (*)(struct net_device *) setall;
    u8 (*)(struct net_device *, int, u8 *) getcap;
    int (*)(struct net_device *, int, u8 *) getnumtcs;
    int (*)(struct net_device *, int, u8) setnumtcs;
    u8 (*)(struct net_device *) getpfcstate;
    void (*)(struct net_device *, u8) setpfcstate;
    void (*)(struct net_device *, int, u32 *) getbcncfg;
    void (*)(struct net_device *, int, u32) setbcncfg;
    void (*)(struct net_device *, int, u8 *) getbcnrp;
    void (*)(struct net_device *, int, u8) setbcnrp;
    int (*)(struct net_device *, u8, u16, u8) setapp;
    int (*)(struct net_device *, u8, u16) getapp;
    u8 (*)(struct net_device *, int, u8 *) getfeatcfg;
    u8 (*)(struct net_device *, int, u8) setfeatcfg;
    u8 (*)(struct net_device *) getdcbx;
    u8 (*)(struct net_device *, u8) setdcbx;
    int (*)(struct net_device *, struct dcb_peer_app_info *, u16 *) peer_getappinfo;
    int (*)(struct net_device *, struct dcb_app *) peer_getapptable;
    int (*)(struct net_device *, struct cee_pg *) cee_peer_getpg;
    int (*)(struct net_device *, struct cee_pfc *) cee_peer_getpfc;
    int (*)(struct net_device *, struct dcbnl_buffer *) dcbnl_getbuffer;
    int (*)(struct net_device *, struct dcbnl_buffer *) dcbnl_setbuffer;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct dcbnl_rtnl_ops {
    int (*)(struct net_device *, struct ieee_ets *) ieee_getets;
    int (*)(struct net_device *, struct ieee_ets *) ieee_setets;
    int (*)(struct net_device *, struct ieee_maxrate *) ieee_getmaxrate;
    int (*)(struct net_device *, struct ieee_maxrate *) ieee_setmaxrate;
    int (*)(struct net_device *, struct ieee_qcn *) ieee_getqcn;
    int (*)(struct net_device *, struct ieee_qcn *) ieee_setqcn;
    int (*)(struct net_device *, struct ieee_qcn_stats *) ieee_getqcnstats;
    int (*)(struct net_device *, struct ieee_pfc *) ieee_getpfc;
    int (*)(struct net_device *, struct ieee_pfc *) ieee_setpfc;
    int (*)(struct net_device *, struct dcb_app *) ieee_getapp;
    int (*)(struct net_device *, struct dcb_app *) ieee_setapp;
    int (*)(struct net_device *, struct dcb_app *) ieee_delapp;
    int (*)(struct net_device *, struct ieee_ets *) ieee_peer_getets;
    int (*)(struct net_device *, struct ieee_pfc *) ieee_peer_getpfc;
    u8 (*)(struct net_device *) getstate;
    u8 (*)(struct net_device *, u8) setstate;
    void (*)(struct net_device *, u8 *) getpermhwaddr;
    void (*)(struct net_device *, int, u8, u8, u8, u8) setpgtccfgtx;
    void (*)(struct net_device *, int, u8) setpgbwgcfgtx;
    void (*)(struct net_device *, int, u8, u8, u8, u8) setpgtccfgrx;
    void (*)(struct net_device *, int, u8) setpgbwgcfgrx;
    void (*)(struct net_device *, int, u8 *, u8 *, u8 *, u8 *) getpgtccfgtx;
    void (*)(struct net_device *, int, u8 *) getpgbwgcfgtx;
    void (*)(struct net_device *, int, u8 *, u8 *, u8 *, u8 *) getpgtccfgrx;
    void (*)(struct net_device *, int, u8 *) getpgbwgcfgrx;
    void (*)(struct net_device *, int, u8) setpfccfg;
    void (*)(struct net_device *, int, u8 *) getpfccfg;
    u8 (*)(struct net_device *) setall;
    u8 (*)(struct net_device *, int, u8 *) getcap;
    int (*)(struct net_device *, int, u8 *) getnumtcs;
    int (*)(struct net_device *, int, u8) setnumtcs;
    u8 (*)(struct net_device *) getpfcstate;
    void (*)(struct net_device *, u8) setpfcstate;
    void (*)(struct net_device *, int, u32 *) getbcncfg;
    void (*)(struct net_device *, int, u32) setbcncfg;
    void (*)(struct net_device *, int, u8 *) getbcnrp;
    void (*)(struct net_device *, int, u8) setbcnrp;
    int (*)(struct net_device *, u8, u16, u8) setapp;
    int (*)(struct net_device *, u8, u16) getapp;
    u8 (*)(struct net_device *, int, u8 *) getfeatcfg;
    u8 (*)(struct net_device *, int, u8) setfeatcfg;
    u8 (*)(struct net_device *) getdcbx;
    u8 (*)(struct net_device *, u8) setdcbx;
    int (*)(struct net_device *, struct dcb_peer_app_info *, u16 *) peer_getappinfo;
    int (*)(struct net_device *, struct dcb_app *) peer_getapptable;
    int (*)(struct net_device *, struct cee_pg *) cee_peer_getpg;
    int (*)(struct net_device *, struct cee_pfc *) cee_peer_getpfc;
    int (*)(struct net_device *, struct dcbnl_buffer *) dcbnl_getbuffer;
    int (*)(struct net_device *, struct dcbnl_buffer *) dcbnl_setbuffer;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct dcbnl_rtnl_ops {
    int (*)(struct net_device *, struct ieee_ets *) ieee_getets;
    int (*)(struct net_device *, struct ieee_ets *) ieee_setets;
    int (*)(struct net_device *, struct ieee_maxrate *) ieee_getmaxrate;
    int (*)(struct net_device *, struct ieee_maxrate *) ieee_setmaxrate;
    int (*)(struct net_device *, struct ieee_qcn *) ieee_getqcn;
    int (*)(struct net_device *, struct ieee_qcn *) ieee_setqcn;
    int (*)(struct net_device *, struct ieee_qcn_stats *) ieee_getqcnstats;
    int (*)(struct net_device *, struct ieee_pfc *) ieee_getpfc;
    int (*)(struct net_device *, struct ieee_pfc *) ieee_setpfc;
    int (*)(struct net_device *, struct dcb_app *) ieee_getapp;
    int (*)(struct net_device *, struct dcb_app *) ieee_setapp;
    int (*)(struct net_device *, struct dcb_app *) ieee_delapp;
    int (*)(struct net_device *, struct ieee_ets *) ieee_peer_getets;
    int (*)(struct net_device *, struct ieee_pfc *) ieee_peer_getpfc;
    u8 (*)(struct net_device *) getstate;
    u8 (*)(struct net_device *, u8) setstate;
    void (*)(struct net_device *, u8 *) getpermhwaddr;
    void (*)(struct net_device *, int, u8, u8, u8, u8) setpgtccfgtx;
    void (*)(struct net_device *, int, u8) setpgbwgcfgtx;
    void (*)(struct net_device *, int, u8, u8, u8, u8) setpgtccfgrx;
    void (*)(struct net_device *, int, u8) setpgbwgcfgrx;
    void (*)(struct net_device *, int, u8 *, u8 *, u8 *, u8 *) getpgtccfgtx;
    void (*)(struct net_device *, int, u8 *) getpgbwgcfgtx;
    void (*)(struct net_device *, int, u8 *, u8 *, u8 *, u8 *) getpgtccfgrx;
    void (*)(struct net_device *, int, u8 *) getpgbwgcfgrx;
    void (*)(struct net_device *, int, u8) setpfccfg;
    void (*)(struct net_device *, int, u8 *) getpfccfg;
    u8 (*)(struct net_device *) setall;
    u8 (*)(struct net_device *, int, u8 *) getcap;
    int (*)(struct net_device *, int, u8 *) getnumtcs;
    int (*)(struct net_device *, int, u8) setnumtcs;
    u8 (*)(struct net_device *) getpfcstate;
    void (*)(struct net_device *, u8) setpfcstate;
    void (*)(struct net_device *, int, u32 *) getbcncfg;
    void (*)(struct net_device *, int, u32) setbcncfg;
    void (*)(struct net_device *, int, u8 *) getbcnrp;
    void (*)(struct net_device *, int, u8) setbcnrp;
    int (*)(struct net_device *, u8, u16, u8) setapp;
    int (*)(struct net_device *, u8, u16) getapp;
    u8 (*)(struct net_device *, int, u8 *) getfeatcfg;
    u8 (*)(struct net_device *, int, u8) setfeatcfg;
    u8 (*)(struct net_device *) getdcbx;
    u8 (*)(struct net_device *, u8) setdcbx;
    int (*)(struct net_device *, struct dcb_peer_app_info *, u16 *) peer_getappinfo;
    int (*)(struct net_device *, struct dcb_app *) peer_getapptable;
    int (*)(struct net_device *, struct cee_pg *) cee_peer_getpg;
    int (*)(struct net_device *, struct cee_pfc *) cee_peer_getpfc;
    int (*)(struct net_device *, struct dcbnl_buffer *) dcbnl_getbuffer;
    int (*)(struct net_device *, struct dcbnl_buffer *) dcbnl_setbuffer;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct dcbnl_rtnl_ops {
    int (*)(struct net_device *, struct ieee_ets *) ieee_getets;
    int (*)(struct net_device *, struct ieee_ets *) ieee_setets;
    int (*)(struct net_device *, struct ieee_maxrate *) ieee_getmaxrate;
    int (*)(struct net_device *, struct ieee_maxrate *) ieee_setmaxrate;
    int (*)(struct net_device *, struct ieee_qcn *) ieee_getqcn;
    int (*)(struct net_device *, struct ieee_qcn *) ieee_setqcn;
    int (*)(struct net_device *, struct ieee_qcn_stats *) ieee_getqcnstats;
    int (*)(struct net_device *, struct ieee_pfc *) ieee_getpfc;
    int (*)(struct net_device *, struct ieee_pfc *) ieee_setpfc;
    int (*)(struct net_device *, struct dcb_app *) ieee_getapp;
    int (*)(struct net_device *, struct dcb_app *) ieee_setapp;
    int (*)(struct net_device *, struct dcb_app *) ieee_delapp;
    int (*)(struct net_device *, struct ieee_ets *) ieee_peer_getets;
    int (*)(struct net_device *, struct ieee_pfc *) ieee_peer_getpfc;
    u8 (*)(struct net_device *) getstate;
    u8 (*)(struct net_device *, u8) setstate;
    void (*)(struct net_device *, u8 *) getpermhwaddr;
    void (*)(struct net_device *, int, u8, u8, u8, u8) setpgtccfgtx;
    void (*)(struct net_device *, int, u8) setpgbwgcfgtx;
    void (*)(struct net_device *, int, u8, u8, u8, u8) setpgtccfgrx;
    void (*)(struct net_device *, int, u8) setpgbwgcfgrx;
    void (*)(struct net_device *, int, u8 *, u8 *, u8 *, u8 *) getpgtccfgtx;
    void (*)(struct net_device *, int, u8 *) getpgbwgcfgtx;
    void (*)(struct net_device *, int, u8 *, u8 *, u8 *, u8 *) getpgtccfgrx;
    void (*)(struct net_device *, int, u8 *) getpgbwgcfgrx;
    void (*)(struct net_device *, int, u8) setpfccfg;
    void (*)(struct net_device *, int, u8 *) getpfccfg;
    u8 (*)(struct net_device *) setall;
    u8 (*)(struct net_device *, int, u8 *) getcap;
    int (*)(struct net_device *, int, u8 *) getnumtcs;
    int (*)(struct net_device *, int, u8) setnumtcs;
    u8 (*)(struct net_device *) getpfcstate;
    void (*)(struct net_device *, u8) setpfcstate;
    void (*)(struct net_device *, int, u32 *) getbcncfg;
    void (*)(struct net_device *, int, u32) setbcncfg;
    void (*)(struct net_device *, int, u8 *) getbcnrp;
    void (*)(struct net_device *, int, u8) setbcnrp;
    int (*)(struct net_device *, u8, u16, u8) setapp;
    int (*)(struct net_device *, u8, u16) getapp;
    u8 (*)(struct net_device *, int, u8 *) getfeatcfg;
    u8 (*)(struct net_device *, int, u8) setfeatcfg;
    u8 (*)(struct net_device *) getdcbx;
    u8 (*)(struct net_device *, u8) setdcbx;
    int (*)(struct net_device *, struct dcb_peer_app_info *, u16 *) peer_getappinfo;
    int (*)(struct net_device *, struct dcb_app *) peer_getapptable;
    int (*)(struct net_device *, struct cee_pg *) cee_peer_getpg;
    int (*)(struct net_device *, struct cee_pfc *) cee_peer_getpfc;
    int (*)(struct net_device *, struct dcbnl_buffer *) dcbnl_getbuffer;
    int (*)(struct net_device *, struct dcbnl_buffer *) dcbnl_setbuffer;
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
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct net_device *, struct dcbnl_buffer *) dcbnl_getbuffer</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct net_device *, struct dcbnl_buffer *) dcbnl_setbuffer</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct net_device *, u8 *, int) dcbnl_setapptrust</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct net_device *, u8 *, int *) dcbnl_getapptrust</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct net_device *, struct dcb_app *) dcbnl_setrewr</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct net_device *, struct dcb_app *) dcbnl_delrewr</code>
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
