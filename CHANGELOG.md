<a name="v0.15.0"></a>
## [v0.15.0] - 2022-11-13
### Chore
- Remove lagging pre-release ref ([#206](https://github.com/txpipe/pallas/issues/206))
- Fix lint warnings ([#205](https://github.com/txpipe/pallas/issues/205))
- Remove pre-release ref from deps ([#204](https://github.com/txpipe/pallas/issues/204))
- Fix address lint issue ([#201](https://github.com/txpipe/pallas/issues/201))
- **miniprotocols:** Fix integration tests after preview respin ([#203](https://github.com/txpipe/pallas/issues/203))
- **miniprotocols:** Add chain-sync tip test ([#199](https://github.com/txpipe/pallas/issues/199))

### Feat
- Migrate to dumb agents ([#198](https://github.com/txpipe/pallas/issues/198))
- **traverse:** produces_at method for MultiEraTx ([#200](https://github.com/txpipe/pallas/issues/200))

### Fix
- **primitives:** Handle generic int in Plutus data ([#202](https://github.com/txpipe/pallas/issues/202))

### BREAKING CHANGE

handshake, chainsync, localstate and blockfetch mini-protocols changed the API surface


<a name="v0.14.0"></a>
## [v0.14.0] - 2022-10-13

<a name="v0.14.0-alpha.6"></a>
## [v0.14.0-alpha.6] - 2022-10-13
### Build
- **deps:** update minicbor requirement from 0.17 to 0.18 ([#134](https://github.com/txpipe/pallas/issues/134))
- **deps:** update bech32 requirement from 0.8.1 to 0.9.1 ([#177](https://github.com/txpipe/pallas/issues/177))

### Chore
- Fix linter warnings ([#194](https://github.com/txpipe/pallas/issues/194))
- Fix lint warnings ([#190](https://github.com/txpipe/pallas/issues/190))
- Move fee logic out of primitives ([#174](https://github.com/txpipe/pallas/issues/174))
- Move time logic out of primitives ([#173](https://github.com/txpipe/pallas/issues/173))
- Move hash logic out of primitives ([#172](https://github.com/txpipe/pallas/issues/172))
- **primitives:** Remove redundant address logic ([#171](https://github.com/txpipe/pallas/issues/171))

### Feat
- return indexes along with outputs returned by produces() ([#193](https://github.com/txpipe/pallas/issues/193))
- Provide access to all assets at a tx out ([#180](https://github.com/txpipe/pallas/issues/180))
- Add magic constants for preview and preprod environments ([#179](https://github.com/txpipe/pallas/issues/179))
- Introduce Bech32 crate ([#176](https://github.com/txpipe/pallas/issues/176))
- **addresses:** Add hex and bech32 for Shelley parts ([#181](https://github.com/txpipe/pallas/issues/181))
- **primitives:** Preserve order of map structures ([#192](https://github.com/txpipe/pallas/issues/192))
- **primitives:** Enable serde of ledger structs ([#169](https://github.com/txpipe/pallas/issues/169))
- **traverse:** Add helper methods to Asset data ([#195](https://github.com/txpipe/pallas/issues/195))
- **traverse:** Provide access to original Datum hash ([#189](https://github.com/txpipe/pallas/issues/189))
- **traverse:** Introduce new MultiEraTx helpers ([#184](https://github.com/txpipe/pallas/issues/184))

### Fix
- Stop double CBOR encoding of Plutus script used for hashing ([#188](https://github.com/txpipe/pallas/issues/188))
- use correct prefix when hashing plutus v2 script ([#182](https://github.com/txpipe/pallas/issues/182))
- **codec:** Make Int struct copy ([#170](https://github.com/txpipe/pallas/issues/170))
- **primitives:** Add missing PartialOrd and Ord to TransactionInput ([#191](https://github.com/txpipe/pallas/issues/191))
- **traverse:** Make ToHash trait public outside crate ([#186](https://github.com/txpipe/pallas/issues/186))


<a name="v0.13.3"></a>
## [v0.13.3] - 2022-10-13
### Fix
- Handle undefined CBOR maps in Plutus data ([#196](https://github.com/txpipe/pallas/issues/196))


<a name="v0.14.0-alpha.5"></a>
## [v0.14.0-alpha.5] - 2022-09-28
### Feat
- **traverse:** Add helper methods to Asset data ([#195](https://github.com/txpipe/pallas/issues/195))


<a name="v0.14.0-alpha.4"></a>
## [v0.14.0-alpha.4] - 2022-09-21
### Chore
- Fix linter warnings ([#194](https://github.com/txpipe/pallas/issues/194))

### Feat
- return indexes along with outputs returned by produces() ([#193](https://github.com/txpipe/pallas/issues/193))
- Provide access to all assets at a tx out ([#180](https://github.com/txpipe/pallas/issues/180))


<a name="v0.14.0-alpha.3"></a>
## [v0.14.0-alpha.3] - 2022-09-15
### Feat
- **primitives:** Preserve order of map structures ([#192](https://github.com/txpipe/pallas/issues/192))

### Fix
- **primitives:** Add missing PartialOrd and Ord to TransactionInput ([#191](https://github.com/txpipe/pallas/issues/191))


<a name="v0.14.0-alpha.2"></a>
## [v0.14.0-alpha.2] - 2022-09-13
### Chore
- Fix lint warnings ([#190](https://github.com/txpipe/pallas/issues/190))

### Feat
- **traverse:** Provide access to original Datum hash ([#189](https://github.com/txpipe/pallas/issues/189))

### Fix
- Stop double CBOR encoding of Plutus script used for hashing ([#188](https://github.com/txpipe/pallas/issues/188))


<a name="v0.14.0-alpha.1"></a>
## [v0.14.0-alpha.1] - 2022-09-11
### Fix
- **traverse:** Make ToHash trait public outside crate ([#186](https://github.com/txpipe/pallas/issues/186))


<a name="v0.14.0-alpha.0"></a>
## [v0.14.0-alpha.0] - 2022-09-11
### Build
- **deps:** update minicbor requirement from 0.17 to 0.18 ([#134](https://github.com/txpipe/pallas/issues/134))
- **deps:** update bech32 requirement from 0.8.1 to 0.9.1 ([#177](https://github.com/txpipe/pallas/issues/177))

### Chore
- Move fee logic out of primitives ([#174](https://github.com/txpipe/pallas/issues/174))
- Move time logic out of primitives ([#173](https://github.com/txpipe/pallas/issues/173))
- Move hash logic out of primitives ([#172](https://github.com/txpipe/pallas/issues/172))
- **primitives:** Remove redundant address logic ([#171](https://github.com/txpipe/pallas/issues/171))

### Feat
- Add magic constants for preview and preprod environments ([#179](https://github.com/txpipe/pallas/issues/179))
- Introduce Bech32 crate ([#176](https://github.com/txpipe/pallas/issues/176))
- **addresses:** Add hex and bech32 for Shelley parts ([#181](https://github.com/txpipe/pallas/issues/181))
- **primitives:** Enable serde of ledger structs ([#169](https://github.com/txpipe/pallas/issues/169))
- **traverse:** Introduce new MultiEraTx helpers ([#184](https://github.com/txpipe/pallas/issues/184))

### Fix
- use correct prefix when hashing plutus v2 script ([#182](https://github.com/txpipe/pallas/issues/182))
- **codec:** Make Int struct copy ([#170](https://github.com/txpipe/pallas/issues/170))


<a name="v0.13.2"></a>
## [v0.13.2] - 2022-08-19
### Fix
- **addresses:** Skip error on pointer address overflow ([#178](https://github.com/txpipe/pallas/issues/178))


<a name="v0.13.1"></a>
## [v0.13.1] - 2022-08-08
### Fix
- **primitives:** Fix overflow on cost model ([#168](https://github.com/txpipe/pallas/issues/168))
- **primitives:** Make cost models optional ([#167](https://github.com/txpipe/pallas/issues/167))


<a name="v0.13.0"></a>
## [v0.13.0] - 2022-08-07
### Chore
- Fix lint warnings ([#166](https://github.com/txpipe/pallas/issues/166))
- Fix trailing comma lint issue ([#165](https://github.com/txpipe/pallas/issues/165))

### Feat
- **primitives:** Add ToHash to DatumOption ([#163](https://github.com/txpipe/pallas/issues/163))
- **traverse:** Add missing getters on output ([#162](https://github.com/txpipe/pallas/issues/162))
- **traverse:** Add missing getters for witness fields ([#160](https://github.com/txpipe/pallas/issues/160))
- **traverse:** Add reference inputs to Tx ([#161](https://github.com/txpipe/pallas/issues/161))
- **traverse:** Expose collateral return ([#158](https://github.com/txpipe/pallas/issues/158))

### Fix
- **primitives:** Handle alonzo headers without prev-hash ([#164](https://github.com/txpipe/pallas/issues/164))
- **primitives:** Force CBOR null primitive for missing aux data ([#159](https://github.com/txpipe/pallas/issues/159))


<a name="v0.12.0"></a>
## [v0.12.0] - 2022-08-02
### Chore
- Add test for output traverse ([#157](https://github.com/txpipe/pallas/issues/157))
- Fix lint warnings

### Fix
- **addresses:** Fix Byron cbor structure ([#155](https://github.com/txpipe/pallas/issues/155))


<a name="v0.12.0-alpha.0"></a>
## [v0.12.0-alpha.0] - 2022-07-20
### Chore
- Apply code formatting
- **primitives:** Add Plutus script hash test ([#147](https://github.com/txpipe/pallas/issues/147))

### Feat
- **addresses:** Improve API ergonomics ([#148](https://github.com/txpipe/pallas/issues/148))
- **miniprotocols:** Add  Tx-Mempool-Monitoring mini-Protocol  ([#150](https://github.com/txpipe/pallas/issues/150))
- **traverse:** Introduce more new accessor methods ([#153](https://github.com/txpipe/pallas/issues/153))
- **traverse:** Introduce new accessor methods ([#152](https://github.com/txpipe/pallas/issues/152))
- **traverse:** Expose multi-era metadata ([#151](https://github.com/txpipe/pallas/issues/151))
- **traverse:** Integrate address library ([#149](https://github.com/txpipe/pallas/issues/149))

### Fix
- **multiplexer:** Honor read timeouts in bearer logic ([#154](https://github.com/txpipe/pallas/issues/154))


<a name="v0.11.1"></a>
## [v0.11.1] - 2022-07-03
### Fix
- **traverse:** Add missing era probe


<a name="v0.11.0"></a>
## [v0.11.0] - 2022-07-02
### Build
- **deps:** update bech32 requirement from 0.8.1 to 0.9.0 ([#104](https://github.com/txpipe/pallas/issues/104))

### Chore
- **primitives:** Organize test data on a single dir ([#112](https://github.com/txpipe/pallas/issues/112))

### Docs
- Update changelog

### Feat
- Add mechanism to check era's features ([#120](https://github.com/txpipe/pallas/issues/120))
- Introduce 'traverse' library ([#117](https://github.com/txpipe/pallas/issues/117))
- Introduce Addresses crate ([#137](https://github.com/txpipe/pallas/issues/137))
- Add Vasil / Babbage compatibility ([#126](https://github.com/txpipe/pallas/issues/126))
- Implement common traverse iterators ([#119](https://github.com/txpipe/pallas/issues/119))
- **multiplexer:** Use single channel for muxer ([#133](https://github.com/txpipe/pallas/issues/133))
- **primitives:** Introduce MintedBlock concept ([#116](https://github.com/txpipe/pallas/issues/116))
- **traverse:** Add era-handling utilities ([#123](https://github.com/txpipe/pallas/issues/123))
- **traverse:** Add output refs for inputs ([#122](https://github.com/txpipe/pallas/issues/122))
- **traverse:** Add tx input traversing ([#121](https://github.com/txpipe/pallas/issues/121))
- **traverse:** Add output-at helper method ([#124](https://github.com/txpipe/pallas/issues/124))
- **traverse:** Add ada amount method on output ([#135](https://github.com/txpipe/pallas/issues/135))
- **traverse:** Expose block number value ([#140](https://github.com/txpipe/pallas/issues/140))
- **traverse:** Improve MultiEraOutput ergonomics ([#141](https://github.com/txpipe/pallas/issues/141))

### Fix
- Add missing README blocking publish
- Add missing README preventing publish
- **multiplexer:** Use buffers that own the inner channel ([#113](https://github.com/txpipe/pallas/issues/113))
- **multiplexer:** Handle bearer io error instead of panic ([#118](https://github.com/txpipe/pallas/issues/118))
- **primitives:** Handle bytes indef in Plutus data ([#143](https://github.com/txpipe/pallas/issues/143))
- **primitives:** Adjust member visibility in structs ([#144](https://github.com/txpipe/pallas/issues/144))
- **traverse:** Handle Shelley's lack of invalid_transactions field ([#138](https://github.com/txpipe/pallas/issues/138))


<a name="v0.10.1"></a>
## [v0.10.1] - 2022-07-02
### Fix
- **primitives:** Handle bytes indef in Plutus data


<a name="v0.11.0-beta.1"></a>
## [v0.11.0-beta.1] - 2022-06-25
### Feat
- Introduce Addresses crate ([#137](https://github.com/txpipe/pallas/issues/137))

### Fix
- Add missing README blocking publish
- **traverse:** Handle Shelley's lack of invalid_transactions field ([#138](https://github.com/txpipe/pallas/issues/138))


<a name="v0.11.0-beta.0"></a>
## [v0.11.0-beta.0] - 2022-06-20
### Build
- **deps:** update bech32 requirement from 0.8.1 to 0.9.0 ([#104](https://github.com/txpipe/pallas/issues/104))

### Feat
- Add Vasil / Babbage compatibility ([#126](https://github.com/txpipe/pallas/issues/126))
- **multiplexer:** Use single channel for muxer ([#133](https://github.com/txpipe/pallas/issues/133))
- **traverse:** Add ada amount method on output ([#135](https://github.com/txpipe/pallas/issues/135))


<a name="v0.11.0-alpha.2"></a>
## [v0.11.0-alpha.2] - 2022-06-17
### Feat
- **traverse:** Add output-at helper method ([#124](https://github.com/txpipe/pallas/issues/124))
- **traverse:** Add era-handling utilities ([#123](https://github.com/txpipe/pallas/issues/123))
- **traverse:** Add output refs for inputs ([#122](https://github.com/txpipe/pallas/issues/122))
- **traverse:** Add tx input traversing ([#121](https://github.com/txpipe/pallas/issues/121))

### Fix
- Add missing README preventing publish


<a name="v0.11.0-alpha.1"></a>
## [v0.11.0-alpha.1] - 2022-06-15
### Feat
- Add mechanism to check era's features ([#120](https://github.com/txpipe/pallas/issues/120))
- Implement common traverse iterators ([#119](https://github.com/txpipe/pallas/issues/119))
- Introduce 'traverse' library ([#117](https://github.com/txpipe/pallas/issues/117))
- **primitives:** Introduce MintedBlock concept ([#116](https://github.com/txpipe/pallas/issues/116))

### Fix
- **multiplexer:** Handle bearer io error instead of panic ([#118](https://github.com/txpipe/pallas/issues/118))


<a name="v0.11.0-alpha.0"></a>
## [v0.11.0-alpha.0] - 2022-06-10
### Chore
- **primitives:** Organize test data on a single dir ([#112](https://github.com/txpipe/pallas/issues/112))

### Docs
- Update changelog

### Fix
- **multiplexer:** Use buffers that own the inner channel ([#113](https://github.com/txpipe/pallas/issues/113))


<a name="v0.10.0"></a>
## [v0.10.0] - 2022-06-04
### Chore
- **deps:** Upgrade to minicbor 0.17 (breaking changes) ([#109](https://github.com/txpipe/pallas/issues/109))

### Feat
- Improve multiplexer ergonomics ([#111](https://github.com/txpipe/pallas/issues/111))
- Add mechanism to retain original CBOR ([#110](https://github.com/txpipe/pallas/issues/110))
- **multiplexer:** Allow fine-grained control of concurrency strategy ([#106](https://github.com/txpipe/pallas/issues/106))
- **primitives:** Add self-contained transaction struct ([#107](https://github.com/txpipe/pallas/issues/107))


<a name="v0.9.1"></a>
## [v0.9.1] - 2022-05-03
### Fix
- Provide access to PlutusScript bytes ([#102](https://github.com/txpipe/pallas/issues/102))


<a name="v0.9.0"></a>
## [v0.9.0] - 2022-04-30
### Ci
- Skip publish confirmation prompt
- Enable tag-based release workflow
- Add draft version of the release workflow ([#101](https://github.com/txpipe/pallas/issues/101))

### Docs
- Add retroactive change log


<a name="v0.9.0-alpha.1"></a>
## [v0.9.0-alpha.1] - 2022-04-29
### Chore
- Add unit test for native script hash ([#98](https://github.com/txpipe/pallas/issues/98))
- Move miniprotocol examples to custom crate ([#97](https://github.com/txpipe/pallas/issues/97))

### Feat
- Implement Plutus Data hashing / JSON ([#100](https://github.com/txpipe/pallas/issues/100))

### Fix
- Use correct struct for metadatum labels ([#96](https://github.com/txpipe/pallas/issues/96))
- Update failing native script json test ([#95](https://github.com/txpipe/pallas/issues/95))
- **primitives:** Fix native scripts policy id (add missing tag) ([#94](https://github.com/txpipe/pallas/issues/94))
- **primitives:** Fix native scripts before/after type serialization ([#93](https://github.com/txpipe/pallas/issues/93))


<a name="v0.9.0-alpha.0"></a>
## [v0.9.0-alpha.0] - 2022-04-26
### Feat
- **primitives:** Implement length-preserving uints ([#92](https://github.com/txpipe/pallas/issues/92))
- **primitives:** Implement canonical JSON serialization ([#90](https://github.com/txpipe/pallas/issues/90))


<a name="v0.8.0"></a>
## [v0.8.0] - 2022-04-11

<a name="v0.8.0-alpha.1"></a>
## [v0.8.0-alpha.1] - 2022-04-11
### Feat
- Improve alonzo address ergonomics ([#87](https://github.com/txpipe/pallas/issues/87))
- Make blockfetch observer mutable ([#86](https://github.com/txpipe/pallas/issues/86))
- **miniprotocols:** Allow step-by-step agents ([#85](https://github.com/txpipe/pallas/issues/85))


<a name="v0.8.0-alpha.0"></a>
## [v0.8.0-alpha.0] - 2022-03-22
### Chore
- Fix rogue clippy warnings ([#79](https://github.com/txpipe/pallas/issues/79))
- Add block-decoding example ([#78](https://github.com/txpipe/pallas/issues/78))
- Update README with new crates ([#77](https://github.com/txpipe/pallas/issues/77))

### Docs
- Split miniprotocol status into initiator vs responder ([#82](https://github.com/txpipe/pallas/issues/82))
- Fix README links ([#81](https://github.com/txpipe/pallas/issues/81))
- Add miniprotocols crate README ([#80](https://github.com/txpipe/pallas/issues/80))

### Feat
- **miniprotocols:** Allow graceful exit on chainsync and blockfetch ([#83](https://github.com/txpipe/pallas/issues/83))

### Refactor
- **miniprotocols:** Use pure functions for state machines ([#84](https://github.com/txpipe/pallas/issues/84))


<a name="pallas-codec@0.7.1"></a>
## [pallas-codec@0.7.1] - 2022-03-16

<a name="pallas-miniprotocols@0.7.1"></a>
## [pallas-miniprotocols@0.7.1] - 2022-03-16
### Fix
- **miniprotocols:** Handle regression related to multi-msg payloads ([#76](https://github.com/txpipe/pallas/issues/76))


<a name="v0.7.0"></a>
## [v0.7.0] - 2022-03-16

<a name="v0.7.0-alpha.1"></a>
## [v0.7.0-alpha.1] - 2022-03-16
### Build
- **deps:** update minicbor requirement from 0.14 to 0.15 ([#72](https://github.com/txpipe/pallas/issues/72))

### Feat
- Use DecodeOwned for improved ergonomic ([#74](https://github.com/txpipe/pallas/issues/74))
- Introduce shared codec lib ([#71](https://github.com/txpipe/pallas/issues/71))

### Fix
- Use minicbor int to represent metadatum ints ([#73](https://github.com/txpipe/pallas/issues/73))
- **primitives:** Handle very BigInt in plutus data ([#75](https://github.com/txpipe/pallas/issues/75))


<a name="v0.7.0-alpha.0"></a>
## [v0.7.0-alpha.0] - 2022-03-13

<a name="pallas-primitives@0.6.4"></a>
## [pallas-primitives@0.6.4] - 2022-03-08
### Fix
- **primitives:** Handle map-indef variant for aux data ([#70](https://github.com/txpipe/pallas/issues/70))


<a name="pallas-primitives@0.6.3"></a>
## [pallas-primitives@0.6.3] - 2022-03-08
### Fix
- **primitives:** Add missing variant (not in CDDL) to AddrAttr enum ([#69](https://github.com/txpipe/pallas/issues/69))


<a name="pallas-primitives@0.6.2"></a>
## [pallas-primitives@0.6.2] - 2022-03-01
### Fix
- **primitives:** Fix decoding of empty Nonce hash ([#67](https://github.com/txpipe/pallas/issues/67))


<a name="pallas-primitives@0.6.1"></a>
## [pallas-primitives@0.6.1] - 2022-02-28
### Fix
- **primitives:** Fix round-trip decoding of Alonzo update struct ([#66](https://github.com/txpipe/pallas/issues/66))


<a name="v0.6.0"></a>
## [v0.6.0] - 2022-02-28

<a name="v0.5.4"></a>
## [v0.5.4] - 2022-02-28
### Build
- **deps:** minicbor-0.14, minicbor-derive-0.9.0, fix build ([#63](https://github.com/txpipe/pallas/issues/63))

### Fix
- **miniprotocols:** Decode BlockContent correctly ([#60](https://github.com/txpipe/pallas/issues/60))
- **primitives:** Fix round-trip decoding of move_instantaneous_reward struct ([#64](https://github.com/txpipe/pallas/issues/64))
- **primitives:** Fix ssc struct codec ([#62](https://github.com/txpipe/pallas/issues/62))
- **primitives:** Fix Byron 'Up' struct decoding ([#61](https://github.com/txpipe/pallas/issues/61))


<a name="v0.5.0"></a>
## [v0.5.0] - 2022-02-24
### Chore
- Fix clippy warnings


<a name="v0.5.0-beta.0"></a>
## [v0.5.0-beta.0] - 2022-02-24
### Chore
- Tidy up examples

### Feat
- Handle correct probing of genesis block ([#57](https://github.com/txpipe/pallas/issues/57))

### Fix
- **primitives:** Fix round-trip decoding of genesis block ([#58](https://github.com/txpipe/pallas/issues/58))


<a name="v0.5.0-alpha.5"></a>
## [v0.5.0-alpha.5] - 2022-02-23
### Feat
- Allow chainsync to start from origin ([#56](https://github.com/txpipe/pallas/issues/56))


<a name="v0.5.0-alpha.4"></a>
## [v0.5.0-alpha.4] - 2022-02-18
### Feat
- add Eq & Ord to Era ([#53](https://github.com/txpipe/pallas/issues/53))


<a name="v0.5.0-alpha.3"></a>
## [v0.5.0-alpha.3] - 2022-02-17
### Feat
- Make chainsync protocol era-agnostic ([#52](https://github.com/txpipe/pallas/issues/52))
- Include cbor probing for all known eras ([#51](https://github.com/txpipe/pallas/issues/51))


<a name="v0.5.0-alpha.2"></a>
## [v0.5.0-alpha.2] - 2022-02-16
### Feat
- Implement rollback buffer ([#49](https://github.com/txpipe/pallas/issues/49))

### Fix
- Add mutability to chainsync observer ([#50](https://github.com/txpipe/pallas/issues/50))


<a name="v0.5.0-alpha.1"></a>
## [v0.5.0-alpha.1] - 2022-02-14
### Chore
- Simplify ChainSync agent logic ([#48](https://github.com/txpipe/pallas/issues/48))

### Feat
- Add Byron header hashing ([#45](https://github.com/txpipe/pallas/issues/45))
- Implement block cbor probing ([#44](https://github.com/txpipe/pallas/issues/44))
- **primitives:** Improve ergonomics for Byron primitives ([#47](https://github.com/txpipe/pallas/issues/47))

### Fix
- **primitives:** Probe old shelley blocks correctly ([#46](https://github.com/txpipe/pallas/issues/46))


<a name="v0.5.0-alpha.0"></a>
## [v0.5.0-alpha.0] - 2022-02-09
### Chore
- Merge Byron / Alonzo into single crate ([#43](https://github.com/txpipe/pallas/issues/43))
- Add logo to README ([#42](https://github.com/txpipe/pallas/issues/42))
- Add logo assets
- Merge mini-protocols into single crate ([#40](https://github.com/txpipe/pallas/issues/40))

### Feat
- Introduce Byron library ([#39](https://github.com/txpipe/pallas/issues/39))

### Test
- Overflow error in ExUnits ([#38](https://github.com/txpipe/pallas/issues/38))


<a name="v0.4.0"></a>
## [v0.4.0] - 2022-01-31
### Build
- Enable dependabot
- **deps:** update minicbor requirement from 0.12 to 0.13 ([#37](https://github.com/txpipe/pallas/issues/37))
- **deps:** update cryptoxide requirement from 0.3.6 to 0.4.1 ([#36](https://github.com/txpipe/pallas/issues/36))
- **deps:** update minicbor-derive requirement from 0.7.2 to 0.8.0

### Docs
- Add block download example ([#24](https://github.com/txpipe/pallas/issues/24))

### Feat
- make use of the `pallas_crypto::Hash` type ([#25](https://github.com/txpipe/pallas/issues/25))

### Fix
- **alonzo:** ExUnits steps overflow ([#35](https://github.com/txpipe/pallas/issues/35))

### Pull Requests
- Merge pull request [#27](https://github.com/txpipe/pallas/issues/27) from txpipe/nicolasdp/ed25519-plus
- Merge pull request [#23](https://github.com/txpipe/pallas/issues/23) from txpipe/nicolasdp/pallas-crypto-faster-hash-computation
- Merge pull request [#21](https://github.com/txpipe/pallas/issues/21) from txpipe/dependabot/cargo/minicbor-derive-0.8.0


<a name="v0.3.9"></a>
## [v0.3.9] - 2022-01-09
### Fix
- **alonzo:** Apply valid cbor codec for Nonce values ([#20](https://github.com/txpipe/pallas/issues/20))


<a name="v0.3.8"></a>
## [v0.3.8] - 2022-01-08
### Fix
- **alonzo:** Contemplate aux data with multiple plutus scripts ([#19](https://github.com/txpipe/pallas/issues/19))


<a name="v0.3.7"></a>
## [v0.3.7] - 2022-01-07
### Fix
- **alonzo:** Apply correct codec for protocol param updates ([#18](https://github.com/txpipe/pallas/issues/18))


<a name="v0.3.6"></a>
## [v0.3.6] - 2022-01-06
### Fix
- **alonzo:** Make 'invalid txs' field optional for old block compatibility ([#17](https://github.com/txpipe/pallas/issues/17))


<a name="v0.3.5"></a>
## [v0.3.5] - 2022-01-03
### Chore
- Fix formatting / linting issues

### Ci
- Ignore clippy needless_range_loop
- **multiplexer:** Fix connection refused error in integration tests ([#13](https://github.com/txpipe/pallas/issues/13))

### Fix
- **chainsync:** Stop the consumer machine when intersect is not found ([#14](https://github.com/txpipe/pallas/issues/14))
- **machines:** Don't warn on expected end-of-input errors ([#15](https://github.com/txpipe/pallas/issues/15))
- **multiplexer:** Remove disconnected protocols from muxer loop ([#16](https://github.com/txpipe/pallas/issues/16))

### Pull Requests
- Merge pull request [#9](https://github.com/txpipe/pallas/issues/9) from 2nd-Layer/main


<a name="v0.3.4"></a>
## [v0.3.4] - 2021-12-19
### Ci
- add validation workflow on push

### Feat
- Disable Unix socket on non-unix platforms
- **multiplexer:** Add error messages to potential panics

### Style
- **multiplexer:** format code

### Test
- **multiplexer:** Add basic integration tests

### Pull Requests
- Merge pull request [#8](https://github.com/txpipe/pallas/issues/8) from 2nd-Layer/disable_unix_socket_on_non-unix_system


<a name="v0.3.3"></a>
## [v0.3.3] - 2021-12-14
### Chore
- improve gitignore

### Docs
- **multiplexer:** tidy up examples
- **multiplexer:** add introduction to readme

### Fix
- **alonzo:** avoid indef arrays isomorphic codec issues
- **alonzo:** deal with transaction body ordering
- **alonzo:** use correct codec for plutus data
- **multiplexer:** resolve lint issues

### Refactor
- make chainsync machine agnostic of content


<a name="v0.3.2"></a>
## [v0.3.2] - 2021-12-10
### Feat
- **blockfetch:** add more observer events


<a name="v0.3.1"></a>
## [v0.3.1] - 2021-12-10
### Feat
- **alonzo:** add instantaneous reward model

### Fix
- intra dev dependencies for example code
- update incompatible doc link versions
- **alonzo:** bad epoch data type
- **alonzo:** visibility of struct members


<a name="v0.3.0"></a>
## v0.3.0 - 2021-12-09
### Chore
- bump version numbers
- bump versions
- **alonzo:** ensure isomorphic decoding / encoding

### Feat
- **alonzo:** small ergonomic improvements to lib api
- **alonzo:** add mechanism to compute hashes of common structs
- **blockfetch:** add on-demand block-fetch client
- **chainsync:** add cursor to observer args
- **chainsync:** add tip finder specialized client

### Fix
- update incompatible doc link versions
- **handshake:** make client struct data public

### Refactor
- **multiplexer:** allow multiplexer channels to be sequantially shared

### Style
- apply fmt to entire workspace


[Unreleased]: https://github.com/txpipe/pallas/compare/v0.15.0...HEAD
[v0.15.0]: https://github.com/txpipe/pallas/compare/v0.14.0...v0.15.0
[v0.14.0]: https://github.com/txpipe/pallas/compare/v0.14.0-alpha.6...v0.14.0
[v0.14.0-alpha.6]: https://github.com/txpipe/pallas/compare/v0.13.3...v0.14.0-alpha.6
[v0.13.3]: https://github.com/txpipe/pallas/compare/v0.14.0-alpha.5...v0.13.3
[v0.14.0-alpha.5]: https://github.com/txpipe/pallas/compare/v0.14.0-alpha.4...v0.14.0-alpha.5
[v0.14.0-alpha.4]: https://github.com/txpipe/pallas/compare/v0.14.0-alpha.3...v0.14.0-alpha.4
[v0.14.0-alpha.3]: https://github.com/txpipe/pallas/compare/v0.14.0-alpha.2...v0.14.0-alpha.3
[v0.14.0-alpha.2]: https://github.com/txpipe/pallas/compare/v0.14.0-alpha.1...v0.14.0-alpha.2
[v0.14.0-alpha.1]: https://github.com/txpipe/pallas/compare/v0.14.0-alpha.0...v0.14.0-alpha.1
[v0.14.0-alpha.0]: https://github.com/txpipe/pallas/compare/v0.13.2...v0.14.0-alpha.0
[v0.13.2]: https://github.com/txpipe/pallas/compare/v0.13.1...v0.13.2
[v0.13.1]: https://github.com/txpipe/pallas/compare/v0.13.0...v0.13.1
[v0.13.0]: https://github.com/txpipe/pallas/compare/v0.12.0...v0.13.0
[v0.12.0]: https://github.com/txpipe/pallas/compare/v0.12.0-alpha.0...v0.12.0
[v0.12.0-alpha.0]: https://github.com/txpipe/pallas/compare/v0.11.1...v0.12.0-alpha.0
[v0.11.1]: https://github.com/txpipe/pallas/compare/v0.11.0...v0.11.1
[v0.11.0]: https://github.com/txpipe/pallas/compare/v0.10.1...v0.11.0
[v0.10.1]: https://github.com/txpipe/pallas/compare/v0.11.0-beta.1...v0.10.1
[v0.11.0-beta.1]: https://github.com/txpipe/pallas/compare/v0.11.0-beta.0...v0.11.0-beta.1
[v0.11.0-beta.0]: https://github.com/txpipe/pallas/compare/v0.11.0-alpha.2...v0.11.0-beta.0
[v0.11.0-alpha.2]: https://github.com/txpipe/pallas/compare/v0.11.0-alpha.1...v0.11.0-alpha.2
[v0.11.0-alpha.1]: https://github.com/txpipe/pallas/compare/v0.11.0-alpha.0...v0.11.0-alpha.1
[v0.11.0-alpha.0]: https://github.com/txpipe/pallas/compare/v0.10.0...v0.11.0-alpha.0
[v0.10.0]: https://github.com/txpipe/pallas/compare/v0.9.1...v0.10.0
[v0.9.1]: https://github.com/txpipe/pallas/compare/v0.9.0...v0.9.1
[v0.9.0]: https://github.com/txpipe/pallas/compare/v0.9.0-alpha.1...v0.9.0
[v0.9.0-alpha.1]: https://github.com/txpipe/pallas/compare/v0.9.0-alpha.0...v0.9.0-alpha.1
[v0.9.0-alpha.0]: https://github.com/txpipe/pallas/compare/v0.8.0...v0.9.0-alpha.0
[v0.8.0]: https://github.com/txpipe/pallas/compare/v0.8.0-alpha.1...v0.8.0
[v0.8.0-alpha.1]: https://github.com/txpipe/pallas/compare/v0.8.0-alpha.0...v0.8.0-alpha.1
[v0.8.0-alpha.0]: https://github.com/txpipe/pallas/compare/pallas-codec@0.7.1...v0.8.0-alpha.0
[pallas-codec@0.7.1]: https://github.com/txpipe/pallas/compare/pallas-miniprotocols@0.7.1...pallas-codec@0.7.1
[pallas-miniprotocols@0.7.1]: https://github.com/txpipe/pallas/compare/v0.7.0...pallas-miniprotocols@0.7.1
[v0.7.0]: https://github.com/txpipe/pallas/compare/v0.7.0-alpha.1...v0.7.0
[v0.7.0-alpha.1]: https://github.com/txpipe/pallas/compare/v0.7.0-alpha.0...v0.7.0-alpha.1
[v0.7.0-alpha.0]: https://github.com/txpipe/pallas/compare/pallas-primitives@0.6.4...v0.7.0-alpha.0
[pallas-primitives@0.6.4]: https://github.com/txpipe/pallas/compare/pallas-primitives@0.6.3...pallas-primitives@0.6.4
[pallas-primitives@0.6.3]: https://github.com/txpipe/pallas/compare/pallas-primitives@0.6.2...pallas-primitives@0.6.3
[pallas-primitives@0.6.2]: https://github.com/txpipe/pallas/compare/pallas-primitives@0.6.1...pallas-primitives@0.6.2
[pallas-primitives@0.6.1]: https://github.com/txpipe/pallas/compare/v0.6.0...pallas-primitives@0.6.1
[v0.6.0]: https://github.com/txpipe/pallas/compare/v0.5.4...v0.6.0
[v0.5.4]: https://github.com/txpipe/pallas/compare/v0.5.0...v0.5.4
[v0.5.0]: https://github.com/txpipe/pallas/compare/v0.5.0-beta.0...v0.5.0
[v0.5.0-beta.0]: https://github.com/txpipe/pallas/compare/v0.5.0-alpha.5...v0.5.0-beta.0
[v0.5.0-alpha.5]: https://github.com/txpipe/pallas/compare/v0.5.0-alpha.4...v0.5.0-alpha.5
[v0.5.0-alpha.4]: https://github.com/txpipe/pallas/compare/v0.5.0-alpha.3...v0.5.0-alpha.4
[v0.5.0-alpha.3]: https://github.com/txpipe/pallas/compare/v0.5.0-alpha.2...v0.5.0-alpha.3
[v0.5.0-alpha.2]: https://github.com/txpipe/pallas/compare/v0.5.0-alpha.1...v0.5.0-alpha.2
[v0.5.0-alpha.1]: https://github.com/txpipe/pallas/compare/v0.5.0-alpha.0...v0.5.0-alpha.1
[v0.5.0-alpha.0]: https://github.com/txpipe/pallas/compare/v0.4.0...v0.5.0-alpha.0
[v0.4.0]: https://github.com/txpipe/pallas/compare/v0.3.9...v0.4.0
[v0.3.9]: https://github.com/txpipe/pallas/compare/v0.3.8...v0.3.9
[v0.3.8]: https://github.com/txpipe/pallas/compare/v0.3.7...v0.3.8
[v0.3.7]: https://github.com/txpipe/pallas/compare/v0.3.6...v0.3.7
[v0.3.6]: https://github.com/txpipe/pallas/compare/v0.3.5...v0.3.6
[v0.3.5]: https://github.com/txpipe/pallas/compare/v0.3.4...v0.3.5
[v0.3.4]: https://github.com/txpipe/pallas/compare/v0.3.3...v0.3.4
[v0.3.3]: https://github.com/txpipe/pallas/compare/v0.3.2...v0.3.3
[v0.3.2]: https://github.com/txpipe/pallas/compare/v0.3.1...v0.3.2
[v0.3.1]: https://github.com/txpipe/pallas/compare/v0.3.0...v0.3.1
