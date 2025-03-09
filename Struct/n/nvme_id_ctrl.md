# Struct: <code>nvme_id_ctrl</code>

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
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct nvme_id_ctrl {
    __le16 vid;
    __le16 ssvid;
    char[20] sn;
    char[40] mn;
    char[8] fr;
    __u8 rab;
    __u8[3] ieee;
    __u8 cmic;
    __u8 mdts;
    __le16 cntlid;
    __le32 ver;
    __le32 rtd3r;
    __le32 rtd3e;
    __le32 oaes;
    __le32 ctratt;
    __u8[28] rsvd100;
    __le16 crdt1;
    __le16 crdt2;
    __le16 crdt3;
    __u8[122] rsvd134;
    __le16 oacs;
    __u8 acl;
    __u8 aerl;
    __u8 frmw;
    __u8 lpa;
    __u8 elpe;
    __u8 npss;
    __u8 avscc;
    __u8 apsta;
    __le16 wctemp;
    __le16 cctemp;
    __le16 mtfa;
    __le32 hmpre;
    __le32 hmmin;
    __u8[16] tnvmcap;
    __u8[16] unvmcap;
    __le32 rpmbs;
    __le16 edstt;
    __u8 dsto;
    __u8 fwug;
    __le16 kas;
    __le16 hctma;
    __le16 mntmt;
    __le16 mxtmt;
    __le32 sanicap;
    __le32 hmminds;
    __le16 hmmaxd;
    __u8[4] rsvd338;
    __u8 anatt;
    __u8 anacap;
    __le32 anagrpmax;
    __le32 nanagrpid;
    __u8[160] rsvd352;
    __u8 sqes;
    __u8 cqes;
    __le16 maxcmd;
    __le32 nn;
    __le16 oncs;
    __le16 fuses;
    __u8 fna;
    __u8 vwc;
    __le16 awun;
    __le16 awupf;
    __u8 nvscc;
    __u8 nwpc;
    __le16 acwu;
    __u8[2] rsvd534;
    __le32 sgls;
    __le32 mnan;
    __u8[224] rsvd544;
    char[256] subnqn;
    __u8[768] rsvd1024;
    __le32 ioccsz;
    __le32 iorcsz;
    __le16 icdoff;
    __u8 ctrattr;
    __u8 msdbd;
    __u8[244] rsvd1804;
    struct nvme_id_power_state[32] psd;
    __u8[1024] vs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct nvme_id_ctrl {
    __le16 vid;
    __le16 ssvid;
    char[20] sn;
    char[40] mn;
    char[8] fr;
    __u8 rab;
    __u8[3] ieee;
    __u8 cmic;
    __u8 mdts;
    __le16 cntlid;
    __le32 ver;
    __le32 rtd3r;
    __le32 rtd3e;
    __le32 oaes;
    __le32 ctratt;
    __u8[28] rsvd100;
    __le16 crdt1;
    __le16 crdt2;
    __le16 crdt3;
    __u8[122] rsvd134;
    __le16 oacs;
    __u8 acl;
    __u8 aerl;
    __u8 frmw;
    __u8 lpa;
    __u8 elpe;
    __u8 npss;
    __u8 avscc;
    __u8 apsta;
    __le16 wctemp;
    __le16 cctemp;
    __le16 mtfa;
    __le32 hmpre;
    __le32 hmmin;
    __u8[16] tnvmcap;
    __u8[16] unvmcap;
    __le32 rpmbs;
    __le16 edstt;
    __u8 dsto;
    __u8 fwug;
    __le16 kas;
    __le16 hctma;
    __le16 mntmt;
    __le16 mxtmt;
    __le32 sanicap;
    __le32 hmminds;
    __le16 hmmaxd;
    __u8[4] rsvd338;
    __u8 anatt;
    __u8 anacap;
    __le32 anagrpmax;
    __le32 nanagrpid;
    __u8[160] rsvd352;
    __u8 sqes;
    __u8 cqes;
    __le16 maxcmd;
    __le32 nn;
    __le16 oncs;
    __le16 fuses;
    __u8 fna;
    __u8 vwc;
    __le16 awun;
    __le16 awupf;
    __u8 nvscc;
    __u8 nwpc;
    __le16 acwu;
    __u8[2] rsvd534;
    __le32 sgls;
    __le32 mnan;
    __u8[224] rsvd544;
    char[256] subnqn;
    __u8[768] rsvd1024;
    __le32 ioccsz;
    __le32 iorcsz;
    __le16 icdoff;
    __u8 ctrattr;
    __u8 msdbd;
    __u8[244] rsvd1804;
    struct nvme_id_power_state[32] psd;
    __u8[1024] vs;
}
```
</details>
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➕</summary>

```c
struct nvme_id_ctrl {
    __le16 vid;
    __le16 ssvid;
    char[20] sn;
    char[40] mn;
    char[8] fr;
    __u8 rab;
    __u8[3] ieee;
    __u8 cmic;
    __u8 mdts;
    __le16 cntlid;
    __le32 ver;
    __le32 rtd3r;
    __le32 rtd3e;
    __le32 oaes;
    __le32 ctratt;
    __u8[28] rsvd100;
    __le16 crdt1;
    __le16 crdt2;
    __le16 crdt3;
    __u8[122] rsvd134;
    __le16 oacs;
    __u8 acl;
    __u8 aerl;
    __u8 frmw;
    __u8 lpa;
    __u8 elpe;
    __u8 npss;
    __u8 avscc;
    __u8 apsta;
    __le16 wctemp;
    __le16 cctemp;
    __le16 mtfa;
    __le32 hmpre;
    __le32 hmmin;
    __u8[16] tnvmcap;
    __u8[16] unvmcap;
    __le32 rpmbs;
    __le16 edstt;
    __u8 dsto;
    __u8 fwug;
    __le16 kas;
    __le16 hctma;
    __le16 mntmt;
    __le16 mxtmt;
    __le32 sanicap;
    __le32 hmminds;
    __le16 hmmaxd;
    __u8[4] rsvd338;
    __u8 anatt;
    __u8 anacap;
    __le32 anagrpmax;
    __le32 nanagrpid;
    __u8[160] rsvd352;
    __u8 sqes;
    __u8 cqes;
    __le16 maxcmd;
    __le32 nn;
    __le16 oncs;
    __le16 fuses;
    __u8 fna;
    __u8 vwc;
    __le16 awun;
    __le16 awupf;
    __u8 nvscc;
    __u8 nwpc;
    __le16 acwu;
    __u8[2] rsvd534;
    __le32 sgls;
    __le32 mnan;
    __u8[224] rsvd544;
    char[256] subnqn;
    __u8[768] rsvd1024;
    __le32 ioccsz;
    __le32 iorcsz;
    __le16 icdoff;
    __u8 ctrattr;
    __u8 msdbd;
    __u8[244] rsvd1804;
    struct nvme_id_power_state[32] psd;
    __u8[1024] vs;
}
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➕</summary>

```c
struct nvme_id_ctrl {
    __le16 vid;
    __le16 ssvid;
    char[20] sn;
    char[40] mn;
    char[8] fr;
    __u8 rab;
    __u8[3] ieee;
    __u8 cmic;
    __u8 mdts;
    __le16 cntlid;
    __le32 ver;
    __le32 rtd3r;
    __le32 rtd3e;
    __le32 oaes;
    __le32 ctratt;
    __u8[28] rsvd100;
    __le16 crdt1;
    __le16 crdt2;
    __le16 crdt3;
    __u8[122] rsvd134;
    __le16 oacs;
    __u8 acl;
    __u8 aerl;
    __u8 frmw;
    __u8 lpa;
    __u8 elpe;
    __u8 npss;
    __u8 avscc;
    __u8 apsta;
    __le16 wctemp;
    __le16 cctemp;
    __le16 mtfa;
    __le32 hmpre;
    __le32 hmmin;
    __u8[16] tnvmcap;
    __u8[16] unvmcap;
    __le32 rpmbs;
    __le16 edstt;
    __u8 dsto;
    __u8 fwug;
    __le16 kas;
    __le16 hctma;
    __le16 mntmt;
    __le16 mxtmt;
    __le32 sanicap;
    __le32 hmminds;
    __le16 hmmaxd;
    __u8[4] rsvd338;
    __u8 anatt;
    __u8 anacap;
    __le32 anagrpmax;
    __le32 nanagrpid;
    __u8[160] rsvd352;
    __u8 sqes;
    __u8 cqes;
    __le16 maxcmd;
    __le32 nn;
    __le16 oncs;
    __le16 fuses;
    __u8 fna;
    __u8 vwc;
    __le16 awun;
    __le16 awupf;
    __u8 nvscc;
    __u8 nwpc;
    __le16 acwu;
    __u8[2] rsvd534;
    __le32 sgls;
    __le32 mnan;
    __u8[224] rsvd544;
    char[256] subnqn;
    __u8[768] rsvd1024;
    __le32 ioccsz;
    __le32 iorcsz;
    __le16 icdoff;
    __u8 ctrattr;
    __u8 msdbd;
    __u8[244] rsvd1804;
    struct nvme_id_power_state[32] psd;
    __u8[1024] vs;
}
```
</details>
</li>
</ul>
