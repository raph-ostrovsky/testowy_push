| Hash/Protocol | Cryptographic technique                                       | Mutual Authentication | Message Type                         | Trusted Third Party                     |
|---------------|--------------------------------------------------------------|-----------------------|--------------------------------------|----------------------------------------|
| NTLM          | Symmetric key cryptography                                   | No                    | Random number                        | Domain Controller                      |
| NTLMv1        | Symmetric key cryptography                                   | No                    | MD4 hash, random number              | Domain Controller                      |
| NTLMv2        | Symmetric key cryptography                                   | No                    | MD4 hash, random number              | Domain Controller                      |
| Kerberos      | Symmetric key cryptography & asymmetric cryptography         | Yes                   | Encrypted ticket using DES, MD5      | Domain Controller/Key Distribution Center (KDC) |


