---
title: "Deoxys-based Authenticated Encryption"
abbrev: "Deoxys-AE"
docname: draft-irtf-cfrg-deoxys-ae-latest
category: info

ipr: trust200902
area: General
workgroup: Crypto Forum
keyword: Internet-Draft, Deoxys, Authenticated Encryption

stand_alone: yes
coding: UTF-8
pi: [toc, sortrefs, symrefs]

author:
 -
    ins: T. Peyrin
    name: Thomas Peyrin
    organization: Nanyang Technological University, Singapore
    email: thomas.peyrin@gmail.com

normative:
  RFC2119:

informative:



--- abstract

This document specifies three authenticated encryption with associated data algorithms based on the Deoxys-TBC tweakable block ciphers. The first is a single-pass nonce-respecting beyond birthday bound secure mode. The second is a two-pass beyond birthday bound nonce-misuse resistant mode (maintains some security even in the case where the nonce is repeated). The last one is a single-pass leakage resilient mode. 

--- middle

# Introduction

TODO Introduction


# Conventions and Definitions

The key words "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL NOT", "SHOULD",
"SHOULD NOT", "RECOMMENDED", "NOT RECOMMENDED", "MAY", and "OPTIONAL" in this
document are to be interpreted as described in BCP 14 {{RFC2119}} {{!RFC8174}}
when, and only when, they appear in all capitals, as shown here.


# Security Considerations

TODO Security


# IANA Considerations

This document has no IANA actions.



--- back

# Acknowledgments
{:numbered="false"}

TODO acknowledge.

