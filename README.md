Decrypted offsets are based on amiitool.

|           Description          | Encrypted Offset (Hex) | Decrypted Offset (Hex) |      Default Value      |                       Note                      |
|:------------------------------:|:----------------------:|:----------------------:|:-----------------------:|:-----------------------------------------------:|
| UID                            | 0-7                    | 1D4-1DB                | 04 C0 0A 46 61 6B 65 0A |                                                 |
| BCC, Internal, Static Lock, CC | 8-F                    | 0-7                    | 65 48 0F E0 F1 10 FF EE |                                                 |
| 0xA5, Write Counter, ?         | 10-13                  | 28-2B                  | A5 00 00 00             | 0xA5, two bytes for write counter, unknown byte |
| Locked Hash                    | 34-53                  | 1B4-1D3                |                         | Generated during encryption                     |
| Identification Block           | 54-5B                  | 1DC-1E3                |                         | The amiibo character ID, always ends in 0x02    |
| Unknown                        | 5C-5F                  | 1E4-1E7                |                         | Possibly some kind of counter                   |
| Keygen Salt                    | 60-7F                  | 1E8-207                |                         | 32 random bytes of encryption salt              |
| Unfixed Hash                   | 80-9F                  | 8-27                   |                         | Generated during encryption                     |
| Dynamic Lock, RFUI             | 208-20B                | 208-20B                | 01 00 0F BD             |                                                 |
| CFG0                           | 20C-20F                | 20C-20F                | 00 00 00 04             |                                                 |
| CFG1                           | 210-213                | 210-213                | 5F 00 00 00             |                                                 |

*Wumiibo is not affiliated, associated, authorized, endorsed by, or in any way officially connected with Nintendo. No  amiibo™ or digital representations of amiibo™ are included in this project. Binaries created with this project are not intended for sale or distribution. This project is for educational and archival purposes only.*
