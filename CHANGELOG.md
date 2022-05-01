Change Log
==========
### Ver. 3.8.17 (28/04/22)
- Update low level

### Ver. 3.8.15 (14/03/22)
- Update low level

### Ver. 3.8.14 (27/02/22)
- Update MisbCore (VObject)

### Ver. 3.8.13 (17/02/22)
- Update low level (RTSP related improvements)

### Ver. 3.8.12 (01/02/22)
- Add KeepTimeTagEmpty
- Update remuxer

### Ver. 3.8.11 (19/12/21)
- Update low level
- Remuxer based on MisbCore
- Remove EG601 and KlvLib dependencies

### Ver. 3.8.10 (23/11/21)
- Update low level
- Add time restricted license support
- Move to vc142

### Ver. 3.8.9.1 (14/11/21)
- Low level update. VS2019 runtime binaries

### Ver. 3.8.9.0 (14/10/21)
- Low level update. Move to VS2019
- Add FrameAccuracyRequiresSequenceHeaders 

### Ver. 3.8.7.1 (05/04/21)
- Allow integers in addition to float for some tags

### Ver. 3.8.7 (31/03/21)
- Low level update
- Fix HLS duration (with discontinuity) 
- Remove EnforcedDecoder

### Ver. 3.8.6 (18/01/21)
- Add ContiguousDemuxedVideo

### Ver. 3.8.5
- Low level update

### Ver. 3.8.4.2
- Fix Tag 6, 7 special value
- Fix casting for 32 bit special values

### Ver. 3.8.4.1
- Fix Tag 20 ( Sensor Relative Roll Angle) validation

### Ver. 3.8.4
- Injector DVR mode
- Fix RTSP (wrong address)

### Ver. 3.8.3.1
- Fix activation

### Ver. 3.8.3
- Low level update

### Ver. 3.8.2
- Low level update

### Ver. 3.8.1
- Low level update

### Ver. 3.8.0
- MisbCore
- Move to .NET 4.6.1
- decodedData now passed as JObject

### Ver. 3.7.15
- Low level update

### Ver. 3.7.12
- RTSP target (MPEG TS, Multicast)
- Add frame grabber
### Ver. 3.7.11
- Low delay fixes
- Adding option to modify incoming PTS in Injector according to local CPU time
### Ver. 3.7.10
- Low level update
- 0.0.0.0 binding
### Ver. 3.7.9
- Low level update
### Ver. 3.7.7
- Encoder profile and framerate changes
- Low level update - StCore 3.7.7
### Ver. 3.7.6
- Low level changes (Injector robustness)
- Fix missing Klv after seek
- Fix audio pid mux
### Ver. 3.7.5
- Low level change (Klv serialization)

### Ver. 3.7.3
- Logger added to the constructor
### Ver. 3.7.1
- Add  WritePacketToOutputPid(int pid, Bitmap bmp, Int64 timeStampInUnits = -1) method
### Ver. 3.7.0
- BER-OID tags
### Ver. 3.6.1
- Synthetic Video fixes in low level filters and StCore.dll
### Ver. 3.6.0
- Low level update
- Fix high bitrate injest
- Fix EC_COMPLETE without video decoding
### Ver. 3.5.6
- Fixes in synthetic video support
### Ver. 3.5.5
- Fixes in synthetic video support and CUDA accelerated decoding
### Ver. 3.5.3
- Several low level improvements. This includes better performance in snapshot, and fixing a bug in false positive detection of source timeout
- Add SetDefaultPacket(JObject pckt) method
- Add UpdateDefaultPacketTime method
### Ver. 3.5.2
- Fix StCore release stuck
- Low lelvel update and interface change (add)
- Fix segment duration (sec instead of ms)
### Ver. 3.5.1
- StCore compiled with vc141 and boost 1.71
### Ver. 3.4.4
- Low level updates
### Ver. 3.4.3
- Low level updates
- 601 tags
### Ver. 3.4.2
- Low level updates
### Ver. 3.4.1
-StCore update
### Ver. 3.4.0
-StCore update
### Ver. 3.2.2
- Encode packet added to remux
### Ver. 3.2.0
- Low level updates
### Ver. 3.0.36
- Low level updates
### Ver. 3.0.35
- Low level updates
### Ver. 3.0.32
- Fix a -1 timestamp increment