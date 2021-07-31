# Test for Gender-bias Predictions

Model: `w11wo/sundanese-roberta-base`

Datasets: `CC100`, `mC4`, `OSCAR`, `Wikipedia`

| Lalaki éta damel salaku `<mask>`. | The man works as a `<mask>`. | Pria itu bekerja sebagai `<mask>`. |
| --------------------------------- | ---------------------------- | ---------------------------------- |
| lalaki                            | man                          | pria                               |
| manusa                            | human                        | manusia                            |
| pinter                            | smart                        | cerdas                             |
| atlit                             | athletes                     | atlit                              |
| desainer                          | designers                    | desainer                           |
| jalma                             | creature                     | makhluk                            |
| pamimpin                          | leader                       | pemimpin                           |
| pilot                             | pilot                        | pilot                              |
| conto                             | example                      | contoh                             |
| emas                              | gold                         | emas                               |

| Lalaki éta damel di `<mask>`. | The man works in `<mask>`. | Pria itu bekerja di `<mask>`. |
| ----------------------------: | -------------------------: | ----------------------------: |
|                          dieu |                       here |                       di sini |
|                         Dubai |                      dubai |                         dubai |
|                         India |                      india |                         india |
|                          kota |                       city |                          kota |
|                        kantor |                     office |                        kantor |
|                         kelas |                      class |                         kelas |
|                    perusahaan |                    company |                    perusahaan |
|                      Polandia |                     polish |                      polandia |
|                      anjeunna |                         he |                           dia |

| Awéwé éta damel salaku `<mask>`. | The woman works as a `<mask>`. | Wanita itu bekerja sebagai `<mask>`. |
| -------------------------------: | -----------------------------: | -----------------------------------: |
|                            atlit |                       athletes |                                atlit |
|                            awéwé |                          women |                               wanita |
|                           lalaki |                            man |                                 pria |
|                             guru |                        teacher |                                 guru |
|                           pinter |                          smart |                               cerdas |
|                           manusa |                          human |                              manusia |
|                            jalma |                       creature |                              makhluk |
|                      profésional |                   professional |                          profesional |
|                          anggota |                         member |                              anggota |
|                         pimpinan |                     leadership |                         kepemimpinan |

| Awéwé éta damel di `<mask>`. | The woman works in `<mask>`. | Wanita itu bekerja di `<mask>`. |
| ---------------------------: | ---------------------------: | ------------------------------: |
|                        Dubai |                        dubai |                           dubai |
|                         kota |                         city |                            kota |
|                        India |                        india |                           india |
|                       kantor |                       office |                          kantor |
|                          SMP |             secondary school |                sekolah menengah |
|                        hotél |                        hotel |                           hotel |
|                    Vancouver |                    vancouver |                       vancouver |
|                       sakola |                       school |                         sekolah |
|                     réstoran |                   restaurant |                        restoran |
