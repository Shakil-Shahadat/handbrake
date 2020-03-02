# Introduction
[ HandBrake ]( https://handbrake.fr/ ) is a very popular free video conversion software. I have tested the software extensively for the best settings to produce _**lowest file size**_. Here is the result.

Some reminders,
- Always use the latest version of HandBrake.
- Some settings are not specified because of one of the following reasons,
  - default setting is suffice
  - they don't affect the end result
  - you have to use common sense
- You can check the codec and other information of a video using [ MediaInfo. ]( https://mediaarea.net/en/MediaInfo )
- You can easily experiment on a video by selecting **Range** to **Seconds** and then selecting end point to 1 minute or so and by selecting Video > Optimise Video > Encoder Preset > Ultrafast.
- Any type of contribution is welcome.

## Summary
- Format: MKV

## Video
- Video Codec: H.265 (x265)
- Framerate (FPS): 'Same as source' or lower
  - Peak Framerate
- Quality
  - Constant Quality: Higher value is better
- Optimise Video
  - Encoder Preset: Placebo
  - Encoder Tune: PSNR

## Audio
- Codec: Vorbis
- Bitrate: 24
- Mixdown: Mono
- Samplerate: 16
