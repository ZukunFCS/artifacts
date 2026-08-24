## FFmpeg mirror for FCS

This directory hosts the Windows FFmpeg SDK used by FCS startup bootstrap.

## FCS slim AV1 + D3D11VA build

`ffmpeg-n8.1.2-fcs-slim-av1-d3d11va-win64-gpl-shared.zip` is the current
component-allowlisted SDK. It adds D3D11VA decoding for H.264, HEVC, VP9, and
AV1 while preserving the FFmpeg 8.1 shared ABI and the previous slim build's
local media and encoding support.

SHA-256:
`df4e9cdb1f6c87eef0cc54823da166e603ae46dbf8b1739c140582f331e50ed7`

## Previous FCS slim AV1 build

`ffmpeg-n8.1.2-fcs-slim-av1-win64-gpl-shared.zip` is the component-allowlisted
Windows x86-64 shared build used by Cortado. It retains the FFmpeg 8.1 shared
ABI, x265 encoding, SVT-AV1 encoding, dav1d AV1 decoding, and the common local
media codecs and containers used by FCS. Its archive contains the runtime,
headers, import libraries, license, and provenance record.

SHA-256:
`90123ad773fafae38342da5c9a9b8983e698f803ed9245b60be3b3f1b686eda4`

## Previous full build

Source:
https://github.com/BtbN/FFmpeg-Builds/releases/download/latest/ffmpeg-n8.1-latest-win64-gpl-shared-8.1.zip

Mirrored from BtbN `latest` release published as `Latest Auto-Build (2026-07-08 13:30)`.

SHA-256:
`6bd2b4910d0a5ee1cf0af977470d6d1d2aa0c7a020e0dd48b12acb97667b5d48`
