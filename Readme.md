# Prelude
[ HandBrake ]( https://handbrake.fr/ ) is a very popular free & open source video conversion software. I have tested the software extensively for the best settings to produce _**lowest file size**_ keeping reasonable video quality. Here are the results.

I have got upto 97% file size reduction using the preset I have provided here.

# Reminders
- Always use the latest version of HandBrake.
- Get yourself familiarized with HandBrake before using the following settings.
- You can download these settings as a preset file from this repository. Just download 'Preset.json' from here and in HandBrake, click 'Presets > Import from file' and then select the file.
- This preset is specifically geared towards video tutorials. For other categories of videos, you must adapt this preset. Take this preset as a guideline and make your own preset.
- Some settings are not specified because of one of the following reasons,
  - default setting is suffice
  - they don't affect the end result
  - you have to use common sense
- You should test your settings before final conversion on a part of the video and see if you are satisfied with the quality.
- You can easily experiment on a video by selecting **Range** to **Seconds** and then selecting end point to 1 minute or so and by selecting Video > Optimise Video > Encoder Preset > Ultrafast. Don't forget to change them back before the final conversion.
- You can check the codec and other information of a video using [ MediaInfo. ]( https://mediaarea.net/en/MediaInfo )
- Due to high compression, conversion might take a long time. But the end result is well worth it.
- In case, the converted video can't be played, install [ K-Lite Codec Pack. ]( http://www.codecguide.com/download_k-lite_codec_pack_basic.htm )
- HandBrake is just the GUI for [ FFmpeg. ]( https://www.ffmpeg.org/ ) So, if you need more options, you can try that.
- Please star this repository and share this with your friends.
- Any type of contribution is welcome.

# Summary
- Format: MKV

## Filters
- Turn off everything.

## Video

- Resulation: Lower is better.
- Video Codec: H.265 (x265)
- Framerate (FPS): 'Same as source' or lower
  - Peak Framerate
- Quality
  - Constant Quality: 30 to 40 ( Higher value produces better compression but inferior video quality )
- Optimise Video
  - Encoder Preset: Placebo
  - Encoder Tune: PSNR

## Audio
- Codec: MP3
- Mixdown: Mono
- Samplerate: 16 ( Click the down arrow beside mixdown to see this option )
- Bitrate: 24 ( Available only after selecting Mixdown and Samplerate )
