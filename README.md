# FFmpeg-Plus README

FFmpeg-Plus is a collection of libraries and tools to process multimedia content
such as audio, video, subtitles and related metadata.

Also bringing more codecs and other supports brought by Martin Eesmaa. :)

## Additionals added in FFmpeg-Plus

* External support of SVT encoders of HEVC and VP9
* Dolby AC-4 native experimental decoding support (patch from librempeg)
* Dolby TrueHD 7.1 surround native encoding support (patch from librempeg)
* Alpha experimental Dolby E-AC-3 Surround 7.1 encoding support (afterwards, require md71 for finalize muxing)
* Apple AAC AudioToolbox encoder support for additional Windows support
* Including external AVS3 video encoder, native QOA audio encoder, external MPEG-H encoder from Ittiam and ADPCM IMA SMJPEG native encoder
* Extra decoders included as libvvdec, libmad, Blackmagic RAW, Delta YUV, MotionCam RAW and libcelt.
* Supports experimental demuxing of State of the Art Audio Codec (SAC)

## Libraries

* `libavcodec` provides implementation of a wider range of codecs.
* `libavformat` implements streaming protocols, container formats and basic I/O access.
* `libavutil` includes hashers, decompressors and miscellaneous utility functions.
* `libavfilter` provides means to alter decoded audio and video through a directed graph of connected filters.
* `libavdevice` provides an abstraction to access capture and playback devices.
* `libswresample` implements audio mixing and resampling routines.
* `libswscale` implements color conversion and scaling routines.

## Tools

* [ffmpeg](https://ffmpeg.org/ffmpeg.html) is a command line toolbox to
  manipulate, convert and stream multimedia content.
* [ffplay](https://ffmpeg.org/ffplay.html) is a minimalistic multimedia player.
* [ffprobe](https://ffmpeg.org/ffprobe.html) is a simple analysis tool to inspect
  multimedia content.
* Additional small tools such as `aviocat`, `ismindex` and `qt-faststart`.

## Documentation

The offline documentation is available in the **doc/** directory.

The online documentation is available in the main [website](https://ffmpeg.org)
and in the [wiki](https://trac.ffmpeg.org).

### Examples

Coding examples are available in the **doc/examples** directory.

## License

FFmpeg codebase is mainly LGPL-licensed with optional components licensed under
GPL. Please refer to the LICENSE file for detailed information.

## Contributing

Patches should be submitted to the ffmpeg-devel mailing list using
`git format-patch` or `git send-email`. Github pull requests should be
avoided because they are not part of our review process and will be ignored.
