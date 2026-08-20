# Awesome-Video-Hosting

## Top Video Hosting Ecosystem

**Curated List of SaaS/Hosted Platforms & Open-Source GitHub Projects**  
*Focused on Video Hosting, Video Streaming, Video Delivery, Video Management, OTT, Live Streaming & Video APIs*  
**Last updated: August 2026**

This repository tracks notable **SaaS/Hosted Platforms** and **open-source projects** for **Video Hosting**. These platforms help organizations upload, store, encode, transcode, manage, stream, distribute, monetize, secure, and analyze video content across websites, applications, OTT services, and internal platforms.

**Examples** include Vimeo, Wistia, Brightcove, Mux, Kaltura, Cloudflare Stream, Spotlightr, JW Player, Dacast, and Bunny Stream.

**Open-source emphasis**: This repository is heavily expanded with open-source video servers, media servers, streaming engines, transcoding frameworks, video players, WebRTC infrastructure, live-streaming platforms, OTT platforms, CDN/origin components, and video-management systems. Particularly important projects include **PeerTube, MediaMTX, Owncast, Jellyfin, Emby, Ant Media Server, OvenMediaEngine, SRS, MistServer, Janus, Jitsi, FFmpeg, GStreamer, Shaka Player, Video.js, and Kodi**.

Video hosting is broader than simply storing MP4 files. A production video platform typically combines **object storage + transcoding + packaging + CDN delivery + adaptive bitrate streaming + player + DRM/security + metadata + analytics + live streaming + recording + search + monetization**.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites or GitHub repositories.

## Table of Contents

- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [Additional Strong Open-Source Options](#additional-strong-open-source-options)
- [Open-Source Video Hosting Stack](#open-source-video-hosting-stack)
- [Video Hosting Building Blocks](#video-hosting-building-blocks)
- [Important Video Hosting Concepts](#important-video-hosting-concepts)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Platform | Description | Pricing | Free Tier / Trial Limits |
| :--- | :--- | :--- | :--- |
| **[Vimeo](https://vimeo.com/)** | Video hosting, management, collaboration, live streaming, video marketing, and VOD platform. | Starts at $12/month (Starter tier, billed annually) or $20/month (billed monthly) | Free forever plan with 1 GB lifetime total storage (up to 30 min recording per video); 30-day free trial for paid plans. |
| **[Vimeo Enterprise](https://vimeo.com/enterprise)** | Enterprise video platform providing secure hosting, corporate communications, SSO, live events, and advanced analytics. | Starts at $65/seat/month (Advanced plan) / custom enterprise quotes (starts ~$7,500/year) | 30-day enterprise evaluation / pilot available upon sales request. |
| **[Wistia](https://wistia.com/)** | Business video marketing and hosting platform with customizable players, lead capture, heatmaps, and webinars. | Starts at $19/month (Plus tier, billed annually) or $24/month (billed monthly) | Free forever plan with 25 GB storage (up to 10 videos), 200 GB monthly bandwidth, and 1 user seat. |
| **[Brightcove](https://www.brightcove.com/)** | Enterprise video cloud platform providing OTT, live broadcasting, monetization, CMS, and video delivery. | Starts at $499/month (Starter enterprise tier, billed annually) | 30-day free trial with access to upload, transcoding, player customization, and analytics. |
| **[Mux](https://www.mux.com/)** | Developer-first video infrastructure API for automated encoding, live streaming, storage, and playback analytics. | Starts at $0 pay-as-you-go ($0.005/min delivery, $0.003/min storage, $0.04/min encoding; optional $20/month starter pack) | Free forever plan with 10 stored videos and 100,000 minutes of video delivery per month (no credit card required). |
| **[Kaltura](https://corp.kaltura.com/)** | Enterprise video platform supporting video management, education, virtual classrooms, corporate communications, and OTT. | Starts at $150/month (Webinars/Events plan) or $500+/month (MediaSpace VOD portal) | 30-day free trial with $100 worth of usage credits and 10 GB hosting/bandwidth. |
| **[Cloudflare Stream](https://www.cloudflare.com/developer-platform/products/cloudflare-stream/)** | Video streaming platform with global edge encoding, storage, and player delivery on Cloudflare's network. | Starts at $5/month (includes 1,000 minutes of video storage; $1 per 1,000 minutes streamed overage) | Free Cloudflare account tier includes 30-day trial / $5 initial usage credit for Stream. |
| **[Spotlightr](https://spotlightr.com/)** | Video hosting and marketing solution with secure video encryption, CTAs, and course analytics. | Starts at $13/month (Light tier, billed annually) or $19/month (billed monthly) | 14-day free trial with 50 GB storage and 200 GB bandwidth (no credit card required). |
| **[JW Player](https://www.jwplayer.com/)** | Video platform providing HTML5 playback, multi-bitrate HLS/DASH streaming, advertising, and OTT infrastructure. | Starts at $10/month (Starter tier, includes HTML5 player and basic hosting) | 14-day free trial with 25 GB hosting and 75 GB streaming bandwidth. |
| **[Dacast](https://www.dacast.com/)** | Online video platform for live event broadcasting, video-on-demand hosting, and paywall monetization. | Starts at $37/month (Starter tier, billed annually) or $39/month (billed monthly) | 14-day free trial with 10 GB bandwidth and 2 GB storage (extendable by 7 days upon request). |
| **[Bunny Stream](https://bunny.net/stream/)** | Cost-effective video streaming CDN with built-in transcoding, player, DRM, and token security. | Starts at $1.00/month minimum account fee ($0.01/GB storage + $0.005/GB CDN delivery) | 14-day free trial with $1.00 credit (up to 1,000 GB CDN bandwidth and 10 GB storage). |
| **[Panopto](https://www.panopto.com/)** | Enterprise and higher-ed video management platform for lecture capture, training, and meeting recording. | Starts at $7,500/year (~$625/month for institutional tier); Panopto Express recorder is $0 | Free forever tier via Panopto Express (unlimited recording time, no watermark); 14-day enterprise trial on demo request. |
| **[Vidyard](https://www.vidyard.com/)** | Business video platform built for sales prospecting, video messaging, marketing automation, and video hosting. | Starts at $59/user/month (Starter tier, billed annually) or $89/user/month (billed monthly) | Free forever plan with up to 25 video uploads and 30-minute recording duration per video. |
| **[SproutVideo](https://sproutvideo.com/)** | Privacy-focused business video hosting with granular access controls, lead capture, and live streaming. | Starts at $10/month (Seed tier, includes 100 GB storage and 100 GB bandwidth) | 30-day free trial with full feature access and no credit card required. |
| **[Uscreen](https://www.uscreen.tv/)** | All-in-one OTT video monetization and membership platform for subscription video services. | Starts at $49/month (Growth tier, billed annually) or $99/month + $1.99/paid member/month | 14-day free trial with complete platform, billing setup, and custom web player access. |
| **[Wowza Video](https://www.wowza.com/products/video)** | Cloud video streaming infrastructure platform for ultra-low latency live streaming and VOD transcoding. | Starts at $25/month (Pay-As-You-Go: $2.50/stream hr, $0.10/viewer hr) or $130/month (Annual bundle) | 30-day free trial with 20 streaming hours, 200 GB bandwidth, and full API access. |
| **[IBM Video Streaming](https://www.ibm.com/products/video-streaming)** | Cloud enterprise video streaming platform for corporate town halls, marketing webcasts, and internal video. | Starts at $137/month (Silver tier, 100 viewer hours, 5 channels, 1 TB storage) | 30-day free trial with 100 viewer hours, 1 broadcast channel, and 1 TB storage. |
| **[Dailymotion Pro](https://www.dailymotion.com/)** | Professional video hosting, ad-monetization, custom HTML5 player, and OTT distribution platform. | Starts at $49/month (Starter tier) | Free forever consumer account (unlimited uploads, ad-supported); 14-day free trial for Dailymotion Pro. |
| **[StreamShark](https://streamshark.io/)** | Live stream management and event broadcasting platform with enterprise security and multi-CDN delivery. | Starts at $159/month (Standard tier, billed annually) or $199/month (billed monthly) | 7-day free trial with 50 GB data transfer and 5 hours of live streaming. |
| **[Muvi](https://www.muvi.com/)** | End-to-end OTT platform to launch white-label VOD, live streaming websites, and multi-device TV apps. | Starts at $199/month (Muvi Playout) or $399/month (Muvi One Standard) | 14-day free trial with complete access to white-label CMS, video player, and DRM controls. |
| **[VPlayed](https://www.vplayed.com/)** | Self-hosted OTT streaming solution for web, mobile, and smart TVs with lifetime licensing. | Starts at ~$30,000 one-time license fee (custom-built, zero recurring monthly platform fees) | 14-day interactive sandbox demo and proof-of-concept environment upon request. |
| **[Cloudinary Video](https://cloudinary.com/products/video)** | Media management platform for video uploading, AI transformations, transcoding, and global CDN delivery. | Starts at $89/month (Plus tier) | Free forever plan with 25 credits/month (~25 GB storage or 25 GB bandwidth or 25,000 video transformations). |
| **[ImageKit Video](https://imagekit.io/)** | Real-time video optimization, adaptive bitrate (HLS/DASH) generation, and global CDN delivery network. | Starts at $9/month (Lite tier, includes 40 GB bandwidth) | Free forever plan with 20 GB bandwidth/month, 3 GB media storage, and 2 user seats. |
| **[AWS Elemental MediaLive](https://aws.amazon.com/medialive/)** | Broadcast-grade live video processing and multi-bitrate packaging cloud infrastructure. | Starts at $0.015/minute ($0.90/hour for single-pipeline AVC inputs) / $0.0075/min for MediaConvert | 12-month AWS Free Tier includes 100 GB/month outbound bandwidth + $200 free trial credits for new accounts. |
| **[Amazon IVS](https://aws.amazon.com/ivs/)** | Managed low-latency and real-time live streaming infrastructure designed for interactive audience apps. | Starts at $0.015/hour (Basic input) + $0.075/hour per viewer (SD output) | 12-month Free Tier with 5 hours of Basic video input and 100 hours of SD video output per month. |
| **[Google Cloud Media CDN](https://cloud.google.com/media-cdn)** | Planetary-scale media and video caching infrastructure built on Google's YouTube network backbone. | Starts at $0.04/GB egress (North America/Europe) + $0.0075 per 10,000 HTTP/HTTPS requests | 90-day Google Cloud trial with $300 in credits applicable across all Media CDN workloads. |
| **[Azure Media Services (Legacy / Ecosystem)](https://azure.microsoft.com/)** | Cloud video workflow services (migrated to partner ecosystems like MediaKind & Bitmovin). | Partner offerings start from $0.01/GB bandwidth & $0.015/min encoding | 30-day Azure Free Trial with $200 credits for deploying media partner infrastructure. |

## Open-Source GitHub Projects

> **Important:** The open-source video ecosystem is much broader than complete Vimeo/Brightcove-style platforms. Projects below include complete video-hosting platforms as well as media servers, transcoding engines, video players, WebRTC infrastructure, streaming protocols, OTT systems, and storage/delivery components.

### Complete Open-Source Video Hosting Platforms

- **[PeerTube](https://github.com/Chocobozzz/PeerTube)**  
  Federated open-source video hosting platform supporting video publishing, streaming, federation, communities, moderation, and ActivityPub interoperability.

- **[Owncast](https://github.com/owncast/owncast)**  
  Open-source self-hosted live video streaming platform with an integrated web player, chat, and decentralized/self-hosted deployment model.

- **[Jellyfin](https://github.com/jellyfin/jellyfin)**  
  Open-source media server for managing and streaming personal and organizational video, audio, and media libraries.

- **[Emby Server](https://github.com/MediaBrowser/Emby)**  
  Media-server software for organizing and streaming personal media collections across devices.

- **[Kodi](https://github.com/xbmc/xbmc)**  
  Open-source media-center platform supporting local and network-based video and audio playback.

- **[MediaCMS](https://github.com/mediacms-io/mediacms)**  
  Open-source video and media management platform designed for hosting, organizing, publishing, and streaming video.

- **[MediaGoblin](https://notabug.org/mediagoblin/mediagoblin)**  
  Federated open-source media publishing platform supporting video and other media types.

- **[ClipBucket](https://github.com/arslancb/clipbucket)**  
  Open-source video-sharing and video-hosting platform with upload, management, playback, and publishing functionality.

- **[MediaDrop](https://github.com/mediadrop/mediadrop)**  
  Open-source media publishing and video management platform.

- **[Video.js HTTP Streaming](https://github.com/videojs/http-streaming)**  
  Open-source HTTP streaming implementation supporting HLS and DASH playback within Video.js.

### Media Servers & Streaming Engines

- **[MediaMTX](https://github.com/bluenviron/mediamtx)**  
  Open-source real-time media server supporting RTSP, RTMP, HLS, WebRTC, SRT, and other media protocols.

- **[SRS](https://github.com/ossrs/srs)**  
  High-performance open-source real-time video streaming server supporting RTMP, WebRTC, HLS, HTTP-FLV, SRT, and other protocols.

- **[OvenMediaEngine](https://github.com/AirenSoft/OvenMediaEngine)**  
  Open-source streaming server focused on ultra-low-latency live streaming using WebRTC, LL-HLS, and related technologies.

- **[Ant Media Server](https://github.com/ant-media/Ant-Media-Server)**  
  Open-source live-streaming and WebRTC server supporting ultra-low-latency streaming, HLS, RTMP, and WebRTC.

- **[MistServer](https://github.com/DDVTECH/mistserver)**  
  Open-source media streaming server supporting multiple streaming protocols and live/on-demand video workflows.

- **[Janus Gateway](https://github.com/meetecho/janus-gateway)**  
  Open-source WebRTC server/gateway designed for building real-time video and audio applications.

- **[mediasoup](https://github.com/versatica/mediasoup)**  
  Open-source WebRTC SFU framework for building scalable real-time audio/video applications.

- **[Pion WebRTC](https://github.com/pion/webrtc)**  
  Pure Go implementation of WebRTC useful for building custom real-time media infrastructure.

- **[LiveKit](https://github.com/livekit/livekit)**  
  Open-source WebRTC infrastructure for real-time audio/video applications, meetings, broadcasting, and interactive streaming.

- **[Jitsi Videobridge](https://github.com/jitsi/jitsi-videobridge)**  
  Open-source WebRTC SFU for scalable real-time video conferencing and media routing.

### Live Streaming Platforms

- **[Owncast](https://github.com/owncast/owncast)**  
  Self-hosted live video streaming platform with web playback and chat.

- **[SRS](https://github.com/ossrs/srs)**  
  Streaming server for building live-video infrastructure.

- **[OvenMediaEngine](https://github.com/AirenSoft/OvenMediaEngine)**  
  Ultra-low-latency live-streaming engine.

- **[Ant Media Server](https://github.com/ant-media/Ant-Media-Server)**  
  Live streaming and WebRTC infrastructure.

- **[MediaMTX](https://github.com/bluenviron/mediamtx)**  
  Lightweight multi-protocol real-time media server.

- **[Restreamer](https://github.com/datarhei/restreamer)**  
  Open-source live-video streaming and restreaming platform with browser-based management.

- **[Nginx-RTMP](https://github.com/arut/nginx-rtmp-module)**  
  Widely used open-source RTMP module for Nginx, enabling RTMP ingest, HLS generation, and basic streaming workflows.

### Video Transcoding & Media Processing

- **[FFmpeg](https://github.com/FFmpeg/FFmpeg)**  
  The foundational open-source multimedia framework for encoding, decoding, transcoding, muxing, demuxing, filtering, recording, and streaming video and audio.

- **[GStreamer](https://github.com/GStreamer/gstreamer)**  
  Open-source multimedia framework for building complex video processing, streaming, encoding, decoding, and media pipelines.

- **[HandBrake](https://github.com/HandBrake/HandBrake)**  
  Open-source video transcoder useful for converting and compressing video files.

- **[Shaka Packager](https://github.com/shaka-project/shaka-packager)**  
  Open-source media packaging tool for preparing video for DASH, HLS, encryption, and adaptive streaming.

- **[Bento4](https://github.com/axiomatic-systems/Bento4)**  
  Open-source MP4 and MPEG-DASH/HLS multimedia toolkit for packaging and processing adaptive-streaming content.

- **[GPAC](https://github.com/gpac/gpac)**  
  Open-source multimedia framework supporting MP4, DASH, media processing, packaging, and streaming.

- **[OpenH264](https://github.com/cisco/openh264)**  
  Open-source H.264 codec implementation useful for video encoding and decoding.

- **[x264](https://code.videolan.org/videolan/x264)**  
  Open-source H.264/AVC video encoder widely used in video transcoding pipelines.

- **[x265](https://bitbucket.org/multicoreware/x265_git)**  
  Open-source H.265/HEVC encoder for high-efficiency video compression.

- **[SVT-AV1](https://gitlab.com/AOMediaCodec/SVT-AV1)**  
  Open-source AV1 encoder optimized for scalable high-performance video encoding.

- **[rav1e](https://github.com/xiph/rav1e)**  
  Open-source AV1 video encoder written in Rust.

### Video Players

- **[Video.js](https://github.com/videojs/video.js)**  
  Open-source HTML5 video player framework supporting adaptive streaming, plugins, captions, and customizable playback experiences.

- **[Shaka Player](https://github.com/shaka-project/shaka-player)**  
  Open-source JavaScript player for adaptive media formats including DASH and HLS.

- **[Plyr](https://github.com/sampotts/plyr)**  
  Simple, customizable open-source HTML5 video and audio player.

- **[Clappr](https://github.com/clappr/clappr)**  
  Extensible open-source media player framework.

- **[MediaElement](https://github.com/johndyer/mediaelement)**  
  HTML5 media player supporting video and audio playback with a consistent interface.

- **[hls.js](https://github.com/video-dev/hls.js)**  
  JavaScript implementation of an HLS client for browsers using Media Source Extensions.

- **[dash.js](https://github.com/Dash-Industry-Forum/dash.js)**  
  Open-source reference client for MPEG-DASH adaptive streaming.

- **[THEOplayer Open Source Components](https://github.com/THEOplayer)**  
  Open-source ecosystem components around web video playback and media workflows.

### WebRTC Infrastructure

- **[Pion WebRTC](https://github.com/pion/webrtc)**  
  Go implementation of WebRTC for custom real-time media applications.

- **[Janus Gateway](https://github.com/meetecho/janus-gateway)**  
  General-purpose WebRTC gateway.

- **[mediasoup](https://github.com/versatica/mediasoup)**  
  Lightweight WebRTC SFU framework.

- **[LiveKit](https://github.com/livekit/livekit)**  
  WebRTC infrastructure for real-time media and interactive streaming.

- **[Jitsi](https://github.com/jitsi/jitsi-meet)**  
  Open-source video-conferencing platform with real-time video infrastructure.

- **[Jitsi Videobridge](https://github.com/jitsi/jitsi-videobridge)**  
  Scalable WebRTC media router.

- **[ion-sfu](https://github.com/pion/ion-sfu)**  
  Open-source WebRTC SFU built using Pion.

- **[Galene](https://github.com/jech/galene)**  
  Open-source videoconferencing server supporting WebRTC.

### OTT & Video Applications

- **[Jellyfin](https://github.com/jellyfin/jellyfin)**  
  Self-hosted media streaming platform.

- **[Kodi](https://github.com/xbmc/xbmc)**  
  Open-source media center.

- **[PeerTube](https://github.com/Chocobozzz/PeerTube)**  
  Federated video publishing and streaming.

- **[Owncast](https://github.com/owncast/owncast)**  
  Self-hosted live streaming.

- **[MediaCMS](https://github.com/mediacms-io/mediacms)**  
  Open-source video management and publishing.

- **[Emby](https://github.com/MediaBrowser/Emby)**  
  Media-server platform for streaming personal content.

- **[MediaGoblin](https://notabug.org/mediagoblin/mediagoblin)**  
  Federated media publishing platform.

### Storage & Video Delivery Infrastructure

- **[MinIO](https://github.com/minio/minio)**  
  S3-compatible object storage suitable for storing video originals, renditions, thumbnails, and media assets.

- **[SeaweedFS](https://github.com/seaweedfs/seaweedfs)**  
  Distributed storage system suitable for large media datasets and object/file storage.

- **[Ceph](https://github.com/ceph/ceph)**  
  Distributed storage platform providing object, block, and file storage for large-scale media infrastructure.

- **[OpenResty](https://github.com/openresty/openresty)**  
  Nginx-based web platform useful for building custom media delivery and API infrastructure.

- **[Nginx](https://github.com/nginx/nginx)**  
  High-performance web server and reverse proxy useful for media delivery, caching, and streaming infrastructure.

- **[Varnish Cache](https://github.com/varnishcache/varnish-cache)**  
  Open-source HTTP accelerator useful for caching video manifests, segments, and other media assets.

### Video Management & Publishing

- **[PeerTube](https://github.com/Chocobozzz/PeerTube)**  
  Federated video management and publishing.

- **[MediaCMS](https://github.com/mediacms-io/mediacms)**  
  Video content management system.

- **[ClipBucket](https://github.com/arslancb/clipbucket)**  
  Video-sharing platform.

- **[MediaGoblin](https://notabug.org/mediagoblin/mediagoblin)**  
  Federated media publishing.

- **[Owncast](https://github.com/owncast/owncast)**  
  Live video management and publishing.

### Video Analytics & Observability

- **[OpenTelemetry](https://github.com/open-telemetry/opentelemetry-collector)**  
  Open-source observability framework useful for instrumenting video platforms and streaming infrastructure.

- **[Prometheus](https://github.com/prometheus/prometheus)**  
  Metrics and monitoring platform for video servers, transcoding workers, CDN infrastructure, and streaming pipelines.

- **[Grafana](https://github.com/grafana/grafana)**  
  Open-source visualization and observability platform useful for video delivery and streaming analytics.

- **[Loki](https://github.com/grafana/loki)**  
  Log aggregation system useful for analyzing streaming and media-server events.

- **[Jaeger](https://github.com/jaegertracing/jaeger)**  
  Distributed tracing platform useful for debugging video-processing and delivery pipelines.

## Additional Strong Open-Source Options

### Video Hosting Platforms

- **[PeerTube](https://github.com/Chocobozzz/PeerTube)** — Federated video hosting.
- **[Owncast](https://github.com/owncast/owncast)** — Self-hosted live streaming.
- **[MediaCMS](https://github.com/mediacms-io/mediacms)** — Video CMS.
- **[ClipBucket](https://github.com/arslancb/clipbucket)** — Video-sharing platform.
- **[Jellyfin](https://github.com/jellyfin/jellyfin)** — Media server.
- **[Emby](https://github.com/MediaBrowser/Emby)** — Media server.
- **[Kodi](https://github.com/xbmc/xbmc)** — Media center.
- **[MediaGoblin](https://notabug.org/mediagoblin/mediagoblin)** — Federated media publishing.

### Streaming Servers

- **[MediaMTX](https://github.com/bluenviron/mediamtx)** — Multi-protocol media server.
- **[SRS](https://github.com/ossrs/srs)** — High-performance streaming server.
- **[OvenMediaEngine](https://github.com/AirenSoft/OvenMediaEngine)** — Ultra-low-latency streaming.
- **[Ant Media Server](https://github.com/ant-media/Ant-Media-Server)** — WebRTC/live streaming.
- **[MistServer](https://github.com/DDVTECH/mistserver)** — Multi-protocol streaming server.
- **[Nginx-RTMP](https://github.com/arut/nginx-rtmp-module)** — RTMP/HLS infrastructure.
- **[Restreamer](https://github.com/datarhei/restreamer)** — Live-streaming management.

### Video Processing

- **[FFmpeg](https://github.com/FFmpeg/FFmpeg)** — Transcoding and media processing.
- **[GStreamer](https://github.com/GStreamer/gstreamer)** — Media pipeline framework.
- **[Shaka Packager](https://github.com/shaka-project/shaka-packager)** — Adaptive-streaming packaging.
- **[Bento4](https://github.com/axiomatic-systems/Bento4)** — MP4/DASH/HLS toolkit.
- **[GPAC](https://github.com/gpac/gpac)** — Multimedia framework.
- **[HandBrake](https://github.com/HandBrake/HandBrake)** — Video transcoding.
- **[x264](https://code.videolan.org/videolan/x264)** — H.264 encoder.
- **[x265](https://bitbucket.org/multicoreware/x265_git)** — HEVC encoder.
- **[SVT-AV1](https://gitlab.com/AOMediaCodec/SVT-AV1)** — AV1 encoder.
- **[OpenH264](https://github.com/cisco/openh264)** — H.264 codec.

### Players

- **[Video.js](https://github.com/videojs/video.js)** — Web video player.
- **[Shaka Player](https://github.com/shaka-project/shaka-player)** — DASH/HLS player.
- **[hls.js](https://github.com/video-dev/hls.js)** — HLS playback.
- **[dash.js](https://github.com/Dash-Industry-Forum/dash.js)** — MPEG-DASH playback.
- **[Plyr](https://github.com/sampotts/plyr)** — Customizable HTML5 player.
- **[Clappr](https://github.com/clappr/clappr)** — Extensible media player.

### Real-Time Video

- **[LiveKit](https://github.com/livekit/livekit)** — WebRTC infrastructure.
- **[Janus](https://github.com/meetecho/janus-gateway)** — WebRTC gateway.
- **[mediasoup](https://github.com/versatica/mediasoup)** — WebRTC SFU.
- **[Pion](https://github.com/pion/webrtc)** — WebRTC implementation.
- **[Jitsi](https://github.com/jitsi/jitsi-meet)** — Video conferencing.
- **[Jitsi Videobridge](https://github.com/jitsi/jitsi-videobridge)** — WebRTC media routing.
- **[ion-sfu](https://github.com/pion/ion-sfu)** — WebRTC SFU.
- **[Galene](https://github.com/jech/galene)** — WebRTC conferencing.

### Storage & Delivery

- **[MinIO](https://github.com/minio/minio)** — S3-compatible object storage.
- **[Ceph](https://github.com/ceph/ceph)** — Distributed object/block/file storage.
- **[SeaweedFS](https://github.com/seaweedfs/seaweedfs)** — Distributed storage.
- **[Nginx](https://github.com/nginx/nginx)** — Web server and media delivery.
- **[Varnish](https://github.com/varnishcache/varnish-cache)** — HTTP caching.

## Open-Source Video Hosting Stack

A practical open-source alternative to commercial video-hosting platforms can be assembled from specialized components:

```text
                         ┌─────────────────────────────────────────────┐
                         │                 VIDEO SOURCES                │
                         │                                             │
                         │ Cameras / Uploads / Mobile / OBS / RTMP      │
                         │ WebRTC / SRT / APIs / Existing Video Files   │
                         └──────────────────────┬──────────────────────┘
                                                │
                                                ▼
                         ┌─────────────────────────────────────────────┐
                         │             INGESTION / UPLOAD               │
                         │                                             │
                         │ MediaMTX / SRS / Nginx-RTMP / WebRTC         │
                         │ Multipart Upload / Resumable Uploads         │
                         └──────────────────────┬──────────────────────┘
                                                │
                                                ▼
                         ┌─────────────────────────────────────────────┐
                         │             OBJECT STORAGE                  │
                         │                                             │
                         │ MinIO / Ceph / SeaweedFS / S3-Compatible     │
                         │ Original Video / Renditions / Thumbnails     │
                         └──────────────────────┬──────────────────────┘
                                                │
                                                ▼
                         ┌─────────────────────────────────────────────┐
                         │            VIDEO PROCESSING                 │
                         │                                             │
                         │ FFmpeg / GStreamer / GPAC / Bento4           │
                         │ Transcoding / Thumbnailing / Metadata       │
                         └──────────────────────┬──────────────────────┘
                                                │
                         ┌──────────────────────┼──────────────────────┐
                         │                      │                      │
                         ▼                      ▼                      ▼
                ┌─────────────────┐    ┌─────────────────┐    ┌─────────────────┐
                │ HLS             │    │ MPEG-DASH       │    │ WEBRTC          │
                │                 │    │                 │    │                 │
                │ .m3u8           │    │ .mpd            │    │ Real-Time       │
                │ TS / CMAF       │    │ CMAF            │    │ Low Latency     │
                └────────┬────────┘    └────────┬────────┘    └────────┬────────┘
                         │                      │                      │
                         └──────────────────────┼──────────────────────┘
                                                │
                                                ▼
                         ┌─────────────────────────────────────────────┐
                         │               CDN / DELIVERY                 │
                         │                                             │
                         │ Nginx / Varnish / CDN / Edge Cache           │
                         │ Signed URLs / Token Authentication            │
                         └──────────────────────┬──────────────────────┘
                                                │
                                                ▼
                         ┌─────────────────────────────────────────────┐
                         │                VIDEO PLAYER                  │
                         │                                             │
                         │ Video.js / Shaka Player / hls.js / dash.js   │
                         │ Custom HTML5 / Mobile / Smart TV Players     │
                         └──────────────────────┬──────────────────────┘
                                                │
                                                ▼
                         ┌─────────────────────────────────────────────┐
                         │              VIDEO APPLICATION               │
                         │                                             │
                         │ OTT / VOD / Live / Courses / Enterprise      │
                         │ Events / Membership / Internal Video         │
                         └─────────────────────────────────────────────┘

```