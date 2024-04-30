# @aitube/ffmpeg

*Collection of useful FFmpeg utilities for NodeJS. Used by AiTube.at*

## ATTENTION

AiTube is currently in heavy development, so this library is experimental,
and may be subject to unannounced breaking changes.

We are sorry for any inconvenience this might cause.

## Installation

To install the package, run the following command:

```bash
npm install @aitube/ffmpeg
```

## Getting Started

```typescript
import {
  getMediaInfo,
  concatenateAudio,
  concatenateVideos,
  concatenateVideosAndMergeAudio,
  concatenateVideosWithAudio,
  createVideoFromFrames,
  convertAudioToWav,
  convertMp4ToMp3,
  convertMp4ToWebm,
  addImageToVideo,
  addTextToVideo,
  createTextOverlayImage,
  getCssStyle,
  htmlToBase64Png,
  imageToVideoBase64,
  cropBase64Video,
  cropVideo,
  scaleVideo,
} from '@aitube/ffmpeg'

```

## Build Instructions

Install [Bun](https://bun.sh/)

Run the following commands:

```bash
bun install

bun run build
```

To publish:

```bash
bun run build

bun run build:declaration

bun run publish
```

## Contributing

We welcome contributions! Please feel free to submit a pull request.

## License

This package is under the MIT License. See `LICENSE` file for more details.
