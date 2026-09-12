# VideoOptimizer by RNPA – GPU Video Compression & Audio Extraction Tool

**Compress videos, reduce file sizes, and extract audio through a fast and intuitive FFmpeg-based interface. Built for VFX, animation, 3D, Unreal Engine, and production workflows.**

VideoOptimizer by RNPA is a free Windows application designed to simplify video compression, conversion, and audio extraction using the power of FFmpeg.

It was originally developed to solve repetitive media-processing tasks in our own production workflow. We use it internally to quickly prepare renders, previews, animation tests, and other audiovisual material for review, delivery, sharing, and storage.

VideoOptimizer combines automatic source analysis, smart presets, GPU acceleration, batch processing, HDR/SDR handling, and advanced encoding controls in a compact interface without requiring command-line knowledge.

## Overview

VideoOptimizer is built for VFX artists, video editors, 2D and 3D animators, Technical Artists, Unreal Engine artists, audiovisual technicians, and content creators who regularly need to prepare media for delivery, review, social platforms, or storage.

The application analyzes each source file and automatically adapts settings such as the encoder, bitrate limits, resolution, color depth, and dynamic range.

For projects that require more control, all essential parameters can also be adjusted manually.

The result is a compact, bilingual, production-focused tool designed to make repetitive media tasks faster and more consistent.

## Main Features

* H.264 and H.265/HEVC video compression.
* Single-file and batch processing.
* Drag-and-drop file importing.
* Automatic source-file analysis.
* Automatic selection of the best available encoder.
* NVIDIA NVENC GPU acceleration.
* AMD AMF GPU acceleration.
* Automatic CPU fallback when no compatible GPU encoder is available.
* CRF/CQ-based quality control.
* Dynamic maximum bitrate calculation based on the source.
* Aspect-ratio preservation when resizing.
* Resolution, frame rate, color depth, range, codec, and container controls.
* Full support for filenames containing spaces, accents, Unicode, and special characters.
* Detailed activity log without intrusive error pop-ups.

## Smart Presets

VideoOptimizer includes ready-to-use profiles for different workflows:

* **Auto:** automatically adapts settings to the source.
* **High Quality:** prioritizes visual fidelity.
* **Recommended:** balances quality, speed, and file size.
* **Web / Social:** optimized for online publishing.
* **Compact:** prioritizes smaller output files.

You can also configure the following settings manually:

* H.264 or H.265 codec.
* Automatic, CPU, NVIDIA, or AMD encoding.
* Resolutions from 480p to 2160p.
* Automatic or custom frame rate.
* CRF/CQ quality level.
* 8-bit or 10-bit color depth.
* Automatic, Video, or Full color range.
* MP4, MOV, or MKV output container.

## GPU and CPU Encoding

VideoOptimizer detects the encoders available on your system and selects the best compatible option.

Supported processing paths include:

* NVIDIA NVENC hardware encoding.
* AMD AMF hardware encoding.
* CPU encoding with x264 or x265.
* Automatic GPU detection with CPU fallback.
* Direct GPU decoding and encoding when the source is compatible.
* Automatic software decoding when filters or format conversions require it.

This provides faster processing on supported hardware while maintaining compatibility with systems that rely entirely on the CPU.

## Color and HDR Processing

VideoOptimizer inspects source metadata through FFprobe and builds the appropriate processing pipeline for each file.

Features include:

* Source color-range detection.
* Limited-range and full-range handling.
* HDR metadata analysis.
* HDR-to-SDR BT.709 conversion when required.
* CPU or OpenCL GPU tone mapping, depending on availability.
* HDR preservation in compatible configurations.
* Correct color primaries, transfer characteristics, matrix, and range metadata.
* Output designed for reliable editing, playback, and distribution.

## Audio Extraction and Conversion

VideoOptimizer can extract or convert audio from video and audio sources into:

* MP3
* AAC
* Opus
* OGG
* M4A
* FLAC
* WAV

Available options include:

* Automatic or manual bitrate.
* Stereo or mono output.
* 44.1, 48, and 96 kHz sample rates.
* Compressed and lossless output formats.
* Batch audio processing.

## Batch Workflow and File Organization

* Process multiple files in one operation.
* Select or exclude individual files from a batch.
* Reorder files with drag and drop.
* Use the source folder or choose a custom output directory.
* Generate output filenames automatically.
* Rename individual outputs with Custom mode.
* Prevent accidental overwriting.
* Preserve application preferences between sessions.
* Cancel an active conversion.
* View output location, filename, size, and encoding time in the activity log.

