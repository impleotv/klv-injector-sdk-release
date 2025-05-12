Change Log
==========

### Ver. 4.2.10 (12/05/25)
- Low level Ver. 1.7.13 (11/5/25)
	- Fix decoder state machine stability while playing corrupted content

### Ver. 4.2.7 (03/04/25)
- Low level 1.7.10 
	- Fixing demux of h265 with bad syntax

### Ver. 4.2.6 (16/03/25)
- Modify setup

### Ver. 4.2.5 (24/02/25)
- low level Ver. 1.7.9 (23/2/25)
	- Added API for enable/disable transport discontinuity events (default is ignore discontinuity)

### Ver. 4.2.4 (19/02/25)
- Replace x32 h264 encoder with x64
- low level Ver. 1.7.8 (19/2/25)
	- Fixed resolution detection in HEVC
	- supporting synthetic video insertion and dynamic input resolution change in encoder
	- fixing a regression bug in video capture mode
	- Supporting aspect ration dynamic change in encoder

### Ver. 4.2.1 (30/01/25)
- Add transcode mode
- low level
 - Adding support for AV1 in RTP input and in decoding
 - AV1 stabilization fixes

### Ver. 4.2.0 (12/01/25)
- low level
 - Upgrading ffmpeg to 5.1.2
 - Use Filters v1.7

### Ver. 4.1.2 (16/10/24)
- low level
	- Fix RTSP if more than 4 tracks
	- Fix Directx renderer dead-lock in low delay

### Ver. 4.1.1 (10/09/24)
- low level modifications
	- Comply with H264 SEI NAL in the beginning of PES

### Ver. 4.1.0 (12/08/24)
- low level modifications
- MisbCore VMTI modifications
	- Add MISB903.6 support 

### Ver. 4.0.6 (26/05/24)
- low level 
	- Add an option to select the gpu device performing the hw accelerated decoding

### Ver. 4.0.4 (13/05/24)
- low level 
	- Modify Log Trace to avoid crash when running in IIS
	- Add Program stream push demux
	- Add option for buffer writes in StCore instead of UDP input

### Ver. 4.0.2 (5/05/24)
- Modify JWT license implementation

### Ver. 4.0.1 (2/05/24)
- Change Setup structure
- low level 
	- Fix pause handling in VideoOverlayMixer
	- improve D3d video renderer performance

### Ver. 4.0.0 (1/05/24)
- Move to .Net 4.7.2
- Add JWT license

- Modify low level 
	- Add delay option in videoOverlayMixer
	- Add option to override aspect ratio in VideoOverlayMixer
	- Improvements in presentation filters

### Ver. 3.12.0 (26/03/24)
- Modify NodeInfo format
Low level:
- Improving performance in D3d rendering
- Fixing VideoOverlayMixer in handling I420 pixel format

### Ver. 3.11.1 (22/02/24)
- Update low level
- Add option for async callback of sync frames
- Modify StCore interface

### Ver. 3.10.11 (27/06/23)
- Low level update. Decoder memory leak fix
### Ver. 3.10.0 (23/05/23)
- Low level update. FFmpeg version change
- Add api for configuring decoding hw acceleration type
### Ver. 3.9.4 (03/04/23)
- Update Low level
- Fix Metadata_AU_cell () in KlvSource filter. Applicable to SYNC_KLV use case
### Ver. 3.9.0 (14/08/22)
- Add tags 115, 116, 121, 122, 128, 138, 139
- Update MisbCore (fix VMTI target id)
- Update low level 

### Ver. 3.8.14 (27/02/22)
- Update MisbCore (VObject)

### Ver. 3.8.11 (19/12/21)
- Update low level

### Ver. 3.8.10 (23/11/21)
- Update low level
- Add time restricted license support
- Move to vc142

### Ver. 3.8.9 (25/10/21)
- Low level update

### Ver. 3.8.8
- Add FrameAccuracyRequiresSequenceHeaders config 
- Low level update

### Ver. 3.8.7 (25/03/21)
- Low level update

### Ver. 3.8.6 (18/01/21)
- Add ContiguousDemuxedVideo

### Ver. 3.8.5 (15/01/21)
- Low level update
- Fix Big Endian Unicode in UTF-16

### Ver. 3.8.4
- Add RTSP support
- Enable FIPS Compliant authorization
- Low level update

### Ver. 3.8.2
- Low level update

### Ver. 3.8.1
- MisbCore changes.
- RAW Klv buffer processing

### Ver. 3.8.0
- MisbCore
- Move to .NET 4.6.1
- decodedData now passed as JObject

### Ver. 3.7.16
- Injector low latency mode

### Ver. 3.7.14,1
- Low level update

### Ver. 3.7.14
- Low level update

### Ver. 3.7.13
- Fix grabber (RGB)

### Ver. 3.7.12
- Add grabber

### Ver. 3.7.11
- Low delay fixes
- Adding option to modify incoming PTS in Injector according to local CPU time

### Ver. 3.7.10
- Low level update 
- Add compress video - VideoCaptureMode

### Ver. 3.7.6
- Low level update 
- Fix empty packet exception

### Ver. 3.7.3
- Add Raw Frame encoding to Injector

### Ver. 3.7.0
- Low level SDK update

### Ver. 3.5.1
- Initial version
