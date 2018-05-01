Honeypots Deployed
==================

- Dionaea
- Cowrie
- Snort

Issues Encountered
==================

- I couldn't manage to get my Cowrie VM to expose itself to
  connections. Very few ports were open on it, and no attacks were
  made on it. My other VMs worked, though, which was odd. I also
  reinstaled the Cowrie honeypot several times, double-checking all of
  the VM settings, to make sure that they were fine. No luck.
- It was tough to understand what the honeypots actually were. The
  documentation on them was a little scarce, and sometimes the links
  to their descriptions were straight up broken.

Attack Summary
==============

- Dionaea : 1902 attacks. No reported malware.
- Snort : 70 attacks. All of them registered some sort of signature,
  most of which were IPs of poor repute, or IPs that were known to be
  compromised. None of the attacks reported malware.

Unresolved Issues
=================

I didn't see any payloads for Dionaea, even though Dionaea is capable
of capturing them. However, in my very short time running Snort, I
managed to capture 70 payloads. All of the attacks on snort were
payloads.