## Real-Time Progress and Notifications

* Real conversion percentage.
* Estimated time remaining.
* Combined progress for multi-file batches.
* Live progress displayed in the Windows taskbar.
* Green status when every file is completed successfully.
* Yellow status when a batch is only partially completed.
* Red status when no file can be converted.
* Visual notification when processing finishes while you are using another application.

## Supported Input Formats

VideoOptimizer supports common video and audio containers, including:

**Video:** MP4, AVI, MKV, MOV, FLV, WMV, MPEG, MPG, M4V, WebM, TS, MTS, and M2TS.

**Audio:** MP3, WAV, OGG, AAC, Opus, FLAC, and M4A.

Specific codec compatibility depends on the FFmpeg build installed or included with your setup.

## Languages

The complete application interface is available in:

* English
* Spanish

You can switch languages directly from the application, and your preference is saved automatically.

## Integrated Update System

* Automatic checks for new releases.
* Update notifications inside the application.
* Download progress display.
* Automatic installation or executable replacement.
* Dark-mode update windows.
* Direct access to the release history.

## Built for Production Workflows

VideoOptimizer was created from a real production need.

High-quality renders, animation previews, Motion Capture tests, Unreal Engine renders, and other production videos can quickly become too large for convenient sharing and review.

Often, there is no need to re-export the original project or manually configure another encoding application. You simply need a smaller, optimized version that can be quickly sent to your team, uploaded for review, or archived.

VideoOptimizer simplifies that process:

**Add files → Choose your settings → Process.**

The application handles the repetitive technical work while still providing manual control when required.

## Ideal For

* Reducing file sizes before delivery.
* Creating previews for clients or supervisors.
* Preparing media for team and production reviews.
* Compressing Unreal Engine renders.
* Preparing animation and VFX previews.
* Optimizing videos for websites and social platforms.
* Converting footage for editing and post-production.
* Processing large batches of media.
* Extracting audio for editing, animation, lipsync, reference, or analysis.
* Archiving content with reduced storage requirements.

## Designed For

VideoOptimizer by RNPA is designed for:

* VFX artists.
* Video editors.
* 2D and 3D animators.
* Technical Artists.
* Unreal Engine artists.
* Motion Designers.
* Compositing artists.
* Audiovisual technicians.
* Content creators.
* Small studios and production teams.

## Advanced Processing Without Complicated Commands

VideoOptimizer brings powerful FFmpeg functionality into an accessible interface.

Use the included presets for fast and reliable results, or manually adjust the essential parameters when your project requires greater control.

No command-line knowledge is required.

## Important Notes

* Designed for Windows.
* Encoding speed depends on your hardware, selected settings, and source material.
* Compression results vary depending on the source codec, quality, resolution, and chosen preset.
* GPU acceleration requires compatible NVIDIA or AMD hardware and drivers.
* Lossless audio formats do not restore information already lost in a compressed source.
* FFmpeg is the processing engine used by the application.

## Free for the Artist Community

VideoOptimizer by RNPA is completely free.

It was originally developed for our own production workflow and is now available for other artists, creators, and studios who may find it useful.

If VideoOptimizer saves you time, feel free to share it with other artists.

## Active Development

VideoOptimizer is actively maintained and continues to receive improvements in compatibility, performance, automation, and usability.

Using and sharing the tool directly supports its growth and helps guide the development of new features and future updates.

## Contact

**Email:** [rodrigopaz.vfx@gmail.com](mailto:rodrigopaz.vfx@gmail.com)

**Instagram:** https://www.instagram.com/rodrigo_npa/

**LinkedIn:** https://www.linkedin.com/in/rodrigo-npa

**ArtStation:** https://www.artstation.com/rodrigo_npa/store/

---

**VideoOptimizer by RNPA**

Created by Rodrigo Paz
Part of RNPA Production Tools

Keywords: VideoOptimizer, VideoOptimizer by RNPA, RNPA, RNPA Production Tools, video compressor, video compression tool, GPU video compression, NVIDIA NVENC, AMD AMF, FFmpeg GUI, FFmpeg compression tool, H.264 compressor, H.265 compressor, HEVC compression, Unreal Engine video compression, VFX tools, 3D artist tools, Technical Artist tools, batch video compressor, audio extraction, HDR to SDR, production tools.
